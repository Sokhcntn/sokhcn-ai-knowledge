# ROUTING RULES — TRỢ LÝ AI SỞ KHOA HỌC VÀ CÔNG NGHỆ TỈNH TÂY NINH

> File: `00_system/routing_rules.md`
>
> Vai trò:
> File này quy định logic định tuyến nghiệp vụ cho Trợ lý AI của Sở Khoa học và Công nghệ tỉnh Tây Ninh.
>
> Mục tiêu:
>
> * Xác định văn bản có thuộc thẩm quyền Sở hay không.
> * Xác định lĩnh vực chính và lĩnh vực liên quan.
> * Xác định đúng 01 phòng/đơn vị chủ trì.
> * Xác định phòng/đơn vị phối hợp.
> * Xác định lãnh đạo phụ trách chuyên môn.
> * Xác định lãnh đạo theo dõi địa bàn khi có xã/phường.
> * Xác định thời hạn xử lý.
> * Hỗ trợ xác định thẩm quyền ký.
> * Hỗ trợ chọn mẫu văn bản.
>
> Nguyên tắc:
> File này là lớp logic định tuyến.
> Không thay thế các văn bản nguồn tại `01_thong_tin_sokhcn/`.

---

# I. NGUỒN DỮ LIỆU BẮT BUỘC

AI phải tra cứu các nguồn sau theo đúng mục đích:

## 1. Xác định thẩm quyền và chức năng

Nguồn:

`01_thong_tin_sokhcn/chuc_nang_nhiem_vu.md`

Dùng để xác định:

* Sở KH&CN có thẩm quyền hay không;
* lĩnh vực chuyên môn;
* phòng/đơn vị có chức năng phù hợp.

---

## 2. Xác định lãnh đạo phụ trách

Nguồn:

`01_thong_tin_sokhcn/phan_cong.md`

Dùng để xác định:

* Ban Giám đốc hiện hành;
* phòng/đơn vị do từng Phó Giám đốc phụ trách;
* lãnh đạo theo dõi địa bàn;
* các điều chỉnh phân công mới nhất.

---

## 3. Xác định quy trình, deadline, thẩm quyền ký

Nguồn:

`01_thong_tin_sokhcn/quy_che_lam_viec.md`

Dùng để xác định:

* nguyên tắc một việc - một đầu mối;
* thời hạn xử lý;
* chế độ trình ký;
* thẩm quyền ký;
* trách nhiệm của các phòng, đơn vị;
* trường hợp phải báo cáo Giám đốc.

---

## 4. Xác định căn cứ chỉ đạo

Nguồn:

`03_can_cu/`

Chỉ sử dụng khi nội dung thực sự liên quan.

---

## 5. Xác định mẫu văn bản

Nguồn:

`02_van_ban_mau/`

Chỉ sử dụng sau khi đã xác định loại văn bản cần soạn.

---

# II. NGUYÊN TẮC ĐỊNH TUYẾN CỐT LÕI

## RULE-001 — Kiểm tra thẩm quyền trước

Mọi văn bản đến phải được kiểm tra:

```yaml
tham_quyen_so: true | false | uncertain
```

Nếu:

```yaml
tham_quyen_so: false
```

AI phải dừng định tuyến nội bộ.

Không được tiếp tục:

* xác định phòng chủ trì;
* xác định lãnh đạo;
* xác định người ký;
* chọn mẫu.

---

## RULE-002 — Một việc chỉ có một đơn vị chủ trì

Mỗi nhiệm vụ phải có:

```yaml
don_vi_chu_tri: 1
don_vi_phoi_hop: 0..n
```

Không được mặc định hai đơn vị cùng chủ trì.

Chỉ sử dụng “đồng chủ trì” nếu văn bản có thẩm quyền quy định rõ.

---

## RULE-003 — Xác định theo bản chất nhiệm vụ

Không định tuyến chỉ dựa vào một từ khóa.

AI phải xác định:

* nội dung chính;
* hành động phải thực hiện;
* sản phẩm đầu ra;
* đối tượng quản lý;
* bản chất quản lý nhà nước hay thực thi kỹ thuật.

---

## RULE-004 — Phòng chuyên môn ưu tiên quản lý nhà nước

Nếu nhiệm vụ thiên về:

* tham mưu;
* chính sách;
* kế hoạch;
* hướng dẫn;
* quản lý nhà nước;
* kiểm tra;
* thẩm định;
* tổng hợp;
* báo cáo ngành;

=> ưu tiên phòng chuyên môn.

---

## RULE-005 — Trung tâm ưu tiên thực thi, kỹ thuật, dịch vụ

Nếu nhiệm vụ thiên về:

* vận hành;
* triển khai;
* hỗ trợ kỹ thuật;
* dịch vụ sự nghiệp;
* thử nghiệm;
* kiểm định;
* nghiên cứu ứng dụng;
* đào tạo;
* vận hành nền tảng;
* hỗ trợ hệ thống;

=> ưu tiên Trung tâm phù hợp.

---

# III. DANH MỤC MÃ ĐƠN VỊ

```yaml
units:

  P_CDS:
    name: "Phòng Chuyển đổi số"

  P_CN_DMST:
    name: "Phòng Công nghệ và Đổi mới sáng tạo"

  P_TDCL:
    name: "Phòng Tiêu chuẩn Đo lường Chất lượng"

  P_KH:
    name: "Phòng Khoa học"

  P_KHTC:
    name: "Phòng Kế hoạch - Tài chính"

  VAN_PHONG:
    name: "Văn phòng Sở"

  TT_CDS:
    name: "Trung tâm Chuyển đổi số"

  TT_KHCN_DMST:
    name: "Trung tâm Khoa học công nghệ và Đổi mới sáng tạo"
```

---

# IV. ĐỊNH TUYẾN PHÒNG CHUYỂN ĐỔI SỐ

```yaml
unit_id: P_CDS
unit_name: "Phòng Chuyển đổi số"
leader_id: PGD_BUI_NGUYEN_KHOI
leader_name: "Bùi Nguyên Khởi"
```

## 1. Nhóm nội dung ưu tiên

* chuyển đổi số;
* chính quyền số;
* kinh tế số;
* xã hội số;
* ứng dụng công nghệ thông tin;
* giao dịch điện tử;
* nền tảng số;
* dữ liệu số;
* kiến trúc chính quyền số;
* hệ thống thông tin ở góc độ quản lý nhà nước;
* hạ tầng thông tin truyền thông;
* kế hoạch chuyển đổi số;
* chương trình chuyển đổi số;
* chỉ số chuyển đổi số;
* DTI;
* số hóa;
* dữ liệu mở;
* tích hợp và chia sẻ dữ liệu ở góc độ quản lý.

## 2. Routing rule

```yaml
if:
  task_nature: "state_management"
  main_field:
    - "chuyen_doi_so"
    - "chinh_quyen_so"
    - "kinh_te_so"
    - "xa_hoi_so"
    - "ung_dung_cntt"
    - "giao_dich_dien_tu"
then:
  lead_unit: P_CDS
```

---

# V. ĐỊNH TUYẾN TRUNG TÂM CHUYỂN ĐỔI SỐ

```yaml
unit_id: TT_CDS
unit_name: "Trung tâm Chuyển đổi số"
leader_id: PGD_NGUYEN_TRUNG_HIEU
leader_name: "Nguyễn Trung Hiếu"
```

## 1. Nhóm nội dung ưu tiên

* vận hành hệ thống;
* hỗ trợ kỹ thuật;
* trung tâm dữ liệu;
* Data Center;
* SOC;
* IOC;
* an toàn thông tin;
* giám sát an toàn thông tin;
* ứng cứu sự cố;
* vận hành nền tảng số;
* vận hành hệ thống thông tin;
* tích hợp kỹ thuật;
* chia sẻ dữ liệu ở góc độ kỹ thuật;
* khai thác dữ liệu;
* hỗ trợ phần mềm;
* dịch vụ kỹ thuật chuyển đổi số.

## 2. Routing rule

```yaml
if:
  task_nature: "technical_execution"
  main_field:
    - "system_operation"
    - "technical_support"
    - "data_center"
    - "soc"
    - "ioc"
    - "cybersecurity_operation"
then:
  lead_unit: TT_CDS
```

---

# VI. PHÂN BIỆT P_CDS VÀ TT_CDS

## Nếu là quản lý nhà nước

```yaml
prefer: P_CDS
```

Ví dụ:

* xây dựng kế hoạch chuyển đổi số;
* tham mưu chính sách;
* hướng dẫn địa phương;
* quản lý nền tảng;
* xây dựng kiến trúc;
* báo cáo chuyển đổi số.

## Nếu là thực thi kỹ thuật

```yaml
prefer: TT_CDS
```

Ví dụ:

* vận hành hệ thống;
* xử lý lỗi kỹ thuật;
* giám sát SOC;
* hỗ trợ người dùng;
* vận hành Data Center.

---

# VII. ĐỊNH TUYẾN PHÒNG CÔNG NGHỆ VÀ ĐỔI MỚI SÁNG TẠO

```yaml
unit_id: P_CN_DMST
unit_name: "Phòng Công nghệ và Đổi mới sáng tạo"
leader_id: PGD_VO_BUU_VIET_CUONG
leader_name: "Võ Bửu Viết Cường"
```

## Nhóm nội dung ưu tiên

* phát triển công nghệ;
* đổi mới công nghệ;
* đổi mới sáng tạo;
* chuyển giao công nghệ;
* công nghệ cao;
* công nghệ chiến lược;
* thị trường khoa học và công nghệ;
* doanh nghiệp KH&CN;
* khởi nghiệp đổi mới sáng tạo;
* sở hữu trí tuệ;
* sáng chế;
* nhãn hiệu;
* chỉ dẫn địa lý;
* sáng kiến;
* bưu chính;
* viễn thông;
* tần số vô tuyến điện;
* công nghiệp CNTT;
* công nghiệp công nghệ số;
* bức xạ;
* an toàn bức xạ;
* hạt nhân.

---

# VIII. ĐỊNH TUYẾN PHÒNG KHOA HỌC

```yaml
unit_id: P_KH
unit_name: "Phòng Khoa học"
leader_id: PGD_HO_THI_DIEP_THUY
leader_name: "Hồ Thị Diệp Thúy"
```

## Nhóm nội dung ưu tiên

* đề tài khoa học;
* nhiệm vụ KH&CN;
* nghiên cứu khoa học;
* đặt hàng nhiệm vụ;
* tuyển chọn;
* giao trực tiếp;
* hội đồng khoa học;
* kiểm tra nhiệm vụ;
* đánh giá;
* nghiệm thu;
* kết quả nghiên cứu;
* ứng dụng kết quả nhiệm vụ KH&CN.

## Routing rule

```yaml
if:
  task_type: "research_task_management"
then:
  lead_unit: P_KH
```

---

# IX. ĐỊNH TUYẾN PHÒNG KẾ HOẠCH - TÀI CHÍNH

```yaml
unit_id: P_KHTC
unit_name: "Phòng Kế hoạch - Tài chính"
leader_id: PGD_HO_THI_DIEP_THUY
leader_name: "Hồ Thị Diệp Thúy"
```

## Nhóm nội dung ưu tiên

* ngân sách;
* dự toán;
* quyết toán;
* tài chính;
* kế toán;
* tài sản công;
* đầu tư;
* vốn;
* kinh phí sự nghiệp KH&CN;
* thẩm định kinh phí;
* định mức;
* đơn giá;
* cơ chế tự chủ;
* kế hoạch tài chính.

## Quy tắc giao thoa

Nếu văn bản có nội dung chuyên môn và kinh phí:

```yaml
lead_unit: "phong_chuyen_mon"
support_units:
  - P_KHTC
```

Không tự động chuyển P_KHTC thành chủ trì chỉ vì văn bản có kinh phí.

---

# X. ĐỊNH TUYẾN PHÒNG TIÊU CHUẨN ĐO LƯỜNG CHẤT LƯỢNG

```yaml
unit_id: P_TDCL
unit_name: "Phòng Tiêu chuẩn Đo lường Chất lượng"
leader_id: PGD_NGUYEN_MINH_HAI
leader_name: "Nguyễn Minh Hải"
```

## Nhóm nội dung ưu tiên

* tiêu chuẩn;
* quy chuẩn;
* TCVN;
* QCVN;
* hợp chuẩn;
* hợp quy;
* đo lường;
* phương tiện đo;
* kiểm định;
* hiệu chuẩn;
* chất lượng sản phẩm;
* chất lượng hàng hóa;
* mã số mã vạch;
* truy xuất nguồn gốc;
* TBT;
* năng suất chất lượng;
* ISO;
* Giải thưởng Chất lượng Quốc gia.

---

# XI. ĐỊNH TUYẾN VĂN PHÒNG SỞ

```yaml
unit_id: VAN_PHONG
unit_name: "Văn phòng Sở"
leader_id: PGD_NGUYEN_TRUNG_HIEU
leader_name: "Nguyễn Trung Hiếu"
```

## Nhóm nội dung ưu tiên

* tổng hợp;
* chương trình công tác;
* báo cáo chung;
* tổ chức cán bộ;
* biên chế;
* vị trí việc làm;
* thi đua;
* khen thưởng;
* cải cách hành chính;
* thủ tục hành chính;
* pháp chế;
* văn thư;
* lưu trữ;
* hành chính;
* quản trị;
* tiếp công dân;
* khiếu nại;
* tố cáo;
* phòng chống tham nhũng;
* công tác nội bộ.

## Cảnh báo

Văn phòng có trách nhiệm:

* theo dõi;
* đôn đốc;
* tổng hợp;

nhưng không thay phòng chuyên môn xử lý nội dung chuyên ngành.

---

# XII. ĐỊNH TUYẾN TRUNG TÂM KHOA HỌC CÔNG NGHỆ VÀ ĐỔI MỚI SÁNG TẠO

```yaml
unit_id: TT_KHCN_DMST
unit_name: "Trung tâm Khoa học công nghệ và Đổi mới sáng tạo"
leader_id: PGD_NGUYEN_MINH_HAI
leader_name: "Nguyễn Minh Hải"
```

## Nhóm nội dung ưu tiên

* nghiên cứu ứng dụng;
* mô hình thử nghiệm;
* sản xuất thử nghiệm;
* chuyển giao công nghệ ở góc độ triển khai;
* thông tin KH&CN;
* thống kê KH&CN;
* Techmart;
* Techconnect;
* Techfest;
* kiểm định;
* hiệu chuẩn;
* thử nghiệm;
* giám định;
* dịch vụ năng suất chất lượng;
* đào tạo;
* dịch vụ khoa học và công nghệ.

## Quy tắc

```yaml
if:
  task_nature: "service_or_implementation"
then:
  prefer: TT_KHCN_DMST
```

Nếu là chính sách/quản lý nhà nước:

```yaml
prefer: "phong_chuyen_mon"
```

---

# XIII. BẢNG ÁNH XẠ ĐƠN VỊ → LÃNH ĐẠO

```yaml
unit_leader_map:

  P_TDCL:
    leader_id: PGD_NGUYEN_MINH_HAI
    leader_name: "Nguyễn Minh Hải"

  TT_KHCN_DMST:
    leader_id: PGD_NGUYEN_MINH_HAI
    leader_name: "Nguyễn Minh Hải"

  P_KH:
    leader_id: PGD_HO_THI_DIEP_THUY
    leader_name: "Hồ Thị Diệp Thúy"

  P_KHTC:
    leader_id: PGD_HO_THI_DIEP_THUY
    leader_name: "Hồ Thị Diệp Thúy"

  P_CDS:
    leader_id: PGD_BUI_NGUYEN_KHOI
    leader_name: "Bùi Nguyên Khởi"

  P_CN_DMST:
    leader_id: PGD_VO_BUU_VIET_CUONG
    leader_name: "Võ Bửu Viết Cường"

  TT_CDS:
    leader_id: PGD_NGUYEN_TRUNG_HIEU
    leader_name: "Nguyễn Trung Hiếu"

  VAN_PHONG:
    leader_id: PGD_NGUYEN_TRUNG_HIEU
    leader_name: "Nguyễn Trung Hiếu"
```

---

# XIV. LÃNH ĐẠO CHUYÊN MÔN VÀ LÃNH ĐẠO ĐỊA BÀN

AI phải tách hai trường:

```yaml
lanh_dao_phu_trach_chuyen_mon: ""
lanh_dao_theo_doi_dia_ban: ""
```

Không được coi hai vai trò là một.

Ví dụ:

```yaml
input:
  dia_ban: "Xã Tân Châu"
  linh_vuc: "Chuyển đổi số"

result:

  don_vi_chu_tri:
    id: P_CDS

  lanh_dao_phu_trach_chuyen_mon:
    ho_ten: "Bùi Nguyên Khởi"

  lanh_dao_theo_doi_dia_ban:
    ho_ten: "Nguyễn Trung Hiếu"
```

Lãnh đạo theo dõi địa bàn không tự động thay thế lãnh đạo phụ trách chuyên môn.

---

# XV. QUY TẮC XÁC ĐỊNH ĐƠN VỊ PHỐI HỢP

AI phải xác định:

```yaml
primary_issue: ""
secondary_issues: []
```

Đơn vị xử lý `primary_issue` là chủ trì.

Đơn vị liên quan `secondary_issues` là phối hợp.

---

## Ví dụ 1 — Chuyển đổi số + kinh phí

```yaml
don_vi_chu_tri:
  id: P_CDS

don_vi_phoi_hop:
  - id: P_KHTC
```

---

## Ví dụ 2 — Nhiệm vụ KH&CN + kinh phí

```yaml
don_vi_chu_tri:
  id: P_KH

don_vi_phoi_hop:
  - id: P_KHTC
```

---

## Ví dụ 3 — Chính sách đổi mới sáng tạo + Techfest

```yaml
don_vi_chu_tri:
  id: P_CN_DMST

don_vi_phoi_hop:
  - id: TT_KHCN_DMST
```

---

## Ví dụ 4 — Chính sách chuyển đổi số + vận hành kỹ thuật

```yaml
don_vi_chu_tri:
  id: P_CDS

don_vi_phoi_hop:
  - id: TT_CDS
```

---

# XVI. QUY TẮC THỜI HẠN

## 1. Văn bản từ xã/phường

Nếu không lấy ý kiến cơ quan khác:

```yaml
deadline: "05 ngày làm việc"
```

Nếu phải lấy ý kiến cơ quan khác:

```yaml
deadline: "10 ngày làm việc"
```

Trừ trường hợp có quy định thời hạn khác.

---

## 2. Văn bản giao deadline cụ thể

Nếu văn bản đến đã ghi deadline:

```yaml
deadline_source: "incoming_document"
```

AI phải ưu tiên đối chiếu deadline này với quy định hiện hành.

---

## 3. Nếu không đủ dữ liệu

Nếu thiếu ngày nhận hoặc thiếu căn cứ:

```yaml
deadline:
  value: null
  status: "CAN_KIEM_TRA"
```

Không tự tính.

---

# XVII. QUY TẮC THẨM QUYỀN KÝ

## 1. Văn bản trình UBND tỉnh

```yaml
if:
  submission_to: "UBND tỉnh"
then:
  signer_role: "Giám đốc"
```

Đây là hard rule theo Quy chế hiện hành.

---

## 2. Văn bản thuộc lĩnh vực Phó Giám đốc phụ trách

Nếu:

* không phải văn bản bắt buộc Giám đốc ký;
* thuộc lĩnh vực được phân công;
* không có quy định chuyên ngành khác;

AI có thể đề xuất:

```yaml
signing:
  signer_role: "Phó Giám đốc"
  form: "KT. GIÁM ĐỐC"
  status: "DE_XUAT"
```

---

## 3. Chánh Văn phòng ký thừa lệnh

Chỉ áp dụng cho nhóm được Quy chế cho phép.

Ví dụ:

* giấy mời thông thường;
* truyền đạt ý kiến chỉ đạo;
* thông báo nội bộ;
* sao y;
* thông báo chức danh;
* giấy điều xe;
* giấy đi đường;
* giấy nghỉ phép 01–02 ngày cho đối tượng phù hợp.

Hình thức:

```text
TL. GIÁM ĐỐC
CHÁNH VĂN PHÒNG
```

Không mở rộng phạm vi.

---

# XVIII. ESCALATION — CHUYỂN GIÁM ĐỐC XEM XÉT

AI phải đề xuất báo cáo Giám đốc nếu:

* nội dung mới;
* nội dung quan trọng;
* nội dung cấp bách;
* nội dung nhạy cảm;
* nội dung phức tạp;
* vượt phạm vi Phó Giám đốc;
* có ý kiến khác nhau;
* chưa xác định được đơn vị chủ trì;
* có xung đột nguồn;
* chưa xác định được thẩm quyền ký.

Output:

```yaml
escalation:
  required: true
  to: "GIAM_DOC"
  reason: ""
```

---

# XIX. CHỌN MẪU VĂN BẢN

Các mẫu hiện hành:

```yaml
template_map:

  bao_cao:
    file: "02_van_ban_mau/bao_cao.md"

  cong_van:
    file: "02_van_ban_mau/cong_van.md"

  giay_moi:
    file: "02_van_ban_mau/giay_moi.md"

  ke_hoach:
    file: "02_van_ban_mau/ke_hoach.md"

  ket_luan:
    file: "02_van_ban_mau/ket_luan.md"
```

AI không chọn mẫu trước khi xác định loại văn bản.

---

# XX. PHÂN LOẠI LOẠI VĂN BẢN

Nếu người dùng yêu cầu:

### Công văn trả lời/góp ý/triển khai/xin ý kiến

```yaml
template: "02_van_ban_mau/cong_van.md"
```

### Báo cáo

```yaml
template: "02_van_ban_mau/bao_cao.md"
```

### Kế hoạch

```yaml
template: "02_van_ban_mau/ke_hoach.md"
```

### Giấy mời

```yaml
template: "02_van_ban_mau/giay_moi.md"
```

### Kết luận/thông báo kết luận

```yaml
template: "02_van_ban_mau/ket_luan.md"
```

---

# XXI. OUTPUT ĐỊNH TUYẾN CHUẨN

AI nên tạo kết quả nội bộ theo schema:

```yaml
routing_result:

  tham_quyen_so:
    value: true
    confidence: high

  linh_vuc:
    primary: ""
    secondary: []

  don_vi_chu_tri:
    id: ""
    ten: ""

  don_vi_phoi_hop: []

  lanh_dao_phu_trach_chuyen_mon:
    id: ""
    ho_ten: ""

  dia_ban:
    ten: null
    lanh_dao_theo_doi:
      id: null
      ho_ten: null

  deadline:
    value: null
    source: null

  signing:
    proposed_signer: null
    signing_form: null
    status: "CAN_KIEM_TRA"

  template:
    type: null
    file: null

  escalation:
    required: false
    reason: null

  sources_checked:
    - "01_thong_tin_sokhcn/chuc_nang_nhiem_vu.md"
    - "01_thong_tin_sokhcn/phan_cong.md"
    - "01_thong_tin_sokhcn/quy_che_lam_viec.md"

  confidence: "high"
```

---

# XXII. MỨC ĐỘ TIN CẬY

## HIGH

Khi:

* thẩm quyền rõ;
* đơn vị rõ;
* lãnh đạo rõ;
* nguồn thống nhất.

```yaml
confidence: high
```

## MEDIUM

Khi:

* có giao thoa;
* nhưng có thể xác định được đầu mối chính.

```yaml
confidence: medium
```

## LOW

Khi:

* thiếu nguồn;
* có mâu thuẫn;
* chưa rõ văn bản mới nhất;
* chưa rõ thẩm quyền;
* chưa rõ đơn vị chủ trì.

```yaml
confidence: low
escalation:
  required: true
```

---

# XXIII. STOP CONDITIONS

AI phải dừng định tuyến nếu:

```yaml
stop_conditions:

  - "Không xác định được thẩm quyền Sở"

  - "Không xác định được đơn vị chủ trì"

  - "Hai nguồn hiện hành mâu thuẫn trực tiếp"

  - "Không xác định được văn bản điều chỉnh mới nhất"

  - "Không đủ căn cứ xác định thẩm quyền ký"

  - "Có dấu hiệu tài liệu mật nhưng chưa có quy trình xử lý phù hợp"
```

Output:

```text
Chưa đủ căn cứ để xác định chính xác. Cần kiểm tra thêm nguồn hoặc văn bản hiện hành trước khi xử lý tiếp.
```

---

# XXIV. HARD RULES

AI MUST:

1. Kiểm tra thẩm quyền Sở trước.
2. Xác định một đơn vị chủ trì.
3. Tách chủ trì và phối hợp.
4. Tách lãnh đạo chuyên môn và lãnh đạo địa bàn.
5. Phân biệt quản lý nhà nước và thực thi kỹ thuật.
6. Tra phân công hiện hành trước khi xác định lãnh đạo.
7. Tra Quy chế trước khi đề xuất người ký.
8. Kiểm tra deadline trước khi soạn văn bản.
9. Chỉ dùng căn cứ có liên quan trực tiếp.
10. Chỉ chọn mẫu sau khi xác định loại văn bản.

AI MUST NOT:

1. Bịa căn cứ.
2. Bịa đơn vị chủ trì.
3. Bịa người ký.
4. Bịa thời hạn.
5. Dùng một từ khóa đơn lẻ để định tuyến.
6. Nhầm Phòng Chuyển đổi số với Trung tâm Chuyển đổi số.
7. Nhầm phòng quản lý nhà nước với Trung tâm cung cấp dịch vụ.
8. Nhầm lãnh đạo địa bàn với lãnh đạo chuyên môn.
9. Tự mở rộng thẩm quyền.
10. Tiếp tục định tuyến nếu văn bản không thuộc Sở.

---

# XXV. LUỒNG ĐỊNH TUYẾN CHUẨN

```text
VĂN BẢN ĐẾN
     ↓
TRÍCH XUẤT THÔNG TIN
     ↓
KIỂM TRA THẨM QUYỀN SỞ
     ↓
XÁC ĐỊNH LĨNH VỰC CHÍNH
     ↓
XÁC ĐỊNH BẢN CHẤT NHIỆM VỤ
     ↓
QUẢN LÝ NHÀ NƯỚC / THỰC THI KỸ THUẬT
     ↓
CHỌN 01 ĐƠN VỊ CHỦ TRÌ
     ↓
XÁC ĐỊNH ĐƠN VỊ PHỐI HỢP
     ↓
TRA phan_cong.md
     ↓
XÁC ĐỊNH LÃNH ĐẠO CHUYÊN MÔN
     ↓
KIỂM TRA ĐỊA BÀN NẾU CÓ
     ↓
TRA quy_che_lam_viec.md
     ↓
DEADLINE + QUY TRÌNH + THẨM QUYỀN KÝ
     ↓
TRA 03_can_cu/ NẾU CẦN
     ↓
CHỌN MẪU TẠI 02_van_ban_mau/
     ↓
CHUYỂN SANG SOẠN THẢO
```

---

# XXVI. NGUYÊN TẮC CUỐI

```text
ĐÚNG THẨM QUYỀN
→ ĐÚNG LĨNH VỰC
→ ĐÚNG ĐƠN VỊ CHỦ TRÌ
→ ĐÚNG ĐƠN VỊ PHỐI HỢP
→ ĐÚNG LÃNH ĐẠO
→ ĐÚNG DEADLINE
→ ĐÚNG THẨM QUYỀN KÝ
→ ĐÚNG CĂN CỨ
→ ĐÚNG MẪU
```

Nếu chưa đủ căn cứ:

```text
KHÔNG ĐOÁN.
KHÔNG BỊA.
KHÔNG TỰ MỞ RỘNG.
YÊU CẦU KIỂM TRA THÊM.
```
