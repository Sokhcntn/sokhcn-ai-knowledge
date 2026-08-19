# MẪU VÀ QUY TẮC SOẠN KẾ HOẠCH
## SỞ KHOA HỌC VÀ CÔNG NGHỆ TỈNH TÂY NINH

> File: `02_van_ban_mau/ke_hoach.md`
>
> Vai trò:
> Đây là file mẫu và quy tắc nghiệp vụ để Trợ lý AI soạn các loại Kế hoạch
> của Sở Khoa học và Công nghệ tỉnh Tây Ninh.
>
> File này được chuẩn hóa từ các Kế hoạch thực tế của Sở, gồm:
> - Kế hoạch triển khai văn bản chỉ đạo;
> - Kế hoạch hành động;
> - Kế hoạch tổ chức hội thảo/sự kiện;
> - Kế hoạch đón tiếp, làm việc với đoàn công tác;
> - Kế hoạch phối hợp tổ chức hoạt động;
> - Kế hoạch đào tạo, tập huấn;
> - Kế hoạch thử nghiệm, khảo sát;
> - Kế hoạch truyền thông;
> - Kế hoạch nội bộ;
> - Kế hoạch có phụ lục phân công nhiệm vụ;
> - Kế hoạch có dự toán/kinh phí.
>
> Lưu ý:
> - File này là mẫu soạn thảo, không phải căn cứ xác định thẩm quyền.
> - Trước khi xác định đơn vị chủ trì phải tra:
>   `01_thong_tin_sokhcn/chuc_nang_nhiem_vu.md`.
> - Trước khi xác định lãnh đạo/người ký phải tra:
>   `01_thong_tin_sokhcn/phan_cong.md`
>   và
>   `01_thong_tin_sokhcn/quy_che_lam_viec.md`.
> - Không sao chép số liệu, kinh phí, thời gian, địa điểm hoặc người ký
>   từ kế hoạch cũ sang kế hoạch mới.

---

# I. TEMPLATE METADATA

```yaml
template:
  id: KE_HOACH_SKHCN
  document_type: "KẾ HOẠCH"
  issuing_agency: "SỞ KHOA HỌC VÀ CÔNG NGHỆ"
  province: "TÂY NINH"
  symbol: "KH-SKHCN"
  language: "vi"
````

---

# II. CÁC LOẠI KẾ HOẠCH HỆ THỐNG HỖ TRỢ

```yaml
plan_types:

  KH_TRIEN_KHAI_VAN_BAN:
    description: "Triển khai công văn, kết luận, kế hoạch, chỉ đạo cấp trên"

  KH_HANH_DONG:
    description: "Kế hoạch hành động có mục tiêu, nhiệm vụ, sản phẩm và tiến độ"

  KH_TO_CHUC_SU_KIEN:
    description: "Hội thảo, hội nghị, trình diễn, đào tạo, tập huấn"

  KH_PHOI_HOP:
    description: "Phối hợp với cơ quan, doanh nghiệp, đơn vị ngoài Sở"

  KH_DON_TIEP_LAM_VIEC:
    description: "Đón tiếp đoàn công tác, làm việc, khảo sát"

  KH_THU_NGHIEM_KHAO_SAT:
    description: "Bay thử nghiệm, kiểm thử, khảo sát, trình diễn công nghệ"

  KH_TRUYEN_THONG:
    description: "Truyền thông, tuyên truyền, phổ biến"

  KH_DAO_TAO:
    description: "Khóa đào tạo, bồi dưỡng, hướng dẫn chuyên môn"

  KH_NOI_BO:
    description: "Tham quan, nghỉ dưỡng, hoạt động nội bộ"

  KH_XUC_TIEN:
    description: "Xúc tiến đầu tư, kết nối cung cầu, quảng bá"

  KH_CHIEN_LUOC_THUC_THI:
    description: "Triển khai mục tiêu dài hạn, kinh tế số, chuyển đổi số, đổi mới sáng tạo"
```

---

# III. THỂ THỨC CHUNG

## 1. Cơ quan ban hành

```text
UBND TỈNH TÂY NINH
SỞ KHOA HỌC VÀ CÔNG NGHỆ
```

## 2. Số, ký hiệu

```text
Số:      /KH-SKHCN
```

AI MUST NOT tự tạo số Kế hoạch.

## 3. Quốc hiệu, tiêu ngữ

```text
CỘNG HÒA XÃ HỘI CHỦ NGHĨA VIỆT NAM
Độc lập - Tự do - Hạnh phúc
```

## 4. Địa danh, ngày tháng

```text
Tây Ninh, ngày ... tháng ... năm ...
```

---

# IV. TÊN LOẠI VÀ TRÍCH YẾU

Tên loại:

```text
KẾ HOẠCH
```

Phần trích yếu phải thể hiện rõ nội dung hành động.

Ví dụ:

```text
Triển khai thực hiện Kế hoạch số ... của UBND tỉnh
```

```text
Tổ chức Hội thảo khoa học trình diễn, kết nối cung - cầu công nghệ
```

```text
Tổ chức bay thử nghiệm hệ thống giám sát bằng thiết bị bay không người lái (UAV)
```

```text
Triển khai công tác truyền thông về phát triển hệ thống đổi mới sáng tạo,
hệ sinh thái khởi nghiệp sáng tạo tỉnh Tây Ninh năm 2026
```

---

# V. PHẦN CĂN CỨ / MỞ ĐẦU

Có thể dùng một trong các cách sau.

## Mẫu 1 — Thực hiện chỉ đạo cấp trên

```text
Thực hiện Kế hoạch số [số/ký hiệu] ngày [ngày]
của UBND tỉnh về [nội dung],
Sở Khoa học và Công nghệ xây dựng Kế hoạch triển khai như sau:
```

## Mẫu 2 — Có nhiều căn cứ pháp lý

```text
Căn cứ [văn bản 1];
Căn cứ [văn bản 2];
Căn cứ [văn bản 3];

Sở Khoa học và Công nghệ xây dựng Kế hoạch [nội dung] như sau:
```

## Mẫu 3 — Kế hoạch chủ động của Sở

```text
Nhằm [mục tiêu],
Sở Khoa học và Công nghệ xây dựng Kế hoạch [nội dung] như sau:
```

---

# VI. QUY TẮC DÙNG CĂN CỨ

AI MUST:

* giữ đúng số, ký hiệu;
* giữ đúng ngày ban hành;
* giữ đúng tên văn bản;
* chỉ dùng căn cứ có liên quan trực tiếp.

AI MUST NOT:

* tự bổ sung văn bản pháp luật không có nguồn;
* dùng toàn bộ `03_can_cu/` chỉ vì cùng chủ đề;
* tự sửa sai số/ký hiệu của nguồn.

---

# VII. CẤU TRÚC KẾ HOẠCH CHUNG

Cấu trúc cơ bản:

```text
I. MỤC ĐÍCH, YÊU CẦU

II. NỘI DUNG / NHIỆM VỤ THỰC HIỆN

III. THỜI GIAN, ĐỊA ĐIỂM / TIẾN ĐỘ

IV. KINH PHÍ THỰC HIỆN

V. TỔ CHỨC THỰC HIỆN
```

Không bắt buộc mọi kế hoạch phải có đầy đủ 05 mục.

---

# VIII. MỤC ĐÍCH, YÊU CẦU

## 1. Mục đích

Mục đích phải trả lời:

```text
KẾ HOẠCH NÀY ĐƯỢC LẬP ĐỂ ĐẠT ĐIỀU GÌ?
```

Nên thể hiện:

* cụ thể hóa chỉ đạo;
* tạo kết quả thực tế;
* nâng cao hiệu quả;
* tăng cường phối hợp;
* đạt mục tiêu/chỉ tiêu;
* giải quyết vấn đề cụ thể.

## 2. Yêu cầu

Yêu cầu nên tập trung:

* đúng tiến độ;
* đúng trách nhiệm;
* đúng sản phẩm;
* tiết kiệm;
* hiệu quả;
* an toàn;
* phối hợp chặt chẽ;
* đúng quy định.

---

# IX. NGUYÊN TẮC "RÕ"

Đối với kế hoạch triển khai nhiệm vụ, AI ưu tiên nguyên tắc:

```yaml
clarity_principles:
  - "rõ người"
  - "rõ việc"
  - "rõ trách nhiệm"
  - "rõ thời gian"
  - "rõ sản phẩm"
  - "rõ kết quả"
```

Nếu nguồn dùng nguyên tắc “6 rõ”, giữ đúng cách thể hiện nguồn.

---

# X. KẾ HOẠCH TRIỂN KHAI VĂN BẢN CẤP TRÊN

Áp dụng khi:

* UBND tỉnh giao nhiệm vụ;
* có Công văn/Kế hoạch/Kết luận cần thực hiện.

Cấu trúc:

```text
I. MỤC ĐÍCH, YÊU CẦU

II. NHIỆM VỤ TRỌNG TÂM

III. TỔ CHỨC THỰC HIỆN

PHỤ LỤC
PHÂN CÔNG NHIỆM VỤ
```

Nếu nhiệm vụ nhiều:

không cần trình bày chi tiết toàn bộ trong thân Kế hoạch.

Có thể ghi:

```text
Các phòng, đơn vị triển khai các nhiệm vụ, sản phẩm,
thời hạn và trách nhiệm theo Phụ lục kèm theo Kế hoạch này.
```

---

# XI. KẾ HOẠCH HÀNH ĐỘNG

Áp dụng khi:

* có nhiều nhiệm vụ;
* có deadline rõ;
* có sản phẩm đầu ra;
* có theo dõi tiến độ.

Cấu trúc:

```text
I. MỤC ĐÍCH, MỤC TIÊU

II. PHẠM VI, ĐỐI TƯỢNG, THỜI GIAN

III. NHIỆM VỤ VÀ GIẢI PHÁP

IV. TỔ CHỨC THỰC HIỆN

PHỤ LỤC PHÂN CÔNG NHIỆM VỤ
```

Mỗi nhiệm vụ nên có:

```yaml
task:
  name: ""
  lead_unit: ""
  support_units: []
  responsible_leader: ""
  deadline: ""
  expected_output: ""
  status_tracking: true
```

---

# XII. MỤC TIÊU ĐỊNH LƯỢNG

Nếu kế hoạch có chỉ tiêu:

```yaml
targets:
  - metric: ""
    baseline: null
    target_2026: null
    target_2030: null
```

AI MUST:

* giữ nguyên chỉ tiêu nguồn;
* giữ đúng mốc năm;
* không tự tạo chỉ tiêu.

---

# XIII. KẾ HOẠCH TỔ CHỨC HỘI THẢO / HỘI NGHỊ / SỰ KIỆN

Cấu trúc:

```text
I. MỤC ĐÍCH, YÊU CẦU

II. NỘI DUNG THỰC HIỆN

1. Tên sự kiện
2. Chủ đề
3. Thời gian
4. Địa điểm
5. Thành phần
6. Nội dung chương trình

III. KINH PHÍ

IV. TỔ CHỨC THỰC HIỆN
```

---

# XIV. THÀNH PHẦN SỰ KIỆN

Có thể gồm:

* cơ quan quản lý nhà nước;
* doanh nghiệp;
* viện, trường;
* chuyên gia;
* hợp tác xã;
* người dân;
* cơ quan báo chí;
* tổ chức nước ngoài.

AI không được tự thêm thành phần.

---

# XV. KẾ HOẠCH PHỐI HỢP

Nếu Sở phối hợp với doanh nghiệp/cơ quan:

phải xác định:

```yaml
coordination:
  lead_entity: ""
  co_organizers: []
  responsibilities:
    - entity: ""
      tasks: []
```

Phải phân biệt:

```text
ĐƠN VỊ CHỦ TRÌ
≠
ĐƠN VỊ PHỐI HỢP
```

---

# XVI. KẾ HOẠCH ĐÓN TIẾP / LÀM VIỆC VỚI ĐOÀN CÔNG TÁC

Cấu trúc:

```text
I. MỤC ĐÍCH, YÊU CẦU

II. NỘI DUNG ĐÓN TIẾP / LỊCH TRÌNH

III. THÀNH PHẦN

IV. KINH PHÍ

V. PHÂN CÔNG THỰC HIỆN
```

Lịch trình có thể trình bày:

```yaml
schedule:
  - date: ""
    time: ""
    activity: ""
    responsible_unit: ""
    location: ""
```

---

# XVII. KẾ HOẠCH KHẢO SÁT / THỬ NGHIỆM / TRÌNH DIỄN

Áp dụng cho:

* UAV;
* công nghệ;
* thiết bị;
* khảo sát thực địa.

Cấu trúc:

```text
I. MỤC ĐÍCH, YÊU CẦU

II. NỘI DUNG / ĐỊA ĐIỂM THỬ NGHIỆM

III. THỜI GIAN, LỊCH TRÌNH

IV. THÀNH PHẦN THAM GIA

V. KINH PHÍ

VI. TỔ CHỨC THỰC HIỆN
```

Nếu có yếu tố an toàn:

phải nêu rõ:

* tuân thủ quy định;
* an toàn con người;
* an toàn thiết bị;
* an toàn khu vực;
* bảo mật/an ninh nếu liên quan.

---

# XVIII. KẾ HOẠCH ĐÀO TẠO / TẬP HUẤN

Cấu trúc:

```text
I. MỤC ĐÍCH, YÊU CẦU

II. NỘI DUNG KẾ HOẠCH

1. Đối tượng tham dự
2. Thời gian
3. Số lượng
4. Địa điểm
5. Nội dung đào tạo
6. Giảng viên/chuyên gia
7. Hình thức
8. Kết quả đầu ra

III. KINH PHÍ

IV. TỔ CHỨC THỰC HIỆN
```

---

# XIX. KẾ HOẠCH TRUYỀN THÔNG

Cấu trúc khuyến nghị:

```text
I. MỤC ĐÍCH, YÊU CẦU

II. NỘI DUNG THỰC HIỆN

1. Xây dựng định hướng/nền tảng truyền thông
2. Truyền thông chính sách
3. Truyền thông mô hình, điển hình
4. Truyền thông số
5. Phối hợp báo chí
6. Theo dõi, đánh giá

III. SẢN PHẨM ĐẦU RA

IV. KINH PHÍ

V. TỔ CHỨC THỰC HIỆN
```

---

# XX. KẾ HOẠCH NỘI BỘ

Áp dụng cho:

* tham quan;
* nghỉ dưỡng;
* hoạt động tập thể.

Cấu trúc có thể đơn giản:

```text
I. MỤC ĐÍCH, YÊU CẦU

II. ĐỐI TƯỢNG

III. ĐỊA ĐIỂM, THỜI GIAN

IV. KINH PHÍ

V. TỔ CHỨC THỰC HIỆN
```

Không áp dụng cấu trúc quá nặng như kế hoạch chiến lược.

---

# XXI. KẾ HOẠCH XÚC TIẾN / KẾT NỐI

Áp dụng cho:

* xúc tiến đầu tư;
* kết nối cung - cầu công nghệ;
* quảng bá hệ sinh thái.

Cấu trúc:

```text
I. MỤC ĐÍCH, YÊU CẦU

II. NỘI DUNG THỰC HIỆN

III. THỜI GIAN, ĐỊA ĐIỂM

IV. KINH PHÍ

V. TỔ CHỨC THỰC HIỆN
```

Nội dung có thể gồm:

* mời doanh nghiệp;
* trưng bày;
* giới thiệu công nghệ;
* tiếp chuyên gia;
* video/tài liệu;
* kết nối nhà đầu tư;
* khảo sát/trình diễn.

---

# XXII. KINH PHÍ THỰC HIỆN

Phần kinh phí có thể viết:

```text
Kinh phí thực hiện Kế hoạch được bố trí từ
[nguồn kinh phí] và thực hiện theo đúng chế độ,
tiêu chuẩn, định mức và quy định hiện hành.
```

Hoặc:

```text
Chi tiết kinh phí tại Phụ lục kèm theo.
```

---

# XXIII. HARD RULE VỀ KINH PHÍ

AI MUST:

* giữ nguyên nguồn kinh phí;
* giữ nguyên số tiền;
* không tự tính kinh phí;
* không tự thêm nguồn;
* không tự khẳng định được sử dụng ngân sách nếu chưa có căn cứ.

```yaml
financial_plan:
  source_required: true
  amount_required_if_stated: true
  appendix_allowed: true
```

---

# XXIV. TỔ CHỨC THỰC HIỆN

Phần này phải trả lời:

```text
AI LÀM?
LÀM VIỆC GÌ?
PHỐI HỢP VỚI AI?
BÁO CÁO AI?
```

Cấu trúc:

```text
1. [Đơn vị chủ trì]
- Chủ trì [...]
- Tổng hợp [...]
- Báo cáo [...]

2. [Đơn vị phối hợp]
- Phối hợp [...]
- Cung cấp [...]

3. Văn phòng Sở
- Theo dõi [...]
- Đôn đốc [...]

4. Phòng Kế hoạch - Tài chính
- Tham mưu kinh phí [...]
```

Không bắt buộc Văn phòng/KHTC xuất hiện trong mọi Kế hoạch.

---

# XXV. PHỤ LỤC PHÂN CÔNG NHIỆM VỤ

Nếu kế hoạch có nhiều nhiệm vụ:

```text
PHỤ LỤC
PHÂN CÔNG NHIỆM VỤ TRIỂN KHAI [...]
(Kèm theo Kế hoạch số .../KH-SKHCN ngày ... tháng ... năm ...)
```

Bảng:

| STT | Nhiệm vụ | Sản phẩm/kết quả | Thời hạn | Lãnh đạo phụ trách | Đơn vị chủ trì | Đơn vị phối hợp | Ghi chú |
| --: | -------- | ---------------- | -------- | ------------------ | -------------- | --------------- | ------- |

---

# XXVI. HARD RULE VỀ ĐƠN VỊ CHỦ TRÌ

Mỗi nhiệm vụ phải có:

```yaml
lead_unit_count: 1
```

Các đơn vị khác:

```yaml
support_units: 0..n
```

Không tự tạo “đồng chủ trì” nếu nguồn không quy định.

---

# XXVII. HARD RULE VỀ LÃNH ĐẠO PHỤ TRÁCH

Nếu phụ lục có cột:

```text
Lãnh đạo phụ trách
```

AI phải tra:

`01_thong_tin_sokhcn/phan_cong.md`

Không tự gán theo cảm tính.

---

# XXVIII. QUY TẮC ĐỐI VỚI DEADLINE

Mỗi nhiệm vụ nếu có thể nên có:

```yaml
deadline:
  value: ""
  source: ""
```

AI MUST NOT tự tạo deadline.

Nếu nhiệm vụ cấp trên đã giao thời hạn:

phải giữ đúng.

---

# XXIX. QUY TẮC ĐỐI VỚI SẢN PHẨM ĐẦU RA

Nên mô tả theo dạng cụ thể:

```text
Văn bản
Báo cáo
Quyết định
Kế hoạch
Cơ sở dữ liệu
Hệ thống đưa vào vận hành
Danh sách doanh nghiệp
Video clip
Bộ tài liệu
Biên bản
Dữ liệu khảo sát
```

Hạn chế:

```text
Hoàn thành tốt nhiệm vụ
```

vì đây không phải sản phẩm kiểm chứng được.

---

# XXX. TRẠNG THÁI HOÀN THÀNH

Đối với kế hoạch hành động:

```yaml
completion_rule:
  completed_when:
    - "product_exists"
    - "product_is_approved_or_operational_if_required"
    - "evidence_available"
```

Không coi nhiệm vụ “đang làm” là “hoàn thành”.

---

# XXXI. THEO DÕI, ĐÔN ĐỐC VÀ BÁO CÁO

Nếu cần:

```text
Văn phòng Sở là đầu mối theo dõi, đôn đốc,
tổng hợp tình hình thực hiện.
```

Hoặc đơn vị chuyên môn khác nếu kế hoạch quy định.

Có thể yêu cầu:

```yaml
reporting:
  frequency:
    - monthly
    - quarterly
    - ad_hoc
  recipient: ""
```

---

# XXXII. XỬ LÝ KHÓ KHĂN, VƯỚNG MẮC

Mẫu:

```text
Trong quá trình thực hiện, nếu phát sinh khó khăn,
vướng mắc hoặc cần điều chỉnh nội dung, tiến độ,
các phòng, đơn vị kịp thời báo cáo [đầu mối]
để tổng hợp, tham mưu Giám đốc Sở xem xét, quyết định
hoặc báo cáo cấp có thẩm quyền.
```

---

# XXXIII. CÂU KẾT

Mẫu:

```text
Kế hoạch này là căn cứ để các phòng, đơn vị
thuộc Sở tổ chức triển khai thực hiện./.
```

hoặc:

```text
Trên đây là Kế hoạch [nội dung] của
Sở Khoa học và Công nghệ./.
```

---

# XXXIV. NƠI NHẬN

Mẫu:

```text
Nơi nhận:
- UBND tỉnh (b/c) [nếu có];
- [Cơ quan phối hợp];
- GĐ, các PGĐ Sở;
- Các phòng, đơn vị thuộc Sở;
- Lưu: VT, [đơn vị].
```

AI không tự thêm UBND tỉnh nếu Kế hoạch chỉ dùng nội bộ.

---

# XXXV. KHỐI KÝ

## Giám đốc

```text
GIÁM ĐỐC


[Họ và tên]
```

## Phó Giám đốc ký thay

```text
KT. GIÁM ĐỐC
PHÓ GIÁM ĐỐC


[Họ và tên]
```

---

# XXXVI. QUY TẮC XÁC ĐỊNH NGƯỜI KÝ

Luồng:

```text
NỘI DUNG KẾ HOẠCH
      ↓
ĐƠN VỊ CHỦ TRÌ
      ↓
phan_cong.md
      ↓
LÃNH ĐẠO PHỤ TRÁCH
      ↓
quy_che_lam_viec.md
      ↓
KIỂM TRA MỨC ĐỘ/ĐỐI TƯỢNG KẾ HOẠCH
      ↓
ĐỀ XUẤT NGƯỜI KÝ
```

Không dùng tên người ký trong kế hoạch mẫu làm quy tắc mặc định.

---

# XXXVII. MẪU KẾ HOẠCH CHUNG

```text
UBND TỈNH TÂY NINH
SỞ KHOA HỌC VÀ CÔNG NGHỆ

Số:      /KH-SKHCN

CỘNG HÒA XÃ HỘI CHỦ NGHĨA VIỆT NAM
Độc lập - Tự do - Hạnh phúc

Tây Ninh, ngày ... tháng ... năm ...

KẾ HOẠCH
[TÊN KẾ HOẠCH]

[Căn cứ/Thực hiện văn bản...]

Sở Khoa học và Công nghệ xây dựng Kế hoạch
[nội dung] như sau:

I. MỤC ĐÍCH, YÊU CẦU

1. Mục đích

[...]

2. Yêu cầu

[...]

II. NỘI DUNG THỰC HIỆN

1. [...]

2. [...]

III. THỜI GIAN, ĐỊA ĐIỂM / TIẾN ĐỘ

[...]

IV. KINH PHÍ THỰC HIỆN

[...]

V. TỔ CHỨC THỰC HIỆN

1. [Đơn vị chủ trì]

[...]

2. [Đơn vị phối hợp]

[...]

Trong quá trình thực hiện, nếu có khó khăn,
vướng mắc, các phòng, đơn vị kịp thời báo cáo
để xem xét, xử lý./.

Nơi nhận:
- [...];
- GĐ, các PGĐ Sở;
- [...];
- Lưu: VT, [...].

[CHỨC DANH NGƯỜI KÝ]


[HỌ VÀ TÊN]
```

---

# XXXVIII. MẪU KẾ HOẠCH TRIỂN KHAI CHỈ ĐẠO

```text
KẾ HOẠCH
Triển khai thực hiện [tên văn bản]

Thực hiện [văn bản],
Sở Khoa học và Công nghệ ban hành Kế hoạch như sau:

I. MỤC ĐÍCH, YÊU CẦU

1. Cụ thể hóa các nhiệm vụ được giao.
2. Phân công rõ trách nhiệm, sản phẩm và tiến độ.
3. Bảo đảm phối hợp chặt chẽ.

II. NHIỆM VỤ TRỌNG TÂM

Các phòng, đơn vị triển khai nhiệm vụ theo
Phụ lục phân công kèm theo Kế hoạch.

III. TỔ CHỨC THỰC HIỆN

1. Các đơn vị chủ trì chịu trách nhiệm về tiến độ và chất lượng.
2. Các đơn vị phối hợp cung cấp đầy đủ thông tin, số liệu.
3. [Đầu mối] theo dõi, đôn đốc, tổng hợp.
4. Khó khăn, vướng mắc phải kịp thời báo cáo.

PHỤ LỤC
PHÂN CÔNG NHIỆM VỤ
```

---

# XXXIX. MẪU KẾ HOẠCH TỔ CHỨC SỰ KIỆN

```text
KẾ HOẠCH
Tổ chức [Hội thảo/Hội nghị/Khóa đào tạo]

I. MỤC ĐÍCH, YÊU CẦU

II. NỘI DUNG

1. Tên sự kiện
2. Chủ đề
3. Thời gian
4. Địa điểm
5. Thành phần
6. Nội dung chương trình

III. KINH PHÍ

IV. TỔ CHỨC THỰC HIỆN

1. [Đơn vị chủ trì]
2. [Đơn vị phối hợp]
3. [Văn phòng/KHTC nếu có]
```

---

# XL. MẪU KẾ HOẠCH HÀNH ĐỘNG

```text
KẾ HOẠCH
Triển khai thực hiện [nội dung hành động]

I. MỤC ĐÍCH, MỤC TIÊU

1. Mục đích
2. Mục tiêu

II. PHẠM VI, ĐỐI TƯỢNG, THỜI GIAN

III. NHIỆM VỤ VÀ GIẢI PHÁP

IV. TỔ CHỨC THỰC HIỆN

PHỤ LỤC
PHÂN CÔNG NHIỆM VỤ, SẢN PHẨM VÀ TIẾN ĐỘ
```

---

# XLI. MẪU KẾ HOẠCH ĐÀO TẠO

```text
KẾ HOẠCH
Tổ chức Khóa đào tạo “[Tên khóa]”

I. MỤC ĐÍCH, YÊU CẦU

II. NỘI DUNG KẾ HOẠCH

1. Đối tượng
2. Thời gian
3. Địa điểm
4. Số lượng
5. Nội dung đào tạo
6. Giảng viên
7. Hình thức tổ chức
8. Sản phẩm/kết quả

III. KINH PHÍ

IV. TỔ CHỨC THỰC HIỆN
```

---

# XLII. MẪU KẾ HOẠCH THỬ NGHIỆM / KHẢO SÁT

```text
KẾ HOẠCH
Tổ chức [bay thử nghiệm/khảo sát/trình diễn] [...]

I. MỤC ĐÍCH, YÊU CẦU

II. NỘI DUNG

III. THỜI GIAN, LỊCH TRÌNH

IV. THÀNH PHẦN

V. KINH PHÍ

VI. TỔ CHỨC THỰC HIỆN

1. Đơn vị chủ trì
2. Đơn vị kỹ thuật
3. Đơn vị phối hợp
4. Đơn vị tài chính
```

---

# XLIII. OUTPUT NỘI BỘ KHUYẾN NGHỊ

```yaml
plan_draft:

  plan_type: ""

  title: ""

  basis_documents: []

  purpose: []

  requirements: []

  scope:
    subjects: []
    geography: []
    period:
      from: null
      to: null

  targets: []

  tasks:
    - id: ""
      name: ""
      lead_unit: ""
      support_units: []
      responsible_leader: null
      deadline: null
      expected_output: null

  event:
    time: null
    location: null
    participants: []

  budget:
    source: null
    amount: null
    appendix_required: false

  monitoring:
    lead: null
    reporting_frequency: null

  appendix:
    required: false
    type: null

  recipients: []

  signing:
    proposed_signer: null
    signing_form: null
    status: "CAN_KIEM_TRA"

  confidence: "high | medium | low"
```

---

# XLIV. ROUTING LOẠI KẾ HOẠCH

```yaml
plan_router:

  if:
    purpose == "implement_superior_document"
  then:
    type: KH_TRIEN_KHAI_VAN_BAN

  if:
    purpose == "execute_multiple_deadline_tasks"
  then:
    type: KH_HANH_DONG

  if:
    purpose in [
      "conference",
      "workshop",
      "training",
      "event"
    ]
  then:
    type: KH_TO_CHUC_SU_KIEN

  if:
    purpose == "coordinate_with_external_entities"
  then:
    type: KH_PHOI_HOP

  if:
    purpose == "receive_or_work_with_delegation"
  then:
    type: KH_DON_TIEP_LAM_VIEC

  if:
    purpose in [
      "pilot",
      "field_test",
      "survey"
    ]
  then:
    type: KH_THU_NGHIEM_KHAO_SAT

  if:
    purpose == "communication"
  then:
    type: KH_TRUYEN_THONG

  if:
    purpose == "training"
  then:
    type: KH_DAO_TAO

  if:
    purpose == "internal_staff_activity"
  then:
    type: KH_NOI_BO

  if:
    purpose == "investment_or_technology_promotion"
  then:
    type: KH_XUC_TIEN
```

---

# XLV. FINAL CHECKLIST

```yaml
final_checklist:

  plan_type_correct: true

  legal_basis_verified: true

  purpose_clear: true

  requirements_clear: true

  tasks_complete: true

  lead_unit_checked: true

  support_units_checked: true

  responsible_leader_checked: true

  deadlines_verified: true

  expected_outputs_verified: true

  budget_source_verified: true

  amount_verified_if_present: true

  time_location_verified_if_event: true

  appendix_consistent_with_body: true

  recipients_verified: true

  signer_checked_with_assignment: true

  signer_checked_with_work_rules: true
```

---

# XLVI. HARD RULES

AI MUST:

1. Xác định loại Kế hoạch trước khi chọn cấu trúc.
2. Chỉ dùng căn cứ có nguồn.
3. Xác định 01 đơn vị chủ trì cho từng nhiệm vụ.
4. Xác định rõ sản phẩm đầu ra.
5. Giữ đúng deadline nguồn.
6. Giữ đúng chỉ tiêu nguồn.
7. Giữ đúng kinh phí nguồn.
8. Dùng phụ lục khi nhiệm vụ nhiều.
9. Tra phân công trước khi gán lãnh đạo.
10. Tra Quy chế trước khi xác định người ký.
11. Phân biệt đơn vị chủ trì kế hoạch và đơn vị chủ trì từng nhiệm vụ.
12. Phân biệt mục tiêu với nhiệm vụ.
13. Phân biệt nhiệm vụ với sản phẩm.

AI MUST NOT:

1. Tự tạo số Kế hoạch.
2. Tự tạo ngày ban hành.
3. Tự tạo căn cứ.
4. Tự tạo chỉ tiêu.
5. Tự tạo deadline.
6. Tự tạo kinh phí.
7. Tự tạo nguồn kinh phí.
8. Tự tạo người ký.
9. Tự tạo đơn vị phối hợp.
10. Tự gán hai đơn vị cùng chủ trì.
11. Sao chép lịch trình cũ sang kế hoạch mới.
12. Sao chép địa điểm cũ nếu chưa xác nhận.
13. Sao chép mức kinh phí của kế hoạch khác.
14. Sao chép người ký từ kế hoạch mẫu.
15. Biến nội dung mang tính định hướng thành nhiệm vụ đã được giao nếu nguồn không quy định.

---

# XLVII. STOP CONDITIONS

```yaml
stop_conditions:

  - "Không xác định được mục tiêu Kế hoạch"

  - "Không xác định được căn cứ"

  - "Không xác định được đơn vị chủ trì"

  - "Không xác định được nhiệm vụ chính"

  - "Có chỉ tiêu nhưng nguồn mâu thuẫn"

  - "Có kinh phí nhưng chưa rõ nguồn"

  - "Có thời hạn nhưng chưa rõ căn cứ"

  - "Có phụ lục nhưng chưa đủ dữ liệu phân công"

  - "Không đủ căn cứ xác định lãnh đạo phụ trách"

  - "Không đủ căn cứ xác định người ký"
```

Output:

```text
Chưa đủ thông tin để hoàn thiện Kế hoạch.
Cần bổ sung hoặc kiểm tra thêm căn cứ, nhiệm vụ,
đơn vị chủ trì, tiến độ, sản phẩm hoặc kinh phí trước khi phát hành dự thảo.
```

---

# XLVIII. QUY TRÌNH AI SOẠN KẾ HOẠCH

```text
YÊU CẦU / VĂN BẢN CHỈ ĐẠO
          ↓
XÁC ĐỊNH LOẠI KẾ HOẠCH
          ↓
XÁC ĐỊNH CĂN CỨ
          ↓
XÁC ĐỊNH MỤC ĐÍCH
          ↓
XÁC ĐỊNH YÊU CẦU
          ↓
XÁC ĐỊNH NHIỆM VỤ
          ↓
XÁC ĐỊNH 01 ĐƠN VỊ CHỦ TRÌ/TỪNG NHIỆM VỤ
          ↓
XÁC ĐỊNH ĐƠN VỊ PHỐI HỢP
          ↓
XÁC ĐỊNH SẢN PHẨM
          ↓
XÁC ĐỊNH DEADLINE
          ↓
XÁC ĐỊNH KINH PHÍ
          ↓
XÁC ĐỊNH PHỤ LỤC
          ↓
TRA phan_cong.md
          ↓
XÁC ĐỊNH LÃNH ĐẠO PHỤ TRÁCH
          ↓
TRA quy_che_lam_viec.md
          ↓
XÁC ĐỊNH NGƯỜI KÝ
          ↓
KIỂM TRA TOÀN BỘ
          ↓
XUẤT KẾ HOẠCH
```

---

# XLIX. NGUYÊN TẮC CUỐI

Một Kế hoạch tốt phải trả lời được:

```text
VÌ SAO PHẢI LÀM?
↓
MỤC TIÊU LÀ GÌ?
↓
CẦN LÀM NHỮNG VIỆC GÌ?
↓
AI CHỦ TRÌ?
↓
AI PHỐI HỢP?
↓
KHI NÀO HOÀN THÀNH?
↓
SẢN PHẨM LÀ GÌ?
↓
KINH PHÍ TỪ ĐÂU?
↓
AI THEO DÕI?
↓
AI CHỊU TRÁCH NHIỆM?
↓
AI CÓ THẨM QUYỀN KÝ?
```

Nguyên tắc:

```text
ĐÚNG CĂN CỨ
→ ĐÚNG MỤC TIÊU
→ ĐÚNG NHIỆM VỤ
→ ĐÚNG ĐƠN VỊ
→ ĐÚNG LÃNH ĐẠO
→ ĐÚNG DEADLINE
→ ĐÚNG SẢN PHẨM
→ ĐÚNG KINH PHÍ
→ ĐÚNG PHỤ LỤC
→ ĐÚNG NGƯỜI KÝ
```

Nếu chưa đủ dữ liệu:

```text
KHÔNG BỊA CĂN CỨ.
KHÔNG BỊA CHỈ TIÊU.
KHÔNG BỊA DEADLINE.
KHÔNG BỊA KINH PHÍ.
KHÔNG TỰ GÁN ĐƠN VỊ.
KHÔNG TỰ CHỌN NGƯỜI KÝ.
PHẢI ĐỂ TRỐNG HOẶC YÊU CẦU BỔ SUNG.
```

```

Một điểm quan trọng tôi giữ từ các file thực tế là **không ép tất cả Kế hoạch vào cùng một cấu trúc cứng**. Ví dụ, kế hoạch tham quan nội bộ chỉ cần mục đích, đối tượng, thời gian, kinh phí và tổ chức thực hiện; :contentReference[oaicite:13]{index=13} kế hoạch hành động 100 ngày lại cần mục tiêu, phạm vi, nhiệm vụ, sản phẩm, deadline và theo dõi rất chặt; :contentReference[oaicite:14]{index=14} còn kế hoạch triển khai Công văn 13756/UBND-TH sử dụng phụ lục phân công có đủ **nhiệm vụ – sản phẩm – thời hạn – lãnh đạo – chủ trì – phối hợp**. :contentReference[oaicite:15]{index=15}

Đây là cách phù hợp nhất để ChatGPT sau này **tự chọn biến thể Kế hoạch theo mục đích thực tế**, thay vì lấy một mẫu chung cho mọi trường hợp.
```
