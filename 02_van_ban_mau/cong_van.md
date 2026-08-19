# MẪU VÀ QUY TẮC SOẠN CÔNG VĂN
## SỞ KHOA HỌC VÀ CÔNG NGHỆ TỈNH TÂY NINH

> File: `02_van_ban_mau/cong_van.md`
>
> Vai trò:
> Đây là file mẫu và quy tắc nghiệp vụ để Trợ lý AI soạn các loại công văn
> của Sở Khoa học và Công nghệ tỉnh Tây Ninh.
>
> File này được chuẩn hóa từ các công văn thực tế của Sở, gồm các nhóm:
> - Công văn đề nghị/phối hợp triển khai nhiệm vụ;
> - Công văn hướng dẫn thực hiện;
> - Công văn góp ý dự thảo;
> - Công văn phúc đáp tổ chức/doanh nghiệp;
> - Công văn lấy ý kiến Thành viên UBND tỉnh;
> - Công văn kiểm tra tiến độ nhiệm vụ KH&CN;
> - Công văn tài chính, thu hồi công nợ;
> - Công văn gửi kèm phụ lục/phiếu thông tin/hướng dẫn.
>
> Lưu ý:
> - File này là mẫu soạn thảo, không phải căn cứ xác định thẩm quyền.
> - Trước khi xác định người ký phải tra:
>   `01_thong_tin_sokhcn/phan_cong.md`
>   và
>   `01_thong_tin_sokhcn/quy_che_lam_viec.md`.
> - Không được sao chép người ký từ công văn mẫu cũ sang văn bản mới.

---

# I. TEMPLATE METADATA

```yaml
template:
  id: CONG_VAN_SKHCN
  document_type: "CÔNG VĂN"
  issuing_agency: "SỞ KHOA HỌC VÀ CÔNG NGHỆ"
  province: "TÂY NINH"
  language: "vi"
````

---

# II. CÁC LOẠI CÔNG VĂN HỆ THỐNG HỖ TRỢ

```yaml
cong_van_types:

  CONG_VAN_DE_NGHI:
    description: "Đề nghị cơ quan, tổ chức phối hợp hoặc thực hiện nhiệm vụ"

  CONG_VAN_TRIEN_KHAI:
    description: "Triển khai nhiệm vụ, văn bản chỉ đạo, kế hoạch"

  CONG_VAN_HUONG_DAN:
    description: "Hướng dẫn cơ quan, đơn vị thực hiện nội dung chuyên môn"

  CONG_VAN_GOP_Y:
    description: "Góp ý dự thảo văn bản, đề án, kế hoạch"

  CONG_VAN_PHUC_DAP:
    description: "Phúc đáp công văn, đề nghị của tổ chức, doanh nghiệp"

  CONG_VAN_LAY_Y_KIEN_TV_UBND:
    description: "Gửi ý kiến Thành viên UBND tỉnh"

  CONG_VAN_KIEM_TRA:
    description: "Thông báo và tổ chức kiểm tra, đánh giá, kiểm tra tiến độ"

  CONG_VAN_TAI_CHINH:
    description: "Thu hồi công nợ, thanh toán, kinh phí, tài chính"

  CONG_VAN_CO_PHU_LUC:
    description: "Công văn có phụ lục, biểu mẫu, phiếu thông tin hoặc hướng dẫn kèm theo"

  CONG_VAN_TRAO_DOI:
    description: "Trao đổi công việc, cung cấp thông tin, phối hợp"
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

Cấu trúc chung:

```text
Số:      /SKHCN-[MÃ ĐƠN VỊ]
```

Ví dụ thực tế:

```text
/SKHCN-CĐS
/SKHCN-KH
/SKHCN-KHTC
/SKHCN-TĐC
/SKHCN-CN&ĐMST
/SKHCN-VP
/SKHCN-TTKHCN
```

AI MUST NOT tự tạo số công văn.

Chỉ được điền mã đơn vị nếu đã xác định chắc chắn đơn vị chủ trì.

---

## 3. Trích yếu

Đặt dưới số, ký hiệu.

Bắt đầu bằng:

```text
V/v ...
```

Trích yếu phải:

* ngắn gọn;
* phản ánh đúng hành động chính;
* không kể lại toàn bộ nội dung;
* ưu tiên động từ hành chính rõ ràng.

Ví dụ:

```text
V/v xây dựng từ điển dữ liệu theo Công văn số ...
```

```text
V/v góp ý dự thảo Tờ trình, Quyết định của UBND tỉnh
```

```text
V/v phúc đáp doanh nghiệp đối với hồ sơ ...
```

```text
V/v kiểm tra tiến độ thực hiện nhiệm vụ KH&CN ...
```

```text
V/v thu hồi công nợ dự án ... sau quyết toán
```

---

# IV. QUỐC HIỆU, TIÊU NGỮ VÀ ĐỊA DANH

```text
CỘNG HÒA XÃ HỘI CHỦ NGHĨA VIỆT NAM
Độc lập - Tự do - Hạnh phúc

Tây Ninh, ngày ... tháng ... năm ...
```

Không tự điền ngày nếu chưa có.

---

# V. KÍNH GỬI

## 1. Một cơ quan

```text
Kính gửi: [Tên cơ quan/tổ chức].
```

## 2. Nhiều cơ quan

```text
Kính gửi:
- [Cơ quan 1];
- [Cơ quan 2];
- [Cơ quan 3].
```

## 3. Cơ quan có đầu mối tiếp nhận

Có thể ghi:

```text
Kính gửi: Văn phòng Bộ Khoa học và Công nghệ
(qua [đơn vị đầu mối])
```

nếu văn bản nguồn hoặc yêu cầu thực tế xác định rõ.

---

# VI. NGUYÊN TẮC XÁC ĐỊNH ĐỐI TƯỢNG NHẬN

AI MUST:

* dùng đúng tên cơ quan;
* dùng đúng cấp hành chính;
* không tự thêm cơ quan nhận;
* phân biệt nơi nhận chính với nơi nhận để phối hợp/báo cáo.

AI MUST NOT:

* sao chép “Kính gửi” của công văn mẫu cũ;
* tự thêm UBND tỉnh vào “Kính gửi” nếu chỉ là nơi nhận báo cáo;
* tự thêm cơ quan phối hợp nếu nguồn không có.

---

# VII. CẤU TRÚC NỘI DUNG CHUNG

Công văn thông thường có cấu trúc:

```text
1. Căn cứ / lý do phát sinh công việc
2. Nội dung chính
3. Yêu cầu / đề nghị / ý kiến của Sở
4. Thời hạn hoặc đầu mối thực hiện nếu có
5. Câu kết
```

Không bắt buộc đánh số nếu văn bản ngắn.

---

# VIII. CÁCH VIẾT PHẦN MỞ ĐẦU

## Mẫu 1 — Có công văn chỉ đạo

```text
Thực hiện Công văn số [số/ký hiệu] ngày [ngày] của [cơ quan]
về việc [trích yếu].
```

---

## Mẫu 2 — Có văn bản đề nghị góp ý

```text
Theo Công văn số [số/ký hiệu] ngày [ngày] của [cơ quan]
về việc [nội dung].
```

---

## Mẫu 3 — Phúc đáp doanh nghiệp/tổ chức

```text
Ngày [ngày], Sở Khoa học và Công nghệ nhận được
[văn bản số ... ngày ...] của [tổ chức/doanh nghiệp]
về việc [nội dung].
```

---

## Mẫu 4 — Có căn cứ pháp lý trực tiếp

```text
Căn cứ [tên văn bản, số, ngày, cơ quan ban hành];
```

Có thể dùng nhiều căn cứ nếu cần.

---

## Mẫu 5 — Nhiệm vụ chủ động của Sở

```text
Nhằm [mục tiêu],
Sở Khoa học và Công nghệ đề nghị [cơ quan] phối hợp thực hiện một số nội dung sau:
```

---

# IX. CÔNG VĂN ĐỀ NGHỊ / PHỐI HỢP

Áp dụng khi Sở đề nghị cơ quan khác:

* phối hợp;
* rà soát;
* cung cấp thông tin;
* triển khai;
* cử đầu mối;
* thực hiện một nhiệm vụ.

Cấu trúc:

```text
Kính gửi: [...]

[Đoạn nêu căn cứ/mục tiêu.]

Sở Khoa học và Công nghệ đề nghị [cơ quan] phối hợp thực hiện
một số nội dung như sau:

1. [Nội dung 1].

2. [Nội dung 2].

3. [Nội dung 3].

Thông tin gửi về Sở Khoa học và Công nghệ trước ngày [...]
để tổng hợp, tham mưu [...]

Đầu mối liên hệ: [...]
```

---

## Ví dụ logic machine-readable

```yaml
request_letter:
  objective: ""
  requested_actions: []
  deadline: null
  contact_person: null
  expected_output: ""
```

---

# X. CÔNG VĂN TRIỂN KHAI / HƯỚNG DẪN

Áp dụng khi:

* triển khai công văn cấp trên;
* hướng dẫn cơ quan thực hiện;
* yêu cầu điền biểu mẫu;
* yêu cầu gửi dữ liệu.

Cấu trúc:

```text
Căn cứ/Thực hiện [văn bản].

Sở Khoa học và Công nghệ đề nghị các cơ quan phối hợp thực hiện:

1. [Nội dung phải thực hiện].

2. [Trường hợp đặc biệt / ngoại lệ / phản hồi].

3. [Thời hạn].

4. [Đầu mối hỗ trợ].
```

Có thể kèm:

```text
Phụ lục hướng dẫn
File Excel
Biểu mẫu
Phiếu thông tin
```

---

# XI. CÔNG VĂN GÓP Ý DỰ THẢO

## Trường hợp thống nhất hoàn toàn

Mẫu ngắn:

```text
Theo Công văn số [số] ngày [ngày] của [cơ quan] về việc
góp ý dự thảo [tên văn bản].

Sau khi nghiên cứu dự thảo, Sở Khoa học và Công nghệ
thống nhất với nội dung dự thảo, kính gửi [cơ quan] tổng hợp.

Trân trọng./.
```

---

## Trường hợp có ý kiến góp ý

```text
Sau khi nghiên cứu dự thảo, Sở Khoa học và Công nghệ
có ý kiến như sau:

1. Về [nội dung]:
[Ý kiến].

2. Về [nội dung]:
[Ý kiến].

3. Đề nghị:
[Nội dung].
```

---

## Trường hợp không có ý kiến

Nếu nguồn/yêu cầu xác định rõ:

```text
Sở Khoa học và Công nghệ thống nhất với nội dung dự thảo,
không có ý kiến bổ sung.
```

Không tự dùng câu này nếu chưa thực sự nghiên cứu dự thảo.

---

# XII. CÔNG VĂN PHÚC ĐÁP

Áp dụng khi:

* doanh nghiệp;
* tổ chức;
* cá nhân;
* cơ quan khác

gửi đề nghị và Sở trả lời.

Cấu trúc chuẩn:

```text
Ngày [ngày], Sở Khoa học và Công nghệ nhận được
[văn bản/đề nghị] của [đơn vị] về [nội dung].

Qua xem xét [hồ sơ/văn bản], Sở Khoa học và Công nghệ
phúc đáp như sau:

[Diễn biến hoặc thông tin hồ sơ.]

[Ý kiến xử lý / kết luận.]

Trên đây là ý kiến của Sở Khoa học và Công nghệ,
thông báo đến [Quý Công ty/đơn vị] được biết và thực hiện
theo quy định.

Trân trọng./.
```

---

# XIII. QUY TẮC PHÚC ĐÁP

AI phải tách rõ:

```text
YÊU CẦU CỦA ĐƠN VỊ
→ DỮ LIỆU/HỒ SƠ SỞ ĐÃ TIẾP NHẬN
→ ĐỐI CHIẾU
→ Ý KIẾN CỦA SỞ
```

Không được:

* suy đoán hồ sơ;
* tự chấp thuận;
* tự từ chối;
* tự bổ sung căn cứ.

---

# XIV. CÔNG VĂN LẤY Ý KIẾN THÀNH VIÊN UBND TỈNH

Áp dụng khi Giám đốc Sở tham gia với tư cách Thành viên UBND tỉnh.

Cấu trúc:

```text
Kính gửi: Văn phòng Ủy ban nhân dân tỉnh

Căn cứ Công văn số [...] của Văn phòng UBND tỉnh
về việc lấy ý kiến Thành viên UBND tỉnh đối với [nội dung].

Giám đốc Sở Khoa học và Công nghệ - Thành viên UBND tỉnh
[thống nhất/có ý kiến] đối với nội dung xin ý kiến
(Phiếu ghi ý kiến kèm theo).

Sở Khoa học và Công nghệ kính gửi Văn phòng UBND tỉnh tổng hợp./.
```

---

## HARD RULE

Loại công văn này gắn với tư cách:

```yaml
signer_capacity:
  role: "Giám đốc Sở"
  additional_capacity: "Thành viên UBND tỉnh"
```

AI không được đổi sang Phó Giám đốc nếu chưa có căn cứ pháp lý rõ ràng.

---

# XV. CÔNG VĂN KIỂM TRA / KIỂM TRA TIẾN ĐỘ NHIỆM VỤ

Áp dụng cho:

* nhiệm vụ KH&CN;
* dự án;
* chương trình;
* nhiệm vụ có kế hoạch kiểm tra.

Cấu trúc:

```text
Căn cứ [quy định pháp lý];
Căn cứ [kế hoạch kiểm tra];
Căn cứ [quyết định thành lập đoàn];

Sở Khoa học và Công nghệ tổ chức kiểm tra [tên nhiệm vụ],
cụ thể như sau:

1. Nội dung kiểm tra:
- [...]
- [...]

2. Thời gian:
[...]

3. Địa điểm:
[...]

Đề nghị [đơn vị] chuẩn bị [báo cáo/hồ sơ/tài liệu]
và gửi về Sở trước ngày [...]

Trân trọng./.
```

---

# XVI. QUY TẮC CÔNG VĂN KIỂM TRA

Nếu có biểu mẫu chuyên ngành:

AI phải giữ đúng:

```text
Tên biểu mẫu
Mã biểu mẫu
Thông tư/Quyết định ban hành mẫu
```

Không tự thiết kế biểu mẫu khác.

Nếu có đoàn kiểm tra:

phải xác định:

* quyết định thành lập đoàn;
* thành viên;
* nội dung kiểm tra;
* thời gian;
* địa điểm;
* tài liệu chuẩn bị.

---

# XVII. CÔNG VĂN TÀI CHÍNH / THU HỒI CÔNG NỢ

Áp dụng khi:

* quyết toán dự án;
* thanh toán thừa;
* thu hồi kinh phí;
* nộp trả ngân sách;
* xử lý công nợ.

Cấu trúc:

```text
Căn cứ [Quyết định phê duyệt quyết toán];

Căn cứ [Hợp đồng/văn bản liên quan];

Theo [kết quả quyết toán/tình hình công nợ], giá trị [...]
trong khi số đã thanh toán là [...], chênh lệch phải thu hồi là [...].

Sở Khoa học và Công nghệ đề nghị [đơn vị] thực hiện:

1. Số tiền phải nộp: [...]
   (Bằng chữ: [...])

2. Nội dung nộp: [...]

3. Tên tài khoản: [...]

4. Số tài khoản: [...]

Thời hạn hoàn thành: [...]

Sau khi thực hiện, đề nghị gửi [chứng từ] về Sở để [...]
```

---

# XVIII. HARD RULE ĐỐI VỚI SỐ TIỀN

AI MUST:

* giữ nguyên số tiền nguồn;
* đối chiếu số và chữ;
* không tự tính nếu thiếu dữ liệu;
* không tự tạo tài khoản Kho bạc;
* không tự tạo mã chương, ngành, nguồn;
* không sao chép số tài khoản từ văn bản cũ sang vụ việc mới.

```yaml
financial_fields:
  amount: "SOURCE_REQUIRED"
  amount_in_words: "VERIFY"
  treasury_account: "SOURCE_REQUIRED"
  budget_code: "SOURCE_REQUIRED"
```

---

# XIX. CÔNG VĂN CÓ PHỤ LỤC

Nếu có phụ lục:

cuối công văn phải thể hiện:

```text
(gửi kèm Phụ lục)
```

hoặc trong nội dung:

```text
Sở Khoa học và Công nghệ gửi kèm theo Công văn này
Phiếu thông tin/Phụ lục [...]
```

Phụ lục đầu trang:

```text
PHỤ LỤC
[TÊN PHỤ LỤC]

(Kèm theo Công văn số .../SKHCN-... ngày ... tháng ... năm ...
của Sở Khoa học và Công nghệ tỉnh Tây Ninh)
```

---

# XX. PHỤ LỤC DẠNG HƯỚNG DẪN

Có thể dùng cấu trúc:

```text
PHỤ LỤC
HƯỚNG DẪN [...]

1. [Nội dung bước 1]

2. [Nội dung bước 2]

2.1. [Trường hợp A]

2.2. [Trường hợp B]

Ví dụ:
[...]
```

Nếu hướng dẫn liên quan file Excel:

cần ghi rõ:

* tên sheet;
* cột;
* trường dữ liệu;
* quy tắc nhập;
* ví dụ.

AI không được đổi logic bảng dữ liệu nếu nguồn đã quy định.

---

# XXI. PHỤ LỤC DẠNG PHIẾU THÔNG TIN

Có thể dùng:

```text
I. THÔNG TIN CHUNG

II. THỰC TRẠNG HOẠT ĐỘNG

III. NĂNG LỰC, NGUỒN LỰC CÓ THỂ CHIA SẺ

IV. NHU CẦU HỖ TRỢ

V. Ý KIẾN, ĐỀ XUẤT
```

Chỉ dùng nếu phù hợp nhiệm vụ.

---

# XXII. CÁCH VIẾT YÊU CẦU THỰC HIỆN

Nên dùng các động từ hành chính:

```text
đề nghị
phối hợp
rà soát
cung cấp
tổng hợp
gửi
thực hiện
cử
phản hồi
báo cáo
chuẩn bị
tham gia
```

Không nên dùng:

```text
ra lệnh
bắt buộc
yêu cầu nghiêm khắc
```

trừ khi thẩm quyền và văn bản cấp trên cho phép.

---

# XXIII. THỜI HẠN

Nếu có thời hạn:

```text
đề nghị gửi về Sở Khoa học và Công nghệ trước ngày ...
```

hoặc:

```text
hoàn thành trước ngày ...
```

AI MUST NOT tự tạo thời hạn.

Nếu văn bản đến có deadline:

ưu tiên đối chiếu:

```text
incoming_document
→ quy_che_lam_viec.md
→ quy định chuyên ngành
```

---

# XXIV. ĐẦU MỐI LIÊN HỆ

Nếu cần hỗ trợ:

```text
Đầu mối liên hệ:
Ông/Bà [họ tên], [chức vụ/đơn vị],
điện thoại: [...]
```

AI không được tự đưa:

* số điện thoại;
* email;
* tên cán bộ;

từ công văn mẫu khác sang văn bản mới.

---

# XXV. CÁCH KẾT THÚC CÔNG VĂN

## 1. Công văn đề nghị

```text
Sở Khoa học và Công nghệ đề nghị [cơ quan] quan tâm,
phối hợp thực hiện.

Trân trọng./.
```

---

## 2. Công văn góp ý

```text
Sở Khoa học và Công nghệ kính gửi [cơ quan] tổng hợp.

Trân trọng./.
```

---

## 3. Công văn phúc đáp

```text
Trên đây là ý kiến của Sở Khoa học và Công nghệ,
thông báo đến [đơn vị] được biết và thực hiện theo quy định.

Trân trọng./.
```

---

## 4. Công văn gửi Bộ/cơ quan cấp trên

```text
Kính đề nghị [cơ quan] tổng hợp, xem xét./.
```

---

## 5. Công văn kiểm tra

```text
Đề nghị [đơn vị] chuẩn bị đầy đủ nội dung, hồ sơ
theo yêu cầu nêu trên.

Trân trọng./.
```

---

# XXVI. NƠI NHẬN

Mẫu cơ bản:

```text
Nơi nhận:
- Như trên;
- GĐ, các PGĐ Sở;
- [Đơn vị liên quan nếu có];
- Lưu: VT, [mã đơn vị/cá nhân soạn].
```

Có thể có:

```text
- UBND tỉnh (báo cáo);
- [Cơ quan phối hợp];
```

nếu có căn cứ thực tế.

AI MUST NOT sao chép nguyên nơi nhận của văn bản cũ.

---

# XXVII. KHỐI KÝ

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

Chỉ khi thuộc phạm vi được Quy chế cho phép:

```text
TL. GIÁM ĐỐC
CHÁNH VĂN PHÒNG


[Họ và tên]
```

---

# XXVIII. QUY TẮC XÁC ĐỊNH NGƯỜI KÝ

Luồng bắt buộc:

```text
NỘI DUNG CÔNG VĂN
      ↓
ĐƠN VỊ CHỦ TRÌ
      ↓
phan_cong.md
      ↓
LÃNH ĐẠO PHỤ TRÁCH
      ↓
quy_che_lam_viec.md
      ↓
KIỂM TRA LOẠI VĂN BẢN
      ↓
KIỂM TRA NGƯỜI NHẬN
      ↓
KIỂM TRA ỦY QUYỀN
      ↓
ĐỀ XUẤT NGƯỜI KÝ
```

---

# XXIX. HARD RULE — VĂN BẢN TRÌNH UBND TỈNH

Nếu công văn thuộc trường hợp trình UBND tỉnh:

```yaml
signer:
  role: "Giám đốc"
```

Không tự đề xuất Phó Giám đốc ký chỉ vì phụ trách lĩnh vực.

---

# XXX. KHÔNG DÙNG NGƯỜI KÝ TRONG MẪU LÀM CĂN CỨ

Các công văn thực tế có thể có người ký khác nhau.

AI phải hiểu:

```text
NGƯỜI KÝ TRONG FILE MẪU
≠
NGƯỜI KÝ MẶC ĐỊNH
```

Ví dụ:

* Công văn lĩnh vực CĐS có thể do PGĐ phụ trách CĐS ký.
* Công văn lĩnh vực KH&CN có thể do PGĐ phụ trách KH ký.
* Công văn gửi với tư cách Thành viên UBND tỉnh có thể do Giám đốc ký.
* Công văn khác có thể do Giám đốc trực tiếp ký.

Phải tra phân công và Quy chế hiện hành.

---

# XXXI. CẤU TRÚC MẪU CÔNG VĂN CHUNG

```text
UBND TỈNH TÂY NINH
SỞ KHOA HỌC VÀ CÔNG NGHỆ

Số:      /SKHCN-[MÃ ĐƠN VỊ]
V/v [TRÍCH YẾU]

CỘNG HÒA XÃ HỘI CHỦ NGHĨA VIỆT NAM
Độc lập - Tự do - Hạnh phúc

Tây Ninh, ngày ... tháng ... năm ...

Kính gửi: [CƠ QUAN/TỔ CHỨC]

[Căn cứ hoặc lý do phát sinh công việc.]

[Nội dung chính.]

Sở Khoa học và Công nghệ [đề nghị/phúc đáp/có ý kiến]
như sau:

1. [...]

2. [...]

3. [...]

[Thời hạn nếu có.]

[Đầu mối liên hệ nếu có.]

[Đoạn kết phù hợp]./.

Nơi nhận:
- Như trên;
- GĐ, các PGĐ Sở;
- [...];
- Lưu: VT, [...].

[CHỨC DANH NGƯỜI KÝ]


[HỌ VÀ TÊN]
```

---

# XXXII. MẪU CÔNG VĂN GÓP Ý

```text
V/v góp ý dự thảo [tên văn bản]

Kính gửi: [Cơ quan]

Theo Công văn số [số/ký hiệu] ngày [ngày] của [cơ quan]
về việc góp ý dự thảo [tên văn bản].

Sau khi nghiên cứu dự thảo, Sở Khoa học và Công nghệ
[có ý kiến/thống nhất] như sau:

1. [Nội dung góp ý nếu có].

2. [Nội dung góp ý nếu có].

Sở Khoa học và Công nghệ kính gửi [cơ quan] tổng hợp.

Trân trọng./.
```

---

# XXXIII. MẪU CÔNG VĂN PHÚC ĐÁP

```text
V/v phúc đáp [nội dung]

Kính gửi: [Tổ chức/doanh nghiệp]

Ngày [ngày], Sở Khoa học và Công nghệ nhận được
[văn bản] của [đơn vị] về [nội dung].

Qua xem xét hồ sơ và nội dung đề nghị,
Sở Khoa học và Công nghệ phúc đáp như sau:

[Thông tin hồ sơ.]

[Đối chiếu.]

[Ý kiến xử lý.]

Trên đây là ý kiến của Sở Khoa học và Công nghệ,
thông báo đến Quý [Công ty/đơn vị] được biết và thực hiện
theo quy định.

Trân trọng./.
```

---

# XXXIV. MẪU CÔNG VĂN ĐỀ NGHỊ PHỐI HỢP

```text
V/v [nội dung]

Kính gửi: [Cơ quan]

Nhằm [mục tiêu], Sở Khoa học và Công nghệ đề nghị
[cơ quan] phối hợp thực hiện một số nội dung như sau:

1. [Nội dung].

2. [Nội dung].

3. [Cử đầu mối nếu cần].

Đề nghị gửi thông tin về Sở trước ngày [...]
để tổng hợp và triển khai các bước tiếp theo.

Thông tin liên hệ:
[Họ tên, đơn vị, điện thoại].

Trân trọng./.
```

---

# XXXV. MẪU CÔNG VĂN HƯỚNG DẪN

```text
V/v hướng dẫn [nội dung]

Kính gửi:
- [...]
- [...]

Căn cứ [văn bản];
Thực hiện [chỉ đạo];

Sở Khoa học và Công nghệ hướng dẫn/đề nghị các cơ quan
thực hiện như sau:

1. [Nội dung].

2. [Cách thực hiện].

3. [Thời hạn].

4. [Trường hợp đặc biệt].

(Phụ lục hướng dẫn kèm theo)

Đầu mối hỗ trợ: [...]

Sở Khoa học và Công nghệ đề nghị các cơ quan quan tâm,
phối hợp thực hiện.

Trân trọng./.
```

---

# XXXVI. MẪU CÔNG VĂN KIỂM TRA

```text
V/v kiểm tra tiến độ [nhiệm vụ]

Kính gửi:
- [Tổ chức chủ trì];
- [Chủ nhiệm];
- [Thành viên đoàn nếu cần].

Căn cứ [văn bản pháp lý];
Căn cứ [kế hoạch];
Căn cứ [quyết định thành lập đoàn];

Sở Khoa học và Công nghệ tổ chức kiểm tra [nhiệm vụ],
cụ thể như sau:

1. Nội dung kiểm tra:
- [...]
- [...]

2. Thời gian:
[...]

3. Địa điểm:
[...]

Đề nghị [đơn vị] chuẩn bị hồ sơ, báo cáo theo [mẫu]
và gửi về Sở trước ngày [...].

Trân trọng./.
```

---

# XXXVII. MẪU CÔNG VĂN TÀI CHÍNH

```text
V/v thu hồi công nợ [tên dự án/nhiệm vụ]

Kính gửi: [Đơn vị]

Căn cứ [Quyết định phê duyệt quyết toán];

Căn cứ [Hợp đồng/văn bản];

Theo kết quả quyết toán, [nội dung].

Sở Khoa học và Công nghệ đề nghị [đơn vị] thực hiện:

1. Số tiền: [...]
   Bằng chữ: [...]

2. Nội dung nộp: [...]

3. Tài khoản: [...]

4. Thời hạn: [...]

Sau khi thực hiện, đề nghị gửi [chứng từ]
về Sở để hoàn thiện hồ sơ theo quy định.

Trân trọng./.
```

---

# XXXVIII. MẪU CÔNG VĂN LẤY Ý KIẾN THÀNH VIÊN UBND TỈNH

```text
V/v ý kiến Thành viên UBND tỉnh đối với [nội dung]

Kính gửi: Văn phòng Ủy ban nhân dân tỉnh

Căn cứ Công văn số [...] của Văn phòng UBND tỉnh
về việc lấy ý kiến Thành viên UBND tỉnh đối với [nội dung].

Giám đốc Sở Khoa học và Công nghệ - Thành viên UBND tỉnh
[thống nhất/có ý kiến] đối với nội dung xin ý kiến
(Phiếu ghi ý kiến kèm theo).

Sở Khoa học và Công nghệ kính gửi Văn phòng UBND tỉnh tổng hợp./.
```

---

# XXXIX. QUY TẮC CÓ/ KHÔNG CÓ ĐÁNH SỐ

Nếu công văn ngắn, chỉ có một ý chính:

```yaml
numbered_sections: false
```

Nếu có từ 2 nội dung trở lên hoặc cần giao nhiệm vụ rõ:

```yaml
numbered_sections: true
```

Không đánh số mục chỉ để làm văn bản dài hơn.

---

# XL. QUY TẮC CĂN CỨ

AI chỉ dùng căn cứ khi:

* liên quan trực tiếp;
* có trong văn bản đến;
* có trong repo;
* cần để xác lập cơ sở xử lý.

Không bắt buộc mọi công văn đều phải có dòng:

```text
Căn cứ ...
```

Ví dụ công văn góp ý ngắn có thể dùng:

```text
Theo Công văn số ...
```

---

# XLI. QUY TẮC VĂN PHONG

AI SHOULD:

* viết ngắn;
* rõ nhiệm vụ;
* rõ đối tượng;
* rõ sản phẩm;
* rõ deadline;
* lịch sự, hành chính;
* ưu tiên câu chủ động.

AI SHOULD NOT:

* diễn giải dài dòng như báo cáo;
* dùng quá nhiều căn cứ không cần thiết;
* lặp lại nguyên văn trích yếu nhiều lần;
* dùng ngôn ngữ quảng bá;
* dùng câu cảm tính.

---

# XLII. QUY TẮC CHO NHIỆM VỤ CÓ DEADLINE

Mỗi nhiệm vụ nên có:

```yaml
task:
  action: ""
  responsible_party: ""
  deadline: ""
  output: ""
```

Ví dụ:

```text
Đề nghị các cơ quan gửi file hoàn chỉnh về Sở
trước ngày ... để tổng hợp, tham mưu UBND tỉnh.
```

---

# XLIII. QUY TẮC CHO NHIỆM VỤ CÓ ĐẦU MỐI

Nếu cần phối hợp thường xuyên:

```yaml
contact:
  name: ""
  unit: ""
  phone: ""
  email: null
```

Không tự thêm thông tin cá nhân nếu không có nguồn.

---

# XLIV. OUTPUT NỘI BỘ KHUYẾN NGHỊ

```yaml
official_letter_draft:

  letter_type: ""

  incoming_reference:
    number: null
    date: null
    agency: null
    subject: null

  lead_unit:
    id: ""
    name: ""

  symbol:
    value: "/SKHCN-"

  subject: ""

  recipients: []

  legal_basis: []

  purpose: ""

  requested_actions: []

  deadline:
    value: null
    source: null

  expected_outputs: []

  attachment:
    required: false
    files: []

  contact:
    required: false
    name: null
    unit: null
    phone: null

  recipients_copy: []

  signing:
    proposed_signer: null
    signing_form: null
    status: "CAN_KIEM_TRA"

  confidence: "high | medium | low"
```

---

# XLV. ROUTING LOẠI CÔNG VĂN

```yaml
cong_van_router:

  if:
    purpose == "request_coordination"
  then:
    type: CONG_VAN_DE_NGHI

  if:
    purpose == "implement_direction"
  then:
    type: CONG_VAN_TRIEN_KHAI

  if:
    purpose == "provide_instructions"
  then:
    type: CONG_VAN_HUONG_DAN

  if:
    purpose == "comment_on_draft"
  then:
    type: CONG_VAN_GOP_Y

  if:
    purpose == "reply_to_request"
  then:
    type: CONG_VAN_PHUC_DAP

  if:
    purpose == "member_of_provincial_ubnd_opinion"
  then:
    type: CONG_VAN_LAY_Y_KIEN_TV_UBND

  if:
    purpose == "inspection"
  then:
    type: CONG_VAN_KIEM_TRA

  if:
    purpose == "financial_recovery"
  then:
    type: CONG_VAN_TAI_CHINH
```

---

# XLVI. FINAL CHECKLIST

Trước khi xuất công văn, AI phải kiểm tra:

```yaml
final_checklist:

  authority_checked: true

  lead_unit_checked: true

  unit_code_correct: true

  incoming_document_number_verified: true

  incoming_document_date_verified: true

  recipient_verified: true

  subject_matches_content: true

  legal_basis_supported: true

  requested_action_clear: true

  deadline_verified: true

  attachment_verified: true

  contact_information_verified: true

  signer_checked_with_assignment: true

  signer_checked_with_work_rules: true

  recipients_copy_verified: true
```

---

# XLVII. HARD RULES

AI MUST:

1. Xác định loại công văn trước khi soạn.
2. Xác định đơn vị chủ trì trước khi điền mã ký hiệu.
3. Kiểm tra văn bản đến trước khi viện dẫn.
4. Xác định rõ hành động cần cơ quan nhận thực hiện.
5. Nêu deadline nếu nguồn quy định.
6. Kiểm tra phụ lục nếu công văn có file kèm.
7. Kiểm tra thẩm quyền ký.
8. Kiểm tra nơi nhận.
9. Giữ đúng số liệu, tiền, mã hồ sơ, số quyết định.
10. Chỉ dùng thông tin liên hệ có nguồn.

AI MUST NOT:

1. Tự tạo số công văn.
2. Tự tạo ngày ban hành.
3. Tự tạo mã đơn vị nếu chưa xác định phòng chủ trì.
4. Tự tạo căn cứ.
5. Tự tạo deadline.
6. Tự tạo người ký.
7. Tự tạo số điện thoại/email.
8. Tự tạo tài khoản Kho bạc.
9. Tự sửa số tiền.
10. Tự chuyển công văn góp ý thành công văn chỉ đạo.
11. Tự chuyển công văn phúc đáp thành quyết định hành chính.
12. Tự đưa đơn vị không liên quan vào nơi nhận.
13. Sao chép chữ ký của công văn mẫu.
14. Sao chép dữ liệu vụ việc cũ sang vụ việc mới.

---

# XLVIII. STOP CONDITIONS

AI phải dừng soạn hoặc để trường trống nếu:

```yaml
stop_conditions:

  - "Không xác định được loại công văn"

  - "Không xác định được cơ quan nhận"

  - "Không xác định được đơn vị chủ trì"

  - "Không đủ thông tin số/ngày văn bản đến"

  - "Nội dung yêu cầu phụ thuộc hồ sơ nhưng chưa có hồ sơ"

  - "Không đủ căn cứ xác định deadline"

  - "Không đủ căn cứ xác định người ký"

  - "Có số tiền nhưng nguồn số liệu mâu thuẫn"

  - "Có phụ lục nhưng chưa có dữ liệu phụ lục"
```

Output:

```text
Chưa đủ thông tin để hoàn thiện công văn.
Cần bổ sung hoặc kiểm tra thêm dữ liệu nguồn trước khi phát hành dự thảo.
```

---

# XLIX. QUY TRÌNH AI SOẠN CÔNG VĂN

```text
VĂN BẢN ĐẾN / YÊU CẦU NGƯỜI DÙNG
              ↓
KIỂM TRA THẨM QUYỀN SỞ
              ↓
XÁC ĐỊNH LĨNH VỰC
              ↓
XÁC ĐỊNH 01 ĐƠN VỊ CHỦ TRÌ
              ↓
XÁC ĐỊNH MÃ CÔNG VĂN
              ↓
XÁC ĐỊNH LOẠI CÔNG VĂN
              ↓
XÁC ĐỊNH KÍNH GỬI
              ↓
TRÍCH XUẤT CĂN CỨ
              ↓
XÁC ĐỊNH NỘI DUNG YÊU CẦU/PHÚC ĐÁP/GÓP Ý
              ↓
XÁC ĐỊNH DEADLINE
              ↓
XÁC ĐỊNH PHỤ LỤC NẾU CÓ
              ↓
XÁC ĐỊNH ĐẦU MỐI NẾU CẦN
              ↓
TRA phan_cong.md
              ↓
TRA quy_che_lam_viec.md
              ↓
XÁC ĐỊNH THẨM QUYỀN KÝ
              ↓
HOÀN THIỆN NƠI NHẬN
              ↓
KIỂM TRA THỂ THỨC
              ↓
XUẤT DỰ THẢO
```

---

# L. NGUYÊN TẮC CUỐI

Một công văn tốt phải trả lời rõ:

```text
GỬI AI?
↓
VÌ SAO GỬI?
↓
CĂN CỨ NÀO?
↓
SỞ MUỐN CƠ QUAN NHẬN LÀM GÌ?
↓
LÀM TRƯỚC KHI NÀO?
↓
SẢN PHẨM GỬI LẠI LÀ GÌ?
↓
LIÊN HỆ AI?
↓
AI CÓ THẨM QUYỀN KÝ?
```

Nguyên tắc:

```text
ĐÚNG LOẠI CÔNG VĂN
→ ĐÚNG ĐƠN VỊ CHỦ TRÌ
→ ĐÚNG MÃ KÝ HIỆU
→ ĐÚNG KÍNH GỬI
→ ĐÚNG CĂN CỨ
→ ĐÚNG NỘI DUNG YÊU CẦU
→ ĐÚNG DEADLINE
→ ĐÚNG PHỤ LỤC
→ ĐÚNG NƠI NHẬN
→ ĐÚNG NGƯỜI KÝ
```

Nếu chưa đủ dữ liệu:

```text
KHÔNG BỊA.
KHÔNG SAO CHÉP DỮ LIỆU CÔNG VĂN CŨ.
KHÔNG TỰ TẠO NGƯỜI KÝ.
ĐỂ TRỐNG HOẶC YÊU CẦU BỔ SUNG.
```

```

Điểm đáng giữ từ các công văn thực tế là **không ép tất cả công văn vào một khuôn cứng**. Công văn góp ý của Sở có thể chỉ vài đoạn rất ngắn; :contentReference[oaicite:8]{index=8} công văn hướng dẫn từ điển dữ liệu lại cần chia nhiệm vụ, deadline, đầu mối và phụ lục hướng dẫn kỹ thuật; :contentReference[oaicite:9]{index=9} công văn kiểm tra nhiệm vụ KH&CN phải có căn cứ, nội dung, thời gian, địa điểm và biểu mẫu kèm theo; :contentReference[oaicite:10]{index=10} còn công văn thu hồi công nợ phải giữ chính xác số tiền, thông tin nộp ngân sách và thời hạn. :contentReference[oaicite:11]{index=11}

Vì vậy `cong_van.md` này nên được xem là **“bộ định tuyến mẫu công văn”**, không phải một mẫu duy nhất.
```
