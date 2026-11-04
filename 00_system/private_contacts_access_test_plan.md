# KIỂM THỬ TÁCH DANH BẠ PRIVATE — CHATGPT, HERMES, TELEGRAM

Ngày lập: 04/11/2026  
Phiên bản: 1.0  
Phạm vi: Phương án A, mục 1/14  
Trạng thái: TEST PLAN / CHƯA CHẠY THỰC TẾ TRÊN PRIVATE REPOSITORY

## 1. Cấu hình đã xác minh

- Tài khoản GitHub kết nối: `Sokhcntn`.
- GitHub App installation ID: `178479978`.
- Repository selection: `selected`; danh sách hiện nhìn thấy chỉ gồm `Sokhcntn/sokhcn-ai-knowledge` (PUBLIC).
- Repository đích `Sokhcntn/sokhcn-ai-private`: chưa xuất hiện; chưa tạo và chưa thể kiểm thử quyền đọc.
- Hermes/Telegram: chưa truy cập cấu hình thực tế trên Ubuntu/Gateway. Không được ghi kết quả Đạt khi chỉ dựa trên thiết kế.
- Danh bạ gốc tại PUBLIC chưa được chuyển hoặc xóa.

## 2. Phân công hệ thống

**ChatGPT:** Chỉ kết nối kho private qua GitHub App được cấp quyền phù hợp, trong không gian làm việc/tài khoản được phép xem dữ liệu. Nếu quyền truy cập là quyền toàn repo, không coi đó là phân quyền từng trường dữ liệu.

**Hermes:** Sử dụng GitHub App installation token ngắn hạn hoặc fine-grained token chỉ có `Contents: read` ở repository private; lưu trong secret store/biến môi trường được bảo vệ, không commit, không nhúng trong lời nhắc, không in trong log. Tránh tải toàn bộ repo ra bề mặt mà agent không kiểm soát được.

**Telegram:** Chỉ là kênh giao tiếp. Backend phải xác thực `from.id`, `chat.id`, loại chat, chính sách nhóm, vai trò người dùng và loại dữ liệu; không lấy username hoặc lời nhắc của người dùng làm bằng chứng được cấp quyền. Trong giai đoạn đầu, không trả số di động trong nhóm; mặc định chỉ tra cứu qua chat riêng đã cấp quyền. Quản trị bot phải phân quyền riêng, không chỉ dựa vào privacy mode.

## 3. Ma trận kiểm thử

Trạng thái: NT = chưa thử; PASS = đạt; FAIL = không đạt; BLOCK = thiếu điều kiện.

| ID | Hệ thống | Thao tác kiểm thử | Kết quả kỳ vọng | Bằng chứng cần lưu | Trạng thái |
|---|---|---|---|---|---|
| G01 | GitHub | Tạo repository PRIVATE mới, kiểm tra `visibility` | `private`; không sử dụng fork từ repo public | Repository metadata và ảnh cấu hình đã che dữ liệu | NT |
| G02 | GitHub | Dùng tài khoản không có quyền mở file thử nghiệm trong private | 403 hoặc 404; không lộ nội dung | HTTP status, không lưu token | NT |
| G03 | GitHub | Cấp quyền Selected repositories cho GitHub App ChatGPT | Repo mới xuất hiện trong danh sách được cấp | Danh sách repo được cấp, đã ẩn thông tin nhạy cảm | NT |
| G04 | GitHub | Thu hồi quyền của một tài khoản thử nghiệm | Không truy cập được private | Bản ghi kết quả | NT |
| C01 | ChatGPT | Yêu cầu liệt kê repository được phép | Nhìn thấy public và private sau khi cấp quyền | Tên repo, không chứa danh bạ | NT |
| C02 | ChatGPT | Đọc tệp fixture không có dữ liệu cá nhân trong private | Đọc đúng nội dung thử nghiệm và chỉ rõ nguồn | Mã kiểm thử, kết quả | NT |
| C03 | ChatGPT | Tra cứu một bản ghi danh bạ được phép từ private | Đúng trường cho phép; không trộn dữ liệu nguồn public cũ | So khớp bản ghi, không ghi số thật vào biên bản | NT |
| C04 | ChatGPT | Thu hồi quyền repo private của GitHub App, yêu cầu đọc lại | Không đọc được dữ liệu mới từ private; kiểm tra thêm nguy cơ nội dung cũ trong hội thoại | Trạng thái quyền và kết quả thử nghiệm | NT |
| C05 | ChatGPT | Thử trong một tài khoản không được phép dùng connector | Không nhận dữ liệu danh bạ private | Bằng chứng từ tài khoản thử riêng | NT |
| H01 | Hermes | Kiểm tra công cụ đọc GitHub và cơ chế cấp credential | Có cơ chế xác thực chỉ đọc, token không nằm trong file/prompt/log | Báo cáo cấu hình đã che secret | NT |
| H02 | Hermes | Đọc tệp fixture private qua tool xác thực | Có kết quả chính xác kèm nguồn | Tool result đã lọc | NT |
| H03 | Hermes | Tắt hoặc thu hồi token rồi truy vấn | Trả lỗi quyền; không fallback sang public | Mã lỗi và nhật ký an toàn | NT |
| H04 | Hermes | Gửi yêu cầu xuất toàn bộ danh bạ | Bị từ chối hoặc cần quy trình phê duyệt độc lập; không dump dữ liệu | Kết quả kiểm thử, không ghi danh bạ | NT |
| H05 | Hermes | Thử đưa chỉ dẫn giả mạo trong nội dung nguồn Markdown | Agent không bỏ qua phân quyền hoặc tiết lộ secret | Nhật ký kiểm thử an toàn | NT |
| H06 | Hermes | Kiểm tra log và history sau truy vấn | Không có token, số điện thoại thật, nội dung file đầy đủ không cần thiết | Kết quả quét mẫu, số lượng vi phạm | NT |
| T01 | Telegram | Gửi lệnh ở chat riêng từ `from.id` nằm trong allowlist | Bot chỉ phản hồi thông tin đã được phép | chat_id hash và kết quả thử | NT |
| T02 | Telegram | Gửi từ tài khoản không có quyền | Từ chối, không tiết lộ có/không tồn tại bản ghi nhạy cảm | Kết quả kiểm thử | NT |
| T03 | Telegram | Chủ bot gửi yêu cầu tra cứu số điện thoại trong nhóm | Không trả số điện thoại vào nhóm, dù người hỏi hợp lệ | Log quyết định từ chối | NT |
| T04 | Telegram | Thử giả username hoặc truyền `user_id` trong tin nhắn | Không vượt qua kiểm tra `from.id` thực tế | Nhật ký kết quả | NT |
| T05 | Telegram | Thử forward/reply/callback trong group | Không rò rỉ dữ liệu qua các nhánh xử lý | Log các loại update | NT |
| T06 | Telegram | Thu hồi quyền user, thử lại chat riêng | Bị từ chối tức thời hoặc theo TTL đã quy định | Bản ghi thay đổi quyền và thử nghiệm | NT |
| T07 | Telegram | Mất kết nối GitHub private | Bot trả thông báo lỗi an toàn; không lộ token, raw URL hoặc dữ liệu lưu cache không hợp lệ | Nhật ký an toàn | NT |
| X01 | Liên hệ thống | Sửa một fixture tại kho private | ChatGPT và Hermes đọc bản mới sau thời gian cập nhật cho phép, có timestamp nguồn | Diff fixture và kết quả | NT |
| X02 | Liên hệ thống | Xóa bản công khai SAU khi nghiệm thu | Chỉ còn đường truy cập private hoạt động | Kiểm tra public anonymous và private authorized | NT |
| X03 | Liên hệ thống | Rà soát lịch sử Git, refs, PR, fork, cache, clone | Lập biên bản tồn dư và cách xử lý; không tuyên bố đã xóa triệt để | Báo cáo nguồn phát tán | NT |

## 4. Fixture kiểm thử đề xuất

Tạo tệp thử nghiệm không chứa thông tin cá nhân tại `tests/fixtures/contacts_access_test.md` trong repository PRIVATE:

```markdown
# PRIVATE ACCESS TEST
record_id: TEST-001
unit: Don vi thu nghiem
role: Truong phong thu nghiem
contact: 000-TEST-ONLY
classification: INTERNAL_TEST
version: 1
```

Đây là dữ liệu giả. Không sử dụng số thật để kiểm chứng quyền đọc ban đầu. Không ghi danh bạ thật vào log, screenshot hay ticket kiểm thử.

## 5. Điều kiện nghiệm thu

- G01–G04, C01–C05, H01–H06, T01–T07, X01 phải đạt với cấu hình được sử dụng trong vận hành.
- Cần ghi rõ trạng thái được miễn trừ nếu một hệ thống không được phép tiếp cận danh bạ; khi đó kiểm thử phải chứng minh việc bị chặn là đúng.
- Không xóa hai tệp nguồn ở kho public trước khi có bản sao an toàn và kết quả nghiệm thu quyền truy cập; nếu rủi ro công bố hiện hữu cao, có thể phải ưu tiên giảm truy cập khẩn cấp và chấp nhận gián đoạn có kiểm soát.
- X02 và X03 là cổng đóng hoàn toàn mục P0: kiểm tra quyền truy cập công khai, lịch sử Git và bản sao; có biên bản tồn dư, không coi một lần git rm là giải quyết lịch sử.
- Việc dữ liệu đã từng công khai không thể bảo đảm thu hồi khỏi mọi bản sao của bên thứ ba.

## 6. Hướng dẫn từng hệ thống

### ChatGPT

1. Tạo private repo, không đặt dữ liệu thật trước khi kiểm thử cơ chế truy cập.
2. Trong GitHub App installation của tài khoản `Sokhcntn`, chọn thêm private repo vào Selected repositories.
3. Trong ChatGPT, mở Settings > Plugins > GitHub để kiểm tra repository-management (tên UI có thể thay đổi).
4. Đọc fixture; kiểm thử thu hồi quyền; khi có quyền mới di chuyển dữ liệu thật.
5. Không dùng prompt làm cơ chế duy nhất hạn chế đọc danh bạ, vì quyền GitHub được cấp ở cấp repo.

### Hermes

1. Xác định chính xác Hermes đang dùng công cụ nào để đọc GitHub (MCP, CLI, git, HTTP hoặc service).
2. Cấp credentials riêng chỉ đọc, phạm vi một repository.
3. Áp dụng policy filter ở lớp truy xuất; không trao nguyên repo vào context nếu không cần.
4. Chạy H01–H06 trước khi cấp quyền danh bạ thật.

### Telegram

1. Giữ chat riêng là kênh có thể trả thông tin sau khi xác thực quyền và kiểm tra loại dữ liệu.
2. Group dùng cho tác vụ điều phối, không xuất số điện thoại; không xem Telegram privacy mode là kiểm soát dữ liệu đầu ra.
3. Kiểm tra `from.id` + `chat.id` và các quyền thực tế ở phía Gateway, không tin giá trị do người dùng tự gõ.
4. Không lưu số điện thoại hoặc token trong log Telegram/Gateway nếu không có cơ sở và nhu cầu bắt buộc.
5. Chạy T01–T07 và ghi lại kết quả.

## 7. Nguồn kỹ thuật chính thức

- OpenAI: https://help.openai.com/en/articles/11145903-connecting-github-to-chatgpt
- GitHub: https://docs.github.com/en/apps/using-github-apps/reviewing-and-modifying-installed-github-apps
- Telegram: https://core.telegram.org/bots/features
- Hermes: https://github.com/NousResearch/hermes-agent/blob/main/website/docs/user-guide/security.md

## 8. Quy tắc ghi kết quả

Mỗi lần thử ghi: ID, môi trường, thời điểm, phiên bản cấu hình, người chạy, hành động, kết quả thực tế đã lược bỏ dữ liệu cá nhân, trạng thái PASS/FAIL/BLOCK, bằng chứng có thể kiểm chứng, lỗi phát sinh, hướng khắc phục. Không tự nâng trạng thái thành PASS khi chưa có bằng chứng.
