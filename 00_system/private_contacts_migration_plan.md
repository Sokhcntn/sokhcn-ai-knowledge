# PHƯƠNG ÁN A — TÁCH DANH BẠ SANG KHO TRI THỨC RIÊNG TƯ

Phiên bản: 1.0 — 04/11/2026  
Trạng thái: PHƯƠNG ÁN TRIỂN KHAI; CHƯA DI CHUYỂN DỮ LIỆU; CHƯA THAY ĐỔI QUYỀN TRUY CẬP  
Repository công khai: `Sokhcntn/sokhcn-ai-knowledge`  
Repository riêng tư dự kiến: `Sokhcntn/sokhcn-ai-private` (chưa được tạo hoặc kiểm chứng)

## 1. Mục tiêu và ranh giới

- Duy trì kho công khai cho văn bản, mẫu, quy trình được phép công bố.
- Di chuyển danh bạ và tài liệu cần hạn chế truy cập sang kho riêng tư, chỉ sau khi xác minh chủ thể quản lý dữ liệu và quyền xử lý.
- Bảo toàn chức năng tra cứu của từng trợ lý được ủy quyền; không tạo đường vòng xuất dữ liệu riêng tư sang repo công khai, Telegram nhóm hoặc đường dẫn không xác thực.
- Kiểm tra lịch sử Git, fork, bản sao và các nguồn công bố khác; không tuyên bố đã thu hồi dữ liệu chỉ vì đã xóa tệp ở nhánh chính.
- Không tự động chuyển hoặc xóa dữ liệu nếu kho đích và kết nối chưa được nghiệm thu.

## 2. Phạm vi nguồn được nhận diện

1. `01_thong_tin_sokhcn/Danh_ba_dien_thoai_toan_tinh_AI_RAG_FULL.md` — danh bạ cấp tỉnh, khoảng 8.888 dòng; kiểm tra quyền công bố và mức độ cần thiết của từng trường.
2. `01_thong_tin_sokhcn/Danh_ba_so_dt` — danh bạ nhân sự Sở KH&CN, khoảng 265 dòng; kiểm tra nguồn, quyền sử dụng và cơ sở chia sẻ với trợ lý.
3. Các dữ liệu khác chỉ đưa vào phạm vi sau khi có kết quả phân loại cụ thể, không mặc định chuyển toàn bộ.

Không sao chép nội dung cá nhân hoặc số điện thoại vào tài liệu phương án này.

## 3. Kiến trúc đích

```text
PUBLIC: Sokhcntn/sokhcn-ai-knowledge
  00_system/           Chính sách và hướng dẫn vận hành được phép công bố
  01_thong_tin_sokhcn/ Chức năng, nhiệm vụ và thông tin công khai đã kiểm chứng
  02_van_ban_mau/      Mẫu nghiệp vụ có quyền công bố
  03_can_cu/           Chỉ mục và văn bản được phép công bố
  Bo_Skill_can_thiet/  Skill và quy tắc không chứa dữ liệu hạn chế

PRIVATE (DỰ KIẾN): Sokhcntn/sokhcn-ai-private
  contacts/province/   Danh bạ toàn tỉnh
  contacts/department/ Danh bạ Sở
  metadata/            Nguồn, ngày kiểm chứng, cấp quyền, người duyệt
  access/              Danh mục vai trò/nhóm được cấp quyền, không lưu token
  audit/               Nhật ký rà soát/kiểm chứng, không đưa dữ liệu cá nhân vào log
```

Kết nối AI: dùng GitHub App/connector được cấp quyền tối thiểu cho từng repository, nếu có hỗ trợ; hoặc API tra cứu riêng qua backend có xác thực và kiểm tra quyền ở phía máy chủ. Không đặt PAT, khóa, token trong file Markdown, commit, URL, prompt hoặc cấu hình repo.

**Nguyên tắc:** quyền truy cập của tài khoản AI/service account không mặc nhiên đồng nghĩa quyền được phát lại dữ liệu cho mọi người dùng trò chuyện. Cần kiểm tra danh tính/nhóm được phép ở lớp truy vấn.

## 4. Quy trình triển khai với cổng nghiệm thu

### Giai đoạn A — Kiểm kê và bảo toàn

1. Xác nhận người có thẩm quyền đối với hai danh bạ; xác minh số điện thoại công vụ nào đã được công bố chính thức, thông tin nào cần kiểm soát.
2. Lập danh mục đường dẫn, hash, ngày cập nhật và nguồn; lưu bản dự phòng an toàn ở nơi có kiểm soát.
3. Kiểm tra tất cả nhánh, tag, commit, PR, GitHub Pages, fork và bản clone liên quan; làm rõ các nguồn đồng bộ ngoài GitHub.
4. Đánh giá mức độ cần xử lý khẩn cấp; nếu phát hiện thông tin xác thực còn hiệu lực, thu hồi/đổi khóa ngay.

**Cổng A:** Phân loại và danh mục tác động được người quản trị xác nhận.

### Giai đoạn B — Kho riêng tư

1. Tạo repository PRIVATE mới, tuyệt đối không fork từ kho PUBLIC (fork có thể mang theo lịch sử dữ liệu không mong muốn).
2. Bật xác thực đa yếu tố cho tài khoản quản trị; giới hạn cộng tác viên; áp dụng quyền tối thiểu, review và kiểm soát nhánh theo khả năng gói GitHub.
3. Chép hai danh bạ qua một kênh được bảo vệ; đối chiếu số dòng/hash và tình trạng đọc được.
4. Ghi metadata nguồn, người duyệt, phân loại và thời điểm kiểm chứng; không công khai số điện thoại trong log hoặc PR.
5. Cấm sao chép ngược sang repo PUBLIC.

**Cổng B:** Hai danh bạ có mặt ở kho riêng tư, được xác minh toàn vẹn và phân quyền.

### Giai đoạn C — Bảo toàn tra cứu AI

1. Lập ma trận ứng dụng và quyền: ChatGPT GitHub connector, trợ lý báo cáo tuần, trợ lý tổng hợp, Hermes/Telegram, các ứng dụng khác.
2. Xác thực từng connector có thể đọc repo PRIVATE hay không; nếu không hỗ trợ, dùng backend tra cứu riêng có xác thực và phân quyền.
3. Test tra cứu có quyền (tìm theo tên, chức vụ, đơn vị), tra cứu không có quyền (bị chặn), tra cứu dữ liệu thiếu và truy vấn hàng loạt (hạn chế).
4. Loại bỏ đường dẫn `raw.githubusercontent.com` công khai cho dữ liệu danh bạ và các bản sao/cache RAG.
5. Kiểm soát không đưa kết quả danh bạ vào nhóm Telegram hoặc báo cáo chia sẻ ngoài phạm vi được phép.

**Cổng C:** 100% luồng tra cứu quan trọng hoạt động theo đúng phân quyền; không có đường công khai thay thế.

### Giai đoạn D — Thu hồi bản công khai và xử lý lịch sử

1. Chỉ xóa hai tệp tại repo PUBLIC sau khi B và C đạt; nếu phân loại xác định dữ liệu rủi ro cao, cân nhắc giảm truy cập ngay thay vì chờ kiểm thử.
2. Đưa chính xác hai đường dẫn vào `.gitignore`, kiểm tra file đã được bỏ tracking.
3. Đánh giá và phê duyệt có nên viết lại lịch sử bằng `git-filter-repo --sensitive-data-removal`; thao tác rewrite có thể phá vỡ SHA, PR và clone, cần kế hoạch rollback và thông báo cộng tác viên.
4. Kiểm tra refs cũ, fork, clone, PR/cached views. Phối hợp GitHub Support nếu đáp ứng điều kiện theo tài liệu chính thức.
5. Nếu có bản sao bên ngoài quyền quản lý, ghi rõ phần dư rủi ro; không xác nhận đã xóa triệt để.

**Cổng D:** Kiểm tra repo public trên trình duyệt không đăng nhập; xác nhận bản hiện hành không còn tệp cần kiểm soát; lịch sử và bản sao được xử lý đến phạm vi có thể, ghi rõ tồn dư.

### Giai đoạn E — Chống tái diễn

1. Thêm kiểm tra PR/commit về danh bạ, chuỗi bí mật, file nhạy cảm, đường dẫn không hợp lệ.
2. Áp dụng chính sách `00_system/data_governance_policy.md`.
3. Rà soát quyền của cộng tác viên và ứng dụng mỗi quý, sau khi có biến động nhân sự hoặc cập nhật AI connector.
4. Lưu hồ sơ nghiệm thu và đầu mối chịu trách nhiệm; theo dõi khả năng tra cứu sau chuyển đổi.

## 5. Ma trận nghiệm thu tối thiểu

| Kịch bản | Kỳ vọng |
|---|---|
| Người dùng không đăng nhập truy cập repo PUBLIC | Không đọc được hai danh bạ trong nhánh hiện hành sau chuyển đổi |
| Tài khoản không được cấp quyền truy cập repo PRIVATE | Bị từ chối truy cập |
| Trợ lý có quyền tra cứu một cán bộ theo tên/chức vụ | Trả về trường được phép, có nguồn và ngày cập nhật |
| Người dùng không được phép yêu cầu số điện thoại hoặc xuất danh bạ hàng loạt | Không trả dữ liệu |
| Hermes/Telegram qua nhóm chat | Không làm lộ dữ liệu ngoài phạm vi được phê duyệt |
| Markdown/RAG cũ có URL public hoặc nội dung cache | Không được sử dụng làm đường truy cập thay thế |
| Kiểm tra nhánh, tag, commit, fork, clone, PR | Có biên bản kết quả và tồn dư |
| Khôi phục nếu connector mới không hoạt động | Dùng bản sao an toàn; không khôi phục bản danh bạ công khai |

## 6. Quyết định và điều kiện để triển khai thật

- Người quản trị xác nhận phạm vi phân loại/nguồn gốc hợp pháp.
- Kiểm tra khả năng tạo và cấp quyền repo riêng tư cho GitHub connector, ChatGPT và Hermes.
- Chỉ thực hiện xóa nhánh công khai sau khi có đối chiếu nguồn và nghiệm thu luồng tra cứu, trừ khi buộc phải hạn chế khẩn cấp.
- Viết lại lịch sử là thao tác riêng, có phê duyệt rõ ràng, bản sao an toàn và phương án phục hồi.

## 7. Tài liệu tham khảo

- GitHub Docs — Removing sensitive data from a repository: https://docs.github.com/en/authentication/keeping-your-account-and-data-secure/removing-sensitive-data-from-a-repository
- GitHub Docs — Setting repository visibility: https://docs.github.com/en/repositories/managing-your-repositorys-settings-and-features/managing-repository-settings/setting-repository-visibility

**Trạng thái thực thi tại thời điểm tạo:** Chỉ lưu phương án này vào kho tri thức công khai, không tạo repo PRIVATE, không chép danh bạ, không xóa file hoặc viết lại lịch sử.
