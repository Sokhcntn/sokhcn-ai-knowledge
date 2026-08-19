# MẪU VÀ QUY TẮC SOẠN THÔNG BÁO KẾT LUẬN
## SỞ KHOA HỌC VÀ CÔNG NGHỆ TỈNH TÂY NINH

> File: `02_van_ban_mau/ket_luan.md`
>
> Vai trò:
> Đây là file mẫu và quy tắc nghiệp vụ để Trợ lý AI soạn
> Thông báo kết luận cuộc họp, buổi làm việc, phiên trao đổi
> của Sở Khoa học và Công nghệ tỉnh Tây Ninh.
>
> File này được chuẩn hóa từ các Thông báo kết luận thực tế của Sở, gồm:
> - Kết luận họp chuyên đề;
> - Kết luận họp liên ngành;
> - Kết luận buổi làm việc với doanh nghiệp;
> - Kết luận họp thẩm định/hoàn thiện hồ sơ dự án;
> - Kết luận họp về mua sắm, tài chính;
> - Kết luận góp ý dự thảo chính sách;
> - Kết luận về giải pháp kỹ thuật, chuyển đổi số;
> - Thông báo có phụ lục danh sách dự họp;
> - Thông báo có phụ lục hướng dẫn kỹ thuật kèm theo.
>
> Lưu ý:
> - File này là mẫu soạn thảo, không phải căn cứ xác định thẩm quyền.
> - Trước khi xác định người chủ trì, đơn vị thực hiện và người ký phải tra:
>   `01_thong_tin_sokhcn/chuc_nang_nhiem_vu.md`
>   `01_thong_tin_sokhcn/phan_cong.md`
>   `01_thong_tin_sokhcn/quy_che_lam_viec.md`
> - Không được biến ý kiến phát biểu tại cuộc họp thành kết luận
>   nếu người chủ trì chưa kết luận nội dung đó.
> - Không được tự tạo nhiệm vụ, thời hạn, cơ quan chủ trì,
>   cơ quan phối hợp hoặc người ký.

---

# I. TEMPLATE METADATA

```yaml
template:
  id: THONG_BAO_KET_LUAN_SKHCN
  document_type: "THÔNG BÁO"
  subtype: "KẾT LUẬN CUỘC HỌP"
  issuing_agency: "SỞ KHOA HỌC VÀ CÔNG NGHỆ"
  province: "TÂY NINH"
  symbol: "TB-SKHCN"
  language: "vi"
````

---

# II. CÁC LOẠI THÔNG BÁO KẾT LUẬN HỆ THỐNG HỖ TRỢ

```yaml
conclusion_types:

  TBKL_HOP_CHUYEN_DE:
    description: "Kết luận cuộc họp chuyên đề theo lĩnh vực"

  TBKL_HOP_LIEN_NGANH:
    description: "Kết luận cuộc họp có nhiều sở, ngành cùng tham gia"

  TBKL_LAM_VIEC_DOANH_NGHIEP:
    description: "Kết luận buổi làm việc với doanh nghiệp, tổ chức"

  TBKL_DU_AN:
    description: "Kết luận họp trao đổi, thẩm định, hoàn thiện hồ sơ dự án"

  TBKL_KY_THUAT:
    description: "Kết luận về giải pháp kỹ thuật, hệ thống thông tin, chuyển đổi số"

  TBKL_TAI_CHINH_MUA_SAM:
    description: "Kết luận về mua sắm, kinh phí, tài sản"

  TBKL_CHINH_SACH:
    description: "Kết luận trao đổi/góp ý dự thảo chính sách, nghị quyết"

  TBKL_GIAO_NHIEM_VU:
    description: "Kết luận có giao nhiệm vụ, sản phẩm và thời hạn cụ thể"
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
Số:      /TB-SKHCN
```

AI MUST NOT tự tạo số Thông báo.

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

Không tự tạo ngày ban hành.

---

# IV. TÊN LOẠI VÀ TRÍCH YẾU

Tên loại:

```text
THÔNG BÁO
```

Dòng dưới là trích yếu.

Các dạng thường dùng:

```text
Kết luận cuộc họp [...]
```

```text
Kết luận của Giám đốc Sở Khoa học và Công nghệ
tại buổi làm việc [...]
```

```text
Kết luận buổi làm việc về [...]
```

```text
Kết luận cuộc họp trao đổi, thống nhất [...]
```

---

# V. NGUYÊN TẮC ĐẶT TRÍCH YẾU

Trích yếu phải trả lời:

```text
KẾT LUẬN CUỘC HỌP/BỦI LÀM VIỆC NÀO?
```

Nên có:

* chủ đề;
* đối tượng;
* thời kỳ nếu cần;
* tên dự án/nhiệm vụ nếu có.

Ví dụ:

```text
Kết luận cuộc họp trao đổi, thống nhất một số nội dung
hồ sơ dự án “[Tên dự án]”
```

hoặc:

```text
Kết luận của Giám đốc Sở Khoa học và Công nghệ
tại buổi làm việc với các doanh nghiệp viễn thông
(chuyên đề kinh tế số - xã hội số)
```

---

# VI. PHẦN MỞ ĐẦU

Phần mở đầu phải xác định tối thiểu:

```yaml
meeting_context:
  date: null
  start_time: null
  location: null
  organizer: "Sở Khoa học và Công nghệ"
  chair:
    name: null
    role: null
  participants: []
  purpose: ""
```

---

# VII. MẪU MỞ ĐẦU CHUNG

```text
Vào lúc [giờ], ngày [ngày], tại [địa điểm],
Sở Khoa học và Công nghệ tổ chức cuộc họp/buổi làm việc
về [nội dung].

Chủ trì cuộc họp: [Ông/Bà, chức vụ].

Thành phần tham dự gồm [mô tả ngắn]
(danh sách tại Phụ lục kèm theo nếu có).
```

---

# VIII. MẪU MỞ ĐẦU KHI KHÔNG CẦN TÁCH CHỦ TRÌ RIÊNG

```text
Ngày [ngày], tại [địa điểm],
Sở Khoa học và Công nghệ tổ chức buổi làm việc
về [nội dung], do [Ông/Bà, chức vụ] chủ trì.
```

---

# IX. PHẦN CHUYỂN TỪ THẢO LUẬN SANG KẾT LUẬN

Mẫu chuẩn:

```text
Sau khi nghe [đơn vị/cơ quan] báo cáo,
ý kiến trao đổi, thảo luận của các đại biểu tham dự,
[Ông/Bà, chức vụ] - Chủ trì cuộc họp kết luận như sau:
```

Hoặc:

```text
Trên cơ sở các ý kiến trao đổi của đại diện các cơ quan dự họp,
[Ông/Bà, chức vụ], chủ trì cuộc họp,
thống nhất kết luận các nội dung như sau:
```

---

# X. HARD RULE — PHÂN BIỆT Ý KIẾN VÀ KẾT LUẬN

AI phải tách:

```yaml
meeting_opinions:
  - speaker: ""
    content: ""

chair_conclusions:
  - content: ""
```

AI MUST NOT:

```text
Ý KIẾN ĐẠI BIỂU
→ TỰ ĐỘNG BIẾN THÀNH KẾT LUẬN
```

Chỉ nội dung được người chủ trì:

* thống nhất;
* kết luận;
* giao;
* yêu cầu;
* đề nghị;
* ghi nhận;

mới đưa vào phần kết luận.

---

# XI. TRƯỜNG HỢP CẦN GHI Ý KIẾN CÁC CƠ QUAN

Nếu việc kết luận phụ thuộc vào ý kiến chuyên môn của nhiều sở, ngành,
có thể sử dụng:

```text
1. Ý kiến của [cơ quan 1]

[...]

2. Ý kiến của [cơ quan 2]

[...]

3. Kết luận cuộc họp

[...]
```

Chỉ sử dụng cấu trúc này khi việc ghi lại ý kiến là cần thiết.

Nếu kết luận đã đủ rõ, không cần chép toàn bộ diễn biến cuộc họp.

---

# XII. CẤU TRÚC KẾT LUẬN CHUNG

Mỗi kết luận nên theo logic:

```text
VẤN ĐỀ
→ NHẬN ĐỊNH/QUAN ĐIỂM
→ NHIỆM VỤ
→ ĐƠN VỊ CHỦ TRÌ
→ ĐƠN VỊ PHỐI HỢP
→ SẢN PHẨM
→ THỜI HẠN
```

Machine-readable:

```yaml
conclusion_item:
  issue: ""
  decision: ""
  lead_unit: null
  support_units: []
  expected_output: null
  deadline: null
```

---

# XIII. KẾT LUẬN DẠNG ĐÁNH GIÁ CHUNG

Có thể mở đầu:

```text
1. Đánh giá chung
```

Dùng khi người chủ trì cần:

* đánh giá kết quả;
* ghi nhận nỗ lực;
* chỉ ra hạn chế;
* xác định nguyên nhân;
* thống nhất quan điểm chỉ đạo.

Không tự tạo đánh giá tích cực hoặc tiêu cực nếu nguồn họp không có.

---

# XIV. KẾT LUẬN DẠNG NHIỆM VỤ CỤ THỂ

Ví dụ cấu trúc:

```text
2. Về [nội dung]

Giao [đơn vị] chủ trì, phối hợp với [đơn vị]
thực hiện [nhiệm vụ].

Sản phẩm: [...]

Thời hạn hoàn thành: [...]
```

---

# XV. CÁC ĐỘNG TỪ KẾT LUẬN NÊN DÙNG

```text
thống nhất
giao
đề nghị
yêu cầu
ghi nhận
tiếp thu
rà soát
hoàn thiện
tham mưu
phối hợp
tổng hợp
báo cáo
khẩn trương
nghiên cứu
triển khai
duy trì
thực hiện
```

Không thay đổi mức độ mệnh lệnh.

Ví dụ:

```text
"đề nghị"
≠
"giao"
≠
"yêu cầu"
```

AI phải giữ đúng sắc thái của người chủ trì.

---

# XVI. KẾT LUẬN HỌP CHUYÊN ĐỀ

Áp dụng cho:

* viễn thông;
* chuyển đổi số;
* kinh tế số;
* khoa học công nghệ;
* chuyên đề ngành.

Cấu trúc:

```text
1. Đánh giá chung

2. Về [nội dung chuyên đề 1]

3. Về [nội dung chuyên đề 2]

4. Về [nội dung chuyên đề 3]

5. Tổ chức thực hiện / chế độ phối hợp
```

Có thể giao nhiều cơ quan nhưng mỗi nhiệm vụ phải xác định đầu mối.

---

# XVII. KẾT LUẬN LÀM VIỆC VỚI DOANH NGHIỆP

Cấu trúc khuyến nghị:

```text
1. Đánh giá chung

2. Quan điểm/thống nhất của Sở

3. Nhiệm vụ của doanh nghiệp

4. Nhiệm vụ của các phòng, đơn vị thuộc Sở

5. Chế độ phối hợp/giao ban thời gian tới
```

Không biến cam kết của doanh nghiệp thành nghĩa vụ pháp lý
nếu cuộc họp chỉ ghi nhận đề xuất hoặc dự kiến.

---

# XVIII. KẾT LUẬN VỀ DỰ ÁN/HỒ SƠ

Áp dụng khi họp:

* thẩm định;
* trao đổi hồ sơ;
* yêu cầu hoàn thiện dự án.

Cấu trúc:

```text
1. Về địa điểm đầu tư

2. Về quy mô đầu tư

3. Về kinh phí/chi phí

4. Về giải pháp và thông số kỹ thuật

5. Về hoàn thiện hồ sơ dự án
```

Tùy từng hồ sơ có thể thay đổi mục.

---

# XIX. HARD RULE VỀ HỒ SƠ DỰ ÁN

Nếu người chủ trì giao hoàn thiện hồ sơ:

nên xác định rõ:

```yaml
project_completion:
  responsible_party: ""
  required_changes: []
  resubmission_deadline: null
  receiving_agency: ""
```

AI không tự thêm nội dung kỹ thuật ngoài ý kiến đã kết luận.

---

# XX. KẾT LUẬN VỀ MUA SẮM/TÀI CHÍNH

Cấu trúc có thể gồm:

```text
I. NỘI DUNG CUỘC HỌP

II. KẾT LUẬN CUỘC HỌP
```

Hoặc trình bày trực tiếp các kết luận.

Mỗi nội dung tài chính phải giữ chính xác:

* định mức;
* số tiền;
* nguồn kinh phí;
* tình trạng khấu hao;
* trình tự, thủ tục;
* cơ quan tham mưu.

AI MUST NOT:

* tự tính mức chi;
* tự sửa định mức;
* tự suy luận nguồn kinh phí.

---

# XXI. KẾT LUẬN VỀ DỰ THẢO CHÍNH SÁCH

Có thể chia:

```text
1. Đối với ý kiến của [cơ quan 1]

2. Đối với ý kiến của [cơ quan 2]

3. Tổ chức thực hiện
```

Trong phần tổ chức thực hiện phải xác định:

* nội dung tiếp thu;
* đơn vị hoàn thiện;
* bước tiếp theo;
* cơ quan cần lấy ý kiến;
* cơ quan thẩm định;
* sản phẩm;
* thời hạn nếu có.

---

# XXII. KẾT LUẬN VỀ GIẢI PHÁP KỸ THUẬT

Cấu trúc:

```text
1. Về giải pháp trước mắt

2. Về giải pháp triển khai thời gian tới

3. Tổ chức phối hợp / hỗ trợ kỹ thuật
```

Nếu có hướng dẫn kỹ thuật kèm:

```text
(Phụ lục hướng dẫn kèm theo)
```

Không tự tạo:

* link;
* số điện thoại;
* thông số kỹ thuật;
* tài khoản;
* mật khẩu;

nếu không có nguồn.

---

# XXIII. GIAO NHIỆM VỤ CHO ĐƠN VỊ THUỘC SỞ

Cấu trúc nên rõ:

```text
Giao Phòng [tên phòng] chủ trì,
phối hợp với [đơn vị] thực hiện [nhiệm vụ],
hoàn thành trước ngày [deadline].
```

Schema:

```yaml
internal_assignment:
  lead_unit: ""
  support_units: []
  task: ""
  deadline: null
  output: null
```

---

# XXIV. GIAO/ĐỀ NGHỊ CƠ QUAN NGOÀI SỞ

Phải dùng đúng sắc thái:

```text
Đề nghị [cơ quan] chủ trì, phối hợp [...]
```

Không mặc định dùng:

```text
Giao [Sở khác] [...]
```

nếu Sở KH&CN không có thẩm quyền giao.

---

# XXV. HARD RULE — MỘT NHIỆM VỤ, MỘT ĐẦU MỐI

```yaml
lead_unit_count: 1
support_units: 0..n
```

Nếu nội dung cuộc họp chỉ nêu nhiều đơn vị cùng thực hiện
nhưng chưa xác định đầu mối:

```yaml
status: "CAN_XAC_DINH_CHU_TRI"
```

Không tự chọn ngẫu nhiên.

---

# XXVI. THỜI HẠN

Nếu người chủ trì kết luận thời hạn cụ thể:

phải ghi nguyên.

Ví dụ:

```text
hoàn thành trước ngày ...
```

```text
hoàn thành trong tháng 7/2026
```

```text
thực hiện định kỳ hằng quý
```

```text
duy trì họp giao ban 01 tháng/lần
```

AI MUST NOT tự tạo deadline.

---

# XXVII. SẢN PHẨM ĐẦU RA

Nếu có thể xác định:

```yaml
expected_outputs:
  - "dự thảo văn bản"
  - "báo cáo"
  - "hồ sơ hoàn thiện"
  - "phương án"
  - "kế hoạch"
  - "cơ sở dữ liệu"
  - "API"
  - "dashboard"
  - "văn bản tham mưu"
```

Chỉ ghi sản phẩm có căn cứ.

---

# XXVIII. CÁCH KẾT THÚC THÔNG BÁO

Các mẫu phù hợp:

```text
Sở Khoa học và Công nghệ thông báo đến
các cơ quan, đơn vị liên quan biết, phối hợp triển khai thực hiện./.
```

hoặc:

```text
Sở Khoa học và Công nghệ thông báo kết luận cuộc họp
để các cơ quan, đơn vị và các thành viên dự họp biết,
phối hợp triển khai thực hiện./.
```

hoặc:

```text
Với nội dung nêu trên,
Sở Khoa học và Công nghệ thông báo đến các cơ quan,
đơn vị liên quan biết, phối hợp triển khai thực hiện./.
```

---

# XXIX. NƠI NHẬN

Mẫu cơ bản:

```text
Nơi nhận:
- Thành phần dự họp;
- GĐ, các PGĐ Sở;
- Các phòng, đơn vị liên quan;
- Lưu: VT, [đơn vị].
```

Nếu có cơ quan ngoài Sở:

```text
- [Sở/cơ quan liên quan];
```

Nếu cần báo cáo Giám đốc:

```text
- GĐ Sở (báo cáo);
```

AI không sao chép nguyên Nơi nhận của Thông báo cũ.

---

# XXX. PHỤ LỤC DANH SÁCH DỰ HỌP

Nếu cần:

```text
PHỤ LỤC
DANH SÁCH THÀNH PHẦN DỰ HỌP

(Kèm theo Thông báo số .../TB-SKHCN
ngày ... tháng ... năm ... của Sở Khoa học và Công nghệ)
```

Danh sách có thể chia:

```text
I. Sở Khoa học và Công nghệ

1. Ông/Bà [...]
2. Ông/Bà [...]

II. [Cơ quan khác]

1. Ông/Bà [...]
```

Không tự thêm đại biểu.

---

# XXXI. PHỤ LỤC HƯỚNG DẪN KỸ THUẬT

Nếu Thông báo kết luận có hướng dẫn cài đặt,
quy trình, tài liệu kỹ thuật:

```text
PHỤ LỤC
HƯỚNG DẪN [...]

1. [...]
2. [...]
3. [...]
```

Phụ lục có thể chứa:

* đường dẫn;
* ảnh minh họa;
* bước cài đặt;
* cấu hình;
* đầu mối hỗ trợ.

AI phải giữ nguyên dữ liệu kỹ thuật có nguồn.

---

# XXXII. QUY TẮC VỀ ĐẦU MỐI LIÊN HỆ

Nếu Thông báo có:

```text
Ông/Bà [...]
Chức vụ [...]
Điện thoại [...]
```

AI không được sao chép sang Thông báo mới
nếu chưa xác nhận đầu mối.

---

# XXXIII. KHỐI KÝ

## 1. Giám đốc ký

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

# XXXIV. QUY TẮC XÁC ĐỊNH NGƯỜI KÝ

Người chủ trì cuộc họp:

```text
KHÔNG TỰ ĐỘNG
=
NGƯỜI KÝ THÔNG BÁO
```

Phải kiểm tra:

```text
NGƯỜI CHỦ TRÌ
      ↓
NỘI DUNG KẾT LUẬN
      ↓
ĐƠN VỊ CHỦ TRÌ THAM MƯU
      ↓
phan_cong.md
      ↓
quy_che_lam_viec.md
      ↓
THẨM QUYỀN KÝ
```

---

# XXXV. QUY TẮC VỀ GIÁM ĐỐC CHỦ TRÌ

Nếu Giám đốc chủ trì và kết luận các nội dung quan trọng,
có thể đề xuất Giám đốc ký.

Nhưng vẫn phải kiểm tra Quy chế.

Không dùng:

```text
Giám đốc chủ trì
→ chắc chắn Giám đốc ký
```

như quy tắc tuyệt đối.

---

# XXXVI. QUY TẮC VỀ PHÓ GIÁM ĐỐC CHỦ TRÌ

Nếu Phó Giám đốc chủ trì trong lĩnh vực được phân công,
có thể đề xuất:

```text
KT. GIÁM ĐỐC
PHÓ GIÁM ĐỐC
```

nếu phù hợp Quy chế và phân công hiện hành.

---

# XXXVII. MẪU THÔNG BÁO KẾT LUẬN CHUNG

```text
UBND TỈNH TÂY NINH
SỞ KHOA HỌC VÀ CÔNG NGHỆ

Số:      /TB-SKHCN

CỘNG HÒA XÃ HỘI CHỦ NGHĨA VIỆT NAM
Độc lập - Tự do - Hạnh phúc

Tây Ninh, ngày ... tháng ... năm ...

THÔNG BÁO
Kết luận cuộc họp [NỘI DUNG]

Vào lúc [giờ], ngày [ngày], tại [địa điểm],
Sở Khoa học và Công nghệ tổ chức cuộc họp
về [nội dung].

Chủ trì: [Ông/Bà, chức vụ].

Thành phần tham dự gồm [...]
(Phụ lục danh sách kèm theo nếu có).

Sau khi nghe [báo cáo/ý kiến] và các ý kiến trao đổi,
thảo luận của đại biểu dự họp,
[Ông/Bà, chức vụ] - Chủ trì kết luận như sau:

1. [Nội dung kết luận 1]

[...]

2. [Nội dung kết luận 2]

[...]

3. Tổ chức thực hiện

Giao/Đề nghị [đơn vị] [...]

Thời hạn: [...]

Sở Khoa học và Công nghệ thông báo kết luận cuộc họp
để các cơ quan, đơn vị liên quan biết,
phối hợp triển khai thực hiện./.

Nơi nhận:
- Thành phần dự họp;
- GĐ, các PGĐ Sở;
- [...];
- Lưu: VT, [...].

[CHỨC DANH NGƯỜI KÝ]


[HỌ VÀ TÊN]
```

---

# XXXVIII. MẪU KẾT LUẬN HỌP LIÊN NGÀNH

```text
THÔNG BÁO
Kết luận cuộc họp trao đổi, thống nhất [nội dung]

Vào lúc [...], ngày [...],
Sở Khoa học và Công nghệ tổ chức cuộc họp
với [các cơ quan].

1. Ý kiến của [cơ quan A]

[...]

2. Ý kiến của [cơ quan B]

[...]

3. Kết luận cuộc họp

Sau khi trao đổi, [người chủ trì] kết luận:

- Đối với [...]:
[...]

- Đối với [...]:
[...]

Trường hợp [vượt thẩm quyền/chưa thống nhất],
các đơn vị báo cáo UBND tỉnh xem xét, quyết định.

Sở Khoa học và Công nghệ thông báo
đến các cơ quan, thành viên dự họp biết, thực hiện./.
```

---

# XXXIX. MẪU KẾT LUẬN HỌP DỰ ÁN

```text
THÔNG BÁO
Kết luận cuộc họp trao đổi, thống nhất một số nội dung
hồ sơ dự án “[TÊN DỰ ÁN]”

Vào lúc [...], ngày [...],
Sở Khoa học và Công nghệ tổ chức cuộc họp
trao đổi, thống nhất hồ sơ dự án “[...]”.

Sau khi nghe Chủ đầu tư, đơn vị tư vấn trình bày
và các ý kiến trao đổi,
[người chủ trì] kết luận như sau:

1. Về [nội dung 1]

[...]

2. Về [nội dung 2]

[...]

3. Về giải pháp kỹ thuật

[...]

4. Về hoàn thiện hồ sơ

Chủ đầu tư phối hợp với đơn vị tư vấn
tiếp thu đầy đủ các ý kiến,
rà soát, điều chỉnh, bổ sung và hoàn thiện hồ sơ.

Hồ sơ hoàn thiện gửi về Sở trước ngày [...]
để tiếp tục xem xét theo quy định.

Sở Khoa học và Công nghệ thông báo kết luận
để các cơ quan, đơn vị biết, phối hợp thực hiện./.
```

---

# XL. MẪU KẾT LUẬN LÀM VIỆC VỚI DOANH NGHIỆP

```text
THÔNG BÁO
Kết luận của [Giám đốc/Phó Giám đốc]
tại buổi làm việc với [doanh nghiệp]

Vào lúc [...], ngày [...],
tại [...], [người chủ trì] chủ trì buổi làm việc
với [doanh nghiệp/cơ quan] về [nội dung].

Sau khi nghe báo cáo, ý kiến đề xuất và thảo luận,
[người chủ trì] kết luận:

1. Đánh giá chung

[...]

2. Về [nội dung]

[...]

3. Nhiệm vụ của các phòng, đơn vị thuộc Sở

[...]

4. Đề nghị doanh nghiệp

[...]

5. Chế độ phối hợp

[...]

Sở Khoa học và Công nghệ thông báo
đến các đơn vị biết và phối hợp thực hiện./.
```

---

# XLI. MẪU KẾT LUẬN CHÍNH SÁCH/DỰ THẢO NGHỊ QUYẾT

```text
THÔNG BÁO
Kết luận cuộc họp trao đổi, thống nhất một số nội dung
dự thảo [Tên văn bản]

Vào lúc [...], ngày [...],
Sở Khoa học và Công nghệ tổ chức cuộc họp
trao đổi về dự thảo [Tên văn bản].

Sau khi nghe ý kiến của các cơ quan,
[người chủ trì] kết luận:

1. Đối với ý kiến của [cơ quan]

- Về thẩm quyền: [...]
- Về căn cứ pháp lý: [...]
- Về nội dung: [...]
- Về hồ sơ: [...]

2. Đối với ý kiến của [cơ quan]

[...]

3. Tổ chức thực hiện

Giao [đơn vị] tiếp thu đầy đủ ý kiến,
hoàn thiện dự thảo/hồ sơ,
gửi [cơ quan] để [xin ý kiến/thẩm định]
trước khi trình cấp có thẩm quyền.

Sở Khoa học và Công nghệ thông báo
đến các cơ quan liên quan biết, phối hợp thực hiện./.
```

---

# XLII. MẪU KẾT LUẬN GIẢI PHÁP KỸ THUẬT

```text
THÔNG BÁO
Kết luận buổi làm việc về [giải pháp/hệ thống]

Ngày [...], Sở Khoa học và Công nghệ
tổ chức buổi làm việc về [nội dung].

Sau khi nghe báo cáo đề xuất kỹ thuật
và ý kiến trao đổi,
[người chủ trì] kết luận:

1. Về giải pháp trước mắt

[...]

2. Về giải pháp thời gian tới

[...]

3. Tổ chức phối hợp

[...]

(Phụ lục hướng dẫn kỹ thuật kèm theo nếu có)

Sở Khoa học và Công nghệ thông báo
để các cơ quan nắm biết và phối hợp thực hiện./.
```

---

# XLIII. MẪU KẾT LUẬN MUA SẮM/TÀI CHÍNH

```text
THÔNG BÁO
Kết luận cuộc họp trao đổi, thống nhất phương án
[nội dung mua sắm/tài chính]

I. NỘI DUNG CUỘC HỌP

[Khái quát nội dung trao đổi.]

II. KẾT LUẬN CUỘC HỌP

Trên cơ sở ý kiến của các cơ quan,
[người chủ trì] kết luận:

1. [...]

2. [...]

3. Giao [đơn vị] [...]

Sở Khoa học và Công nghệ gửi Thông báo
đến các cơ quan, thành viên dự họp biết, thực hiện./.
```

---

# XLIV. OUTPUT NỘI BỘ KHUYẾN NGHỊ

```yaml
meeting_conclusion_draft:

  conclusion_type: ""

  meeting:
    date: null
    start_time: null
    location: null
    purpose: ""

  chair:
    name: null
    role: null

  participants: []

  basis_documents: []

  discussion_summary: []

  external_opinions:
    - agency: ""
      content: ""

  conclusions:
    - id: ""
      issue: ""
      decision: ""
      lead_unit: null
      support_units: []
      expected_output: null
      deadline: null
      escalation: false

  attachments:
    participant_list: false
    technical_guide: false
    other: []

  recipients: []

  signing:
    proposed_signer: null
    signing_form: null
    status: "CAN_KIEM_TRA"

  confidence: "high | medium | low"
```

---

# XLV. ROUTING LOẠI THÔNG BÁO KẾT LUẬN

```yaml
conclusion_router:

  if:
    purpose == "specialized_meeting"
  then:
    type: TBKL_HOP_CHUYEN_DE

  if:
    purpose == "interagency_coordination"
  then:
    type: TBKL_HOP_LIEN_NGANH

  if:
    purpose == "work_with_business"
  then:
    type: TBKL_LAM_VIEC_DOANH_NGHIEP

  if:
    purpose == "project_file_review"
  then:
    type: TBKL_DU_AN

  if:
    purpose == "technical_solution"
  then:
    type: TBKL_KY_THUAT

  if:
    purpose == "procurement_or_finance"
  then:
    type: TBKL_TAI_CHINH_MUA_SAM

  if:
    purpose == "policy_draft_discussion"
  then:
    type: TBKL_CHINH_SACH
```

---

# XLVI. FINAL CHECKLIST

Trước khi xuất Thông báo kết luận, AI phải kiểm tra:

```yaml
final_checklist:

  meeting_date_verified: true

  meeting_time_verified: true

  location_verified: true

  chair_verified: true

  participants_verified: true

  meeting_subject_verified: true

  opinions_distinguished_from_conclusions: true

  conclusions_supported_by_source: true

  lead_units_verified: true

  support_units_verified: true

  deadlines_verified: true

  expected_outputs_verified: true

  external_requests_use_correct_authority_language: true

  attachments_verified: true

  recipients_verified: true

  signer_checked_with_assignment: true

  signer_checked_with_work_rules: true
```

---

# XLVII. HARD RULES

AI MUST:

1. Xác định chính xác cuộc họp/buổi làm việc.
2. Xác định đúng người chủ trì.
3. Phân biệt ý kiến đại biểu với kết luận.
4. Chỉ ghi nội dung đã được người chủ trì kết luận.
5. Xác định 01 đầu mối cho từng nhiệm vụ nếu có.
6. Giữ đúng sắc thái “giao”, “đề nghị”, “yêu cầu”, “ghi nhận”.
7. Giữ đúng thời hạn.
8. Giữ đúng sản phẩm đầu ra.
9. Kiểm tra phụ lục nếu có.
10. Kiểm tra thẩm quyền ký.
11. Phân biệt người chủ trì và người ký.
12. Không mở rộng nội dung kết luận vượt quá nội dung cuộc họp.

AI MUST NOT:

1. Tự tạo kết luận.
2. Tự biến ý kiến của đại biểu thành chỉ đạo.
3. Tự tạo nhiệm vụ.
4. Tự tạo đơn vị chủ trì.
5. Tự tạo đơn vị phối hợp.
6. Tự tạo deadline.
7. Tự tạo số liệu.
8. Tự tạo căn cứ pháp lý.
9. Tự tạo người ký.
10. Tự thay đổi mức độ chỉ đạo.
11. Tự dùng “Giao” đối với cơ quan ngoài Sở nếu không có thẩm quyền.
12. Sao chép người ký của Thông báo cũ.
13. Sao chép danh sách dự họp cũ.
14. Sao chép số điện thoại, link kỹ thuật từ cuộc họp khác.
15. Tự thêm nội dung “đã thống nhất” nếu nguồn chỉ thể hiện “đề xuất”.

---

# XLVIII. STOP CONDITIONS

```yaml
stop_conditions:

  - "Không xác định được người chủ trì"

  - "Không xác định được nội dung kết luận của người chủ trì"

  - "Chỉ có biên bản ý kiến nhưng chưa có kết luận"

  - "Không phân biệt được ý kiến và quyết định cuối cùng"

  - "Có nhiệm vụ nhưng chưa rõ đơn vị chủ trì"

  - "Có deadline nhưng nguồn mâu thuẫn"

  - "Không rõ cơ quan ngoài Sở được giao hay chỉ được đề nghị"

  - "Không đủ căn cứ xác định người ký"

  - "Danh sách dự họp chưa được xác nhận"

  - "Có phụ lục kỹ thuật nhưng chưa có dữ liệu nguồn"
```

Output:

```text
Chưa đủ thông tin để hoàn thiện Thông báo kết luận.
Cần kiểm tra thêm nội dung kết luận của người chủ trì,
đơn vị thực hiện, thời hạn hoặc thẩm quyền ký trước khi phát hành dự thảo.
```

---

# XLIX. QUY TRÌNH AI SOẠN THÔNG BÁO KẾT LUẬN

```text
BIÊN BẢN / GHI CHÉP / NỘI DUNG CUỘC HỌP
                  ↓
XÁC ĐỊNH CUỘC HỌP
                  ↓
XÁC ĐỊNH NGƯỜI CHỦ TRÌ
                  ↓
XÁC ĐỊNH THÀNH PHẦN
                  ↓
TÁCH Ý KIẾN ĐẠI BIỂU
                  ↓
TÁCH KẾT LUẬN CỦA CHỦ TRÌ
                  ↓
PHÂN LOẠI TỪNG NỘI DUNG KẾT LUẬN
                  ↓
XÁC ĐỊNH NHIỆM VỤ
                  ↓
XÁC ĐỊNH 01 ĐƠN VỊ CHỦ TRÌ
                  ↓
XÁC ĐỊNH ĐƠN VỊ PHỐI HỢP
                  ↓
XÁC ĐỊNH SẢN PHẨM
                  ↓
XÁC ĐỊNH DEADLINE
                  ↓
KIỂM TRA CƠ QUAN NGOÀI SỞ:
"GIAO" HAY "ĐỀ NGHỊ"
                  ↓
XÁC ĐỊNH PHỤ LỤC
                  ↓
TRA phan_cong.md
                  ↓
TRA quy_che_lam_viec.md
                  ↓
XÁC ĐỊNH NGƯỜI KÝ
                  ↓
HOÀN THIỆN NƠI NHẬN
                  ↓
XUẤT THÔNG BÁO KẾT LUẬN
```

---

# L. NGUYÊN TẮC CUỐI

Một Thông báo kết luận tốt phải trả lời rõ:

```text
CUỘC HỌP NÀO?
↓
AI CHỦ TRÌ?
↓
ĐÃ THẢO LUẬN VẤN ĐỀ GÌ?
↓
NGƯỜI CHỦ TRÌ KẾT LUẬN GÌ?
↓
AI PHẢI LÀM?
↓
PHỐI HỢP VỚI AI?
↓
SẢN PHẨM LÀ GÌ?
↓
HOÀN THÀNH KHI NÀO?
↓
NỘI DUNG NÀO VƯỢT THẨM QUYỀN?
↓
AI CÓ THẨM QUYỀN KÝ THÔNG BÁO?
```

Nguyên tắc:

```text
ĐÚNG CUỘC HỌP
→ ĐÚNG CHỦ TRÌ
→ ĐÚNG Ý KIẾN
→ ĐÚNG KẾT LUẬN
→ ĐÚNG NHIỆM VỤ
→ ĐÚNG ĐƠN VỊ
→ ĐÚNG SẢN PHẨM
→ ĐÚNG DEADLINE
→ ĐÚNG SẮC THÁI CHỈ ĐẠO
→ ĐÚNG NGƯỜI KÝ
```

Nếu chưa đủ căn cứ:

```text
KHÔNG BIẾN Ý KIẾN THÀNH KẾT LUẬN.
KHÔNG TỰ TẠO NHIỆM VỤ.
KHÔNG TỰ TẠO DEADLINE.
KHÔNG TỰ GÁN CƠ QUAN CHỦ TRÌ.
KHÔNG TỰ CHỌN NGƯỜI KÝ.
PHẢI ĐỂ TRỐNG HOẶC YÊU CẦU BỔ SUNG.
```

```

Có hai điểm từ các file thực tế mà tôi cho là rất quan trọng để AI không “học sai”.

Thứ nhất, **không phải Thông báo kết luận nào cũng cần thuật lại toàn bộ diễn biến**. Ví dụ Thông báo về hồ sơ dự án “Xây dựng nền tảng số phục vụ chuyển đổi số cho HĐND tỉnh” đi thẳng từ bối cảnh họp sang 05 nhóm kết luận rất cụ thể và chốt luôn hạn gửi hồ sơ điều chỉnh trước ngày 15/8/2026. :contentReference[oaicite:8]{index=8} Ngược lại, cuộc họp về dự án đầu tư hỗn hợp cần giữ riêng ý kiến Sở Tài chính, Sở Xây dựng rồi mới đến kết luận của chủ trì, vì chính quá trình trao đổi liên ngành là căn cứ để hiểu kết luận cuối cùng. :contentReference[oaicite:9]{index=9}

Thứ hai, **“giao” và “đề nghị” phải được AI phân biệt rất chặt**. Trong Thông báo viễn thông, Sở có thể “giao” Trung tâm Chuyển đổi số nghiên cứu giải pháp kết nối dữ liệu, nhưng với Ban Quản lý Khu kinh tế, Sở Công Thương hoặc doanh nghiệp thì văn bản dùng cách “đề nghị” phù hợp với quan hệ phối hợp liên cơ quan. :contentReference[oaicite:10]{index=10} Đây nên là một hard rule quan trọng trong repo.
```
