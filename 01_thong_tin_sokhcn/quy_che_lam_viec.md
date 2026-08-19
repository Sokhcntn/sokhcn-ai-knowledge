Tôi đã đối chiếu lại **Quyết định số 39/QĐ-SKHCN ngày 03/7/2025** và toàn bộ Quy chế làm việc kèm theo. Quy chế xác định chế độ Thủ trưởng, trách nhiệm tập thể lãnh đạo, trách nhiệm Giám đốc/Phó Giám đốc, quan hệ với xã/phường, thời hạn 05–10 ngày làm việc, chế độ họp, xử lý văn bản đến, trình ký, thẩm quyền ký và chế độ báo cáo.     

Dưới đây là bản hoàn thiện để đặt tại:

`01_thong_tin_sokhcn/quy_che_lam_viec.md`

````md
# QUY CHẾ LÀM VIỆC
## SỞ KHOA HỌC VÀ CÔNG NGHỆ TỈNH TÂY NINH

> File: `01_thong_tin_sokhcn/quy_che_lam_viec.md`
>
> Vai trò:
> Đây là nguồn dữ liệu nghiệp vụ dùng để Trợ lý AI xác định:
> - nguyên tắc giải quyết công việc;
> - trách nhiệm của Ban Giám đốc;
> - trách nhiệm của phòng, đơn vị và cá nhân;
> - quan hệ phối hợp;
> - thời hạn xử lý;
> - chế độ hội họp, báo cáo;
> - quy trình xử lý văn bản đến;
> - quy trình trình ký;
> - thẩm quyền ký văn bản;
> - trường hợp cần báo cáo, xin ý kiến hoặc chuyển Giám đốc xem xét.
>
> Lưu ý:
> - File này là bản chuẩn hóa phục vụ AI.
> - Nguồn pháp lý trực tiếp là Quy chế làm việc ban hành kèm Quyết định số 39/QĐ-SKHCN ngày 03/7/2025.
> - Khi cần kết luận pháp lý chính thức phải đối chiếu văn bản gốc.
> - File này không thay thế `phan_cong.md`.
> - Việc xác định người ký phải kết hợp cả `phan_cong.md` và file này.

---

# I. THÔNG TIN VĂN BẢN NGUỒN

```yaml
document:
  type: "Quyết định"
  number: "39/QĐ-SKHCN"
  issued_date: "2025-07-03"
  issuing_agency: "Sở Khoa học và Công nghệ tỉnh Tây Ninh"
  title: "Về việc ban hành Quy chế làm việc của Sở Khoa học và Công nghệ tỉnh Tây Ninh"
  signer:
    role: "Giám đốc"
    name: "Huỳnh Thị Hồng Nhung"
  status: "active_unless_amended_or_replaced"
````

Quyết định:

* ban hành Quy chế làm việc của Sở KH&CN tỉnh Tây Ninh;
* giao Chánh Văn phòng phối hợp với Trưởng các phòng, đơn vị tổ chức triển khai;
* thay thế các quyết định trước đây trái với Quyết định này;
* áp dụng từ ngày ký.

---

# II. PHẠM VI ÁP DỤNG

Quy chế điều chỉnh:

* chế độ làm việc của Sở KH&CN;
* quan hệ công tác với các sở, ban, ngành tỉnh;
* quan hệ công tác với xã, phường;
* quan hệ giữa các phòng, đơn vị thuộc Sở;
* quan hệ với các tổ chức đoàn thể;
* trách nhiệm của công chức, viên chức, người lao động;
* xử lý văn bản;
* trình ký;
* báo cáo;
* tiếp công dân;
* quản lý nội bộ.

Đối tượng áp dụng gồm:

* Ban Giám đốc;
* các phòng chuyên môn;
* Văn phòng Sở;
* các đơn vị trực thuộc;
* công chức;
* viên chức;
* người lao động;
* tổ chức, công dân có quan hệ công tác với Sở.

---

# III. NGUYÊN TẮC LÀM VIỆC

## RULE-QC-001 — Chế độ Thủ trưởng

Sở KH&CN làm việc theo chế độ Thủ trưởng.

```yaml
head_of_agency:
  role: "Giám đốc Sở"
  responsibility: "Chịu trách nhiệm về toàn bộ hoạt động của Sở"
```

Giám đốc là người đứng đầu cơ quan.

---

## RULE-QC-002 — Tuân thủ pháp luật và chức năng

Mọi hoạt động phải:

* bảo đảm sự lãnh đạo của Đảng;
* tuân thủ pháp luật;
* phù hợp chức năng, nhiệm vụ được UBND tỉnh giao;
* đúng trách nhiệm;
* đúng thẩm quyền;
* đúng thứ bậc hành chính;
* có phối hợp giữa các đơn vị.

---

## RULE-QC-003 — Một việc, một đầu mối chịu trách nhiệm

Khi giao nhiệm vụ phải bảo đảm:

```yaml
lead_unit_count: 1
responsible_person_count: 1
```

Nếu công việc liên quan nhiều đơn vị:

* xác định 01 đơn vị chủ trì;
* các đơn vị khác phối hợp.

AI MUST NOT mặc định:

```yaml
lead_units:
  - unit_a
  - unit_b
```

trừ khi văn bản có thẩm quyền giao rõ đồng chủ trì.

---

## RULE-QC-004 — Không làm thay trách nhiệm của cấp dưới

Nguyên tắc:

* cấp trên không làm thay công việc thuộc trách nhiệm cấp dưới;
* cấp dưới phải chấp hành sự chỉ đạo của cấp trên;
* người đứng đầu phòng/đơn vị chịu trách nhiệm về toàn bộ nhiệm vụ của đơn vị.

---

# IV. TÁC PHONG LÀM VIỆC

Công chức, viên chức, người lao động phải:

* tuân thủ kỷ luật, kỷ cương hành chính;
* không đùn đẩy trách nhiệm;
* không né tránh công việc;
* không lợi dụng chức vụ, quyền hạn;
* chủ động xử lý nhiệm vụ;
* bảo đảm đúng trình tự, thủ tục và thời hạn;
* tăng cường phối hợp;
* tôn trọng tổ chức, cá nhân và đồng nghiệp;
* hướng dẫn đầy đủ, rõ ràng;
* mặc trang phục phù hợp;
* đeo thẻ theo quy định.

---

# V. NHỮNG NỘI DUNG PHẢI THẢO LUẬN TẬP THỂ LÃNH ĐẠO

Trước khi Giám đốc quyết định, tập thể lãnh đạo Sở phải thảo luận đối với:

1. Chiến lược.
2. Quy hoạch.
3. Kế hoạch 05 năm.
4. Kế hoạch hằng năm.
5. Chương trình công tác.
6. Chủ trương và giải pháp về tổ chức.
7. Tuyển dụng.
8. Bổ nhiệm.
9. Điều động.
10. Luân chuyển.
11. Khen thưởng.
12. Kỷ luật.
13. Phân công trách nhiệm trong Ban Giám đốc.
14. Các nội dung khác do Giám đốc quyết định cần thảo luận tập thể.

```yaml
collective_discussion_required:
  - strategy
  - planning
  - five_year_plan
  - annual_plan
  - organization
  - personnel
  - leadership_assignment
  - other_issues_decided_by_director
```

---

# VI. TRÁCH NHIỆM CỦA GIÁM ĐỐC

Giám đốc:

* chịu trách nhiệm toàn diện về hoạt động của Sở;
* tổ chức, điều hành thực hiện chức năng, nhiệm vụ của Sở;
* trực tiếp phụ trách một số lĩnh vực;
* thực hiện nhiệm vụ được Chủ tịch UBND tỉnh ủy quyền;
* phân công các Phó Giám đốc;
* phân cấp hoặc ủy quyền khi cần thiết;
* trực tiếp xử lý công việc cấp bách, quan trọng;
* xử lý công việc khi Phó Giám đốc phụ trách vắng mặt;
* quyết định khi các Phó Giám đốc có ý kiến khác nhau;
* chủ trì họp giao ban, họp lãnh đạo Sở.

## Escalation về Giám đốc

```yaml
escalate_to_director_if:
  - "urgent"
  - "important"
  - "new_issue"
  - "beyond_deputy_director_authority"
  - "deputy_directors_disagree"
  - "responsible_deputy_absent_and_work_requires_resolution"
```

---

# VII. TRÁCH NHIỆM CỦA PHÓ GIÁM ĐỐC

Phó Giám đốc:

* giúp Giám đốc thực hiện nhiệm vụ được phân công;
* trực tiếp phụ trách phòng, đơn vị hoặc lĩnh vực được giao;
* chủ động chỉ đạo, kiểm tra, đôn đốc;
* chịu trách nhiệm trước Giám đốc;
* phối hợp với các Phó Giám đốc khác khi cần thiết.

Quan hệ giữa các Phó Giám đốc là quan hệ đồng cấp.

Nếu không thống nhất:

```yaml
action: "REPORT_TO_DIRECTOR"
```

Phó Giám đốc không được tự quyết định công việc thuộc lĩnh vực Phó Giám đốc khác phụ trách, trừ khi được Giám đốc ủy quyền.

Nếu một Phó Giám đốc vắng:

```yaml
replacement:
  automatic: false
  decided_by: "Giám đốc"
```

AI không được tự chọn người thay thế.

---

# VIII. TRÁCH NHIỆM CỦA TRƯỞNG PHÒNG, ĐƠN VỊ

Trưởng phòng/đơn vị:

* chịu trách nhiệm trước Giám đốc;
* chịu trách nhiệm trước Phó Giám đốc phụ trách trực tiếp;
* chịu trách nhiệm về toàn bộ công việc của đơn vị;
* vẫn chịu trách nhiệm kể cả khi đã giao hoặc ủy quyền cho cấp phó;
* tổ chức thực hiện nhiệm vụ;
* quản lý công chức, viên chức, người lao động;
* quản lý tài sản, thiết bị;
* là đầu mối quan hệ công tác;
* lập kế hoạch công tác;
* phân công công việc;
* theo dõi, đôn đốc tiến độ;
* ứng dụng CNTT, chuyển đổi số;
* báo cáo khó khăn, vướng mắc và nhiệm vụ mới.

---

# IX. BÁO CÁO TUẦN CỦA PHÒNG, ĐƠN VỊ

Vào thứ Sáu hằng tuần:

Trưởng phòng/đơn vị báo cáo:

* nhiệm vụ trọng tâm đã thực hiện;
* nhiệm vụ đang triển khai;
* kế hoạch tuần tiếp theo.

Gửi:

1. lãnh đạo Sở phụ trách trực tiếp;
2. Văn phòng Sở.

Văn phòng tổng hợp báo cáo Ban Giám đốc vào thứ Hai tuần kế tiếp.

```yaml
weekly_report:
  unit_deadline: "Thứ Sáu hằng tuần"
  recipients:
    - "Lãnh đạo Sở phụ trách trực tiếp"
    - "Văn phòng Sở"
  office_consolidation: "Thứ Hai tuần kế tiếp"
```

---

# X. TRÁCH NHIỆM ĐẶC THÙ CỦA CHÁNH VĂN PHÒNG

Ngoài trách nhiệm chung, Chánh Văn phòng:

* cung cấp thông tin cho Giám đốc và Phó Giám đốc;
* chuẩn bị báo cáo;
* chuẩn bị thông báo kết luận giao ban;
* hướng dẫn chế độ thông tin, báo cáo;
* theo dõi, đôn đốc các phòng;
* kiểm tra việc thực hiện kết luận của Giám đốc và Phó Giám đốc;
* tổng hợp tình hình;
* đề xuất các vấn đề cần xử lý;
* báo cáo nội dung phản ánh của báo chí, dư luận xã hội.

---

# XI. TRÁCH NHIỆM CỦA CẤP PHÓ PHÒNG/ĐƠN VỊ

Cấp phó:

* giúp cấp trưởng;
* phụ trách công việc do cấp trưởng phân công;
* thay mặt cấp trưởng điều hành khi cấp trưởng vắng mặt;
* chịu trách nhiệm trước cấp trưởng và pháp luật về nhiệm vụ được giao.

---

# XII. TRÁCH NHIỆM CỦA CÔNG CHỨC, VIÊN CHỨC, NGƯỜI LAO ĐỘNG

Phải:

* tuân thủ pháp luật;
* tuân thủ quy chế cơ quan;
* xây dựng kế hoạch công tác cá nhân;
* chủ động phối hợp;
* thực hiện đúng nhiệm vụ;
* báo cáo khi phát sinh vấn đề chưa hợp lý;
* bảo đảm bí mật nhà nước;
* cập nhật công việc trên hệ thống quản lý văn bản, điều hành;
* ứng dụng CNTT, chuyển đổi số;
* thực hiện KPI theo quy định riêng;
* cập nhật chính xác thông tin cá nhân trên hệ thống quản lý cán bộ.

Nếu nhận nhiệm vụ thấy chưa hợp lý:

```yaml
action:
  - "REPORT_TO_DIRECT_MANAGER"
  - "PROPOSE_SOLUTION"
```

Nếu lãnh đạo giữ nguyên quyết định:

* vẫn phải thực hiện;
* được quyền bảo lưu ý kiến;
* có thể kiến nghị cấp có thẩm quyền theo Quy chế.

---

# XIII. QUAN HỆ VỚI CÔNG DÂN VÀ TỔ CHỨC

Các phòng, đơn vị:

* giải quyết đúng chức năng, nhiệm vụ;
* TTHC thuộc thẩm quyền Sở phải thực hiện thông qua Hệ thống thông tin giải quyết TTHC tỉnh theo quy định;
* phải giải quyết nhanh chóng, thuận tiện và đúng pháp luật.

## Hard rule

```yaml
private_home_processing:
  allowed: false
```

Công chức, viên chức, người lao động không tiếp nhận và giải quyết công việc của công dân, tổ chức tại nhà riêng.

Nếu công việc có thời hạn:

```yaml
must_meet_deadline: true
```

---

# XIV. QUAN HỆ VỚI SỞ, BAN, NGÀNH TỈNH

Khi cơ quan khác lấy ý kiến Sở:

* phải trả lời bằng văn bản;
* thực hiện trong thời hạn cơ quan chủ trì yêu cầu.

Khi được mời họp:

* phải cử đúng thành phần;
* nếu ủy quyền người khác dự thì người ủy quyền chịu trách nhiệm về ý kiến của người được ủy quyền.

```yaml
external_consultation:
  response_format: "written"
  deadline_source: "requesting_agency"
```

---

# XV. QUAN HỆ VỚI XÃ, PHƯỜNG

Đây là quy tắc deadline đặc biệt quan trọng.

Các phòng/đơn vị phải tham mưu giải quyết đề nghị của xã, phường thuộc thẩm quyền Sở.

## Trường hợp không cần lấy ý kiến cơ quan khác

```yaml
commune_response_deadline:
  external_consultation: false
  maximum: "05 ngày làm việc"
  start: "kể từ ngày nhận văn bản đề nghị"
```

## Trường hợp phải lấy ý kiến cơ quan khác

```yaml
commune_response_deadline:
  external_consultation: true
  maximum: "10 ngày làm việc"
```

Ngoại lệ:

* có quy định thời hạn khác;
* trường hợp bất khả kháng, khách quan theo nội dung Quy chế.

Sở khuyến khích:

* ứng dụng CNTT;
* chuyển đổi số;
* AI;

để rút ngắn thời gian nhưng không vượt quá thời hạn quy định.

## HARD RULE

```yaml
if:
  incoming_agency_level: "xa_phuong"
  external_consultation: false
then:
  deadline: "05_working_days"

if:
  incoming_agency_level: "xa_phuong"
  external_consultation: true
then:
  deadline: "10_working_days"
```

---

# XVI. QUAN HỆ GIỮA CÁC PHÒNG, ĐƠN VỊ

Quan hệ giữa các phòng, đơn vị là quan hệ phối hợp.

Việc phối hợp phải thông qua lãnh đạo phòng, đơn vị.

Văn phòng Sở:

* nắm tình hình chung;
* tổng hợp;
* tham mưu lãnh đạo Sở điều hành.

```yaml
internal_coordination:
  through_unit_leaders: true
  office_role:
    - monitor
    - consolidate
    - advise
```

---

# XVII. THỜI GIAN LÀM VIỆC

```yaml
working_time:
  hours_per_week: 40
  hours_per_day: 8

  morning:
    start: "07:00"
    end: "11:30"

  afternoon:
    start: "13:30"
    end: "17:00"
```

---

# XVIII. KẾ HOẠCH CÔNG TÁC

## Kế hoạch năm

Các phòng, đơn vị:

```yaml
annual_work_plan:
  submit_to: "Văn phòng Sở"
  deadline: "Trong tháng 12 của năm trước"
```

Văn phòng trình lãnh đạo Sở phê duyệt.

## Phân công công việc tại phòng

Các phòng chuyên môn phải xây dựng bảng phân công nhiệm vụ cụ thể cho công chức:

* gắn với vị trí việc làm;
* gửi Văn phòng theo dõi;
* thực hiện trong Quý I.

```yaml
individual_assignment_plan:
  deadline: "Quý I"
  recipient: "Văn phòng Sở"
```

---

# XIX. ĐI CÔNG TÁC, HỘI HỌP

Lãnh đạo Sở và lãnh đạo phòng/đơn vị phải dành thời gian đi cơ sở định kỳ để:

* kiểm tra;
* nắm tình hình;
* theo dõi chính sách;
* kịp thời đề xuất giải pháp.

Người đi công tác:

* phải báo nơi đến;
* phải báo cáo kết quả với lãnh đạo trực tiếp.

Người đi họp:

* đúng thành phần;
* đúng phân công.

---

# XX. CHÀO CỜ, NGÀY PHÁP LUẬT VÀ GIAO BAN

## Chào cờ

```yaml
flag_ceremony:
  schedule: "Thứ Hai hằng tuần"
  time: "07:00"
```

Đơn vị trực thuộc có trụ sở riêng tổ chức tại đơn vị.

Riêng thứ Hai tuần đầu tháng:

* chào cờ tại Sở.

---

## Ngày pháp luật

```yaml
law_day:
  schedule: "Thứ Hai tuần cuối tháng"
  notice_by: "Văn phòng Sở"
```

---

## Họp giao ban tuần

Sáng thứ Hai:

* các Phó Giám đốc có thể họp các phòng/đơn vị mình phụ trách;
* thời gian do Phó Giám đốc quyết định.

Văn phòng:

* tổng hợp báo cáo tuần;
* báo cáo Ban Giám đốc.

---

## Họp giao ban tháng

```yaml
monthly_briefing:
  schedule: "Sáng thứ Hai tuần đầu tiên của tháng"
  chair: "Giám đốc"
```

Thành phần:

* Ban Giám đốc;
* Trưởng, Phó các phòng;
* lãnh đạo đơn vị trực thuộc;
* thành phần khác do người chủ trì quyết định.

Nếu Giám đốc vắng:

```yaml
chair_replacement:
  automatic: false
  method: "Giám đốc ủy quyền 01 Phó Giám đốc"
```

---

# XXI. TIẾP CÔNG DÂN, KHIẾU NẠI, TỐ CÁO

Giám đốc:

* tổ chức tiếp công dân;
* giải quyết khiếu nại, tố cáo thuộc thẩm quyền.

Phó Giám đốc:

* tham gia tiếp công dân theo quy định.

Bộ phận tham mưu:

* phối hợp các phòng;
* hướng dẫn, trả lời;
* báo cáo Giám đốc khi vượt thẩm quyền;
* báo cáo vấn đề nhạy cảm, phức tạp.

```yaml
citizen_escalation:
  if:
    - "beyond_authority"
    - "sensitive"
    - "complex"
  then:
    report_to: "Giám đốc"
```

---

# XXII. NGHỈ PHÉP

## Trưởng, Phó trưởng phòng/đơn vị

```yaml
leave_approval:
  subject: "Trưởng/Phó trưởng phòng, đơn vị"
  approver: "Ban Giám đốc"
```

## Công chức thuộc phòng của Sở

### Nghỉ 01–02 ngày

```yaml
leave:
  duration: "01-02 ngày"
  approver: "Trưởng phòng"
```

Đồng thời thực hiện theo quy định liên quan tại khoản 3 Điều 29.

### Nghỉ từ 03 ngày trở lên

```yaml
leave:
  duration: ">= 03 ngày"
  approver: "Ban Giám đốc"
```

## Hai đơn vị trực thuộc

Công chức, viên chức, người lao động tại hai đơn vị trực thuộc:

```yaml
leave_policy_source: "Quy chế của đơn vị"
```

---

# XXIII. XỬ LÝ VĂN BẢN ĐẾN

## 1. Văn bản giấy

Văn thư:

1. vào sổ theo dõi;
2. đóng dấu đến;
3. ghi số đến;
4. ghi ngày đến;
5. scan;
6. chuyển lãnh đạo Sở xử lý.

```yaml
paper_incoming_document:
  workflow:
    - register
    - stamp_received
    - assign_received_number
    - record_received_date
    - scan
    - forward_to_department_leadership
```

---

## 2. Văn bản điện tử

Văn thư:

1. phân loại;
2. vào sổ;
3. lấy số đến;
4. chuyển lãnh đạo Sở xử lý.

```yaml
electronic_incoming_document:
  workflow:
    - classify
    - register
    - assign_received_number
    - forward_to_department_leadership
```

---

## 3. Văn bản mang tính thông tin

Chánh Văn phòng được ủy quyền xử lý ban đầu các văn bản đến mang tính chất thông tin cho các phòng, đơn vị.

```yaml
informational_incoming_document:
  initial_handler: "Chánh Văn phòng"
```

Đây không phải quyền xử lý chung mọi văn bản đến.

---

## 4. Trách nhiệm phòng, đơn vị

Lãnh đạo phòng/đơn vị:

* xử lý văn bản trên hệ thống quản lý văn bản và điều hành;
* theo dõi tiến độ;
* đôn đốc nhiệm vụ;
* bảo đảm thời gian yêu cầu.

---

## 5. Văn bản mật

```yaml
classified_document:
  separate_register: true
  governed_by: "Quy định pháp luật về bảo mật"
```

AI không được tự xử lý tài liệu mật ngoài quy trình phù hợp.

---

# XXIV. LƯU TRỮ VÀ BẢO MẬT

Văn thư, tổ chức và cá nhân phải:

* thực hiện chế độ lưu trữ;
* bảo mật tài liệu;
* tuân thủ quy định của Chính phủ;
* tuân thủ hướng dẫn nghiệp vụ của cơ quan có thẩm quyền.

---

# XXV. CHẾ ĐỘ TRÌNH KÝ

## HARD RULE

Tất cả văn bản trình lãnh đạo Sở ký phải chuyển qua hệ thống phần mềm quản lý văn bản.

```yaml
signature_submission:
  system_required: true
  system: "Phần mềm quản lý văn bản"
```

Văn bản đi có yêu cầu phản hồi văn bản đến phải:

* kết nối;
* liên thông;

với văn bản đến trên hệ thống.

---

## Trách nhiệm lãnh đạo phòng/đơn vị

Lãnh đạo phòng/đơn vị chịu trách nhiệm về:

* nội dung;
* thể thức văn bản.

Phải ký tắt tại dấu:

```text
./.
```

trên văn bản theo Quy chế.

```yaml
unit_head_precheck:
  content: true
  format: true
  initials_required: true
```

---

# XXVI. THẨM QUYỀN KÝ CỦA GIÁM ĐỐC

Giám đốc ký:

## 1. Tất cả văn bản trình UBND tỉnh

```yaml
if:
  submission_to: "UBND tỉnh"
then:
  signer_role: "Giám đốc"
```

Đây là HARD RULE.

AI MUST NOT đề xuất Phó Giám đốc ký văn bản trình UBND tỉnh chỉ vì Phó Giám đốc phụ trách chuyên môn.

---

## 2. Văn bản thuộc lĩnh vực Giám đốc trực tiếp phụ trách

```yaml
signer_role: "Giám đốc"
```

---

## 3. Văn bản thuộc lĩnh vực Phó Giám đốc phụ trách nhưng Phó Giám đốc vắng hoặc do yêu cầu công tác

Giám đốc có thể ký.

---

## 4. Các văn bản khác

Theo Quy chế, Giám đốc có thẩm quyền ký các văn bản khác thuộc trách nhiệm của mình.

---

# XXVII. THẨM QUYỀN KÝ CỦA PHÓ GIÁM ĐỐC

Phó Giám đốc ký thay Giám đốc:

## Trường hợp 1

Văn bản thuộc lĩnh vực được giao phụ trách.

```yaml
signing:
  form: "KT. GIÁM ĐỐC"
  signer_role: "PHÓ GIÁM ĐỐC"
```

Phải tra:

`01_thong_tin_sokhcn/phan_cong.md`

để biết Phó Giám đốc nào phụ trách.

---

## Trường hợp 2

Khi Giám đốc vắng và một Phó Giám đốc được ủy quyền điều hành.

Phó Giám đốc đó được ký văn bản thuộc thẩm quyền Giám đốc trong phạm vi ủy quyền.

```yaml
director_absent:
  authorized_deputy_required: true
```

AI không được tự giả định người được ủy quyền.

---

# XXVIII. CHÁNH VĂN PHÒNG KÝ THỪA LỆNH

Chánh Văn phòng được Giám đốc ủy quyền ký thừa lệnh một số văn bản.

Hình thức:

```text
TL. GIÁM ĐỐC
CHÁNH VĂN PHÒNG
```

Nhóm văn bản gồm:

1. Giấy mời thông thường.
2. Truyền đạt ý kiến chỉ đạo của lãnh đạo Sở.
3. Thông báo các phòng/đơn vị thực hiện một số nhiệm vụ nội bộ.
4. Sao y văn bản của Sở.
5. Thông báo chức danh, chức vụ:

   * Ban Giám đốc;
   * Trưởng phòng;
   * Phó trưởng phòng;
   * đơn vị thuộc Sở.
6. Giấy điều xe.
7. Giấy đi đường.
8. Giấy nghỉ phép công chức, viên chức từ 01–02 ngày, trừ Trưởng phòng và Phó trưởng phòng.

## HARD RULE

```yaml
chief_of_office_signing:
  form: "TL. GIÁM ĐỐC"
  scope: "LIMITED"
  universal_authority: false
```

Không được mở rộng thẩm quyền ký thừa lệnh sang các văn bản khác nếu không có căn cứ.

---

# XXIX. LÃNH ĐẠO ĐƠN VỊ TRỰC THUỘC

Lãnh đạo các đơn vị thuộc Sở ký văn bản thuộc:

* chức năng;
* nhiệm vụ;
* quyền hạn;

được giao cho đơn vị.

```yaml
subordinate_unit_signing:
  allowed_within_assigned_authority: true
```

---

# XXX. LOGIC XÁC ĐỊNH NGƯỜI KÝ CHO AI

AI phải thực hiện:

```text
LOẠI VĂN BẢN
      ↓
ĐƠN VỊ CHỦ TRÌ
      ↓
phan_cong.md
      ↓
LÃNH ĐẠO PHỤ TRÁCH
      ↓
KIỂM TRA NGƯỜI NHẬN
      ↓
CÓ TRÌNH UBND TỈNH KHÔNG?
      ↓
KIỂM TRA QUY CHẾ
      ↓
KIỂM TRA ỦY QUYỀN
      ↓
ĐỀ XUẤT NGƯỜI KÝ
```

Không được làm ngược:

```text
TỪ TÊN PHÓ GIÁM ĐỐC
→ SUY RA NGƯỜI KÝ
```

---

# XXXI. SIGNING DECISION TREE

```yaml
signing_rules:

  - condition:
      submission_to_ubnd_province: true
    result:
      signer: "GIAM_DOC"

  - condition:
      field_directly_managed_by_director: true
    result:
      signer: "GIAM_DOC"

  - condition:
      within_deputy_assigned_field: true
      mandatory_director_signature: false
    result:
      signer: "PHO_GIAM_DOC"
      form: "KT. GIÁM ĐỐC"

  - condition:
      director_absent: true
      explicit_authorization_exists: true
    result:
      signer: "AUTHORIZED_PHO_GIAM_DOC"

  - condition:
      document_in_chief_office_authorized_list: true
    result:
      signer: "CHANH_VAN_PHONG"
      form: "TL. GIÁM ĐỐC"

  - condition:
      insufficient_basis: true
    result:
      status: "CAN_KIEM_TRA_THEM"
```

---

# XXXII. CHẾ ĐỘ BÁO CÁO

Các phòng, đơn vị phải báo cáo:

* tình hình thực hiện kế hoạch;
* nhiệm vụ chuyên môn;
* nhiệm vụ lãnh đạo giao.

Báo cáo phải có:

* phân tích;
* nhận xét;
* đánh giá;
* kết quả đã làm;
* việc chưa làm được;
* nguyên nhân;
* đề xuất giải pháp.

```yaml
report_content_required:
  - analysis
  - assessment
  - completed_tasks
  - incomplete_tasks
  - causes
  - proposals
```

---

# XXXIII. BÁO CÁO ĐỊNH KỲ

Các phòng/đơn vị thực hiện:

* báo cáo định kỳ theo quy định của Bộ KH&CN;
* báo cáo tháng;
* báo cáo quý;
* báo cáo 06 tháng;
* báo cáo 09 tháng;
* báo cáo năm;
* báo cáo chuyên đề;
* báo cáo đột xuất khi được yêu cầu.

Khi repo có quy định thời gian cụ thể trong văn bản nguồn hoặc văn bản giao việc:

```yaml
deadline_priority:
  - "quy định chuyên ngành"
  - "văn bản giao nhiệm vụ"
  - "quy chế làm việc"
```

AI không được lấy deadline trong một mẫu báo cáo khác để áp dụng chung.

---

# XXXIV. KỶ LUẬT BÁO CÁO

Việc:

* gửi đúng hạn;
* chất lượng báo cáo;

được xem xét trong thi đua, khen thưởng.

Báo cáo chậm hoặc chất lượng chưa bảo đảm có thể bị xem xét trừ điểm thi đua.

---

# XXXV. PHÁT NGÔN VÀ CUNG CẤP THÔNG TIN CHO BÁO CHÍ

Việc phát ngôn và cung cấp thông tin cho cơ quan báo chí:

```yaml
media_statement:
  rule: "Thực hiện theo quy định hiện hành"
```

File này không xác định thêm người phát ngôn nếu văn bản nguồn không quy định tại đây.

---

# XXXVI. QUẢN LÝ CÔNG CHỨC, VIÊN CHỨC, NGƯỜI LAO ĐỘNG

Thực hiện theo:

* pháp luật về cán bộ, công chức;
* pháp luật về viên chức;
* các quy định liên quan.

Hoạt động nghề nghiệp ngoài giờ liên quan chức năng của Sở:

```yaml
outside_professional_activity:
  requires_head_approval: true
```

Công tác:

* quy hoạch;
* bổ nhiệm;
* bổ nhiệm lại;
* luân chuyển;
* từ chức;
* miễn nhiệm;
* đào tạo;
* bồi dưỡng;
* đánh giá;

thực hiện theo pháp luật và thẩm quyền.

---

# XXXVII. NHỮNG VIỆC CÔNG CHỨC KHÔNG ĐƯỢC LÀM

Bao gồm theo Quy chế:

* trốn tránh trách nhiệm;
* thoái thác nhiệm vụ;
* gây bè phái, mất đoàn kết;
* tự ý bỏ việc hoặc tham gia đình công;
* sử dụng tài sản nhà nước trái pháp luật;
* lợi dụng, lạm dụng nhiệm vụ, quyền hạn;
* sử dụng thông tin công vụ để vụ lợi;
* phân biệt đối xử;
* tiết lộ bí mật nhà nước;
* thực hiện các việc bị cấm theo pháp luật về phòng, chống tham nhũng và tiết kiệm, chống lãng phí.

---

# XXXVIII. LƯU Ý VỀ ĐIỀU 34

Tại Điều 34 khoản 1, văn bản nguồn ghi:

> “Những việc được quy định tại khoản 2, 3, 4 Điều 34 của Quy chế này.”

Đây là nội dung được ghi trong văn bản nguồn.

AI MUST NOT:

* tự sửa thành điều khác;
* tự suy đoán đây là lỗi đánh máy rồi thay nội dung;
* tự viện dẫn một điều khác nếu chưa có văn bản đính chính.

```yaml
source_text_issue:
  article: 34
  paragraph: 1
  status: "PRESERVE_SOURCE"
  auto_correct: false
```

Khi cần viện dẫn pháp lý chính thức:

```yaml
action: "CHECK_ORIGINAL_OR_CORRECTION_DOCUMENT"
```

---

# XXXIX. AN TOÀN VÀ VĂN HÓA CƠ QUAN

Công tác:

* bảo vệ;
* giữ gìn tài sản;
* phòng cháy, chữa cháy;

thực hiện theo nội quy của Sở.

Hằng năm thực hiện xây dựng cơ quan văn hóa theo quy định.

---

# XL. THI ĐUA, KHEN THƯỞNG VÀ KỶ LUẬT

Việc chấp hành Quy chế:

* là căn cứ quản lý;
* có liên quan đánh giá;
* thi đua;
* khen thưởng;
* xử lý vi phạm.

Lãnh đạo phòng/đơn vị cũng chịu trách nhiệm quản lý khi để người thuộc quyền vi phạm Quy chế theo mức độ và quy định.

---

# XLI. HIỆU LỰC VÀ XỬ LÝ VƯỚNG MẮC

```yaml
effective_from: "2025-07-03"
```

Trong quá trình thực hiện:

Nếu có khó khăn, vướng mắc:

```text
Công chức/viên chức/người lao động
→ Văn phòng Sở
→ đề xuất Giám đốc
→ xem xét điều chỉnh/bổ sung
```

---

# XLII. CÁC HARD RULE QUAN TRỌNG CHO AI

## HARD RULE 1 — Một việc, một chủ trì

```yaml
lead_unit: 1
```

Không tự đề xuất “đồng chủ trì”.

---

## HARD RULE 2 — Văn bản xã/phường

```yaml
no_external_consultation: "≤ 05 ngày làm việc"
external_consultation_required: "≤ 10 ngày làm việc"
```

Trừ trường hợp có quy định khác.

---

## HARD RULE 3 — Văn bản trình UBND tỉnh

```yaml
signer: "Giám đốc"
```

---

## HARD RULE 4 — Văn bản trình ký

```yaml
must_use_document_management_system: true
```

---

## HARD RULE 5 — Trưởng đơn vị chịu trách nhiệm

Kể cả đã giao cấp phó:

```yaml
unit_head_final_responsibility: true
```

---

## HARD RULE 6 — Chánh Văn phòng không có quyền TL. chung

```yaml
chief_of_office_general_signing_power: false
```

Chỉ các trường hợp được Quy chế liệt kê.

---

## HARD RULE 7 — Không tự chọn Phó Giám đốc thay thế

Nếu lãnh đạo phụ trách vắng:

```yaml
automatic_replacement: false
```

Giám đốc quyết định hoặc phải có ủy quyền.

---

# XLIII. WORKFLOW XỬ LÝ VĂN BẢN ĐẾN

```text
VĂN BẢN ĐẾN
      ↓
VĂN THƯ TIẾP NHẬN
      ↓
ĐĂNG KÝ / SỐ ĐẾN
      ↓
CHUYỂN LÃNH ĐẠO SỞ
      ↓
XÁC ĐỊNH THẨM QUYỀN
      ↓
XÁC ĐỊNH 01 ĐƠN VỊ CHỦ TRÌ
      ↓
XÁC ĐỊNH ĐƠN VỊ PHỐI HỢP
      ↓
TRA phan_cong.md
      ↓
XÁC ĐỊNH PGĐ PHỤ TRÁCH
      ↓
XÁC ĐỊNH DEADLINE
      ↓
PHÒNG/ĐƠN VỊ XỬ LÝ TRÊN HỆ THỐNG
      ↓
LÃNH ĐẠO PHÒNG KIỂM TRA
      ↓
KÝ TẮT ./.
      ↓
TRÌNH LÃNH ĐẠO
      ↓
KIỂM TRA THẨM QUYỀN KÝ
      ↓
PHÁT HÀNH
```

---

# XLIV. WORKFLOW AI KẾT HỢP 03 FILE LÕI

```text
01. chuc_nang_nhiem_vu.md
        ↓
"Có thuộc Sở không?"
"Đơn vị nào có chức năng?"

        ↓

02. phan_cong.md
        ↓
"Lãnh đạo nào phụ trách đơn vị/lĩnh vực?"

        ↓

03. quy_che_lam_viec.md
        ↓
"Thời hạn bao lâu?"
"Xử lý theo quy trình nào?"
"Ai có thẩm quyền ký?"
```

---

# XLV. OUTPUT NỘI BỘ KHUYẾN NGHỊ

```yaml
work_rule_analysis:

  lead_unit:
    id: ""
    name: ""

  responsible_leader:
    id: ""
    name: ""

  processing_deadline:
    value: null
    unit: "working_days"
    source: null

  external_consultation:
    required: false

  submission:
    via_document_management_system: true

  unit_head_review:
    required: true

  initials:
    required: true
    mark: "./."

  signing:
    recipient: null
    signer_role: null
    signer_name: null
    signing_form: null
    authorization_required: false
    status: "CAN_KIEM_TRA"

  escalation:
    required: false
    reason: null

  sources_checked:
    - "01_thong_tin_sokhcn/chuc_nang_nhiem_vu.md"
    - "01_thong_tin_sokhcn/phan_cong.md"
    - "01_thong_tin_sokhcn/quy_che_lam_viec.md"

  confidence: "high | medium | low"
```

---

# XLVI. STOP CONDITIONS

AI phải dừng kết luận hoặc yêu cầu kiểm tra thêm nếu:

```yaml
stop_conditions:

  - "Không xác định được đơn vị chủ trì"

  - "Không xác định được lãnh đạo phụ trách"

  - "Không đủ căn cứ xác định người ký"

  - "Giám đốc vắng nhưng chưa có thông tin người được ủy quyền"

  - "Phó Giám đốc phụ trách vắng nhưng chưa có phân công thay"

  - "Có xung đột giữa Quy chế và văn bản mới hơn"

  - "Có văn bản mới sửa đổi Quy chế nhưng chưa cập nhật nội dung"

  - "Văn bản mật chưa có quy trình xử lý phù hợp"

  - "Không đủ thông tin để tính deadline"
```

Output:

```text
Chưa đủ căn cứ để xác định chính xác quy trình hoặc thẩm quyền xử lý.
Cần kiểm tra thêm Quy chế, phân công, văn bản ủy quyền hoặc văn bản mới hơn trước khi tiếp tục.
```

---

# XLVII. AI MUST

AI phải:

1. Tra chức năng trước khi áp dụng Quy chế.
2. Xác định đúng 01 đơn vị chủ trì.
3. Tra `phan_cong.md` để xác định lãnh đạo.
4. Tra file này để xác định quy trình.
5. Kiểm tra deadline.
6. Kiểm tra thẩm quyền ký.
7. Kiểm tra người nhận văn bản.
8. Kiểm tra có trình UBND tỉnh không.
9. Kiểm tra ủy quyền nếu có.
10. Bảo đảm văn bản được trình qua hệ thống.
11. Tôn trọng trách nhiệm của Trưởng phòng/đơn vị.
12. Báo Giám đốc khi có vấn đề vượt thẩm quyền hoặc chưa thống nhất.

---

# XLVIII. AI MUST NOT

AI không được:

1. Tự gán hai đơn vị cùng chủ trì.
2. Tự chọn người ký chỉ vì người đó phụ trách lĩnh vực.
3. Đề xuất PGĐ ký văn bản trình UBND tỉnh trái với Quy chế.
4. Mặc định Chánh Văn phòng được ký TL. mọi văn bản.
5. Tự chọn Phó Giám đốc thay lãnh đạo vắng.
6. Bỏ qua hệ thống quản lý văn bản.
7. Bỏ qua bước kiểm tra của lãnh đạo phòng.
8. Bỏ qua deadline 05/10 ngày đối với xã/phường.
9. Tự sửa nội dung Điều 34 khoản 1.
10. Tự tạo quy định mà Quy chế không có.
11. Dùng mẫu văn bản để thay thế thẩm quyền ký trong Quy chế.
12. Dùng phân công địa bàn để thay thế phân công chuyên môn.

---

# XLIX. CÁC CÂU HỎI FILE NÀY PHẢI TRẢ LỜI

File này dùng để trả lời:

```text
"Công việc phải xử lý theo quy trình nào?"

"Thời hạn xử lý là bao lâu?"

"Trưởng phòng có trách nhiệm gì?"

"Phó Giám đốc có được quyết định nội dung này không?"

"Văn bản này phải trình qua hệ thống không?"

"Văn bản trình UBND tỉnh do ai ký?"

"PGĐ có thể ký thay trong trường hợp nào?"

"Chánh Văn phòng được ký TL. những văn bản nào?"

"Văn bản xã/phường phải trả lời trong bao lâu?"

"Khi có xung đột hoặc vượt thẩm quyền thì báo ai?"
```

---

# L. NGUYÊN TẮC CUỐI CÙNG

```text
CHỨC NĂNG
→ ĐƠN VỊ CHỦ TRÌ
→ LÃNH ĐẠO PHỤ TRÁCH
→ QUY TRÌNH XỬ LÝ
→ DEADLINE
→ KIỂM TRA NỘI DUNG
→ KÝ TẮT
→ THẨM QUYỀN KÝ
→ PHÁT HÀNH
```

Và:

```text
chuc_nang_nhiem_vu.md
        ↓
XÁC ĐỊNH ĐƠN VỊ

phan_cong.md
        ↓
XÁC ĐỊNH LÃNH ĐẠO

quy_che_lam_viec.md
        ↓
XÁC ĐỊNH QUY TRÌNH + DEADLINE + THẨM QUYỀN KÝ
```

Nếu chưa đủ căn cứ:

```text
KHÔNG ĐOÁN.
KHÔNG TỰ CHỌN NGƯỜI KÝ.
KHÔNG TỰ MỞ RỘNG THẨM QUYỀN.
PHẢI KIỂM TRA THÊM.
```

```

Một điểm tôi cố tình giữ nguyên trong bản này là **Điều 34 khoản 1 có dấu hiệu dẫn chiếu nội bộ chưa hợp lý**; tôi không tự sửa vì văn bản nguồn thực tế ghi như vậy. :contentReference[oaicite:5]{index=5} Ngoài ra, quy tắc quan trọng nhất để hệ thống AI không sai luồng là: **văn bản trình UBND tỉnh → Giám đốc ký; Phó Giám đốc ký thay trong lĩnh vực được phân công; Chánh Văn phòng chỉ ký thừa lệnh trong phạm vi được liệt kê**. :contentReference[oaicite:6]{index=6} :contentReference[oaicite:7]{index=7}
```
