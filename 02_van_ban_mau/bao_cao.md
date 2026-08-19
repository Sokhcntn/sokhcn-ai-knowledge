# MẪU VÀ QUY TẮC SOẠN BÁO CÁO
## SỞ KHOA HỌC VÀ CÔNG NGHỆ TỈNH TÂY NINH

> File: `02_van_ban_mau/bao_cao.md`
>
> Vai trò:
> Đây là file mẫu và quy tắc nghiệp vụ để Trợ lý AI soạn các loại Báo cáo của
> Sở Khoa học và Công nghệ tỉnh Tây Ninh.
>
> File này được chuẩn hóa từ các báo cáo thực tế của Sở, gồm:
> - Báo cáo kết quả triển khai Kế hoạch hành động 100 ngày xử lý các điểm nghẽn về chuyển đổi số;
> - Báo cáo tình hình thực hiện nhiệm vụ và các vấn đề trọng tâm phục vụ làm việc với Phó Chủ tịch UBND tỉnh;
> - Báo cáo kết quả triển khai hoạt động Tổ Công nghệ số cộng đồng;
> - Báo cáo tình hình phát triển kinh tế - xã hội tháng và kế hoạch tháng tiếp theo lĩnh vực KH&CN.
>
> Mục đích:
> - chọn đúng cấu trúc báo cáo;
> - giữ đúng thể thức hành chính;
> - trình bày kết quả có số liệu, căn cứ và đánh giá;
> - phân biệt kết quả, tồn tại, nguyên nhân, phương hướng và kiến nghị;
> - hỗ trợ tạo phụ lục/bảng tiến độ khi cần.
>
> Lưu ý:
> - File này là mẫu soạn thảo, không phải căn cứ xác định thẩm quyền.
> - Trước khi xác định người ký phải tra:
>   `01_thong_tin_sokhcn/phan_cong.md`
>   và
>   `01_thong_tin_sokhcn/quy_che_lam_viec.md`.

---

# I. TEMPLATE METADATA

```yaml
template:
  id: BAO_CAO_SKHCN
  document_type: "BÁO CÁO"
  agency: "SỞ KHOA HỌC VÀ CÔNG NGHỆ"
  province: "TÂY NINH"
  symbol: "BC-SKHCN"
  language: "vi"
````

---

# II. CÁC LOẠI BÁO CÁO HỆ THỐNG HỖ TRỢ

```yaml
report_types:

  BAO_CAO_DINH_KY:
    description: "Báo cáo tháng, quý, 6 tháng, 9 tháng, năm"

  BAO_CAO_CHUYEN_DE:
    description: "Báo cáo một lĩnh vực hoặc nhiệm vụ chuyên đề"

  BAO_CAO_TIEN_DO:
    description: "Báo cáo tiến độ thực hiện kế hoạch, chương trình, nhiệm vụ"

  BAO_CAO_PHUC_VU_LANH_DAO:
    description: "Báo cáo phục vụ buổi làm việc, họp, kiểm tra, giám sát"

  BAO_CAO_KET_QUA:
    description: "Báo cáo kết quả triển khai một nhiệm vụ cụ thể"

  BAO_CAO_KHO_KHAN_KIEN_NGHI:
    description: "Báo cáo tập trung vào khó khăn, vướng mắc và đề xuất"

  BAO_CAO_TONG_HOP:
    description: "Báo cáo nhiều lĩnh vực hoặc toàn Sở"
```

---

# III. THỂ THỨC CHUNG

## 1. Phần đầu văn bản

```text
UBND TỈNH TÂY NINH
SỞ KHOA HỌC VÀ CÔNG NGHỆ

Số:      /BC-SKHCN

CỘNG HÒA XÃ HỘI CHỦ NGHĨA VIỆT NAM
Độc lập - Tự do - Hạnh phúc

Tây Ninh, ngày ... tháng ... năm ...
```

AI MUST NOT tự tạo số báo cáo nếu người dùng chưa cung cấp.

Sử dụng:

```text
Số:      /BC-SKHCN
```

hoặc trường trống tương đương.

---

## 2. Tên loại văn bản

```text
BÁO CÁO
```

In hoa, đậm, canh giữa.

---

## 3. Trích yếu

Trích yếu phải:

* ngắn gọn;
* phản ánh đúng nội dung chính;
* không quá chung chung;
* không đưa nội dung kiến nghị vào trích yếu nếu đó không phải mục tiêu chính.

Ví dụ:

```text
Kết quả triển khai thực hiện Kế hoạch hành động 100 ngày
xử lý các điểm nghẽn về chuyển đổi số
```

hoặc:

```text
Tình hình phát triển kinh tế - xã hội tháng 8 năm 2026
và kế hoạch tháng 9 năm 2026 lĩnh vực Khoa học và Công nghệ
```

hoặc:

```text
Tình hình thực hiện nhiệm vụ và các vấn đề trọng tâm
của Sở Khoa học và Công nghệ phục vụ làm việc với Phó Chủ tịch UBND tỉnh
```

---

# IV. PHẦN MỞ ĐẦU

Phần mở đầu của báo cáo nên trả lời:

1. Báo cáo được thực hiện theo căn cứ/chỉ đạo nào?
2. Cơ quan nào giao nhiệm vụ?
3. Báo cáo về nội dung gì?
4. Kỳ báo cáo hoặc thời điểm chốt số liệu là khi nào?

---

## Mẫu mở đầu loại 1 — Có văn bản căn cứ

```text
Thực hiện [tên, số, ký hiệu, ngày ban hành của văn bản chỉ đạo/kế hoạch],
Sở Khoa học và Công nghệ báo cáo [nội dung báo cáo] như sau:
```

---

## Mẫu mở đầu loại 2 — Có nhiều căn cứ

```text
Thực hiện [văn bản 1]; [văn bản 2]; [văn bản 3],
Sở Khoa học và Công nghệ báo cáo [nội dung] như sau:
```

---

## Mẫu mở đầu loại 3 — Báo cáo phục vụ buổi làm việc

Có thể vào trực tiếp nội dung:

```text
I. KHÁI QUÁT CHUNG
```

nếu mục đích và đối tượng phục vụ đã thể hiện rõ trong trích yếu.

---

# V. NGUYÊN TẮC DÙNG CĂN CỨ

AI MUST:

* ghi đầy đủ số, ký hiệu;
* ghi ngày ban hành nếu có;
* ghi đúng cơ quan ban hành;
* chỉ dùng căn cứ có liên quan trực tiếp.

AI MUST NOT:

* tự tạo căn cứ;
* tự bổ sung văn bản pháp lý theo kiến thức chung;
* viện dẫn toàn bộ `03_can_cu/` chỉ vì cùng lĩnh vực;
* sửa số, ngày của căn cứ nguồn.

---

# VI. CẤU TRÚC A — BÁO CÁO ĐỊNH KỲ

Áp dụng cho:

* báo cáo tháng;
* báo cáo quý;
* báo cáo 6 tháng;
* báo cáo 9 tháng;
* báo cáo năm.

Cấu trúc khuyến nghị:

```text
I. KẾT QUẢ NỔI BẬT

II. KẾT QUẢ CHI TIẾT THEO LĨNH VỰC

III. TỒN TẠI, HẠN CHẾ; KHÓ KHĂN, VƯỚNG MẮC

IV. PHƯƠNG HƯỚNG, NHIỆM VỤ KỲ TIẾP THEO

V. ĐỀ XUẤT, KIẾN NGHỊ
```

Tùy dữ liệu thực tế có thể bỏ mục III hoặc V nếu không phát sinh.

---

# VII. CẤU TRÚC B — BÁO CÁO CHUYÊN ĐỀ / TIẾN ĐỘ

Áp dụng cho:

* thực hiện một kế hoạch;
* chương trình hành động;
* nhiệm vụ chuyên đề;
* kiểm tra tiến độ.

Cấu trúc khuyến nghị:

```text
1. Công tác chỉ đạo, điều hành

2. Kết quả triển khai thực hiện

3. Phương hướng thực hiện

4. Khó khăn, vướng mắc, đề xuất, kiến nghị
```

Có thể kèm:

```text
PHỤ LỤC
BẢNG TỔNG HỢP KẾT QUẢ THỰC HIỆN NHIỆM VỤ
```

---

# VIII. CẤU TRÚC C — BÁO CÁO CHUYÊN ĐỀ CÓ CHỈ TIÊU

Áp dụng khi cần báo cáo:

* kết quả hoạt động;
* số lượng;
* tỷ lệ;
* địa phương thực hiện;
* tình trạng hoàn thành.

Cấu trúc:

```text
I. CÔNG TÁC BAN HÀNH THỂ CHẾ, CHÍNH SÁCH VÀ CHỈ ĐẠO,
TRIỂN KHAI THỰC HIỆN

II. KẾT QUẢ THỰC HIỆN

III. TỒN TẠI, HẠN CHẾ; KHÓ KHĂN, VƯỚNG MẮC

IV. ĐỀ XUẤT, KIẾN NGHỊ
```

Trong mục II có thể sử dụng bảng chỉ tiêu.

Ví dụ:

| STT | Chỉ tiêu đánh giá |   Kết quả |
| --: | ----------------- | --------: |
|   1 | [Chỉ tiêu]        | [Số liệu] |
|   2 | [Chỉ tiêu]        | [Số liệu] |

---

# IX. CẤU TRÚC D — BÁO CÁO PHỤC VỤ LÃNH ĐẠO LÀM VIỆC

Áp dụng cho:

* làm việc với Chủ tịch/PCT UBND tỉnh;
* đoàn kiểm tra;
* đoàn giám sát;
* họp giao ban chuyên đề.

Cấu trúc nên thiên về điều hành:

```text
I. KHÁI QUÁT CHUNG

II. KẾT QUẢ NỔI BẬT

III. PHƯƠNG HƯỚNG, NHIỆM VỤ TRỌNG TÂM

IV. KHÓ KHĂN, VƯỚNG MẮC

V. KIẾN NGHỊ, ĐỀ XUẤT
```

Có thể chia phần nhiệm vụ theo:

* Trung ương giao;
* Tỉnh ủy giao;
* UBND tỉnh giao;
* nhiệm vụ trọng tâm của Sở;
* từng lĩnh vực chuyên môn.

---

# X. CẤU TRÚC KẾT QUẢ THEO LĨNH VỰC

Đối với báo cáo tổng hợp toàn Sở, AI có thể chia:

```text
1. Lĩnh vực khoa học

2. Lĩnh vực công nghệ và đổi mới sáng tạo

3. Lĩnh vực chuyển đổi số

4. Lĩnh vực tiêu chuẩn đo lường chất lượng

5. Lĩnh vực kế hoạch - tài chính

6. Công tác hành chính, tổ chức, quản trị

7. Hoạt động các đơn vị sự nghiệp
```

Chỉ sử dụng các mục có dữ liệu.

Không tạo mục rỗng chỉ để đủ cấu trúc.

---

# XI. CÁCH VIẾT PHẦN KẾT QUẢ

Mỗi kết quả nên ưu tiên cấu trúc:

```text
NHIỆM VỤ
→ HÀNH ĐỘNG ĐÃ THỰC HIỆN
→ SẢN PHẨM/KẾT QUẢ
→ SỐ LIỆU
→ VĂN BẢN CHỨNG MINH
→ TRẠNG THÁI
```

Ví dụ logic:

```yaml
result_item:
  task: ""
  action: ""
  output: ""
  quantity: null
  evidence_document: ""
  status: "completed | in_progress | delayed"
```

---

# XII. QUY TẮC SỬ DỤNG SỐ LIỆU

AI MUST:

* giữ nguyên số liệu nguồn;
* ghi rõ thời điểm chốt số liệu khi có;
* tính tỷ lệ chỉ khi đủ tử số và mẫu số;
* nếu tính lại thì phải bảo đảm toán học chính xác.

Ví dụ:

```text
92/96 xã, phường, đạt 95,83%.
```

Nếu nguồn đã có tỷ lệ:

* giữ nguyên nếu không có yêu cầu kiểm tra;
* không tự sửa chỉ vì thấy có khả năng sai.

Nếu dữ liệu giữa các nguồn khác nhau:

```yaml
status: "CAN_KIEM_TRA_SO_LIEU"
```

Không tự chọn số có vẻ hợp lý hơn.

---

# XIII. QUY TẮC VỀ MỐC THỜI GIAN

Nên ghi rõ:

```text
Tính đến ngày ...
```

hoặc:

```text
Trong kỳ báo cáo ...
```

hoặc:

```text
Đến hết ngày ...
```

Không trộn số liệu có các thời điểm chốt khác nhau mà không chú thích.

---

# XIV. CÁCH VIẾT KẾT QUẢ NỔI BẬT

Phần này không phải liệt kê toàn bộ nhiệm vụ.

Chỉ chọn:

* kết quả có tác động lớn;
* nhiệm vụ đã hoàn thành;
* chỉ tiêu nổi bật;
* vấn đề có ý nghĩa điều hành;
* sản phẩm đã được ban hành/phê duyệt;
* kết quả có số liệu đáng chú ý.

AI SHOULD:

```yaml
highlight_selection:
  prefer:
    - high_impact
    - completed
    - measurable
    - strategic
    - leadership_relevant
```

---

# XV. CÁCH VIẾT TỒN TẠI, HẠN CHẾ

Không viết chung chung.

Mỗi nội dung nên có:

```text
VẤN ĐỀ
→ HIỆN TRẠNG
→ PHẠM VI/ĐƠN VỊ BỊ ẢNH HƯỞNG
→ TÁC ĐỘNG
```

Ví dụ dạng cấu trúc:

```yaml
issue:
  problem: ""
  evidence: ""
  impact: ""
```

---

# XVI. CÁCH VIẾT NGUYÊN NHÂN

Nếu nguồn có dữ liệu, có thể chia:

```text
1. Nguyên nhân khách quan
2. Nguyên nhân chủ quan
```

Không tự tạo nguyên nhân.

Nếu nguồn chỉ thể hiện hiện trạng nhưng chưa xác định nguyên nhân:

AI không được suy đoán.

---

# XVII. CÁCH VIẾT PHƯƠNG HƯỚNG, NHIỆM VỤ

Mỗi nhiệm vụ kỳ tới nên có nếu dữ liệu cho phép:

```yaml
future_task:
  task: ""
  lead_unit: ""
  deadline: ""
  output: ""
```

Ưu tiên cách viết hành động:

* tiếp tục;
* hoàn thành;
* tham mưu;
* trình;
* ban hành;
* tổ chức;
* rà soát;
* đôn đốc;
* phối hợp;
* kiểm tra.

Hạn chế câu chung chung như:

```text
Tiếp tục thực hiện tốt các nhiệm vụ được giao.
```

nếu có thể xác định nhiệm vụ cụ thể.

---

# XVIII. CÁCH VIẾT ĐỀ XUẤT, KIẾN NGHỊ

Kiến nghị phải gắn với khó khăn đã nêu.

Cấu trúc:

```text
KHÓ KHĂN
→ CƠ QUAN CÓ THẨM QUYỀN
→ HÀNH ĐỘNG ĐỀ NGHỊ
→ KẾT QUẢ MONG MUỐN
```

Ví dụ schema:

```yaml
recommendation:
  issue: ""
  requested_agency: ""
  requested_action: ""
  expected_result: ""
```

Không kiến nghị vượt thẩm quyền hoặc không có căn cứ.

---

# XIX. QUY TẮC ĐỐI VỚI NHIỆM VỤ CHẬM TIẾN ĐỘ

Nếu nhiệm vụ chậm:

phải nêu rõ nếu nguồn có:

* nhiệm vụ;
* thời hạn ban đầu;
* nguyên nhân;
* tình trạng hiện tại;
* giải pháp;
* thời hạn đề nghị điều chỉnh/gia hạn.

Không che giấu trạng thái chậm bằng cách chỉ ghi “đang triển khai”.

Ví dụ:

```yaml
task_status:
  status: "delayed"
  original_deadline: ""
  cause: ""
  corrective_action: ""
  proposed_new_deadline: ""
```

---

# XX. PHỤ LỤC TIẾN ĐỘ

Nếu báo cáo có nhiều nhiệm vụ, nên dùng phụ lục.

Mẫu:

```text
PHỤ LỤC
BẢNG TỔNG HỢP KẾT QUẢ THỰC HIỆN NHIỆM VỤ
(Kèm theo Báo cáo số .../BC-SKHCN ngày ... tháng ... năm ...)
```

Bảng:

| STT | Nhiệm vụ/chỉ tiêu | Chủ trì | Phối hợp | Thời hạn | Sản phẩm đầu ra | Kết quả thực hiện | Trạng thái |
| --: | ----------------- | ------- | -------- | -------- | --------------- | ----------------- | ---------- |

---

# XXI. BẢNG THỐNG KÊ TỔNG HỢP

Có thể dùng trước bảng chi tiết:

| Nội dung thống kê          | Số lượng |
| -------------------------- | -------: |
| Tổng số nhiệm vụ được giao |    [...] |
| Đã hoàn thành              |    [...] |
| Đang thực hiện             |    [...] |
| Chậm tiến độ               |    [...] |
| Chưa triển khai            |    [...] |

AI chỉ tạo các dòng có dữ liệu.

---

# XXII. TRẠNG THÁI NHIỆM VỤ

Chuẩn hóa:

```yaml
task_status_values:
  - NOT_STARTED
  - IN_PROGRESS
  - COMPLETED
  - DELAYED
  - SUSPENDED
  - CANCELLED
  - WAITING_FOR_INPUT
```

Khi xuất ra văn bản hành chính, chuyển thành:

```text
Chưa triển khai
Đang thực hiện
Hoàn thành
Chậm tiến độ
Tạm dừng
Dừng thực hiện
Chờ số liệu/ý kiến
```

---

# XXIII. PHẦN KẾT THÚC BÁO CÁO

Tùy mục đích:

## Báo cáo để tổng hợp

```text
Trên đây là Báo cáo [trích yếu] của Sở Khoa học và Công nghệ,
kính gửi [cơ quan] tổng hợp./.
```

## Báo cáo UBND tỉnh

```text
Trên đây là Báo cáo [trích yếu] của Sở Khoa học và Công nghệ,
kính báo cáo UBND tỉnh./.
```

## Báo cáo xin chỉ đạo

```text
Trên đây là Báo cáo [trích yếu] của Sở Khoa học và Công nghệ,
kính báo cáo và xin ý kiến chỉ đạo của UBND tỉnh./.
```

## Báo cáo phục vụ buổi làm việc

```text
Trên đây là Báo cáo phục vụ buổi làm việc của [chức danh/cơ quan]
với Sở Khoa học và Công nghệ./.
```

Không dùng “kính đề nghị” ở đoạn kết nếu nội dung báo cáo không có đề xuất.

---

# XXIV. NƠI NHẬN

Mẫu tổng quát:

```text
Nơi nhận:
- [Cơ quan nhận báo cáo];
- GĐ, các PGĐ Sở;
- Các phòng, đơn vị thuộc Sở;
- Lưu: VT, [đơn vị soạn thảo].
```

AI phải điều chỉnh theo từng báo cáo.

Không tự thêm cơ quan nhận nếu không liên quan.

---

# XXV. KHỐI KÝ

Mặc định:

```text
GIÁM ĐỐC



[Họ và tên]
```

hoặc nếu đủ căn cứ:

```text
KT. GIÁM ĐỐC
PHÓ GIÁM ĐỐC



[Họ và tên]
```

AI MUST NOT tự chọn người ký chỉ từ mẫu.

Phải tra:

```text
01_thong_tin_sokhcn/phan_cong.md
→
01_thong_tin_sokhcn/quy_che_lam_viec.md
```

Đặc biệt:

```yaml
if:
  report_submitted_to_ubnd_province: true
then:
  signer_role: "Giám đốc"
```

theo Quy chế hiện hành.

---

# XXVI. CẤU TRÚC MẪU HOÀN CHỈNH — BÁO CÁO CHUYÊN ĐỀ

```text
UBND TỈNH TÂY NINH
SỞ KHOA HỌC VÀ CÔNG NGHỆ

Số:      /BC-SKHCN

CỘNG HÒA XÃ HỘI CHỦ NGHĨA VIỆT NAM
Độc lập - Tự do - Hạnh phúc

Tây Ninh, ngày ... tháng ... năm ...

BÁO CÁO
[TRÍCH YẾU]

Thực hiện [văn bản/căn cứ], Sở Khoa học và Công nghệ
báo cáo [nội dung] như sau:

I. [CÔNG TÁC CHỈ ĐẠO, TRIỂN KHAI]

[Nội dung]

II. [KẾT QUẢ THỰC HIỆN]

1. [Nội dung 1]

[Nội dung]

2. [Nội dung 2]

[Nội dung]

III. TỒN TẠI, HẠN CHẾ; KHÓ KHĂN, VƯỚNG MẮC

1. [Nội dung]

2. [Nội dung]

IV. PHƯƠNG HƯỚNG, NHIỆM VỤ

1. [Nội dung]

2. [Nội dung]

V. ĐỀ XUẤT, KIẾN NGHỊ

1. [Nội dung]

2. [Nội dung]

Trên đây là Báo cáo [trích yếu] của Sở Khoa học và Công nghệ,
kính [báo cáo/gửi/xin ý kiến] [cơ quan]./.

Nơi nhận:
- [...];
- GĐ, các PGĐ Sở;
- [...];
- Lưu: VT, [...].

[CHỨC DANH NGƯỜI KÝ]


[HỌ VÀ TÊN]
```

---

# XXVII. CẤU TRÚC MẪU — BÁO CÁO ĐỊNH KỲ THÁNG

```text
BÁO CÁO
Tình hình [nội dung] tháng ... năm ...
và phương hướng, nhiệm vụ tháng ... năm ...

Thực hiện [căn cứ nếu có], Sở Khoa học và Công nghệ
báo cáo như sau:

I. KẾT QUẢ NỔI BẬT

[Nêu ngắn các kết quả đáng chú ý nhất trong kỳ.]

II. KẾT QUẢ CHI TIẾT THEO LĨNH VỰC

1. Lĩnh vực khoa học

[...]

2. Lĩnh vực công nghệ và đổi mới sáng tạo

[...]

3. Lĩnh vực chuyển đổi số

[...]

4. Lĩnh vực tiêu chuẩn đo lường chất lượng

[...]

5. Lĩnh vực kế hoạch - tài chính

[...]

6. Công tác hành chính, tổ chức, quản trị

[...]

III. TỒN TẠI, HẠN CHẾ; KHÓ KHĂN, VƯỚNG MẮC

[...]

IV. PHƯƠNG HƯỚNG, NHIỆM VỤ THÁNG TIẾP THEO

[...]

V. ĐỀ XUẤT, KIẾN NGHỊ

[Chỉ lập nếu có.]
```

---

# XXVIII. CẤU TRÚC MẪU — BÁO CÁO PHỤC VỤ LÃNH ĐẠO

```text
BÁO CÁO
Tình hình thực hiện nhiệm vụ và các vấn đề trọng tâm
của Sở Khoa học và Công nghệ phục vụ [nội dung làm việc]

I. KHÁI QUÁT CHUNG

1. Tổ chức bộ máy
2. Nhân sự
3. Điều kiện hoạt động
4. Thông tin cần thiết khác

II. KẾT QUẢ NỔI BẬT

[...]

III. NHIỆM VỤ TRỌNG TÂM THỜI GIAN TỚI

1. Công tác tham mưu
2. Cơ chế, chính sách
3. Khoa học
4. Công nghệ và đổi mới sáng tạo
5. Chuyển đổi số
6. Tiêu chuẩn đo lường chất lượng
7. Kế hoạch - tài chính
8. Công tác nội bộ

IV. KHÓ KHĂN, VƯỚNG MẮC

[...]

V. KIẾN NGHỊ, ĐỀ XUẤT

[...]
```

---

# XXIX. CẤU TRÚC MẪU — BÁO CÁO TIẾN ĐỘ KẾ HOẠCH

```text
BÁO CÁO
Kết quả triển khai thực hiện [tên Kế hoạch/Chương trình]

Thực hiện [số, ký hiệu văn bản], Sở Khoa học và Công nghệ
báo cáo kết quả triển khai như sau:

1. Công tác chỉ đạo, điều hành

[...]

2. Kết quả triển khai thực hiện

Tổng số nhiệm vụ: [...]
Đã hoàn thành: [...]
Đang thực hiện: [...]
Chậm tiến độ: [...]

(Chi tiết tại Phụ lục kèm theo)

3. Phương hướng thực hiện

[...]

4. Khó khăn, vướng mắc, đề xuất, kiến nghị

[...]
```

---

# XXX. CẤU TRÚC MẪU — BÁO CÁO KẾT QUẢ HOẠT ĐỘNG CÓ CHỈ TIÊU

```text
BÁO CÁO
Kết quả [tên hoạt động/chương trình]

I. CÔNG TÁC BAN HÀNH THỂ CHẾ, CHÍNH SÁCH VÀ CHỈ ĐẠO,
TRIỂN KHAI THỰC HIỆN

1. Về ban hành thể chế, chính sách và công tác chỉ đạo
2. Công tác triển khai thực hiện
3. Công tác đào tạo, bồi dưỡng/tuyên truyền nếu có

II. KẾT QUẢ HOẠT ĐỘNG

1. Kết quả tổ chức thực hiện

[...]

2. Kết quả các chỉ tiêu

| STT | Chỉ tiêu đánh giá | Kết quả |
|---:|---|---:|
| 1 | [...] | [...] |
| 2 | [...] | [...] |

III. TỒN TẠI, HẠN CHẾ; KHÓ KHĂN, VƯỚNG MẮC

[...]

IV. ĐỀ XUẤT, KIẾN NGHỊ

[...]
```

---

# XXXI. QUY TẮC TỔNG HỢP NHIỀU PHÒNG/ĐƠN VỊ

Khi dữ liệu đầu vào do nhiều phòng cung cấp:

AI phải:

1. gom theo lĩnh vực;
2. loại bỏ nội dung trùng;
3. không cộng số liệu nếu chưa chắc các tập dữ liệu độc lập;
4. thống nhất thời điểm chốt số liệu;
5. giữ văn bản chứng minh quan trọng;
6. ưu tiên kết quả đầu ra thay vì liệt kê quá trình.

Schema:

```yaml
aggregation:
  group_by: "field"
  deduplicate: true
  sum_numbers_only_if_comparable: true
  preserve_evidence: true
```

---

# XXXII. QUY TẮC RÚT GỌN NỘI DUNG

Nếu báo cáo quá dài:

AI ưu tiên giữ:

1. kết quả chính;
2. số liệu;
3. sản phẩm đầu ra;
4. nhiệm vụ chậm;
5. khó khăn;
6. kiến nghị;
7. deadline quan trọng.

Có thể chuyển chi tiết sang phụ lục.

```yaml
if:
  report_too_long: true
then:
  move_task_details_to_appendix: true
```

---

# XXXIII. QUY TẮC VỀ PHỤ LỤC

Phụ lục phù hợp khi có:

* trên 10 nhiệm vụ;
* nhiều chỉ tiêu;
* nhiều địa phương;
* bảng tiến độ;
* sản phẩm đầu ra;
* trạng thái từng nhiệm vụ.

Phần thân báo cáo chỉ cần tổng hợp các kết quả đáng chú ý.

---

# XXXIV. PHONG CÁCH NGÔN NGỮ

AI SHOULD:

* viết hành chính, rõ ràng;
* ưu tiên câu chủ động;
* hạn chế tính từ đánh giá không có số liệu;
* dùng số liệu để chứng minh;
* tránh lặp lại một kết quả ở nhiều mục;
* dùng từ “đã”, “đang”, “chưa”, “hoàn thành”, “tiếp tục” đúng trạng thái.

AI SHOULD NOT:

* viết theo kiểu quảng bá;
* phóng đại kết quả;
* tự nhận xét “rất thành công”, “xuất sắc” nếu nguồn không có;
* tự tạo nguyên nhân;
* tự tạo kiến nghị.

---

# XXXV. QUY TẮC KIỂM TRA TRƯỚC KHI XUẤT

AI phải kiểm tra:

```yaml
final_checklist:

  document_type_correct: true

  subject_matches_content: true

  legal_basis_verified: true

  numbers_preserved: true

  reporting_period_consistent: true

  completed_and_pending_tasks_distinguished: true

  difficulties_supported_by_source: true

  recommendations_linked_to_difficulties: true

  recipient_correct: true

  signing_authority_checked: true

  appendix_consistent_with_body: true
```

---

# XXXVI. OUTPUT NỘI BỘ KHUYẾN NGHỊ

```yaml
report_draft:

  report_type: ""

  reporting_period:
    from: null
    to: null
    snapshot_date: null

  basis_documents: []

  title: ""

  sections: []

  statistics:
    total_tasks: null
    completed: null
    in_progress: null
    delayed: null

  highlights: []

  difficulties: []

  recommendations: []

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

# XXXVII. HARD RULES

AI MUST:

1. Xác định loại báo cáo trước khi chọn cấu trúc.
2. Giữ đúng số liệu nguồn.
3. Giữ đúng thời điểm chốt số liệu.
4. Phân biệt kết quả và phương hướng.
5. Phân biệt khó khăn và kiến nghị.
6. Nêu rõ nhiệm vụ chậm nếu nguồn thể hiện chậm.
7. Sử dụng phụ lục khi có nhiều nhiệm vụ.
8. Kiểm tra căn cứ trước khi viện dẫn.
9. Kiểm tra thẩm quyền ký trước khi điền tên người ký.
10. Không dùng báo cáo cũ làm nguồn số liệu cho báo cáo mới nếu chưa được xác nhận.

AI MUST NOT:

1. Tự tạo số báo cáo.
2. Tự tạo ngày ký.
3. Tự tạo số liệu.
4. Tự tạo tỷ lệ nếu không đủ dữ liệu.
5. Tự tạo căn cứ pháp lý.
6. Tự tạo khó khăn.
7. Tự tạo kiến nghị.
8. Tự sửa số liệu nguồn mà không có yêu cầu kiểm tra.
9. Tự chọn Giám đốc/Phó Giám đốc ký chỉ dựa vào mẫu cũ.
10. Sao chép tên người ký từ báo cáo mẫu sang báo cáo mới.
11. Sao chép “Nơi nhận” của báo cáo cũ nếu đối tượng nhận khác.
12. Sao chép nguyên trạng cấu trúc một báo cáo chuyên đề cho mọi loại báo cáo.

---

# XXXVIII. QUY TẮC CHỌN CẤU TRÚC TỰ ĐỘNG

```yaml
report_structure_router:

  if:
    reporting_cycle in ["month", "quarter", "six_month", "nine_month", "year"]:
    use: "BAO_CAO_DINH_KY"

  if:
    purpose == "report_progress_of_plan":
    use: "BAO_CAO_TIEN_DO"

  if:
    purpose == "report_specific_activity_with_metrics":
    use: "BAO_CAO_CHUYEN_DE"

  if:
    purpose == "serve_leadership_meeting":
    use: "BAO_CAO_PHUC_VU_LANH_DAO"

  if:
    purpose == "report_result_of_specific_task":
    use: "BAO_CAO_KET_QUA"

  if:
    purpose == "focus_on_obstacles_and_requests":
    use: "BAO_CAO_KHO_KHAN_KIEN_NGHI"
```

---

# XXXIX. QUY TRÌNH AI SOẠN BÁO CÁO

```text
YÊU CẦU / VĂN BẢN GIAO NHIỆM VỤ
          ↓
XÁC ĐỊNH LOẠI BÁO CÁO
          ↓
XÁC ĐỊNH KỲ / THỜI ĐIỂM CHỐT SỐ LIỆU
          ↓
XÁC ĐỊNH CĂN CỨ
          ↓
THU THẬP KẾT QUẢ
          ↓
PHÂN LOẠI:
HOÀN THÀNH / ĐANG LÀM / CHẬM
          ↓
TỔNG HỢP SỐ LIỆU
          ↓
XÁC ĐỊNH KẾT QUẢ NỔI BẬT
          ↓
XÁC ĐỊNH KHÓ KHĂN
          ↓
XÁC ĐỊNH PHƯƠNG HƯỚNG
          ↓
XÁC ĐỊNH KIẾN NGHỊ
          ↓
TẠO PHỤ LỤC NẾU CẦN
          ↓
KIỂM TRA NƠI NHẬN
          ↓
KIỂM TRA THẨM QUYỀN KÝ
          ↓
HOÀN THIỆN BÁO CÁO
```

---

# XL. NGUYÊN TẮC CUỐI

Một Báo cáo tốt phải trả lời được:

```text
CĂN CỨ GÌ?
↓
ĐÃ LÀM GÌ?
↓
KẾT QUẢ RA SAO?
↓
SỐ LIỆU NÀO CHỨNG MINH?
↓
CÒN VIỆC GÌ CHƯA XONG?
↓
VÌ SAO?
↓
SẮP TỚI LÀM GÌ?
↓
CẦN CẤP CÓ THẨM QUYỀN GIẢI QUYẾT GÌ?
```

Nguyên tắc:

```text
ĐÚNG CĂN CỨ
→ ĐÚNG KỲ BÁO CÁO
→ ĐÚNG SỐ LIỆU
→ ĐÚNG TRẠNG THÁI
→ ĐÚNG TRỌNG TÂM
→ ĐÚNG KIẾN NGHỊ
→ ĐÚNG NGƯỜI NHẬN
→ ĐÚNG THẨM QUYỀN KÝ
```

Nếu dữ liệu chưa đủ:

```text
KHÔNG BỊA SỐ LIỆU.
KHÔNG TỰ TẠO KẾT QUẢ.
KHÔNG TỰ TẠO KIẾN NGHỊ.
PHẢI ĐỂ TRỐNG HOẶC YÊU CẦU BỔ SUNG.
```

```

Bản này cố ý không biến một báo cáo cụ thể thành “mẫu cứng”. Ví dụ, báo cáo Kế hoạch 100 ngày dùng cấu trúc **chỉ đạo → kết quả → phương hướng → khó khăn/kiến nghị** và có phụ lục tiến độ; :contentReference[oaicite:4]{index=4} báo cáo Tổ Công nghệ số cộng đồng dùng cấu trúc **thể chế/chỉ đạo → kết quả có chỉ tiêu → tồn tại → kiến nghị**; :contentReference[oaicite:5]{index=5} còn báo cáo tháng đi theo **kết quả nổi bật → chi tiết theo lĩnh vực → nhiệm vụ kỳ tới**. :contentReference[oaicite:6]{index=6} Báo cáo phục vụ Phó Chủ tịch UBND tỉnh lại tập trung mạnh vào khái quát tổ chức, kết quả nổi bật, nhiệm vụ trọng tâm và các vấn đề cần lãnh đạo xem xét. :contentReference[oaicite:7]{index=7}

Vì vậy `bao_cao.md` này sẽ giúp ChatGPT **chọn đúng “biến thể” báo cáo theo mục đích**, thay vì sao chép một khuôn duy nhất cho mọi trường hợp.
```
