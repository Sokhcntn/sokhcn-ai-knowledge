Tôi đã đối chiếu 05 Giấy mời anh/chị vừa tải lên. Bộ mẫu này bao phủ khá tốt các tình huống thực tế của Sở: **mời họp thẩm định kinh phí nhiệm vụ KH&CN**, **mời Hội đồng xét đặt hàng**, **mời họp lấy ý kiến thẩm định dự án**, **mời làm việc với cơ quan chuyên môn**, và **mời họp Ban Giám đốc/giao ban nội bộ**. Các mẫu cho thấy phần thân Giấy mời thay đổi khá linh hoạt theo mục đích, nhưng các trường cốt lõi luôn xoay quanh **thành phần – chủ trì – thời gian – địa điểm – hình thức – nội dung – tài liệu – yêu cầu chuẩn bị**.     

Dưới đây là bản hoàn thiện cho:

`02_van_ban_mau/giay_moi.md`

````md
# MẪU VÀ QUY TẮC SOẠN GIẤY MỜI
## SỞ KHOA HỌC VÀ CÔNG NGHỆ TỈNH TÂY NINH

> File: `02_van_ban_mau/giay_moi.md`
>
> Vai trò:
> Đây là file mẫu và quy tắc nghiệp vụ để Trợ lý AI soạn Giấy mời
> của Sở Khoa học và Công nghệ tỉnh Tây Ninh.
>
> File này được chuẩn hóa từ các Giấy mời thực tế của Sở, gồm:
> - Giấy mời họp thẩm định kinh phí nhiệm vụ KH&CN;
> - Giấy mời Hội đồng xét đặt hàng nhiệm vụ KH&CN và đổi mới sáng tạo;
> - Giấy mời họp cho ý kiến thẩm định dự án;
> - Giấy mời làm việc, trao đổi với cơ quan chuyên môn;
> - Giấy mời họp Ban Giám đốc/giao ban nội bộ.
>
> Lưu ý:
> - File này là mẫu soạn thảo, không phải căn cứ xác định thẩm quyền.
> - Trước khi xác định người ký phải tra:
>   `01_thong_tin_sokhcn/phan_cong.md`
>   và
>   `01_thong_tin_sokhcn/quy_che_lam_viec.md`.
> - Không được sao chép người ký từ Giấy mời cũ sang Giấy mời mới.
> - Không được mặc định Phó Chánh Văn phòng có quyền ký TL. GIÁM ĐỐC
>   chỉ vì có một mẫu thực tế đã thể hiện như vậy; phải kiểm tra căn cứ ủy quyền
>   hoặc phân công cụ thể trước khi áp dụng.

---

# I. TEMPLATE METADATA

```yaml
template:
  id: GIAY_MOI_SKHCN
  document_type: "GIẤY MỜI"
  issuing_agency: "SỞ KHOA HỌC VÀ CÔNG NGHỆ"
  province: "TÂY NINH"
  symbol: "GM-SKHCN"
  language: "vi"
````

---

# II. CÁC LOẠI GIẤY MỜI HỆ THỐNG HỖ TRỢ

```yaml
invitation_types:

  GM_HOP_THAM_DINH_KINH_PHI:
    description: "Họp thẩm định kinh phí nhiệm vụ KH&CN"

  GM_HOI_DONG_KHCN:
    description: "Họp Hội đồng xét đặt hàng, tuyển chọn, tư vấn, đánh giá"

  GM_THAM_DINH_DU_AN:
    description: "Họp lấy ý kiến/thẩm định dự án, hồ sơ"

  GM_LAM_VIEC_TRAO_DOI:
    description: "Làm việc, trao đổi, thống nhất nội dung chuyên môn"

  GM_GIAO_BAN_NOI_BO:
    description: "Họp Ban Giám đốc, giao ban, họp nội bộ"

  GM_HOP_CHUYEN_DE:
    description: "Họp chuyên đề theo lĩnh vực"

  GM_HOP_TRUC_TUYEN:
    description: "Họp trực tuyến hoặc kết hợp trực tiếp - trực tuyến"
```

---

# III. THỂ THỨC CHUNG

## 1. Cơ quan ban hành

```text
UBND TỈNH TÂY NINH
SỞ KHOA HỌC VÀ CÔNG NGHỆ
```

---

## 2. Số, ký hiệu

```text
Số:      /GM-SKHCN
```

AI MUST NOT tự tạo số Giấy mời.

---

## 3. Quốc hiệu, tiêu ngữ

```text
CỘNG HÒA XÃ HỘI CHỦ NGHĨA VIỆT NAM
Độc lập - Tự do - Hạnh phúc
```

---

## 4. Địa danh, ngày tháng

```text
Tây Ninh, ngày ... tháng ... năm ...
```

Không tự điền ngày nếu người dùng chưa cung cấp hoặc chưa xác định.

---

# IV. TÊN LOẠI VÀ TRÍCH YẾU

Tên loại:

```text
GIẤY MỜI
```

In hoa, đậm, canh giữa.

Phần trích yếu đặt ngay dưới tên loại.

Ví dụ:

```text
Họp thẩm định kinh phí nhiệm vụ khoa học và công nghệ cấp tỉnh
“...”
```

hoặc:

```text
Tham dự Hội đồng xét đặt hàng nhiệm vụ
khoa học và công nghệ và đổi mới sáng tạo
“...”
```

hoặc:

```text
Họp cho ý kiến thẩm định dự án:
“...”
```

hoặc:

```text
Trao đổi, thống nhất một số nội dung liên quan đến triển khai
Kế hoạch ...
```

hoặc:

```text
Tham dự họp Ban Giám đốc tháng .../...
```

---

# V. NGUYÊN TẮC VIẾT TRÍCH YẾU

Trích yếu phải trả lời:

```text
MỜI HỌP VIỆC GÌ?
```

Không nên chỉ ghi:

```text
GIẤY MỜI HỌP
```

nếu có thể xác định rõ nội dung.

Ưu tiên:

```yaml
subject_should_include:
  - meeting_purpose
  - project_or_task_name_if_relevant
  - period_if_internal_meeting
```

---

# VI. KÍNH GỬI

## 1. Một cơ quan

```text
Kính gửi: [Tên cơ quan].
```

## 2. Nhiều cơ quan/đối tượng

```text
Kính gửi:
- [Cơ quan/đối tượng 1];
- [Cơ quan/đối tượng 2];
- [Cơ quan/đối tượng 3].
```

## 3. Hội đồng/Tổ thẩm định

```text
Kính gửi:
- Thành viên [Hội đồng/Tổ thẩm định];
- [Đơn vị chủ trì];
- [Chủ nhiệm nhiệm vụ].
```

## 4. Họp nội bộ

Có thể không cần phần `Kính gửi` nếu phần thành phần đã được trình bày trực tiếp trong nội dung.

---

# VII. CÁCH VIẾT PHẦN MỞ ĐẦU

## Mẫu 1 — Có Quyết định thành lập Hội đồng/Tổ

```text
Căn cứ Quyết định số [số/ký hiệu] ngày [ngày]
của Sở Khoa học và Công nghệ về việc [nội dung].
```

---

## Mẫu 2 — Có Tờ trình/hồ sơ cần thẩm định

```text
Sở Khoa học và Công nghệ nhận được Tờ trình số [số]
ngày [ngày] của [cơ quan] về việc [nội dung].
```

---

## Mẫu 3 — Có Kế hoạch/Chỉ đạo của UBND tỉnh

```text
Thực hiện Kế hoạch số [số] ngày [ngày]
của UBND tỉnh về [nội dung].
```

---

## Mẫu 4 — Họp nội bộ định kỳ

```text
Thực hiện Quy chế làm việc của Sở Khoa học và Công nghệ
và [quy trình/kế hoạch có liên quan], Sở tổ chức cuộc họp
[Ban Giám đốc/giao ban] như sau:
```

---

# VIII. CÁC TRƯỜNG THÔNG TIN CỐT LÕI

Mọi Giấy mời nên xác định tối đa các trường sau:

```yaml
meeting:
  purpose: ""
  participants: []
  chair: null
  date: null
  start_time: null
  end_time: null
  location: null
  format: null
  agenda: []
  materials: []
  preparation_requirements: []
  contact: null
```

Không bắt buộc trường nào cũng xuất hiện nếu không cần.

---

# IX. THÀNH PHẦN THAM DỰ

Có thể ghi:

```text
1. Thành phần tham dự:
- Đại diện lãnh đạo ...
- Chuyên viên phụ trách ...
- Thành viên Hội đồng ...
```

Hoặc ghi ngay ở `Kính gửi`.

AI phải phân biệt:

```text
Kính gửi
≠
Nơi nhận
≠
Thành phần tham dự
```

---

# X. CHỦ TRÌ

Nếu xác định rõ:

```text
Chủ trì: Ông/Bà [họ tên], [chức vụ].
```

hoặc:

```text
Chủ trì: [Chức danh].
```

AI MUST NOT tự tạo người chủ trì.

Phải dựa trên:

* Quyết định thành lập Hội đồng/Tổ;
* phân công lãnh đạo;
* yêu cầu của lãnh đạo;
* lịch họp chính thức.

---

# XI. THỜI GIAN

Mẫu:

```text
Thời gian: 14 giờ 00 phút, ngày .../.../... (...).
```

hoặc:

```text
Thời gian: Từ 07 giờ 00 đến 07 giờ 30, ngày ...
```

AI phải:

* giữ đúng giờ;
* giữ đúng ngày;
* không tự suy diễn thứ nếu không chắc;
* nếu ghi thứ thì phải bảo đảm khớp ngày.

---

# XII. ĐỊA ĐIỂM

Mẫu:

```text
Địa điểm: Phòng họp trực tuyến lầu 3,
Sở Khoa học và Công nghệ,
số 367 Quốc lộ 1, phường Long An, tỉnh Tây Ninh.
```

Nếu có nhiều cơ sở:

```text
Địa điểm:
- Cơ sở 1: [...]
- Cơ sở 2: [...]
```

Không sao chép địa chỉ cũ sang cuộc họp khác nếu chưa xác nhận.

---

# XIII. HÌNH THỨC HỌP

Giá trị chuẩn:

```yaml
meeting_format:
  - DIRECT
  - ONLINE
  - HYBRID
```

Khi xuất:

```text
Hình thức: Trực tiếp.
```

hoặc:

```text
Hình thức: Trực tuyến.
```

hoặc:

```text
Hình thức: Trực tiếp và trực tuyến.
```

---

# XIV. LINK HỌP TRỰC TUYẾN

Nếu có:

```text
Đường dẫn họp trực tuyến: [...]
Mã cuộc họp: [...]
Mật khẩu: [...]
```

AI không được tự tạo link họp.

---

# XV. NỘI DUNG CUỘC HỌP

Có thể ghi:

```text
Nội dung: [Nội dung chính].
```

Hoặc chi tiết:

```text
5. Nội dung cuộc họp:
- [...]
- [...]
```

Nếu họp thẩm định:

nên nêu rõ nội dung từng cơ quan cần cho ý kiến nếu nguồn xác định.

---

# XVI. GIẤY MỜI HỌP THẨM ĐỊNH KINH PHÍ

Áp dụng khi:

* có Tổ thẩm định;
* có nhiệm vụ KH&CN;
* đơn vị chủ trì/chủ nhiệm tham dự.

Cấu trúc:

```text
GIẤY MỜI
Họp thẩm định kinh phí nhiệm vụ khoa học và công nghệ
“[Tên nhiệm vụ]”

Kính gửi:
- Thành viên Tổ thẩm định kinh phí;
- [Tổ chức chủ trì];
- [Chủ nhiệm nhiệm vụ].

Căn cứ Quyết định số [...] về việc thành lập Tổ thẩm định kinh phí.

Sở Khoa học và Công nghệ trân trọng kính mời
các thành phần nêu trên tham dự họp thẩm định kinh phí nhiệm vụ.

- Tên nhiệm vụ: [...]
- Thời gian: [...]
- Địa điểm: [...]
- Hình thức: [...]

Đề nghị:
- Thành viên Tổ thẩm định tham dự đầy đủ;
- Tổ chức chủ trì và Chủ nhiệm chuẩn bị nội dung;
- Báo cáo phần đã chỉnh sửa nếu có;
- Trình bày dự toán kinh phí thực hiện nhiệm vụ.

Trân trọng./.
```

---

# XVII. GIẤY MỜI HỘI ĐỒNG KHOA HỌC

Áp dụng cho:

* xét đặt hàng;
* tuyển chọn;
* giao trực tiếp;
* đánh giá;
* nghiệm thu;
* tư vấn.

Cấu trúc:

```text
GIẤY MỜI
Tham dự Hội đồng [loại Hội đồng]
“[Tên nhiệm vụ]”

Sở Khoa học và Công nghệ trân trọng kính mời:

- Thành viên Hội đồng
  (theo Quyết định số ...).

Tham dự họp Hội đồng [nội dung].

Nhiệm vụ do [đơn vị] đăng ký/chủ trì,
[ông/bà] đăng ký/chủ nhiệm nhiệm vụ.

- Thời gian: [...]
- Chủ trì: [...]
- Địa điểm: [...]
- Hình thức: [...]

Đề nghị các thành viên sắp xếp tham dự đầy đủ./.
```

---

# XVIII. GIẤY MỜI THẨM ĐỊNH DỰ ÁN

Áp dụng khi:

* cần lấy ý kiến nhiều cơ quan;
* có hồ sơ dự án;
* mỗi cơ quan có trách nhiệm góp ý theo lĩnh vực.

Cấu trúc:

```text
GIẤY MỜI
Họp cho ý kiến thẩm định dự án:
“[Tên dự án]”

Kính gửi:
- [...]
- [...]

Sở Khoa học và Công nghệ nhận được
[Tờ trình/Hồ sơ] số [...] ngày [...] của [cơ quan].

Để có cơ sở tổng hợp, tham mưu cấp có thẩm quyền
phê duyệt dự án theo quy định, Sở Khoa học và Công nghệ
trân trọng kính mời các cơ quan tham dự cuộc họp như sau:

1. Thành phần tham dự:
[...]

2. Thời gian:
[...]

3. Hình thức, địa điểm:
[...]

4. Chủ trì:
[...]

5. Nội dung cuộc họp:
[...]

6. Tài liệu phục vụ họp:
[...]

Đề nghị các đơn vị nghiên cứu trước hồ sơ,
tham dự đầy đủ và chuẩn bị ý kiến cụ thể.
```

---

# XIX. PHÂN CÔNG NỘI DUNG CHO TỪNG CƠ QUAN

Nếu cuộc họp yêu cầu nhiều cơ quan cho ý kiến chuyên môn:

AI có thể trình bày:

```text
* [Cơ quan 1]:
Cho ý kiến về [...]

* [Cơ quan 2]:
Cho ý kiến về [...]

* [Chủ đầu tư]:
- Chuẩn bị [...]
- Giải trình [...]
- Hoàn thiện [...]
```

Chỉ sử dụng nếu nguồn/yêu cầu xác định rõ.

Không tự phân công nhiệm vụ cho cơ quan khác.

---

# XX. GIẤY MỜI LÀM VIỆC / TRAO ĐỔI

Áp dụng khi Sở mời một hoặc vài cơ quan đến trao đổi chuyên môn.

Cấu trúc:

```text
GIẤY MỜI
Trao đổi, thống nhất một số nội dung liên quan đến [nội dung]

Kính gửi: [Cơ quan].

Thực hiện [Kế hoạch/Công văn nếu có].

Sở Khoa học và Công nghệ trân trọng kính mời
đại diện lãnh đạo và cán bộ chuyên môn của [cơ quan]
đến dự buổi làm việc.

Chủ trì: [...]
Thời gian: [...]
Địa điểm: [...]
Nội dung: [...]

Đề nghị đại biểu nghiên cứu trước tài liệu kèm theo
và tham dự đúng thành phần, thời gian.

Trân trọng./.
```

---

# XXI. GIẤY MỜI GIAO BAN / BAN GIÁM ĐỐC

Áp dụng cho họp nội bộ.

Cấu trúc:

```text
GIẤY MỜI
Tham dự họp Ban Giám đốc tháng .../...

Thực hiện Quy chế làm việc của Sở và
[quy trình/kế hoạch nếu có], Sở tổ chức cuộc họp
Ban Giám đốc như sau:

1. Thời gian:
[...]

2. Địa điểm:
[...]

3. Nội dung, thời gian và thành phần tham dự:

3.1. [Nội dung 1]
- Thời gian: [...]
- Thành phần: [...]

3.2. [Nội dung 2]
- Thời gian: [...]
- Thành phần: [...]

Đề nghị các đồng chí tham dự đúng thành phần,
thời gian quy định.

[Tài liệu họp được tải lên hệ thống họp không giấy nếu có.]

Trân trọng./.
```

---

# XXII. LỊCH HỌP NHIỀU NỘI DUNG

Nếu một Giấy mời có nhiều phiên:

```yaml
agenda:
  - item: 1
    title: ""
    from: ""
    to: ""
    participants: []

  - item: 2
    title: ""
    from: ""
    to: ""
    participants: []
```

Khi xuất:

```text
3.1. [Nội dung]
- Thời gian: Từ ... đến ...
- Thành phần: ...

3.2. [Nội dung]
- Thời gian: Từ ... đến ...
- Thành phần: ...
```

---

# XXIII. TÀI LIỆU PHỤC VỤ HỌP

Có thể ghi:

```text
Tài liệu phục vụ họp:
- Hồ sơ dự án đính kèm;
- Thuyết minh nhiệm vụ;
- Dự toán kinh phí;
- Phiếu nhận xét;
- Tài liệu tải trên hệ thống họp không giấy.
```

AI không được tự nói “đính kèm” nếu thực tế không có tài liệu.

---

# XXIV. YÊU CẦU CHUẨN BỊ

Có thể gồm:

```text
- Nghiên cứu trước tài liệu;
- Chuẩn bị ý kiến;
- Chuẩn bị báo cáo;
- Chuẩn bị hồ sơ;
- Cử đúng thành phần;
- Cử đầu mối;
- Chuẩn bị giải trình.
```

Mỗi yêu cầu phải có nguồn hoặc căn cứ từ mục đích cuộc họp.

---

# XXV. CÁCH KẾT THÚC

## Mẫu 1

```text
Để buổi làm việc đạt kết quả cao,
Sở Khoa học và Công nghệ đề nghị các đại biểu
sắp xếp tham dự đầy đủ, đúng thành phần.

Trân trọng./.
```

## Mẫu 2

```text
Đề nghị các cơ quan, đơn vị nghiên cứu trước hồ sơ,
tham dự đầy đủ và chuẩn bị ý kiến cụ thể.

Sở Khoa học và Công nghệ rất mong nhận được
sự quan tâm, phối hợp của các đơn vị./.
```

## Mẫu 3 — Nội bộ

```text
Đề nghị các đồng chí tham dự họp đúng thành phần,
giờ quy định.

Trân trọng./.
```

---

# XXVI. GIẤY MỜI THAY THẾ GIẤY MỜI TRƯỚC

Nếu có thay đổi:

```text
Giấy mời này thay thế Giấy mời số .../GM-SKHCN
ngày ... tháng ... năm ... của Sở Khoa học và Công nghệ.
```

AI MUST NOT tự dùng câu này nếu không có Giấy mời trước đó.

---

# XXVII. NƠI NHẬN

Mẫu cơ bản:

```text
Nơi nhận:
- Như trên;
- GĐ, các PGĐ Sở;
- [Đơn vị chuẩn bị phòng họp nếu có];
- [Phòng/đơn vị liên quan];
- Lưu: VT, [...].
```

Đối với họp nội bộ:

```text
Nơi nhận:
- Như trên;
- Lưu: VT, VP.
```

AI không được sao chép nguyên `Nơi nhận` của mẫu cũ.

---

# XXVIII. ĐƠN VỊ PHỤC VỤ HỌP

Nếu có phân công:

```text
- Văn phòng Sở (bố trí phòng họp);
```

hoặc:

```text
- Văn phòng Sở
  (bố trí phòng họp, kết nối trực tuyến, phương tiện...);
```

Chỉ ghi khi thực sự có giao nhiệm vụ.

---

# XXIX. KHỐI KÝ

## 1. Giám đốc

```text
GIÁM ĐỐC


[Họ và tên]
```

---

## 2. Phó Giám đốc ký thay

```text
KT. GIÁM ĐỐC
PHÓ GIÁM ĐỐC


[Họ và tên]
```

---

## 3. Chánh Văn phòng ký thừa lệnh

Theo Quy chế, Giấy mời thông thường có thể thuộc phạm vi Chánh Văn phòng được ký thừa lệnh, trừ trường hợp cuộc họp quan trọng hoặc thành phần mời thuộc nhóm cần lãnh đạo Sở ký.

```text
TL. GIÁM ĐỐC
CHÁNH VĂN PHÒNG


[Họ và tên]
```

---

# XXX. CẢNH BÁO VỀ PHÓ CHÁNH VĂN PHÒNG KÝ TL.

Trong một Giấy mời nội bộ thực tế có hình thức:

```text
TL. GIÁM ĐỐC
PHÓ CHÁNH VĂN PHÒNG
```

AI phải coi đây là:

```yaml
observed_in_sample: true
general_rule: false
```

Không được suy ra rằng mọi Phó Chánh Văn phòng đều có quyền ký thừa lệnh.

Trước khi sử dụng phải có:

* văn bản ủy quyền;
* phân công cụ thể;
* quy chế/quy định hiện hành khác;
* hoặc chỉ đạo hợp lệ.

Nếu chưa có căn cứ:

```yaml
signing:
  status: "CAN_KIEM_TRA_THEM"
```

---

# XXXI. LOGIC XÁC ĐỊNH NGƯỜI KÝ

```text
LOẠI GIẤY MỜI
      ↓
MỨC ĐỘ CUỘC HỌP
      ↓
THÀNH PHẦN ĐƯỢC MỜI
      ↓
CHỦ TRÌ CUỘC HỌP
      ↓
ĐƠN VỊ CHỦ TRÌ SOẠN
      ↓
phan_cong.md
      ↓
quy_che_lam_viec.md
      ↓
KIỂM TRA ỦY QUYỀN
      ↓
ĐỀ XUẤT NGƯỜI KÝ
```

---

# XXXII. GIẤY MỜI THÔNG THƯỜNG VÀ GIẤY MỜI QUAN TRỌNG

## Giấy mời thông thường

Ví dụ:

* họp nội bộ;
* trao đổi chuyên môn;
* làm việc cấp phòng;
* cuộc họp thông thường.

Có thể xem xét:

```text
TL. GIÁM ĐỐC
CHÁNH VĂN PHÒNG
```

nếu đúng phạm vi Quy chế.

## Giấy mời quan trọng

Ví dụ có thể gồm:

* Hội đồng KH&CN quan trọng;
* họp có lãnh đạo tỉnh;
* họp có nhiều cơ quan cấp tỉnh;
* cuộc họp do Giám đốc/Phó Giám đốc chủ trì;
* nội dung có tính quyết định/thẩm định lớn.

AI không được mặc định Chánh Văn phòng ký.

Phải kiểm tra thẩm quyền cụ thể.

---

# XXXIII. MẪU GIẤY MỜI CHUNG

```text
UBND TỈNH TÂY NINH
SỞ KHOA HỌC VÀ CÔNG NGHỆ

Số:      /GM-SKHCN

CỘNG HÒA XÃ HỘI CHỦ NGHĨA VIỆT NAM
Độc lập - Tự do - Hạnh phúc

Tây Ninh, ngày ... tháng ... năm ...

GIẤY MỜI
[NỘI DUNG CUỘC HỌP]

Kính gửi:
- [...];
- [...].

[Căn cứ/lý do tổ chức.]

Sở Khoa học và Công nghệ trân trọng kính mời
[cơ quan/đại biểu] tham dự cuộc họp, cụ thể:

1. Thành phần:
[...]

2. Thời gian:
[...]

3. Địa điểm:
[...]

4. Hình thức:
[...]

5. Chủ trì:
[...]

6. Nội dung:
[...]

7. Tài liệu/yêu cầu chuẩn bị:
[...]

Đề nghị các đại biểu nghiên cứu trước tài liệu,
tham dự đầy đủ, đúng thành phần và thời gian.

Trân trọng./.

Nơi nhận:
- Như trên;
- GĐ, các PGĐ Sở;
- [...];
- Lưu: VT, [...].

[CHỨC DANH NGƯỜI KÝ]


[HỌ VÀ TÊN]
```

---

# XXXIV. MẪU GIẤY MỜI HỌP THẨM ĐỊNH

```text
GIẤY MỜI
Họp thẩm định [nội dung]
“[Tên nhiệm vụ/dự án]”

Kính gửi:
- [...];
- [...].

Căn cứ [Quyết định/Tờ trình/văn bản].

Sở Khoa học và Công nghệ trân trọng kính mời
các thành phần tham dự cuộc họp thẩm định:

- Thời gian: [...]
- Địa điểm: [...]
- Hình thức: [...]
- Chủ trì: [...]

Nội dung:
[...]

Đề nghị các đơn vị/đại biểu:
- Nghiên cứu trước hồ sơ;
- Chuẩn bị ý kiến;
- Chuẩn bị báo cáo/giải trình nếu có.

Trân trọng./.
```

---

# XXXV. MẪU GIẤY MỜI LÀM VIỆC

```text
GIẤY MỜI
Trao đổi, thống nhất [nội dung]

Kính gửi: [Cơ quan].

Thực hiện [Kế hoạch/Công văn].

Sở Khoa học và Công nghệ trân trọng kính mời
đại diện lãnh đạo và cán bộ chuyên môn của [cơ quan]
đến dự buổi làm việc.

Chủ trì: [...]
Thời gian: [...]
Địa điểm: [...]
Nội dung: [...]

Đề nghị đại biểu nghiên cứu trước tài liệu kèm theo
và tham dự đúng thành phần, thời gian.

Trân trọng./.
```

---

# XXXVI. MẪU GIẤY MỜI HỌP BAN GIÁM ĐỐC

```text
GIẤY MỜI
Tham dự họp Ban Giám đốc tháng .../...

Thực hiện Quy chế làm việc của Sở,
Sở Khoa học và Công nghệ tổ chức cuộc họp Ban Giám đốc như sau:

1. Thời gian:
[...]

2. Địa điểm:
[...]

3. Nội dung, thời gian và thành phần:

3.1. [...]
- Thời gian: [...]
- Thành phần: [...]

3.2. [...]
- Thời gian: [...]
- Thành phần: [...]

Đề nghị các đồng chí tham dự đúng thành phần,
thời gian quy định.

[Tài liệu họp được tải lên hệ thống họp không giấy.]

Trân trọng./.
```

---

# XXXVII. QUY TẮC DÙNG CĂN CỨ

AI chỉ dùng căn cứ khi:

* cuộc họp được tổ chức trên cơ sở văn bản;
* Hội đồng/Tổ được thành lập bằng Quyết định;
* có Tờ trình/hồ sơ cần xử lý;
* có Kế hoạch/chỉ đạo giao nhiệm vụ.

Không phải mọi Giấy mời đều cần nhiều dòng “Căn cứ”.

---

# XXXVIII. QUY TẮC VỀ TÊN NHIỆM VỤ/DỰ ÁN

AI MUST:

* giữ nguyên tên nhiệm vụ;
* giữ nguyên tên dự án;
* giữ nguyên tên Hội đồng/Tổ;
* không tự rút gọn tên nếu có thể gây thay đổi nghĩa.

---

# XXXIX. QUY TẮC VỀ THỜI GIAN

AI phải kiểm tra:

```yaml
time_check:
  date_present: true
  time_present: true
  weekday_consistent: true
  start_before_end: true
```

Nếu không chắc thứ trong tuần:

không tự thêm.

---

# XL. QUY TẮC VỀ THÀNH PHẦN

Nếu mời:

```text
Đại diện lãnh đạo và chuyên viên phụ trách chuyên môn
```

AI phải giữ đúng mức thành phần.

Không tự nâng thành:

```text
Thủ trưởng cơ quan
```

hoặc hạ xuống:

```text
Chuyên viên
```

nếu nguồn không quy định.

---

# XLI. QUY TẮC VỀ HỌP TRỰC TUYẾN

Nếu hình thức trực tuyến/hybrid:

AI phải xác định nếu có:

* địa điểm đầu cầu;
* nền tảng họp;
* đường dẫn;
* thiết bị;
* đơn vị hỗ trợ kỹ thuật.

Không tự tạo thông tin kết nối.

---

# XLII. QUY TẮC VỀ TÀI LIỆU HỌP KHÔNG GIẤY

Nếu có:

```text
Tài liệu họp được tải lên hệ thống họp không giấy.
```

Chỉ sử dụng khi đã xác nhận thực tế.

---

# XLIII. OUTPUT NỘI BỘ KHUYẾN NGHỊ

```yaml
invitation_draft:

  invitation_type: ""

  title: ""

  basis_documents: []

  invitees: []

  participants: []

  chair:
    name: null
    role: null

  schedule:
    date: null
    start_time: null
    end_time: null
    weekday: null

  location:
    primary: null
    secondary: []

  format:
    value: null

  agenda: []

  materials: []

  preparation_requirements: []

  contact:
    name: null
    unit: null
    phone: null

  replacement_notice:
    replaces_previous_invitation: false
    previous_number: null
    previous_date: null

  signing:
    proposed_signer: null
    signing_form: null
    authorization_required: false
    status: "CAN_KIEM_TRA"

  confidence: "high | medium | low"
```

---

# XLIV. ROUTING LOẠI GIẤY MỜI

```yaml
invitation_router:

  if:
    purpose == "appraise_science_budget"
  then:
    type: GM_HOP_THAM_DINH_KINH_PHI

  if:
    purpose in [
      "science_council",
      "order_selection",
      "selection",
      "evaluation"
    ]
  then:
    type: GM_HOI_DONG_KHCN

  if:
    purpose == "project_appraisal"
  then:
    type: GM_THAM_DINH_DU_AN

  if:
    purpose == "professional_working_session"
  then:
    type: GM_LAM_VIEC_TRAO_DOI

  if:
    purpose in [
      "board_meeting",
      "internal_briefing"
    ]
  then:
    type: GM_GIAO_BAN_NOI_BO
```

---

# XLV. FINAL CHECKLIST

Trước khi xuất Giấy mời, AI phải kiểm tra:

```yaml
final_checklist:

  invitation_type_correct: true

  subject_clear: true

  invitees_verified: true

  participants_verified: true

  chair_verified: true

  date_verified: true

  time_verified: true

  weekday_verified_if_present: true

  location_verified: true

  meeting_format_verified: true

  agenda_verified: true

  materials_verified: true

  preparation_requirements_verified: true

  signer_checked_with_assignment: true

  signer_checked_with_work_rules: true

  authorization_checked_if_needed: true

  recipients_copy_verified: true
```

---

# XLVI. HARD RULES

AI MUST:

1. Xác định mục đích cuộc họp trước khi soạn.
2. Xác định đúng đối tượng mời.
3. Xác định đúng thời gian, địa điểm.
4. Xác định chủ trì nếu có.
5. Giữ nguyên tên nhiệm vụ/dự án.
6. Nêu rõ yêu cầu chuẩn bị nếu có.
7. Kiểm tra tài liệu đính kèm.
8. Kiểm tra thẩm quyền ký.
9. Kiểm tra nơi nhận.
10. Kiểm tra Giấy mời có thay thế Giấy mời trước hay không.

AI MUST NOT:

1. Tự tạo số Giấy mời.
2. Tự tạo ngày.
3. Tự tạo thời gian họp.
4. Tự tạo địa điểm.
5. Tự tạo thành phần.
6. Tự tạo Chủ trì.
7. Tự tạo link họp.
8. Tự tạo tài liệu kèm.
9. Tự chọn người ký.
10. Sao chép chữ ký từ Giấy mời mẫu.
11. Sao chép địa điểm từ cuộc họp cũ sang cuộc họp mới.
12. Tự phân công nhiệm vụ cho cơ quan khác.
13. Tự dùng “TL. GIÁM ĐỐC – PHÓ CHÁNH VĂN PHÒNG” nếu chưa có căn cứ cụ thể.

---

# XLVII. STOP CONDITIONS

AI phải dừng hoặc để trường trống nếu:

```yaml
stop_conditions:

  - "Không xác định được mục đích cuộc họp"

  - "Không xác định được thành phần mời"

  - "Không có ngày hoặc giờ họp"

  - "Không xác định được địa điểm"

  - "Không xác định được Chủ trì trong trường hợp bắt buộc phải nêu"

  - "Có Hội đồng/Tổ nhưng chưa có thông tin Quyết định thành lập"

  - "Không rõ Giấy mời mới có thay thế Giấy mời cũ hay không"

  - "Không đủ căn cứ xác định người ký"

  - "Dự kiến ký TL. bởi Phó Chánh Văn phòng nhưng chưa có căn cứ ủy quyền"
```

Output:

```text
Chưa đủ thông tin để hoàn thiện Giấy mời.
Cần bổ sung hoặc kiểm tra thêm thành phần, thời gian,
địa điểm, chủ trì hoặc thẩm quyền ký trước khi phát hành dự thảo.
```

---

# XLVIII. QUY TRÌNH AI SOẠN GIẤY MỜI

```text
YÊU CẦU TỔ CHỨC HỌP
        ↓
XÁC ĐỊNH MỤC ĐÍCH CUỘC HỌP
        ↓
XÁC ĐỊNH LOẠI GIẤY MỜI
        ↓
XÁC ĐỊNH CĂN CỨ
        ↓
XÁC ĐỊNH THÀNH PHẦN MỜI
        ↓
XÁC ĐỊNH CHỦ TRÌ
        ↓
XÁC ĐỊNH THỜI GIAN
        ↓
XÁC ĐỊNH ĐỊA ĐIỂM
        ↓
XÁC ĐỊNH HÌNH THỨC
        ↓
XÁC ĐỊNH NỘI DUNG
        ↓
XÁC ĐỊNH TÀI LIỆU
        ↓
XÁC ĐỊNH YÊU CẦU CHUẨN BỊ
        ↓
TRA phan_cong.md
        ↓
TRA quy_che_lam_viec.md
        ↓
KIỂM TRA THẨM QUYỀN KÝ
        ↓
HOÀN THIỆN NƠI NHẬN
        ↓
XUẤT GIẤY MỜI
```

---

# XLIX. NGUYÊN TẮC CUỐI

Một Giấy mời tốt phải trả lời rõ:

```text
MỜI AI?
↓
HỌP VIỆC GÌ?
↓
AI CHỦ TRÌ?
↓
HỌP LÚC NÀO?
↓
Ở ĐÂU?
↓
TRỰC TIẾP HAY TRỰC TUYẾN?
↓
PHẢI CHUẨN BỊ GÌ?
↓
CÓ TÀI LIỆU KÈM KHÔNG?
↓
AI CÓ THẨM QUYỀN KÝ?
```

Nguyên tắc:

```text
ĐÚNG MỤC ĐÍCH
→ ĐÚNG THÀNH PHẦN
→ ĐÚNG CHỦ TRÌ
→ ĐÚNG THỜI GIAN
→ ĐÚNG ĐỊA ĐIỂM
→ ĐÚNG HÌNH THỨC
→ ĐÚNG NỘI DUNG
→ ĐÚNG TÀI LIỆU
→ ĐÚNG THẨM QUYỀN KÝ
```

Nếu chưa đủ dữ liệu:

```text
KHÔNG BỊA THỜI GIAN.
KHÔNG BỊA ĐỊA ĐIỂM.
KHÔNG BỊA THÀNH PHẦN.
KHÔNG TỰ CHỌN NGƯỜI KÝ.
ĐỂ TRỐNG HOẶC YÊU CẦU BỔ SUNG.
```

```

Có một điểm quan trọng tôi đã chủ động xử lý trong file này: mẫu họp Ban Giám đốc thực tế có khối ký **“TL. GIÁM ĐỐC – PHÓ CHÁNH VĂN PHÒNG”**. :contentReference[oaicite:5]{index=5} Trong khi quy tắc chúng ta đã chuẩn hóa từ `quy_che_lam_viec.md` chỉ xác định phạm vi ký thừa lệnh của **Chánh Văn phòng** đối với giấy mời thông thường. Vì vậy tôi không biến trường hợp thực tế đó thành quy tắc chung; hệ thống chỉ được dùng lại khi có căn cứ ủy quyền/phân công cụ thể. Đây là cách an toàn hơn để repo không “học nhầm” một trường hợp cá biệt thành thẩm quyền mặc định.
```
