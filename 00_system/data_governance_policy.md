# CHÍNH SÁCH PHÂN LOẠI VÀ CÔNG BỐ DỮ LIỆU KHO TRI THỨC AI

Phiên bản: 1.0  
Ngày thiết lập: 04/11/2026  
Phạm vi: repository `Sokhcntn/sokhcn-ai-knowledge` và nguồn dữ liệu đồng bộ vào trợ lý AI.

> QUY TẮC QUAN TRỌNG: Repository hiện đang PUBLIC. Không bổ sung dữ liệu cá nhân, thông tin nội bộ hoặc dữ liệu cần kiểm soát vào repository này nếu chưa có căn cứ và phê duyệt công bố. Chính sách này không có tác dụng thu hồi dữ liệu đã công khai trong lịch sử Git.

## 1. Phân loại dữ liệu

| Cấp | Nhóm dữ liệu | Quy tắc |
|---|---|---|
| PUBLIC | Văn bản, thông tin đã được cơ quan có thẩm quyền công khai hợp lệ | Được lưu tại repository công khai, kèm nguồn, ngày kiểm chứng và phạm vi sử dụng |
| INTERNAL | Danh bạ công tác không công bố chính thức, báo cáo nội bộ, bản dự thảo, phân công vận hành chưa công khai | Chỉ đưa vào kho riêng tư, phân quyền theo nhiệm vụ |
| RESTRICTED | Dữ liệu cá nhân chi tiết, hồ sơ nhạy cảm, tài liệu có phạm vi tiếp cận hạn chế | Không đưa vào GitHub công khai; chỉ xử lý trên hệ thống được phép và với quyền tối thiểu |
| SECRET | Bí mật nhà nước, thông tin xác thực (token, API key, mật khẩu), khóa riêng | Không lưu trong repository; áp dụng cơ chế lưu trữ và xử lý chuyên dụng, đúng quy định |

Phân loại cuối cùng căn cứ vào nguồn gốc, mục đích, phạm vi công bố, quy định pháp luật và quyết định của đơn vị có thẩm quyền. Việc một số điện thoại được dùng cho công việc không mặc nhiên đồng nghĩa với quyền công bố công khai.

## 2. Danh sách cần rà soát ưu tiên

1. `01_thong_tin_sokhcn/Danh_ba_dien_thoai_toan_tinh_AI_RAG_FULL.md` — danh bạ cấp tỉnh, nhiều thông tin liên hệ theo tên và chức vụ.
2. `01_thong_tin_sokhcn/Danh_ba_so_dt` — danh sách công chức, viên chức và người lao động thuộc Sở.
3. Các tệp báo cáo, nhiệm vụ, quyết định và hồ sơ dữ liệu khác — kiểm tra nội dung và nguồn công bố trước khi tiếp tục cập nhật.

Trạng thái của các tệp trên: **PENDING_REVIEW**, không phải kết luận rằng toàn bộ nội dung đều không được công khai.

## 3. Cổng kiểm soát trước khi đưa tài liệu vào kho

Mỗi tài liệu mới phải có:
- Tên và đường dẫn nguồn gốc.
- Đơn vị quản lý hoặc đầu mối xác minh.
- Cấp phân loại và căn cứ được phép công bố.
- Ngày ban hành, ngày cập nhật, ngày kiểm chứng; trạng thái hiệu lực nếu là văn bản quy phạm.
- Kết quả kiểm tra dữ liệu cá nhân, thông tin xác thực và tài liệu nội bộ.
- Người kiểm tra và người phê duyệt, nếu tài liệu cần kiểm soát.

Nếu thiếu căn cứ công bố: dừng đưa vào repository PUBLIC, chuyển trạng thái `NEEDS_APPROVAL`.

## 4. Xử lý dữ liệu đã đưa lên repository công khai

1. Kiểm kê chính xác các tệp và bản commit chứa thông tin cần bảo vệ.
2. Hạn chế truy cập repository hoặc chuyển dữ liệu cần kiểm soát sang kho riêng tư sau khi đánh giá tác động đến các trợ lý đang sử dụng.
3. Không coi việc xóa tệp khỏi nhánh chính là đã xóa khỏi lịch sử; đánh giá nhu cầu làm sạch lịch sử, bản fork, cache và các bản sao, với người có thẩm quyền.
4. Nếu phát hiện thông tin xác thực còn hiệu lực: thu hồi và xoay vòng khóa ngay; không chỉ xóa chuỗi ký tự khỏi file.
5. Ghi nhật ký xử lý, đầu mối phê duyệt, thời điểm khắc phục và kiểm tra lại quyền truy cập.

## 5. Nguyên tắc cho AI và agent

- Không tự xuất danh bạ cá nhân hàng loạt hoặc đồng bộ lên kênh công khai.
- Chỉ trả về thông tin phù hợp quyền truy cập của người yêu cầu.
- Không dùng Markdown/RAG để thay thế quyết định phân loại, công bố hoặc giải mật.
- Nếu chưa kiểm chứng dữ liệu nguồn, nêu trạng thái và yêu cầu xác minh.
- Không tự thực hiện thay đổi phạm vi công khai hay xóa lịch sử nếu chưa được người có thẩm quyền cho phép.

## 6. Điều kiện hoàn thành đợt rà soát P0

- Hai tệp danh bạ được phân loại, có quyết định giữ công khai, hạn chế hoặc chuyển kho riêng tư.
- Các tài liệu còn lại đã được sàng lọc theo quy trình nêu trên.
- Không còn dữ liệu cần kiểm soát có thể được truy cập công khai ngoài phạm vi được phép.
- Có biên bản kiểm tra quyền truy cập và kiểm soát đồng bộ tới các trợ lý AI.

Chủ tài liệu và ngày rà soát tiếp theo: cập nhật bởi người quản trị repository.
