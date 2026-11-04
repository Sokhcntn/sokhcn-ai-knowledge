---
title: "Danh bạ điện thoại toàn tỉnh - bản biên tập đầy đủ cho AI/RAG"
source_file: "Danh ba dien thoai toan tinh.xlsx"
source_sheet_directory: "DBDT_25-8-2025"
source_sheet_index: "Mục lục DBĐT 8-2025"
snapshot_label: "DBĐT_25-8-2025"
data_type: "danh bạ cơ quan và thông tin liên hệ cán bộ"
data_sensitivity: "personal_contact_information"
ai_ready: true
rag_ready: true
---

# DANH BẠ ĐIỆN THOẠI TOÀN TỈNH

> **Mục đích biên tập:** Chuyển toàn bộ workbook Excel thành một tài liệu Markdown có cấu trúc để AI tra cứu theo cơ quan, đơn vị, họ tên, chức vụ, số điện thoại, email và địa chỉ. Không tự cập nhật hoặc sửa nội dung ngoài dữ liệu nguồn.

> **Lưu ý:** Tài liệu chứa thông tin liên hệ cá nhân và cơ quan. Chỉ sử dụng trong phạm vi nghiệp vụ/công vụ được phép và nên đối chiếu nguồn mới nhất trước khi liên hệ chính thức.

## 1. Cấu trúc dữ liệu nguồn

- Sheet danh bạ chi tiết: **DBDT_25-8-2025** — 5,816 dòng dữ liệu nguồn.
- Sheet mục lục: **Mục lục DBĐT 8-2025** — 163 dòng dữ liệu nguồn.
- Các trường chính: **STT, Họ và tên, Chức vụ Đảng/Chính quyền, Di động, Cơ quan, Email, Địa chỉ**.
- Thông tin điện thoại bàn, email, website hoặc địa chỉ nếu được ghi trực tiếp trong tiêu đề đơn vị được giữ nguyên.

## 2. Quy tắc tra cứu cho AI

1. Tra theo **tên người**: tìm đúng họ tên, sau đó xác định cơ quan/đơn vị gần nhất ở phía trên.
2. Tra theo **cơ quan/đơn vị**: dùng mục lục để định tuyến, sau đó ưu tiên dữ liệu chi tiết trong phần danh bạ.
3. Không suy diễn số điện thoại, email, địa chỉ hoặc chức vụ khi nguồn để trống.
4. Khi một người có nhiều số điện thoại, giữ nguyên toàn bộ số theo nguồn.
5. Ký hiệu `//`, ô trống hoặc ghi chú bất thường được giữ nguyên để phản ánh chất lượng dữ liệu nguồn.
6. Nếu người dùng hỏi dữ liệu 'mới nhất', phải hiểu đây là ảnh chụp dữ liệu theo workbook nguồn, không mặc nhiên coi là trạng thái hiện hành.

# 3. MỤC LỤC CƠ QUAN, ĐƠN VỊ

> **Ghi chú nguồn:** Đã cập nhật 7/2025

## Các cơ quan đơn vị thuộc Tỉnh ủy

| STT | Cơ quan/đơn vị | Trạng thái | Ghi chú/đầu mối |
|---:|---|---|---|
| 1 | Văn phòng Tỉnh ủy | R |  |
| 2 | Ban Tổ chức Tỉnh ủy | R |  |
| 3 | Ban Tuyên giáo và Dân vận Tỉnh ủy | R |  |
| 4 | Ban Nội chính Tỉnh ủy | R | Lâm Thị Mai Hương |
| 5 | Ủy ban Kiểm tra Tỉnh ủy | R | ledieuubkt2014@gmail.com |
| 6 | Đảng ủy các cơ quan Đảng tỉnh | R | plduong@tayninh.gov.vn |
| 7 | Đảng ủy UBND tỉnh | R |  |
| 8 | Đảng ủy Công an tỉnh | R |  |
| 9 | Đảng ủy Quân sự tỉnh | R |  |
|  | Mặt trận Tổ quốc Việt Nam tỉnh | R |  |
|  | ĐB Quốc hội, HĐND tỉnh | R |  |
|  | UBND tỉnh, Văn phòng UBND tỉnh | R |  |

## Sở Ngành

| STT | Cơ quan/đơn vị | Trạng thái | Ghi chú/đầu mối |
|---:|---|---|---|
| 1 | Sở Công Thương | R |  |
| 2 | Sở Giáo dục và Đào tạo | R | Trần Thị Tam Thể |
| 3 | Sở Khoa học và Công nghệ | R |  |
| 4 | Sở Nội vụ | R |  |
| 5 | Sở Tài chính | R |  |
| 6 | Sở Tư pháp | R |  |
| 7 | Sở Văn hóa, Thể thao và Du lịch | R | Trần Thị Ngọc Niệm |
| 8 | Sở Xây dựng | R |  |
| 9 | Sở Y tế | R |  |
| 10 | Thanh tra tỉnh | R |  |
| 11 | Sở Nông nghiệp và Môi trường | R |  |
| 12 | Sở Ngoại vụ | R |  |
| 13 | Sở Dân tộc - Tôn giáo | R |  |
| 14 | Trường Chính trị tỉnh | R |  |
| 15 | Quỹ Đầu tư Phát triển tỉnh | R |  |
| 16 | Ban Quản lý Khu Kinh tế | R |  |
| 17 | BQL Dự án Đầu tư xây dựng tỉnh Tây Ninh | R | quanglnn@tayninh.gov.vn |
| 18 | BQL Dự án ĐT XD ngành Nông nghiệp và PTNT | R |  |
| 19 | Ban An toàn Giao thông | R |  |
| 20 | BQL các Khu di tích lịch sử Cách Mạng Miền Nam | R | vanthu.bqlmn2024@gmail.com |
| 21 | BQL Khu Du lịch Quốc Gia Núi Bà Đen | R |  |
| 22 | BQL Vườn Quốc Gia Lò Gò - Xa Mát | R |  |
| 23 | Trung tâm phát triển quỹ đất tỉnh | R |  |
| 24 | Báo và Đài Phát thanh Truyền hình | R |  |
| 25 | Phân xã Thông tấn xã Việt Nam | R |  |

## Các cơ quan ngành dọc

| STT | Cơ quan/đơn vị | Trạng thái | Ghi chú/đầu mối |
|---:|---|---|---|
| 1 | Công an tỉnh | R |  |
| 2 | BCH Quân sự tỉnh | R |  |
| 3 | BCH Bộ đội Biên phòng tỉnh | R |  |
| 4 | Thuế tỉnh Tây Ninh | R |  |
| 5 | Chi cục Hải quan khu vực XVII | R |  |
| 6 | Cục Thống kê | R |  |
| 7 | Bảo hiểm xã hội khu vực XXIX. | R |  |
| 8 | Ngân hàng Nhà nước Việt Nam khu vực XIII | R |  |
| 9 | Kho bạc Nhà nước khu vực XVIII | R | minhph01@vst.gov.vn |
| 10 | Ngân hàng Chính sách XH tỉnh | R |  |
| 11 | Tòa án Nhân dân tỉnh | R |  |
| 12 | Việm kiểm sát Nhân dân tỉnh | R |  |
| 13 | Thi hành án dân sự tỉnh | R |  |
| 14 | viễn thông | R |  |
| 15 | bưu điện tỉnh | R |  |
| 16 | Điện lực tỉnh | R | Nguyễn Khắc Thành Đạt |
|  | Các Hội quần chúng, một số Cty | Các hội hiện nay chưa chốt nhân sự chính thức nên ko đưa vào |  |
| 1 | Công ty TNHH MTV 30-4 Tây Ninh | R |  |
| 2 | Công ty TNHH Phát triển xanh Long An | R |  |
| 3 | Công ty TNHH MTV Khai thác Thủy lợi | R |  |
| 4 | Trường Cao đẳng Long An | R |  |
| 5 | Trường Cao đẳng Y tế Long An | R |  |
| 6 | Trường Cao đẳng Nghề Tây Ninh | R |  |
| 7 | Hội Văn học nghệ thuật tỉnh Tây Ninh | R |  |
| 8 | Liên minh Hợp tác xã tỉnh | R | tayninh@vca.org.vn |

## Xã, phường

| STT | Cơ quan/đơn vị | Trạng thái | Ghi chú/đầu mối |
|---:|---|---|---|
| 1 | Phường Long An |  |  |
| 2 | Phường Tân An |  |  |
| 3 | Phường Khánh Hậu |  | Nguyễn Thị Tuyết Hiếu |
| 4 | Phường Kiến Tường |  |  |
| 5 | Phường Thanh Điền |  |  |
| 6 | Phường Hoà Thành |  |  |
| 7 | Phường Long Hoa |  |  |
| 8 | Phường Tân Ninh |  |  |
| 9 | Phường Bình Minh |  |  |
| 10 | Phường Trảng Bàng |  |  |
| 11 | Phường An Tịnh |  |  |
| 12 | Phường Gia Lộc |  |  |
| 13 | Phường Gò Dầu |  |  |
| 14 | Phường Ninh Thạnh |  |  |
| 15 | Xã Tân Hưng |  |  |
| 16 | Xã Hưng Điền |  |  |
| 17 | Xã Vĩnh Thạnh |  |  |
| 18 | Xã Vĩnh Châu |  |  |
| 19 | Xã Vĩnh Hưng |  |  |
| 20 | Xã Tuyên Bình |  | tranthimyhuongxvb@gmail.com |
| 21 | Xã Khánh Hưng |  |  |
| 22 | Xã Bình Hiệp |  |  |
| 23 | Xã Tuyên Thạnh |  | lamvan@tayninh.gov.vn |
| 24 | Xã Mộc Hoá |  |  |
| 25 | Xã Bình Hoà |  |  |
| 26 | Xã Tân Thạnh |  |  |
| 27 | Xã Hậu Thạnh |  |  |
| 28 | Xã Nhơn Hòa Lập |  |  |
| 29 | Xã Nhơn Ninh |  |  |
| 30 | Xã Thạnh Hóa |  |  |
| 31 | Xã Bình Thành |  |  |
| 32 | Xã Thạnh Phước |  |  |
| 33 | Xã Tân Tây |  |  |
| 34 | Xã Thủ Thừa |  |  |
| 35 | Xã Mỹ An |  |  |
| 36 | Xã Mỹ Thạnh |  |  |
| 37 | Xã Tân Long |  |  |
| 38 | Xã Mỹ Quý |  |  |
| 39 | Xã Đông Thành |  |  |
| 40 | Xã Đức Huệ |  | daothelinh5@gmail.com |
| 41 | Xã Hậu Nghĩa |  |  |
| 42 | Xã Đức Hòa |  |  |
| 43 | Xã Hiệp Hoà |  |  |
| 44 | Xã Đức Lập |  |  |
| 45 | Xã Mỹ Hạnh |  |  |
| 46 | Xã An Ninh |  |  |
| 47 | Xã Hoà Khánh |  |  |
| 48 | Xã Bến Lức |  | hladuy.bluc@tayninh.gov.vn |
| 49 | Xã Thạnh Lợi |  |  |
| 50 | Xã Bình Đức |  |  |
| 51 | Xã Lương Hoà |  |  |
| 52 | Xã Mỹ Yên |  |  |
| 53 | Xã Cần Đước |  |  |
| 54 | Xã Long Cang |  |  |
| 55 | Xã Rạch Kiến |  |  |
| 56 | Xã Mỹ Lệ |  |  |
| 57 | Xã Tân Lân |  |  |
| 58 | Xã Long Hựu |  |  |
| 59 | Xã Cần Giuộc |  |  |
| 60 | Xã Phước Lý |  | ubndphuocly2@tayninh.gov.vn |
| 61 | Xã Mỹ Lộc |  |  |
| 62 | Xã Phước Vĩnh Tây |  |  |
| 63 | Xã Tân Tập |  |  |
| 64 | Xã Tân Trụ |  |  |
| 65 | Xã Nhựt Tảo |  |  |
| 66 | Xã Vàm Cỏ |  |  |
| 67 | Xã Tầm Vu |  |  |
| 68 | Xã Thuận Mỹ |  |  |
| 69 | Xã An Lục Long |  |  |
| 70 | Xã Vĩnh Công |  | mybinh8083@gmail.com |
| 71 | Xã Tân Biên |  |  |
| 72 | Xã Tân Lập |  |  |
| 73 | Xã Thạnh Bình |  | Nguyễn Chi Bao (chibao1993@tayninh.gov.vn) |
| 74 | Xã Trà Vong |  |  |
| 75 | Xã Tân Châu |  | Đặng Ngọc Hà |
| 76 | Xã Tân Đông |  |  |
| 77 | Xã Tân Hoà |  |  |
| 78 | Xã Tân Hội |  |  |
| 79 | Xã Tân Phú |  | ngoctam1990@tayninh.gov.vn |
| 80 | Xã Tân Thành |  |  |
| 81 | Xã Hưng Thuận |  |  |
| 82 | Xã Phước Chỉ |  |  |
| 83 | Xã Bến Cầu |  |  |
| 84 | Xã Long Thuận |  |  |
| 85 | Xã Long Chữ |  |  |
| 86 | Xã Phước Thạnh |  |  |
| 87 | Xã Thạnh Đức |  | bichtuyen1985@tayninh.gov.vn |
| 88 | Xã Truông Mít |  |  |
| 89 | Xã Phước Vinh |  |  |
| 90 | Xã Ninh Điền |  |  |
| 91 | Xã Hoà Hội |  |  |
| 92 | Xã Hảo Đước |  |  |
| 93 | Xã Châu Thành |  | quoctoan1987@tayninh.gov.vn |
| 94 | Xã Dương Minh Châu |  |  |
| 95 | Xã cầu Khởi |  |  |
| 96 | Xã Lộc Ninh |  |  |

# 4. DANH BẠ CHI TIẾT

Dữ liệu dưới đây được giữ theo đúng thứ tự của sheet `DBDT_25-8-2025`.

## Các cơ quan đơn vị thuộc Tỉnh ủy

### Thường trực Tỉnh ủy

- Nhóm: 1
- Mã/STT nhóm: 1

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 1 | Nguyễn Văn Quyết | Bí thư Tỉnh ủy | 0965 799 899 |  |  |  |
| 2 | Nguyễn Mạnh Hùng | Phó Bí thư Thường trực Tỉnh uỷ | 0918 383 839 |  |  |  |

### Văn phòng Tỉnh ủy / ĐT bàn: 02723 826232; 0273 822134; email: vptu tayninh gov vn

- Nhóm: 1
- Mã/STT nhóm: 2

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 5 | Trần Thế Luân | CVP Tỉnh ủy | 0907 137 168 |  |  |  |
| 6 | Lê Quốc An | Phó CVP Tỉnh ủy | 0918 128 453 |  |  |  |
| 7 | Huỳnh Thanh Phong | Phó CVP Tỉnh ủy | 0918 499 459 |  |  |  |
| 8 | Vũ Ngọc Hà | Phó CVP Tỉnh ủy | 0913 443 797 |  |  |  |
| 9 | Châu Thu Vân | Phó CVP Tỉnh ủy | 0906 489 484 |  |  |  |
| 10 | Bùi Văn Hận | Phó CVP Tỉnh ủy, Thư ký Bí thư | 0915 551 711 |  |  |  |
| 11 | Hồ Thanh Bình | Trưởng Phòng Tổng hợp | 0937 648 909 |  |  |  |
| 12 | Tạ Phương Bình | Phó Trưởng Phòng Tổng hợp | 0908 780 208 |  |  |  |
| 13 | Trần Võ Thanh Hồng Linh | Phó Trưởng Phòng Tổng hợp | 0983 196 931 |  |  |  |
| 14 | Nguyễn Văn Luôn | Phó Trưởng Phòng Tổng hợp | 0918 611 922 |  |  |  |
| 15 | Trần Thị Tú Anh | Phó Trưởng Phòng Tổng hợp | 0918 226 207 |  |  |  |
| 16 | Đinh Hoàng Phong | Phó Trưởng Phòng Tổng hợp | 0916 671 189 |  |  |  |
| 17 | Phan Thị Mỹ Nương | Trưởng Phòng Hành chính, lưu trữ | 0764 647 879 |  |  |  |
| 18 | Nguyễn Thiện Huân | Phó Trưởng Phòng Hành chính, lưu trữ | 0977 747 806 |  |  |  |
| 19 | Đỗ Thị Hồng Hạnh | Trưởng Phòng Tài chính Đảng | 0904 532 228 |  |  |  |
| 20 | Trần Thị Thu Trâm | Phó Trưởng Phòng Tài chính Đảng | 0977 033 727 |  |  |  |
| 21 | Văn Thị Nhân | Phó Trưởng Phòng Tài chính Đảng | 0396 933 331 |  |  |  |
| 22 | Nguyễn Phú Tĩ | Trưởng Phòng Chuyển đổi số - Cơ yếu | 0815 382 777 |  |  |  |
| 23 | Hồ Huỳnh Tuyến | Trưởng phòng Quản trị | 0906 333 038 |  |  |  |
| 24 | Ngô Thị Phượng | Phó Trưởng Phòng Quản trị | 0985 495 275 |  |  |  |

### Ban Tổ chức Tỉnh ủy - ĐT: 02723 826 112 / Địa chỉ: Số 118 Trương Định, phường Long An, tỉnh Tây Ninh

- Nhóm: 1
- Mã/STT nhóm: 3

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 1 | Võ Đức Trong | Ủy viên Ban TVTU - Trưởng Ban | 0918 430 310 |  |  |  |
| 2 | Võ Thanh Phong | Tỉnh ủy viên - Phó TB Thường trực | 0918 589 063 |  |  |  |
| 3 | Lê Anh Tuấn | Tỉnh ủy viên - Phó Trưởng ban | 0913 647 855 |  |  |  |
| 4 | Bùi Quốc Bảo | Tỉnh ủy viên - Phó Trưởng ban | 0909 738 908 |  |  |  |
| 5 | Nguyễn Tuấn Khanh | Phó Trưởng ban | 0982 341 118 |  |  |  |
| 6 | Nguyễn Dương Phong Linh | Phó Trưởng ban | 0918 266 008 |  |  |  |
| 7 | Lê Thị Khuyên | Phó Trưởng ban | 0945 727 827 |  |  |  |
| 8 | Lê Quốc Gấm | Phó Trưởng ban | 0918 781 520 |  |  |  |
| 9 | Lê Văn Thành | Trưởng phòng Tổ chức cán bộ | 0386 457 022 |  |  |  |
| 13 | Nguyễn Thị Kim Trọng | Phó Trưởng phòng Tổ chức cán bộ | 0914 450 278 |  |  |  |
| 14 | Phan Hữu Hiệp | Phó Trưởng phòng Tổ chức cán bộ | 0989 664 792 / 0932 634 318 |  |  |  |
| 15 | Nguyễn Thị Bích Hằng | Phó Trưởng phòng Tổ chức cán bộ | 0949 368 164 |  |  |  |
| 10 | Nguyễn Thành Giang | Trưởng phòng Tổ chức đảng, đảng viên | 0903 910 653 |  |  |  |
| 16 | Nguyễn Thị Thu Loan | Phó TP Tổ chức đảng, đảng viên | 0918 019 470 |  |  |  |
| 17 | Lê Thị Ngọc Diễm | Phó TP Tổ chức đảng, đảng viên | 0913 393 134 |  |  |  |
| 11 | Trần Thị Xuân Hương | Trưởng phòng Bảo vệ chính trị nội bộ | 0915 699 811 |  |  |  |
| 18 | Nguyễn Thanh Tuấn | Phó Trưởng phòng Bảo vệ chính trị nội bộ | 0919 104 532 |  |  |  |
| 19 | Lương Hoàng Tú | Phó Trưởng phòng Bảo vệ chính trị nội bộ | 0988 043 855 |  |  |  |
| 20 | Mai Thị Huyền Nga | Phó Trưởng phòng Bảo vệ chính trị nội bộ | 0913 660 476 |  |  |  |
| 12 | Lê Thụy Phương Vy | Chánh Văn phòng | 0907 585 500 |  |  |  |
| 21 | Nguyễn Xuân Hòa | Phó Chánh Văn phòng | 0948 544 790 |  |  |  |
| 22 | Phạm Thị Kim Anh | Phó Chánh Văn phòng | 0908 336 416 |  |  |  |
| 23 | Võ Xuân Lin | Phó Chánh Văn phòng | 0919 935 369 |  |  |  |
| 24 | Nguyễn Công Tiếp | Phó Chánh Văn phòng | 0919 249 319 |  |  |  |

### Ban Tuyên giáo và Dân vận Tỉnh ủy, ĐT bàn: 02723826183 / Đ/c: Số 118, Trương Định, phường Long An, tỉnh Tây Ninh

- Nhóm: 1
- Mã/STT nhóm: 4

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 1 | Nguyễn Thị Xuân Hương | UV.BTVTU, Trưởng ban | 0983 705 743 |  |  |  |
| 2 | Võ Trần Tuấn Thanh | TUV, Phó Trưởng ban thường trực | 0979 777 713 |  |  |  |
| 3 | Thành Từ Dũ | TUV, Phó Trưởng ban | 0913 955 965 |  |  |  |
| 4 | Huỳnh Thị Thu Năm | TUV, Phó Trưởng ban | 0943 067 070 |  |  |  |
| 5 | Nguyễn Thuý Oanh | Phó Trưởng Ban | 0913 955 112 |  |  |  |
| 6 | Mai Đặng Thảo Nguyên | Phó Trưởng Ban | 0835 867 999 |  |  |  |
| 7 | Phùng Tấn Tú | Phó Trưởng Ban | 0942 707 272 |  |  |  |
| 8 | Đinh Tấn Nhàn | Chánh Văn phòng | 0908 000 242 |  |  |  |
| 9 | Trần Hoàng Hải | TP Tuyên truyền - Báo chí - Xuất bản | 0965 512 639 |  |  |  |
| 10 | Lê Thị Thu Thảo | TP Phòng Khoa giáo, Văn hoá - Văn nghệ | 0918 371 888 |  |  |  |
| 11 | Huỳnh Thị Phương Linh | Trưởng phòng Thông tin - Tổng hợp | 0975 280 228 |  |  |  |
| 12 | Nguyễn Thanh Huy | Trưởng phòng Phòng Đoàn thể và các hội | 0918 976 653 |  |  |  |
| 13 | Nguyễn Tấn Hải | Phó Chánh Văn phòng | 0907 973 793 |  |  |  |
| 14 | Tô Thị Kim Nhung | Phó Chánh Văn phòng | 0949 487 879 |  |  |  |
| 15 | Ngô Thanh Bình | Phó TP, phụ trách Phòng Dân vận các cơ quan nhà nước, dân tộc và tôn giáo | 0917 541 158 |  |  |  |
| 16 | Lê Văn Hùng | Phó Trưởng phòng Dân vận các cơ quan nhà nước, dân tộc và tôn giáo | 0917 378 485 |  |  |  |
| 17 | Hoàng Thị Minh Thùy | Phó Trưởng phòng Đoàn thể và các hội | 0988 298 428 |  |  |  |
| 18 | Huỳnh Thanh Tâm | Phó Trưởng phòng Đoàn thể và các hội | 0907 633 335 |  |  |  |
| 19 | Nguyễn Thị Chung | Phó Trưởng phòng Khoa giáo, Văn hoá - Văn nghệ | 0903 129 254 |  |  |  |

### Ban Nội chính Tỉnh ủy / Đ/c: 40 Cách Mạng Tháng 8, Phường Long An, Tỉnh Tây Ninh

- Nhóm: 1
- Mã/STT nhóm: 5

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 1 | Trương Nhật Quang | UV Ban TVTU - Trưởng ban | 0913 884 097 |  |  |  |
| 2 | Nguyễn Thị Thúy | TUV, Phó Trưởng ban | 0888 180 848 |  |  |  |
| 3 | Nguyễn Thành Tiễn | TUV, Phó Trưởng ban | 0913 955 053 |  |  |  |
| 4 | Hồ Thành Hiên | Phó Trưởng ban | 0913 988 727 |  |  |  |
| 5 | Nguyễn Sơn | Phó Trưởng ban | 0913 959 777 |  |  |  |
| 6 | Lưu Tấn Sĩ | Phó Trưởng ban | 0979 898 619 |  |  |  |
| 7 | Nguyễn Tấn Dũng | Chánh Văn phòng | 0918 821 668 |  |  |  |
| 8 | Phan Đức Trung | TP TDCT PCTNLPTC | 0909 211 766 |  |  |  |
| 9 | Nguyễn Hoàng Hiệp | TP TDCT Nội chính và CCTP | 0918 848 072 |  |  |  |
| 10 | Nguyễn Thế Triều | TP TDCT xử lý đơn, thư và TCD | 0913 884 100 |  |  |  |

### Ủy ban Kiểm tra Tỉnh ủy Tây Ninh - ĐT bàn: 02723 826 114

- Nhóm: 1
- Mã/STT nhóm: 5

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 1 | Nguyễn Thành Vững | Chủ nhiệm | 0918 127 685 |  |  |  |
| 2 | Trương Văn Hoàn | Phó Chủ nhiệm | 0913 182 555 |  |  |  |
| 3 | Phạm Huy Sơn | Phó Chủ nhiệm | 0945 336 339 |  |  |  |
| 4 | Ngô Thị Nhẫn | Phó Chủ nhiệm | 0976 427 555 |  |  |  |
| 5 | Nguyễn Thị Hồng Loan | Phó Chủ nhiệm | 0918 949 513 |  |  |  |
| 6 | Nguyễn Thái Bình | Phó Chủ nhiệm | 0918 793 292 |  |  |  |
| 7 | Trần Hữu Trọng | Ủy viên | 0976 144 256 |  |  |  |
| 8 | Nguyễn Thị Tuyết Oanh | Ủy viên | 0918 895 248 |  |  |  |
| 9 | Huỳnh Hữu Lập | Ủy viên | 0909 391 646 |  |  |  |
| 10 | Lê Hữu Bình | Ủy viên | 0918 623 627 |  |  |  |
| 11 | Nguyễn Thị Tuyết Nhung | Ủy viên | 0915 663 909 |  |  |  |
| 12 | Nguyễn Thị Thu Phương | Ủy viên | 0949 465 365 |  |  |  |
| 13 | Dương Văn Truyên | Ủy viên | 0387 827 952 |  |  |  |
| 14 | Trần Thế Phong | Ủy viên | 0909 243 381 |  |  |  |
| 15 | Lê Thị Cẩm Lan | Chánh Văn phòng | 0949 947 270 |  |  |  |
| 16 | Ngô Thị Huỳnh Loan | PTP phụ trách phòng Nghiệp vụ III | 0985 538 588 |  |  |  |
| 17 | Võ Thúy Tâm | PTP phụ trách phòng Nghiệp vụ II | 0907 667 680 |  |  |  |
| 18 | Khúc Tân Biên | PTP phụ trách phòng Nghiệp vụ I | 0902 678 090 |  |  |  |
| 19 | Nguyễn Thị Cẩm Nhan | Phó Chánh Văn phòng | 0908 351 367 |  |  |  |
| 20 | Đặng Minh Hải | PTP Nghiệp vụ I | 0938 934 224 |  |  |  |
| 21 | Mai Ngọc Hậu | PTP Nghiệp vụ III | 0975 368 228 |  |  |  |
| 22 | Trần Thị Phương Châu | PTP Nghiệp vụ III | 0916 118 220 |  |  |  |

### ĐẢNG ỦY CÁC CƠ QUAN ĐẢNG TỈNH TÂY NINH / Đ/c: số 53, Nguyễn Huệ, phường Long An, tỉnh Tây Ninh / ĐT: 02723 838 414; Email: dukcqt@tayninh gov vn;

- Nhóm: 1
- Mã/STT nhóm: 6

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 1 | Huỳnh Thanh Phương | TUV - PBT Đảng ủy chuyên trách | 0918 368 987 |  |  |  |
| 2 | Lê Quang Hướng | Phó CVP Đảng ủy | 0889 773 772 |  |  |  |
| 3 | Hồng Việt Tân | PTB Tổ chức Đảng ủy | 0909 777 130 |  |  |  |
| 4 | Lưu Hồng Ân | PTB Tổ chức Đảng ủy | 0983 829 369 |  |  |  |
| 5 | Hồ Thị Ngọc Thúy | PCN UBKT Đảng ủy | 0943 949 949 |  |  |  |
| 6 | Nguyễn Quốc Phong | PCN UBKT Đảng ủy | 0931 550 623 |  |  |  |
| 7 | Trần Thị Cẩm Lợi | PTB Tuyên giáo và Dân vận | 0917 692 369 |  |  |  |
| 8 | Đặng Đăng Khoa | CV Ban Tuyên giáo và Dân vận | 0976 852 852 |  |  |  |
| 9 | Nguyễn Huỳnh | CV Ban Tuyên giáo và Dân vận | 0973 086 957 |  |  |  |
| 10 | Châu Thị Thanh Thảo | Văn thư Đảng ủy | 0947 106 783 |  |  |  |
| 11 | Trương Thị Thanh Loan | Kế toán Đảng ủy | 0968 655 156 |  |  |  |
| 12 | Phan Lê Dương | CV Văn phòng Đảng ủy | 0383 817 790 |  |  |  |
| 13 | Nguyễn Sơn Tùng | CV Ban Tổ chức Đảng ủy | 0792 688 988 |  |  |  |
| 14 | Hồ Phạm Ngọc Châu | CV Ban Tổ chức Đảng ủy | 0973 726 559 |  |  |  |
| 15 | Nguyễn Ngọc Giang | Ủy viên UBKT Đảng ủy | 0918 383 789 |  |  |  |

### Đảng ủy UBND tỉnh / ĐT bàn: 02723 957 679; email: duubndla@tayninh.gov.vn

- Nhóm: 1
- Mã/STT nhóm: 7

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 1 | Nguyễn Văn Cường | Phó Bí thư chuyên trách | 0948 727 688 |  |  |  |
| 2 | Hồ Thị Ngọc Dung | Phó CVP Đảng ủy | 0989 959 626 |  |  |  |
| 3 | Nguyễn Minh Thắng | Phó CVP Đảng ủy | 0985 568 468 |  |  |  |
| 4 | Trần Đức Trọng | PTB Tổ chức Đảng ủy | 0909 241 451 |  |  |  |
| 5 | Nguyễn Quốc Ánh | PTB Tổ chức Đảng ủy | 0983 033 303 |  |  |  |
| 6 | Lê Thị Kim Kha | PCN UBKT Đảng ủy | 0944 887 197 |  |  |  |
| 7 | Phạm Minh Trí | PTB Tuyên giáo và Dân vận | 0918 774 546 |  |  |  |
| 8 | Phan Thị Cẩm Vân | PTB Tuyên giáo và Dân vận | 0975 992 307 |  |  |  |

### Đảng ủy Công an tỉnh Tây Ninh

- Nhóm: 1
- Mã/STT nhóm: 8

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 1 | Thiếu tướng Vũ Như Hà | Giám đốc | 0903 731 083 |  |  |  |
| 2 | Phan Văn Triều | Phó Giám đốc | 0913 955 466 |  |  |  |
| 3 | Trần Văn Luận | Phó Giám đốc | 0918 227 254 |  |  |  |
| 4 | Lê Văn Thuận | Phó Giám đốc | 0937 333 010 |  |  |  |
| 5 | Lê Trung Ái | Phó Giám đốc | 0905 228 234 |  |  |  |
| 6 | Nguyễn Quốc Toàn | Phó Giám đốc | 0989 990 268 |  |  |  |
| 7 | PhạmThanh Tâm | Phó Giám đốc | 0983 446 472 |  |  |  |

### Đảng ủy Quân sự tỉnh Tây Ninh

- Nhóm: 1
- Mã/STT nhóm: 9

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 1 | Đồng chí Nguyễn Thành Tâm | UV Ban TVTU, Chỉ huy trưởng | 0979 290 568 |  |  |  |
| 2 | Đồng chí Nguyễn Thanh Phong | Chính ủy | 0989 006 871 |  |  |  |
| 3 | Đồng chí Trần Đình Hưng | Phó CHT, Tham mưu trưởng | 0918 128 215 |  |  |  |
| 4 | Đồng chí Nguyễn Minh Tấn | Phó Chính ủy | 0965 737 573 |  |  |  |
| 5 | Đồng chí Ngô Khánh | Phó Chính ủy | 0982 102 008 |  |  |  |
| 6 | Đồng chí Nguyễn Đình Huân | Phó Chỉ huy trưởng | 0906 757 568 |  |  |  |
| 7 | Đồng chí Nguyễn Thành Đạt | Phó Chỉ huy trưởng | 0975 964 717 |  |  |  |
| 8 | Đồng chí Hà Thanh Tuấn | Phó Chỉ huy trưởng | 0985 712 175 |  |  |  |

### Mặt trận Tổ quốc Việt Nam tỉnh

- Nhóm: 1
- Mã/STT nhóm: 10

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 1 | Nguyễn Thanh Hải | Phó Bí thư Tỉnh uỷ, CT UBMTTQ VN tỉnh | 0918 602 244 |  |  |  |
| 2 | Nguyễn Thị Thu Trinh | UV. BTV Tỉnh uỷ, PCT TT MTTQ VN tỉnh | 0944 827 993 |  |  |  |
| 3 | Nguyễn Tiến Tân | PCT MTTQ VN tỉnh, Chánh Văn phòng | 0933 017 817 |  |  |  |
| 4 | Lê Thị Cẩm Tú | PCT MTTQ VN tỉnh, Trưởng ban TCKT | 0914 025 938 |  |  |  |
| 5 | Hồ Đức Hải | Phó Chủ tịch MTTQ VN tỉnh, / TB Dân chủ, Giám sát và Phản biện XH | 0987886979 |  |  |  |
| 6 | Võ Quốc Thắng | PCT MTTQ VN tỉnh, / TB Ban Tuyên giáo, Công tác XH | 0918.400.333 |  |  |  |
| 7 | Trần Hải Phú | PCT MTTQ VN tỉnh, Bí thư Tỉnh Đoàn | 0909453250 |  |  |  |
| 8 | Lê Thị Ngọc Yến | TUV, PCT MTTQ VN tỉnh, CT Hội Nông dân | 0982 634 569 |  |  |  |
| 9 | Phan Thị Thuỳ Vân | TUV, PCT MTTQ VN tỉnh, CT Hội LHPN tỉnh | 0908414231 |  |  |  |
| 10 | Nguyễn Văn Kìa | PCT MTTQ VN tỉnh, CTHội CCB tỉnh | 0982 959 982 |  |  |  |
| 11 | Trần Lê Duy | TUV, PCT MTTQ VN tỉnh, CT LĐLĐ tỉnh | 0898.776.465 |  |  |  |

### Văn phòng

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 1 | Nguyễn Văn Chiểu | Phó Chánh văn phòng | 0333394959 |  |  |  |
| 2 | Phùng Thị Thanh Thúy | Phó Chánh văn phòng | 0902369910 |  |  |  |
| 3 | Nguyễn Thái Hòa | Phó Chánh văn phòng | 0937177772 |  |  |  |
| 4 | Võ Thị Thu Thảo | Phó Chánh văn phòng | 0988383813 |  |  |  |
| 5 | Lê Thanh Tiếp | Phó Chánh văn phòng | 0933028992 |  |  |  |

### Ban Tổ chức Kiểm tra

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 1 | Đặng CDanh | Phó Trưởng ban | 0948869997 |  |  |  |
| 2 | Trần Thị Kiều Hoanh | Phó Trưởng ban | 0908741174 |  |  |  |
| 3 | Nguyễn Huỳnh Giang | Phó Trưởng ban | 0916256508 |  |  |  |

### Ban Dân chủ, Giám sát và Phản biện xã hội

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 1 | Hồ Mộng Thu | Phó Trưởng ban | 0944955919 |  |  |  |
| 2 | Nguyễn Thị Lệ Uyên | Phó Trưởng ban | 0833118573 |  |  |  |
| 3 | Lê Minh Mẫn | Phó Trưởng ban | 0931354167 |  |  |  |

### Ban Tuyên giáo, Công tác xã hội

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 1 | Nguyễn Thị Ngọc Cẩm | Phó Trưởng ban | 0942.678.503 |  |  |  |
| 2 | Châu Trần Nhật Minh | Phó Trưởng ban | 0933.485.008 |  |  |  |
| 3 | Võ Thúy An | Phó Trưởng ban | 0949.405.062 |  |  |  |

### Ban Công tác Đoàn và Thanh thiếu nhi

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 1 | Phạm Văn Hậu | Phó Bí thư Tỉnh Đoàn kiêm Trưởng ban | 0389558225 |  |  |  |
| 2 | Nguyễn Thị Tố Mi | Phó Trưởng ban | 0932414985 |  |  |  |
| 3 | Hồ Thị Thùy Trang | Phó Trưởng ban | 0978656061 |  |  |  |
| 4 | Lê Xuân Thịnh | Phó Trưởng ban | 0946113191 |  |  |  |
| 5 | Phạm Hồng Quân | Phó Trưởng ban | 0326948980 |  |  |  |
| 6 | Phạm Trần Thiên Tú | Phó Trưởng ban | 0966311108 |  |  |  |
| 7 | Nguyễn Xuân Hòa | Phó Trưởng ban | 0886321890 |  |  |  |
| 8 | Trần Nguyễn Trúc Phượng | Phó Trưởng ban | 0976657676 |  |  |  |

### Ban Công tác Nông dân

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 1 | Ngô Thanh Tuyền | Phó Chủ tịch HND tỉnh kiêm Trưởng ban | 0918 430 096 |  |  |  |
| 2 | Đặng Thị Thu Thủy | Phó Trưởng ban | 0966 712 487 |  |  |  |
| 3 | Trần Thị Thanh Thúy | Phó Trưởng ban | 0908 906 517 |  |  |  |
| 4 | Trần Nhật Đông | Phó Trưởng ban | 0918 000 137 |  |  |  |
| 5 | Nguyễn Thanh Hiếu | Phó Trưởng ban | 0912 946 679 |  |  |  |
| 6 | Nguyễn Minh Tuấn | Phó Trưởng ban | 0909 108 797 |  |  |  |
| 7 | Trần Gia | Phó Trưởng ban | 0833 579 808 |  |  |  |
| 8 | Nguyễn Trung Tướng | Phó Trưởng ban | 0945 096 775 |  |  |  |

### Ban Công tác Phụ nữ

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 1 | Võ Thị Thuý Yên | Phó Chủ tịch Hội LHPN tỉnh kiêm Trưởng ban | 0987790805 |  |  |  |
| 2 | Nguyễn Thị Kim Liên | Phó Chủ tịch Hội LHPN tỉnh | 083887111 |  |  |  |
| 3 | Nguyễn Thị Kim Loan | Phó Trưởng ban | 0976948448 |  |  |  |
| 4 | Đỗ Thị Thùy Dung | Phó Trưởng ban | 0933970365 |  |  |  |
| 5 | Vũ Thị Vân | Phó Trưởng ban | 0941489550 |  |  |  |
| 6 | Nguyễn Thị Thu Trúc | Phó Trưởng ban | 0917174585 |  |  |  |
| 7 | Nguyễn Thị Châu Thùy | Phó Trưởng ban | 0368595820 |  |  |  |
| 8 | Phạm Huỳnh Yến Anh | Phó Trưởng ban | 0938392878 |  |  |  |
| 9 | Tạ Ngọc Huệ | Phó Trưởng ban | 0984299158 |  |  |  |
| 10 | Nguyễn Thị Mỹ Kiều | Phó Trưởng ban | 0933661900 |  |  |  |

### Ban Công tác Cựu chiến binh

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 1 | Nguyễn Văn Đẹp | PCT Hội CCB tỉnh kiêm Trưởng ban | 0913 107 472 |  |  |  |
| 2 | Nguyễn Văn Một | PCT Hội CCB tỉnh | 0982 415 315 |  |  |  |
| 3 | Nguyễn Tấn Đảo | PCT Hội CCB tỉnh | 0983 396 855 |  |  |  |
| 4 | Đỗ Văn Thu | PCT Hội CCB tỉnh | 0913 614 524 |  |  |  |
| 5 | Phạm Thành Thật | PCT Hội CCB tỉnh | 0918 160 012 |  |  |  |
| 6 | Nguyễn Duy Thành | Phó Trưởng ban | 0366 220 963 |  |  |  |
| 7 | Nguyễn Đình Thanh | Phó Trưởng ban | 0917 119 421 |  |  |  |
| 8 | Võ Tấn Chính | Phó Trưởng ban | 0983 283 411 |  |  |  |
| 9 | Tạ Tiến Minh | Phó Trưởng ban | 0982 300 865 |  |  |  |
| 10 | Phạm Văn Tý | Phó Trưởng ban | 0913 169 176 |  |  |  |
| 11 | Nguyễn Ngọc Vũ | Phó Trưởng ban | 0918 894 303 |  |  |  |

### Ban Công tác công đoàn

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 1 | Nguyễn Hoài Thanh | PCT LĐLĐ tỉnh kiêm Trưởng ban | 0947.818.828 |  |  |  |
| 2 | Phạm Thị Quyên | PCT LĐLĐ tỉnh | 0919.884.099 |  |  |  |
| 3 | Đoàn Thụy Trúc Châu | Phó Trưởng ban | 0919.853.788 |  |  |  |
| 4 | Cao Quốc Hòa | Phó Trưởng ban | 0982.990.018 |  |  |  |
| 5 | Nguyễn Thị Ngọc Loan | Phó Trưởng ban | 0792.811.025 |  |  |  |
| 6 | Trang Hồng Thảo | Phó Trưởng ban | 0933.433.865 |  |  |  |
| 7 | Phạm Thành Thêm | Phó Trưởng ban | 0977.690.009 |  |  |  |

### Ban công đoàn khu công nghiệp

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 1 | Dương Đại Lộc | PCT LĐLĐ tỉnh kiêm Trưởng ban | 0917.822.852 |  |  |  |
| 2 | Nguyễn Phước Đạt | Phó Trưởng ban | 0907.458.827 |  |  |  |
| 3 | Trần Văn Hòa | Phó Trưởng ban | 0919.105.854 |  |  |  |
| 4 | Nguyễn Hải Đăng | Phó Trưởng ban | 0832.425.135 |  |  |  |
| 5 | Nguyễn Trọng Danh | Phó Trưởng ban | 0976.272.755 |  |  |  |

### Đoàn ĐBQH tỉnh Tây Ninh / Đ/c: Số 28 Trương CXưởng, phường Long An, tỉnh Tây Ninh / ĐT: 02723 676 757

- Nhóm: 1
- Mã/STT nhóm: 11

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 1 | Phạm Hùng Thái | Phó Bí thư TU, Trưởng đoàn ĐBQH tỉnh | 0913 956 020 |  |  |  |
| 2 | Hoàng Thị Thanh Thuý | Tỉnh uỷ viên, Phó TĐ ĐBQH tỉnh | 0909 929 457 |  |  |  |
| 3 | Lê Thị Song An | Tỉnh uỷ viên, Phó TĐ ĐBQH tỉnh | 0975 831 881 |  |  |  |
| 4 | Nguyễn Trọng Nghĩa | Ủy viên Bộ Chính trị, Bí thư TWĐ, / TB Tuyên giáo và Dân vận Trung ương |  |  |  |  |
| 5 | Nguyễn Thanh Hải | Phó Bí thư TU, Chủ tịch UBMTTQVN tỉnh | 0918 602 244 |  |  |  |
| 6 | Lê Tấn Tới | Ủy viên BCH TWĐ, Ủy viên UBTV Quốc hội, CN Ủy ban Quốc phòng, An ninh và Đối ngoại của QH | 0913 892 747 |  |  |  |
| 7 | Nguyễn Mạnh Tiến | PCN Ủy ban Quốc phòng, An ninh và Đối ngoại của Quốc hội | 0978 931 111 |  |  |  |
| 8 | Hoàng Văn Liên | PCN Ủy ban Pháp luật và Tư pháp của Quốc hội | 0913 611 323 |  |  |  |
| 9 | Huỳnh Thanh Phương | Tỉnh ủy viên, Phó Bí thư chuyên trách Đảng ủy các cơ quan Đảng tỉnh | 0918 368 987 |  |  |  |
| 10 | Trần Hữu Hậu | Ủy viên Ủy ban Pháp luật và Tư pháp của Quốc hội, CT Hiệp hội Doanh nghiệp tỉnh | 0903 904 021 |  |  |  |
| 11 | Phan Thị Mỹ Dung | Tỉnh uỷ viên, GĐ Sở Tư pháp | 0918 069 359 | 02723 829 524 |  |  |
| 12 | Nguyễn Hoàng Uyên | Phó GĐ Sở Y tế | 0909 676 069 | 02723 823 784 |  |  |
| 13 | Trần Quốc Quân | Bí thư Đảng ủy Tân Lân | 0917 397 307 |  |  |  |

### Thường trực và các Ban của HĐND tỉnh

- Nhóm: 1
- Mã/STT nhóm: 12

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 1 | Nguyễn Mạnh Hùng | Phó Bí thư Thường trực Tỉnh uỷ, / Chủ tịch HĐND tỉnh | 0918 383 839 |  |  |  |
| 2 | Nguyễn Đài Thy | Uỷ viên Ban Thường vụ Tỉnh uỷ, / Phó Chủ tịch Thường trực HĐND tỉnh | 0919 655 999 | 02723 826 221 |  |  |
| 3 | Đặng Thị Ngọc Mai | Tỉnh uỷ viên, Phó Chủ tịch HĐND tỉnh | 0918 976 633 |  |  |  |
| 4 | Nguyễn Hồng Sơn | Tỉnh uỷ viên, Phó Chủ tịch HĐND tỉnh | 0913 646 939 |  |  |  |
| 5 | Nguyễn Hoàng Nam | Tỉnh ủy viên, TB Kinh tế - Ngân sách HĐND tỉnh | 0901 190 779 | 02723 828 685 |  |  |
| 6 | Hồ Văn Xuân | PTB Kinh tế - Ngân sách HĐND tỉnh | 0909 301 160 | 02723 830 966 |  |  |
| 7 | Phạm Văn Đặng | TB Pháp chế HĐND tỉnh | 0983 006 061 |  |  |  |
| 8 | Võ Quốc Khánh | PTB Pháp chế HĐND tỉnh | 0909 565 323 | 02723 986 699 |  |  |
| 9 | Nguyễn Thị Hồng Phúc | TB Văn hoá - Xã hội HĐND tỉnh | 0912 834 849 | 02723 599 345 |  |  |
| 10 | Nguyễn Việt Cường | PTB Văn hoá – Xã hội HĐND tỉnh | 0909 636 571 | 02723 828 617 |  |  |

### Văn phòng Đoàn ĐBQH và HĐND tỉnh

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 1 | Phạm Trung Chánh | Chánh Văn phòng | 0913 138 880 | 02723 676 997 |  |  |
| 2 | Lâm Thị Kim Chi | Phó Chánh Văn phòng | 0918 945 379 |  |  |  |
| 3 | Nguyễn Tuyết Thư | Phó Chánh Văn phòng | 0907 381 820 |  |  |  |
| 4 | Trịnh Quang Hiền | Phó Chánh Văn phòng | 0913 624 952 | 02723 676 626 |  |  |
| 5 | Lê Huỳnh Phúc | Phó Chánh Văn phòng | 0908 655 001 |  |  |  |
| 6 | Nguyễn Quốc Phan | Phó Chánh Văn phòng | 0913 999 782 |  |  |  |

### Phòng Công tác Quốc hội

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 1 | Nguyễn Nhật Duy | Trưởng phòng | 0938 095 525 | 02723 826 580 |  |  |
| 2 | Nguyễn Hoàng Long | Phó Trưởng phòng | 0858 824 824 | 02723 821 489 |  |  |
| 3 | Trần Thị Kim Ngọc | Phó Trưởng phòng | 0918 239 069 |  |  |  |
| 4 | Lại Hữu Lộc | Chuyên viên | 0943 225 067 |  |  |  |
| 5 | Nguỵ Trương Nhật Linh | Chuyên viên | 0974 478 740 |  |  |  |
| 6 | Nguyễn Thị Hoa | Chuyên viên | 0838 617 618 | 02723 821 489 |  |  |
| 7 | Bùi Thanh Hoàng | Chuyên viên | 0942 943 454 | 02723 821 489 |  |  |

### Phòng Công tác Hội đồng nhân dân

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 1 | Trần Lê Anh Thy | Trưởng phòng | 0903 644 352 | 02723 826 399 |  |  |
| 2 | Ngô CThành | Phó Trưởng phòng | 0933 893 472 | 02723 826 399 |  |  |
| 3 | Trần Vũ Yến Phương | Phó Trưởng phòng | 0909 451 708 |  |  |  |

### Phòng Dân tộc, Tôn giáo, Dân nguyện, Email: pdttgdn@tayninh gov vn

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 1 | Nguyễn Thanh Trung | PTP phụ trách | 0918 604 788 |  |  |  |
| 2 | Đặng Thị Ngọc Cẩm | Phó Trưởng phòng | 0986 494 549 | 02723 580 949 |  |  |
| 3 | Trần Thiện Tâm | Chuyên viên | 0945 944 489 | 02723 580 949 |  |  |
| 4 | Nguyễn Thị Thúy Hằng | Chuyên viên | 0399 259 156 | 02723 830 600 |  |  |
| 5 | Trần Thái Hàn Hải Nhi | Chuyên viên | 0974 499 798 |  |  |  |

#### Phòng Hành chính, Tổ chức, Quản trị

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 1 | Dương Thành Nhàn | Trưởng phòng | 0918 400 593 |  |  |  |
| 2 | Phạm Huỳnh Linh Thái | Phó Trưởng phòng | 0949 717 754 | 02723 830 600 |  |  |
| 3 | Nguyễn Thị Hạnh Nga | Kế toán | 0938 252 454 |  |  |  |

### Ủy ban nhân dân tỉnh / Đ/c: 61 Nguyễn Huệ, phường Long An, tỉnh Tây Ninh / ĐT: 0272 3838 454, email: vpubnd@tayninh.gov.vn; Website: https://www.tayninh.gov.vn

- Nhóm: 1
- Mã/STT nhóm: 13

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 1 | Nguyễn Văn Út | Chủ tịch | 0918 450 689 |  |  |  |
| 2 | Nguyễn Minh Lâm | Phó Chủ tịch | 0908 121 173 |  |  |  |
| 3 | Phạm Tấn Hòa | Phó Chủ tịch | 0913 656 085 |  |  |  |
| 4 | Huỳnh Văn Sơn | Phó Chủ tịch | 0913 678 743 |  |  |  |
| 5 | Nguyễn Hồng Thanh | Phó Chủ tịch | 0914 853 991 |  |  |  |
| 6 | Đoàn Trung Kiên | Phó Chủ tịch | 0907 747 666 |  |  |  |

### Văn phòng UBND tỉnh / Đ/c: 61 Nguyễn Huệ, phường Long An, tỉnh Tây Ninh / ĐT: 0272 3838 454, email: vpubnd@tayninh.gov.vn

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 1 | Võ Thành Trí | Chánh Văn phòng | 0903 049 639 |  |  |  |
| 2 | Nguyễn Hồng Hải | Phó Chánh Văn phòng | 0919 169 096 |  |  |  |
| 3 | Đào Hòa Hưng | Phó Chánh Văn phòng | 0917 122 600 |  |  |  |
| 4 | Trần Thị Ngọc Mai | Phó Chánh Văn phòng | 0903 116 653 |  |  |  |
| 5 | Nguyễn Tấn Lực | Phó Chánh Văn phòng | 0961 212 969 |  |  |  |
| 6 | Nguyễn Hồng Phúc | Phó Chánh Văn phòng | 0918 977 844 |  |  |  |
| 7 | Phan Thị Tuyết Nhung | Phó Chánh Văn phòng | 0913 822 223 |  |  |  |

### Phòng Hành chính - Tổ chức

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 8 | Nguyễn Hữu Vân | Trưởng phòng | 0944 404 033 |  |  |  |
| 9 | Nguyễn Thị Lệ Hằng | Phó Trưởng phòng | 0919 284 845 |  |  |  |
| 10 | Võ Hồng Trinh | Phó Trưởng phòng | 0944 727 319 |  |  |  |

### Phòng Quản trị - Tài vụ:

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 11 | Nguyễn Thị Ngọc Hà | Trưởng phòng | 0776 926 123 |  |  |  |
| 12 | Phạm Thị Thanh Kiều | Phó Trưởng phòng | 0911 371 166 |  |  |  |

### Phòng Tổng hợp:

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 13 | Nguyễn Thị Như Ngọc | Trưởng phòng | 0934 893 063 |  |  |  |
| 14 | Phạm Thị Thanh Hường | Phó Trưởng phòng | 0378 615 407 |  |  |  |

### Phòng Kinh tế - Tài chính:

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 15 | Phạm Ngọc Ẩn | Trưởng phòng | 0916 263 075 |  |  |  |
| 16 | Mai Chính Trung | Phó Trưởng phòng | 0909 988 327 |  |  |  |
| 17 | Huỳnh Thị Hạnh Thi | Phó Trưởng phòng | 0937 492 209 |  |  |  |

### Phòng Văn hóa - Xã hội:

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 18 | Huỳnh Quang Vinh | Trưởng phòng | 0938 868 852 |  |  |  |
| 19 | Nguyễn Thị Sang | Phó Trưởng phòng | 0977 889 693 |  |  |  |
| 20 | Huỳnh Thị Ngọc Thu | Phó Trưởng phòng | 0842 493 669 |  |  |  |
| 21 | Dương Duy Thanh | Phó Trưởng phòng | 0933 133 072 |  |  |  |

### Phòng Nội chính:

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 22 | Trịnh Kim Quý | Trưởng phòng | 0976 298 538 |  |  |  |
| 23 | Lưu Thị Mỹ Bình | Phó Trưởng phòng | 0911 513 303 |  |  |  |

### Ban Tiếp dân tỉnh, ĐT trực: 0272 3829 973 / Đ/c: Số 2C Nguyễn cửu Vân, phường Long An tỉnh Tây Ninh

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 24 | Trương Thị Dưng | Phó trưởng Ban | 0916 009 012 |  |  |  |
| 25 | Võ Châu Thông | Phó trưởng Ban | 0987 974 922 |  |  |  |

### Trung tâm Phục vụ Hành chính công tỉnh Tây Ninh, ĐT: 0272 3979 299 / Đ/c: số 02 đường Song Hành, phường Long An, tỉnh Tây Ninh

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 26 | Lưu Hiếu Trung | Phó Giám đốc phụ trách | 0918 700 837 |  |  |  |
| 27 | Nguyễn Hùng Tấn | Phó Giám đốc | 0816 011 485 |  |  |  |
| 28 | Đỗ Duy Linh | Phó Giám đốc | 0919 882 557 |  |  |  |
| 29 | Huỳnh Văn Tây | Phó Giám đốc | 0919 635 636 |  |  |  |

### Trung tâm Công báo – Tin học:

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 30 | Nguyễn Thị Linh Nhâm | Giám đốc | 0906 801 122 |  |  |  |
| 31 | Đặng Thị Kim Trang | Phó Giám đốc | 0908 978 418 |  |  |  |

### Trung tâm Phục vụ Hội nghị tỉnh:

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 32 | Lê Cao Đạt | Giám đốc | 0916 707 808 |  |  |  |
| 33 | Nguyễn Hoàng Nam | Phó Giám đốc | 0967 031 311 |  |  |  |
| 34 | Huỳnh Thị Kim Thành | Phó Giám đốc | 0913 716 347 |  |  |  |

## Các Sở Ngành tỉnh

### Sở Công Thương / Đ/c: Số 4, đường Song Hành, Phường Long An, Tỉnh Tây Ninh

- Nhóm: 1
- Mã/STT nhóm: 1

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 1 | Huỳnh Văn Quang Hùng | Giám đốc | 0938 515 999 |  |  |  |
| 2 | Ngô Văn Lê | Phó Giám đốc | 0938 908 178 |  |  |  |
| 3 | Châu Thị Lệ | Phó Giám đốc | 0918 955 666 |  |  |  |
| 4 | Trần Thanh Toản | Phó Giám đốc | 0989 617 663 |  |  |  |
| 5 | Huỳnh Đăng Khoa | Phó Giám đốc | 0913 731 567 |  |  |  |
| 6 | Trần Đăng Tiến | Phó Giám đốc | 0933 121 757 |  |  |  |
| 7 | Châu Thanh Long | Phó Giám đốc | 0908 863 218 |  |  |  |
| 8 | Nguyễn Thị Hạnh | Chánh Văn phòng | 0948 836 849 | 02723 826 206 |  |  |
| 9 | Cáp Thuận An | Phó Chánh Văn phòng | 0938 862 007 |  |  |  |
| 10 | Nguyễn Khắc Mộc | Phó Chánh Văn phòng | 0933 646 268 |  |  |  |
| 11 | Bùi Thị Thuý Hằng | Trưởng phòng KHTH | 0913 642 634 | 02723 832 099 |  |  |
| 12 | Lê Ngọc Nha | PTP KHTH | 0944 333 789 |  |  |  |
| 13 | Lương Nhất Tuấn | TP Pháp chế | 0918 383 585 | 02723 832 731 |  |  |
| 14 | Nguyễn Thị Song Thanh | PTP Pháp chế | 0913 999 938 |  |  |  |
| 15 | Trần Văn Kết | TP QLTM | 0931 546 566 | 02723 821 411 |  |  |
| 16 | Nguyễn Thị Thùy Trang | PTP QLTM | 0902 542 130 |  |  |  |
| 17 | Nguyễn Duy Phong | TP KTATMT | 0987 706 625 | 02723 521 123 |  |  |
| 18 | Nguyễn Tấn Cường | PTP KTATMT | 0703 366 491 |  |  |  |
| 19 | Võ Trường Minh | TP QLCN | 0988 388 113 | 02723 567 367 |  |  |
| 20 | Trần Thị Ngọc Ánh | PTP QLCN | 0906 848 689 |  |  |  |
| 21 | Nguyễn Tấn Bửu Trân | TP QLNL | 0983 880 538 | 02723 832 066 |  |  |
| 22 | Phạm Thanh Quận | PTP QLNL | 0907 031 777 |  |  |  |
| 23 | Lâm Khắc Trường | PTP QLNL | 0348 399 399 |  |  |  |

### TT Khuyến cvà Tư vấn PTCN / Đ/c: Số 5, Nguyễn Huệ, Phường Long An, Tỉnh Tây Ninh / ĐT: 3550 100; Fax: 3521 969

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 24 | Huỳnh Anh Phụng | Giám đốc Trung tâm | 0917 646 595 | 02723 521 600 |  |  |
| 25 | Phạm Văn Hường | Phó GĐ TT | 0903 722 220 | 02723 838 969 |  |  |
| 26 | Thái Quốc Cường | Phó GĐ TT | 0989 757 639 | 02723 521 454 |  |  |
| 27 | Nguyễn Thế Phương | Phó GĐ TT | 0929 306 879 |  |  |  |
| 28 | Lê Khánh Trình | Phó GĐ TT | 0913 955 003 |  |  |  |

### Chi cục Quản lý thị trường - ĐT: 02723 826 595 / Đ/c: Số 67 Hùng Vương, Phường Long An, Tỉnh Tây Ninh

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 29 | Nguyễn Minh | Chi cục trưởng | 0913 677 959 |  |  |  |
| 30 | Phạm Đức Chinh | Phó Chi cục trưởng | 0988 252 228 |  |  |  |
| 31 | Cao Văn Hồng | Phó Chi cục trưởng | 0918 258 188 |  |  |  |
| 32 | Lê Hoàng Dinh | Phó Chi cục trưởng | 0905 355 955 |  |  |  |
| 33 | Lê CPhước | Phó Chi cục trưởng | 0908 863 219 |  |  |  |
| 34 | Hồng Văn Hoàng | Phó Chi cục trưởng | 0888 506 792 |  |  |  |
| 35 | Nguyễn Hòa Bình | Phó Chi cục trưởng | 0901 422 211 |  |  |  |

### Sở Giáo dục và Đào tạo / Đ/c: Số 411, Quốc lộ 1, phường Long An, tỉnh Tây Ninh / ĐT: 02723 826 394; Email: sgd@tayninh gov vn; website: sgddt tayninh gov vn

- Nhóm: 1
- Mã/STT nhóm: 2

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 1 | Nguyễn Quang Thái | Giám đốc | 0908 579 995 | 02723 524 220 |  |  |
| 2 | Phan Thị Dạ Thảo | Phó Giám đốc | 0908 796 009 | 02723 823 202 |  |  |
| 3 | Huỳnh Phương Vũ | Phó Giám đốc | 0905 601 475 | 02723 525 755 |  |  |
| 4 | Trần Ngọc Uyển | Phó Giám đốc | 0917 453 377 | 02723 732 588 |  |  |
| 5 | Nguyễn Văn Phước | Phó Giám đốc | 0947 842 222 | 02723 732 600 |  |  |
| 6 | Bùi Tuấn Hải | Phó Giám đốc | 0913 730 205 | 02723 732 800 |  |  |
| 7 | Phan Minh Tùng | Phó Giám đốc | 0913 647 647 | 02723 732 808 |  |  |
| 8 | Lý Thanh Bình | Phó Giám đốc | 0918 384 929 | 02723 732 966 |  |  |
| 9 | Nguyễn Phúc Hiền | Chánh Văn phòng | 0943 976 576 | 02723 827 042 |  |  |
| 10 | Nguyễn Thanh Bình | Phó Chánh Văn phòng | 0987 079 822 | 02723 826 394 |  |  |
| 11 | Trần Thị Kim Sen | Phó Chánh Văn phòng | 0982 066 223 | 02763 822 375 |  |  |
| 12 | Phạm Đình Tứ | Phó Chánh Văn phòng | 0886 796 178 | 02763 822 375 |  |  |
| 13 | Hồ Văn Hậu | TP Kế hoạch - Tài chính | 0913 180 473 | 02723 833 909 |  |  |
| 14 | Nguyễn Thanh Nhàn | PTP Kế hoạch - Tài chính | 0908 671 192 | 02723 821 759 |  |  |
| 15 | Nguyễn Thị Lan Phương | TP Giáo dục Mầm non | 0937 353 079 | 02723 827 466 |  |  |
| 16 | Đinh Thị Kim Nguyên | PTP Giáo dục Mầm non | 0974 855 215 | 02723 827 466 |  |  |
| 17 | Hồ Văn Yên | TP GD Chuyên nghiệp-GD T xuyên | 0907 230 678 | 02723 823 498 |  |  |
| 18 | Dương Nguyên Quốc | TP Giáo dục phổ thông | 0938 382 385 | 02723 826 180 |  |  |
| 19 | Lê Phước Dũng | PTP Giáo dục phổ thông | 0946 154 385 | 02723 826 180 |  |  |
| 20 | Trần Thanh Việt | PTP Giáo dục phổ thông | 0974 539 500 | 02723 826 180 |  |  |
| 21 | Nguyễn Văn Hậu | TP Tổ chức cán bộ | 0917 676 569 | 02723 821 701 |  |  |
| 22 | Nguyễn Thị Quỳnh Châu | PTP Tổ chức cán bộ | 0918 781 222 | 02723 821 701 |  |  |
| 23 | Trần Anh Tuấn | PTP Tổ chức cán bộ | 0855 250 720 | 02763 822 375 |  |  |
| 24 | Nguyễn Thanh Nam | TP QL chất lượng - chuyển đổi số | 0963 764 656 | 02723 831 105 |  |  |
| 25 | Huỳnh Văn Chớ | PTP QL chất lượng - chuyển đổi số | 0911 696 780 | 02763 815 982 |  |  |

### Sở Khoa học và Công nghệ / ĐT bàn 02723 826 249; email: skhcn@tayninh.gov.vn; website: https://skhcn.tayninh.gov.vn

- Nhóm: 1
- Mã/STT nhóm: 3

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 1 | Huỳnh Thị Hồng Nhung | Giám đốc | 0834 005 006 |  |  |  |
| 2 | Nguyễn Minh Hải | Phó Giám đốc | 0989 971 525 |  |  |  |
| 3 | Hồ Thị Diệp Thúy | Phó Giám đốc | 0919 105 814 |  |  |  |
| 4 | Võ Bửu Viết Cường | Phó Giám đốc | 0917 343 839 |  |  |  |
| 5 | Bùi Nguyên Khởi | Phó Giám đốc | 0889 691 777 |  |  |  |
| 6 | Nguyễn Thị Kim Tuyến | Phó Giám đốc | 0918 359 714 |  |  |  |
| 7 | Nguyễn Trung Hiếu | Phó Giám đốc | 0913 955 333 |  |  |  |
| 8 | Liêu Thụy Hoàng Phương | Chánh Văn phòng | 0908 352 548 |  |  |  |
| 9 | Lê Thị Hồng Diễm | Phó CVP Sở | 0946 788 910 |  |  |  |
| 10 | Lê Thị Bích Thuận | Phó CVP Sở | 0908 518 487 |  |  |  |
| 11 | Phạm Thị Thu Vân | Trưởng phòng Kế hoạch - Tài chính | 0918 400 301 |  |  |  |
| 12 | Nguyễn Thanh Tây | PTP Kế hoạch - Tài chính | 0948 683 448 |  |  |  |
| 13 | Huỳnh Thị Thu Hà | PTP Kế hoạch - Tài chính | 0913 849 905 |  |  |  |
| 14 | Tăng Thị Ngọc Em | Trưởng phòng Chuyển đổi số | 0946 700 369 | 02723 523 888 |  |  |
| 15 | Trần Thị Ngọc Gấm | PTP Chuyển đổi số | 0918 998 746 | 02723 523 888 |  |  |
| 16 | Trần Bảo Nguyên | TP Tiêu chuẩn Đo lường chất lượng | 0938 228 395 | 02723 832 072 |  |  |
| 17 | Huỳnh Tấn Luật | PTP Tiêu chuẩn Đo lường Chất lượng | 0942 118 176 | 02723 832 072 |  |  |
| 18 | Lê Tấn Bình | PTP Tiêu chuẩn Đo lường Chất lượng | 0913 782 789 | 02723 832 072 |  |  |
| 19 | Nguyễn Thị Xuân Lam | PTP Tiêu chuẩn Đo lường Chất lượng | 0909 904 448 |  |  |  |
| 20 | Trương Như Ý | Trưởng phòng Cnghệ và đổi mới sáng tạo | 0976 205 911 |  |  |  |
| 21 | Lê Dương Phong | PTP Công nghệ và Đổi mới sáng tạo | 0979 097 333 |  |  |  |
| 22 | Nguyễn Nhựt Thanh | PTP Công nghệ và Đổi mới sáng tạo | 0908 598 084 |  |  |  |
| 23 | Nguyễn Tấn Phát | PTP Công nghệ và Đổi mới sáng tạo | 0976 263 838 |  |  |  |
| 24 | Nguyễn Hoàng Tấn | Trưởng phòng Khoa học | 0913 636 696 |  |  |  |
| 25 | Trần Thị Thanh Thúy | PTP Khoa học | 0904 474 605 |  |  |  |
| 26 | Lê Thanh Quang | Giám đốc TT Khoa học Công nghệ / và Đổi mới sáng tạo | 0919 723 267 |  |  |  |
| 27 | Đoàn Minh Tuyết | Phó GĐ TT Khoa học công nghệ / và Đổi mới sáng tạo | 0916 376 660 |  |  |  |
| 28 | Nguyễn Thế Ka | Phó GĐ TT Khoa học công nghệ / và Đổi mới sáng tạo | 0918 414 814 |  |  |  |
| 29 | Lê Thị Ngọc Hiếu | Phó GĐ TT Khoa học công nghệ / và Đổi mới sáng tạo | 0978 339 340 |  |  |  |
| 30 | Nguyễn Hồ Hạnh | Phó GĐ TT Khoa học công nghệ / và Đổi mới sáng tạo | 0909 257 967 |  |  |  |
| 31 | Nguyễn Mai Tuấn Khoa | Giám đốc TT Chuyển đổi số | 0912 426 357 |  |  |  |
| 32 | Nguyễn Thanh Tuấn | Phó GĐ TT Chuyển đổi số | 0909 988 376 |  |  |  |
| 33 | Vương Duy Thanh | Phó GĐ TT Chuyển đổi số | 0932 624 462 |  |  |  |
| 34 | Trần Thị Thu Trâm | Phó GĐ TT Chuyển đổi số | 0913 955 816 |  |  |  |

### Sở Nội vụ / ĐT bàn: 02723 826 353; 02763 824 386; email: snv@tayninh.gov.vn; / website: snv.tayninh.gov.vn

- Nhóm: 1
- Mã/STT nhóm: 4

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 1 | Phạm Xuân Bách | Giám đốc | 0918 955 475 |  |  |  |
| 2 | Nguyễn Hoàng Minh | Phó Giám đốc | 0918 885 377 |  |  |  |
| 3 | Trần Hải Tuấn | Phó Giám đốc | 0945 491 576 |  |  |  |
| 4 | Nguyễn Đại Tánh | Phó Giám đốc | 0903 112 997 |  |  |  |
| 5 | Đặng Ngọc Tảo | Phó Giám đốc | 0908 279 172 |  |  |  |
| 6 | Nguyễn Thị Thanh Nhàn | Phó Giám đốc | 0918 169 009 |  |  |  |
| 7 | Nguyễn Thanh Tùng | Phó Giám đốc | 0977 500 977 |  |  |  |
| 8 | Trần Thị Lan | Phó Giám đốc | 0909 646 744 |  |  |  |
| 9 | Trần Quốc Bảo | Phó Giám đốc | 0919 506 677 |  |  |  |

#### Văn phòng Sở

- Điện thoại cơ quan: 02723 826 353

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 10 | Nguyễn Xuân Vinh | Chánh Văn phòng | 0967 071 738 |  |  |  |
| 11 | Phạm Thị Mơ | Phó Chánh Văn phòng | 0946 866 126 |  |  |  |
| 12 | Vũ Văn Hùng | Phó Chánh Văn phòng | 0987 283 018 |  |  |  |
| 13 | Trần Ngọc Hiền | Phó Chánh Văn phòng | 0918 001 726 | 02763 824 386 |  |  |

#### Phòng Người có công

- Điện thoại cơ quan: 02723 822 487

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 14 | Lê Thanh Thuý | Trưởng phòng | 0933 077 082 |  |  |  |
| 15 | Phạm Huy Tín | Phó Trưởng Phòng | 0979 257 707 |  |  |  |
| 16 | Ngụy Hoàng Châu Duy | Phó Trưởng Phòng | 0919 732 883 |  |  |  |

#### Phòng Xây dựng chính quyền

- Điện thoại cơ quan: 02723 824 537

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 17 | Trương Thị Lệ Quyền | Trưởng phòng | 0944 315 969 |  |  |  |
| 18 | Võ Thanh Tuấn | Phó Trưởng Phòng | 0973 795 927 |  |  |  |
| 19 | Thiều Hoàng Phú Dương | Phó Trưởng Phòng | 0933 382 678 |  |  |  |

#### Phòng Lao động - Việc làm

- Điện thoại cơ quan: 02723 826 953

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 20 | Phan Thành Phải | Trưởng phòng | 0913 653 740 |  |  |  |
| 21 | Phạm Thị Trinh | Phó Trưởng Phòng | 0909 817 176 | 02723 523 960 |  |  |
| 22 | Phạm Xuân Lộc | Phó Trưởng Phòng | 0946 215 292 |  |  |  |

#### Phòng Cải cách hành chính

- Điện thoại cơ quan: 02723 837 030

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 23 | Trần Thị Trúc Liên | Phó Trưởng phòng phụ trách | 0838 833 239 |  |  |  |

#### Phòng Văn thư - Lưu trữ

- Điện thoại cơ quan: 02723 553 252

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 24 | Mai Bá Quân | Trưởng phòng | 0919 749 417 |  |  |  |
| 25 | Doãn Thị Phượng | Phó Trưởng phòng | 0933 247 337 |  |  |  |

#### Phòng Công chức - Viên chức

- Điện thoại cơ quan: 02723 828 176

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 26 | Lâm Ngọc Truyền | Trưởng phòng | 0918 888 395 |  |  |  |
| 27 | Nguyễn Thị Thu Bông | Phó Trưởng phòng | 0914 336 101 |  |  |  |
| 28 | Võ Thị Huyền Trinh | Phó Trưởng phòng | 0965 342 529 |  |  |  |

#### Phòng Tổ chức - Biên chế

- Điện thoại cơ quan: 02723 822 593

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 29 | Lê Thị Phương Thảo | Phó Trưởng phòng phụ trách | 0932 737 378 |  |  |  |
| 30 | Đặng Thị Tuyết Hồng | Phó Trưởng phòng | 0916 659 577 |  |  |  |
| 31 | Trần Thị Thúy Hằng | Phó Trưởng phòng | 0973 919 434 |  |  |  |

#### Ban Thi đua - Khen thưởng

- Điện thoại cơ quan: 02723 976 679

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 32 | Trần Thị Mỹ An | Trưởng ban | 0984 592 623 |  |  |  |
| 33 | Ngô Thị Phương Thảo | Phó Trưởng ban | 0936 267 479 |  |  |  |

#### Trung tâm Dịch vụ việc làm

- Điện thoại cơ quan: 02723 871 711

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 34 | Trần Văn Tiếng | Giám đốc trung tâm | 0918 978 233 |  |  |  |
| 35 | Nguyễn Thị Thanh Hằng | Phó Giám đốc trung tâm | 0937 872 037 |  |  |  |
| 36 | Trần Quốc Bảo | Phó Giám đốc trung tâm | 0913 169 327 |  |  |  |
| 37 | Lê Trường Thọ | Phó Giám đốc trung tâm | 0814 300 339 |  |  |  |

#### Ban Quản lý nghĩa trang tỉnh

- Điện thoại cơ quan: 02723 826 913

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 38 | Nguyễn Văn Cường | Trưởng Ban | 0989 373 887 |  |  |  |
| 39 | Võ Anh Tuấn | Phó Trưởng Ban | 0976 284 555 |  |  |  |

#### Trung tâm Lưu trữ lịch sử tỉnh

- Điện thoại cơ quan: 02723 839 030

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 40 | Lê Hoàng Dũng | Giám đốc trung tâm | 0919 607 337 |  |  |  |
| 41 | Phan Hồng Tùng | Phó Giám đốc trung tâm | 0944 306 099 |  |  |  |
| 42 | Nguyễn Văn Mạnh | Phó Giám đốc trung tâm | 0918 353 854 |  |  |  |

#### Trung tâm Điều dưỡng Người có công

- Điện thoại cơ quan: 02763 787 152

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 43 | Lê Hùng Việt | Giám đốc trung tâm | 0918 276 610 |  |  |  |
| 44 | Lưu Phước Ninh | Phó Giám đốc trung tâm | 0937 689 727 |  |  |  |
| 45 | Nguyễn Thị Hồng Diễm | Phó Giám đốc trung tâm | 0974 955 647 |  |  |  |

### Sở Tài chính Đ/c: Số 61 Trương Định, Phường Long An. ĐT bàn: 02763 886009; / Email: stc@tayninh.gov.vn; Website: stc.tayninh.gov.vn;

- Nhóm: 1
- Mã/STT nhóm: 5

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 1 | Trương Văn Liếp | Giám đốc | 0933 160 283 |  |  |  |
| 2 | Nguyễn Tấn Quí | Phó Giám đốc | 0983 616 696 |  |  |  |
| 3 | Trần Văn Tươi | Phó Giám đốc | 0918 129 254 |  |  |  |
| 4 | Lê Thị Hồng Gấm | Phó Giám đốc | 0908 324 777 |  |  |  |
| 5 | Trần Văn Vũ | Phó Giám đốc | 0913 678 249 |  |  |  |
| 6 | Hồ Quốc Công | Phó Giám đốc | 0918 602 414 |  |  |  |
| 7 | Hồng Lê Minh Nguyệt | Phó Giám đốc | 0918 117 842 |  |  |  |
| 8 | Hồ Thị Mỹ Phường | Phó Giám đốc | 0913 642 448 |  |  |  |
| 9 | Đặng Đình Toàn | Phó Giám đốc | 0909 395 453 |  |  |  |
| 10 | Nguyễn Kiên Cường | Phó GĐ | 0919 069 074 | 02763 813179 |  |  |
| 11 | Phạm Hồng Ngân Hà | Chánh Văn phòng | 0988 736 735 | 02723 886 009 |  |  |
| 12 | Nguyễn Phương Thảo | Phó Chánh Văn phòng | 0949 189 807 | 02723 886 009 |  |  |
| 13 | Đặng Hoàng Phong | Phó Chánh Văn phòng | 0903 072 825 | 02723 886 009 |  |  |
| 14 | Phan Lĩnh Cương | Phó Chánh Văn phòng | 0888 061 168 | 02723 886 009 |  |  |
| 15 | Lê Anh Phong | Phó Chánh Văn phòng | 0949 170 737 | 02763 812660 |  |  |
| 16 | Trương Nguyễn Hiếu | Trưởng phòng Thẩm định | 0949 043 396 |  |  |  |
| 17 | Nguyễn Minh Tấn | PTP Thẩm định | 0903 141 200 |  |  |  |
| 18 | Nguyễn Gia Thịnh | PTP Thẩm định | 0918 556 223 |  |  |  |
| 19 | Lê Quốc Thuần | PTP Thẩm định | 0976 183 796 | 02763 823380 |  |  |
| 20 | Lê Văn Thạo | Trưởng phòng Đầu tư công | 0916 878 004 | 02732 822 043 |  |  |
| 21 | Võ Thành Nhân | PTP Đầu tư công | 0939 021 980 | 02732 822 043 |  |  |
| 22 | Huỳnh Văn Lâm | PTP Đầu tư công | 0907 409 174 | 02732 822 043 |  |  |
| 23 | Nguyễn Hồng Tuyết Mai | PTP Đầu tư công | 0972 504 369 | 02732 822 043 |  |  |
| 24 | Phan Nguyễn Thanh Tuấn | PTP Đầu tư công | 0918 557 525 | 02763 825118 |  |  |
| 25 | Nguyễn Việt Bình | Trưởng phòng Đăng ký kinh doanh | 0918 859 757 | 02723 826 428 |  |  |
| 26 | Nguyễn Kim Phượng | PTP Đăng ký kinh doanh | 0949 485 929 | 02723 825 651 |  |  |
| 27 | Trịnh Thị Ánh Tuyết | PTP Đăng ký kinh doanh | 0944 495 131 | 02723 825 651 |  |  |
| 28 | Phan Thành Kiệt | PTP Đăng ký kinh doanh | 0913 999 338 | 02723 825 651 |  |  |
| 29 | Lâm Huỳnh Kim Thu | Trưởng phòng Hành chính sự nghiệp | 0826 806 868 |  |  |  |
| 30 | Thái Thanh Thuận | PTP Hành chính sự nghiệp | 0919 735 989 |  |  |  |
| 31 | Nguyễn Thị Hồng Mận | PTP Hành chính sự nghiệp | 0908 429 775 |  |  |  |
| 32 | Nguyễn Chí Cường | PTP Hành chính sự nghiệp | 0987 241 033 |  |  |  |
| 33 | Phạm Anh Nguyên | Trưởng phòng Hợp tác đầu tư | 0919 220 389 | 02723 826 199 |  |  |
| 34 | Dương Đình Khang | PTP Hợp tác đầu tư | 0964 409 715 | 02723 826 199 |  |  |
| 35 | Trần Thị Ánh Hồng | PTP Hợp tác đầu tư | 0909 733 286 | 02723 826 199 |  |  |
| 36 | Ngô Thị Hồng Cẩm | PTP Hợp tác đầu tư | 0902 505 459 | 02723 826 199 |  |  |
| 37 | Lê Minh Khánh | PTP Hợp tác đầu tư | 0949 155 157 | 02763 825179 |  |  |
| 38 | Nguyễn Bình Minh | Trưởng phòng Ngân sách | 0942 790 686 | 02723 824 795 |  |  |
| 39 | Trương Phú Trí | PTP Ngân sách | 0937 147 927 | 02723 824 795 |  |  |
| 40 | Huỳnh Thị Thanh Nam | PTP Ngân sách | 0938 694 551 | 02763 812232 |  |  |
| 41 | Lê Thị Hà Ninh | PTP Ngân sách | 0979 717 798 | 02763 812232 |  |  |
| 42 | Phạm Hồng Nghi | Trưởng phòng Giá - Csản | 0937 331 499 | 02723 824 730 |  |  |
| 43 | Nguyễn Trần Diễm Chi | PTP Giá - Csản | 0987 030 090 | 02723 824 730 |  |  |
| 44 | Cù Thị Kim Ngân | PTP Giá - Csản | 0985 363 618 | 02723 824 730 |  |  |
| 45 | Đặng Thị Tố Loan | PTP Giá - Csản | 0933 955 189 | 02763 823126 |  |  |
| 46 | Hồ Hoàng Lâm Vũ | Trưởng phòng Tổng hợp - Quy hoạch | 0983 636 107 | 02723 823 462 |  |  |
| 47 | Võ Tấn Lộc | PTP Tổng hợp - Quy hoạch | 0918 238 918 | 02723 823 462 |  |  |
| 48 | Nguyễn Kim Phượng | PTP Tổng hợp - Quy hoạch | 0913 072 275 | 02723 823 462 |  |  |
| 49 | Hồ Hải Thanh | PTP Tổng hợp - Quy hoạch | 0918 383 006 | 02763 823127 |  |  |
| 50 | Trần Ngọc Nhung | GĐ TT Xúc tiến và Hỗ trợ đầu tư | 0933 687 279 | 02723 835 373 |  |  |
| 51 | Phùng Thanh Phong | Phó GĐ TT Xúc tiến và Hỗ trợ đầu tư | 0974 976 948 | 02723 833 567 |  |  |

### Sở Tư pháp - Đ/c: Số 151 Nguyễn Đình Chiểu, phường Long An / ĐT bàn: 02723 829 522; Email: stp@tayninh.gov.vn; Website: stp.tayninh.gov.vn;

- Nhóm: 1
- Mã/STT nhóm: 6

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 1 | Phan Thị Mỹ Dung | Giám đốc sở | 0918 069 359 |  |  |  |
| 2 | Trần Văn Năm | Phó Giám đốc sở | 0918 129 529 |  |  |  |
| 3 | Lý Hồng Huấn | Phó Giám đốc sở | 0948 307 938 |  |  |  |
| 4 | Nguyễn Minh Sang | Phó Giám đốc sở | 0907 203 447 |  |  |  |
| 5 | Huỳnh Thị Mộng Trinh | Phó Giám đốc sở | 0987 970 293 |  |  |  |
| 6 | Lê Phan Mỹ An | Phó Giám đốc sở | 0916 843 977 |  |  |  |
| 7 | Nguyễn Phú Huynh | Chánh văn phòng | 0947 480 650 | 02723 829 522 |  |  |
| 8 | Phạm Ngọc Tuấn | Phó Chánh văn phòng | 0908 650 416 |  |  |  |
| 9 | Nguyễn Thị Ngọc Ánh | Trưởng phòng | 0902 369 594 | 02723 837 850 |  |  |
| 10 | Nguyễn Thị Thanh Xuân | Phó Trưởng phòng | 0971 854 971 |  |  |  |
| 11 | Trần Thị Hồng Nhung | Trưởng phòng | 0917 861 612 | 02723 830 805 |  |  |
| 12 | Trần Ngọc Dương | Phó Trưởng phòng | 0943 950 949 |  |  |  |
| 13 | Nguyễn Thị Thanh Trúc | Trưởng phòng | 0839 388 699 | 02723 839 632 |  |  |
| 14 | Nguyễn Thị Thu Trang | Phó Trưởng phòng | 987232883 |  |  |  |
| 15 | Lê Thị Lo | Trưởng phòng | 0918 603 242 | 02723 837 736 |  |  |
| 16 | Đào Thị Anh Tuyết | Phó Trưởng phòng | 966220182 |  |  |  |
| 17 | Hồ Văn Triều | Phó Trưởng phòng | 0913 818 164 | 02723 839 633 |  |  |

#### TRUNG TÂM TRỢ GIÚP PHÁP LÝ NHÀ NƯỚC TỈNH TÂY NINH; / Email: tttgphaply@tayninh.gov.vn; Đ/c: Số 28 Nguyễn Đình Chiểu, phường Long An

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 1 | Lê Minh Hiền | Giám đốc | 0918 985 988 | 02723 821 630 |  |  |
| 2 | Đặng Kim Hà | Phó Giám đốc | 0918 283 376 |  |  |  |
| 3 | Trần Thị Cẩm Vân | Phó Giám đốc | 0944 125 290 |  |  |  |

#### TRUNG TÂM DỊCH VỤ ĐẤU GIÁ TÀI SẢN - SỞ TƯ PHÁP; Email: nguyenthily@tayninh.gov.vn; Đ/c: Số 82 Trần Hưng Đạo, phường Tân Ninh

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 1 | Nguyễn Thị Lý | Giám đốc | 0949 982 981 | 02763 813 218 |  |  |
| 2 | Phan Thị Kim Mai | Phó Giám đốc | 0988 414 708 |  |  |  |

#### PHÒNG CCHỨNG SỐ 1 - SỞ TƯ PHÁP; Email: pccs1-stp@tayninh.gov.vn; Đ/c: Số 82 Trần Hưng Đạo, phường Tân Ninh

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 1 | Kim Ngọc Thông | Trưởng phòng | 0915 005 445 | 02763 822 975 |  |  |
| 2 | Mai Thị Yến Linh | Phó Trưởng phòng | 0976 234 027 |  |  |  |

#### PHÒNG CCHỨNG SỐ 2 - SỞ TƯ PHÁP; Email: pccs2-stp@tayninh.gov.vn; Đ/c: Số 297, KP Rạch Sơn, phường Gò Dầu

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 1 | Trần Hùng Nghiễm | Trưởng phòng | 0909 120 269 | 02763 854 028 |  |  |

#### PHÒNG CCHỨNG SỐ 3 - SỞ TƯ PHÁP; Email: pccs3-stp@tayninh.gov.vn; Đ/c: Đường Nguyễn Hữu Dụ, Khu phố 3, xã Tân Châu

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 1 | Nguyễn Chí Thiện | Phó Trưởng phòng | 0888 210 983 | 02763 730 488 |  |  |

### Sở Văn hóa, Thể thao và Du lịch / ĐT bàn: 02723 831 079; 02763 822 320; / Email: svhttdl@tayninh gov vn; website: https://svhttdl longan gov vn

- Nhóm: 1
- Mã/STT nhóm: 7

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 1 | Trần Anh Minh | Giám đốc | 0918 745 768 |  |  |  |
| 2 | Nguyễn Thành Thanh | Phó Giám đốc | 0913 763 855 |  |  |  |
| 3 | Nguyễn Tấn Quốc | Phó Giám đốc | 0918 518 918 |  |  |  |
| 4 | Huỳnh Cao Chánh | Phó Giám đốc | 0918 955 779 |  |  |  |
| 5 | Lê Thị Hồng Kết | Phó Giám đốc | 0949 394 171 |  |  |  |
| 6 | Lê Quang Chánh | Phó Giám đốc | 0913 222 307 |  |  |  |
| 7 | Trần Thị Huy Hoàng | Phó Giám đốc | 0918 280 586 |  |  |  |

### Văn phòng Sở

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 1 | Đặng Chí Trung | Chánh Văn phòng | 0949 474 710 | 02723 831 079 |  |  |
| 2 | Lưu Thị Xuân Thảo | Phó Chánh Văn phòng | 0917 120 340 | 02723 822 631 |  |  |
| 3 | Nguyễn Ngọc Thanh | Phó Chánh Văn phòng | 0355 141 454 | 02724 822 631 |  |  |
| 4 | Nguyễn Thị Huỳnh Mai | Phó Chánh Văn phòng | 0907 775 570 |  |  |  |

### Phòng Quản lý Văn hóa và Gia đình

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 1 | Đoàn Văn Vũ | Trưởng phòng | 0829 599 899 | 02723 833 687 |  |  |
| 3 | Nguyễn Ngọc Phát | PTP | 0933 597 910 | 02724 833 686 |  |  |
| 4 | Văn Hoàng Quân | PTP | 0779 049 033 | 02725 833 687 |  |  |
| 5 | Bùi Minh Tuấn | PTP | 0988 414 640 | 02763 381 8157 |  |  |
| 6 | Trịnh Duy Cường | PTP | 0919 064 074 | 02727 833 687 |  |  |

### Phòng Quản lý Thtin, Báo chí và Xuất bản

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 1 | Nguyễn Minh Hoàng | Trưởng phòng | 0913 999 234 | 02723 824 888 |  |  |
| 2 | Khấu Thị Thanh Tâm | PTP | 0946 567 717 | 02724 824 888 |  |  |

### Phòng Quản lý Thể dục thể thao

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 1 | Đoàn Văn Trọng | Trưởng phòng | 0913 679 767 | 02723 822 352 |  |  |
| 2 | Đào Kim Nguyễn Thụy Thanh | PTP | 0798 482 288 | 02723 822 352 |  |  |
| 3 | Lê Trung Kiên | PTP | 0986 120 758 | 02723 822 352 |  |  |

### Phòng Quản lý Du lịch

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 1 | Nguyễn Thái Bình Dương | Trưởng phòng | 0913 666 825 | 02723 830 736 |  |  |
| 2 | Hồ Phan Mộng Tuyền | PTP | 0948 446 222 | 02724 830 736 |  |  |

### BẢO TÀNG TỈNH

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 1 | Trần Thị Đoan Quang | Giám đốc | 0918 651 757 | 02723 835 174 |  |  |
| 3 | Đặng Thị Kim Sử | Phó GĐ | 0342 717 438 |  |  |  |

### THƯ VIỆN TỈNH

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 1 | Phạm Thị Cẩm Nhung | Phó GĐ phụ trách | 0818 243 224 | 02723 837 050 |  |  |
| 2 | Nguyễn Võ Duyên Anh | Phó GĐ | 0907 555 661 |  |  |  |

### Trung tâm Văn hóa Nghệ thuật tỉnh

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 1 | Nguyễn Triệu Minh | Giám đốc | 0918 129 525 | 02723 829 229 |  |  |
| 2 | Hàng Thị Quý Tâm | Phó GĐ | 0832 861 057 |  |  |  |
| 3 | Lê Thị Cẩm Châu | Phó GĐ | 0941 682 941 |  |  |  |
| 4 | Lê Bảo Minh | Phó GĐ | 0943 444 442 |  |  |  |

### TT HUẤN LUYỆN VÀ THI ĐẤU THỂ THAO

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 1 | Nguyễn Bảo Hoàn | Giám đốc | 0919 105 635 | 02723 826 988 |  |  |
| 2 | Mai Hồng Hải | Phó GĐ | 0918 297 990 |  |  |  |
| 3 | Châu Thị Kiều Oanh | Phó GĐ | 0972 097 478 |  |  |  |
| 4 | Nguyễn Tấn Phúc | Phó GĐ | 0913 945 838 |  |  |  |

### TT XÚC TIẾN DU LỊCH

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 1 | Trần Quốc Thịnh | Giám đốc | 0938 884 584 | 02723 939 585 |  |  |
| 2 | Lê Thị Hồng Thủy | Phó GĐ | 0982 464 549 / 0914 071 379 | 02723 939 575 |  |  |
| 3 | Phan ĐHùng | Phó GĐ | 0983 081 931 |  |  |  |

### TRƯỜNG THỂ DỤC THỂ THAO

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 1 | Trần Minh Đức | Hiệu trưởng | 0918 097 729 | 02723 523 594 |  |  |

### ĐOÀN NGHỆ THUẬT CẢI LƯƠNG

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 1 | Hồ Thị Ngọc Trinh | Trưởng đoàn | 0909 393 030 | 02723 826 166 |  |  |

### Sở Xây dựng - Đ/c: 04 Song Hành, phường Long An - / ĐT bàn 02723 824 725; email: sxd@tayninh gov vn; website: https://sxd tayninh gov vn

- Nhóm: 1
- Mã/STT nhóm: 8

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 1 | Nguyễn Nam Hưng | Giám đốc | 0913 955 407 |  |  |  |
| 2 | Lê Thị Dân An | Phó Giám đốc | 0913 700 116 |  |  |  |
| 3 | Nguyễn Ngọc Châu | Phó Giám đốc | 0983 034 779 |  |  |  |
| 4 | Đặng Hoàng Chương | Phó Giám đốc | 0989 170 028 |  |  |  |
| 5 | Lâm CDự | Phó Giám đốc | 0982 586 979 |  |  |  |
| 6 | Lưu Văn Khánh | Phó Giám đốc | 0913 999 870 |  |  |  |
| 7 | Nguyễn Thành Ngoãn | Phó Giám đốc | 0933 607 007 |  |  |  |
| 8 | Trần Bá Phước | Phó Giám đốc | 0903 738 686 |  |  |  |
| 9 | Nguyễn Văn Trang | Phó Giám đốc | 0913 166 019 |  |  |  |
| 10 | Nguyễn Hoài Trung | Phó Giám đốc | 0932 070 868 |  |  |  |

### Văn phòng Sở

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 1 | Lý Ngọc Tiên | Chánh Văn phòng | 0949 569 899 |  |  |  |
| 2 | Nguyễn Thị Bích Hạnh | Phó CVP | 0944 607 600 |  |  |  |
| 3 | Lê Diễm Thúy | Phó CVP | 0916 044 989 |  |  |  |

### Phòng Kế hoạch, Tổng hợp

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 1 | Vũ Thế Cường | Trưởng phòng | 0918 455 778 |  |  |  |
| 2 | Trịnh Phượng Hằng | PTP | 0909 626 387 |  |  |  |
| 3 | Nguyễn Thị Hoàng Yến | PTP | 0989 678 754 |  |  |  |

### Phòng Quản lý Hoạt động xây dựng

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 1 | Lê Tuấn Nhạc | Trưởng phòng | 0908 433 247 |  |  |  |
| 2 | Lương Minh Giang | PTP | 0913 757 307 |  |  |  |
| 3 | Nguyễn Thanh Hải | PTP | 0918 168 984 |  |  |  |
| 4 | Mai Thị Khánh Vân | PTP | 0941 222 227 |  |  |  |

### Phòng Quản lý kết cấu hạ tầng

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 1 | Võ Huy Thông | Trưởng phòng | 0918 622 091 |  |  |  |
| 2 | Trương Văn Hiện | PTP | 0918 751 362 |  |  |  |
| 3 | Nguyễn Thị Diễm Kiều | PTP | 0948 722 486 |  |  |  |
| 4 | Võ Phương Nam | PTP | 0938 438 231 |  |  |  |

### Phòng Quản lý Nhà, Thị trường Bất động sản

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 1 | Châu Ngọc Lâm | Trưởng phòng | 0985 992 535 |  |  |  |
| 2 | Đỗ Kim Nguyên | PTP | 0908 228 655 |  |  |  |
| 3 | Nguyễn Văn Sơn | PTP | 0908 835 297 |  |  |  |

### Phòng Quản lý Vận tải

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 1 | Lê Phan Phi Phụng | Trưởng phòng | 0852 592 592 |  |  |  |
| 2 | Hoàng Văn Dũng | PTP | 0986 600 831 |  |  |  |
| 3 | Nguyễn Thị Như | PTP | 0978 751 827 |  |  |  |
| 4 | Võ Tấn Phát | PTP | 0982 597 676 |  |  |  |
| 5 | Nguyễn Minh Tâm | PTP | 0937 946 843 |  |  |  |

### Phòng Quản lý Vật liệu xây dựng, môi trường

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 1 | Nguyễn Minh Toãn | Trưởng phòng | 0972 957 585 |  |  |  |
| 2 | Lê Nhật Khánh | PTP | 0919 034 668 |  |  |  |
| 3 | Lê Thị Cẩm Linh | PTP | 0988 682 980 |  |  |  |

### Phòng Quy hoạch, Phát triển đô thị

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 1 | Nguyễn Hoàng Giang | Trưởng phòng | 0907 230 882 |  |  |  |
| 2 | Trần Thị Ly Lan | PTP | 0918 049 663 |  |  |  |
| 3 | Trần Hồng Pha | PTP | 0398 563 376 |  |  |  |
| 4 | Lê Trọng Thái | PTP | 0906 576 865 |  |  |  |

### Phòng Thẩm định, phát triển giao thông

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 1 | Nguyễn Hoài Phong | Trưởng phòng | 0913 798 018 |  |  |  |
| 2 | Nguyễn Phú Hoài | PTP | 0942 620 106 |  |  |  |
| 3 | Vương Lâm Vũ | PTP | 0989 170 038 |  |  |  |

### Cảng vụ Đường thủy nội địa - Đ/c: Số 1B, Quốc lộ 1, Kp Thanh Xuân, Phường Long An, tỉnh Tây Ninh

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 1 | Lê Hùng Dũng | Giám đốc | 0908 610 633 |  |  |  |
| 2 | Đinh CKhanh | Phó GĐ | 0909 919 979 |  |  |  |
| 3 | Lê Tấn Lửa | Phó GĐ | 0913 884 527 |  |  |  |
| 4 | Lê Tuấn Phong | Phó GĐ | 0918 602 245 |  |  |  |
| 5 | Lại Hoàng Phương | Phó GĐ | 0918 332 335 |  |  |  |

### TT Quản lý đường bộ-đường sông - ĐT bàn: 02723 525 681 / Đ/c: Số 1A, Quốc lộ 1, Kp Thanh Xuân, Phường Long An, tỉnh Tây Ninh

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 1 | Huỳnh Khải Phong | Giám đốc | 0986 769 797 |  |  |  |
| 2 | Trần Bá Vũ Khoa | Phó GĐ | 0918 078 207 |  |  |  |
| 3 | Nguyễn Thanh Tùng | Phó GĐ | 0944 815 559 |  |  |  |

### TT Đăng kiểm xe cơ giới - ĐT bàn: 02723 821 496 / Đ/c: Số 12 Quốc lộ 1, Phường Long An, Tỉnh Tây Ninh

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 1 | Nguyễn Văn Phúc | Giám đốc | 0942 706 979 |  |  |  |
| 2 | Hồ Văn Dũng | Phó GĐ | 0919 127 782 |  |  |  |
| 3 | Trương Ngọc Tâm | Phó GĐ | 0918 371 831 |  |  |  |

### TT Kiểm định và dịch vụ xây dựng - ĐT bàn: 02763 813 766 / Đ/c: Số 003 Trương Định, phường Tân Ninh

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 1 | Trịnh Văn Trọng | Giám đốc | 0908 057 599 |  |  |  |
| 2 | Phạm Mạnh Hiếu | Phó GĐ | 0908 689 305 |  |  |  |
| 3 | Trần Thị Anh Thư | Phó GĐ | 0918 743 499 |  |  |  |

### TT Giám định chất lượng xây dựng - ĐT bàn: 02723 837 925 / Đ/c: Số 39 Huỳnh Văn Tạo, Phường Long An, tỉnh Tây Ninh

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 1 | Du Quang Vinh | Giám đốc | 0903 157 075 |  |  |  |
| 2 | Huỳnh Ngọc Lưu | Phó GĐ | 0918 289 167 |  |  |  |
| 3 | Nguyễn Thị Anh Phương | Phó GĐ | 0913 959 160 |  |  |  |
| 4 | Nguyễn Thanh Sơn | Phó GĐ | 0977 173 399 |  |  |  |
| 5 | Lê Quang Thống | Phó GĐ | 0909 202 628 |  |  |  |

### TT Quy hoạch Xây dựng - ĐT bàn: 02723 835 412 / Đ/c: 257-259 Đường số 12 Phường Long An Tỉnh Tây Ninh

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 1 | Nguyễn Văn Quới | Phó GĐ phụ trách | 0918 019 353 |  |  |  |
| 2 | Võ Thanh Hoài | Phó GĐ | 0907 992 558 |  |  |  |
| 3 | Hà Quốc Hưng | Phó GĐ | 0903 317 531 |  |  |  |

### Sở Y tế

- Nhóm: 1
- Mã/STT nhóm: 9

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 1 | Đỗ Hồng Sơn | Giám đốc | 918331341 |  |  |  |
| 2 | Mai Văn Dũng | Phó Giám đốc | 918234559 |  |  |  |
| 3 | Vũ Gia Phương | Phó Giám đốc | 914755797 |  |  |  |
| 4 | Nguyễn Hoàng Uyên | Phó Giám đốc | 909676069 |  |  |  |
| 5 | Huỳnh Trần Công Hiền | Phó Giám đốc | 913730306 |  |  |  |

### VĂN PHÒNG

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 1 | Phạm Ngọc Hải | Chánh Văn phòng | 946700779 |  |  |  |
| 2 | Nguyễn Phú Cường | Phó Chánh văn phòng | 918807587 |  |  |  |
| 3 | Trần Thị Ngọc Cúc | Chuyên viên | 983606010 |  |  |  |
| 4 | Huỳnh Hữu Minh | Chuyên viên | 919124408 |  |  |  |
| 5 | Trương Thái Thanh Vy | Chuyên viên | 909045152 |  |  |  |
| 6 | Lương Văn Việt | Chuyên viên | 918412967 |  |  |  |
| 7 | Lê Thị Phương Thảo | Chuyên viên | 944814979 |  |  |  |
| 8 | Nguyễn Thị Mỹ Tiên | Chuyên viên | 919205838 |  |  |  |
| 9 | Mai Nhung | Chuyên viên | 948899749 |  |  |  |
| 10 | Huỳnh Thị Như Phượng | Chuyên viên | 977001628 |  |  |  |
| 11 | Nguyễn Trần Thi Thơ | Chuyên viên | 985154126 |  |  |  |
| 12 | Nguyễn Ngô Cẩm Tú | Chuyên viên | 909489415 |  |  |  |

### PHÒNG TỔ CHỨC CÁN BỘ

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 1 | Nguyễn Điều | Phó trưởng phòng- Phụ trách | 913464089 |  |  |  |
| 2 | Đường Minh Anh | Phó Trưởng phòng | 906608978 |  |  |  |
| 3 | Mai Chí Linh | Phó Trưởng phòng | 913955573 |  |  |  |
| 4 | Nguyễn Thị Bảo Khánh | Chuyên viên | 933390874 |  |  |  |
| 5 | Nguyễn Thị Ngọc Thạch | Chuyên viên | 933606670 |  |  |  |
| 6 | Ngô Thị Thanh Thảo | Chuyên viên | 919822039 |  |  |  |
| 7 | Đoàn Thị Bích Thủy | Chuyên viên | 948444818 |  |  |  |
| 8 | Võ Nguyễn Nhất Phương | Chuyên viên | 385209901 |  |  |  |
| 9 | Lại Thị Như Huỳnh | Chuyên viên | 969165455 |  |  |  |
| 10 | Trịnh Thị Ánh Nguyệt | Chuyên viên | 984550181 |  |  |  |

### PHÒNG KẾ HOẠCH TÀI CHÍNH

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 1 | Phạm Hồng Thái | Trưởng phòng | 903810176 |  |  |  |
| 2 | Đinh Phan Chí Linh | Phó Trưởng phòng | 919285879 |  |  |  |
| 3 | Trần Thị Hương | Phó Trưởng phòng | 946853378 |  |  |  |
| 4 | Trần Huỳnh Châu | Phó Trưởng phòng | 937214543 |  |  |  |
| 5 | Nguyễn Ngọc Diễm | Chuyên viên | 987253376 |  |  |  |
| 6 | Bùi Thị Thùy Lam | Chuyên viên | 944333477 |  |  |  |
| 7 | Lê Thị Liên | Chuyên viên |  | Ngày 01/8/2025 nghỉ hưu |  |  |
| 8 | Hứa Thụy Thanh Thư | Chuyên viên | 947142111 |  |  |  |
| 9 | Nguyễn Hồng Tuyến | Chuyên viên | 398782350 |  |  |  |
| 10 | Lê Thanh Kiếm | Chuyên viên | 948717078 |  |  |  |
| 11 | Lê Thanh Long | Chuyên viên | 933688093 |  |  |  |
| 12 | Quách Văn Hùng | Chuyên viên | 906848872 |  |  |  |
| 13 | Đặng Ngọc Tuyết Mai | Chuyên viên |  | Đã có đơn xin thôi việc |  |  |
| 14 | Nguyễn Thị Ngọc My | Chuyên viên |  | Chuyển công tác Sở Nội vụ từ 10/7/2025. |  |  |
| 15 | Phan Thị Như Anh | Chuyên viên | 977043187 |  |  |  |
| 16 | Lưu Thị Xuân | Chuyên viên | 917079352 |  |  |  |
| 17 | Nguyễn Đại Bằng | Chuyên viên | 908818318 |  |  |  |

### PHÒNG NGHIỆP VỤ 1

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 1 | Huỳnh Văn Bằng | Trưởng phòng | 852484427 |  |  |  |
| 2 | Phan Thị Mai Hương | Phó Trưởng phòng | 938214558 |  |  |  |
| 3 | Võ Thị Như Diệu | Chuyên viên | 768820979 |  |  |  |
| 4 | Dương Thị Mỹ Nhân | Chuyên viên | 914198475 |  |  |  |
| 5 | Bùi Thành Phú | Chuyên viên |  |  |  |  |
| 6 | Trần Thị Phương Thảo | Chuyên viên | 834613423 |  |  |  |
| 7 | Phạm Ngọc Trí | Chuyên viên | 944977944 |  |  |  |
| 8 | Lê Đặng Minh Đạo | Chuyên viên | 915782009 |  |  |  |
| 9 | Đặng Phước Điền | Chuyên viên | '0977324224 |  |  |  |

### PHÒNG NGHIỆP VỤ 2

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 1 | Phạm Bảo Trường | Trưởng phòng | 918099727 |  |  |  |
| 2 | Lý Quang Xuân | Phó Trưởng phòng | 918129070 |  |  |  |
| 3 | Trương Phi Hùng | Phó Trưởng phòng | 918232416 |  |  |  |
| 4 | Phùng Văn Mười | Chuyên viên | 918089527 |  |  |  |
| 5 | Nguyễn Thị Diệu Hiền | Chuyên viên | 919392002 |  |  |  |
| 6 | Lê Thị Hoàng Cầm | Chuyên viên | 918206707 |  |  |  |
| 7 | Nguyễn Nghiêm Trang | Chuyên viên | 389862095 |  |  |  |
| 8 | Bùi Hoài Phương | Chuyên viên | 937658577 |  |  |  |

### PHÒNG BẢO TRỢ XÃ HỘI VÀ TRẺ EM

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 1 | Phạm Công Phong | Trưởng phòng | 901551224 |  |  |  |
| 2 | Nguyễn Thị Thúy Vân (1983) | Phó Trưởng phòng | 0904 406528 |  |  |  |
| 3 | Nguyễn Thị Thúy Vân (1982) | Phó Trưởng phòng | 0983 974303 |  |  |  |
| 4 | Nguyễn Thị Bạch | Chuyên viên | 977836342 |  |  |  |
| 5 | Lê Hoàng Long | Chuyên viên | 829246399 |  |  |  |
| 6 | Nguyễn Thị Kim Hương | Chuyên viên | 944321949 |  |  |  |
| 7 | Phạm Tấn Ngàn | Chuyên viên | 988164902 |  |  |  |
| 8 | Phạm Thị Hương Giang | Chuyên viên | 978626366 |  |  |  |
| 9 | Trần Thị Duyên | Chuyên viên | 898751989 |  |  |  |
| 10 | Trần Công Bền | Chuyên viên | 886770352 |  |  |  |

### Thanh tra tỉnh Tây Ninh - / Đ/c: số 51A, Nguyễn Huệ, phường Long An - / ĐT bàn: 02723 824 958, 0276 382 2158; email: ttra@tayninh.gov.vn; website: https://thanhtratinh.tayninh.gov.vn;

- Nhóm: 1
- Mã/STT nhóm: 10

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 1 | Phan Huỳnh Quốc Vinh | Chánh Thanh tra | 0907 331 707 | 02723 826 741 |  |  |
| 2 | Nguyễn Văn Lâm | Phó Chánh Thanh tra | 0393 974 637 |  |  |  |
| 3 | Lê Văn Tẳng | Phó Chánh Thanh tra | 0918 743 553 |  |  |  |
| 4 | Trần Thị Hồng Gấm | Phó Chánh Thanh tra | 0918 691 707 |  |  |  |
| 5 | Trần Xuân Long | Phó Chánh Thanh tra | 0913 134 525 |  |  |  |
| 6 | Nguyễn Ngọc Vệ | Phó Chánh Thanh tra | 0909 900 088 |  |  |  |

### Văn phòng

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 1 | Nguyễn Văn Biên | Chánh Văn phòng | 0839 209 044 |  |  |  |
| 2 | Nguyễn Tấn Bền | Phó Chánh Văn phòng | 0836 364 569 |  |  |  |
| 3 | Lê Thành Nhân | Phó Chánh Văn phòng | 0943 903 413 |  |  |  |
| 4 | Võ Thị Ngoan | Phó Chánh Văn phòng | 0829 922 957 |  |  |  |

### Phòng Thanh tra, Tiếp cdân giải quyết khiếu nại, tố cáo (Phòng Nghiệp vụ 1)

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 1 | Nguyễn Nhựt Huy | Trưởng Phòng | 0966 717 168 0816 717 168 |  |  |  |
| 2 | Bùi Thanh Bình | PTP | 0931 782 486 0941 416 168 |  |  |  |
| 3 | Nguyễn Thị Kim Trang | PTP | 0916 731 394 |  |  |  |
| 4 | Đỗ Quang Thuận | PTP | 0985 050 590 |  |  |  |

### Phòng Thanh tra Phòng, chống tham nhũng, lãng phí, tiêu cực (Phòng nghiệp vụ 2)

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 1 | Trương Thành CLý | PTP | 0937 085 442 |  |  |  |
| 2 | Đinh Văn Hoàng An | PTP | 0849 490 959 |  |  |  |
| 3 | Nguyễn Đăng Duy | PTP | 0852 478 466 |  |  |  |

### Phòng Thanh tra lĩnh vực nội chính, nội vụ, ngoại vụ, dân tộc, tôn giáo (Phòng nghiệp vụ 3)

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 1 | Phan Thị Anh Thư | Trưởng Phòng | 0916 257 748 |  |  |  |
| 2 | Nguyễn Duy Kha | PTP | 0946 906 468 |  |  |  |
| 3 | Nguyễn Tuấn An | PTP | 0908 288 222 |  |  |  |
| 4 | Trần Mai Thủy Uyên | PTP | 0902 412 523 |  |  |  |

### Phòng Thanh tra lĩnh vực tài chính, xây dựng (Phòng nghiệp vụ 4)

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 1 | Nguyễn Thị Hiếu Hạnh | Trưởng Phòng | 0388 482 404 |  |  |  |
| 2 | Phạm Tuấn Kiệt | PTP | 0983 666 932 |  |  |  |
| 3 | Trần Minh Khuyên | PTP | 0985 565 399 |  |  |  |
| 4 | Nguyễn Thanh Hiền | PTP | 0919 045 056 |  |  |  |

### Phòng Thanh tra lĩnh vực nnghiệp và môi trường (gọi tắt là Phòng nghiệp vụ 5)

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 1 | Đỗ Minh Thương | Trưởng Phòng | 0937 899 745 |  |  |  |
| 2 | Tạ Văn Nguyễn Hoàng | PTP | 0917 289 381 |  |  |  |
| 3 | Ngô Chí Cường | PTP | 0908 831 494 |  |  |  |
| 4 | Ngô CToàn | PTP | 0974 749 799 |  |  |  |

### Phòng Thanh tra lĩnh vực y tế, giáo dục và khoa học, cnghệ (Phòng nghiệp vụ 6)

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 1 | Nguyễn Huy Hoàng | Trưởng Phòng | 0911 678 779 |  |  |  |
| 2 | Huỳnh Văn Hiệp | PTP | 0833 436 869 |  |  |  |
| 3 | Nguyễn Tứ Đức Học | PTP | 0934 116 677 |  |  |  |
| 4 | Nguyễn Tiến Sĩ | PTP | 0968 153 357 |  |  |  |

### Phòng Thanh tra lĩnh vực cthương và văn hóa, thể thao, du lịch (Phòng nghiệp vụ 7)

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 1 | Nguyễn Thanh Tân | Trưởng Phòng | 0918 585 015 |  |  |  |
| 2 | Nguyễn Thanh Vũ | PTP | 0933 453 039 0979 525 845 |  |  |  |
| 3 | Đặng Hoàng Phong | PTP | 0913 959 654 |  |  |  |
| 4 | Bùi Thị Thúy Kiều | PTP | 0978 606 292 |  |  |  |

### Phòng Giám sát, thẩm định, theo dõi, đôn đốc và xử lý sau thanh tra (Phòng nghiệp vụ 8)

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 1 | Phạm Văn Dũng | Trưởng Phòng | 0982 229 299 |  |  |  |
| 2 | Văn Thế Thiện | PTP | 0909 879 747 |  |  |  |
| 3 | Nguyễn Minh Tâm | PTP | 0948 846 737 |  |  |  |

### Sở Nông nghiệp và Môi trường / Đ/c: Số 04 Đường Song Hành, Phường Long An, tỉnh Tây Ninh; / ĐT bàn: 02723 826 260; 02763 822 648

- Nhóm: 1
- Mã/STT nhóm: 11

### LÃNH ĐẠO SỞ

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 1 | Võ Minh Thành | Giám đốc | 0982 291 239 |  |  |  |
| 2 | Nguyễn Tân Thuấn | Phó Giám đốc | 0915 408 545 |  |  |  |
| 3 | Đinh Thị Phương Khanh | Phó Giám đốc | 0943 864 445 |  |  |  |
| 4 | Phan Văn Tâm | Phó Giám đốc | 0917 600 686 |  |  |  |
| 5 | Đỗ Hữu Phương | Phó Giám đốc | 0916 155 939 |  |  |  |
| 6 | Nguyễn Đình Xuân | Phó Giám đốc | 0916 825 154 |  |  |  |
| 7 | Trần Khắc Phục | Phó Giám đốc | 0983 400 636 |  |  |  |
| 8 | Trương Tấn Đạt | Phó Giám đốc | 0943 785 566 |  |  |  |
| 9 | Trần Văn Quy | Phó Giám đốc | 0941 888 678 |  |  |  |
| 10 | Lê Quang Định | Phó Giám đốc | 0909 395 375 |  |  |  |

### Văn phòng Sở

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 1 | Trần Thị Mộng Thúy | Quyền Chánh Văn phòng | 0903 887 671 |  |  |  |
| 2 | Huỳnh Thị Quyền | Phó Chánh Văn phòng | 0986 977 866 |  |  |  |
| 3 | Phan Nguyễn Ly Ly | Phó Chánh Văn phòng | 0933 658 382 |  |  |  |
| 4 | Huỳnh Thị Thuý Nguyên | Phó Chánh Văn phòng | 0985 645 843 |  |  |  |
| 5 | Võ Phạm Mai Phương | Phó CVP (biệt phái) | 0908 655 015 |  |  |  |
| 6 | Nguyễn Thị Thu Truyền | Phó CVP (biệt phái) | 0383 065 200 |  |  |  |

### Phòng Quản lý, Xây dựng ctrình

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 1 | Phạm Hoàng Long | Trưởng phòng | 0907 548 830 |  |  |  |
| 2 | Trần Thanh Thuyên | PTP | 0969 458 468 |  |  |  |
| 3 | Võ Kim Loan | PTP | 0945 815 915 |  |  |  |
| 4 | Nguyễn Thị Giang | PTP | 0919 222 873 |  |  |  |
| 5 | Lê Thiết Trình | PTP | 0946 801 799 |  |  |  |

### Phòng pháp chế - Chính sách

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 1 | Nguyễn Thị Hoa | Trưởng phòng | 0975 992 804 |  |  |  |
| 2 | Trần Ngọc Hiến Trang | PTP | 0918 593 583 |  |  |  |
| 3 | Huỳnh Phước Hậu | PTP | 0906 357 035 |  |  |  |
| 4 | Nguyễn Thanh Toàn | PTP | 0909 932 224 |  |  |  |

### Phòng Tài nguyên nước và Khoáng sản

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 1 | Trần Thị Mộng Thu | Trưởng phòng | 0916 680 666 |  |  |  |
| 2 | Hồ Quang Minh | PTP | 0918 701 939 |  |  |  |
| 3 | Ngô Thị Mỹ Hạnh | PTP | 0945 173 757 |  |  |  |
| 4 | Vũ Tiến Dũng | PTP | 0909 309 305 |  |  |  |

### Phòng Quản lý đất đai

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 1 | Võ Thị Mỹ Nhân | Trưởng phòng | 0919 622 336 |  |  |  |
| 2 | Lương Minh Tuấn | PTP | 0918 458 468 |  |  |  |
| 3 | Trần Thanh Sơn | PTP | 0383 260 278 |  |  |  |
| 4 | Bùi Thị Thắm Nhanh | PTP | 0984 307 686 |  |  |  |
| 5 | Nguyễn Thị Yến Trinh | PTP | 0938 914 491 |  |  |  |
| 6 | Mai Hoài Hiếu | PTP | 0941 888 481 |  |  |  |

### Chi cục Môi trường và Biến đổi khí hậu, ĐT cơ quan: 02723 672 000 / Đ/c: Số 04 Đường Song Hành, Phường Long An, tỉnh Tây Ninh.

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 1 | Phan CHợi | Quyền Chi cục trưởng | 0908 987 848 |  |  |  |
| 2 | Trương Thị Ngọc Yến | Phó Chi cục trưởng | 0906 302 907 |  |  |  |
| 3 | Trần Phước Hùng | Phó Chi cục trưởng | 0917 266 626 |  |  |  |
| 4 | Đoàn Nguyễn Phương Thảo | Phó Chi cục trưởng | 0937 100 429 |  |  |  |

### Chi cục Kiểm lâm, ĐT bàn: 02763 822 369; Email: CCKltayninh@gmail.com / Đ/c: Số 108, đường 30/4, KP 14 P Tân Ninh, tỉnh Tây Ninh

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 1 | Trần Thị Ngân Hà | Chi cục trưởng | 0908 499 247 | 02763 821 217 |  |  |
| 2 | Trịnh Hùng Cường | Phó Chi cục trưởng | 0987 307 936 | 02723 521 978 |  |  |
| 3 | Tạ Văn Tính | Phó Chi cục trưởng | 0939 665 939 |  |  |  |
| 4 | Võ Văn Trí | Phó Chi cục trưởng | 0989 178 986 | 02763 821 215 |  |  |

### Chi cục Nông nghiệp, ĐT cơ quan: 02723 826 702 / Đ/c: Số 319, QL1, phường Long An, tỉnh Tây Ninh

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 1 | Lê Thị Mai Khanh | Chi cục trưởng | 0902 931 198 |  |  |  |
| 2 | Lương Ngọc Linh | Phó Chi cục trưởng | 0978 311 444 |  |  |  |
| 3 | Trần Thị Mộng Thi | Phó Chi cục trưởng | 0919 289 382 |  |  |  |
| 4 | Lê Thị Kiều Trang | Phó Chi cục trưởng | 0378 082 087 |  |  |  |
| 5 | Nguyễn Thị Hồng Loan | Phó Chi cục trưởng | 0786 449 988 |  |  |  |
| 6 | Nguyễn Võ Thị Ngọc Giàu | Phó Chi cục trưởng | 0974 362 893 |  |  |  |
| 7 | Nguyễn Thị Ngọc Linh | Phó Chi cục trưởng | 0987 780 819 |  |  |  |

### Chi cục Phát triển nông thôn, ĐT bàn: 02723 985 899; Email: ccptnt@tayninh.gov.vn / Đ/c: Số 02, Trần Văn Thiện, Phường Long An, tỉnh Tây Ninh

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 1 | Nguyễn Hoàng Tân | Chi cục trưởng | 0907 578 009 |  |  |  |
| 2 | Lê Hồng Sơn | Phó Chi cục trưởng | 0392 200 778 |  |  |  |
| 3 | Triệu Thị Minh Lý | Phó Chi cục trưởng | 0909 364 061 |  |  |  |
| 4 | Võ Phạm Mai Phương | Phó Chi cục trưởng | 0908 655 015 |  |  |  |
| 5 | Phạm Đăng Khoa | Phó Chi cục trưởng | 0987 698 504 |  |  |  |

### Chi cục Thuỷ lợi, ĐT cơ quan: 0276 3824 324 / Đ/c: Số 606, Đường 30/4, Phường Tân Ninh, tỉnh Tây Ninh

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 1 | Trần Quang Vinh | Chi cục trưởng | 0908 286 276 |  |  |  |
| 2 | Lâm Hồng Thái | Phó Chi cục Trưởng | 0908 842 588 |  |  |  |
| 3 | Phan Thị Thu Cúc | Phó Chi Cục Trưởng | 0967 639 152 |  |  |  |
| 4 | Nguyễn Thị Thu Truyền | Phó Chi Cục Trưởng | 0383 065 200 |  |  |  |

### TT Khuyến nông và Dịch vụ nông nghiệp - / Đ/c: số 31 Quốc lộ 62 phường Tân An, tỉnh Tây Ninh

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 1 | Dương Văn Tuấn | Quyền GĐ | 0985 990 343 |  |  |  |
| 2 | Lê Tấn Tài | Phó GĐ | 0938 592 842 |  |  |  |
| 3 | Võ Thành Nghĩa | Phó GĐ | 0918 895 443 |  |  |  |
| 4 | Hà Thanh Tùng | Phó GĐ | 0907 457 857 |  |  |  |
| 5 | Kiều Quốc Hưng | Phó GĐ | 0988 339 452 |  |  |  |
| 6 | Dương Quốc Hoàng | Phó GĐ | 0918 552 990 |  |  |  |

### TT Thủy lợi và Nước sạch, ĐT cơ quan: 02763 922 281 / Đ/c: Số 1A, Huỳnh Hũu Thống, Phường Long An, tỉnh Tây Ninh

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 1 | Trang Tấn Tài | GĐ | 0918 128 218 | 02723 526 404 |  |  |
| 2 | Giáp Hoàng Quân | Phó GĐ | 0913 999 317 | 02723 839 025 |  |  |
| 3 | Võ Hoàng Quân | Phó GĐ | 0975 071 019 | 02723 526 454 |  |  |
| 4 | Huỳnh Tấn Phúc | Phó GĐ | 0987 830 072 | 02763 922 281 |  |  |

### TT Kỹ thuật tài nguyên và môi trường Đ/c: Số 135 Quốc lộ 1, phường Tân An, tỉnh Tây Ninh.

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 1 | Quách Cao Minh | GĐ | 0989 012 391 |  |  |  |
| 2 | Lê Văn Khơi | Phó GĐ | 0918 855 910 |  |  |  |
| 3 | Huỳnh Võ Tuyết Hân | Phó GĐ | 0945 677 879 |  |  |  |
| 4 | Phan Kim Đồng | Phó GĐ | 0907 979 606 |  |  |  |
| 5 | Lâm Văn Xinh | Phó GĐ | 0918 902 666 |  |  |  |

### Văn phòng Đăng ký đất đai, ĐT cơ quan: 02723 521 111; 02763 815 269 / Đ/c: Số 137 Quốc lộ 1, phường Long An, tỉnh Tây Ninh

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 1 | Lê Thành Được | GĐ | 0915 197 672 | 02723 521 111 |  |  |
| 2 | Huỳnh Anh Tuấn | Phó GĐ | 0918 832 851 | 02723 521 111 |  |  |
| 3 | Nguyễn Thanh Liêm | Phó GĐ | 0918 808 541 | 02723 521 111 |  |  |
| 4 | Trương Nhật Tâm | Phó GĐ | 0976 526 272 | 02723 521 111 |  |  |
| 5 | Lương Nguyễn Đằng Duy | Phó GĐ | 0918 276 656 | 02763 815 269 |  |  |
| 6 | Trần Đặng Đa Lộc | Phó GĐ | 0979 069 797 | 02763 815 269 |  |  |

### Ban Quản lý khu rừng phòng hộ Dầu Tiếng, ĐT cơ quan: 02763 750 408 / Đ/c: Đường 794, ấp 2, xã Tân Hoà, tỉnh Tây Ninh

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 1 | Vũ Anh Đức | Quyền GĐ | 0972 900 877 |  |  |  |
| 2 | Đỗ Phước Vinh | Phó GĐ | 0909 688 691 |  |  |  |

### Khu Bảo tồn đất ngập nước Láng Sen / Đ/c: Ấp Cả Nổ, xã Tân Hưng, tỉnh Tây Ninh

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 1 | Trương Thanh Sơn | GĐ | 0918 127 448 |  |  |  |
| 2 | Nguyễn CToại | Phó GĐ | 0937 990 953 |  |  |  |

### Sở Ngoại vụ / Địa chỉ: Số 65B Châu Văn Giác, Phường Long An, tỉnh Tây Ninh / Email: sngv@tayninh gov vn - Website: sngv tayning gov vn

- Nhóm: 1
- Mã/STT nhóm: 12

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 1 | Đoàn Minh Long | Giám đốc | 0971 767 777 |  |  |  |
| 2 | Lê Hoàng Thanh | Phó Giám đốc | 0918 866 922 |  |  |  |
| 3 | Trần Thị Thu Hằng | Phó Giám đốc | 0908 982 816 |  |  |  |
| 4 | Đặng Thị Thanh Huyền | Phó Giám đốc | 0909 241 462 |  |  |  |
| 5 | Nguyễn Hải Kim Hạnh | Chánh Văn phòng | 0909 393 742 |  |  |  |
| 6 | Nguyễn Thanh Tiến | Phó CVP | 0989 165 072 |  |  |  |
| 7 | Đinh Thị Kim Quyên | PTP PT HTQT - LS | 0834 999 339 |  |  |  |
| 8 | Huỳnh Thị Mỹ Hạnh | PTP PT Quản lý Biên giới | 0819 207 338 |  |  |  |
| 9 | Phạm Nguyễn Hoàng Thảo Uyên | PTP Quản lý Biên giới | 0909 498 938 |  |  |  |
| 10 | Nguyễn Thị Lan Hương | Kế toán | 0949 393 778 |  |  |  |
| 11 | Phùng Đặng Quang Vinh | Chuyên viên | 0985 502 709 |  |  |  |
| 12 | Lê văn Thất | Văn thư | 0916 230 786 |  |  |  |
| 13 | Phan Thị Phúc Nguyên | Chuyên viên | 0946 769 900 |  |  |  |
| 14 | Mai CTrình | Chuyên viên | 0964 494 958 |  |  |  |
| 15 | Võ Lâm Thảo Nguyên | Chuyên viên | 0981 960 103 |  |  |  |
| 16 | Ngô Thị Trường An | Chuyên viên | 0975 345 750 |  |  |  |
| 17 | Nguyễn Lê Thanh Xuân | Chuyên viên | 0813 725 734 |  |  |  |
| 18 | Võ Thanh Tuyền | Lái xe | 0983 000 539 |  |  |  |
| 19 | Danh Thị Thúy Vân | Chuyên viên | 0935 349 862 |  |  |  |
| 20 | Nguyễn Thái Hòa | Chuyên viên | 0918 128 365 |  |  |  |
| 21 | Trần CPhi | Chuyên viên | 0949 499 946 |  |  |  |
| 22 | Hồ Thanh Gia Lộc | Chuyên viên | 0357 225 317 |  |  |  |
| 23 | Đặng Hoàng Tường Vy | Chuyên viên | 0938 908 080 |  |  |  |
| 24 | Đinh Thị Thùy Vân | Chuyên viên | 0798 994 567 |  |  |  |
| 25 | Kim Res Mây | Chuyên viên | 0946 843 635 |  |  |  |

### Sở Dân tộc - Tôn giáo - ĐT bàn: 02763 822 521 / Đ/c: Tầng 3, Khối nhà cơ quan 4, số 2 đường Song Hành, phường Long An, tỉnh Tây Ninh

- Nhóm: 1
- Mã/STT nhóm: 13

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 1 | Trương Thị Phương Thảo | Giám đốc | 0918 457 607 |  |  |  |
| 2 | Trần Minh Nay | Phó Giám đốc | 0913 160 684 |  |  |  |
| 3 | Nguyễn Văn Mưng | Phó Giám đốc | 0374 758 729 |  |  |  |
| 4 | Trịnh Thị Như Trang | Phó Giám đốc | 0976 799 591 |  |  |  |
| 5 | Phạm Minh Trí | Chánh Văn phòng | 0917 032 424 |  |  |  |
| 6 | Nguyễn Minh Sang | Trưởng phòng Tôn giáo | 0918 831 150 |  |  |  |
| 7 | Nguyễn Vĩnh Thế | PTP Tôn giáo | 0917 824 740 |  |  |  |
| 8 | Nguyễn Thanh Sơn | Trưởng phòng Dân tộc | 0947 718 959 |  |  |  |
| 9 | Nguyễn Minh Nhật | PTP Dân tộc | 0913 667 021 |  |  |  |
| 10 | Nguyễn Thị Thúy Ngọc | PTP , phụ trách phòng Tín ngưỡng | 0945 935 912 |  |  |  |

### Trường Chính trị tỉnh Tây Ninh, ĐT bàn: 02723 511 574 / Đ/c: số 1005 Quốc lộ 1A, phường Khánh Hậu, tỉnh Tây Ninh

- Nhóm: 1
- Mã/STT nhóm: 14

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 1 | Phạm Ngọc Hải | Tỉnh ủy viên, Hiệu trưởng | 0909 758 788 |  |  |  |
| 2 | Phan Thị Xuân Lan | Phó Hiệu trưởng | 0984 204 599 |  |  |  |
| 3 | Nguyễn Xuân Luyến | Phó Hiệu trưởng | 0918 300 001 |  |  |  |
| 4 | Nguyễn Hoài Thân | Phó Hiệu trưởng | 0944 979 080 |  |  |  |

#### Khoa Lý luận cơ sở

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 1 | Huỳnh Minh Khởi | Trưởng khoa | 0946 973 633 |  |  |  |
| 2 | Nguyễn Tấn Phước | Phó Trưởng khoa | 0942 074 039 |  |  |  |
| 3 | Phạm Trường Sinh | Phó Trưởng khoa | 0984 226 387 |  |  |  |
| 4 | Nguyễn Thị Huệ | Phó Trưởng khoa | 0903 617 847 |  |  |  |

#### Khoa Xây dựng Đảng

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 1 | Phạm Thị Cẩm Lài | Trưởng khoa | 0906 740 631 |  |  |  |
| 2 | Trần Thanh Phong | Phó Trưởng khoa | 0918 439 732 |  |  |  |
| 3 | Lê Thị Thúy Hà | Phó Trưởng khoa | 0982 121 227 |  |  |  |

#### Khoa Nhà nước và Pháp luật

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 1 | Đoàn Văn Xê | Trưởng khoa | 0918 955 679 |  |  |  |
| 2 | Võ Đình Nguyên Hạnh | Phó Trưởng khoa | 0833 988 206 |  |  |  |
| 3 | Trần Ngọc Hưởng | Phó Trưởng khoa | 0907 673 705 |  |  |  |

#### Phòng Quản lý đào tạo và Nghiên cứu khoa học

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 1 | Mai Tuấn Kiệt | Trưởng phòng | 0947 669 255 |  |  |  |
| 2 | Lê Thị Thanh Thúy | Phó Trưởng phòng | 0945 390 262 |  |  |  |
| 3 | Nguyễn Thị Minh | Phó Trưởng phòng | 0965 318 179 |  |  |  |
| 4 | Nguyễn Hồng Thật | Phó Trưởng phòng | 0979 509 641 |  |  |  |

#### Phòng Tổ chức, hành chính, thông tin, tư liệu

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 1 | Trần Thanh Lâm | Trưởng phòng | 0917 454 116 |  |  |  |
| 2 | Trần Minh Quang | Phó Trưởng phòng | 0948 454 254 |  |  |  |
| 3 | Nguyễn Văn Thới | Phó Trưởng phòng | 0397 399 168 |  |  |  |

### Quỹ Đầu tư Phát triển tỉnh - Quỹ Quỹ Bảo vệ môi trường tỉnh - Quỹ Phát triển đất tỉnh Tây Ninh / Đ/c: 51, Trà Quý Bình, phường Long An, tỉnh Tây Ninh; / Email: quydautuphattrien@tayninh.gov.vn Website: quydtpt.tayninh.gov.vn

- Nhóm: 1
- Mã/STT nhóm: 15

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 1 | Lương Minh Trí | Giám đốc | 0918 585 727 | 850 516 |  |  |
| 2 | Ngô Phạm Phương Thu | Phó Giám đốc | 0909 937 678 | 681318 |  |  |
| 3 | Nguyễn Thị Lộc | Phó Giám đốc | 0946 455 888 | 681319 |  |  |
| 4 | Nguyễn Thuý Huyên | Phó Giám đốc | 0913 977 246 | 551 922 |  |  |
| 5 | Đặng Thị Thuý Hà | Phó Giám đốc | 0918 105 375 | 986 222 |  |  |
| 6 | Trần Thị Phương Minh | Chánh Văn phòng | 0971 698 689 | 553 935 |  |  |
| 7 | Phan Quang Vinh | Phó Chánh Văn phòng | 0393 333 657 | 553 935 |  |  |
| 8 | Lê CĐiệp | Phó Chánh Văn phòng | 0902 330 404 | 553 935 |  |  |
| 9 | Đặng Thị Kiều Oanh | Kế toán trưởng | 0369 182 332 | 553 677 |  |  |
| 10 | Phạm Thị Thanh Hoà | Phó Trưởng phòng Tài chính Kế toán | 0985 407 665 | 553 677 |  |  |
| 11 | Huỳnh Thị Hồng Mỹ | Phó Trưởng phòng Tài chính Kế toán | 0909 882 909 | 553 677 |  |  |
| 12 | Huỳnh Thanh Bình | Trưởng phòng Tín dụng | 0946 688 917 | 553 738 |  |  |
| 13 | Nguyễn Thị Ngọc Bích | Phó Trưởng phòng Tín dụng | 0902 657 557 | 553 738 |  |  |
| 14 | Trương Thị Hương Lan | Phó Trưởng phòng Tín dụng | 0984 015 215 | 553 738 |  |  |
| 15 | Nguyễn Thị Bích Đào | Phó Trưởng phòng Tín dụng | 0983 331 711 | 553 738 |  |  |
| 16 | Trần Thị Thanh Thoảng | Trưởng phòng Kế hoạch Thẩm định | 0816 616 463 | 839 202 |  |  |
| 17 | Huỳnh Văn Sáu | Phó Trưởng phòng Kế hoạch Thẩm định | 0946 106 060 | 839 202 |  |  |
| 18 | Nguyễn Xuân Phát | Phó Trưởng phòng Kế hoạch Thẩm định | 0933 609 960 | 839 202 |  |  |
| 19 | Nguyễn Ngọc Lý | Phó Trưởng phòng Kế hoạch Thẩm định | 0916 083 868 | 839 202 |  |  |
| 20 | Thới Thị Hoa Thơm | Trưởng phòng Ủy thác | 0912 005 552 | 935 456 |  |  |
| 21 | Lưu Thái Phong | Phó Trưởng phòng Ủy thác | 0907 676 167 | 935 456 |  |  |
| 54 | Lục Văn Cỏng | Trưởng ban Quản lý Cụm Cnghiệp | 0913 999 342 | 550 144 |  |  |

### Ban Quản lý Khu Kinh tế - / Đ/c: 25, quốc lộ 62, phường Long An, tỉnh Tây Ninh / ĐT bàn: 02723 825 445; 02763 922 661; Email: bqlkkt@tayninh.gov.vn; Website: bqlkkt.tayninh.gov.vn

- Nhóm: 1
- Mã/STT nhóm: 16

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 1 | Trương Thanh Liêm | Trưởng ban | 0912 783 979 |  |  |  |
| 2 | Trương Văn Hùng | PTB, kiêm GĐ TT QL cửa khẩu Tây Ninh | 0888 819 333 |  |  |  |
| 3 | Nguyễn Văn Thông | Phó Trưởng ban | 0909 236 544 |  |  |  |
| 4 | Võ Anh Linh | Phó Trưởng ban | 0913 999 339 |  |  |  |
| 5 | Lê Thanh Kiệt | Phó Trưởng ban | 0915 407 354 |  |  |  |
| 6 | Thái Bình An | Phó Trưởng ban | 0913 880 220 |  |  |  |
| 7 | Nguyễn Anh Vũ | Chánh Văn phòng | 0908 503 988 | 02723 825 445 |  |  |
| 8 | Nguyễn Kim Hà | Phó Chánh VP | 0984 807 762 |  |  |  |
| 9 | Đặng Phước Thành | Trưởng phòng Doanh nghiệp và Lao động | 0833 999 268 | 02723 825 449 |  |  |
| 10 | Nguyễn Anh Quốc Tuấn | Phó phòng Doanh nghiệp và Lao động | 0949 819 964 |  |  |  |
| 11 | Trần Minh Trí | Trưởng phòng Kế hoạch và Đầu tư | 0903 383 753 | 02723 825 446 |  |  |
| 12 | Trần Vĩnh Thái | Phó phòng Kế hoạch và Đầu tư | 0987 304 872 |  |  |  |
| 13 | Tô Huệ Tri | Phó phòng Kế hoạch và Đầu tư | 0907 058 068 |  |  |  |
| 14 | Vương Thị Mai Thi | Trưởng phòng Môi trường | 0908 113 358 |  |  |  |
| 15 | Phan Hửu Phát | Phó phòng Môi trường | 0983 944 550 |  |  |  |
| 16 | Nguyễn Trần Bảo Trường | Phó phòng Môi trường | 0945 246 470 |  |  |  |
| 17 | Ngô Vĩnh Thiện | Trưởng phòng Quy hoạch và Xây dựng | 0919 213 825 | 02723 835 600 |  |  |
| 18 | Huỳnh Hữu Khoa | Phó phòng Quy hoạch và Xây dựng | 0908 596 650 |  |  |  |
| 19 | Vương Trọng Nghĩa | Phó phòng Quy hoạch và Xây dựng | 0919 058 749 |  |  |  |
| 20 | Nguyễn Phạm Trí Quang | Phó phòng Quy hoạch và Xây dựng | 0983 644 631 |  |  |  |
| 21 | Hồ Ngọc Hiếu | Phó GĐ TT quản lý cửa khẩu Tây Ninh | 0945 152 525 |  |  |  |
| 22 | Trương Quốc Toàn | Phó GĐ TT quản lý cửa khẩu Tây Ninh | 0931 792 257 |  |  |  |
| 23 | Lê Tất Thành | Phó GĐ TT quản lý cửa khẩu Tây Ninh | 0906 208 748 |  |  |  |

### Ban Quản lý Dự án Đầu tư xây dựng tỉnh Tây Ninh; / Đ/c: 86, Phạm Tung, Khu phố 1, Phường Tân Ninh, tỉnh Tây Ninh / ĐT bàn: 027632240008 ; website: banquanlyduantinh.tayninh.gov.vn;

- Nhóm: 1
- Mã/STT nhóm: 17

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 1 | Trương Văn Dễ | Giám đốc | 0913 955 875 |  |  |  |
| 2 | Nguyễn Thị Ngọc Vui | Phó Giám đốc | 0915 414 449 |  |  |  |
| 3 | Đặng Xuân Trường | Phó Giám đốc | 0989 170 030 |  |  |  |
| 4 | Huỳnh Hữu Khang Hy | Phó Giám đốc | 0915 414 557 |  |  |  |
| 5 | Phạm Phương Bình | Phó Giám đốc | 0909 982 078 |  |  |  |
| 6 | Nguyễn Sơn Phước | Chánh Văn phòng | 0986 928 707 |  |  |  |
| 7 | Lê công đoàn | Phó CVP | 0989 757 226 |  |  |  |
| 8 | Dương Nguyễn Phúc | Phó CVP | 0942 719 346 |  |  |  |
| 9 | Trần Thanh Dũng | Trưởng phòng - phòng Tài chính | 0906 815 678 |  |  |  |
| 10 | Trần Thanh Phong | PTP - phòng Tài chính | 0909 934 985 |  |  |  |
| 11 | Nguyễn Thị Thanh Thúy | PTP - phòng Tài chính | 0983 011 213 |  |  |  |
| 12 | Dương Hoài Thanh | Trưởng phòng - phòng Kỹ thuật - Thẩm định | 0969 557 657 |  |  |  |
| 13 | Phan Thanh Thảo | PTP - phòng Kỹ thuật - Thẩm định | 0907 900 888 |  |  |  |
| 14 | Lê Trung Kiên | PTP - phòng Kỹ thuật - Thẩm định | 0918 489 780 |  |  |  |
| 15 | Trần CTuấn Anh | Trưởng phòng - phòng Quản lý dự án ctrình dân dụng | 0834 221 274 |  |  |  |
| 16 | Cao Thanh Vân | PTP - phòng Quản lý dự án ctrình dân dụng | 0907 762 977 |  |  |  |
| 17 | Nguyễn Huy | PTP - phòng Quản lý dự án ctrình dân dụng | 0907 973 686 |  |  |  |
| 18 | Trịnh Hải Âu | Trưởng phòng - phòng Quản lý dự án ctrình Giao th- hạ tầng kỹ thuật | 0983 607 798 |  |  |  |
| 19 | Mai Thái Duy | PTP - phòng Quản lý dự án ctrình Giao th- hạ tầng kỹ thuật | 0908 258 779 |  |  |  |
| 20 | Đặng Quốc Thái | PTP - phòng Quản lý dự án ctrình Giao th- hạ tầng kỹ thuật | 0968 655 133 |  |  |  |

#### BAN QUẢN LÝ DỰ ÁN ĐẦU TƯ XÂY DỰNG KHU VỰC 1; Đ/c: Số 135, đường Nguyễn Trãi, khu phố 13, Phường Tân Ninh, tỉnh Tây Ninh

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 1 | Lương Văn Có | Phó GĐ phụ trách | 0907 132 087 |  |  |  |
| 2 | Lê Thành Phụng | Phó GĐ | 0916 499 749 |  |  |  |

#### BAN QUẢN LÝ DỰ ÁN ĐẦU TƯ XÂY DỰNG KHU VỰC 2; Đ/c: Số 87, đường Hùng Vương, Khu phố 2, Phường Long Hoa, tỉnh Tây Ninh

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 1 | Lâm Minh Bảo | GĐ | 0913 878 957 |  |  |  |
| 2 | Trần Ngọc Minh | Phó GĐ | 0948 135 252 |  |  |  |
| 3 | Nguyễn Thế Nam | Phó GĐ | 0977 674 577 |  |  |  |

#### BAN QUẢN LÝ DỰ ÁN ĐẦU TƯ XÂY DỰNG KHU VỰC 3; Đ/c: Số 103 đường Duy Tân, khu phố Lộc Thành, phường Trảng Bàng, tỉnh Tây Ninh

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 1 | Trần Tấn Phát | GĐ | 0913 884 111 |  |  |  |
| 2 | Nguyễn Nhất Linh | Phó GĐ | 0913 955 465 |  |  |  |
| 3 | Hà Minh Chất | Phó GĐ | 0913 065 252 |  |  |  |

#### BAN QUẢN LÝ DỰ ÁN ĐẦU TƯ XÂY DỰNG KHU VỰC 4; Đ/c: Đường Nguyễn Hữu Thọ, phường Gò Dầu, tỉnh Tây Ninh

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 1 | Thái Văn Cường | GĐ | 0914 833 767 |  |  |  |
| 2 | Phạm Văn Thuận | Phó GĐ | 0918 430 198 |  |  |  |
| 3 | Nguyễn Phương Duy | Phó GĐ | 0938 442 918 |  |  |  |

#### BAN QUẢN LÝ DỰ ÁN ĐẦU TƯ XÂY DỰNG KHU VỰC 5; Đ/c: Số 257, đường Nguyễn Chí Thanh, xã Dương Minh Châu, tỉnh Tây Ninh

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 1 | Phạm Minh Tùng | GĐ | 0909 498 997 |  |  |  |
| 2 | Nguyễn Bảo Hà | Phó GĐ | 0902 748 307 |  |  |  |

#### BAN QUẢN LÝ DỰ ÁN ĐẦU TƯ XÂY DỰNG KHU VỰC 6; Đ/c: Đường Nguyễn Hữu Dụ, Khu phố 3, Xã Tân Châu, Tây Ninh

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 1 | Hoàng Văn Huy | GĐ | 0975 320 739 |  |  |  |
| 2 | Nguyễn Ngọc Nguyên | Phó GĐ | 0818 156 116 |  |  |  |

#### BAN QUẢN LÝ DỰ ÁN ĐẦU TƯ XÂY DỰNG KHU VỰC 7; Đ/c: số 15, đường Nguyễn Văn Linh, khu phố 3, xã Tân Biên, tỉnh Tây Ninh

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 1 | Nguyễn Minh Thành | GĐ | 0975 594 594 |  |  |  |
| 2 | Trần Thị Thùy Dương | Phó GĐ | 0979 979 537 |  |  |  |

#### BAN QUẢN LÝ DỰ ÁN ĐẦU TƯ XÂY DỰNG KHU VỰC 8; Đ/c: Đường Hoàng Lê Kha, xã Châu Thành, tỉnh Tây Ninh

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 1 | Nguyễn Phạm Ngọc San | Phó GĐ phụ trách | 0983 570 876 |  |  |  |
| 2 | Nguyễn Bảo Duy | Phó GĐ | 0868 897 070 |  |  |  |

#### BAN QUẢN LÝ DỰ ÁN ĐẦU TƯ XÂY DỰNG KHU VỰC 9; Đ/c: khu phố 1, xã Bến Cầu, tỉnh Tây Ninh

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 1 | Tạ Hoàng Vũ | Phó GĐ phụ trách | 0986 681 197 |  |  |  |

### BQL Dự án ĐTXD ngành Nông nghiệp và PTNT tỉnh / Đ/c: Số 17 đường Võ Thị Sáu, phường Tân Ninh, tỉnh Tây Ninh / ĐT bàn: 02763 827 760; email: bqlnn.tayninh@gmail.com;

- Nhóm: 1
- Mã/STT nhóm: 18

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 1 | Nguyễn Thành Quan | GĐ | 0983 635 695 |  |  |  |
| 2 | Bùi Xuân Phượng | Phó GĐ | 0979 665 188 |  |  |  |
| 3 | Võ Văn Hoài Linh | Phó GĐ | 0979 757 377 |  |  |  |
| 4 | Huỳnh Thanh Hoài | Phó CVP, phụ trách | 0915 412 990 |  |  |  |
| 5 | Nguyễn Phương Ngọc | PTP Kế hoạch - Tổng hợp, phụ trách | 0974 698 631 |  |  |  |
| 6 | Nguyễn Thành Trung | Trưởng phòng Quản lý dự án | 0908 883 505 |  |  |  |
| 7 | Nguyễn Văn Việt Danh | Trưởng phòng Kỹ thuật - Thẩm định | 0909 782 265 |  |  |  |
| 8 | Phan Hữu Đức | PTP Kỹ thuật - Thẩm định | 0797 378 738 |  |  |  |
| 9 | Nguyễn Hải Đăng | Kế toán trưởng, phụ trách phòng Tài chính - Kế toán | 0941 309 292 |  |  |  |

### Ban An toàn Giao thông - / Đ/c: số 04 đường Song Hành, Phường Long An, tỉnh Tây Ninh. / email: banatgt@tayninh.gov.vn;

- Nhóm: 1
- Mã/STT nhóm: 19

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 1 | Nguyễn Nam Hưng | Giám đốc Sở Xây dựng - kiêm Phó trưởng Ban | 0913 955 407 |  |  |  |
| 2 | Nguyễn Đỗ Xuân Vũ | Chánh Văn phòng Ban | 0903 113 332 |  |  |  |
| 3 | Võ Hồng Thái | Phó Chánh Văn phòng Ban | 0918 114 282 |  |  |  |

### BAN QUẢN LÝ CÁC KHU DI TÍCH LỊCH SỬ CÁCH MẠNG MIỀN NAM - / Đ/c: Số 57 Pasteur, phường Tân Ninh, tỉnh Tây Ninh / ĐT: 02763 818 178; ttps://bqldtcmmn tayninh gov vn

- Nhóm: 1
- Mã/STT nhóm: 20

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 1 | Phan Thanh Nhàn | GĐ | 913955081 |  |  |  |
| 2 | Trần Văn Hiếu | Phó GĐ | 938066699 |  |  |  |
| 3 | Phạm An Chiến | Phó GĐ | 978405406 |  |  |  |
| 4 | Thái Thị Quyên | Trưởng phòng Tổ chức - Hành chính | 915424552 |  |  |  |
| 5 | Đoàn Văn Thành | PTP Tổ chức - Hành chính | 915987066 |  |  |  |
| 6 | Cao Hoài Phương | PTP Quản lý & Khai thác di tích | 982093739 |  |  |  |
| 7 | Lê Trung Hiếu | PTP Quản lý & Khai thác di tích | 974134357 |  |  |  |

### Ban Quản lý Khu du lịch quốc gia Núi Đen - / Địa chỉ: Khu phố Ninh Phú, Phường Bình Minh, tỉnh Tây Ninh / Điện thoại bàn 02763823378; email: bqlnuiba@gmail.com; website: https://bqlnuiba.tayninh.gov.vn

- Nhóm: 1
- Mã/STT nhóm: 21

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 1 | Trần Thái Nam | Bí thư chi bộ, Trưởng ban | 0987 175 152 |  |  |  |
| 2 | Trần Thị Thu Hằng | Phó Bí thư chi bộ, Phó Trưởng ban | 0949 095 051 |  |  |  |
| 3 | Phạm Thanh Tuyền | Phó Trưởng ban | 0918 986 198 |  |  |  |
| 4 | Hồ Nhựt Khoa | CUV, TP Quản lý di tích và Hoạt động du lịch | 0396 077 836 |  |  |  |
| 5 | Phạm Xuân Thành | CUV, PCVP phụ trách Văn phòng Ban Quản lý | 0949 019 919 |  |  |  |
| 6 | Hồ Đắc Long | PTP phụ trách Phòng Quản lý bảo vệ rừng | 0908 361 007 |  |  |  |
| 7 | Nguyễn Văn Sang | PTP phụ trách Phòng Quy hoạch đầu tư và Xây dựng | 0364 100 111 |  |  |  |

### Ban Quản lý Vườn Quốc Gia Lò Gò - Xa Mát - / Đ/c: Xã Tân Biên, tỉnh Tây Ninh / Email: vqglogoxamat@tayninh.gov.vn

- Nhóm: 1
- Mã/STT nhóm: 22

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 1 | Lê CHiệu | Phó GĐ phụ trách | 0822 645 139 | 0663 874 018 |  |  |
| 2 | Tạ Ngọc Dân | Phó GĐ | 0909 477 983 |  |  |  |
| 3 | Nguyễn Minh Cường | Phó GĐ | 0914 652 972 |  |  |  |
| 4 | Nguyễn Văn Cường | Trưởng phòng Kế hoạch - Tài chính | 0913 477 887 |  |  |  |
| 5 | Trần Văn Lành | PTP Kế hoạch - Tài chính | 0918 575 828 |  |  |  |
| 6 | Nguyễn Xuân Hiếu | Trưởng phòng TCHC | 0976 040 516 |  |  |  |
| 7 | Nguyễn Thị Hằng | PTP TCHC | 0933 249 696 |  |  |  |
| 8 | Nguyễn Long Điền | Trưởng phòng QLBVR | 0908 685 605 |  |  |  |
| 9 | Lê Quang Bản | PTP QLBVR | 0909 197 155 |  |  |  |
| 10 | Lê Văn Nam | PTP QLBVR | 0914 572 256 |  |  |  |
| 11 | Nguyễn Hoàng Sơn | Trưởng phòng KHBT&HTQT | 0918 271 471 |  |  |  |
| 12 | Nguyễn Thị Tuyết Mai | Phó GĐ phụ trách TTGD&DVMTR | 0977 613 402 |  |  |  |

### TT PHÁT TRIỂN QUỸ ĐẤT TỈNH TÂY NINH - / Đ/c: Số 141 Quốc lộ 1, phường Long An, tỉnh Tây Ninh; email: ttptqd@tayninh gov vn

- Nhóm: 1
- Mã/STT nhóm: 23

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 1 | Nguyễn Minh Hùng | GĐ | 0913 883 889 |  |  |  |
| 2 | Nguyễn Anh Đức | Phó GĐ | 0963 299 209 |  |  |  |
| 3 | Phạm Tùng Chinh | Phó GĐ | 0918 896 636 |  |  |  |
| 4 | Nguyễn Văn Hải | CVP | 0916 998 948 |  |  |  |
| 5 | Dương Hoàng An | Phó CVP | 0902 610 426 |  |  |  |
| 6 | Phan Thị Trà Mi | Phó CVP | 0947 352 067 |  |  |  |
| 7 | Hồ Hoài Vũ | TP Bồi thường và GPMB | 0919 458 090 |  |  |  |
| 8 | Phan Phúc Hiếu | PTP Bồi thường và Gpmb | 0908 586 422 |  |  |  |
| 9 | Nguyễn Lê Duy | TP Quản lý và khai thác quỹ đất | 0913 999 916 |  |  |  |
| 10 | Phan Việt Linh | PTP Quản lý và khai thác quỹ đất | 0918 792 529 |  |  |  |
| 11 | Nguyễn Phương Minh | PTP Quản lý và khai thác quỹ đất | 0918 767 933 |  |  |  |
| 12 | Dương Quốc Phương | PTP Quản lý và khai thác quỹ đất | 0977 503 992 |  |  |  |
| 13 | Trần Thanh Nhàn | Trưởng phòng Tư vấn giá đất | 0918 976 776 |  |  |  |
| 14 | Nguyễn Thị Ngọc Hương | PTP Tư vấn giá đất | 0942 718 377 |  |  |  |
| 15 | Lê Thế Khanh | Trưởng phòng | 0909 588 115 |  |  |  |

### Chi nhánh TT Phát triển quỹ đất Khu vực Bến Lức / Số 213 Quốc lộ 1, xã Bến Lức, tỉnh Tây Ninh

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 16 | Bùi Văn Trí | GĐ | 0918 499 669 |  |  |  |
| 17 | Trần Thị Thu Chinh | Phó GĐ | 0989 812 737 |  |  |  |
| 18 | Huỳnh Lê Trung Việc | Phó GĐ | 0847 277 879 |  |  |  |

### Chi nhánh TT Phát triển quỹ đất Khu vực Cần Giuộc / Số 151 Quốc Lộ 50, xã Cần Giuộc, tỉnh Tây Ninh

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 19 | Võ Văn Thơ | GĐ | 0919 611 606 |  |  |  |
| 20 | Ngô Trung Thanh | Phó GĐ | 0908 242 709 |  |  |  |
| 21 | Phùng Văn Vinh | Phó GĐ | 0931 913 153 |  |  |  |
| 22 | Lê Minh Phương | Phó GĐ | 0917 150 777 |  |  |  |

### Chi nhánh TT Phát triển quỹ đất Khu vực Kiến Tường / Đường Nguyễn Thị Lẹ, Khu phố 12, Phường Kiến Tường, tỉnh Tây Ninh

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 23 | Lê Thanh Lê | GĐ | 0913 727 798 |  |  |  |
| 24 | La Văn Hâu | Phó GĐ | 0948 737 681 |  |  |  |
| 25 | Châu Phú Hùng | Phó GĐ | 0944 008 939 |  |  |  |
| 26 | Đỗ Thành Anh Tiến | Phó GĐ | 0978 237 332 |  |  |  |

### Chi nhánh TT Phát triển quỹ đất Khu vực Đức Hòa / Đường 3 tháng 2, xã Hậu Nghĩa, tỉnh Tây Ninh

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 27 | Lê Thành Trung | GĐ | 0918 704 911 |  |  |  |
| 28 | Lê Văn Tình | Phó GĐ | 0905 699 849 |  |  |  |

### Chi nhánh TT Phát triển quỹ đất Khu vực Tân An / Số 187, đường Hùng Vương, phường Long An, tỉnh Tây Ninh

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 29 | Võ Thành An | Phó GĐ phụ trách | 0916 711 847 |  |  |  |
| 30 | Nguyễn Minh Duy | Phó GĐ | 0918 899 647 |  |  |  |
| 31 | Nguyễn Nhất Linh | Phó GĐ | 0972 989 979 |  |  |  |

### Báo và Phát thanh truyền hình tỉn Tây Ninh / ĐT bàn: 02723 826 244

- Nhóm: 1
- Mã/STT nhóm: 24

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 1 | Lê Hồng Phước | Tổng Biên tập | 0382 345 288 |  |  |  |
| 2 | Lê Thị Thanh Tuyền | Phó Tổng Biên tập | 0918 589 502 |  |  |  |
| 3 | Nguyễn Thị Thùy Dung | Phó Tổng Biên tập | 0908 633 474 |  |  |  |
| 4 | Châu Hồng Khá | Phó Tổng Biên tập | 0918 700 591 |  |  |  |
| 5 | Nguyễn Thị Huyền Thu | Phó Tổng Biên tập | 0906 708 981 |  |  |  |
| 6 | Võ Văn Quý | Phó Tổng Biên tập | 0945 612 772 |  |  |  |
| 7 | Đặng Hoàng Thái | Phó Tổng Biên tập | 0913 955 775 |  |  |  |
| 8 | Dương Nguyễn Hoàng Anh | Phó Tổng Biên tập | 0913 884 796 |  |  |  |
| 9 | Lê Bá Thành | Trưởng phòng Tổ chức-Hành chính | 0987 733 332 |  |  |  |
| 10 | Bùi Thị Minh Tâm | TP Dịch vụ quảng cáo-Phát hành | 0946 858 080 |  |  |  |
| 11 | Nguyễn Thanh Tuấn | TP Kỹ thuật và Công nghệ | 0918 896 736 |  |  |  |
| 12 | Nguyễn Minh Hiếu | TP Phát thanh và Văn nghệ giải trí | 0913 833 423 |  |  |  |
| 13 | Nguyễn Trung Hiếu | TP Sản xuất chương trình | 0944 454 651 |  |  |  |
| 14 | Nguyễn Văn Bằng | Trưởng phòng Thời sự | 0947 569 929 |  |  |  |
| 15 | Nguyễn Thái Hòa | Trưởng phòng Chuyên đề | 0913 884 239 |  |  |  |
| 16 | Trần Thanh Hiểu | Trưởng phòng Thư ký Biên tập | 0917 676 330 |  |  |  |
| 17 | Nguyễn Đăng Châu | TP Báo điện tử và Nội dung số | 0937 769 254 |  |  |  |

### Phân xã Thông tấn xã Việt Nam / Cơ sở 1: 19 Trương Định, phường Long An, tỉnh Tây Ninh / Cơ sở 2: 261 đường Cách Mạng Tháng 8, khu phố 2, phường Tân Ninh, tỉnh Tây Ninh

- Nhóm: 1
- Mã/STT nhóm: 25

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 1 | CQTT TTXVN tại Tây Ninh | Bí thư Chi bộ Cụm Bắc SHậu; Trưởng CQTT TTXVN tại Tây Ninh | 0909 203 866 |  |  |  |
| 2 | CQTT TTXVN tại Tây Ninh ( CS 2) | Phạm Thanh Tân -Phó Trưởng CQTT TTXVN tại Tây Ninh | 09080075 444 |  |  |  |

## Các cơ quan ngành dọc

### Công an tỉnh / Số Điện thoại Trực ban: 02723 829 399; 0693 609 174

- Nhóm: 1
- Mã/STT nhóm: 1

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 1 | Vũ Như Hà | Giám đốc | 0988 885 885 |  |  |  |
| 2 | Phan Văn Triều | Phó Giám đốc | 0913 955 466 |  |  |  |
| 3 | Trần Văn Luận | Phó Giám đốc | 0918 227 254 |  |  |  |
| 4 | Lê Văn Thuận | Phó Giám đốc | 0913 647 632 |  |  |  |
| 5 | Lê Trung Ái | Phó Giám đốc | 0905 228 234 |  |  |  |
| 6 | Nguyễn Quốc Toàn | Phó Giám đốc | 0989 990 268 |  |  |  |
| 7 | Phạm Thanh Tâm | Phó Giám đốc | 0983 446 472 |  |  |  |
| 8 | Nguyễn Phú Cường | Trưởng phòng PA01 | 0387 344 409 |  |  |  |
| 9 | Nguyễn Thanh Sơn | Trưởng phòng PA02 | 0915 417 375 |  |  |  |
| 10 | Phan Thị Tường Vi | Trưởng phòng PA03 | 0919 606 900 |  |  |  |
| 11 | Đặng Chí Trung Hiếu | Trưởng phòng PA04 | 0786 688 666 |  |  |  |
| 12 | Nguyễn Quốc Hải | Trưởng phòng PA05 | 0988 612 320 |  |  |  |
| 13 | Nguyễn Minh Sáng | Trưởng phòng PA06 | 0913 601 909 |  |  |  |
| 14 | Trần Văn Đông | Trưởng phòng PA08 | 0913 822 844 |  |  |  |
| 15 | Huỳnh Văn Trinh | Trưởng phòng PA09 | 0913 999 708 |  |  |  |
| 16 | Nguyễn Thanh Phong | Trưởng phòng PC01 | 0917 725 075 |  |  |  |
| 17 | Huỳnh Văn Quang Vũ | Trưởng phòng PC02 | 0933 666 086 |  |  |  |
| 18 | Phạm Văn Rum | Trưởng phòng PC03 | 0913 880 316 |  |  |  |
| 19 | Nguyễn Thanh Phong | Trưởng phòng PC04 | 0919 369 370 |  |  |  |
| 20 | Trương Nhật Minh | Trưởng phòng PC06 | 0909 838 289 |  |  |  |
| 21 | Nguyễn CBằng | Trưởng phòng PC07 | 0848 453 459 |  |  |  |
| 22 | Nguyễn Hoàng Anh | Trưởng phòng PC08 | 0943 444 404 |  |  |  |
| 23 | Nguyễn Thanh Phú | Trưởng phòng PC09 | 0983 881 517 |  |  |  |
| 24 | Trần Minh Hoàng | Trưởng phòng PC10 | 0908 288 509 |  |  |  |
| 25 | Lê Quốc Hưng | Trưởng phòng PC11A | 0917 602 977 |  |  |  |
| 26 | Nguyễn CĐỉnh | Trưởng phòng PC11B | 0908 172 656 |  |  |  |
| 27 | Nguyễn Ngọc Thành | Trưởng phòng PK02 | 0903 050 161 |  |  |  |
| 28 | Nguyễn Hai Mừng | Trưởng phòng PV01 | 0913 609 454 |  |  |  |
| 29 | Nguyễn Văn Tiển | Trưởng phòng PV06 | 0986 869 797 |  |  |  |
| 30 | Nguyễn Phước Hòa | Trưởng phòng PX01 | 0903 608 434 |  |  |  |
| 31 | Lê Văn Phước | Trưởng phòng PX03 | 0918 499 998 |  |  |  |
| 32 | Trịnh Văn Tạo | Trưởng phòng PX05 | 0903 717 238 |  |  |  |
| 33 | Phan Thị Đình Nghiêm | Trưởng phòng PX06 | 0899 505 665 |  |  |  |
| 34 | Trương Thanh Bình | Trưởng phòng PH10 | 0942 765 789 |  |  |  |

### Bộ Chỉ huy Quân sự tỉnh Tây Ninh - ĐT bàn: 02723 826 338; 02723 834 873 / Đ/c: 175 quốc lộ 62, phường Long An, tỉnh Tây Ninh

- Nhóm: 1
- Mã/STT nhóm: 2

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 1 | Nguyễn Thành Tâm | Uỷ viên Ban TVTU, Chỉ huy trưởng | 0979 290 568 | 069 649 101 |  |  |
| 2 | Nguyễn Thanh Phong | Tỉnh uỷ viên, Chính uỷ BCHQS tỉnh | 0989 006 871 | 069 649 102 |  |  |
| 3 | Trần Đình Hưng | Phó CHT kiêm Tham mưu trưởng Bộ Chỉ huy Quân sự tỉnh | 0975 110 055 | 069 649 103 |  |  |
| 4 | Đàm Quang Ngoạt | Tỉnh uỷ viên, Phó CHT BCHQS tỉnh / kiêm Chỉ huy trưởng Ban Chỉ huy Bộ đội Biên phòng tỉnh | 0967 636 983 | 069 646 501 |  |  |
| 5 | Hà Thanh Tuấn | Phó CHT Bộ Chỉ huy Quân sự tỉnh | 0985 712 175 | 069 649 104 |  |  |
| 6 | Nguyễn Đình Huân | Phó CHT Bộ Chỉ huy Quân sự tỉnh | 0906 757 568 | 069 649 105 |  |  |
| 7 | Nguyễn Thành Đạt | Phó CHT Bộ Chỉ huy Quân sự tỉnh | 0975 964 717 | 069 649 220 |  |  |
| 8 | Nguyễn Minh Tấn | Phó Chính uỷ Bộ Chỉ huy Quân sự tỉnh | 0965 737 573 | 069 649 106 |  |  |
| 9 | Phạm Văn Quốc | Phó Chính uỷ Bộ Chỉ huy Quân sự tỉnh | 0869 683 585 | 069 649 276 |  |  |
| 10 | Ngô Khánh | Phó Chính uỷ Bộ Chỉ huy Quân sự tỉnh | 0982 102 008 | 069 649 110 |  |  |
| 11 | Trần Phi Hữu | CVP Bộ Chỉ huy Quân sự tỉnh | 0963 051 442 | 069 649 133 |  |  |
| 12 | Nguyễn Minh Kha | Phó CVP Bộ Chỉ huy Quân sự tỉnh | 0982 482 779 |  |  |  |
| 13 | Huỳnh Minh Mẫn | Phó CVP Bộ Chỉ huy Quân sự tỉnh | 0983 220 048 |  |  |  |
| 14 | Nguyễn Trung Chính | TB Tài chính Bộ Chỉ huy Quân sự tỉnh | 0988 189179 | 069 649 166 |  |  |
| 15 | Đào Thanh Hải | PTB Tài chính Bộ Chỉ huy Quân sự tỉnh | 0986 888 832 |  |  |  |
| 16 | Phạm Văn Quốc | Phó CVP Bộ Chỉ huy Quân sự tỉnh | 0979 864 447 |  |  |  |
| 17 | Nguyễn Đức Thảo | Phó Tham mưu trưởng | 0868 699 947 | 069 649 111 |  |  |
| 18 | Lê Thanh Định | Phó Tham mưu trưởng | 0945 439 027 | 069 649 112 |  |  |
| 19 | Lê Việt Thắng | Phó Tham mưu trưởng | 0984 841 819 | 069 649 113 |  |  |
| 20 | Võ Minh Quốc | Phó Tham mưu trưởng | 0983 477 485 | 069 649 114 |  |  |
| 21 | Trần Đức Mạnh | Phó Tham mưu trưởng | 0358 462 271 | 069 649 135 |  |  |
| 22 | Nguyễn Đình Phương | Chủ nhiệm Chính trị | 0982 443 223 | 069 649 141 |  |  |
| 23 | Võ Lê Hiến | PCN Chính trị | 0989 842 431 | 069 649 142 |  |  |
| 24 | Võ Đức Dũng | PCN Chính trị | 0989 099 399 |  |  |  |
| 25 | Đặng Thanh Liêm | PCN Chính trị Bộ Chỉ huy Quân sự tỉnh | 0977 555 625 | 069 649 156 |  |  |
| 26 | Nguyễn Thanh Phong | PCN Phòng Chính trị | 0977 620 987 | 069 649 151 |  |  |
| 27 | Huỳnh Trunh Hậu | Chủ nhiệm Hậu cần-Kỹ thuật | 0963 787 892 | 069 649 181 |  |  |
| 28 | Đặng Thanh Tòng | PCN Hậu cần-Kỹ thuật | 0989 277 778 | 069 649 183 |  |  |
| 29 | Mai Bá Phước | PCN Hậu cần-Kỹ thuật | 0937 001 267 | 069 649 162 |  |  |
| 30 | Vũ Trường Thanh | PCN Hậu cần-Kỹ thuật | 0982 798 797 |  |  |  |
| 31 | Đoàn Văn Tờ | PCN Hậu cần-Kỹ thuật | 0973 597 537 | 069 649 163 |  |  |
| 32 | Lê Thanh Tùng | Chỉ huy trưởng Ban CH phòng thủ Khu vực 1 - Bến Lức | 0982 452 662 | 069 975 460 |  |  |
| 33 | Hồ Thanh Lâm | Chính uỷ Ban Chỉ huy phòng thủ Khu vực 1 - Bến Lức | 0973 623 823 | 069 975 461 |  |  |
| 34 | Nguyễn Thành Cao | Chỉ huy TB Chỉ huy phòng thủ Khu vực 2 - Gò Dầu | 0397 084 635 | 069 979 640 |  |  |
| 35 | Nguyễn Văn Tiên | Chính uỷ Ban Chỉ huy phòng thủ Khu vực 2 - Gò Dầu | 0395 350 775 | 069 979 641 |  |  |
| 36 | Võ Văn Thọ | Chỉ huy TB Chỉ huy phòng thủ Khu vực 3 - Tân Ninh | 0968 071 004 | 069 646 101 |  |  |
| 37 | Trần Văn Toàn | Chính uỷ Ban Chỉ huy phòng thủ Khu vực 3 - Tân Ninh | 0901 282 499 | 069 646 102 |  |  |
| 38 | Nguyễn Thành Lâm | Chỉ huy TB Chỉ huy phòng thủ Khu vực 4 - Tân Thạnh | 0962 745 738 | 069 979 601 |  |  |
| 39 | Lê Chánh Tín | Chính uỷ Ban Chỉ huy phòng thủ Khu vực 4 - Tân Thạnh | 0908 450 007 | 069 979 602 |  |  |
| 40 | Dương Văn Dược | Chính uỷ Ban Chỉ huy Bộ đội Biên phòng | 0909 117 339 | 069 646 502 |  |  |
| 41 | Ngô Thạch Thất | Trung đoàn trưởng Trung đoàn bộ binh 738 | 0977 644 779 | 069 976 100 |  |  |
| 42 | Nguyễn Vũ Linh | Chính uỷ Trung đoàn bộ binh 738 | 0986 747 228 | 069 976 101 |  |  |
| 43 | Đoàn Thế Bảo | Trung đoàn trưởng Trung đoàn bộ binh 174 | 0914 096762 | 069 976 130 |  |  |
| 44 | Vũ Trường Trung | Chính uỷ Trung đoàn bộ binh 174 | 0909 927947 | 069 976 131 |  |  |

### BCH Bộ đội Biên phòng tỉnh / Đ/c: 395 CMT8, phường Tân Ninh, tỉnh Tây Ninh

- Nhóm: 1
- Mã/STT nhóm: 3

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 1 | Đàm Quang Ngoạt | Chỉ huy trưởng | 0967 636 983 | 02763 818 055 |  |  |
| 2 | Dương Văn Dược | Chính ủy | 0909 117 339 | 02673 814 878 |  |  |
| 3 | Phạm Văn Cờ | Phó CHT-TMT | 0989 258 877 | 02763 814 877 |  |  |
| 4 | Lê Trọng Tình | Phó CHT-TMT | 0985 358 228 |  |  |  |
| 5 | Nguyễn Đình Mạnh | Phó CHT | 0982 734 566 | 02763 814 876 |  |  |
| 6 | Cao Xuân An | Phó CHT NV | 0967 435 858 | 02763 814 879 |  |  |
| 7 | Trương Thùy Dương | Phó CHT NV | 0977 773 759 |  |  |  |
| 8 | Nguyễn Ngọc Dung | Phó Chính ủy | 0979 364 824 | 02763 628 008 |  |  |
| 9 | Vũ Minh Tùng | Phó Chính ủy | 0919 170 809 | 02763 818 507 |  |  |
| 10 | Trương Thanh Bình | Phó Tham mưu trưởng | 0382 519 999 |  |  |  |
| 11 | Lê Thanh Cần | Phó Tham mưu trưởng | 0919 618 818 |  |  |  |
| 12 | Nguyễn Văn Giào | Phó Tham mưu trưởng | 0376 327 979 |  |  |  |
| 13 | Nguyễn Ngọc Sơn | Phó Tham mưu trưởng | 0975 467 700 | 0276 3814 880 |  |  |
| 14 | Nguyễn Văn Hội | Phó Tham mưu trưởng | 0918 121 999 |  |  |  |
| 15 | Phạm Thanh Thuận | Phó Tham mưu trưởng | 0972 622 998 |  |  |  |
| 16 | Lê Trung Hiếu | Phó Tham mưu trưởng | 0917 731 869 |  |  |  |
| 17 | Đồng Như Hải | Phó Tham mưu trưởng | 0918 439 748 |  |  |  |
| 18 | Nguyễn Công Tuân | Chủ nhiệm Chính trị | 0913 142 636 | 0276 3828 773 |  |  |
| 19 | Phạm Văn Tú | Phó Chủ nhiệm Chính trị | 0962 130 123 |  |  |  |
| 20 | Lê Thành Nam | Phó Chủ nhiệm Chính trị | 0973 232 852 |  |  |  |
| 21 | Đào Đình Luyện | Phó Chủ nhiệm Chính trị | 0968 139 090 |  |  |  |
| 22 | Võ Thanh Tùng | Phó Chủ nhiệm Chính trị | 0912 314 823 |  |  |  |
| 23 | Lê Văn Hoàng | Phó Chủ nhiệm Chính trị | 0982 077 611 | 0276 3814 881 |  |  |
| 24 | Hoàng Văn Dũng | Phó Chủ nhiệm UBKT | 0914 007 034 |  |  |  |
| 25 | Trương Công Số | Trưởng phòng Nghiệp vụ | 0975 072 288 | 0276 3815 778 |  |  |
| 26 | Nguyễn Công Thiết | Phó phòng Nghiệp vụ | 0888 857 868 |  |  |  |
| 27 | Nguyễn Minh Trí | Phó phòng Nghiệp vụ | 0963 288 884 |  |  |  |
| 28 | Lể Văn Đàm | Phó phòng Nghiệp vụ | 0986 926 131 |  |  |  |
| 29 | Nguyễn Ngọc Thoản | Phó phòng Nghiệp vụ | 0984 157 022 |  |  |  |
| 30 | Mai Hồng Thanh | Phó phòng Nghiệp vụ | 0965 451 166 |  |  |  |
| 31 | Nguyễn Văn Hiếu | Phó phòng Nghiệp vụ | 0945 674 765 |  |  |  |
| 32 | Nguyễn Trọng Thắng | Phó phòng Nghiệp vụ | 0588 866 899 |  |  |  |
| 33 | Lê Huy Bình | Phó phòng Nghiệp vụ | 0948 653 509 |  |  |  |
| 34 | Phan Thanh Tùng | Trưởng phòng HC - KT | 0972 496 404 |  |  |  |
| 35 | Đinh Văn Nam | Phó phòng HC - KT | 0974 543 700 |  |  |  |
| 36 | Nguyễn Văn Giáp | Phó phòng HC - KT | 0982 558 691 |  |  |  |
| 37 | Đỗ Văn Đoàn | Phó phòng HC - KT | 0988 592 426 |  |  |  |
| 38 | Phạm Đức Tuấn | Phó phòng HC - KT | 0986 289 542 |  |  |  |
| 39 | Nguyễn Khánh Ngọc | Trưởng ban Tài chính | 0918 065 579 | 0276 3818 606 |  |  |
| 40 | Nguyễn Tấn Đạt | Đồn trưởng | 0989 880 885 | 0276 3739815 | Đồn Biên phòng Tống Lê Chân |  |
| 41 | Vũ Văn Tới | Chính trị viên | 0984 898 958 |  | Đồn Biên phòng Tống Lê Chân |  |
| 42 | Tạ Quang Ninh | Phó đồn trưởng Quân sự | 0978 100 066 |  | Đồn Biên phòng Tống Lê Chân |  |
| 43 | Phùng Văn Duy | Phó đồn trưởng Quân sự | 0963 653 555 |  | Đồn Biên phòng Tống Lê Chân |  |
| 44 | Phạm Xuân Toàn | Phó đồn trưởng Nghiệp vụ | 0974 796 046 |  | Đồn Biên phòng Tống Lê Chân |  |
| 45 | Trần Văn Ngưu | Đồn trưởng | 0983 058 757 | 0276 3510817 | Đồn Biên phòng Suối Lam |  |
| 46 | Dương Mạnh Hùng | Chính trị viên | 0963 848 505 |  | Đồn Biên phòng Suối Lam |  |
| 47 | Bùi Thế Hợp | Phó đồn trưởng Quân sự | 0987 422 567 |  | Đồn Biên phòng Suối Lam |  |
| 48 | Trần Lê Nhật Bình | Phó đồn trưởng Nghiệp vụ | 0979 261 515 |  | Đồn Biên phòng Suối Lam |  |
| 49 | Trương Văn Phương | Phó đồn trưởng Nghiệp vụ | 0868 707 750 |  | Đồn Biên phòng Suối Lam |  |
| 50 | Nguyễn Văn Hà | Chính trị viên phó | 0866 635 661 |  | Đồn Biên phòng Suối Lam |  |
| 51 | Phạm Minh Phượng | Đồn trưởng | 0988 987 099 | 0276 3751573 | Đồn Biên phòng Kà Tum |  |
| 52 | Bùi Thế Công | Chính trị viên | 0977 189 266 |  | Đồn Biên phòng Kà Tum |  |
| 53 | Nguyễn Đình Quang | Phó đồn trưởng Quân sự | 0973 266 622 |  | Đồn Biên phòng Kà Tum |  |
| 54 | Bùi Quang Thành | Phó đồn trưởng Nghiệp vụ | 0988 307 307 |  | Đồn Biên phòng Kà Tum |  |
| 55 | Nguyễn Văn Hào | Chính trị viên phó | 0967 004 676 |  | Đồn Biên phòng Kà Tum |  |
| 56 | Dương Quốc Trạng | Đồn trưởng | 0985 662 212 | 0276 3738430 | Đồn Biên phòng Tân Hà |  |
| 57 | Lê Tấn Bạc | Chính trị viên | 0858 150 252 |  | Đồn Biên phòng Tân Hà |  |
| 58 | Phan Văn Nghiêm | Phó đồn trưởng Quân sự | 0353 280 988 |  | Đồn Biên phòng Tân Hà |  |
| 59 | Võ Văn Hoài | Phó đồn trưởng Quân sự | 0961 747 794 |  | Đồn Biên phòng Tân Hà |  |
| 60 | Vũ Khắc Út | Phó đồn trưởng Nghiệp vụ | 0966 590 682 |  | Đồn Biên phòng Tân Hà |  |
| 61 | Hồ Ngọc Sơn | Chính trị viên phó | 0979 225 999 |  | Đồn Biên phòng Tân Hà |  |
| 62 | Vũ Văn Minh | Đồn trưởng | 0989 178 551 | 0276 3778823 | Đồn BPCK Chàng Riệc |  |
| 63 | Phan Đình Tố | Chính trị viên | 0987 228 585 |  | Đồn BPCK Chàng Riệc |  |
| 64 | Trần Văn Pha | Phó đồn trưởng Quân sự | 0962 054 307 |  | Đồn BPCK Chàng Riệc |  |
| 65 | Nguyễn Quốc Thành | Phó đồn trưởng Quân sự | 0979 955 757 |  | Đồn BPCK Chàng Riệc |  |
| 66 | Nguyễn Minh Trí | Phó đồn trưởng Nghiệp vụ | 0949 619 916 |  | Đồn BPCK Chàng Riệc |  |
| 67 | Phạm Đức Tùng | Chính trị viên phó | 0965 020190 |  | Đồn BPCK Chàng Riệc |  |
| 68 | Nguyễn Đức Tây | Chính trị viên phó | 0382 550 707 |  | Đồn BPCK Chàng Riệc |  |
| 69 | Vũ Xuân Huy | Đồn trưởng | 0962 905 257 | 0276 3872367 | Đồn BP CKQT Xa Mát |  |
| 70 | Phạm Văn Xá | Chính trị viên | 0967 691 357 |  | Đồn BP CKQT Xa Mát |  |
| 71 | Phan Minh Vương | Phó đồn trưởng Nghiệp vụ | 0983 864 532 |  | Đồn BP CKQT Xa Mát |  |
| 72 | Huỳnh Tấn Thuần | Chính trị viên phó | 0965 569 598 |  | Đồn BP CKQT Xa Mát |  |
| 73 | Nguyễn Văn Thì | Phó đồn trưởng Quân sự | 0973 055 570 |  | Đồn BP CKQT Xa Mát |  |
| 74 | Nguyễn Việt Anh | Phó đồn trưởng Quân sự | 0909 225 568 |  | Đồn BP CKQT Xa Mát |  |
| 75 | Trần Văn Bồi | Đồn trưởng | 0969 000 055 | 0276 3818831 | Đồn BP Tân Phú |  |
| 76 | Nguyễn Văn Thắng | Chính trị viên | 0984 470 088 |  | Đồn BP Tân Phú |  |
| 77 | Huỳnh Anh Phúc | Phó đồn trưởng Quân sự | 0978 017 081 |  | Đồn BP Tân Phú |  |
| 78 | Trương Đức Hạnh | Phó đồn trưởng Nghiệp vụ | 0983 732 575 |  | Đồn BP Tân Phú |  |
| 79 | Đặng Văn Trí | Phó đồn trưởng Nghiệp vụ | 0963 288 889 |  | Đồn BP Tân Phú |  |
| 80 | Phạm Đại Dương | Chính trị viên phó | 0984 719 988 |  | Đồn BP Tân Phú |  |
| 81 | Hoàng Văn Mạnh | Đồn trưởng | 0981 890 686 | 02763 718 833 | Đồn BP CKQT Tân Nam |  |
| 82 | Trương Thanh Đẳng | Chính trị viên | 0985 672 293 |  | Đồn BP CKQT Tân Nam |  |
| 83 | Trịnh Quốc Giao | Phó đồn trưởng Quân sự | 0964 545 656 |  | Đồn BP CKQT Tân Nam |  |
| 84 | Trần Văn Quyết | Phó đồn trưởng Quân sự | 0985 585 223 |  | Đồn BP CKQT Tân Nam |  |
| 85 | Mai Văn Đến | Phó đồn trưởng Nghiệp vụ | 0945 262 653 |  | Đồn BP CKQT Tân Nam |  |
| 86 | Trương Công Đức | Chính trị viên phó | 0985 686 885 |  | Đồn BP CKQT Tân Nam |  |
| 87 | Nguyễn Hoài Phong | Đồn trưởng | 0943 684 141 | 0276 3871956 | Đồn BP Lò Gò |  |
| 88 | Nguyễn Văn Vương | Chính trị viên | 0968 763 399 |  | Đồn BP Lò Gò |  |
| 89 | Nguyễn Viết Đức | Phó đồn trưởng Quân sự | 0981 251 189 |  | Đồn BP Lò Gò |  |
| 90 | Nguyễn Minh Đức | Phó đồn trưởng Quân sự | 0983 000 599 |  | Đồn BP Lò Gò |  |
| 91 | Nguyễn Huy Cường | Phó đồn trưởng Nghiệp vụ | 0982 819 303 |  | Đồn BP Lò Gò |  |
| 92 | Hoàng Anh Dũng | Chính trị viên phó | 0865 956 991 |  | Đồn BP Lò Gò |  |
| 93 | Phạm Đình Thắng | Đồn trưởng | 0967 158 889 | 0276 3878344 | Đồn BP Vàm Trảng Trâu |  |
| 94 | Hoàng Như Nam | Chính trị viên | 0986 182 952 |  | Đồn BP Vàm Trảng Trâu |  |
| 95 | Huỳnh Minh Bảo | Phó đồn trưởng Quân sự | 0982 529 352 |  | Đồn BP Vàm Trảng Trâu |  |
| 96 | Nguyễn Minh Tuấn | Phó đồn trưởng Quân sự | 0973 232 668 |  | Đồn BP Vàm Trảng Trâu |  |
| 97 | Đinh Quang Lực | Phó đồn trưởng Nghiệp vụ | 0985 593 594 |  | Đồn BP Vàm Trảng Trâu |  |
| 98 | Nguyễn Văn Quyền | Chính trị viên phó | 0377 690 992 |  | Đồn BP Vàm Trảng Trâu |  |
| 99 | Võ Hoài Thanh | Đồn trưởng | 0983 197 017 | 0276 3783125 | Đồn BPCK Phước Tân |  |
| 100 | Triệu Ngọc Am | Chính trị viên | 0977 757 707 |  | Đồn BPCK Phước Tân |  |
| 101 | Vũ Hồng Tuấn | Phó đồn trưởng Quân sự | 0968 755 499 |  | Đồn BPCK Phước Tân |  |
| 102 | Trần Văn Lơ | Phó đồn trưởng Quân sự | 0348 857 773 |  | Đồn BPCK Phước Tân |  |
| 103 | Trần Hồng Quân | Phó đồn trưởng Nghiệp vụ | 0941 069 345 |  | Đồn BPCK Phước Tân |  |
| 104 | Nguyễn Trường An | Chính trị viên phó | 0979 202 037 |  | Đồn BPCK Phước Tân |  |
| 105 | Nguyễn Văn Khỏe | Chính trị viên phó | 0973 250 074 |  | Đồn BPCK Phước Tân |  |
| 106 | Trần Đức Dũng | Đồn trưởng | 0973 378 966 | 2763619845 | Đồn BP Ninh Điền |  |
| 107 | Nguyễn Trọng Nghĩa | Chính trị viên | 0359 569 452 |  | Đồn BP Ninh Điền |  |
| 108 | Trương Khánh Hùng | Phó đồn trưởng Quân sự | 0974 056 164 |  | Đồn BP Ninh Điền |  |
| 109 | Võ Văn Thắng | Phó đồn trưởng Quân sự | 0973 789 117 |  | Đồn BP Ninh Điền |  |
| 110 | Trần Trọng Hữu | Phó đồn trưởng Nghiệp vụ | 0944 743 999 |  | Đồn BP Ninh Điền |  |
| 111 | Lê Tuấn Anh | Chính trị viên phó | 0338 627 668 |  | Đồn BP Ninh Điền |  |
| 112 | Trần Văn Thành | Đồn trưởng | 0387 224 139 | 0276 3876580 | Đồn BP Long Phước |  |
| 113 | Nguyễn Văn Hảo | Chính trị viên | 0984 933 660 |  | Đồn BP Long Phước |  |
| 114 | Nguyễn Thanh Tuấn | Phó đồn trưởng Quân sự | 0979 111 107 |  | Đồn BP Long Phước |  |
| 115 | Nguyễn Thanh Tùng | Phó đồn trưởng Nghiệp vụ | 0983 705 605 |  | Đồn BP Long Phước |  |
| 116 | Dương Trọng Toàn | Phó đồn trưởng Nghiệp vụ | 0382 320 840 |  | Đồn BP Long Phước |  |
| 117 | Nguyễn Trọng Nghĩa | Chính trị viên phó | 0359 018 814 |  | Đồn BP Long Phước |  |
| 118 | Vi Trung Kiên | Đồn trưởng | 0983 750 069 | 0276 3876181 | Đồn BP CKQT Mộc Bài |  |
| 119 | Phạm Văn Hoàn | Chính trị viên | 0968 921 968 |  | Đồn BP CKQT Mộc Bài |  |
| 120 | Nguyễn Khánh Hoàng | Phó đồn trưởng Nghiệp vụ | 0966 847 719 |  | Đồn BP CKQT Mộc Bài |  |
| 121 | Trương Thanh Vũ | Chính trị viên phó | 0971 523 624 |  | Đồn BP CKQT Mộc Bài |  |
| 122 | Ngô Xuân Kiên | Phó đồn trưởng Quân sự | 0961 531 688 |  | Đồn BP CKQT Mộc Bài |  |
| 123 | Nguyễn Văn Hùng | Phó đồn trưởng Quân sự | 0868 077 785 |  | Đồn BP CKQT Mộc Bài |  |
| 124 | Nguyễn Tấn Tiên | Đồn trưởng | 0345 678 991 | 0276 3889146 | Đồn BP Phước Chỉ |  |
| 125 | Mai Văn Hòa | Chính trị viên | 0985 708 789 |  | Đồn BP Phước Chỉ |  |
| 126 | Nguyễn Văn Tuấn | Phó đồn trưởng Quân sự | 0966 666 122 |  | Đồn BP Phước Chỉ |  |
| 127 | Lương Hữu Hợp | Phó đồn trưởng Quân sự | 0979 167 307 |  | Đồn BP Phước Chỉ |  |
| 128 | Phạm Bá Huy | Phó đồn trưởng Nghiệp vụ | 0964 548 181 |  | Đồn BP Phước Chỉ |  |
| 129 | Nguyễn Văn Hậu | Chính trị viên phó | 0972 480 555 |  | Đồn BP Phước Chỉ |  |
| 130 | Trần Bá Trình | Tiểu đoàn trưởng | 0974 300 585 | 0276 3753819 | Tiểu đoàn HL-CĐ (TN cũ) |  |
| 131 | Nguyễn Văn Sỹ | Chính trị viên | 0972 183 325 |  | Tiểu đoàn HL-CĐ (TN cũ) |  |
| 132 | Lê Hoàng Mới | Phó Tiểu đoàn trưởng | 0969 248 787 |  | Tiểu đoàn HL-CĐ (TN cũ) |  |
| 133 | Phạm Hoàng Hợp | Tiểu đoàn trưởng | 0336 215 082 | 0272 3841 930 | Tiểu đoàn HL-CĐ (LA cũ) |  |
| 134 | Lê Văn Huỳnh | Chính trị viên | 0981 810 866 |  | Tiểu đoàn HL-CĐ (LA cũ) |  |
| 135 | Trần Quốc Tuấn | Phó Tiểu đoàn trưởng | 0346 100 001 |  | Tiểu đoàn HL-CĐ (LA cũ) |  |
| 136 | Trần Long An | Chính trị viên phó | 0969 201 212 |  | Tiểu đoàn HL-CĐ (LA cũ) |  |
| 137 | Phạm Thành Trung | Đồn trưởng | 0852 166 668 | 0272 3856 015 | Đồn BPCK Mỹ Quý Tây |  |
| 138 | Nguyễn Minh Lợi | Chính trị viên | 0979 059 185 |  | Đồn BPCK Mỹ Quý Tây |  |
| 139 | Trần Bình Nam | Phó đồn trưởng Quân sự | 0965 136 565 |  | Đồn BPCK Mỹ Quý Tây |  |
| 140 | Võ Hoàng Minh | Phó đồn trưởng Quân sự | 0946 607 473 |  | Đồn BPCK Mỹ Quý Tây |  |
| 141 | Trần Ngọc Dương | Phó đồn trưởng Nghiệp vụ | 0986 322 332 |  | Đồn BPCK Mỹ Quý Tây |  |
| 142 | Phạm Việt Tiến | Chính trị viên phó | 0399 964 213 |  | Đồn BPCK Mỹ Quý Tây |  |
| 143 | Phạm Bình Khuê | Chính trị viên phó | 0964 868 899 |  | Đồn BPCK Mỹ Quý Tây |  |
| 144 | Lê Anh Tuấn | Đồn trưởng | 0969 310 808 | 0272 3786 028 | Đồn BP Mỹ Thạnh Tây |  |
| 145 | Nguyễn Văn Nam | Chính trị viên | 0963 196 677 |  | Đồn BP Mỹ Thạnh Tây |  |
| 146 | Nguyễn Văn Hóa | Phó đồn trưởng Quân sự | 0976 105 555 |  | Đồn BP Mỹ Thạnh Tây |  |
| 147 | Nguyễn Hữu Nhật | Phó đồn trưởng Quân sự | 0968 428 470 |  | Đồn BP Mỹ Thạnh Tây |  |
| 148 | Phạm Minh Khánh | Phó đồn trưởng Nghiệp vụ | 0346 099 777 |  | Đồn BP Mỹ Thạnh Tây |  |
| 149 | Trương Đông Phi | Chính trị viên phó | 0396 627 827 |  | Đồn BP Mỹ Thạnh Tây |  |
| 150 | Trần Văn Bì | Đồn trưởng | 0918 417 007 | 0272 3919 969 | Đồn BP Thuận Bình |  |
| 151 | Mai Thành Dững | Chính trị viên | 0912 129 325 |  | Đồn BP Thuận Bình |  |
| 152 | Đặng Văn Nhu | Phó đồn trưởng Quân sự | 0968 174 466 |  | Đồn BP Thuận Bình |  |
| 153 | Phạm Minh Chào | Phó đồn trưởng Quân sự | 0973 131 416 |  | Đồn BP Thuận Bình |  |
| 154 | Trần Văn Chung | Phó đồn trưởng Nghiệp vụ | 0974 546 556 |  | Đồn BP Thuận Bình |  |
| 155 | Nguyễn Thiết Tân | Chính trị viên phó | 0393 924 692 |  | Đồn BP Thuận Bình |  |
| 156 | Nguyễn Trường Giang | Đồn trưởng | 0966 773 131 | 0272 3840 875 | Đồn BP Bình Thạnh |  |
| 157 | Nguyễn Hữu Trí | Chính trị viên | 0908 899 203 |  | Đồn BP Bình Thạnh |  |
| 158 | Nguyễn Văn Cẩm | Phó đồn trưởng Quân sự | 0944 209 996 |  | Đồn BP Bình Thạnh |  |
| 159 | Phan Thanh Quyền | Phó đồn trưởng Quân sự | 0983 400 692 |  | Đồn BP Bình Thạnh |  |
| 160 | Trần Lâm Vũ | Phó đồn trưởng Nghiệp vụ | 0372 063 076 |  | Đồn BP Bình Thạnh |  |
| 161 | Trần Ngọc Hải | Chính trị viên phó | 0982 783 131 |  | Đồn BP Bình Thạnh |  |
| 162 | Nguyễn Văn Nghĩa | Đồn trưởng | 0948 735 176 | 0272 3841 729 | Đồn BP Thạnh Trị |  |
| 163 | Lê Trung Sơn | Chính trị viên | 0944 334 377 |  | Đồn BP Thạnh Trị |  |
| 164 | Lê Quốc Dũng | Phó đồn trưởng Quân sự | 0984 144 567 |  | Đồn BP Thạnh Trị |  |
| 165 | Phan Đình Huy | Phó đồn trưởng Quân sự | 0977 978 166 |  | Đồn BP Thạnh Trị |  |
| 166 | Hà Minh Hải | Phó đồn trưởng Nghiệp vụ | 0969 496 677 |  | Đồn BP Thạnh Trị |  |
| 167 | Nguyễn Hồng Thân | Chính trị viên phó | 0988 272 718 |  | Đồn BP Thạnh Trị |  |
| 168 | Nguyễn Văn Tiền | Đồn trưởng | 0814 421 116 | 0272 3951 317 | Đồn BP CKQT Bình Hiệp |  |
| 169 | Phạm Khắc Thụ | Chính trị viên | 0974 632 468 |  | Đồn BP CKQT Bình Hiệp |  |
| 170 | Dương Minh Tiến | Phó đồn trưởng Quân sự | 0383 528 573 |  | Đồn BP CKQT Bình Hiệp |  |
| 171 | Lê Thành Danh | Phó đồn trưởng Nghiệp vụ | 0968 280 088 |  | Đồn BP CKQT Bình Hiệp |  |
| 172 | Vi Đình Hạnh | Phó đồn trưởng Nghiệp vụ | 0855 553 260 |  | Đồn BP CKQT Bình Hiệp |  |
| 173 | Trần Văn Tú | Chính trị viên phó | 0365 851 807 |  | Đồn BP CKQT Bình Hiệp |  |
| 174 | Nguyễn Văn Hải | Đồn trưởng | 0986 744 169 | 0272 3847079 | Đồn BP Tuyên Bình |  |
| 175 | Vũ Mạnh Hà | Chính trị viên | 0983 279 216 |  | Đồn BP Tuyên Bình |  |
| 176 | Lê Viễn Khắc | Phó đồn trưởng Quân sự | 0989 628 629 |  | Đồn BP Tuyên Bình |  |
| 177 | Nguyễn Thái Thuận | Phó đồn trưởng Quân sự | 0824 860 981 |  | Đồn BP Tuyên Bình |  |
| 178 | Lại Vũ Đức Thành | Phó đồn trưởng Nghiệp vụ | 0919 807 185 |  | Đồn BP Tuyên Bình |  |
| 179 | Phùng Quang Tính | Đồn trưởng | 0352 655 535 | 0272 3973 075 | Đồn BP Long Khốt |  |
| 180 | Đỗ Văn Long | Chính trị viên | 0982 095 989 |  | Đồn BP Long Khốt |  |
| 181 | Nguyễn Văn Giáp | Phó đồn trưởng Quân sự | 0986 814 729 |  | Đồn BP Long Khốt |  |
| 182 | Lê Đình Thơ | Phó đồn trưởng Quân sự | 0979 051 191 |  | Đồn BP Long Khốt |  |
| 183 | Huỳnh Tấn Triêm | Phó đồn trưởng Nghiệp vụ | 0973 044 949 |  | Đồn BP Long Khốt |  |
| 184 | Nguyễn Văn Thế | Chính trị viên phó | 0978 957 836 |  | Đồn BP Long Khốt |  |
| 185 | Trần Văn Quân | Đồn trưởng | 0969 081 983 | 0272 3979 078 | Đồn BP Bến Phố |  |
| 186 | Đậu Hồng Lam | Chính trị viên | 0919 684 977 |  | Đồn BP Bến Phố |  |
| 187 | Hà Văn Khải | Phó đồn trưởng Quân sự | 0947 952 828 |  | Đồn BP Bến Phố |  |
| 188 | Nguyễn Huy Dũng | Phó đồn trưởng Nghiệp vụ | 0976 918 456 |  | Đồn BP Bến Phố |  |
| 189 | Phạm Văn Nhân | Phó đồn trưởng Nghiệp vụ | 0963 613 737 |  | Đồn BP Bến Phố |  |
| 190 | Lê Văn Hoàn | Chính trị viên phó | 0337 986 272 |  | Đồn BP Bến Phố |  |
| 191 | Phạm Văn Toàn | Đồn trưởng | 0974 333 835 | 0272 3860 919 | Đồn BP Sông Trăng |  |
| 192 | Bùi Ngọc Thiệp | Chính trị viên | 0975 488 025 |  | Đồn BP Sông Trăng |  |
| 193 | Dương Văn Quới | Phó đồn trưởng Quân sự | 0849 813 200 |  | Đồn BP Sông Trăng |  |
| 194 | Đoàn Minh Hiếu | Phó đồn trưởng Quân sự | 0989 767 781 |  | Đồn BP Sông Trăng |  |
| 195 | Nguyễn Hùng Cường | Phó đồn trưởng Nghiệp vụ | 0962 613 535 |  | Đồn BP Sông Trăng |  |
| 196 | Nguyễn Đình Thông | Chính trị viên phó | 0855 676 194 |  | Đồn BP Sông Trăng |  |
| 197 | Hoàng Minh Bảo | Đồn trưởng | 0968 086 656 | 0272 3638 311 | Đồn BP CKC Bến Lức |  |
| 198 | Vũ Văn Hải | Chính trị viên | 0914 035 760 |  | Đồn BP CKC Bến Lức |  |
| 199 | Trần Việt Hoàn | Phó đồn trưởng Quân sự | 0962 928 779 |  | Đồn BP CKC Bến Lức |  |
| 200 | Lê Ngự Bình | Phó đồn trưởng Nghiệp vụ | 0333 999 393 |  | Đồn BP CKC Bến Lức |  |
| 201 | Trần Quang Hưng | Phó đồn trưởng Nghiệp vụ | 0981 648 678 |  | Đồn BP CKC Bến Lức |  |

### Thuế tỉnh Tây Ninh / Địa chi: Số 10, Quốc lộ 1, phường Long An, tỉnh Tây Ninh

- Nhóm: 1
- Mã/STT nhóm: 4

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 1 | Nguyễn Nam Bình | Trưởng Thuế tỉnh | (0272) 3681638 | 0903 738 712 |  |  |
| 2 | Nguyễn Ngọc Minh Sang | Phó Trưởng Thuế tỉnh | (0272) 3665579 | 0918 589 477 |  |  |
| 3 | Trần Thị Thu Vân | Phó Trưởng Thuế tỉnh | (0272) 3823618 | 0917 373 797 |  |  |
| 4 | Trần Chí Cường | Phó Trưởng Thuế tỉnh | (0272) 3823619 | 0908 457 386 |  |  |
| 5 | Nguyễn Tấn Lợi | Phó Trưởng Thuế tỉnh | (0272) 3985639 | 0974 858 558 |  |  |
| 6 | Nguyễn Thị Sang | Phó Trưởng Thuế tỉnh |  | 0902 440 506 |  |  |

#### Văn phòng

- Di động: (0272) 3939180

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 7 | Nguyễn Mạnh Hùng | Chánh Văn phòng | (0272) 3823662 | 0913 180 009 |  |  |
| 8 | Trần Thụy Ngọc Hân | Phó Chánh Văn phòng | (0272) 3823662 | 0909 932 240 |  |  |
| 9 | Ngô Kim Bạch Phi Hổ | Phó Chánh Văn phòng | (0272) 3828797 | 0839 066 606 |  |  |
| 10 | Nguyễn Như Trang | Văn thư đi | (0272) 3839180 | 0387 143 128 |  |  |
| 11 | Đinh Thị Thùy Quyên | Văn thư đến | (0272) 3839180 | 0352 872 600 |  |  |
| 12 | Phòng Tổ chức cán bộ |  | (0272) 3823661 |  |  |  |
| 13 | Võ Văn Cường | Phó Trưởng phòng - PT | (0272) 3552601 | 0918 499 092 |  |  |
| 14 | Lê Thị Nga | Phó Trưởng phòng | (0272) 3823661 | 0948 940 889 |  |  |
| 15 | Nguyễn Hồng Phong | Phó Trưởng phòng | (0272) 3823661 | 0913 797 939 |  |  |

#### Phòng Nghiệp vụ, dự toán pháp chế

- Di động: (0272) 3826389

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 16 | Phạm Văn Hồng | Trưởng phòng | (0272) 3989019 | 0913 955 488 |  |  |
| 17 | Nguyễn Thị Phương Kiều | Phó Trưởng Phòng | (0272) 3826286 | 0946 133 967 |  |  |
| 18 | Nguyễn Thanh Ý | Phó Trưởng phòng | (0272) 3829146 | 0919 718 879 |  |  |
| 19 | Kiều Công Danh | Phó Trưởng phòng | (0272) 3826286 | 0919 820 870 |  |  |
| 20 | Lê Tấn Lộc | Phó Trưởng phòng | (0272) 3826389 | 0919 124 425 |  |  |
| 21 | Trần Thị Kim Oanh | Phó Trưởng phòng | (0272) 3826389 | 0917 265 727 |  |  |
| 22 | Phòng Thuế cá nhân, hộ kinh doanh và thu khác |  | (0272) 3839235 |  |  |  |
| 23 | Ngô Phước Nam | Trưởng phòng | (0272) 3839235 | 0937 252 020 |  |  |
| 24 | Nguyễn Thị Minh Hương | Phó Trưởng phòng | (0272) 3839210 | 0908 027 898 |  |  |
| 25 | Nguyễn Văn Quanh | Phó Trưởng phòng | (0272) 3837900 | 0909 395 659 |  |  |
| 26 | Hoàng Văn Hoàn | Phó Trưởng phòng | (0272) 3823620 | 0989 934 424 |  |  |

#### Phòng Quản trị dữ liệu và Quản lý rủi ro

- Di động: (0272) 3822873

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 27 | Huỳnh Thanh Dẫn | Trưởng phòng |  | 0916 107 155 |  |  |
| 28 | Võ Thanh Tiến | Phó Trưởng phòng | (0272) 3834150 | 0937 855 418 |  |  |

#### Phòng Quản lý, hỗ trợ doanh nghiệp số 1

- Di động: (0272) 3826196

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 29 | Mao Huỳnh Đức | Trưởng phòng | (0272) 3826042 | 0918 129 029 |  |  |
| 30 | Nguyễn Tấn Cường | Phó Trưởng phòng | (0272) 3826196 | 0915 440 939 |  |  |
| 31 | Võ Thị Hải Yến | Phó Trưởng phòng | (0272) 3571828 | 0984 437 837 |  |  |
| 32 | Lương Ngọc Trinh | Phó Trưởng phòng | (0272) 3825571 | 0919 289 337 |  |  |

#### Phòng Quản lý, hỗ trợ doanh nghiệp số 2

- Di động: (0272) 3837809

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 33 | Võ Văn Út | Trưởng phòng |  | 0775 707 812 |  |  |
| 34 | Phạm Thị Bạch Huệ | Phó Trưởng phòng | (0272) 3837809 | 0799 623272 |  |  |
| 35 | Nguyễn Thanh Toán | Phó Trưởng phòng |  | 0918 127 635 |  |  |
| 36 | Nguyễn Thị Thanh Vân | Phó Trưởng phòng | (0272) 3551803 | 0949 395 438 |  |  |

#### Phòng Quản lý, hỗ trợ doanh nghiệp số 3

- Di động: (0272) 3985637

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 37 | Đặng Mỹ Linh | Phó Trưởng phòng - PT | (0272) 3985637 | 0918 743 536 |  |  |
| 38 | Trịnh Bá Nhị | Phó Trưởng phòng | (0272) 3823617 | 0902 579 500 |  |  |
| 39 | Nguyễn Văn Mậu | Phó Trưởng phòng | (0272) 3823617 | 0984952956 |  |  |

#### Phòng Kiểm tra số 1

- Di động: (0272) 3823620

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 40 | Võ Văn Lộc | Trưởng phòng | (0272) 3823620 | 0909 654 116 |  |  |
| 41 | Nguyễn Văn Bé | Phó Trưởng phòng | (0272) 3823620 | 0918 955 471 |  |  |
| 42 | Võ Thị Kim Liên | Phó Trưởng phòng | (0272) 3823620 | 0917 641 357 |  |  |
| 43 | La Thị Hải Hà | Phó Trưởng phòng | (0272) 3823620 | 0968 498 369 |  |  |
| 44 | Vương Thế Minh | Phó Trưởng phòng |  | 0909 665 515 |  |  |

#### Phòng Kiểm tra số 2

- Di động: (0272) 3839618

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 45 | Trương Ngọc Trần Huy | Trưởng phòng | (0272) 3839618 | 0944 240 919 |  |  |
| 46 | Nguyễn Hữu Tình | Phó Trưởng phòng | (0272) 3839618 | 0901 623 638 |  |  |
| 47 | Nguyễn Văn Thiệp | Phó Trưởng phòng | (0272) 3839618 | 0968 814 333 |  |  |
| 48 | Hồ Ngọc Hậu | Phó Trưởng phòng | (0272) 3839618 | 0917 676 999 |  |  |
| 49 | Nguyễn Thị Hoàng Nam | Phó Trưởng phòng | (0272) 3839618 | 0937 188 918 |  |  |

### Chi cục Hải quan khu vực XVII / ĐT (02723).829601/826449/823690, email: kv17@customs.gov.vn, website: https://kv17.customs.gov.vn

- Nhóm: 1
- Mã/STT nhóm: 5

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 1 | Nguyễn Trần Hiệu | Chi cục trưởng, Bí thư Đảng bộ | 0913 514 496 |  |  |  |
| 2 | Nguyễn Văn Bổng | Phó Chi cục trưởng | 0908 700 555 |  |  |  |
| 3 | Lê Nam Quốc | Phó Chi cục trưởng, Phó Bí thư | 0919 126 909 |  |  |  |
| 4 | Võ Thành Ngoạn | Phó Chi cục trưởng, Phó Bí thư | 0989 671 672 |  |  |  |
| 5 | Nguyễn Văn Khánh | Phó Chi cục trưởng | 0916 660 088 |  |  |  |
| 6 | Phan Văn Vũ | Phó Chi cục trưởng | 0772 999 009 |  |  |  |

### Thống kê tỉnh Tây Ninh / Đ/c: Số 30D, đường Sương Nguyệt Anh, phường Long An, tỉnh Tây Ninh / Điện thoại bàn: 02723 521 527; Email: tayninh@nso.gov.vn; Website: cucthongke.tayninh.gov.vn

- Nhóm: 1
- Mã/STT nhóm: 6

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 1 | Võ Thanh Sang | Trưởng Thống kê | 0903 003 645 | 02723 826 693 |  |  |
| 2 | Đào Văn Thi | Phó Trưởng Thống kê | 0913 167 534 | 02723 822 396 |  |  |
| 3 | Nguyễn Thị Kim Quyên | Phó Trưởng Thống kê | 0917 945 179 | 02723 820 916 |  |  |
| 4 | Nguyễn Thị Hạnh Nguyên | Quyền Trưởng phòng, Phòng TC-HC | 0383 877 314 | 02723 973 997 |  |  |
| 5 | Nguyễn Văn Công | PTP , Phòng TC-HC | 0911 037 137 | 02763 822 324 |  |  |
| 6 | Hoàng Thị Thu Hiền | Trưởng phòng, Phòng TK Cnghiệp & Xây dựng | 0386 777 590 | 02763 824 590 |  |  |
| 7 | Trần Thị Kim Phi | Trưởng phòng, Phòng TK Dịch vụ và Giá | 0976 424 310 | 02723 973 994 |  |  |
| 8 | Phạm Ngọc Thu Hằng | PTP , Phòng TK Dịch vụ và Giá | 0975 934 094 | 02723 826 694 |  |  |
| 9 | Võ Thanh Văn | Trưởng phòng, Phòng TK Nnghiệp và Xã hội | 0388 483 307 | 02763 826 103 |  |  |
| 10 | Tạ Quốc Doanh | PTP , Phòng TK Nnghiệp và Xã hội | 0983 976 801 | 02723 826 423 |  |  |
| 11 | Võ Trung Hiếu | PTP , Phòng TK Nnghiệp và Xã hội | 0388 115 593 | 02763 814 086 |  |  |
| 12 | Võ Hoài Phong | Trưởng phòng, Phòng TK Tổng hợp | 0912 468 440 | 02723 825 386 |  |  |

#### Thống kê cơ sở Long An, phường Long An tỉnh Tây Ninh; Điện thoại bàn: 02723 826 340. / Số 76 Hùng Vương, phường Long An, tỉnh Tây Ninh

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 1 | Trần Quang Tú | Trưởng Thống kê cơ sở | 0916 660 235 | 02723 826 340 |  |  |

#### Thống kê cơ sở Kiến Tường, phường Kiến Tường, tỉnh Tây Ninh; Điện thoại bàn 02723 841 577 / Số 41, đường Lê Lợi, khu phố 1, phường Kiến Tường, tỉnh Tây Ninh

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 1 | Nguyễn Văn Tâm | Trưởng Thống kê cơ sở | 0826 309 869 | 02723 841 577 |  |  |
| 2 | Võ Hữu Khánh | Phó Trưởng Thống kê cơ sở | 0973 792 611 |  |  |  |

#### Thống kê cơ sở Vĩnh Hưng, xã Vĩnh Hưng, tỉnh Tây Ninh; Điện thoại bàn 02723 847 414 / Số 70, đường 30-4, ấp Măng Đa, xã Vĩnh Hưng, Tỉnh Tây Ninh

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 1 | Trần Văn Đông | Trưởng Thống kê cơ sở | 0913 165 818 | 02723 861 096 |  |  |
| 2 | Trần Quang Học | Phó Trưởng Thống kê cơ sở | 0378 070 001 | 02723 847 414 |  |  |

#### Thống kê cơ sở Tân Thạnh, xã Tân Thạnh tỉnh Tây Ninh; Điện thoại bàn: 02723 844 040 / Số 04, đường Lê Văn Trầm, ấp 1, xã Tân Thạnh, tỉnh Tây Ninh

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 1 | Lê Minh Mến | Trưởng Thống kê cơ sở | 0919 346 446 | 02723 844 040 |  |  |
| 2 | Phùng Thanh Việt | Phó Trưởng Thống kê cơ sở | 0905 287 704 | 02723 857 118 |  |  |

#### Thống kê cơ sở Hậu Nghĩa, xã Hậu Nghĩa, tỉnh Tây Ninh; Điện thoại bàn: 02723 810 414 / Đường 29/4, Ô 7, Khu B, xã Hậu Nghĩa, tỉnh Tây Ninh

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 1 | Hồ Thị Sinh | Trưởng Thống kê cơ sở | 0826 567 167 | 02723 810 414 |  |  |

#### Thống kê cơ sở Tầm Vu, xã Tầm Vu, tỉnh Tây Ninh; Điện thoại bàn: 02723 877 238 / Ấp 3, xã Tầm Vu, tỉnh Tây Ninh

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 1 | Trần Thế Tri | Quyền Trưởng Thống kê cơ sở | 0845 888 678 | 02723 877 238 |  |  |

#### Thống kê cơ sở Bến Lức, xã Bến Lức, tỉnh Tây Ninh; Điện thoại bàn: 02723 871 591 / Số 211, QL1A, ấp Bến Lức 3, xã Bến Lức, tỉnh Tây Ninh

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 1 | Nguyễn Tuấn Linh | Trưởng Thống kê cơ sở | 0367 155 250 | 02723 871 591 |  |  |

#### Thống kê cơ sở Cần Đước, xã Cần Đước, tỉnh Tây Ninh; Điện thoại bàn: 02723 881 690 / Số 02, đường Trần Phú, ấp 1, xã Cần Đước, tỉnh Tây Ninh

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 1 | Nguyễn Đức Ngoan | Trưởng Thống kê cơ sở | 0919 682 283 | 02723 881 690 |  |  |

#### Thống kê cơ sở Cần Giuộc, xã Cần Giuộc, tỉnh Tây Ninh; Điện thoại bàn: 02723 875 056 / Số 255, đường Nguyễn Thái Bình, ấp 4, xã Cần Giuộc, tỉnh Tây Ninh

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 1 | Đào Thế Nguyên | Trưởng Thống kê cơ sở | 0909 398 060 | 02723 875 056 |  |  |
| 2 | Lê Phan Nhân | Phó Trưởng Thống kê cơ sở | 0947 350 606 | 02723 875 056 |  |  |

#### Thống kê cơ sở Tân Ninh, Phường Tân Ninh, tỉnh Tây Ninh; Điện thoại bàn: 02763 622 686 / Số 072, đường Ngô Gia Tự, khu phố 16, Phường Tân Ninh, tỉnh Tây Ninh

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 1 | Đặng Thu Phong | Trưởng Thống kê cơ sở | 0834 004 474 | 02763 622 686 |  |  |

#### Thống kê cơ sở Châu Thành, xã Châu Thành, tỉnh Tây Ninh; Điện thoại bàn: 02763 878 114 / Số 1144, đường Hoàng Lê Kha, xã Châu Thành tỉnh Tây Ninh

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 1 | Cù Thị Yến | Trưởng Thống kê cơ sở | 0333 918 676 | 02763 878 114 |  |  |

#### Thống kê cơ sở Trảng Bàng, phường Trảng Bàng, tỉnh Tây Ninh; Điện thoại bàn: 02763 880 279 / Số 08, đường Đặng Văn Trước, khu phố Lộc An, phường Trảng Bàng, tỉnh Tây Ninh

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 1 | Nguyễn Hữu Nhẫn | Trưởng Thống kê cơ sở | 0985 995 480 | 02763 880 279 |  |  |
| 2 | Bồ Thị Kim Hiền | Phó Trưởng Thống kê cơ sở | 0976 987 616 |  |  |  |

#### Thống kê cơ sở Tân Châu, xã Tân Châu, tỉnh Tây Ninh; Điện thoại bàn: 02763 875 134 / Đường Nguyễn Văn Trỗi, khu phố 3, xã Tân Châu, tỉnh Tây Ninh

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 1 | Nguyễn Duy Khánh | Trưởng Thống kê cơ sở | 0988 790 186 | 02763 875 134 |  |  |

#### Thống kê cơ sở Long Hoa, Phường Long Hoa, tỉnh Tây Ninh; Điện thoại bàn: 02763 841 100 / Số 87A, đường Hùng Vương, khu phố 4, phường Long Hoa, tỉnh Tây Ninh

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 1 | Phạm Ngọc Quan | Trưởng Thống kê cơ sở | 0976 272 770 | 02763 841 100 / 02763 877 269 |  |  |

#### Thống kê cơ sở Gò Dầu, Phường Gò Dầu, tỉnh Tây Ninh; Điện thoại bàn: 02763 876 100 / Đường Nguyễn Hữu Thọ, khu phố Nội Ô A, phường Gò Dầu, tỉnh Tây Ninh

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 1 | Lê Mạnh Hùng | Quyền Trưởng Thống kê cơ sở | 0819 223 392 | 02763 876 100 / 02763 853 132 |  |  |

### Bảo hiểm Xã hội tỉnh Tây Ninh / Đ/c: Số 8 tuyến tránh, Quốc lộ 1, phường Long An, tỉnh Tây Ninh

- Nhóm: 1
- Mã/STT nhóm: 7

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 1 | Nguyễn Văn Huấn | GĐ | 0908 999 686 | 02723 839 676 |  |  |
| 2 | Võ Văn Thảo | Phó GĐ | 0913 601 188 | 02723 526 146 |  |  |
| 3 | Bùi Quang Triết | Phó GĐ | 0916 348 578 | 02723 516 751 |  |  |

### Phòng Tổ chức - Hành chính

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 4 | Diệp Minh Trường | Trưởng phòng | 0886 486 567 | 02723 822 426 |  |  |
| 5 | Nguyễn Ngọc Tú | PTP | 0918 902 918 |  |  |  |
| 6 | Trần Thị Tố Như | PTP | 0919 838 781 |  |  |  |
| 7 | Hồ Ngọc Hoài | PTP | 0918 616 794 | 02723 822 420 |  |  |
| 8 | Phạm Sương Thanh | PTP | 0919 201 056 | 02723 822 426 |  |  |
| 9 | Nguyễn Ngọc Đào | PTP | 0817 743 333 | 02723 522 122 |  |  |

### Phòng Cnghệ thtin và Chuyển đổi số

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 10 | Nguyễn Thanh Sơn | Trưởng phòng | 0968 516 060 | 02723 822 462 |  |  |

### Phòng Kế hoạch - Tài chính

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 11 | Lê Văn Thuận | Trưởng phòng | 0919 124 924 | 02723 822 253 |  |  |
| 12 | Phùng Hồng Lam | PTP | 0984 515 660 | 02723 822 253 |  |  |
| 13 | Mạc Lệ Thảo | PTP | 0908 818 440 |  |  |  |

### Phòng Chế độ bảo hiểm xã hội

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 14 | Phạm Hoàng Diễm Trang | Trưởng phòng | 0834 603 604 | 02723 824 584 |  |  |
| 15 | Võ Thị Tuyết Nhung | PTP | 0983 232 067 | 02723 824 584 |  |  |
| 16 | Nguyễn Thị Diễm Thúy | PTP | 0917 040 278 | 02723 824 584 |  |  |
| 17 | Vương Thái Bình | PTP | 0907 648 675 | 02723 824 584 |  |  |
| 18 | Nguyễn Quốc Toản | PTP | 0902 777 055 | 02723 824 584 |  |  |

### Phòng Quản lý thu và Phát triển người tham gia

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 19 | Nguyễn Thanh Quyền | Trưởng phòng | 0903 696 121 | 02723 826 796 |  |  |
| 20 | Phạm Thị Thúy Minh | PTP | 0919 821 982 | 02723 826 796 |  |  |
| 21 | Lê Vũ Tường Vân | PTP | 0949 573 986 | 02723 826 796 |  |  |
| 22 | Nguyễn Thị Thùy Linh | PTP | 0903 377 512 | 02723 826 796 |  |  |
| 23 | Trần Minh Hòa | PTP | 0982 172 800 | 02723 826 796 |  |  |

### Phòng Tuyên truyền và hỗ trợ người tham gia

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 24 | Nguyễn Thị Trúc Linh | Trưởng phòng | 0919 200 313 | 02723 821 764 |  |  |
| 25 | Trần Tú Phương | PTP | 0938 131 413 | 02723 821 764 |  |  |
| 26 | Nguyễn Trọng Thắng | PTP | 0919 542 929 | 02723 821 764 |  |  |

### Phòng Chế độ bảo hiểm y tế

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 27 | Đỗ Tường Tuấn | Trưởng phòng | 0917 188 828 | 02723 821 078 |  |  |
| 28 | Nguyễn Minh Tuấn | PTP | 0908 482 144 | 02723 821 078 |  |  |
| 29 | Nguyễn Thị Bích Hạnh | PTP | 0913 915 515 | 02723 821 078 |  |  |
| 30 | Võ Thị Hoa Phượng | PTP | 0982 702 479 | 02723 821 078 |  |  |

### Phòng Thanh tra - Kiểm tra

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 31 | Mai Hữu Toàn | Trưởng phòng | 0938 542 200 | 02723 525 522 |  |  |
| 32 | Phan Ngọc Sang | PTP | 0943 942 672 | 02723 525 522 |  |  |
| 33 | Nguyễn Thị Thùy Trang | PTP | 0919 014 567 | 02723 525 522 |  |  |

### Ngân hàng Nhà nước Việt Nam khu vực XIII

- Nhóm: 1
- Mã/STT nhóm: 8

### Kho bạc Nhà nước khu vực XVIII - ĐT bàn 02723 837 976 / Đ/c: Số 18 Tuyến tránh Quốc lộ 1, phường Long An, tỉnh Tây Ninh

- Nhóm: 1
- Mã/STT nhóm: 9

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 1 | Mai Đăng Khuê | GĐ | 0983 911 744 | 3829 782 |  |  |
| 2 | Nguyễn Văn Hòa | Phó GĐ | 0946 768 757 | 3829 781 |  |  |
| 3 | Nguyễn Hoài Minh | Phó GĐ | 0378 114 556 |  |  |  |
| 4 | Huỳnh Phúc Luân | Phó GĐ | 0917 720 548 | 3777 548 |  |  |
| 5 | Lê Tấn Toàn | Phó GĐ | 0909 367 086 | 3828 103 |  |  |
| 6 | Nguyễn Nhật Tảo | Phó GĐ | 0913 647 747 |  |  |  |
| 7 | Dương Quan Nhã | Phó GĐ | 0913 660 450 |  |  |  |
| 8 | Huỳnh Văn Tuấn | Phó GĐ | 0977 585 814 |  |  |  |
| 9 | Nguyễn Trường Sơn | Phó GĐ | 0909 662 559 |  |  |  |
| 10 | Nguyễn Thị Thanh Hương | Phó GĐ | 0914 222 565 | 3766 548 |  |  |
| 11 | Nguyễn CBình | Trưởng phòng Tổ chức - Hành chính | 0908 011 744 | 3837 976 |  |  |
| 12 | Võ Thị Thu Trang | PTP Tổ chức - Hành chính | 0918 662 666 | 3822 169 |  |  |
| 13 | Tôn Mai Bích Giang | PTP Tổ chức - Hành chính | 0978 363 799 | 3822 169 |  |  |
| 14 | Huỳnh Hải Hân | PTP Tổ chức - Hành chính | 0382 119 792 | 3822 169 |  |  |
| 15 | Võ Thị Thu Trang | Trưởng phòng Kế toán Nhà nước | 0979 075 395 | 3829 461 |  |  |
| 16 | Nguyễn Thị Hoàng Oanh | PTP Kế toán Nhà nước | 0984 113 897 | 3829 456 |  |  |
| 17 | Lữ Song An | PTP Kế toán Nhà nước | 0919 481 277 | 3829 456 |  |  |
| 18 | Đặng Thị Hồng Thắm | PTP Kế toán Nhà nước | 0397 324 256 | 3829 456 |  |  |
| 19 | Nguyễn Thị Bích Trâm | PTP Kế toán Nhà nước | 0907 608 539 |  |  |  |
| 20 | Lê Văn Hải | PTP Kế toán Nhà nước | 0936 970 003 |  |  |  |
| 21 | Võ Thanh Lâm | Trưởng phòng Kiểm tra | 0909 137 456 | 3824 052 |  |  |
| 22 | Đoàn Trọng Đăng | PTP Kiểm tra | 0973 776 448 | 3829 455 |  |  |
| 23 | Nguyễn Hữu Đức | PTP Kiểm tra | 0919 239 099 | 3829 455 |  |  |
| 24 | Phan Anh Tài | PTP Kiểm tra | 0911 982 599 |  |  |  |
| 25 | Nguyễn Thị Ngọc Nhi | Trưởng phòng Tài vụ - Quản trị | 0972 884 690 | 3830 292 |  |  |
| 26 | Mai Tấn Hưng | PTP Tài vụ - Quản trị | 0919 383 395 | 3830 292 |  |  |
| 27 | Võ Ngọc Thi | PTP Tài vụ - Quản trị | 0984 099 179 | 3830 292 |  |  |
| 28 | Trần Thị Vinh | PTP Tài vụ - Quản trị | 0983 763 205 | 3830 292 |  |  |
| 29 | Lê Ngọc Danh | Trưởng phòng Hỗ trợ Giao dịch và Cnghệ thtin | 0908 615 852 | 3835 036 |  |  |
| 30 | Trần Huỳnh Vũ | PTP Hỗ trợ Giao dịch và Cnghệ thtin | 0907 524 534 | 3835 036 |  |  |
| 31 | Nguyễn Quang Vũ | Trưởng phòng Nghiệp vụ 1 | 0919 541 578 | 3828 102 |  |  |
| 32 | Lê Hùng Cường | PTP Nghiệp vụ 1 | 0908 608 882 | 3822 684 |  |  |
| 33 | Trần Thị Tuyết Anh | PTP Nghiệp vụ 1 | 0918 199 844 | 3822 684 |  |  |
| 34 | La Thanh Phong | Trưởng phòng Nghiệp vụ 2 | 0909 332 996 |  |  |  |
| 35 | Lương Tấn Lộc | PTP Nghiệp vụ 2 | 0919 070 776 |  |  |  |
| 36 | Nguyễn Minh Tuấn | PTP Nghiệp vụ 2 | 0918 435 165 |  |  |  |
| 37 | Lê Thị Thùy | PTP Nghiệp vụ 2 | 0919 588 476 |  |  |  |
| 38 | Lê Minh Quyền | Trưởng phòng Nghiệp vụ 3 | 0908 929 858 | 3877 050 |  |  |
| 39 | Nguyễn Thế Hằng | PTP Nghiệp vụ 3 | 0815 995 599 | 3877 050 |  |  |
| 40 | Bùi Thị Thu Hà | Trưởng phòng Nghiệp vụ 4 | 0836 134 990 | 3867 298 |  |  |
| 41 | Cao Tiến Long | PTP Nghiệp vụ 4 | 0901 656 886 | 3867 141 |  |  |

### Ngân hàng Chính sách XH tỉnh Tây Ninh / Đ/c: Số 79, đường Huỳnh Thị Mai, phường Long An, tỉnh Tây Ninh, ĐT bàn 02723 826 126

- Nhóm: 1
- Mã/STT nhóm: 10

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 1 | Đào Anh Tuấn | Giám đốc | 0912 131 304 |  |  |  |
| 2 | Nguyễn Trọng Điệp | Phó Giám đốc | 0918 089 493 |  |  |  |
| 3 | Nguyễn Thị Ánh Hồng | Phó Giám đốc | 0978 160 077 |  |  |  |
| 4 | Trần Hoàng Khải | Phó Giám đốc | 0989 177 426 |  |  |  |
| 5 | Lê Thanh Điền | Phó Giám đốc | 0942 428 872 |  |  |  |
| 6 | Nguyễn Thị Minh Hằng | Phó Giám đốc | 0944 402 140 | D |  |  |
| 7 | Hồ Văn Khanh | Phó Giám đốc | 0918 811 554 |  |  |  |
| 8 | Thành Duy Vũ | TP. HCTC | 0908 246 137 |  |  |  |
| 9 | Vũ Minh Thư | TP. KTNQ | 0919 821 407 |  |  |  |
| 10 | Trần Thanh Cần | TP. KTNB | 0888 038 186 |  |  |  |
| 11 | Võ Hoàng Bửu | TP. KHNVTD | 0919 550 094 |  |  |  |
| 12 | Phan Minh Hiếu | PTP phụ trách P.Tin học | 0914 260 278 |  |  |  |
| 13 | Huỳnh Vũ Tuấn Hiền | PTP. Tin học | 0949 171 781 |  |  |  |
| 14 | Nguyễn Quang Vinh | PTP. HCTC | 0979 596 706 |  |  |  |
| 15 | Lê Ngọc Phượng | PTP.KTNB | 0934 065 909 |  |  |  |
| 16 | Trần Thế Vinh | PTP.KHNV | 0937 762 010 |  |  |  |
| 17 | Phạm Quang Tiến | PTP.KHNV | 0983 859 596 |  |  |  |
| 18 | Nguyễn Thị Phương Thảo | PTP.KHNV | 0939 590 345 |  |  |  |
| 19 | Nguyễn Thị Trúc Lan Duyên | PTP. KTNQ | 0907 426 219 |  |  |  |

### PHÒNG GIAO DỊCH NHCSXH NINH THẠNH, ĐT BÀN 02763 820 456

- Email: Số 1303 đường Cách Mạng Tháng 8, phường Ninh Thạnh, tỉnh Tây Ninh

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 1 | Trần Nguyễn Như Trâm | Giám đốc PGD | 0913 634 546 |  |  |  |
| 2 | Ngô Hoàng Yên Thi | Phó Giám đốc PGD | 0949 176 446 |  |  |  |

### PHÒNG GIAO DỊCH NHCSXH GÒ DẦU, ĐT BÀN 02763 521 122

- Email: Số 9 đường Lê Hồng Phong, khu phố Rạch Sơn, phường Gò Dầu, tỉnh Tây Ninh

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 1 | Nguyễn Thành Lai | Giám đốc PGD | 0918 437 953 |  |  |  |
| 2 | Ngô Thị Xuân Hồng | Phó Giám đốc PGD | 0944 010 708 |  |  |  |

### PHÒNG GIAO DỊCH NHCSXH TRẢNG BÀNG, ĐT BÀN 02763 883 417

- Email: Khu phố Hòa Bình, Phường Trảng Bàng, tỉnh Tây Ninh

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 1 | Lê Nguyễn Anh Huy | Giám đốc PGD | 0918 811 944 |  |  |  |
| 2 | Trần Thị Thùy Linh | Phó Giám đốc PGD | 0917 797 892 |  |  |  |

### PHÒNG GIAO DỊCH NHCSXH TÂN CHÂU, ĐT BÀN 02763 730 353

- Email: Số 145A đường Lê Duẩn, xã Tân Châu, tỉnh Tây Ninh

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 1 | Trương Hoàng Sơn | Giám đốc PGD | 0979 825 552 |  |  |  |
| 2 | Trần Thái Dương | Phó Giám đốc PGD | 0909 045 146 |  |  |  |
| 3 | Đặng Anh Tuấn | Phó Giám đốc PGD | 0983 624 514 |  |  |  |

### PHÒNG GIAO DỊCH NHCSXH CHÂU THÀNH, ĐT BÀN 02763 780 332

- Email: Số 23 đường ĐT 781, khu phố 3, xã Châu Thành, tỉnh Tây Ninh

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 1 | Lại Thị Ngọc Hạnh | Phó Giám đốc PT PGD | 0913 884 920 |  |  |  |
| 2 | Cao Thị Hồng Xuân | Phó Giám đốc PGD | 0945 155 544 |  |  |  |

### PHÒNG GIAO DỊCH NHCSXH TÂN BIÊN, ĐT BÀN 02763 744 918

- Email: Số 17 đường Nguyễn Văn Linh, khu phố 3, xã Tân Biên, tỉnh Tây Ninh

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 1 | Phạm Hồng Vinh | Giám đốc PGD | 0977 349 050 |  |  |  |
| 2 | Lưu Quốc Tuấn | Phó Giám đốc PGD | 0908 989 458 |  |  |  |
| 3 | Hồ Văn Luật | Phó Giám đốc PGD | 0949 465 051 |  |  |  |

### PHÒNG GIAO DỊCH NHCSXH BẾN CẦU, ĐT BÀN 02763 761 127

- Email: Số 02 đường Nguyễn Trung Trực, khu phố 2, xã Bến Cầu, tỉnh Tây Ninh

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 1 | Nguyễn Võ Nhật Duy An | Giám đốc PGD | 0918872725 |  |  |  |
| 2 | Võ Thị Cẩm Giang | Phó Giám đốc PGD | 0911997733 |  |  |  |

### PHÒNG GIAO DỊCH NHCSXH HÒA THÀNH, ĐT BÀN 02763 830 927

- Email: Số 119 đường Lý Thường Kiệt, phường Long Hoa, tỉnh Tây Ninh.

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 1 | Nguyễn Quốc Cường | Giám đốc PGD | 0908 695 353 |  |  |  |
| 2 | Nguyễn Thị Như Thùy | Phó Giám đốc PGD | 0917 621 412 |  |  |  |

### PHÒNG GIAO DỊCH NHCSXH DƯƠNG MINH CHÂU, ĐT BÀN 02763 720 134

- Email: Đường Dương Minh Châu, ấp 1, xã Dương Minh Châu, tỉnh Tây Ninh

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 1 | Nguyễn Việt Huy | Giám đốc PGD | 0918 400 703 |  |  |  |
| 2 | Nguyễn Hữu Phước | Phó Giám đốc PGD | 0918 177 760 |  |  |  |

### PHÒNG GIAO DỊCH NHCSXH THỦ THỪA, ĐT BÀN 02723 611 127

- Email: Đường Võ Văn Tịnh, ấp Cầu Xây, xã Thủ Thừa, tỉnh Tây Ninh

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 1 | Nguyễn Thị Minh Nguyệt | Giám đốc PGD | 0834 570 946 |  |  |  |

### PHÒNG GIAO DỊCH NHCSXH TÂN TRỤ, ĐT BÀN 02723 868 470

- Email: Đường Nguyễn Trung Trực, ấp Tân Bình, xã Tân Trụ, tỉnh Tây Ninh

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 1 | Huỳnh Trọng Tín | Giám đốc PGD | 0946 789 565 |  |  |  |
| 2 | Trần Bá Lộc | Phó Giám đốc PGD | 0982 298 787 |  |  |  |

### PHÒNG GIAO DỊCH NHCSXH BẾN LỨC, ĐT BÀN 02723 631 763

- Email: Số 174 đường Võ Công Tồn, ấp Bến Lức 1, xã Bến Lức, tỉnh Tây Ninh

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 1 | Trương Trần Tuấn | Giám đốc PGD | 0903 071 660 |  |  |  |
| 2 | Nguyễn Thị Thúy Phượng | Phó Giám đốc PGD | 0332 549 548 |  |  |  |

### PHÒNG GIAO DỊCH NHCSXH CẦN GIUỘC, ĐT BÀN 02723 893 739

- Email: Số 85 đường Nguyễn An Ninh, ấp 3, xã Cần Giuộc, tỉnh Tây Ninh

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 1 | Nguyễn Thế Thắng | Giám đốc PGD | 0918 976 336 |  |  |  |
| 2 | Phan Ngọc Mẫn | Phó Giám đốc PGD | 0902 413 113 |  |  |  |

### PHÒNG GIAO DỊCH NHCSXH CẦN ĐƯỚC, ĐT BÀN 02723 885 646

- Email: Quốc lộ 50, ấp 1, xã Cần Đước, tỉnh Tây Ninh

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 1 | Châu Ngọc Vũ | Giám đốc PGD | 0944 662 727 |  |  |  |
| 2 | Phạm Thị Ngọc Phương Diễm | Phó Giám đốc PGD | 0907 014 789 |  |  |  |

### PHÒNG GIAO DỊCH NHCSXH ĐỨC HÒA, ĐT BÀN 02723 812 583

- Email: Số 307 Tỉnh lộ 825, xã Hậu Nghĩa, tỉnh Tây Ninh

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 1 | Nguyễn Thị Anh Thư | Giám đốc PGD | 0909 817 259 |  |  |  |
| 2 | Lương Ngọc Ép | Phó Giám đốc PGD | 0936 026 435 |  |  |  |

### PHÒNG GIAO DỊCH NHCSXH ĐỨC HUỆ, ĐT BÀN 02723 855 761

- Email: Số 294 đường Nguyễn Trung Trực, ấp Thành Nam, xã Đông Thành, tỉnh Tây Ninh

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 1 | Lê Tấn Thành | Giám đốc PGD | 0919 399 747 |  |  |  |
| 2 | Nguyễn Trung Tính | Phó Giám đốc PGD | 0979 438 646 |  |  |  |

### PHÒNG GIAO DỊCH NHCSXH TÂN THẠNH, ĐT BÀN 02723 844 927

- Email: Số 02 đường Trần Văn Trà, ấp 1, xã Tân Thạnh, tỉnh Tây Ninh

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 1 | Nguyễn Trung Việt | Giám đốc PGD | 0938 745 516 |  |  |  |
| 2 | Phạm Thị Thúy Hằng | Phó Giám đốc PGD | 0948 700 881 |  |  |  |

### PHÒNG GIAO DỊCH NHCSXH MỘC HÓA, ĐT BÀN 02723 968 699

- Email: Đường Thủ Khoa Huân, ấp cả đá, xã Mộc Hóa, tỉnh Tây Ninh

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 1 | Lê Hoài Nhân | Giám đốc PGD | 0917 910 815 |  |  |  |
| 2 | Nguyễn Danh Toại | Phó Giám đốc PGD | 0982 729 936 |  |  |  |

### PHÒNG GIAO DỊCH NHCSXH VĨNH HƯNG, ĐT BÀN 02723 848 335

- Email: Số 6 đường 30/4, ấp Măng Đa, xã Vĩnh Hưng, tỉnh Tây Ninh

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 1 | Phan Trọng Trinh | Giám đốc PGD | 0983 801 456 |  |  |  |
| 2 | Nguyễn Ngọc Sinh | Phó Giám đốc PGD | 0917 472 117 |  |  |  |

### PHÒNG GIAO DỊCH NHCSXH THẠNH HÓA, ĐT BÀN 02723 911 985

- Email: Đường Hùng Vương, ấp Cái Vòm, xã Thạnh Hóa, tỉnh Tây Ninh

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 1 | Nguyễn Thành Kết | Giám đốc PGD | 0986796677 |  |  |  |
| 2 | Lữ Thanh Hòa | Phó Giám đốc PGD | 0948859777 |  |  |  |

### PHÒNG GIAO DỊCH NHCSXH TẦM VU, ĐT BÀN 02723 887 450

- Email: Số 220 đường Đỗ Tường Phong, ấp Tân Xuân, xã Tầm Vu, tỉnh Tây Ninh

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 1 | Nguyễn Văn Lừng | Giám đốc PGD | 0913 818 578 |  |  |  |
| 2 | Võ Duy Tiền | Phó Giám đốc PGD | 0919 936 074 |  |  |  |

### PHÒNG GIAO DỊCH NHCSXH TÂN HƯNG, ĐT BÀN 02723 861 468

- Email: Số 28 đường 3/2, ấp Gò Thuyền B, xã Tân Hưng, tỉnh Tây Ninh

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 1 | Phạm Hoàng Long | Phó Giám đốc PT PGD | 0919 801 805 |  |  |  |
| 2 | Phan Trung Nhân | Phó Giám đốc PGD | 0988 415 457 |  |  |  |

### PHÒNG GIAO DỊCH NHCSXH KIẾN TƯỜNG, ĐT BÀN 02723 843 543

- Email: Số 25 đường Thiên Hộ Dương, khu phố 8, phường Kiến Tường, tỉnh Tây Ninh

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 1 | Phạm Văn Kiệt | Giám đốc PGD | 0918 701 979 |  |  |  |
| 2 | Phan Xuân Vinh | Phó Giám đốc PGD | 0917 737 715 |  |  |  |

### Tòa án nhân dân tỉnh / Đ/c: số 12 Tuyến tránh Quốc lộ 1, Phường Long An, tỉnh Tây Ninh

- Nhóm: 1
- Mã/STT nhóm: 11

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 1 | Lê Quốc Dũng | Chánh án | 918955012 |  |  |  |
| 2 | Đỗ Văn Thinh | Phó Chánh án | 0339 779 486 |  |  |  |
| 3 | Lương Minh Trí | Phó Chánh án | 0916 535 999 |  |  |  |
| 4 | Phan Ngọc Hoàng Đình Thục | Phó Chánh án | 0918 128 993 |  |  |  |

#### Các đơn vị trực thuộc TAND tỉnh

#### Tòa Hình sự

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 1 | Trần Quốc Khánh | Chánh tòa | 0949 198 197 |  |  |  |
| 2 | Nguyễn Thiện Tâm | Phó Chánh Tòa | 0909 108 644 |  |  |  |
| 3 | Phạm Thị Thanh Giang | Phó Chánh Tòa | 0918 400 447 |  |  |  |

#### Tòa Dân sự

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 1 | Lê Thị Kim Nga | Chánh tòa | 0945 896 519 |  |  |  |
| 2 | Huỳnh Thị Hồng Vân | Phó Chánh Tòa | 0907 319 294 |  |  |  |
| 3 | Nguyễn Thị Mỹ Hạnh | Phó Chánh Tòa | 0902 581 235 |  |  |  |

#### Tòa Hành chính

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 1 | Phan Thanh Tùng | Chánh tòa | 0918 663 448 |  |  |  |
| 2 | Nguyễn Quốc Tuấn | Phó Chánh Tòa | 0919 188 306 |  |  |  |
| 3 | Nguyễn Phước Thanh | Phó Chánh Tòa | 0909 275 773 |  |  |  |

#### Tòa Gia đình và người chưa thành niên

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 1 | Phùng Thị Cẩm Hồng | Chánh tòa | 0919 765 446 |  |  |  |
| 2 | Phạm Thị Hồng Vân | Phó Chánh Tòa | 0902 988 205 |  |  |  |

#### Phòng Tổ chức cán bộ

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 1 | Nguyễn Thị Thuận | Trưởng phòng | 0906 303 217 |  |  |  |
| 2 | Lê Thị Ngọc Lan | Phó Trưởng phòng | 0907 772 717 |  |  |  |
| 3 | Trịnh Minh Hải | Phó Trưởng phòng | 0858 039 058 |  |  |  |

#### Văn phòng

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 2 | Trần Trọng Nhân | Q.Phó Chánh Văn phòng | 0977 965 052 |  |  |  |
| 3 | Ngô Thị Ngọc Trinh | Phó Chánh Văn phòng | 0903 706 391 |  |  |  |

#### Phòng Giám đốc, kiểm tra, thanh tra và thi hành án

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 1 | Lê Thị Thu Trang | Trưởng phòng | 0917 255 475 |  |  |  |
| 2 | Nguyễn Văn Nam | Phó Trưởng phòng | 0919 466 060 |  |  |  |

### Việm kiểm sát Nhân dân tỉnh / Đc: Địa chỉ số 14 Tuyến tránh Quốc lộ 1, Phường Long An, tỉnh Tây Ninh

- Nhóm: 1
- Mã/STT nhóm: 12

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 1 | Mai Văn Linh | Viện trưởng |  | 0903 641 163 |  |  |
| 2 | Trương Văn Nghị | Phó Viện trưởng |  | 0918 350 880 | 02723 821 794 |  |
| 3 | Phạm Văn Hiệp | Phó Viện trưởng |  | 0838 695 969 | 02723 824 331 |  |
| 4 | Nguyễn Thành Bông | Phó Viện trưởng |  | 0908 951 069 | 02723 839 627 |  |
| 5 | Tống Thị Kim Hương | Phó Viện trưởng |  | 0908 919 969 | 02723 825 674 |  |
| 6 | Phan Văn Ne | Phó Viện trưởng |  | 0918 623 707 |  |  |
| 7 | Nguyễn Hoàng Dũng | Phó Viện trưởng |  | 0903 077 292 |  |  |
| 8 | Trần Thị Thụy Vũ | Phó Viện trưởng |  | 0907 584 457 |  |  |

#### Các Phòng trực thuộc VKSND tỉnh

#### Phòng 1

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 9 | Lê Hồng Nhân | Trưởng phòng |  | 0919 737 227 | 02723 551 759 |  |
| 10 | Nguyễn Thị Hằng | Phó Trưởng phòng |  | 0909 019 900 |  |  |

#### Phòng 2

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 11 | Nguyễn Văn Kho | Trưởng phòng |  | 0919 460 053 | 02723 825 755 |  |
| 12 | Vũ Thị Bích Hường | Phó Trưởng phòng |  | 0919 908 974 |  |  |
| 13 | Nguyễn Hoàng Quân | Phó Trưởng phòng |  | 0908 490 037 |  |  |

#### Phòng 3

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 14 | Nguyễn Văn Thảo | Trưởng phòng |  | 0919 720 587 |  |  |
| 15 | Nguyễn Văn Anh | Phó Trưởng phòng |  | 0908 044 222 |  |  |

#### Phòng 7

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 16 | Bùi Văn Phước | Trưởng phòng |  | 0919 124 600 | 02723 838 362 |  |
| 17 | Trần Quốc Vương | Phó Trưởng phòng |  | 0983 121 751 |  |  |

#### Phòng 8

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 18 | Lê Hoàng Khải | Trưởng phòng |  | 0913 818 770 |  |  |
| 19 | Đỗ Hoàng Phận | Phó Trưởng phòng |  | 0909 369 773 |  |  |
| 20 | Nguyễn Văn Tấn | Phó Trưởng phòng |  | 0916 405 252 |  |  |

#### Phòng 9

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 21 | Nguyễn Thị Cẩm Hồng | Trưởng phòng |  | 0917 676 673 | 02723 512 227 |  |
| 22 | Lê Ngọc Hiền | Phó Trưởng phòng |  | 0982 121 377 |  |  |
| 23 | Huỳnh Thị Mộng Thúy | Phó Trưởng phòng |  | 0918 875 670 |  |  |
| 24 | Nguyễn Khánh Bình | Phó Trưởng phòng |  | 0387 666 638 |  |  |

#### Phòng 10

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 25 | Lương Hữu Hiệp | Trưởng phòng |  | 0919 257 077 | 02723 552 569 |  |
| 26 | Lê Thị Hồng Hạnh | Phó Trưởng phòng |  | 0917 636 610 |  |  |

#### Phòng 15

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 27 | Lê Thị Thu Hồng | Trưởng phòng |  | 0919 204 369 | 02723 838 362 |  |
| 28 | Trần Vạn Quốc | P.Trưởng phòng |  | 0974 747 127 |  |  |

#### Thanh tra - Khiếu tố

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 29 | Phạm Thanh Loan | Chánh Thanh tra |  | 0983 336 517 | 02723 553 259 |  |
| 30 | Lê Thị Ngọc Lan | Phó Chánh Thanh tra |  | 0856 903 969 |  |  |

#### Văn phòng

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 31 | Phạm Thị Thanh Nhã | Chánh VP |  | 0987 302 181 | 02723 513 434 |  |
| 32 | Nguyễn Thị Xuân Bích | Phó Chánh VP |  | 0333 393 586 |  |  |
| 33 | Lê Văn Biết | Phó Chánh VP |  | 0914 449 255 |  |  |
| 34 | Nguyễn Hải Đăng | Kế toán trưởng |  | 0919 282 298 | 02723 830 923 |  |

### Thi hành án dân sự tỉnh Tây Ninh / Đ/c: Số 266A, tỉnh lộ 827A, Khu phố Bình Nam, phường Tân An, tỉnh Tây Ninh / ĐT bàn: 02723 837 835 - 02723 829 523

- Nhóm: 1
- Mã/STT nhóm: 13

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 1 | Bùi Phú Hưng | Trưởng THADS tỉnh | 0908 460 324 |  |  |  |
| 2 | Lê Đức Thọ | Phó Trưởng THADS tỉnh | 0982 299 919 |  |  |  |
| 3 | Đặng Hoàng Yên | Phó Trưởng THADS tỉnh | 0906 743 182 |  |  |  |
| 4 | Đặng Văn Vũ | Phó Trưởng THADS tỉnh | 0913 999 538 |  |  |  |
| 5 | Đặng Thị Tuyền | Phó Trưởng THADS tỉnh | 0902 960 313 |  |  |  |
| 6 | Bùi Thị Thu Hương | Quyền Chánh Văn phòng | 0902 325 725 |  |  |  |
| 8 | Nguyễn Thị Hồng Nhiễm | Phó Trưởng phòng TCCB | 0933 707 268 |  |  |  |
| 9 | Trần Thị Thanh Biếc | Trưởng phòng TCKT | 0919 574 667 |  |  |  |
| 10 | Phạm Lê Tuấn An | Trưởng phòng NV&TCTHADS | 0909 980 736 |  |  |  |
| 11 | Lê Minh Gập | Phó Trưởng phòng NV&TCTHADS | 0849 124 979 |  |  |  |
| 12 | Võ Xuân Lam | Phó Trưởng phòng NV&TCTHADS | 0937 323 542 |  |  |  |
| 13 | Nguyễn Quốc Khánh | Phó Trưởng phòng NV&TCTHADS | 0906 752 757 |  |  |  |

#### PHÒNG THI HÀNH ÁN DÂN SỰ KHU VỰC 1- TÂY NINH (TÂN AN, THỦ THỪA)

- Email: Số 05A Nguyễn Thị Rành, Khu phố Tân Xuân 4, Phường Long An, tỉnh Tây Ninh

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 1 | Nguyễn Xuân Hải | Trưởng phòng | 0919 899 794 |  |  |  |

#### PHÒNG THI HÀNH ÁN DÂN SỰ KHU VỰC 2 - TÂY NINH (TÂN THẠNH, THẠNH HÓA, ĐỨC HUỆ)

- Điện thoại cơ quan: 02723 857 156
- Email: Đường Trần Văn Trà, Khu phố 3, xã Thạnh Hoá, tỉnh Tây Ninh

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 1 | Lê Khắc Huy | Phó Trưởng phòng | 0943 300 589 |  |  |  |

#### PHÒNG THI HÀNH ÁN DÂN SỰ KHU VỰC 3 - TÂY NINH (ĐỨC HÒA)

- Điện thoại cơ quan: 02723 851 509
- Email: Đường Nguyễn Trọng Thế, / Khu B, xã Hậu Nghĩa, tỉnh Tây Ninh

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 1 | Nguyễn Thành Công | Trưởng phòng | 0949 198 261 |  |  |  |
| 2 | Bùi Thanh Tuấn | Phó Trưởng phòng | 0908 636 866 |  |  |  |
| 3 | Trần Văn Tuấn | Phó Trưởng phòng | 0903 260 163 |  |  |  |

#### PHÒNG THI HÀNH ÁN DÂN SỰ KHU VỰC 4 - TÂY NINH (BẾN LỨC)

- Điện thoại cơ quan: 02723 871 321
- Email: Đường Võ Công Tồn, Khu / phố 3, xã Bến Lức, tỉnh Tây Ninh

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 1 | Phạm Công Nhơn | Trưởng phòng | 0907 337 976 |  |  |  |

#### PHÒNG THI HÀNH ÁN DÂN SỰ KHU VỰC 5 - TÂY NINH (CHÂU THÀNH, TÂN TRỤ)

- Điện thoại cơ quan: 02723 877 029
- Email: Số 51/6 đường Đỗ Tường / Phong, Khu phố 3, xã Tầm Vu, tỉnh Tây Ninh

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 1 | Trần Thành Được | Quyền Trưởng phòng | 0918 371 999 |  |  |  |

#### PHÒNG THI HÀNH ÁN DÂN SỰ KHU VỰC 6 - TÂY NINH (CẦN ĐƯỚC)

- Điện thoại cơ quan: 02723 881 341
- Email: Số 199 đường tỉnh 826, Khu / 1C, xã Cần Đước, tỉnh Tây Ninh

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 1 | Lê Văn Nhì | Trưởng phòng | 0365 298 708 |  |  |  |
| 3 | Bùi Nam | Phó Trưởng phòng | 0934 054 778 |  |  |  |

#### PHÒNG THI HÀNH ÁN DÂN SỰ KHU VỰC 7 - TÂY NINH (CẦN GIUỘC)

- Điện thoại cơ quan: 02723 874 988
- Email: Số 126 Quốc lộ 50, Khu phố 4, xã Cần Giuộc, tỉnh Tây Ninh

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 1 | Nguyễn Phúc Lê Phương | Trưởng phòng | 0919 369 120 |  |  |  |
| 2 | Hồ Phan Thanh Phú | Phó Trưởng phòng | 0908 209 173 |  |  |  |

#### PHÒNG THI HÀNH ÁN DÂN SỰ KHU VỰC 8 - TÂY NINH (KIẾN TƯỜNG, MỘC HÓA)

- Điện thoại cơ quan: 02723 841 487
- Email: Số 08 đường 30/4, Khu phố 1, Phường Kiến Tường, tỉnh Tây Ninh

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 1 | Nguyễn Văn Thưởng | Trưởng phòng | 0979 563 877 |  |  |  |
| 2 | Trần Ngọc Trát | Phó Trưởng phòng | 0917 731 888 |  |  |  |

#### PHÒNG THI HÀNH ÁN DÂN SỰ KHU VỰC 9 - TÂY NINH (VĨNH HƯNG, TÂN HƯNG)

- Điện thoại cơ quan: 02723 847 127
- Email: Số 55 đường 30/4, Khu phố / Măng Đa, xã Vĩnh Hưng, tỉnh Tây Ninh

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 1 | Nguyễn Văn Việt | Trưởng phòng | 0832 861 448 |  |  |  |
| 2 | Lê Anh Quý | Phó Trưởng phòng | 0944 243 479 |  |  |  |
| 3 | Hồ Văn Dũng | Phó Trưởng phòng | 0965 756 568 |  |  |  |

#### PHÒNG THI HÀNH ÁN DÂN SỰ KHU VỰC 10 - TÂY NINH (TÂY NINH, HÒA THÀNH, CHÂU THÀNH)

- Điện thoại cơ quan: 02763 815 969
- Email: Số 01 đường Đặng Ngọc / Chinh, Khu phố 1, Phường Tân Ninh, tỉnh Tây Ninh

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 1 | Hồ Chí Bửu Nghi | Trưởng phòng | 0918 310 032 |  |  |  |
| 2 | Lê Thị Thu Thảo | Phó Trưởng phòng | 0919 357 657 |  |  |  |
| 3 | Đàm Thị Phương | Phó Trưởng phòng | 0985 566 693 |  |  |  |
| 4 | Nguyễn Minh Chí | Phó Trưởng phòng | 0902 400 272 |  |  |  |

#### PHÒNG THI HÀNH ÁN DÂN SỰ KHU VỰC 11 - TÂY NINH (TÂN CHÂU, TÂN BIÊN, DƯƠNG MINH CHÂU)

- Điện thoại cơ quan: 02763 874 010
- Email: Số 02 Lê Trọng Tấn, Khu phố 4, xã Tân Châu, tỉnh Tây Ninh

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 1 | Nguyễn Thị Lành | Trưởng phòng | 0376 788 715 |  |  |  |
| 2 | Trần Thị Diễm Trang | Phó Trưởng phòng | 0979 172 773 |  |  |  |
| 3 | Phạm Thanh Phong | Phó Trưởng phòng | 0938 260 062 |  |  |  |
| 5 | Phạm Thúy Kiều | Phó Trưởng phòng | 0798 461 979 |  |  |  |

#### PHÒNG THI HÀNH ÁN DÂN SỰ KHU VỰC 12 - TÂY NINH (GÒ DẦU, BẾN CẦU, TRẢNG BÀNG)

- Điện thoại cơ quan: 02763 853 023
- Email: Số 7 đường Nguyễn Hữu Thọ, Khu phố Nội Ô A, Phường Gò Dầu, tỉnh Tây Ninh

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 1 | Nguyễn Thành Sang | Trưởng phòng | 0907 453 475 |  |  |  |
| 2 | Nguyễn Minh Văn | Phó Trưởng phòng | 0978 438 588 |  |  |  |
| 3 | Lê Văn Nhân | Phó Trưởng phòng | 0909 361 540 |  |  |  |
| 4 | Đặng Minh Phương | Phó Trưởng phòng | 0918 083 868 |  |  |  |
| 5 | Trần Khắc Huy | Phó Trưởng phòng | 0913 070 504 |  |  |  |
| 4 | Hồ Thị Kim Ngân | Phó Trưởng phòng | 0919 181 161 |  |  |  |
| 5 | Phạm Thúy Kiều | Phó Trưởng phòng | 0798 461 979 |  |  |  |

#### PHÒNG THI HÀNH ÁN DÂN SỰ KHU VỰC 12 - TÂY NINH (GÒ DẦU, BẾN CẦU, TRẢNG BÀNG)

- Điện thoại cơ quan: 02763 853 023
- Email: Số 7 đường Nguyễn Hữu Thọ, Khu phố Nội Ô A, Phường Gò Dầu, tỉnh Tây Ninh

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 1 | Nguyễn Thành Sang | Trưởng phòng | 0907 453 475 |  |  |  |
| 2 | Nguyễn Minh Văn | Phó Trưởng phòng | 0978 438 588 |  |  |  |
| 3 | Lê Văn Nhân | Phó Trưởng phòng | 0909 361 540 |  |  |  |
| 4 | Đặng Minh Phương | Phó Trưởng phòng | 0918 083 868 |  |  |  |
| 5 | Trần Khắc Huy | Phó Trưởng phòng | 0913 070 504 |  |  |  |

### Viễn thông Long An / Đ/c: Số 2, đường 22, Khu đô thị Trung tâm Hành chínhTỉnh, KP Bình Cư 2, phường Long An, tỉnh Tây Ninh / ĐT bàn 02723 821 619; email: vnptlongan@vnpt.vn;

- Nhóm: 1
- Mã/STT nhóm: 14

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 1 | Nguyễn Nam Quốc | Trưởng đại diện, Giám đốc VNPT Long An | 0913 497 029 | 3826 234 |  |  |
| 2 | Huỳnh Chí Tường | Phó Giám đốc VNPT Long An | 0913 622 899 | 3828 009 |  |  |
| 3 | Trần Nguyễn Hưng Thái | Phó Giám đốc VNPT Long An, Giám đốc TTKD VNPT - Long An | 0919 937 938 | 3825 888 |  |  |
| 4 | Huỳnh Thị Bích Liên | Chủ tịch Công đoàn VNPT Long An | 0917 676 676 | 3830 830 |  |  |
| 5 | Trần Văn Thắm | Trưởng phòng Nhân sự - Tổng hợp | 0919 541 567 | 3836 234 |  |  |
| 6 | Châu Văn Hoàng | Phó trưởng phòng Nhân sự - Tổng hợp | 0918 085 789 | 3552 234 |  |  |
| 7 | Đinh Tấn Hữu | Kế toán trưởng, Trưởng phòng Kế hoạch - Kế toán | 0918 129 789 | 3824 732 |  |  |
| 8 | Lương Thế Phú | Trưởng phòng Kỹ thuật - Đầu tư | 0919 820 826 | 3839 878 |  |  |
| 9 | Trương Đình Tuệ Phúc | Phó trưởng phòng Kỹ thuật - Đầu tư | 0918 266 004 | 3823 877 |  |  |

### Bưu điện tỉnh Long An / Đ/c: Số 55 Trương Định, Phường Long An, tỉnh Tây Ninh

- Nhóm: 1
- Mã/STT nhóm: 15

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 1 | Ôn Thị Kim Hồng | Bí thư ĐU, Giám đốc BĐT | 0918 700 799 | 3552 299 |  |  |
| 2 | Lại Thị Kim Thoa | Phó BTĐU, Phó Giám đốc BĐT | 0917 095 777 | 3838 234 |  |  |
| 3 | Nguyễn Hoàn Long | Phó Giám đốc BĐT | 0916 996 666 | 3521 000 |  |  |
| 4 | Lưu Thái Dũng | Kế toán trưởng BĐT | 0946 788 999 | 3823 056 |  |  |
| 5 | Võ Thị Mỹ An | Phó phòng Tài chính - Kế hoạch | 0919 820 838 | 3823 052 |  |  |
| 6 | Nguyễn Hoàng Mai Chi | Trưởng phòng Tổ chức - Hành chính | 0946 190 776 | 3829 430 |  |  |
| 7 | Phạm Nguyễn Tú | Phó phòng Tổ chức - Hành chính | 0917 641 525 | 3552 345 |  |  |
| 8 | Phạm Khắc Điệp | Phó Giám đốc Trung tâm kinh doanh | 0918 606 969 |  |  |  |
| 9 | Nguyễn Thanh Xuân | Phó Giám đốc Trung tâm vận hành | 0919 124 767 | 3827 415 |  |  |

### CTY ĐIỆN LỰC TÂY NINH / Đ/c: Số 168 Tuyến tránh, Phường Long An, Tỉnh Tây Ninh / ĐT: 19001006; Email: pctayninh@evnspc.vn; Website: https://pctayninh.evnspc.vn;

- Nhóm: 1
- Mã/STT nhóm: 16

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 1 | Nguyễn Tấn Hùng | GĐ | 0915 955 040 |  |  |  |
| 2 | Trần Thanh Liêm | Phó GĐ Kỹ thuật | 0913 239 839 |  |  |  |
| 3 | Nguyễn Huy Phương | Phó GĐ Kỹ thuật | 0914 687 489 |  |  |  |
| 4 | Đỗ Anh Dũng | Phó GĐ Kinh doanh/Sản xuất khác | 0833 689 939 |  |  |  |
| 5 | Nguyễn Ngọc Tuấn | Phó GĐ Kinh doanh/Sản xuất khác | 0913 686 853 |  |  |  |
| 6 | Phạm Ngô Hoàng Trang | Phó GĐ Đầu tư xây dựng | 0918 675 292 |  |  |  |
| 7 | Nguyễn Hoàng Hải | Phó GĐ Đầu tư xây dựng | 0913 686 853 |  |  |  |
| 8 | Lê Tấn Việt | Trưởng phòng điều độ | 0914 563 436 |  |  |  |
| 9 | Trần Nguyên Khánh | PTP Điều độ | 0842 820 210 |  |  |  |
| 10 | Nguyễn Văn Lam | PTP Điều độ | 0948 999 801 |  |  |  |
| 11 | Nguyễn Hồ Hữu Ngọc | PTP Điều độ | 0962 555 377 |  |  |  |
| 12 | Hoàng Xuân Tuyên | PTP Điều độ | 0962 537 817 |  |  |  |

### ĐỘI QUẢN LÝ ĐIỆN TÂN CHÂU - ĐT: 19001006, / Đ/c: 151 Lê Duẩn, ấp 4, xã Tân Châu, tỉnh Tây Ninh

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 1 | Âu Khương Tình | Đội trưởng | 0915 022 080 |  |  |  |
| 2 | Trần Thanh Tâm | Đội phó | 0964 884 807 |  |  |  |
| 3 | Nguyễn Bá Phước | Đội phó | 0971 522 052 |  |  |  |

### ĐỘI QUẢN LÝ ĐIỆN GÒ DẦU - ĐT: 19001006, / Đ/c: 11 Lê Hồng Phong, khu phố Rạch Sơn, phường Gò Dầu, tỉnh Tây Ninh

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 1 | Mai Phong Phi Long | Đội trưởng | 0899 994 439 |  |  |  |
| 2 | Đặng Trung Hiếu | Đội phó | 0913 511 692 |  |  |  |
| 3 | Nghiêm Đình Anh Khoa | Đội phó | 0918 521 215 |  |  |  |

### ĐỘI QUẢN LÝ ĐIỆN TRẢNG BÀNG - ĐT: 19001006, / Đ/c: Đường số 12, Khu cnghiệp Trảng Bàng, phường An Tịnh, tỉnh Tây Ninh

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 1 | Phạm Hoàng Chí | Đội trưởng | 0937 114 114 |  |  |  |
| 2 | Nguyễn Duy Tân | Đội phó | 0974 918 718 |  |  |  |

### ĐỘI QUẢN LÝ ĐIỆN THÁI BÌNH - ĐT: 19001006, / Đ/c: Số 117, đường Tua Hai - Đồng Khởi, xã Châu Thành, tỉnh Tây Ninh

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 1 | Nguyễn Quốc Nam | Đội trưởng | 0916 700 911 |  |  |  |
| 2 | Trần Hồng Nhựt | Đội phó | 0913 989 440 |  |  |  |
| 3 | Bùi Trung Thành | Đội phó | 0969 396 868 |  |  |  |

### ĐỘI QUẢN LÝ ĐIỆN DƯƠNG MINH CHÂU - ĐT: 19001006, / Đ/c: ấp Tân Định 1, xã Dương Minh Châu, tỉnh Tây Ninh

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 1 | Lê Văn Phư | Đội trưởng | 0912 992 207 |  |  |  |
| 2 | Nguyễn Văn Thành Kha | Đội phó | 0914 091 441 |  |  |  |
| 3 | Nguyễn Phú Đức | Đội phó | 0989 517 839 |  |  |  |

### ĐỘI QUẢN LÝ ĐIỆN TÂN BIÊN - ĐT: 19001006, / Đ/c: Số 117 Nguyễn Chí Thanh, Xã Tân Biên Tỉnh Tây Ninh

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 1 | Nguyễn Ngọc Thanh Tâm | Đội trưởng | 0963 777 199 |  |  |  |
| 2 | Châu Quang Đạt | Đội phó | 0963 070 171 |  |  |  |
| 3 | Huỳnh Trần Bửu Khoa | Đội phó | 0915 409 949 |  |  |  |

### ĐỘI QUẢN LÝ ĐIỆN TÂN NINH - ĐT: 19001006, / Đ/c: số 508, đường CMT8, KP3, Phường Tân Ninh, tỉnh Tây Ninh

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 1 | Lê Tấn Đạt | Đội trưởng | 0917 851 111 |  |  |  |
| 2 | Phan Lê Anh Tuấn | Đội phó | 0908 685 252 |  |  |  |
| 3 | Huỳnh Quang Vinh | Đội phó | 0937 099 911 |  |  |  |

### ĐỘI QUẢN LÝ ĐIỆN HÒA THÀNH - ĐT: 19001006, / Đ/c: số 3, hẻm 18, Đường Ngô Quyền, ấp Long Hải, Phường Long Hoa, tỉnh Tây Ninh

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 1 | Lê Thanh Chinh | Đội trưởng | 0918 199 955 |  |  |  |
| 2 | Cao Hoàng Sơn | Đội phó | 0915 852 857 |  |  |  |
| 3 | Lê Phước Lễ | Đội phó | 0963 933 977 |  |  |  |

### ĐỘI QUẢN LÝ ĐIỆN BẾN CẦU - ĐT: 19001006, / Đ/c: Số 78, đường Nguyễn Trung Trực, KP2, xã Bến Cầu, tỉnh Tây Ninh

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 1 | Huỳnh Phước Lương | Đội trưởng | 0962 505 515 |  |  |  |
| 2 | Dương Cao Sang | Đội phó | 0919 962 969 |  |  |  |

### ĐỘI QUẢN LÝ ĐIỆN ĐỨC HÒA - ĐT: 19001006 / Ô 7, Khu B, Xã Hậu Nghĩa, tỉnh Tây Ninh

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 1 | Nguyễn Tấn Định | Đội trưởng | 0913 226 675 |  |  |  |
| 2 | Nguyễn Văn Điệu | Đội phó | 0916 962 762 |  |  |  |
| 3 | Đinh Văn Thắng | Đội phó | 0962 711 644 |  |  |  |

### ĐỘI QUẢN LÝ ĐIỆN BẾN LỨC - ĐT: 19001006 / 199 Quôc lộ 1A, xã Bến Lức, tinh Tây Ninh

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 1 | Nguyễn Viết Lĩnh | Đội trưởng | 0913 999 272 |  |  |  |
| 2 | Nguyễn Minh Thuyên | Đội phó | 0912 427 767 |  |  |  |
| 3 | Trần Quốc Tuấn | Đội phó | 0963 858 789 |  |  |  |

### ĐỘI QUẢN LÝ ĐIỆN CẦN GIUỘC - ĐT: 19001006 / Số 56 Nguyễn Thị Bảy, xã Cần Giuộc tỉnh Tây Ninh, Việt Nam

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 1 | Huỳnh Anh Dũng | Đội trưởng | 0916 165 939 |  |  |  |
| 2 | Hồng Bảo Toàn | Đội phó | 0916 446 722 |  |  |  |
| 3 | Phạm Trung Trực | Đội phó | 0949 263 636 |  |  |  |

### ĐỘI QUẢN LÝ ĐIỆN THỦ THỪA - ĐT: 19001006 / Số 5, KDC Bến xe, Khu Phố Thủ Khoa Thừa 2, Xã Thủ Thừa, Tỉnh Tây Ninh

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 1 | Lê Tấn Quốc | Đội trưởng | 0822 101 292 |  |  |  |
| 2 | Nguyễn Thanh Liêm | Đội phó | 0918 128 551 |  |  |  |
| 3 | Huỳnh Văn Triệu | Đội phó | 0963 781 242 |  | Số 78, đường Nguyễn Văn Linh, xã Vĩnh Hưng, tỉnh Tây Ninh |  |

### ĐỘI QUẢN LÝ ĐIỆN KIẾN TƯỜNG - ĐT: 19001006 / số 89 Lý Thường Kiệt Phường Kiến Tường tỉnh Tây Ninh

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 1 | Ngô Hữu Lợi | Đội trưởng | 0857 337 799 |  |  |  |
| 2 | Đặng Thành Thái | Đội phó | 0914 395 501 |  | Đường Thủ Khoa Huân, Xã Tân Hưng, Tỉnh Tây Ninh |  |

### ĐỘI QUẢN LÝ ĐIỆN TẦM VU - ĐT: 19001006 / số 30 Đỗ Tường Phong, xã Tầm Vu, tỉnh Tây Ninh

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 1 | Lương Văn Mão | Đội trưởng | 0948 185 577 |  |  |  |
| 2 | Võ Ngọc Giao | Đội phó | 0916 812 355 |  |  |  |
| 3 | Ngô Hồng Trung | Đội phó | 0918 418 958 |  |  |  |

### ĐỘI QUẢN LÝ ĐIỆN TÂN THẠNH - ĐT: 19001006 / Số 69, Quốc lộ 62, ấp 5, xã Tân Thạnh, tỉnh Tây Ninh

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 1 | Lý Quốc Tâm | Đội trưởng | 0919 380 220 |  |  |  |
| 2 | Phạm Minh Tiền | Đội phó | 0855 999 199 |  |  |  |

### ĐỘI QUẢN LÝ ĐIỆN TÂN TRỤ - ĐT: 19001006 / ấp Tân Bình, xã Tân Trụ, tỉnh Tây Ninh

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 1 | Nguyễn Tuấn Anh | Đội trưởng | 0834 597 799 |  |  |  |
| 2 | Nguyễn Hoàng Nam | Đội phó | 0913 494 647 |  |  |  |

### ĐỘI QUẢN LÝ ĐIỆN CẦN ĐƯỚC - ĐT: 19001006 / Ấp 8 Xã Cần Đước, Tỉnh Tây Ninh

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 1 | Phan Quốc Việt | Đội trưởng | 0945 999 529 |  |  |  |
| 2 | Nguyễn Phạm Hành | Đội phó | 0949 531 958 |  |  |  |
| 3 | Lê Quy Toàn | Đội phó | 0914 947 775 |  |  |  |

### ĐỘI QUẢN LÝ ĐIỆN VĨNH HƯNG - ĐT: 19001006

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 1 | Nguyễn Ngọc Dễ | Đội trưởng | 0963 782 792 |  |  |  |
| 2 | Nguyễn Hữu Hồng | Đội phó | 0914 395 504 |  |  |  |

### ĐỘI QUẢN LÝ ĐIỆN TÂN HƯNG - ĐT: 19001006

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 1 | Võ Quốc Cường | Đội trưởng | 0944 211 254 |  |  |  |
| 2 | Nguyễn Thanh Liêm | Đội phó | 0919 380 440 |  |  |  |

### ĐỘI QUẢN LÝ ĐIỆN ĐỨC HUỆ - ĐT: 19001006 / Số 55A, đường Nguyễn Trung Trực, ấp Thành Đông, xã ĐThành, tỉnh Tây Ninh

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 1 | Nguyễn Minh Thiện | Đội trưởng | 0962 622 999 |  |  |  |
| 2 | Nguyễn Hữu Bạc | Đội phó | 0962 522 368 |  |  |  |

### ĐỘI QUẢN LÝ ĐIỆN THẠNH HÓA - ĐT: 19001006 / Khu Phố 3, xã Thạnh Hóa, Tỉnh Tây Ninh

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 1 | Huỳnh Văn Nguyền | Đội trưởng | 0912 440 479 |  |  |  |
| 2 | Dương Thành Được | Đội phó | 0944 174 797 |  |  |  |

### ĐỘI QUẢN LÝ ĐIỆN TÂN AN - ĐT: 19001006 / số 61/9 A Nguyễn Thái Bình, phường Long An, tỉnh Tây Ninh

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 1 | Nguyễn CLuận | Đội trưởng | 0947 999 801 |  |  |  |
| 2 | Trần Vũ Anh Khoa | Đội phó | 0833 916 879 |  |  |  |
| 3 | Vũ Thị Minh Thiện | Đội phó | 0949 075 939 |  |  |  |

## Các Hội quần chúng, một số Cty

### Cty TNHH MTV 30-4 Tây Ninh

- Nhóm: 1
- Mã/STT nhóm: 1

### HỘI ĐỒNG THÀNH VIÊN (3)

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 1 | Lê Minh Quyền | Thành viên HĐTV | 0909885777 |  |  |  |
| 2 | Nguyễn Văn Mỹ | Thành viên HĐTV | 0903333461 |  |  |  |
| 3 | Phạm Thanh Bình | Thành viên HĐTV | 0933300307 |  |  |  |

### BAN GIÁM ĐỐC (4)

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 1 | Phạm Văn Hải | Giám đốc, TV HĐTV | 0913987108 |  |  |  |
| 2 | Nguyễn Hồng Phúc | Phó Giám đốc | 0918091240 |  |  |  |
| 3 | Phan Thanh Tùng | Phó Giám đốc | 0914368918 |  |  |  |

### Cty TNHH Phát triển xanh Long An / Đ/c: Số 347, Quốc lộ 62, Phường Long An, Tỉnh Tây Ninh / ĐT bàn 02723 838 314 - 02723 821 316 - 02723 829 308; email: phattrienxanhlongan@gmail.com

- Nhóm: 1
- Mã/STT nhóm: 2

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 1 | Huỳnh Văn Nha | Chủ Tịch | 0904 169 722 |  |  |  |
| 2 | Đinh Thị Mỹ Liên | Phó GĐ | 0919 828 439 |  |  |  |
| 3 | Lê Quốc Thịnh | Phó GĐ | 0985 886 993 |  |  |  |
| 4 | Phùng Ngọc Mai | Kế toán trưởng | 0937 347 886 |  |  |  |
| 5 | Võ CThành | Trưởng phòng Tổ chức - Hành chính | 0918 260 304 |  |  |  |
| 6 | Nguyễn Hải Minh Trân | PTP Kế hoạch - Sản xuất kinh doanh | 0949 322 631 |  |  |  |
| 7 | Nguyễn Thị Anh Thư | PTP Kế hoạch - Sản xuất kinh doanh | 0836 972 490 |  |  |  |

### Cty TNHH MTV Khai thác Thủy lợi Tây Ninh - ĐT bàn: 0276.3827380 / Đ/c: Số 211, đường 30/4, phường Tân Ninh, tỉnh Tây Ninh.

- Nhóm: 1
- Mã/STT nhóm: 3

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 1 | Nguyễn Hùng Thắng | Chủ tịch Công ty | 933313777 |  |  |  |
| 2 | Đinh Hùng Danh | Giám đốc Công ty | 982911174 |  |  |  |
| 3 | Bùi Mạnh Toản | Phó Giám đốc Công ty | 907641577 |  |  |  |
| 4 | Nguyễn Thanh Phong | Phó Giám đốc Công ty | 918383992 |  |  |  |
| 5 | Lê Phước Hoàng | Phó Giám đốc Công ty | 919976577 |  |  |  |

### Trường Cao đẳng Long An / Đ/c: Số 60, QL1, phường Long An, tỉnh Tây Ninh / Đt bàn 02723 827 694; email: tcdnla@tayninh.gov.vn; website: https://lac.edu.vn

- Nhóm: 1
- Mã/STT nhóm: 4

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 1 | Lê Quốc Hùng | Bí thư Đảng ủy, Hiệu trưởng | 0919 088 196 |  |  |  |
| 2 | Lê Minh Tâm | Phó Bí thư Đảng ủy, Phó Hiệu trưởng | 0983 030 008 |  |  |  |
| 3 | Đào Văn Hon | UVBCH ĐU,Phó Hiệu trưởng/Giám đốc CS Đức Hòa | 0933 203 072 |  |  |  |
| 4 | Phạm Văn Thịnh | UVBCH ĐU,Phó Hiệu trưởng/Giám đốc CS Bến Lức | 0911 448 846 |  |  |  |
| 5 | Nguyễn Hữu Trí | UVBCH ĐU, Trưởng phòng Tổ chức - Hành chính | 0983 414 072 |  |  |  |
| 6 | Võ Thành Đức | Phó Trưởng phòng Tổ chức - Hành chính | 0948 600 677 |  |  |  |
| 7 | Lê Thị Dung | UVBCH ĐU,Trưởng phòng Công tác HSSV | 0919 639 716 |  |  |  |
| 8 | Đặng Minh Thọ | UVBTV ĐU,Trưởng phòng Kế hoạch - Tài chính | 0938 142 778 |  |  |  |
| 9 | Đặng Thị Cẩm Vân | Phó Trưởng phòng Kế hoạch - Tài chính | 0794 716 085 |  |  |  |
| 10 | Nguyễn Văn Hòa | UVBCH ĐU,Trưởng phòng Đào tạo | 0986 034 349 |  |  |  |
| 11 | Trần Minh Tân | Phó Trưởng phòng Đào tạo | 0939 676 655 |  |  |  |
| 12 | Trần Hồng Nhung | Phó Trưởng phòng Đào tạo | 0949 491 869 |  |  |  |
| 13 | Đỗ Thanh Phong | UVBCH ĐU, Trưởng phòng Thanh tra, khảo thí &BĐCL | 0938 743 479 |  |  |  |
| 14 | Thôi Thanh Đông | Bí thư CB, Giám đốc Trung tâm ĐTLX | 0913 921 772 |  |  |  |
| 15 | Trần Long Điền | Chi ủy viên, Phó Giám đốc Trung tâm ĐTLX | 0938 989 272 |  |  |  |
| 16 | Nguyễn Văn Sơn | Phó BTCB, Phó Giám đốc Trung tâm ĐTLX | 0918 371 555 |  |  |  |
| 17 | Nguyễn Văn Xủng | Chi ủy viên, Phó Giám đốc Cơ sở Đức Hòa | 0908 944 292 |  |  |  |
| 18 | Võ Thị Mai Trâm | Phó BTCB,Phó Giám đốc Cơ sở Đức Hòa | 0703 043 944 |  |  |  |
| 19 | Nguyễn Hoàng Giang | Bí thư CB, Giám đốc Cơ sở Cần Giuộc | 0918 955 225 |  |  |  |
| 20 | Nguyễn Thị Phương Dung | UVBCH ĐU, Phó Giám đốc Cơ sở Cần Giuộc | 0819 456 960 |  |  |  |
| 21 | Trần Văn Tài | UVBCH ĐU, Giám đốc Cơ sở Đồng Tháp Mười | 0916 656 855 |  |  |  |
| 22 | Châu Hải Bằng | Phó BTCB,Phó Giám đốc Cơ sở Bến Lức | 0918 896 222 |  |  |  |

### Trường Cao đẳng Y tế Long An / Đ/c: Số 93, Quốc lộ 62, phường Long An, tỉnh Tây Ninh / ĐT bàn 02723 826349; 02723 828851; Email: tcdyt@tayninh.gov.vn website: caodangytela.edu.vn

- Nhóm: 1
- Mã/STT nhóm: 5

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 1 | Bùi Quốc Dũng | Q.Hiệu trưởng | 0918756867 |  |  |  |
| 2 | Huỳnh Thái Hòa | Phó. Hiệu trưởng | 0918367164 |  |  |  |
| 3 | Trần Thị Kim Duyên | Phụ trách. Phòng ĐT-HTQT | 0934137879 |  |  |  |
| 4 | Trương Thị Kiều Diễm | Phó. Trưởng phòng TCHC | 0945 944 666 |  |  |  |
| 5 | Phạm Thị Gái Loan | Kế toán trưởng | 0164 7 427 828 |  |  |  |
| 6 | Nguyễn Minh Thành | Phó. Trưởng khoa Điều dưởng | 0918 677 288 |  |  |  |
| 7 | Võ Văn Trọng | Phó. Trưởng khoa Dược | 0983 099 737 |  |  |  |

### Trường Cao đẳng nghề Tây Ninh / Địa chỉ: Số 019, đường Võ Thị Sáu, khu phố 7, phường Tân Ninh, tỉnh Tây Ninh / ĐT: 02763 822 438 - 02763 815 480; Email: caodangnghe.tn@gmail.com; / Website: http://cdnghetayninh.edu.vn/

- Nhóm: 1
- Mã/STT nhóm: 6

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 1 | Châu Thành Trọng | Hiệu trưởng | 0914 276 889 | 3814 393 |  |  |
| 2 | Lê Thị Thu Thảo | Phó Hiệu trưởng | 0918 203 346 | 3815 479 |  |  |
| 3 | Nguyễn Thành Thiện | Trưởng phòng TCHC | 0364 981 197 |  |  |  |
| 4 | Ngô Phương Ý | Trưởng phòng Đào tạo | 0912 024 755 |  |  |  |
| 5 | Nguyễn Thái Hà | Phụ trách phòng CTHSSV | 0988 216 114 |  |  |  |
| 6 | Đặng Văn Của | Phụ trách phòng NCKH-TTSX | 0905 256 395 |  |  |  |
| 7 | Nguyễn Tấn Khương | Phó trưởng phòng TCHC | 0984 515 153 |  |  |  |

### Hội Văn học nghệ thuật tỉnh - ĐT bàn: 02723 838 165 / Đ/c: Số 44 Nguyễn Huệ, phường Long An, Tây Ninh

- Nhóm: 1
- Mã/STT nhóm: 7

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 1 | Nguyễn Tấn Quốc | Chủ tịch | 0918 518 918 |  |  |  |
| 2 | Nguyễn Lành | Phó chủ tịch | 0909 196 215 |  |  |  |
| 3 | Nguyễn Văn Chiểu | Phó chủ tịch | 0913 876 220 |  |  |  |

### LIÊN MINH HỢP TÁC XÃ TỈNH TÂY NINH - Quỹ Hỗ trợ Phát triển Hợp tác xã tỉnh Tây Ninh / Đ/c: 23 Phan Chu Trinh, khu phố 16, phường Tân Ninh, tỉnh Tây Ninh / ĐT bàn 02763 824 002; Email: tayninh@vca org vn

- Nhóm: 1
- Mã/STT nhóm: 8

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 1 | La Hữu Nghị | Chủ tịch | 0913 955 080 | 02763 825 498 |  |  |
| 2 | Nguyễn Hữu Thuận | CVP | 0909 626 210 | 02763 824 002 |  |  |
| 3 | Lâm Bảo Trân | Phó CVP | 0909 190 949 | 02763 824 002 |  |  |
| 4 | Lê Văn Tuyển | TP KH hỗ trợ | 0938 909 070 | 02763 628 777 |  |  |
| 5 | Vương Thị Kim Hồng | P TP KH hỗ trợ | 0947 800 990 | 02763 628 777 |  |  |
| 6 | Pham Văn Mặn | TP Tổ chức PT và CS PT HTX | 0938 909 098 | 02763 813 189 |  |  |
| 7 | Lê Thị Hồng Nhung | PTP Tổ chức PT và CS PT HTX | 0908 533 722 | 2763 813 189 |  |  |
| 8 | Nguyễn Hữu Tính | TB kiểm tra | 0908 033 819 |  |  |  |

### Các Xã, Phường

- Nhóm: 1

### PHƯỜNG LONG AN

- Nhóm: 1
- Mã/STT nhóm: 1

### Đảng ủy - Số 90, đường Bạch Đằng, phường Long An

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 1 | Lê Công Đỉnh | UV BTVTU, BT Đảng ủy, CT HĐND | 0918 239 439 | 02723 821 889 |  |  |
| 2 | Nguyễn Thị Hoa | Phó Bí thư Thường trực Đảng uỷ | 0919 916 272 | 02723 839 917 |  |  |
| 3 | Nguyễn Duy Linh | UV BTV - TB xây dựng Đảng | 0942 221 569 | 02723 826 197 |  |  |
| 4 | Huỳnh Thị Thùy Linh | ĐUV - PTB Xây dựng Đảng | 0845 621 905 | 02723 832 600 |  |  |
| 5 | Trần Văn Bình | UV BTV - CN UBKT | 0913 999 967 | 02723 822 368 |  |  |
| 6 | Lê Thị Hồng Diễm | ĐUV - PCN UBKT | 0909 785 994 |  |  |  |
| 7 | Nguyễn Thị Bích Thùy | ĐUV - CVP Đảng uỷ | 0976 924 763 | 02723 831 509 |  |  |
| 8 | Trần Thị Thu Sương | ĐUV - GĐ TT chính trị | 0908 621 881 | 02723 839 944 |  |  |

## Mặt trận Tổ quốc - Số 540, QL62, phường Long An

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 9 | Hà Ngọc Diệp | UV BTV - Chủ tịch UBMTTQ | 0989 968 472 |  |  |  |
| 10 | Trần Thị Phương Uyên | ĐUV - PCT MTTQ, CT Hội LHPN | 0977 371 919 |  |  |  |
| 11 | Ngô Thanh Hùng | ĐUV - PCTMTTQ, CT Hội ND | 0383 882 336 |  |  |  |
| 12 | Nguyễn Thái Nhân | ĐUV - PCT MTTQ, Bí thư Đoàn TN | 0977 794 675 |  |  |  |

### Hội đồng nhân dân - Số 76, đường Hùng Vương, phường Long An

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 14 | Hồ Phong Vũ | UV BTV, PCT HĐND, / kiêm TB Kinh tế - Ngân sách | 0983 040 501 | 02723 524 201 |  |  |
| 15 | Nguyễn Thị Thu Hường | ĐUV, PTB Kinh tế - Ngân sách | 0397 797 998 | 02723 826 706 |  |  |
| 16 | Nguyễn Văn Truyền | Phó TB Văn hóa - Xã hội | 0983 966 309 | 02723 826 706 |  |  |

### Ủy ban nhân dân - ĐT bàn 02723 826 198; email: ubndplongan@tayninh.gov.vn; Website: https://longan.tayninh.gov.vn.

### Số 76, đường Hùng Vương, phường Long An

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 17 | Võ Hồng Thảo | PBT Đảng uỷ - Chủ tịch UBND | 0945 674 848 | 02723 667 939 |  |  |
| 18 | Trịnh Đăng Khoa | UV BTV - PCT UBND | 0919 124 676 | 02723 823 430 |  |  |
| 19 | Huỳnh Thị Diễm Lệ | UV BTV - PCT UBND | 0855 474 379 | 02723 525 329 |  |  |
| 20 | Võ Thị Thanh Hằng | ĐUV - CVP HĐND và UBND | 0942 727 405 | 02723 838 571 |  |  |
| 21 | Nguyễn Quốc Trinh | Phó CVP HĐND và UBND | 0986 960 016 | 02723 829 332 |  |  |
| 22 | Phạm Thành Tài | ĐUV - TP Kinh tế, Hạ tầng và Đô thị | 0913 430 012 |  |  |  |
| 23 | Nguyễn Phúc Toàn | Phó TP Kinh tế, Hạ tầng và Đô thị | 0916 487 139 |  |  |  |
| 24 | Nguyễn Thị Kim Lưu | ĐUV, TP Văn hoá - Xã hội | 0902 325 894 |  |  |  |
| 25 | Nguyễn Tây Giang | Phó TP Văn hóa - Xã hội | 0869 154 954 |  |  |  |
| 26 | Nguyễn Hoài Phương | PGĐ TT phục vụ Hành chính công | 0842 579 338 |  |  |  |
| 27 | Nguyễn Thị Mộng Trinh | ĐUV - GĐ TT cung ứng dịch vụ / sự nghiệp công / Số 42, đường Võ Văn Tần | 0937 214 720 | 02723 826 492 |  |  |
| 28 | Nguyễn Hồng Anh | PGĐ TT cung ứng DV sự nghiệp công | 0918 599 513 | 02723 837 681 |  |  |
| 29 | Võ Văn Hết | UV BTV - Trưởng Công an / Đc: Số 01, đường Hồ Văn Long | 0919 332 435 | 02723 826 303 / 02723 826 294 |  |  |
| 30 | Đỗ Thành Tài | ĐUV - Phó Trưởng Công an | 0918 976 498 | 02723 826 294 / 02723 826 303 |  |  |
| 31 | Nguyễn Thái Bình | UV BTV - CHT BCH Quân sự / Số 471, đường Nguyễn Đình Chiểu | 0911 414 414 | 02723 826 319 |  |  |
| 32 | Nguyễn Thanh Tùng | ĐUV - Phó CHT BCH Quân sự | 0915 675 499 | 02723 826 319 |  |  |
| 33 | Trần Anh Tuấn | ĐUV, HT Trường THCS Lý Tự Trọng | 0918 593 614 | 02723 829 843 |  |  |
| 34 | Nguyễn Thị Hương Giang | ĐUV, HT Trường Mầm non 1-6 | 0948 969 694 | 02723 829 343 |  |  |

### PHƯỜNG TÂN AN

- Nhóm: 1
- Mã/STT nhóm: 2

### Khối Đảng, MTTQ _ ĐT: 02723 939 829 (Đảng ủy phường)

### Địa chỉ: 349 Châu Thị Kim

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 1 | Nguyễn Anh Việt | Bí thư Đảng ủy | 0941 681 828 |  |  |  |
| 2 | Lê Thị Thúy Loan | UV BTV - TB Xây dựng Đảng | 0918 609 629 |  |  |  |
| 3 | Nguyễn Quang Hải | ĐUV - PTB Xây dựng Đảng | 0983 046 363 |  |  |  |
| 4 | Nguyễn Thái Bình | UV BTV - CN UBKT | 0983 014 462 |  |  |  |
| 5 | Trần Thị Kim Hoàng | ĐUV - Phó CN UBKT | 0917 676 964 |  |  |  |
| 6 | Nguyễn Chí Tâm | UV BTV - Chủ tịch UBMTTQ | 0943 272 961 |  |  |  |
| 7 | Huỳnh Thị Ngọc Hương | ĐUV - PCT MTTQ - CT Cđoàn, / CT Hội Ndân | 0907 665 003 |  |  |  |
| 8 | Lê Trung Chiến | ĐUV - PCT MTTQ - BT Đoàn TN | 0388 114 606 |  |  |  |
| 9 | Võ Hoàng Tân | ĐUV - CVP Đảng ủy | 0902 622 939 |  |  |  |

### Khối Hội đồng nhân dân - Địa chỉ: 349 Châu Thị Kim

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 10 | Nguyễn Thị Ngọc Dư | Phó Bí thư - CT HĐND | 0918 623 211 |  |  |  |
| 11 | Phan Thanh Bình | UV BTV - PCT HĐND | 0909 733 911 |  |  |  |
| 12 | Phạm Hoàng Tuấn Khanh | ĐUV - PTB Kinh tế - Ngân sách | 0911 616 839 |  |  |  |
| 13 | Lê Thị Phương Quyên | ĐUV - PTB Văn hóa - Xã hội | 0987 921 446 |  |  |  |

### Khối Chính quyền và các cơ quan; ĐT 02723 829 202 (UBND phường)

### Mail: ubndtanan@longan.gov.vn _ Website: https://tanan.tayninh.gov.vn/

### Địa chỉ: 468 Nguyễn Thông

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 14 | Lê Văn Thảo | Phó Bí thư - CT UBND | 0983 045 056 |  |  |  |
| 15 | Nguyễn Thị Kim Phụng | UV BTV - PCT UBND | 0854 953 968 |  |  |  |
| 16 | Nguyễn Thanh Phúc | UV BTV - PCT UBND | 0327 359 459 |  |  |  |
| 17 | Đoàn Thị Ngọc Thảo | ĐUV - CVP HĐND và UBND | 0978 656 016 |  |  |  |
| 18 | Bùi Đức Quốc | PCVP HĐND và UBND | 0919 883 574 |  |  |  |
| 19 | Trần Văn Khiêm | ĐUV - TP Kinh tế, Hạ tầng và Đô thị | 0916 969 307 |  |  |  |
| 20 | Trần Quốc Nghĩa | PTP Kinh tế, Hạ tầng và Đô thị | 0977 096 497 |  |  |  |
| 21 | Nguyễn Hoàng Phi | ĐUV - TP Văn hóa - Xã hội | 0946 547 386 |  |  |  |
| 22 | Phạm Nguyên Mai Khanh | PTP Văn hóa - Xã hội | 0938 515 644 |  |  |  |
| 23 | Nguyễn Minh Thiện | ĐUV - PGĐ TT Phục vụ HC công | 0857 788 729 |  |  |  |
| 24 | Hồ Thanh Phong | GĐ TT cung ứng DVSN sự nghiệp công | 0983 754 965 |  |  |  |
| 25 | Nguyễn Phương Quang | PGĐ TT cung ứng DVSN công | 0973 318 319 |  |  |  |
| 26 | Hồ Thị Kim Anh | Trưởng Trạm Y tế | 0333 878 645 |  |  |  |
| 27 | Võ Thị Thùy Duyên | Phó trưởng Trạm Y tế | 0359 759 037 |  |  |  |
| 28 | Phạm CKhanh | UV BTV - Trưởng Công an | 0918 700 129 |  |  |  |
| 29 | Nguyễn Hồng Phong | ĐUV - Phó Trưởng Công an | 0913 678 345 |  |  |  |
| 30 | Lê Quốc Việt | UV BTV - CHT BCH Quân sự | 0943 650 079 |  |  |  |
| 31 | Lê Minh Phương | ĐUV - Phó CHT BCH Quân sự | 0392 648 706 |  |  |  |

### PHƯỜNG KHÁNH HẬU

- Nhóm: 1
- Mã/STT nhóm: 3

### Đảng ủy phường Khánh Hậu

### Địa chỉ: 177 Đường Hoàng Anh khu phố Thủ Tửu 2, phường Khánh Hậu

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 1 | Nguyễn Việt Cường | Bí thư | 0911 360 999 | 0272 3681 777 |  |  |
| 2 | Nguyễn Ngọc Sang | Phó Bí thư | 0917 752 800 |  |  |  |
| 3 | Lữ Văn Khởi | UV BTV - CN UBKT | 0918 898 259 |  |  |  |
| 4 | Mai Hùng Vương | UV BCH - Phó CN UBKT | 0972 823 007 |  |  |  |
| 5 | Nguyễn Thị Thu Hiền | UV BTV - TB Xây dựng đảng | 0937 424 462 |  |  |  |
| 6 | Nguyễn Thanh Sơn | UV BCH - PTB Xây dựng đảng | 0937 939 884 |  |  |  |
| 7 | Lê Thị Ngọc Thuận | UV BCH - CVP Đảng ủy | 0394 323 160 |  |  |  |
| 8 | Mai Thị Xuân Phương | UV BTV - CT MTTQ | 0918 057 172 |  |  |  |
| 9 | Lương Ngọc Hạnh | UV BCH - PCT MTTQ, CT Hội LHPN | 0707 327 225 |  |  |  |
| 10 | Nguyễn Thế Vinh | UV BCH - PCT MTTQ, BT Đoàn TN | 0941 172 931 |  |  |  |

### HĐND phường Khánh Hậu - Địa chỉ: 337 Nguyễn Huỳnh Đức, Phường Khánh Hậu

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 13 | Nguyễn Ngọc Sang | Phó Bí thư - CT HĐND | 0917 752 800 |  |  |  |
| 14 | Mai Thanh Trúc | Ban Kinh tế - HĐND | 0972 820 716 |  |  |  |
| 15 | Mai Thị Xuân Phương | Ban VHXH - HĐND | 0918 057 172 |  |  |  |

### UBND phường Khánh Hậu - ĐT bàn: 02723580116

### mail: ubnd.khanhhau@tayninh.gov.vn

### Địa chỉ: 337 Nguyễn Huỳnh Đức, Phường Khánh Hậu

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 16 | Nguyễn Quốc Cường | Phó Bí thư - CT UBND | 0983 896 232 |  |  |  |
| 17 | Lương CĐức | Ủy viên BTV Đảng ủy - PCT UBND | 0918 616 679 |  |  |  |
| 18 | Hồ Thị Hạnh | Ủy viên BTV Đảng ủy- PCT UBND | 0907 938 399 |  |  |  |
| 19 | Nguyễn Hữu Phúc | Đảng ủy viên - CVP HĐND và UBND | 0907 400 989 |  |  |  |
| 20 | Nguyễn Thị Tuyết Hiếu | PCVP HĐND và UBND | 0919 825 655 |  |  |  |
| 21 | Ngô Hoàng Trí | - TP Kinh tế | 0942 626 287 |  |  |  |
| 22 | Huỳnh Thị Minh Thảo | PTP Kinh tế | 0946 674 539 |  |  |  |
| 23 | Huỳnh Thị Bạch Lan | Đảng ủy viên - TP Văn hóa - Xã Hội | 0907 952 007 |  |  |  |
| 24 | Lê CKhanh | PTP Văn hóa - Xã Hội | 0949 882 952 |  |  |  |
| 25 | Hồ Thị Hạnh | GĐ TT Hành chính công | 0907 938 399 |  |  |  |
| 26 | Võ Văn Thang | PGĐ TT Hành chính công | 0383 644 579 |  |  |  |
| 27 | Nguyễn Trung Tín | GĐ TT Cung ứng DVSN công / Địa chỉ: | 0909 767 271 |  |  |  |
| 28 | Nguyễn Hữu Lợi | PGĐ TT Cung ứng DVSN công | 0847 522 236 |  |  |  |
| 29 | Châu Thanh Hùng | Đảng ủy viên - Trưởng Công an / Địa chỉ: | 0919 596 727 |  |  |  |
| 30 | Nguyễn Thanh Bình | Phó trưởng Công an | 0913 999 747 |  |  |  |
| 31 | Nguyễn Hữu Lợi | UV BTV - CHT BCH Quân sự / Địa chỉ | 0364 504 699 |  |  |  |

### PHƯỜNG KIẾN TƯỜNG

- Nhóm: 1
- Mã/STT nhóm: 4

### Đảng ủy phường

### Địa chỉ: số 16, đường 30/4

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 1 | Lê Thanh Đông | Bí thư | 0906 303 969 |  |  |  |
| 2 | Võ Thị Thu Duyên | Phó Bí thư thường trực - CT HBND phường | 0854 346 946 |  |  |  |
| 3 | Ngô Thị Nguyệt | UV BTV - CN UBKT ĐU phường | 0918 220 125 |  |  |  |
| 4 | Đoàn Thị Hoài Thương | UV BCH - Phó CN UBKTĐU phường | 0833 800 005 |  |  |  |
| 5 | Lê Minh Dũng | UV BTV - TB Xây dựng đảng | 0909 380 125 |  |  |  |
| 6 | Mai Thị Hồng Nhiên | UV BCH - PTB Xây dựng đảng | 0773 858 977 |  |  |  |
| 7 | Đoàn Thị Hờ | UV BCH - CVP Đảng ủy phường | 0906 782 600 |  |  |  |
| 8 | Nguyễn Thị Ngọc Dung | UV BTV - CT MTTQ phường | 0918 895 532 |  |  |  |
| 9 | Nguyễn Hoàng Minh Hiếu | UV BCH - PCT MTTQ, CT Hội LHPN phường | 0827 667 797 |  |  |  |
| 10 | Đặng Thị Duyên | UV BCH - PCT MTTQ, CT Hội nông dân phường | 0855 999 898 |  |  |  |
| 11 | Nguyễn Thị Vân Anh | UV BCH - PCT MTTQ, BT Đoàn TN | 0826 343 272 |  |  |  |
| 12 | Nguyễn Trọng Sáu | UV BCH - PCT MTTQ, CT Hội CCB phường | 0918 589 653 |  |  |  |

### Hội đồng nhân dân phường - Địa chỉ:số 12, đường 30/4

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 13 | Văn Thị Mỹ Yên | UV BTV - Phó CT HĐND | 0395 053 668 |  |  |  |
| 14 | Nguyễn Thị Phương Nhã | UV BCH - Phó Ban Kinh tế - HĐND | 091 557 3990 |  |  |  |
| 15 | Tăng Thị Như Phương | UV BCH - Phó Ban VHXH - HĐND | 083 399 8002 |  |  |  |

### Ủy ban nhân dân phường - ĐT bàn: 0272.3.841.981 ; email: ubndkientuong.@tayninh.gov.vn

### Địa chỉ:số 12, đường 30/4

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 16 | La Văn Dân | Phó Bí thư - CT UBND | 0918 701 586 |  |  |  |
| 17 | Huỳnh Thanh Vinh | UV BTV - PCT UBND | 0986 501 617 |  |  |  |
| 18 | Lê Tấn Lộc | UVBTV - PCT UBND - GĐ TT HÀNH CHÍNH CÔNG | 0918 288 775 |  |  |  |
| 19 | Nguyễn Thị Thanh Nhàn | UV BCH - CVP HĐND và UBND phường | 0944 461 846 |  |  |  |
| 20 | Phạm Văn Kha | PCVP HĐND và UBND | 0918 895 550 |  |  |  |
| 21 | Nguyễn Thị Thúy Hằng | UV BCH - Trưởng phòng kinh tế | 0814 183 183 |  |  |  |
| 22 | Phạm Thị Ngọc Bích | Phó Trưởng phòng kinh tế | 0974 895 125 |  |  |  |
| 23 | Nguyễn Văn Nghĩa | UV BCH - TP Văn hóa - Xã hội | 0903 161 229 |  |  |  |
| 24 | Phạm Thị Hồng Nhung | PTP Văn hóa - Xã hội | 0916 685 972 |  |  |  |
| 25 | Trương Mỹ Thanh | UV BCH- PGĐ TT Hành chính công | 0949 024 547 |  |  |  |
| 26 | Trần Toại Nguyện | GĐ TT Cung ứng DVSN công | 0886 789 337 |  |  |  |
| 27 | Nguyễn Thanh Sồi | UV BTV - Trưởng Công an phường | 0889 740 357 |  |  |  |
| 28 | Thái Toàn Thắng | ĐUV - Phó Trưởng công an phường | 0942 232 626 |  |  |  |
| 29 | Nguyễn Văn Khánh | UVBTV - CHT BCH Quân sự phường | 0941 679 400 |  |  |  |
| 30 | Lê Ngọc Hiếu | ĐUV - Phó CHT BCH Quân sự phường | 0918 891 734 |  |  |  |
| 31 | Hồ Thị Kiều Diễm | Trưởng trạm y tế phường | 0984 445 576 |  |  |  |

### PHƯỜNG THANH ĐIỀN

- Nhóm: 1
- Mã/STT nhóm: 5

### Đảng ủy phường - Địa chỉ: Số 381, đường Phạm Văn Đồng

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 1 | Nguyễn Thị Kim Quyên | Bí thư - Chủ tịch HĐND phường | 0913 846 644 |  |  |  |
| 2 | Phan Thị Thùy Dương | Phó Bí thư - CT MTTQ xã | 0919 489 012 |  |  |  |
| 3 | Nguyễn Chí Trung | UV BTV - CN UBKT | 0973 275 435 |  |  |  |
| 4 | La Thanh Hiền | UV BCH - PCN UBKT | 0979 713 138 |  |  |  |
| 5 | Lương Thị Ngọc Thanh | UV BTV - TB Xây dựng đảng | 0909 991 518 |  |  |  |
| 6 | Trần Thị Kim Nhanh | UV BCH - PTB Xây dựng đảng | 0979 721 249 |  |  |  |
| 7 | Nguyễn Thị Lan Phương | UV BCH - CVP Đảng ủy | 0909 878 077 |  |  |  |
| 8 | Đinh Thị Loan Phương | UV BCH - PCT MTTQ, CT Hội PN | 0919 767 157 |  |  |  |
| 9 | Lưu Thị Tuyết Mai | UV BCH - PCT MTTQ, CT Hội ND | 0934 139 160 |  |  |  |
| 10 | Bùi Huỳnh Băng Sơn | UV BCH - PCT MTTQ, BT Đoàn TN | 0973 740 707 |  |  |  |
| 11 | Lê Thị Xuân Thu | UV BCH - PCT MTTQ phụ trách Cđoàn | 0983 119 964 |  |  |  |
| 12 | Nguyễn Hữu Tài | PCT MTTQ phụ trách CCB | 0988 916 616 |  |  |  |
| 13 | Nguyễn Thị Thu Hà | PCN UBKT Đảng ủy | 0909 783 728 |  |  |  |
| 14 | Nguyễn Huỳnh Lợi | PTB Xây dựng Đảng | 0906 785 575 |  |  |  |
| 15 | Thái Thanh Triển | Phó CVP Đảng ủy | 0938 356 311 |  |  |  |
| 16 | Trang Lê Huynh | Phó CVP Đảng ủy | 0917 822 503 |  |  |  |

### Hội đồng nhân dân

### Địa chỉ: Số 18, hẻm số 10, đường số 6, đường Lạc Long Quân

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 17 | Trần Phi Hùng | Ủy viên BTV - PCT HĐND | 0932 064 081 |  |  |  |
| 18 | Ngô Thị Thùy Dương | Ban Kinh tế - HĐND | 0987 407 901 |  |  |  |
| 19 | Phan Thị Phương Yến | Ban VHXH - HĐND | 0933 995 661 |  |  |  |

### Ủy ban nhân dân ; email: ubndthanhdien@tayninh.gov.vn

### Địa chỉ: Số 18, hẻm số 10, đường số 6, đường Lạc Long Quân

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 20 | Nguyễn Trí Cường | Phó Bí thư - CT UBND | 0916 061 212 |  |  |  |
| 21 | Trần Thiện Thanh | Ủy viên BTV - PCT UBND - GĐ TT Hành chính công | 0918 585 875 |  |  |  |
| 22 | Đặng Thanh Xuân | Ủy viên BCH - PCT UBND | 0917 999 883 |  |  |  |
| 23 | Trần Trọng Duy | UV BCH - Chánh VP HĐND - UBND | 0975 438 443 |  |  |  |
| 24 | Phạm Hùng Sơn | PCVP HĐND và UBND | 0937 943 949 |  |  |  |
| 25 | Đỗ Hoàng Hải Đăng | Ủy viên BCH - Trưởng phòng Kinh tế, Hạ tầng và Đô thị | 0975 487 087 |  |  |  |
| 26 | Lâm Thanh Bình | PTP Kinh tế, Hạ tầng và Đô thị | 0987 290 779 |  |  |  |
| 27 | Lâm Tiến Thành | Ủy viên BCH - TP Văn hóa - Xã hội | 0978 880 835 |  |  |  |
| 28 | Nguyễn Quốc Hoàn | PTP Văn hóa - Xã hội | 0917 499 535 |  |  |  |
| 29 | Tô Đình Hương Yri | PTP Văn hóa - Xã hội | 0943 098 681 |  |  |  |
| 30 | Võ Kiên Trung | PGĐ TT Hành chính công | 0987 201 170 |  |  |  |
| 31 | Huỳnh Minh Tân | GĐ TT Cung ứng DVSN công | 0907 585 051 |  |  |  |
| 32 | Trần Minh Trâm | PGĐ TT Cung ứng DVSN công | 0903 685 719 |  |  |  |
| 33 | Nguyễn Khánh Ly | UV BTV - Trưởng Công an | 0918 490 888 |  |  |  |
| 34 | Nguyễn Kim Lệ Thy | UV BCH - Phó Trưởng Công an | 0983 884 616 |  |  |  |
| 35 | Hà Minh Chệnh | Phó Trưởng Công an | 0933 909 224 |  |  |  |
| 36 | Võ Hoàng Ẩn | Phó Trưởng Công an | 0913 107 789 |  |  |  |
| 37 | Phan Thị Trúc Linh | Phó Trưởng Công an | 0903 041 083 |  |  |  |
| 38 | Đặng Thanh Ngân | Phó Trưởng Công an | 0911 421 412 |  |  |  |
| 39 | Trần Thanh Xuân | Ủy viên BTV - CHT BCH Quân sự | 0985 201 450 |  |  |  |
| 40 | Đoàn Linh Tâm | Phó chỉ huy TB CHQS | 0367 491 492 |  |  |  |

### PHƯỜNG HÒA THÀNH

- Nhóm: 1
- Mã/STT nhóm: 6

### Đảng ủy phường

### Địa chỉ: 606 Quốc lộ 22B, khu phố Long Yên

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 1 | Dương Quốc Khánh | Bí thư Đảng ủy, CT. HĐND phường | 916485486 |  |  |  |
| 2 | Nguyễn Ngọc Ánh | Phó Bí thư | 909232970 |  |  |  |
| 3 | Nguyễn Thị Thanh Thúy | UV BTV - CN UBKT | 919190212 |  |  |  |
| 4 | Cao Tấn Kiệt | UV BCH - PCN UBKT | 905352550 |  |  |  |
| 5 | Ngô Thị Kim Hiếu | UV BTV - TB Xây dựng đảng | 909887550 |  |  |  |
| 6 | Phạm Thị Ánh Nguyệt | UV BCH - PTB Xây dựng đảng | 913671184 |  |  |  |
| 7 | Nguyễn Thành Lộc | UV BCH - CVP Đảng ủy | 918747852 |  |  |  |
| 8 | Nguyễn Ngọc Ánh | Phó Bí thư Đảng ủy - CT MTTQ xã | 909232970 |  |  |  |
| 9 | Điền Thị Hoàng Oanh | UV BCH - PCT MTTQ, CT Hội PN | 919594877 |  |  |  |
| 10 | Nguyễn Thị Hoàng Oanh | UV BCH - PCT MTTQ, CT Hội ND | 917697858 |  |  |  |
| 11 | Cao Hồng Thảo | UV BCH - PCT MTTQ, BT Đoàn TN | 372011881 |  |  |  |
| 12 | Tô Hiền Đức | UV BCH - PCT MTTQ, CT Hội CCB | 983159365 |  |  |  |

### Hội đồng nhân dân

### Địa chỉ: Số 18, đường 31 Phạm Hùng, khu phố Long Chí

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 13 | Lê Huỳnh Hải Đăng | UV BTV - Phó CT HĐND | 908887810 |  |  |  |
| 14 | Nguyễn Thành An | Phó Ban Kinh tế - HĐND | 946301404 |  |  |  |
| 15 | Nguyễn Thành Huy | Phó Ban VHXH - HĐND | 912995653 |  |  |  |

### Ủy ban nhân dân; email: ubndhoathanh@tayninh.gov.vn

### Địa chỉ: Số 18, đường 31 Phạm Hùng, khu phố Long Chí

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 16 | Nguyễn Đức Hảo | Phó Bí thư - CT UBND | 918623114 |  |  |  |
| 17 | Võ Thị Hạnh | Thường vụ Đảng ủy - PCT UBND | 366672337 |  |  |  |
| 18 | Nguyễn Hoàng Sơn | Thường vụ Đảng ủy - PCT UBND | 919270185 |  |  |  |
| 19 | Tô Thanh Tú | ĐUV - CVP HĐND và UBND phường | 919030908 |  |  |  |
| 20 | Nguyễn Hồng Mai | PCVP HĐND và UBND phường | 344043499 |  |  |  |
| 21 | Nguyễn Thành Giáp | Đảng ủy viên - TP Kinh tế | 937072470 |  |  |  |
| 22 | Mai Huy Phương | PTP Kinh tế | 978782001 |  |  |  |
| 23 | Châu Thị Bích Hiền | Đảng ủy viên - TP Văn hóa - Xã hội | 908513387 |  |  |  |
| 24 | Lê Lô Ril | PTP Văn hóa - Xã hội | 344739555 |  |  |  |
| 25 | Võ Thị Hạnh | GĐ TT Hành chính công | 366672337 |  |  |  |
| 26 | Mai Thị Ngọc Huệ | PGĐ TT Hành chính công | 933279925 |  |  |  |
| 27 | Nguyễn Thanh Tâm | GĐ TT Cung ứng DVSN công | 907623205 |  |  |  |
| 28 | Trần Thị Bích Ngọc | PGĐ TT Cung ứng DVSN công | 979220494 |  |  |  |
| 29 | Trần Thị Ngọc Truyến | UV BTV - Trưởng Công an | 918800057 |  |  |  |
| 30 | Huỳnh Xuân Diễm | Phó Trưởng Công an | 946455556 |  |  |  |
| 31 | Nguyễn Hải Trung | Phó Trưởng Công an | 918821373 |  |  |  |
| 32 | Phạm Trung Kiên | Phó Trưởng Công an | 971221227 |  |  |  |
| 33 | Huỳnh Văn Thòn | Phó Trưởng Công an | 916847576 |  |  |  |
| 34 | Phan Thanh Huấn | Phó Trưởng Công an | 911222248 |  |  |  |
| 35 | La Thanh Hải | UV BTV - CHT BCH Quân sự phường | 974540321 |  |  |  |

### PHƯỜNG LONG HOA

- Nhóm: 1
- Mã/STT nhóm: 7

### ĐẢNG UỶ PHƯỜNG ĐT bàn 02723 622 122; Email:danguylonghoa@tayninh.dcs.vn

### UBND PHƯỜNG ĐT bàn: 02763 841 238; Email: ubndplonghoa@tayninh.gov.vn

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 1 | Nguyễn Thị Thu Hiền | Bí thư - Chủ tịch HĐND | 0911 829 888 |  |  |  |
| 2 | Huỳnh CLuận | Phó Bí thư - Thường trực ĐU | 0918 757 011 |  |  |  |
| 3 | Lê Minh Vương | TVĐU, TB Xây dựng Đảng | 0937 482 843 |  |  |  |
| 4 | Nguyễn Thế Xuân | TVĐU, CN UBKT | 0962 882 353 |  |  |  |
| 5 | Nguyễn Thu | TVĐU, Chủ tịch MTTQ | 0987 522 251 |  |  |  |
| 6 | Nguyễn Hữu Huy | TVĐU, PCT HĐND | 0938 747 232 |  |  |  |
| 7 | Nguyễn Quốc Cường | TVĐU, Phó Bí thư - CT UBND | 0988 414 844 |  |  |  |
| 8 | Nguyễn Hữu Vinh | TVĐU, PCT UBND phường / GĐ TT Phục vụ Hành chính công | 0909 476 612 |  |  |  |
| 9 | Trần Trung Hiếu | TVĐU, PCT UBND | 0902 919 637 |  |  |  |
| 10 | Nguyễn Trung Thái | TVĐU, Trưởng Công an | 0918 540 840 |  |  |  |
| 11 | Tô Ni | TVĐU, CHT BCH Quân sự | 0967 666 890 |  |  |  |
| 12 | Trần Thuý Oanh | Phó CN UBKT Đảng uỷ | 0363 705 597 |  |  |  |
| 13 | Nguyễn Minh Phúc | PTB XDĐ | 0973 322 657 |  |  |  |
| 14 | Nguyễn Duy Hiếu | GĐ TT chính trị | 0975 488 505 |  |  |  |
| 15 | Lê Minh Tiến | CVP Đảng uỷ | 0352 813 272 |  |  |  |
| 16 | Phan Thị Kim Phướng | Phó Ban Kinh tế – Ngân sách HĐND | 0935 447 003 |  |  |  |
| 17 | Nguyễn Hoài Vi | Phó Ban Văn hóa - Xã hội HĐND | 0908 061 077 |  |  |  |
| 18 | Trần Thị Bích Dung | CVP HĐND-UBND | 0937 195 523 |  |  |  |
| 19 | Trần Hồng Quân | PCVP HĐND-Ủy ban nhân dân | 0949 576 576 |  |  |  |
| 20 | Nguyễn Trần Thanh Sơn | PGĐ TT phục vụ Hành chính công | 0946 949 266 |  |  |  |
| 21 | Phạm Thị Kim Anh | PGĐ TT phục vụ Hành chính công | 0917 275 604 |  |  |  |
| 22 | Nguyễn Trung Hiếu | Trưởng phòng Kinh tế, Hạ tầng và Đô thị | 0949 478 887 |  |  |  |
| 23 | Cao Long Đỉnh | PTP Kinh tế, Hạ tầng và Đô thị | 0982 828 757 |  |  |  |
| 24 | Nguyễn Hoàng Nhã Trúc | Trưởng phòng Văn hóa - Xã hội | 0949 110 551 |  |  |  |
| 25 | Lâm Thị Mỹ Huyên | PTP Văn hóa - Xã hội | 0968 438 979 |  |  |  |
| 26 | Lê Anh Ngữ | Phó CT MTTQ - Bí thư ĐTN | 0983 353 387 |  |  |  |
| 27 | Nguyễn Thuỵ Nhã Trúc | Phó CT MTTQ - CT Hội PN | 0937 242 023 |  |  |  |
| 28 | Nguyễn Hữu Phúc | Phó CT MTTQ - CT Hội ND | 0974 567 568 |  |  |  |
| 29 | Lê Thị Thanh Phương | Phó CT MTTQ - Chủ tịch Cđoàn | 0946 788 488 |  |  |  |
| 30 | Nguyễn Hồng Phương | Phó Trưởng Công an | 0909 888 720 |  |  |  |

### PHƯỜNG TÂN NINH

- Nhóm: 1
- Mã/STT nhóm: 8

### Đảng ủy phường Tân Ninh

### Địa chỉ: 019 Nguyễn Chí Thanh, phường Tân Ninh

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 1 | Lê Minh Thế | Bí thư - CT HĐND | 0913 761 323 |  |  |  |
| 2 | Cao Thị Thu | Phó Bí thư | 0949 468 513 |  |  |  |
| 3 | Nguyễn Thị Vân An | UV BTV - TB Xây dựng đảng | 0937 454 057 |  |  |  |
| 4 | Nguyễn ĐQuỳnh | UV BTV - CN UBKT - TB VHXH | 0946 456 777 |  |  |  |
| 5 | Trần Kim Bảo Châu | UV BCH - PTB Xây dựng đảng | 0918 563 632 |  |  |  |
| 6 | Nguyễn Ngọc Nga | UV BCH - PCN UBKTĐU | 0919 720 155 |  |  |  |
| 7 | Lưu Thị Thu | UV BCH - GĐ TT chính trị | 0916 323 389 |  |  |  |
| 8 | Nguyễn Văn Thuận | UV BCH - CVP Đảng ủy | 0915 719 547 |  |  |  |
| 9 | Lê Tấn Phát | UV BCH - CT MTTQ | 0976 166 165 |  |  |  |
| 10 | Huỳnh Thị Kim Oanh | UV BCH - PCT MTTQ, CT Hội LHPN | 0985 201 388 |  |  |  |
| 11 | Phạm Quốc Phong | UV BCH - PCT MTTQ, CT Cđoàn | 0909 110 005 |  |  |  |
| 12 | Nguyễn Thị Kim Phú | UV BCH - PCT MTTQ, BT Đoàn TN | 0366 044 509 |  |  |  |
| 13 | Thái Bá Hải | PCT MTTQ, CT Hội CCB | 0973 995 252 |  |  |  |

### HĐND phường Tân Ninh / Địa chỉ: Số 381, Đường 30/4, KP22, Phường Tân Ninh, Tây Ninh

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 14 | Phạm Văn Thảo | UV BTV - PCT HĐND - TB Kinh tế - Ngân sách | 0987 780 846 |  |  |  |
| 15 | Đoàn Thị Cẩm Nhung | PTB Kinh tế - Ngân sách | 0906 785 995 |  |  |  |
| 16 | Lê Hoàng Linh | PTB VHXH - HĐND | 0907 667 969 |  |  |  |

### Ủy ban nhân dân phường Tân Ninh - ĐT bàn: 0276.3822157 - 0276.3827809; email: ubndtanninh@tayninh.gov.vn

### Địa chỉ: Số 381, Đường 30/4, KP22, Phường Tân Ninh, Tây Ninh

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 17 | Nguyễn Thị Hoàng Oanh | Phó Bí thư - CT UBND | 0919 270 417 |  |  |  |
| 18 | Nguyễn Thị Thiên Hương | UV BTV - PCT UBND - GĐ TT Hành chính công | 0976 501 983 |  |  |  |
| 19 | Lữ Thanh Tùng | UV BTV - PCT UBND | 0918 623 093 |  |  |  |
| 20 | Nguyễn Thị Loan | UV BCH - CVP HĐND và UBND | 0982 632 002 |  |  |  |
| 21 | Nguyễn Tấn Đạt | PCVP HĐND và UBND | 0903 908 309 |  |  |  |
| 22 | Tô Nguyễn Nhị Linh | UV BCH - Trưởng phòng KT,HT&ĐT | 0909 278 072 |  |  |  |
| 23 | Ma Hữu Nghĩa | PTP KT,HT&ĐT | 0986 080 727 |  |  |  |
| 24 | Lý Minh Tâm | PTP KT,HT&ĐT | 0909 861 860 |  |  |  |
| 25 | Hồ Thị Cẩm | UV BCH - TP Văn hóa - Xã Hội | 0933 211 330 |  |  |  |
| 26 | Bùi Thị Hà | PTP Văn hóa - Xã Hội | 0973 125 557 |  |  |  |
| 27 | Phạm Tấn Vũ | PTP Văn hóa - Xã Hội | 0986 542 932 |  |  |  |
| 28 | Huỳnh Thanh Nhã | PGĐ TT Hành chính công | 0987 506 166 |  |  |  |
| 29 | Nguyễn Thị Ngọc Hà | PGĐ TT Hành chính công | 0914 599 699 |  |  |  |
| 30 | Lâm Thu Hương | GĐ TT Cung ứng DVSN công | 0942 243 224 |  |  |  |
| 31 | Trần Thị Kim Khánh | PGĐ TT Cung ứng DVSN công | 0915 403 317 |  |  |  |
| 32 | Nguyễn Thành Sơn | PGĐ TT Cung ứng DVSN công | 0975 044 640 |  |  |  |
| 33 | Trần Quang Nam | UV BTV - Trưởng Công an | 0913 880 554 |  |  |  |
| 34 | Nguyễn Trường Ân | UV BCH - Phó trưởng Công an | 0902 400 009 |  |  |  |
| 35 | Nguyễn Thị Thanh Trúc | Phó trưởng Công an | 0919 595 932 |  |  |  |
| 36 | Trần Quyền Huy | Phó trưởng Công an | 0973 768 486 |  |  |  |
| 37 | Lê Duy Linh | UV BTV - CHT BCH Quân sự | 0933 977 557 |  |  |  |
| 38 | Nguyễn Văn Lâm | UV BCH - CHP BCH Quân sự | 0982 274 895 |  |  |  |
| 39 | Trần Thị Lan Phượng | Phó GĐ BQL Dự án | 0913 199 887 |  |  |  |

### PHƯỜNG BÌNH MINH

- Nhóm: 1
- Mã/STT nhóm: 9

### Đảng ủy phường Bình Minh

### Địa chỉ: Số 504, đường Trần Văn Trà, khu phố Kinh Tế, phường Bình Minh

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 1 | Võ Hồng Sang | Bí thư kiêm Chủ tịch HĐND | 0907 465 626 |  |  |  |
| 2 | Nguyễn Thị Thanh Thúy | Phó Bí thư | 0987 616 940 |  |  |  |
| 3 | Trần Thanh Danh | UV BTV - CN UBKT / kiêm TB VHXH-HĐND | 0976 235 741 |  |  |  |
| 4 | Phạm Thị Ngọc Trâm | UV BCH - PCN UBKT | 0934 784 880 |  |  |  |
| 5 | Phạm Thanh Sơn | PCN UBKT | 0937 574 998 |  |  |  |
| 6 | Dương Nguyễn Nhật Linh | UV BTV - TB Xây dựng đảng | 0909 5958 932 |  |  |  |
| 7 | Trần Minh Trị | UV BCH - PTB Xây dựng đảng | 0984 642 347 |  |  |  |
| 8 | Lưu Trung Đan | PTB Xây dựng đảng | 0918 623 680 |  |  |  |
| 9 | Phạm Kim Uyên | UV BCH - CVP Đảng ủy | 0888 080 381 |  |  |  |
| 10 | Nguyễn Thanh Tuấn | PCVP Đảng ủy | 0901 545 937 |  |  |  |
| 11 | Dương Quốc Hữu | PCVP Đảng ủy | 0907 075 731 |  |  |  |
| 12 | Lê Thị Ngọc Diễm | UV BTV - CT MTTQ | 0779 703 336 |  |  |  |
| 13 | Phạm Thị Hồng Thái | UV BCH - PCT MTTQ, CT Hội PN | 0908 866 923 |  |  |  |
| 14 | Võ Thị Thu Hồng | UV BCH - PCT MTTQ, CT Hội ND | 0908 705 039 |  |  |  |
| 15 | Nguyễn Văn Hào | UV BCH - PCT MTTQ, BT Đoàn TN | 0362 213 196 |  |  |  |
| 16 | Cao Xuân Vinh | PCT MTTQ, CT Hội Cựu chiến binh | 0908 768 157 |  |  |  |
| 17 | Đoàn Thị Thu Hiền | UV BCH - PCT MTTQ, CT Cđoàn | 0358 388 817 |  |  |  |

### Hội đồng nhân dân phường

### Địa chỉ: Địa chỉ: Số 504, đường Trần Văn Trà, khu phố Kinh Tế, phường Bình Minh

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 18 | Nguyễn Văn Nam | UV BTV - PCT HĐND / kiêm TB Kinh tế, Ngân sách - HĐND | 0937 038 278 |  |  |  |
| 19 | Phạm Thị Kim Hoa | PTB Kinh tế, Ngân sách - HĐND | 0944 366 290 |  |  |  |
| 20 | Võ Cao Đỉnh | PTB VHXH - HĐND | 0919 902 826 |  |  |  |

### Ủy ban nhân dân phường - ĐT bàn: 02763 ….. ; email: ubndbinhminh@tayninh.gov.vn

### Địa chỉ: 601 đường Bời Lời, khu phố Ninh Thọ, phường Bình Minh

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 21 | Lương Bá Công an | Phó Bí thư - CT UBND | 0909 789 702 |  |  |  |
| 22 | Trần Văn Tùng | UV BTV - PCT UBND | 0982 862 628 |  |  |  |
| 23 | Nguyễn Thanh Nghị | UV BTV - PCT UBND / kiêm GĐ TT Hành chính công | 0919 664 757 |  |  |  |
| 24 | Trần Hữu Ngọc | UV BCH - CVP HĐND và UBND | 0908 423 377 |  |  |  |
| 25 | Võ Ngọc Thanh Hằng | PCVP HĐND và UBND phường | 0779 724 189 |  |  |  |
| 26 | Nguyễn Thị Hồng Huế | PCVP HĐND và UBND phường | 0977 659 507 |  |  |  |
| 27 | Nguyễn Thanh Long | UV BCH- TP Kinh tế, Hạ tầng và Đô thị | 0985 494 748 |  |  |  |
| 28 | Trịnh Xuân Tứ | PTP Kinh tế, Hạ tầng và Đô thị | 0981 751 750 |  |  |  |
| 29 | Bùi Thị Hồng Quyên | PTP Kinh tế, Hạ tầng và Đô thị | 0947 151 349 |  |  |  |
| 30 | Nguyễn Thị Anh Đào | UV BCH - TP Văn hóa - Xã hội | 0984 736 297 | ABC |  |  |
| 31 | Đào Thị Kim Loan | PTP Văn hóa - Xã hội | 0903 965 371 |  |  |  |
| 32 | Võ Phú Đông | PTP Văn hóa - Xã hội | 0963 910 639 |  |  |  |
| 33 | Nguyễn Hoàng Phương | PGĐ TT Hành chính công | 0913 843 409 |  |  |  |
| 34 | Nguyễn Châu Loan | PGĐ TT Hành chính công | 0917 859 782 |  |  |  |
| 35 | Phạm Quang Duy | GĐ TT Cung ứng DVSN công | 0937 988 332 |  |  |  |
| 36 | Nguyễn Hoàng Nam (SN 1982) | PGĐ TT Cung ứng DVSN công | 0943 447 154 |  |  |  |
| 37 | Nguyễn Hoàng Nam (SN 1977) | PGĐ TT Cung ứng DVSN công | 0978 078 115 |  |  |  |
| 38 | Đinh Trọng Hiếu | UV BTV - Trưởng Công an | 933489588 |  |  |  |
| 39 | Trần Thị Hồng Nhung | UV BCH - Phó trưởng Công an | 0918 623 613 |  |  |  |
| 40 | Trần Hòa Bình | Phó trưởng Công an | 0946 326 828 |  |  |  |
| 41 | Huỳnh Thanh Hiền | Phó trưởng Công an | 0939 577 738 |  |  |  |
| 42 | Nguyễn Vũ Trường | Phó trưởng Công an | 0325 292 392 |  |  |  |
| 43 | Phạm Vũ Nguyên | Phó trưởng Công an | 0913 884 022 |  |  |  |
| 44 | Nguyễn Hữu Phong | UV BTV - CHT BCH Quân sự phường | 0917 217 921 |  |  |  |

### PHƯỜNG TRẢNG BÀNG

- Nhóm: 1
- Mã/STT nhóm: 10

### Đảng ủy phường Trảng Bàng ĐT bàn: 02763 880 218 Email:ubndtrangbang@tayninh.gov.vn

### Địa chỉ: khu phố Lộc An, phường Trảng Bàng

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 1 | Văn Tiến Dũng | Bí thư | 0913 884 167 |  |  |  |
| 2 | Nguyễn Minh Thuận | Phó Bí thư | 0919 330 770 |  |  |  |
| 3 | Phạm Văn Diện | UV BTV - CN UBKT | 0938 385 658 |  |  |  |
| 4 | Nguyễn Tú Anh | UV BCH - PCN UBKT | 0933 341 552 |  |  |  |
| 5 | Nguyễn Thị Đài Loan | UV BTV - TB Xây dựng đảng | 0919 235 552 |  |  |  |
| 6 | Nguyễn Thị Thuỳ Nhiên | UV BCH - PTB Xây dựng đảng | 0946 813 189 |  |  |  |
| 7 | Trần Khánh Nhẫn | UV BCH - CVP Đảng ủy | 0933 301 290 |  |  |  |
| 8 | Nguyễn Minh Thuận | PBT.TT - CT MTTQ | 0919 330 770 |  |  |  |
| 9 | Đỗ Thị Thanh Trúc | UV BCH - PCT MTTQ, CT Hội LHPN | 0975 209 725 |  |  |  |
| 10 | đang khuyết | UV BCH - PCT MTTQ, CT Hội ndân |  |  |  |  |
| 11 | Trần Khải Hoàn | UV BCH - PCT MTTQ, BT Đoàn TN | 0812 836 699 |  |  |  |

#### 12

### Hội đồng nhân dân phường Trảng Bàng

### Địa chỉ: khu phố Lộc An, phường Trảng Bàng

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 13 | Văn Tiến Dũng | Bí thư - CT HĐND | 0913 884 167 |  |  |  |
| 14 | Huỳnh Văn Sang | Ban Kinh tế - HĐND | 0915 417 839 |  |  |  |
| 15 | Võ Thị Tuyết Thương | Ban VHXH - HĐND | 0915 407 399 |  |  |  |

### Ủy ban nhân dân - ĐT bàn: 02763 880 218 ; email: ubndtrangbang@tayninh.gov.vn

### Địa chỉ: khu phố Lộc An, phường Trảng Bàng

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 16 | Trần Minh Tâm | Phó Bí thư - CT UBND | 0913 130 087 |  |  |  |
| 17 | Huỳnh Thị Thuỳ Trang | UV.BTV - PCT UBND | 0917 070 638 |  |  |  |
| 18 | Đinh Thị Dương Thuý | UV.BCH - PCT UBND | 0903 328 847 |  |  |  |
| 19 | Ngô Minh Tân | UV.BCH - CVP HĐND và UBND | 0913 621 279 |  |  |  |
| 20 | Hà Minh Tuấn | PCVP HĐND và UBND |  |  |  |  |
| 21 | Nguyễn Hội | UV.BCH - Trưởng phòng Kinh tế | 0938 284 248 |  |  |  |
| 22 | đang khuyết | PTP Knh tế |  |  |  |  |
| 23 | Trần CDanh | UV.BCH - TP Văn hóa - Xã hội | 0912 548 275 | ABC |  |  |
| 24 | Trần Thị Hồng Thắm | PTP Văn hóa - Xã hội | 0918 889 232 |  |  |  |
| 25 | Huỳnh Thị Thuỳ Trang | GĐ TT Hành chính công | 0917 070 638 |  |  |  |
| 26 | Nguyễn Anh Tuấn | PGĐ TT Hành chính công | 0918 353 608 |  |  |  |
| 27 | Lương Trí Vũ | GĐ TT Cung ứng DVSN công | 0922 505 444 |  |  |  |
| 28 | Lê Thị Mỹ Hiếu | PGĐ TT Cung ứng DVSN công | 0982 656 651 |  |  |  |
| 29 | Đoàn Thị Trúc Giang | UV.BTV - Trưởng Công an | 0786 575 626 |  |  |  |
| 30 | Nguyễn Minh Khai | UV.BCH Phó trưởng Công an | 0918 567 232 |  |  |  |
| 31 | Đặng Tuấn Kiệt | UV.BTV - CHT BCH Quân sự | 0938 380 502 |  |  |  |

### PHƯỜNG AN TỊNH

- Nhóm: 1
- Mã/STT nhóm: 11

#### Quốc lộ 22, khu phố An Bình, phường An Tịnh

- Địa chỉ: Quốc lộ 22, khu phố An Bình, phường An Tịnh

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 1 | Ngô Minh Xuyên | Chủ tịch UBND phường | 0918 234 585 |  |  | Quốc lộ 22, khu phố An Bình, phường An Tịnh |
| 2 | Trần Thông Trực | PCT UBND phường - / kiêm Giám đốc TTPVHCC | 0913 955 190 |  |  |  |
| 3 | Hà Thị Cẩm Tiên | PCT HĐND | 0909 324 225 |  |  |  |
| 4 | Trịnh Thị Uyên | PCT UBND phường | 0906 482 449 |  |  |  |
| 5 | Nguyễn Văn Dân | Phó Ban Văn Hóa - Xã hội HĐND | 0919 542 595 |  |  |  |
| 6 | Phan Uy Khôi | Chánh VP HĐND và UBND | 0916 686 787 |  |  |  |
| 7 | Lương Tấn Phú | Phó Chánh VP HĐND và UBND | 0916 763 003 |  |  |  |
| 8 | Nguyễn Văn Phúc | Trưởng phòng Kinh tế Hạ tầng đô thị | 0909 122 489 |  |  |  |
| 9 | Nguyễn Thành Cao Trí | Phó phòng Kinh tế Hạ tầng đô thị | 0938 642 652 |  |  |  |
| 10 | Đoàn Hoài Linh | Trưởng phòng Văn hóa - Xã hội | 0919 980 112 |  |  |  |
| 11 | Nguyễn Thị Thái Lan | Phó phòng Văn hóa - Xã hội | 0918 499 448 |  |  |  |
| 12 | Nguyễn Đông Đức | Phó Giám đốc TTPVHCC | 0989 745 292 |  |  |  |

### PHƯỜNG GIA LỘC

- Nhóm: 1
- Mã/STT nhóm: 12

### Đảng ủy phường Gia Lộc

### Địa chỉ: Khu phố Lộc Trát, phường Gia Lộc

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 1 | Hồ Văn Hồng | Bí thư | 0913 884 118 |  | honghv@tayninh.gov.vn |  |
| 2 | Nguyễn Văn Lam | Phó Bí thư Thường trực | 0919 215 469 |  | lamnv@tayninh.gov.vn |  |
| 3 | Trần Nguyễn Thuỳ Linh | UV BTV - CN UBKT ĐU phường | 0913 884 533 |  |  |  |
| 4 | Lê Thị Lựu | UV BCH - PCN UBKTĐU phường | 0937 263 272 |  |  |  |
| 5 | Phạm Công Danh | UV BTV - TB Xây dựng đảng | 0913 884 213 |  |  |  |
| 6 | Nguyễn Thành Thiện | UV BCH - PTB Xây dựng đảng | 0912 982 251 |  |  |  |
| 7 | Nguyễn Thị Kim Thoa | UV BCH - CVP Đảng ủy phường | 0941 428 916 |  |  |  |
| 8 | Nguyễn Văn Lam | PBTTT - CT MTTQ phường | 0919 215 469 |  |  |  |
| 9 | Nguyễn Thị Hồng Thi | UV BCH - PCT MTTQ, CT Hội PN | 0987 944 305 |  |  |  |
| 10 | Lê Văn Sĩ | UV BCH - PCT MTTQ, CT Hội ND | 0983 555 557 |  |  |  |
| 11 | Nguyễn Minh Phước | UV BCH - PCT MTTQ, BT Đoàn TN | 0963 292 273 |  |  |  |
| 12 | Nguyễn Xuân Tươi | UV BCH - PCT MTTQ, Công đoàn | 0784 566 128 |  |  |  |

### Hội đồng nhân dân phường Gia Lộc

### Địa chỉ: Khu phố Suối Cao A, phường Gia Lộc

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 13 | Hồ Văn Hồng | Bí thư - CT HĐND phường | 0913 884 118 |  | honghv@tayninh.gov.vn |  |
| 14 | Nguyễn Văn Rã | UV BTV - PCT HĐND phường | 0912 977 131 |  | vanra1971@tayninh.gov.vn |  |
| 15 | Trần Nguyễn Thuỳ Linh | Trưởng Ban Kinh tế - HĐND | 0913 884 533 |  |  |  |
| 16 | Phạm Công Danh | Trưởng Ban VHXH - HĐND | 0913 884 213 |  |  |  |

### Ủy ban nhân dân phường - ĐT bàn: 02763 ….. ; email: ubndgialoc@tayninh.gov.vn

### Địa chỉ: Khu phố Suối Cao A, phường Gia Lộc

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 17 | Lê Thị Hồng Thắm | Phó Bí thư - CT UBND | 0919 908 846 |  | thamlth@tayninh.gov.vn |  |
| 18 | Nguyễn Văn Đậu | UV BTV - PCT UBND | 0982 353 033 |  | vandau@tayninh.gov.vn |  |
| 19 | Nguyễn Thị Thu Trang | UV BCH - PCT UBND | 0943 416 534 |  | thutrang1982@tayninh.gov.vn |  |
| 20 | Vũ Thị Thanh Tâm | ĐUV - CVP HĐND và UBND phường | 0972 171 687 |  | thanhtam1987@tayninh.gov.vn |  |
| 21 | Nguyễn Thị Thúy Nhung | PCVP HĐND và UBND phường | 0987 943 047 |  | thuynhung1987@tayninh.gov.vn |  |
| 22 | Phạm Thanh Phong | ĐUV - TP Kinh tế, Hạ tầng và Đô thị phường | 0385 434 895 |  | thanhphong1985@tayninh.gov.vn |  |
| 23 | Huỳnh Văn Út | Phó TP Kinh tế, Hạ tầng và Đô thị phường | 0937 557 232 |  | vanut1976@tayninh.gov.vn |  |
| 24 | Phan Thành Nhơn | ĐUV - TP Văn hóa - Xã hội | 0943 430 660 |  | thanhnhon1991@tayninh.gov.vn |  |
| 25 | Tạ Thị Hồng Cẩm | PTP Văn hóa - Xã hội | 0906 828 979 |  | hongcam1983@tayninh.gov.vn |  |
| 26 | Nguyễn Thị Thu Trang | GĐ TT Hành chính công | 0943 416 534 |  | thutrang1982@tayninh.gov.vn |  |
| 27 | - | PGĐ TT Hành chính công | - |  |  |  |
| 28 | Nguyễn Văn Đậu | GĐ TT Cung ứng DVSN công | 0982 353 033 |  | vandau@tayninh.gov.vn |  |
| 29 | - | PGĐ TT Cung ứng DVSN công | - |  |  |  |
| 30 | Nguyễn Văn Riệng | UV BTV - Trưởng Công an phường | 0913 955 110 |  |  |  |
| 31 | Nguyễn Đức Tính | ĐUV - Phó trưởng Công an phường | 0917 424 656 |  |  |  |
| 32 | Phạm Thị Thoại | Phó trưởng Công an phường | 0907 055 717 |  |  |  |
| 33 | Mai Việt Bình | Phó trưởng Công an phường | 0972 969 299 |  |  |  |
| 34 | Nguyễn Hoàng Minh | Phó trưởng Công an phường | 0967 086 768 |  |  |  |
| 35 | Nguyễn Hoàng Nam | Phó trưởng Công an phường | 0888 414 115 |  |  |  |

### BCH Quân sự phường Gia Lộc

### Địa chỉ: Khu phố Lộc Trát, phường Gia Lộc

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 36 | Trần Minh Vương | UV BTV - CHT BCH Quân sự phường | 0933 825 346 |  |  |  |
| 37 | Trần Thanh Trường | Chỉ huy Phó BCHQS phường | 0823 944 900 |  |  |  |
| 38 | Nguyễn Hoài Nam | Trợ lý BCHQS phường | 0832 777 780 |  |  |  |

### PHƯỜNG GÒ DẦU

- Nhóm: 1
- Mã/STT nhóm: 13

#### Email: ubndgodau@tayninh.gov.vn

#### Website: godau.tayninh.gov.vn

#### Đc: Đường Trần Quốc Đại, khu phố Nội ô A, phường Gò Dầu

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 1 | Trịnh Ngọc Phương | Tỉnh ủy viên - Bí thư - CT HĐND | 0913 956 157 |  |  |  |
| 2 | Vương Thị Thúy Oanh | Phó Bí thư thường trực Đảng ủy | 0982 473 339 |  |  |  |
| 3 | Nguyễn Thanh Hải | Phó Bí thư - CT UBND | 0918 810 107 |  |  |  |
| 4 | Đỗ Văn Minh | UV BTV - PCT UBND - GĐ TTPCHCC | 0929 166 699 |  |  |  |
| 5 | Lê Huy Vũ | UV BTV - PCT UBND | 0948 491 741 |  |  |  |
| 6 | Trịnh Minh Hiếu | UV BTV - PCT HĐND | 0913 955 946 |  |  |  |
| 7 | Nguyễn Huỳnh Ninh Hải | UV BTV - CT MTTQ | 0919 777 752 |  |  |  |
| 8 | Đặng Viết Dũng | UV. BCH - PCT MTTQ - CT Hội ND | 0907 022 071 |  |  |  |
| 9 | Trần Thị Ngọc Em | UV. BCH - PCT MTTQ - CT Cđoàn | 0971 261 515 |  |  |  |
| 10 | Nguyễn Thị Thanh Thúy | UV. BCH - PCT MTTQ - CT Hội PN | 0972 358 392 |  |  |  |
| 11 | Lê Nguyễn Du | UV. BCH - PCT MTTQ - BT Đoàn TN | 0908 851 874 |  |  |  |
| 12 | Nguyễn Văn Bền | UV. BCH - PCT MTTQ - CT Hội CCB | 0908 948 180 |  |  |  |
| 13 | Lê Thị Cẩm Nhung | UV BTV - TB Xây dựng Đảng / TB VH-XH HĐND | 0918 868 439 |  |  |  |
| 14 | Nguyễn Thị Lẽ | PTB VH- XH HĐND | 0978 331 356 |  |  |  |
| 15 | Huỳnh Thanh Hải | UV BTV - CN UBKT / TB KT-NS HĐND | 0938 971 946 |  |  |  |
| 16 | Nguyễn Thị Mai Thi | PTB KT-NS HĐND | 0909 358 065 |  |  |  |
| 17 | Nguyễn Thanh Lâm | UV BTV - CHT BCHQS | 0779 226 702 |  |  |  |
| 18 | Nguyễn Tất Linh | PCHT BCHQS | 0972 182 277 |  |  |  |
| 19 | Đoàn Văn Vũ Em | UV BTV - Trưởng Công an | 0909 066 678 |  |  |  |
| 20 | Trần Thị Tiền | Phó trưởng Công an | 0918 870 717 |  |  |  |
| 21 | Nguyễn Sơn Tùng | Phó trưởng CA - phụ tách Tổ CS khu vực | 0862 849 951 |  |  |  |
| 22 | Nguyễn Bảo Giang | Phó trưởng CAP - phụ trách Tổ CSTT | 0906 691 233 |  |  |  |
| 23 | Nguyễn Thành Trung | Phó trưởng CAP - phụ trách Tổ An ninh | 0915 407 718 |  |  |  |
| 24 | Nguyễn Minh Trí | Phó trưởng Công an | 0919 539 832 |  |  |  |
| 25 | Bùi Hữu Đức | UV. BCH - CVP HĐND và UBND | 0937 291 280 |  |  |  |
| 26 | Nguyễn Văn Lập | Phó CVP HĐND và UBND | 0777 736 777 |  |  |  |
| 27 | Nguyễn Thị Gái Liên | UV. BCH - TP Kinh tế, Hạ tầng và Đô thị | 0938 983 933 |  |  |  |
| 28 | Tô Hữu Lộc | PTP Kinh tế, Hạ tầng và Đô thị | 0947 841 248 |  |  |  |
| 29 | Nguyễn Ngọc Thạch | UV. BCH - TP Văn hóa-Xã hội | 0815 792 792 |  |  |  |
| 30 | Trần Kim Hồng | PTP Văn hóa - Xã hội | 0372 266 369 |  |  |  |
| 31 | Đặng Văn Thương | PGĐ TT phục vụ hành chính công | 0983 853 634 |  |  |  |

### PHƯỜNG NINH THẠNH

- Nhóm: 1
- Mã/STT nhóm: 14

### Số 420 Đường Điện Biên Phủ, Khu phố Ninh Hòa, phường Ninh Thạnh

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 1 | Nguyễn Tấn Đức | Bí thư Đảng ủy (kiêm Chủ tịch HĐND) | 0913 955 145 |  |  |  |
| 2 | Nguyễn Quang Thắng | Phó Bí thư Thường trực Đảng uỷ | 0977 019 021 |  |  | Số 420 Đường Điện Biên Phủ, Khu phố Ninh Hòa, phường Ninh Thạnh |
| 3 | Đặng Thủ Thừa | Phó Bí thư Đảng uỷ, Chủ tịch UBND | 0907 577 420 |  |  | Số 1350, khu phố Ninh Thuận, phường Ninh Thạnh |
| 4 | Nguyễn Quang Vinh | UV BTV - TB Xây dựng Đảng - / TB Kinh tế - Ngân sách HĐND | 0919 807 952 |  |  | Số 420 Đường Điện Biên Phủ, Khu phố Ninh Hòa, phường Ninh Thạnh |
| 5 | Vương Thị Trường | UV BTV - CN UBKT - / kiêm TB Văn hoá - Xã hội HĐND | 0938 627 429 |  |  | Số 420 Đường Điện Biên Phủ, Khu phố Ninh Hòa, phường Ninh Thạnh |
| 6 | Huỳnh Quốc Tuấn | UV BTV - Chủ tịch MTTQ | 0937 477 277 |  |  | Số 420 Đường Điện Biên Phủ, Khu phố Ninh Hòa, phường Ninh Thạnh |
| 7 | Lê Thành Lâm | UV BTV - PCT HĐND | 0947 771 368 |  |  | Số 1350, khu phố Ninh Thuận, phường Ninh Thạnh |
| 8 | Lê Thành Chung | UV BTV - PCT UBND | 0906 763 273 |  |  | Số 1350, khu phố Ninh Thuận, phường Ninh Thạnh |
| 9 | Mai Lâm Định | UV BTV - PCT UBND / kiêm GĐ TT Phục vụ hành chính công | 0918 567 577 |  |  | Số 1350, khu phố Ninh Thuận, phường Ninh Thạnh |
| 10 | Võ Văn Thời | UV BCH - CVP HĐND và UBND | 0848 393 212 |  |  | Số 1350, khu phố Ninh Thuận, phường Ninh Thạnh |
| 11 | Nguyễn Trương Uy Vũ | UV BCH - TP Kinh tế, Hạ tầng và Đô thị | 0908 809 990 |  |  | Số 1350, khu phố Ninh Thuận, phường Ninh Thạnh |
| 12 | Quách Thị Yến Linh | UV BCH - TP Văn hóa - Xã hội | 0944 317 391 |  |  | Số 1350, khu phố Ninh Thuận, phường Ninh Thạnh |
| 13 | Lê Ngọc Quyên | UV BCH - CVP Đảng uỷ | 0916 466 172 |  |  | Số 420 Đường Điện Biên Phủ, Khu phố Ninh Hòa, phường Ninh Thạnh |
| 14 | Phạm Thị Kiều Trang | UV BCH - PTB Xây dựng Đảng | 0977 042 346 |  |  | Số 420 Đường Điện Biên Phủ, Khu phố Ninh Hòa, phường Ninh Thạnh |
| 15 | Phạm Thạnh Hưng | UV BCH - PCN Uỷ ban Kiểm tra | 0918 646 511 |  |  | Số 420 Đường Điện Biên Phủ, Khu phố Ninh Hòa, phường Ninh Thạnh |
| 16 | Lê Hương có | UV BCH - PCT MTTQ (kiêm BT Đoàn TN) | 0333 550 586 |  |  | Số 420 Đường Điện Biên Phủ, Khu phố Ninh Hòa, phường Ninh Thạnh |
| 17 | Huỳnh Hồng Thu | UV BCH - PCT MTTQ (kiêm CT Hội PN) | 0908 296 600 |  |  | Số 420 Đường Điện Biên Phủ, Khu phố Ninh Hòa, phường Ninh Thạnh |
| 18 | Trần Thanh Hải | UV BCH - PCT MTTQ (kiêm CT Hội ND) | 0984 665 997 |  |  | Số 420 Đường Điện Biên Phủ, Khu phố Ninh Hòa, phường Ninh Thạnh |
| 19 | Huỳnh Thế Tài | Phó CVP HĐND và UBND | 0983 110 501 |  |  | Số 1350, khu phố Ninh Thuận, phường Ninh Thạnh |
| 20 | Lê Thị Ngọc Bích | PTP Kinh tế, Hạ tầng và Đô thị | 0917 600 284 |  |  | Số 1350, khu phố Ninh Thuận, phường Ninh Thạnh |
| 21 | Nguyễn Minh Châu | PTP Văn hóa – Xã hội | 0902 877 223 |  |  | Số 1350, khu phố Ninh Thuận, phường Ninh Thạnh |
| 22 | Trần Ngọc Long | Phó GĐ TT phục vụ hành chính công | 0909 333 145 |  |  | Số 1350, khu phố Ninh Thuận, phường Ninh Thạnh |
| 23 | Trần Quốc Tuấn | GĐ TT cung ứng DV sự nghiệp công | 0971 367 736 |  |  | Số 1350, khu phố Ninh Thuận, phường Ninh Thạnh |
| 24 | Võ Duy Khang | Phó GĐ TT cung ứng dịch vụ sự nghiệp công | 0944 685 757 |  |  | Số 1350, khu phố Ninh Thuận, phường Ninh Thạnh |

### XÃ TÂN HƯNG

- Nhóm: 1
- Mã/STT nhóm: 15

### Số 06, đường Tôn Đức Thắng, ấp Rọc Chanh A, xã Tân Hưng,

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 1 | Trương Hải Đăng | Bí thư Đảng ủy xã | 0859 778 888 | 0272.3.861.024 |  | Số 06, đường Tôn Đức Thắng, ấp Rọc Chanh A, xã Tân Hưng |
| 2 | Trần Thị Đào | Phó BT Thường trực - Chủ tịch HĐND | 0988 468 408 |  |  | Số 06, đường Tôn Đức Thắng, ấp Rọc Chanh A, / xã Tân Hưng |
| 3 | Phan Hòa Nông | Phó Bí thư Đảng ủy - Chủ tịch UBND xã | 0913 818 639 |  |  | Số 01, đường Tôn Đức Thắng, ấp Rọc Chanh A, / xã Tân Hưng |
| 4 | Hồ Quốc Việt | Trưởng ban Xây dựng Đảng - / Trưởng Ban Văn hóa - Xã hội HĐND xã | 0979 849 497 |  |  | Số 06, đường Tôn Đức Thắng, ấp Rọc Chanh A, / xã Tân Hưng |
| 5 | Nguyễn Thị Châu Quyên | PCT HĐND xã | 0977 797 082 |  |  | Số 01, đường Tôn Đức Thắng, ấp Rọc Chanh A, / xã Tân Hưng |
| 6 | Nguyễn Cao Đẳng | PCT UBND xã | 0976 299 292 |  |  | Số 01, đường Tôn Đức Thắng, ấp Rọc Chanh A, / xã Tân Hưng |
| 7 | Nguyễn Lương Tuấn | PCT UBND xã | 0932 822 433 |  |  | Số 01, đường Tôn Đức Thắng, ấp Rọc Chanh A, / xã Tân Hưng |
| 8 | Lê Từ Văn | CT. UBMTTQ Việt Nam xã | 0912 151 715 |  |  | Số 06, đường Tôn Đức Thắng, ấp Rọc Chanh A, / xã Tân Hưng |
| 9 | Võ Viết Vinh | CN UBKT Đảng ủy xã | 0919 598 555 |  |  | Số 06, đường Tôn Đức Thắng, ấp Rọc Chanh A, / xã Tân Hưng |
| 10 | Nguyễn Đức Tính | Trưởng Công an | 0915 535 996 | 0272.3.861.046 |  | Số 179, đường 3/2, ấp Rọc Chanh A, / xã Tân Hưng |
| 11 | Lê Anh Tuấn | CHT BCHQS xã | 0968 199 784 | 0272.3.861.647 |  | Số 35, đường 24/3, ấp Gò Thuyền A, xã Tân Hưng |
| 12 | Trần Chí Hiếu | Chánh Văn Phòng Đảng ủy xã | 0837 764 567 |  |  | Số 06, đường Tôn Đức Thắng, ấp Rọc Chanh A, / xã Tân Hưng |
| 13 | Nguyễn Thị Ánh Xuân | PTB Xây dựng Đảng Đảng ủy xã | 0937 119 449 |  |  | Số 06, đường Tôn Đức Thắng, ấp Rọc Chanh A, / xã Tân Hưng |
| 14 | Lê Văn U Thanh | Phó CN UBKT Đảng ủy xã | 0979 005 007 |  |  | Số 06, đường Tôn Đức Thắng, ấp Rọc Chanh A, / xã Tân Hưng |
| 15 | Lý Thị Thùy Trang | PCT MTTQ - CT. Hội PN | 0975 698 399 |  |  | Số 06, đường Tôn Đức Thắng, ấp Rọc Chanh A, / xã Tân Hưng |
| 16 | Nguyễn Văn Tùng Em | PCT MTTQ - CT Hội ND | 0946 966 727 |  |  | Số 06, đường Tôn Đức Thắng, ấp Rọc Chanh A, / xã Tân Hưng |
| 17 | Lê Tuấn | PCT UBMTTQ - Bí thư Đoàn TN | 0943 454 595 |  |  | Số 06, đường Tôn Đức Thắng, ấp Rọc Chanh A, / xã Tân Hưng |
| 18 | Nguyễn Văn Sỹ | Phó Ban VH-XH HĐND xã | 0909 720 910 |  |  | Số 01, đường Tôn Đức Thắng, ấp Rọc Chanh A, / xã Tân Hưng |
| 19 | Nguyễn Văn Đoàn | Phó Ban KT-NS HĐND xã | 0983 986 011 |  |  | Số 01, đường Tôn Đức Thắng, ấp Rọc Chanh A, / xã Tân Hưng |
| 20 | Tống Xuân Tú | Chánh Văn Phòng HĐND và UBND | 0942 404 460 |  |  | Số 01, đường Tôn Đức Thắng, ấp Rọc Chanh A, / xã Tân Hưng |
| 21 | Huỳnh Thanh Dũng | Trưởng Phòng VH-XH | 0933 712 700 |  |  | Số 01, đường Tôn Đức Thắng, ấp Rọc Chanh A, / xã Tân Hưng |
| 22 | Nguyễn Thị Kim Huệ | Trưởng Phòng Kinh tế | 0912 979 447 |  |  | Số 01, đường Tôn Đức Thắng, ấp Rọc Chanh A, / xã Tân Hưng |
| 23 | Nguyễn Hoàng Quân | Phó CHT BCHQS xã | 0938 914 985 | 0272.3.861.647 |  | Số 35, đường 24/3, ấp Gò Thuyền A, xã Tân Hưng |
| 24 | Nguyễn Văn Tình | Phó Trưởng Công an | 0938 707 666 | 0272.3.861.046 |  | Số 179, đường 3/2, ấp Rọc Chanh A, / xã Tân Hưng |
| 25 | Phạm Văn Cường | Giám Đốc TT Chính trị xã | 0918 430 787 |  |  | Số 148, Đường 3/2, ấp Rọc Chanh A, / xã Tân Hưng |
| 26 | Võ Hồng Vân | GĐ TT cung ứng Dịch vụ sự nghiệp công | 0913 989 078 |  |  | Số 01, đường Tôn Đức Thắng, ấp Rọc Chanh A, / xã Tân Hưng |
| 27 | Hồ Khoa Ly | PGĐ TT phục vụ HCC xã | 0856 676 677 |  |  | Số 01, đường Tôn Đức Thắng, ấp Rọc Chanh A, / xã Tân Hưng |
| 28 | Lâm Mộc Tiền | Trưởng Trạm Y tế xã | 0942 600 309 |  |  | Ấp Cái Tràm, xã Tân Hưng |
| 29 | Lê Văn Thắng | Hiệu trưởng Trường THPT Tân Hưng | 0919 460 278 | 0272.3.861.257 |  | Số 01, đường Gò Gòn, ấp Rọc Chanh A, xã Tân Hưng |

### XÃ HƯNG ĐIỀN

- Nhóm: 1
- Mã/STT nhóm: 16

### Đảng ủy xã Hưng Điền

### Địa chỉ: ấp Kinh Mới, xã Hưng ĐiềN

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 1 | Nguyễn Quốc Khánh | Bí thư | 0946 700 766 |  |  |  |
| 2 | Tạ Văn Mệnh | Phó Bí thư | 0918 897 600- 0852 445 446 |  |  |  |
| 3 | Trần Đường Thẳng | UV BTV - CN UBKT ĐU xã | 0918 656 545 |  |  |  |
| 4 | Nguyễn Văn Lít | UV BCH - Phó CN UBKTĐU xã | 0979 593 049 |  |  |  |
| 5 | Lê Văn Tho | UV BTV - TB Xây dựng đảng | 0948 300 033 |  |  |  |
| 6 | Võ Văn Đa | UV BCH - PTB Xây dựng đảng | 0984 780 733 |  |  |  |
| 7 | Trần Văn Tấn | PTB Xây dựng đảng | 0399 976 446 |  |  |  |
| 8 | Phan Thị Ngọc Thất | UV BCH - CVP Đảng ủy xã | 0946 484 994 |  |  |  |
| 9 | Nguyễn Thị Mỹ Nương | Phó CVP Đảng ủy xã | 0797 751 304 |  |  |  |
| 10 | Trần Duy Tám | Chức vụ đảng - CT MTTQ xã | 0918 898 398 |  |  |  |
| 11 | Lý Thị Thanh Thủy | UV BCH - PCT MTTQ, CT Hội PN | 0986 285 446 |  |  |  |
| 12 | Đỗ Văn Tèo | UV BCH - PCT MTTQ, CT Hội ND | 0779 942 666 |  |  |  |
| 13 | Trương Văn Thùy | UV BCH - PCT MTTQ, BT Đoàn TN | 0942 649 5339 |  |  |  |

### HĐND xã Hưng Điền

### Địa chỉ: ấp Kinh Mới, xã Hưng Điền

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 14 | Nguyễn Quốc Khánh | Bí thư - CT HĐND | 0946 700 766 |  |  |  |
| 15 | Trương Đông Hồ | UV.BTV-PCT.HĐND | 0364 532 623 |  |  |  |
| 16 | Trần Văn Liêm | Ban Kinh tế - HĐND | 0973 415 236 |  |  |  |
| 17 | Nguyễn Đình Long | Ban VHXH - HĐND | 0988 789 729 |  |  |  |

### UBND xã Hưng Điền- ĐT bàn: 02763 ….. ; email: ubnd….@tayninh.gov.vn

### Địa chỉ: ấp Kinh Mới, xã Hưng Điền

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 18 | Lê Thành Yên | Phó Bí thư - CT UBND | 0913 180 210 | 02723 860 399 |  |  |
| 19 | Trần Quốc Cường | UV.BTV - PCT UBND | 0845 696 269 | 02723 860 399 |  |  |
| 20 | Lê Phan Quang Trung | UV.BTV - PCT UBND | 0919 821 424 | 02723 860 399 |  |  |
| 21 | Nguyễn Thành Trung | UV.BCH - CVP HĐND và UBND xã | 0986 840 323 |  |  |  |
| 22 | Phan Văn Lê | PCVP HĐND và UBND xã | 0839 484 444 |  |  |  |
| 23 | Lê Quang Vinh | UV.BCH - Trưởng phòng kinh tế xã | 0985 762 085 |  |  |  |
| 24 | Đoàn Chí Tính | Phó Trưởng phòng kinh tế xã | 0939 833 250 |  |  |  |
| 25 | Nguyễn Vũ Linh | UV.BCH - TP Văn hóa - Xã hội | 0388 443 444 |  |  |  |
| 26 | Võ Hữu Tài | PTP Văn hóa - Xã hội | 0937 214 405 |  |  |  |
| 27 | Lê Phan Quang Trung | UV.BTV-PCT.UBND- / GĐ TT Hành chính công | 0919 821 424 |  |  |  |
| 28 | Trịnh Văn Huân | UV.BCH-PGĐ TT Hành chính công | 0934 950 905 |  |  |  |
| 29 | Nguyễn Thị Phương Lan | UV.BCH-GĐ TT Cung ứng DVSN công | 0919 330 560 |  |  |  |
| 30 | Nguyễn Văn Giàu | PGĐ TT Cung ứng DVSN công | 0987 706 799 |  |  |  |
| 31 | Nguyễn Thanh Bình | UV.BTV - Trưởng Công an | 0918 127 447 | 02723 860 076 |  |  |
| 32 | Phạm Tấn Liệp | Phó trưởng Công an | 0948 999 080 | 02723860076 |  |  |
| 33 | Lê Ngọc Đông | Phó trưởng Công an | 0903 080 020 | 02723860076 |  |  |
| 34 | Tạ Văn Lợi | Phó trưởng Công an | 0916 659 993 | 02723860076 |  |  |
| 35 | Nguyễn Hoài Hận | Phó trưởng Công an | 0989 951 195 | 02723860076 |  |  |
| 36 | Phạm Toàn Định | Phó trưởng Công an | 0772 020 807 | 02723860076 |  |  |
| 37 | Phạm Huy Mạnh | UV.BTV - CHT BCH Quân sự | 0368 195 107 |  |  |  |
| 38 | Lê Thanh Hùng | UV.BCH-PCHT.BCHQS xã | 0989 602 373 |  |  |  |

### Xã Vĩnh Thạnh

- Nhóm: 1
- Mã/STT nhóm: 17

### Đảng ủy xã Vĩnh Thạnh - Địa chỉ: . . .

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 1 | Nguyễn Thành Phương | Bí thư - CT. HĐND xã | 0918 713 340 |  |  |  |
| 2 | Lê Văn Thủy | Phó Bí thư | 0918 593 866 |  |  |  |
| 3 | Đặng Thị Thu Vui | UV BTV - CN UBKT ĐU - / TB KT. HĐND xã | 0785 942 779 |  |  |  |
| 4 | Nguyễn Tấn Đạt | UV BCH - PCN UBKTĐU xã | 0964 913 183 |  |  |  |
| 5 | Nguyễn Văn Tăng | UV BTV - TB Xây dựng đảng | 0975 209 618 |  |  |  |
| 6 | Trần Phú Thuận | UV BCH - PTB Xây dựng đảng | 0918 896 133 |  |  |  |
| 7 | Trần Quốc Hữu | UV BCH - CVP Đảng ủy xã | 0919 599 489 |  |  |  |
| 8 | Châu Phú Hiệp | UV BCH - CT MTTQ xã - / TB VHXH. HĐND xã | 0917 380 587 |  |  |  |
| 9 | Nguyễn Thị Diễm Phương | UV BCH - PCT MTTQ, CT Hội PN | 0834 656 768 |  |  |  |
| 10 | Võ Hùng Kiệt | UV BCH - PCT MTTQ, CT Hội ND | 0918 886 875 |  |  |  |
| 11 | Trần Quốc Tuấn | UV BCH - PCT MTTQ, BT Đoàn TN | 0393 900 363 |  |  |  |
| 12 | Nguyễn Văn Lâm | PCT MTTQ - CT HCCB | 0948 679 759 |  |  |  |

### HĐND xã - Địa chỉ: . . .

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 13 | Lâm Văn Hồng | Phó CT HĐND | 0984 445 639 |  |  |  |
| 14 | Phạm Thanh Phong | Ban Kinh tế - HĐND | 0942 593 036 |  |  |  |
| 15 | Huỳnh Thị Lê | Ban VHXH - HĐND | 0986 610 595 |  |  |  |

### UBND xã - ĐT bàn: ……..; email: ubndvinhthanh@tayninh.gov.vn

### Địa chỉ: Ấp Gò Gòn xã Vĩnh Thạnh, Tây Ninh

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 16 | Nguyễn Hồng Kha | Phó Bí thư - CT UBND | 0908 715 292 |  |  |  |
| 17 | Phạm Thanh Hùng | UVBTV - PCT UBND | 0918 338 766 |  |  |  |
| 18 | Nguyễn Văn Nghĩa | UV BTV - PCT UBND | 0913 686 882 |  |  |  |
| 19 | Nguyễn Thị Ánh Ngọc | UV BCH - CVP HĐND và UBND xã | 0974 247 724 |  |  |  |
| 20 | Nguyễn Hoàng Anh | PCVP HĐND và UBND xã | 0941 363 739 |  |  |  |
| 21 | Ngân Văn Giang | UV BCH - Trưởng phòng kinh tế xã | 0833 554 448 |  |  |  |
| 22 | Nguyễn Văn Thanh | Phó Trưởng phòng kinh tế xã | 0969 346 162 |  |  |  |
| 23 | Nguyễn Thị Liễu | UV BCH - TP Văn hóa - Xã Hội xã | 0979 861 448 |  |  |  |
| 24 | Nguyễn Minh Chửng | PTP Văn hóa - Xã Hội xã | 0946 970 616 |  |  |  |
| 26 | Lâm Văn Khánh | PGĐ Trung tâm Hành chính công | 0919 990 924 |  |  |  |
| 27 | Mai Tuyết Quyên | UV BCH - GĐ TT Cung ứng DVSN công | 0919 588 550 |  |  |  |
| 28 | Nguyễn Thị Thu Vân | PGĐ TT Cung ứng DVSN công | 0949 168 138 |  |  |  |
| 29 | Nguyễn Văn Cải | UV BCH - Trưởng Công an xã | 0909 932 218 |  |  |  |
| 30 | Nguyễn Văn Em | Phó trưởng Công an xã | 0825 666 499 |  |  |  |
| 31 | Nguyễn Giải Phóng | Phó trưởng Công an xã | 0983 836 937 |  |  |  |
| 32 | Huỳnh Văn Thức | Phó trưởng Công an xã | 0933 678 094 |  |  |  |
| 33 | Thân Ngọc Lương | Phó trưởng Công an xã | 0986 610 585 |  |  |  |
| 34 | Phan Thanh Tùng | Phó trưởng Công an xã | 0372 842 901 |  |  |  |
| 35 | Lê Quốc Khánh | CHT Ban CHQS xã | 0982 990 443 |  |  |  |
| 36 | Trần Chí Bửu | PCHT Ban CHQS xã | 0785 114 695 |  |  |  |

### XÃ VĨNH CHÂU

- Nhóm: 1
- Mã/STT nhóm: 18

### Đảng ủy - Địa chỉ: Ấp Vĩnh Ân, xã Vĩnh Châu

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 1 | Huỳnh Thanh Hiền | Bí thư - Chủ tịch HĐND | 0918 449 186 |  |  |  |
| 2 | Nguyễn Thanh Hải | Phó Bí thư Thường trực | 0918 898 498 |  |  |  |
| 3 | Nguyễn Anh Văn | UV BTV - CN UBKT | 0942 919 579 |  |  |  |
| 4 | Trần Văn Học | UV BCH - PCN UBKT | 0909 676 650 |  |  |  |
| 5 | Đoàn Thái Ngọc | UV BTV - TB Xây dựng đảng | 0918 103 411 |  |  |  |
| 6 | Nguyễn Thị Giàu | UV BCH - PTB Xây dựng đảng | 0842 955 788 |  |  |  |
| 7 | Phạm Văn Tuân | UV BCH - CVP Đảng ủy | 0944 708 333 |  |  |  |
| 8 | Nguyễn Thị Lệ Huyền | UV BTV - CT MTTQ xã | 0948 129 247 |  |  |  |
| 9 | Dương Thị Thúy Nhanh | UV BCH - PCT MTTQ, CT Hội PN | 0988 808 276 |  |  |  |
| 10 | Trần Văn Minh | UV BCH - PCT MTTQ, CT Hội ND | 0944 008 676 |  |  |  |
| 11 | Trương Thành Phát | UV BCH - PCT MTTQ, BT Đoàn TN | 0393 073 565 |  |  |  |

### Hội đồng nhân dân - Địa chỉ: Ấp Vĩnh Ân, xã Vĩnh Châu

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 12 | Trần Hữu Phúc | UV BTV - PCT HĐND | 0909 356 145 |  |  |  |
| 13 | Nguyễn Văn Ken | UV BCH - Phó Ban KT-NS HĐND | 0972 948 980 |  |  |  |
| 14 | Nguyễn Văn Hào | UV BCH - Phó Ban VH-XH HĐND | 0919 404 052 |  |  |  |

### Ủy ban nhân dân - ĐT bàn: 02723 987 989; email: ubndvinhchau@tayninh.gov.vn

### Địa chỉ: Ấp Vĩnh Ân, xã Vĩnh Châu

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 15 | Nguyễn Văn Chi | Phó Bí thư - CT UBND | 0909 170 202 |  |  |  |
| 16 | Mai Văn Cảm | UV BTV - PCT UBND - GĐ TT PV HCC | 0856 566 557 |  |  |  |
| 17 | Nguyễn Văn Mến | UV BCH - PCT UBND | 0917 171 132 |  |  |  |
| 18 | Lê Quang Lế | UV BCH - CVP HĐND và UBND | 0944 993 978 |  |  |  |
| 19 | Lê Văn Quậy | PCVP HĐND và UBND | 0946 245 474 |  |  |  |
| 20 | Phan Văn Nỉ | UV BCH - Trưởng phòng kinh tế | 0948 239 507 |  |  |  |
| 21 | Phạm Ngọc Cát | PTP kinh tế | 0918 855 992 |  |  |  |
| 22 | Nguyễn Ngọc Toàn | UV BCH - TP Văn hóa - Xã hội | 0918 029 245 |  |  |  |
| 23 | Bùi Văn Hồng | PTP Văn hóa - Xã hội | 0918 898 466 |  |  |  |
| 24 | Bùi Thị Kim Nghĩa | UV BCH - PGĐ TT Phục vụ HCC | 0913 862 432 |  |  |  |
| 25 | Võ Mạnh Tùng | UV BCH - GĐ TT Cung ứng DVSN công | 0937 472 082 |  |  |  |
| 26 | Võ Thành Thuận | PGĐ TT Cung ứng DVSN công | 0919 870 988 |  |  |  |
| 27 | Trương Thanh Hoài | UV BTV - Trưởng Công an | 0824 849 484 |  |  |  |
| 28 | Lê Văn Tùng | UV BTV - CHT BCH Quân sự | 349944884 |  |  |  |

### XÃ VĨNH HƯNG

- Nhóm: 1
- Mã/STT nhóm: 19

### Đảng ủy Vĩnh Hưng _ Địa chỉ: Số 18, đường 30/4, ấp Măng Đa, xã Vĩnh Hưng

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 1 | Nguyễn Tuấn Anh | Bí thư - CT HĐND | 0918 701 441 | 02723 971 750 |  |  |
| 2 | Phạm Thị Kiều Phương | Phó Bí thư Thường trực | 0907 596 939 |  |  |  |
| 3 | Trần Văn Khánh | UV BTV - CN UBKT | 0812 663 664 |  |  |  |
| 4 | Võ Minh Kha | UV BCH - PCN UBKT | 0986 399 821 |  |  |  |
| 5 | Ngô Hoàng Nam | UV BTV - TB Xây dựng đảng | 0911 678 789 |  |  |  |
| 6 | Phạm Thị Thúy Nga | UV BCH - PTB Xây dựng đảng | 0972 633 066 |  |  |  |
| 7 | Nguyễn Thị Phương Linh | UV BCH - CVP Đảng ủy | 0986 977 118 |  |  |  |
| 8 | Nguyễn Việt Trung | UV BTV - CT MTTQ xã | 0909 356 116 |  |  |  |
| 9 | Trần Thị Huệ | UV BCH - PCT MTTQ, CT Hội PN | 0942 711 083 |  |  |  |
| 10 | Hồ Trọng Hải | UV BCH - PCT MTTQ, CT Hội ND | 0972 633 056 |  |  |  |
| 11 | Nguyễn Minh Cường | UV BCH - PCT MTTQ, BT Đoàn TN | 0815 819 737 |  |  |  |
| 12 | Nguyễn Ngọc Sương | UV BCH - PCT MTTQ, CT Hội CCB | 0983 848 675 |  |  |  |

### Hội đồng nhân dân - Địa chỉ: Số 16, đường 30/4, ấp Măng Đa, xã Vĩnh Hưng

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 13 | Nguyễn Thanh Toàn | UV BTV - PCT HĐND | 0918 091 197 | 02723 847 252 |  |  |
| 14 | Nguyễn Thị Ngọc Hằng | UV BCH - Ban Kinh tế - HĐND | 0943 784 208 |  |  |  |
| 15 | Lê Đại Sĩ | UV BCH - Ban VHXH - HĐND | 0975 717 126 |  |  |  |

### Ủy ban nhân dân xã - ĐT bàn: 02723 847 252; email: ubndvinhhung@tayninh.gov.vn

### Địa chỉ: Số 16, đường 30/4, ấp Măng Đa, xã Vĩnh Hưng, Tây Ninh

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 16 | Nguyễn Văn Tuấn | Phó Bí thư - CT UBND | 0917 936 195 |  |  |  |
| 17 | Bùi Văn Tỉnh | UV BTV - PCT UBND | 0918 129 321 |  |  |  |
| 18 | Nguyễn Thị Cẩm Huyền | UV BTV - PCT UBND | 0983 847 210 |  |  |  |
| 19 | Phan Thị Thanh Tâm | UV BCH - CVP HĐND và UBND | 0987 003 736 |  |  |  |
| 20 | Nguyễn Văn Cường | PCVP HĐND và UBND | 0908 818 312 |  |  |  |
| 21 | Phan Thành Gẩm | UV BCH - Trưởng phòng kinh tế | 0918 019 198 |  |  |  |
| 22 | Đinh Châu Phong | PTP kinh tế | 0786 235 362 |  |  |  |
| 23 | Nguyễn Thị Kim Hạnh | UV BCH - TP Văn hóa - Xã hội | 0819 001 079 |  |  |  |
| 24 | Nguyễn Hoàng Hiếu | PTP Văn hóa - Xã hội | 0906 769 869 |  |  |  |
| 25 | Nguyễn Thị Cẩm Huyền | UVBTV - PCT UBND - / GĐ TT Hành chính công | 0983 847 210 |  |  |  |
| 26 | Nguyễn Bảo Ngân | PGĐ TT Hành chính công | 0947 096 878 |  |  |  |
| 27 | Nguyễn Tiến Phúc | GĐ TT Cung ứng DVSN công | 0902 945 999 |  |  |  |
| 28 | Nguyễn Quốc Tuấn | PGĐ TT Cung ứng DVSN công | 0918 881 810 |  |  |  |

### Công an _ Địa chỉ: Số 46, đường Long Khốt, ấp Măng Đa, xã Vĩnh Hưng

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 29 | Đoàn Chí Hải | UV BTV - Trưởng Công an | 0918 897 910 |  |  |  |
| 30 | Khuất Văn Ly | UV BCH Phó trưởng Công an | 0945 089 117 |  |  |  |

### BCH Quân sự - Địa chỉ: Số 01, đường Tháp Mười, ấp 2, xã Vĩnh Hưng

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 31 | Lê Tấn Lộc | UV BTV - CHT BCH Quân sự | 0974 433 441 |  |  |  |
| 32 | Lê Văn Trạch | UVBCH - Phó CHT BCHQS xã | 0983 495 421 |  |  |  |

### TT Chính trị - / Địa chỉ: Đường Nguyễn Văn Tịch, ấp Măng Đa, xã Vĩnh Hưng

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 33 | Nguyễn Thị Thanh Thúy | UV BCH - GĐ TT Chính trị | 0818 638 668 |  |  |  |

### XÃ TUYÊN BÌNH

- Nhóm: 1
- Mã/STT nhóm: 20

### Ấp 1, xã Tuyên Bình

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 1 | Võ Văn Bảo | Bí thư Đảng ủy - Chủ tịch HĐND | 0849 499 977 | 02723 848 606 |  | Ấp 1, xã Tuyên Bình |
| 2 | Nguyễn Việt Hồng | Phó Bí thư thường trực Đảng ủy | 0979 895 509 | 02723 848 606 |  | Ấp 1, xã Tuyên Bình |
| 3 | Võ Văn Cho | PCT HĐND kiêm TB Kinh tế - Ngân sách | 0918 245 039 | 02723 847 295 |  | Ấp 1, xã Tuyên Bình |
| 4 | Trần Tấn Nhỏ | Phó Bí thư, Chủ tịch UBND | 0918 701 442 | 02723 847 295 |  | Ấp 1, xã Tuyên Bình |
| 5 | Tạ Thành Đô | PCT UBND (Kinh tế) | 0813 130 606 | 02723 847 295 |  | Ấp 1, xã Tuyên Bình |
| 6 | Võ Hồng Lĩnh | PCT UBND (VHXH) | 0986 296 046 | 02723 847 295 |  | Ấp 1, xã Tuyên Bình |
| 7 | Nguyễn Văn Lên | Chánh Văn phòng Đảng ủy | 0918 499 086 | 02723 848 606 |  | Ấp 1, xã Tuyên Bình |
| 8 | Lê Minh Nhuệ | Phó Chánh Văn phòng Đảng ủy | 0942 696 972 | 02723 848 606 |  | Ấp 1, xã Tuyên Bình |
| 9 | Dương Thanh Minh | Trưởng Ban Xây dựng Đảng | 0987 996 855 | 02723 848 606 |  | Ấp 1, xã Tuyên Bình |
| 10 | Nguyễn Vũ Long | PTB Xây dựng Đảng | 0367 933 117 | 02723 848 606 |  | Ấp 1, xã Tuyên Bình |
| 11 | Bùi Đức Thọ | CN UBKT kiêm TB Văn hóa - Xã hội HĐND | 0969 196 379 | 02723 848 606 |  | Ấp 1, xã Tuyên Bình |
| 12 | Vũ Thị Hoàn | Phó CN UBKT | 0913 744 727 | 02723 848 606 |  | Ấp 1, xã Tuyên Bình |
| 13 | Nguyễn Văn Sự | Chủ tịch MTTQ | 0918 430 163 | 02723 848 904 |  | Ấp 1, xã Tuyên Bình |
| 14 | Võ Thị Cẩm Hồng | PCT MTTQ kiêm Chủ tịch Hội LHPN | 0985 475 382 | 02723 848 904 |  | Ấp 1, xã Tuyên Bình |
| 15 | Trần Chí Tâm | PCT MTTQ kiêm Chủ tịch Hội Nông dân | 0989 944 535 | 02723 848 904 |  | Ấp 1, xã Tuyên Bình |
| 16 | Nguyễn Minh Tấn | PCT MTTQ kiêm Bí thư Đoàn | 0989 919 545 | 02723 848 904 |  | Ấp 1, xã Tuyên Bình |
| 17 | Nguyễn Minh Dũng | PCT MTTQ kiêm Chủ tịch Hội CCB | 0818 881 587 | 02723 848 904 |  | Ấp 1, xã Tuyên Bình |
| 18 | Nguyễn Vinh Quốc | Phó Ban Kinh tế - Ngân sách, HĐND | 0907 133 284 | 02723 847 295 |  | Ấp 1, xã Tuyên Bình |
| 19 | Nguyễn Quốc Phong | Phó Ban Văn hóa - Xã hội, HĐND | 0918 895 683 | 02723 847 295 |  | Ấp 1, xã Tuyên Bình |
| 20 | Đào Hoàng Nam | Chánh Văn phòng | 0984 512 070 | 02723 847 295 |  | Ấp 1, xã Tuyên Bình |
| 21 | Hồ Sĩ Đỉnh | Phó Chánh Văn phòng | 0983 973 600 | 02723 847 295 |  | Ấp 1, xã Tuyên Bình |
| 22 | Hồ Minh Cần | Trưởng phòng | 0918 029 246 | 02723 975 588 |  | Ấp 1, xã Tuyên Bình |
| 23 | Trần Văn Tài | Phó Trưởng phòng | 0379 506 609 | 02723 975 588 |  | Ấp 1, xã Tuyên Bình |
| 24 | Ngô Tráng Sỉ | Trưởng phòng | 0918 897 443 | Chưa có |  | Ấp 1, xã Tuyên Bình |
| 25 | Võ Văn Tánh | Phó Trưởng phòng | 0395 070 313 | Chưa có |  | Ấp 1, xã Tuyên Bình |
| 26 | Trần Thị Hiền | Phó Giám đốc | 0815 832 344 | 02726 292 888 |  | Ấp 1, xã Tuyên Bình |
| 27 | Nguyễn Xuân Hùng | Giám đốc | 0972 747 287 | Chưa có |  | Ấp 1, xã Tuyên Bình |
| 28 | Huỳnh Văn Phương | Phó Giám đốc | 0947 776 064 | Chưa có |  | Ấp 1, xã Tuyên Bình |
| 29 | Nguyễn Minh Vững | Trưởng Công an | 0909 437 222 | 02726 540 888 |  | Ấp Rạch Mây, xã Tuyên Bình |
| 30 | Nguyễn Văn Dụ | Phó Trưởng Công an | 0918 085 809 | 02726 540 888 |  | Ấp Rạch Mây, xã Tuyên Bình |
| 31 | Huỳnh Văn Lắm | Phó Trưởng Công an | 0907 807 555 | 02726 540 888 |  | Ấp Rạch Mây, xã Tuyên Bình |
| 32 | Lê Trọng Nhân | Phó Trưởng Công an | 0909 676 967 | 02726 540 888 |  | Ấp Rạch Mây, xã Tuyên Bình |
| 33 | Trần Quốc Tuấn | Phó Trưởng Công an | 0945 612 315 | 02726 540 888 |  | Ấp Rạch Mây, xã Tuyên Bình |
| 34 | Huỳnh Công Toại | Phó Trưởng Công an | 0963 567 006 | 02726 540 888 |  | Ấp Rạch Mây, xã Tuyên Bình |
| 35 | Tô Hoàng Sơn | CHT.QS xã | 0798 593 406 | Chưa có |  | Ấp Trung Trực, xã Tuyên Bình |
| 36 | Trần Trung Kiên | CHP.QS xã | 0784 466 496 | Chưa có |  | Ấp Trung Trực, xã Tuyên Bình |

### XÃ KHÁNH HƯNG

- Nhóm: 1
- Mã/STT nhóm: 21

### Ấp Gò Châu Mai xã Khánh Hưng

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 1 | Trần Văn Cường | Bí thư - CT HĐND | 0918 532 185 |  |  |  |
| 2 | Châu Thanh Đăng | Phó Bí thư TT.ĐU | 0943 242 309 |  |  |  |
| 3 | Trần Văn Bằng | Phó Bí thư - CT.UBND | 0914 756 223 |  |  |  |
| 4 | Huỳnh Hoàng Lam | UV BTV - PCT.HĐND | 0919 249 739 |  |  |  |
| 5 | Nguyễn Hoàng Em | UV BTV - PCT UBND | 0913 165 138 |  |  |  |
| 6 | Lê Minh Ngọc | UV BTV - PCT UBND | 0919 425 240 |  |  |  |
| 7 | Trương Hồng Non | UV BTV - TB XDĐ | 0944 977 118 |  |  |  |
| 8 | Lê Hoàng Vũ | UV BTV - CN. UBKT | 0983 696 320 |  |  |  |
| 9 | Nguyễn Minh Luân | UV BTV - CT.UBMTTQ | 0829 294 929 |  |  |  |
| 10 | Lê Văn Dốn | UV BTV - CHT. BCH Quân sự | 0974 666 506 |  |  |  |
| 11 | Nguyễn Văn Dân | UV BTV - Trưởng Công an | 0909 300 879 |  |  |  |
| 12 | Trần Hữu Hiệp | UV BCH - CVP HĐND và UBND | 0366 538 707 |  |  |  |
| 13 | Nguyễn Thanh Tùng | UV BCH - Tr Phòng Kinh tế | 0823 413 681 |  |  |  |
| 14 | Phạm Minh Phụng | UV BCH - Tr Phòng VH - XH | 0983 828 966 |  |  |  |
| 15 | Lê CThạo | UV BCH - PGĐ.TTHCC | 0983 961 157 |  |  |  |
| 16 | Nguyễn Văn Măng | UV BCH - PTB.XDĐ | 0944 644 084 |  |  |  |
| 17 | Nguyễn Thị Kốl Ka | UV BCH - PCN.UBKT | 0949 134 499 |  |  |  |
| 18 | Huỳnh Văn Trúc Nhơn | UV BCH - Chánh VP Đảng ủy | 0385 405 014 |  | Ấp Bắc chan 1, xã Tuyên Thạnh |  |
| 19 | Võ Điền Phú | UV BCH - PCHT.BCH Quân sự | 0375 196 741 |  | Ấp Bắc chan 1, xã Tuyên Thạnh |  |
| 20 | Đặng Văn Bảng | UV BCH - Phó trưởng Công an | 0832 898 389 |  | Ấp Sồ Đô, Xã Tuyên Thạnh |  |
| 21 | Võ Thị Nhanh | UV BCH - Phó ban KT-NS | 0987 116 260 |  | Ấp Sồ Đô, Xã Tuyên Thạnh |  |
| 22 | Huỳnh Văn Xuyên | UV BCH - Phó ban VH-XH | 0907 748 981 |  | Ấp Sồ Đô, Xã Tuyên Thạnh |  |
| 23 | Trương Văn Hải | UV BCH-PCT.MTTQ-CT.HCCB | 0979 569 012 |  | Ấp Sồ Đô, Xã Tuyên Thạnh |  |
| 24 | Lê Quốc Bổn | UV BCH - PCT.MTTQ-CT. HND | 0815 158 477 |  | Ấp Bắc chan 1, xã Tuyên Thạnh |  |
| 25 | Phạm Thị Ngọc Hải | UV BCH -PCT.MTTQ-CT. HPN | 0384 305 097 |  | Ấp Bắc chan 1, xã Tuyên Thạnh |  |
| 26 | Trương Hữu Tài | UV BCH -PCT.MTTQ - BT.ĐTN | 0939 139 761 |  | Ấp Bắc chan 1, xã Tuyên Thạnh |  |
| 27 | Bùi Văn Hiệu | GĐ. TTCUDVC | 0909 163 323 |  | Ấp Sồ Đô, Xã Tuyên Thạnh |  |
| 28 | Phạm Thị Chiêu Sa | Phó chánh VP HĐND-UBND | 0867 823 824 |  | Ấp Sồ Đô, Xã Tuyên Thạnh |  |
| 29 | Nguyễn Thành Khoang | PTP Kinh tế | 0937 453 876 |  | Ấp Sồ Đô, Xã Tuyên Thạnh |  |
| 30 | Trần Thanh Thịnh | Phó trường phòng VH-XH | 0983 707 000 |  | Ấp Bắc chan 1, xã Tuyên Thạnh |  |
| 31 | Nguyễn Văn Truyền | Phó chánh VP ĐU | 0986 777 118 |  | Ấp Sồ Đô, Xã Tuyên Thạnh |  |

### XÃ BÌNH HIỆP

- Nhóm: 1
- Mã/STT nhóm: 22

### Đảng ủy xã Bình Hiệp - Địa chỉ: Ấp Bình tây 1, xã Bình Hiệp

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 1 | Nguyễn Thị Lụa | Bí thư Đảng ủy - CT HĐND | 0948 859 868 | 02723 956 869 | luant@tayninh.gov.vn |  |
| 2 | Nguyễn Thành Được | Phó Bí thư Đảng ủy | 0919 126 795 |  | duocnt@tayninh.gov.vn |  |
| 3 | Bùi Thùy Trang | UV BTV - CN UBKT ĐU xã | 0983 951 094 |  | trangbt.binhhiep@tayninh.gov.vn |  |
| 4 | Lê Thiện An | UV BCH - Phó CN UBKTĐU xã | 0838 800 905 |  | an.binhhiep@tayninh.gov.vn |  |
| 5 | Võ Đình Long | UV BTV - TB Xây dựng đảng | 0838 027 776 |  | long.binhhiep@tayninh.gov.vn |  |
| 6 | Nguyễn Tấn Cần | UV BCH - PTB Xây dựng đảng | 0949 197 992 |  | cannt.binhhiep@tayninh.gov.vn |  |
| 7 | Nguyễn Thị Kim Anh | UV BCH - CVP Đảng ủy xã | 0966 186 511 |  | ntkanh@tayninh.gov.vn |  |
| 8 | Lý Minh Vũ | Phó Chánh VP Đảng ủy xã | 0916 345 287 |  | phut.binhhiep@tayninh.gov.vn |  |
| 9 | Nguyễn Thanh Phú | UV BTV - CT MTTQ xã | 0918 417 174 |  |  |  |
| 10 | Nguyễn Thị Anh Thư | UV BCH - PCT MTTQ, CT Hội LHPN xã | 0947 160 164 |  |  |  |
| 11 | Nguyễn Thanh Bình | UV BCH - PCT MTTQ, CT Hội nông dân xã | 0834 008 078 |  |  |  |
| 12 | Nguyễn Thị Kim Thảo | UV BCH - PCT MTTQ, BT Đoàn TN | 0919 320 035 |  |  |  |
| 13 | Phạm Văn Bìa | Chủ tịch Hội cựu chiến binh | 0889 937 854 |  |  |  |

### HĐND xã Bình Hiệp - Địa chỉ: Ấp ông Nhan tây, xã Bình Hiệp

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 14 | Nguyễn Thị Lụa | Bí thư Đảng ủy - CT HĐND | 0948859868 |  |  |  |
| 15 | Bùi Thùy Trang | UV BTV - CN UBKT -TB KT - NS - HĐND | 0983951094 |  |  |  |
| 16 | Nguyễn Mạnh Hùng | UV BCH -PB KT-NS - HĐND | 0912579480 |  | hung.binhhiep@tayninh.gov.vn |  |
| 17 | Nguyễn Thị Kim Duyên | UV BTV - PCT.HĐND - TB VHXH - HĐND | 812535727 |  | duyen.binhhiep@tayninh.gov.vn |  |
| 18 | Nguyễn Thành Ngoan | UV BCH-PB VHXH - HĐND | 916237364 |  | ngoan.binhhiep@tayninh.gov.vn |  |

### UBND xã - ĐT bàn: 02723.952.345 ; email: ubndbinhhiep@tayninh.gov.vn

### Địa chỉ: Ấp Ông Nhan Tây, xã Bình Hiệp, Tây Ninh

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 19 | Nguyễn Hữu Trọng | Phó Bí thư - CT UBND | 0917 155 551 |  | trongnh.binhhiep@tayninh.gov.vn |  |
| 20 | Huỳnh Thanh Tâm | UV BTV - PCT UBND - GĐTT hành chính công | 0907 082 927 |  | tamht.binhhiep@tayninh.gov.vn |  |
| 21 | Lê Hoàng Thiện | UV BTV - PCT UBND | 0847 214 721 |  | thien.binhhiep@tayninh.gov.vn |  |
| 22 | Trương Văn Thanh | UV BCH - CVP HĐND và UBND xã | 0918 891 914 |  | thanh.binhhiep@tayninh.gov.vn |  |
| 23 | Dương Thị Tú Xuân | PCVP HĐND và UBND xã | 0975 248 490 |  | xuan.binhiep@tayninh.gov.vn |  |
| 24 | Ngô Hữu Đức | UV BCH - Trưởng phòng kinh tế xã | 0913 959 957 |  | duc.binhhiep@tayninh.gov.vn |  |
| 25 | Lê Hùng Nhớ | Phó Trưởng phòng kinh tế xã | 0981 801 328 |  | nho.binhhiep@tayninh.gov.vn |  |
| 26 | Phạm Anh Phương | UV BCH - TP Văn hóa - Xã hội | 0915 841 277 |  | phuongpa.binhhiep@tayninh.gov.vn |  |
| 27 | Mai Hùng Vương | PTP Văn hóa - Xã hội | 0916 535 729 |  | vuong.binhhiep@tayninh.gov.vn |  |
| 28 | Trương Văn Y | UV BCH-PGĐ TT Hành chính công | 0918 461 440 |  | ytv.binhhiep@tayninh.gov.vn |  |
| 29 | Ngô Hữu Toàn | GĐ TT Cung ứng DVSN công | 0839 263 456 |  | toannh.binhiep@tayninh.gov.vn |  |
| 30 | Trần Thái Hoài Phương | PGĐ TT Cung ứng DVSN công | 0989 232 596 |  | phuongttt.binhhiep@tayninh.gov.vn |  |
| 31 | Võ Văn Lộc | UV BTV - Trưởng Công an | 0834 770 307 | 02723 951 949 |  |  |
| 32 | Đoàn Quý | Phó trưởng Công an | 375560009 | 02723 951 949 |  |  |
| 33 | Nguyễn Văn Công | Phó trưởng Công an | 918897969 | 02723 951 949 |  |  |
| 34 | Đặng Thanh Hội | UV BCH - Phó trưởng Công an | 947971397 | 02723 951 949 |  |  |
| 35 | Nguyễn Hữu Lộc | Phó trưởng Công an | 347999113 | 02723 951 949 |  |  |
| 36 | Hà Minh Quang | Phó trưởng Công an | 0946 146 235 | 02723 951 949 |  |  |
| 37 | Nguyễn Thành Nam | UVBTV - CHT BCH Quân sự | 0944 456 485 |  |  |  |
| 38 | Nguyễn Hoàng Phúc | UV BCH - PCHT BCH Quân sự | 0344 810 099 |  |  |  |

### XÃ TUYÊN THẠNH

- Nhóm: 1
- Mã/STT nhóm: 23

### Ấp Sồ Đô, Xã Tuyên Thạnh

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 1 | Lê Hồng Hạnh | Bí thư - CT HĐND | 0917 453 030 |  | Ấp Sồ Đô, Xã Tuyên Thạnh |  |
| 2 | Lâm Thị Thúy Hằng | Phó Bí thư | 0942 058 772 |  | Ấp Sồ Đô, Xã Tuyên Thạnh |  |
| 3 | Lâm Tấn Đạt | Phó Bí thư - CT UBND | 0918 788 345 |  | Ấp Sồ Đô, Xã Tuyên Thạnh |  |
| 4 | Hà Quốc Nhủ | PCT HĐND | 0933 818 982 |  | Ấp Bắc chan 1, xã Tuyên Thạnh |  |
| 5 | Nguyễn Thị Kim Dút | PCT UBND | 0942 578 292 |  | Ấp Bắc chan 1, xã Tuyên Thạnh |  |
| 6 | Nguyễn Hùng Dũng | PCT UBND | 0918 937 947 |  | Ấp Bắc chan 1, xã Tuyên Thạnh |  |
| 7 | Lâm Hoà Đông | CN UBKT | 0918 430 070 |  |  |  |
| 8 | Nguyễn De Goonl | TB Xây dựng Đảng | 0817 682 485 |  |  |  |
| 9 | Phạm Thanh Sang | Chủ tịch UBMTTQ | 0918 896 626 |  |  |  |
| 10 | Nguyễn Hoàng Nhựt | CVP HĐND và UBND | 0849 765 795 |  |  |  |
| 11 | Nguyễn Phú Quốc | Trưởng Phòng Văn hóa - Xã hội | 0854 310 125 |  |  |  |
| 12 | Dương Tuấn Anh | Trưởng Phòng Kinh tế | 0984 924 337 |  |  |  |
| 13 | Trần Kỉnh Đức | PCT UBMTTQ | 0919 847 716 |  |  |  |
| 14 | Nguyễn Văn Bình Em | PTB Kinh tế | 0918 895 710 |  |  |  |
| 15 | Trần Quốc Thắng | CVP Đảng ủy | 0388 449 799 |  |  |  |
| 16 | Trương Duy Phong | PGĐ TTPVHCC | 0976 699 797 |  |  |  |
| 17 | Lê Thanh Tuấn | Phó TB Xây dựng Đảng | 0838 028 992 |  |  |  |
| 18 | Trần Thị Thiện | PCT Hội Liên hiệp Phụ nữ | 0835 158 626 |  |  |  |
| 19 | Võ Thị Anh Thư | PTB VH-XH | 0834 240 557 |  |  |  |
| 20 | Trần Hải Đăng | Phó Trưởng Công an | 0948 066 949 |  |  |  |
| 21 | Huỳnh Văn Ngoan | Trưởng Công an | 0916 634 018 |  |  |  |
| 22 | Trương Thái Trung | CHT BCHQS | 0976 393 642 |  |  |  |
| 23 | Phạm Đăng Trung | Chỉ huy Phó BCHQS | 0976 393 642 |  |  |  |
| 24 | Phạm Hoàng Phi | PCN UBKT | 0383 188 201 |  |  |  |

### XÃ MỘC HÓA

- Nhóm: 1
- Mã/STT nhóm: 24

### Đảng ủy Mộc Hóa, - Địa chỉ: đường 30/4, ấp Cả Đá, xã Mộc Hóa

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 1 | Nguyễn Văn Vũ | Bí thư | 0918 445 638 |  |  |  |
| 2 | Phan Thị Tuyết Sương | Phó Bí thư | 0915 573 919 |  |  |  |
| 3 | Lâm Thanh Thao | UV BTV - CN UBKT | 0945 245 688 |  |  |  |
| 4 | Nguyễn Duy Phương | UV BCH - PCN UBKT | 0905 048 339 |  |  |  |
| 5 | Ngô Thị Hồng Thanh | UV BTV - TB Xây dựng đảng | 0364 532 972 |  |  |  |
| 6 | Phạm Văn Mến | UV BCH - PTB Xây dựng đảng | 0917 689 541 |  |  |  |
| 7 | Lê Văn Đoàn | UV BCH - CVP Đảng ủy | 0349 578 573 |  |  |  |
| 8 | Phan Thị Khánh Vâng | UV BTV - CT MTTQ xã | 0943 684 699 |  |  |  |
| 9 | Nguyễn Thị Vàng | UV BCH - PCT MTTQ, CT Hội PN | 0918 955 635 |  |  |  |
| 10 | Lê Văn Tùng | UV BCH - PCT MTTQ, CT Hội ND | 0962 139 932 |  |  |  |
| 11 | Nguyễn Thị Yến Thu | UV BCH - PCT MTTQ, BT Đoàn TN | 0347 010 626 |  |  |  |
| 12 | Đặng Hoài Vũ | PCT MTTQ, CT Hội CCB | 0918 895 313 |  |  |  |
| 13 | Nguyễn Thị Điệp | UV BCH - GĐ TT Chính trị | 0948 789 063 |  |  |  |

### HĐND Mộc Hóa - Địa chỉ: đường 30/4, ấp Cả Đá, xã Mộc Hóa

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 14 | Phan Thị Tuyết Sương | Phó Bí thư - CT HĐND | 0915 573 919 |  |  |  |
| 15 | Lê Quốc Trưởng | UV BTV, Phó CT HĐND kiêm Trưởng / Ban Kinh tế - Ngân sách HĐND | 0987 151 512 |  |  |  |
| 16 | Lý Thị Nghiên | UV BCH, PTB Kinh tế - Ngân sách HĐND | 0945 242 421 |  |  |  |
| 17 | Lâm Thanh Thao | UV BTV, CH UBKT ĐU, Trưởng / Ban VHXH - HĐND | 0945 245 688 |  |  |  |
| 18 | Hồ Thị Hồng Cúc | UV BCH, PTB VHXH - HĐND | 0917 735 651 |  |  |  |

### UBND xã Mộc Hóa - ĐT: 02723 956 312 ; email: ubndmochoa@tayninh gov vn

### Địa chỉ: đường 30/4, ấp Cả Đá, xã Mộc Hóa

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 19 | Trương Tiến Dũng | Phó Bí thư - CT UBND | 0837 188 767 |  |  |  |
| 20 | Nguyễn Thanh Sang | UV BTV - PCT UBND | 0914 496 359 |  |  |  |
| 21 | Lê Xa Lem | UV BTV - PCT UBND | 0915 717 222 |  |  |  |
| 22 | Hà Quốc Linh | UV BCH - CVP HĐND và UBND | 0968 141 225 | 02723 956 312 |  |  |
| 23 | Đặng Văn Lâm | PCVP HĐND và UBND | 0972 917 311 |  |  |  |
| 24 | TRần Thị Kim Trúc | PCVP HĐND và UBND | 0835 158 562 |  |  |  |
| 25 | Bùi Văn Đoàn | UV BCH - Trưởng phòng kinh tế | 0948 131 919 | 02723 956 261 |  |  |
| 26 | Trần Thanh Vũ | UV BCH - TP Văn hóa - Xã hội | 0918 701 080 | 02723 956 677 |  |  |
| 27 | Nguyễn Thanh Sang | GĐ TT Hành chính công | 0914 496 359 |  |  |  |
| 28 | Nguyễn Vũ Thoại | UV BCH, GĐ TT Cung ứng DVSN công | 0914 256 491 | 02723 956 656 |  |  |
| 29 | Lâm Văn Chương | UV BTV - Trưởng Công an | 0918 256 287 |  |  |  |
| 30 | Đặng Nhật Trường | UV BTV - CHT BCH Quân sự | 0947 351 719 |  |  |  |
| 31 | Trần Văn Ninh | UV BCH - GĐ TTYT khu vực Mộc Hóa | 0918 617 303 |  |  |  |

### XÃ BÌNH HÒA

- Nhóm: 1
- Mã/STT nhóm: 25

### Đảng ủy Bình Hòa - Địa chỉ: Ấp 1 xã Bình Hòa tỉnh Tây Ninh

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 1 | Võ Minh Quốc | Bí thư | 097 506 0712 |  |  |  |
| 2 | Nguyễn Thị Thanh Hoa | Phó Bí thư | 0983 934 975 |  |  |  |
| 3 | Trần Anh Thông | UV BTV - CN UBKT | 0346 801 329 |  |  |  |
| 4 | Dương Tiến Vũ | UV BCH - PCN UBKT | 0966 644 663 |  |  |  |
| 5 | Nguyễn Phú Rạng | UV BTV - TB Xây dựng đảng | 0902 892 245 |  |  |  |
| 6 | Nguyễn Văn Nghiêm | UV BCH - PTB Xây dựng đảng | 0912 041 939 |  |  |  |
| 7 | Phạm Quốc Việt | UV BCH - PTB Xây dựng đảng | 0941 679 939 |  |  |  |
| 8 | Nguyễn Thành Luân | UV BCH - CVP Đảng ủy | 0935 494 398 |  |  |  |
| 9 | Lê Văn Phân | UV BTV - CT MTTQ xã | 0945 909 793 |  |  |  |
| 10 | Nguyễn Thị Quyên | UV BCH - PCT MTTQ, CT Hội PN | 0838 028 177 |  |  |  |
| 11 | Lê Minh Hoàng | UV BCH - PCT MTTQ, CT Hội ND | 0854 666 662 |  |  |  |
| 12 | Phạm Trọng Phú | UV BCH - PCT MTTQ, BT Đoàn TN | 0944 944 972 |  |  |  |
| 13 | Trương Thế Như | UV BCH - PCT MTTQ, CT Hội CCB | 0849 911 637 |  |  |  |

### HĐND Bình Hòa - Địa chỉ: Ấp Bình Nam xã Bình Hòa tỉnh Tây Ninh

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 14 | Nguyễn Thị Thanh Hoa | Phó Bí thư - CT HĐND | 0983 934 975 |  |  |  |
| 15 | Võ Thị Cẩm Tú | UV BTV ĐU - PCT HĐND kiêm TB Kinh tế - Ngân sách HĐND | 0845 443 499 |  |  |  |
| 16 | Lê Văn Phân | TB Văn hóa-Xã hội HĐND | 0945 909 793 |  |  |  |
| 17 | Võ Bạch Tuyết | PTB Kinh tế -Ngân sách HĐND | 0919 202 459 |  |  |  |
| 18 | Nguyễn Thị Kim Khánh | PTB Văn hóa-Xã hội HĐND | 0985 300 920 |  |  |  |

### UBND xã - ĐT bàn: 02723841545 ; email: ubndbinhhoa@tayninh.gov.vn

### Địa chỉ: Ấp Bình Nam xã Bình Hòa tỉnh Tây Ninh

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 19 | Nguyễn Thanh Nam | Phó Bí thư - CT UBND | 0989 625 503 |  |  |  |
| 20 | Lê CTrường | UVBTVĐU - PCT UBND | 0945 484 539 |  |  |  |
| 21 | Hoàng Thị Thùy Như | UVBTVĐU - PCT UBND | 0976 511 522 |  |  |  |
| 22 | Phạm Chí Cầm | CVP HĐND và UBND | 0836 843 547 |  |  |  |
| 23 | Lê Quốc Thi | PCVP HĐND và UBND | 0946 939 485 |  |  |  |
| 24 | Nguyễn Huỳnh Thanh | PCVP HĐND và UBND | 0947 351 666 |  |  |  |
| 25 | Võ Hữu Đức | Trưởng phòng kinh tế | 0836 282 868 |  |  |  |
| 26 | Lê Minh Nhật | PTP kinh tế | 0982 338 517 |  |  |  |
| 27 | Nguyễn Văn Hiệp | PTP kinh tế | 0835 021 234 |  |  |  |
| 28 | Đặng Thị Kim Thanh | PTP kinh tế | 0938 142 998 |  |  |  |
| 29 | Huỳnh Bá Diệu | TP Văn hóa - Xã hội | 0941 686 689 |  |  |  |
| 30 | Võ Văn Hiền | PTP Văn hóa - Xã hội | 0819 988 116 |  |  |  |
| 31 | Trần Quang Đăng | PTP Văn hóa - Xã hội | 0915 857 872 |  |  |  |
| 32 | Lê CTrường | PCT UBND - GĐ TT Hành chính công | 0945 484 539 |  |  |  |
| 33 | Nguyễn Duy Trường | PGĐ TT Hành chính công | 0919 202 048 |  |  |  |
| 34 | Nguyễn Thành Phuông | GĐ TT Cung ứng DVSN công | 0949 036 464 |  |  |  |
| 35 | Lê Chí Trung | PGĐ TT Cung ứng DVSN công | 0854 818 959 |  |  |  |
| 36 | Bùi Tuấn Ninh | UVBTVĐU - Trưởng Công an | 0907 168 864 |  |  |  |
| 37 | Võ Ngọc Thiệt | Phó trưởng Công an | 0973 501 491 |  |  |  |
| 38 | Nguyễn Văn Vạn | Phó trưởng Công an | 0918 700 667 |  |  |  |
| 39 | Nguyễn Thanh Tùng | Phó trưởng Công an | 0989 232 595 |  |  |  |
| 40 | Đặng Chí ĐPhương | Phó trưởng Công an | 0919 015 408 |  |  |  |
| 41 | Châu Thành Nhân | Phó trưởng Công an | 0847 909 595 |  |  |  |
| 42 | Lê Thanh Phong | UVBTVĐU- CHT BCH Quân sự | 0919 182 602 |  |  |  |

### XÃ TÂN THẠNH

- Nhóm: 1
- Mã/STT nhóm: 26

### Quốc lộ 62, ấp 1, xã Tân / Thạnh

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 1 | Lê Xuân Khang | Bí thư Đảng ủy xã | 0919 233 975 |  | Quốc lộ 62, ấp 1, xã Tân / Thạnh |  |
| 2 | Trần Kim Oanh | Phó Bí thư, Chủ tịch HĐND xã | 0919 488 558 |  | Quốc lộ 62, ấp 1, xã Tân / Thạnh |  |
| 3 | Lê Phước Vẹn | Phó Bí thư, Chủ tịch UBND xã | 0888 833 345 |  | Quốc lộ 62, ấp 1, xã Tân / Thạnh |  |
| 4 | Nguyễn Thị Cẩm Nhung | UVBTV,Trưởng Ban Xây dựng Đảng | 0987 107 990 |  | Quốc lộ 62, ấp 1, xã Tân / Thạnh |  |
| 5 | Nguyễn Thị Tuyết Nhung | UVBTV, CN ủy ban kiểm tra | 0989 610 601 |  | Quốc lộ 62, ấp 1, xã Tân / Thạnh |  |
| 6 | Hồ Thị Bích Siêng | UVBTV, PCT UBND xã | 0985 220 984 |  | Quốc lộ 62, ấp 1, xã Tân / Thạnh |  |
| 7 | Dương Thị Dung | UVBTV, Chủ tịch Mặt trận Tổ quốc | 0965 456 869 |  | Quốc lộ 62, ấp 1, xã Tân / Thạnh |  |
| 8 | Nguyễn Thị Ngọc Lệ | ĐUV, PCT HĐND | 0856 794 479 |  | Quốc lộ 62, ấp 1, xã Tân / Thạnh |  |
| 9 | Lê Minh Tuấn | ĐUV, PCT UBND xã | 0983 765 435 |  | Quốc lộ 62, ấp 1, xã Tân / Thạnh |  |
| 10 | Trần Nhật Tân | UVBTV, Trưởng Công an | 0948 975 965 |  | Quốc lộ 62, ấp 1, xã Tân / Thạnh |  |
| 11 | Lê Trần Thanh | ĐUV, Phó trưởng Công an | 0938 391 919 |  | Quốc lộ 62, ấp 1, xã Tân / Thạnh |  |
| 12 | Trần Trung Giang | CHT BCH Quân sự | 0362 638 701 |  | ấp 3, xã Tân Thạnh |  |
| 13 | Nguyễn Đông Phúc | PCHT BCH Quân sự | 0834 607 487 |  | ấp 3, xã Tân Thạnh |  |
| 14 | Nguyễn Thị Nhẹ | ĐUV, Chánh Văn Phòng Đảng ủy | 0397 168 326 |  | Quốc lộ 62, ấp 1, xã Tân / Thạnh |  |
| 15 | Nguyễn Thị Xuân Thắm | ĐUV, PTB Đảng | 0983 633 739 |  | Quốc lộ 62, ấp 1, xã Tân / Thạnh |  |
| 16 | Huỳnh Thị Thu Tư | ĐUV, PTB Đảng | 0949 653 456 |  | Quốc lộ 62, ấp 1, xã Tân / Thạnh |  |
| 17 | Nguyễn Ngọc Khuyên | ĐUV, Giám đốc TT Chính trị | 0355 746 345 |  | Quốc lộ 62, ấp 1, xã Tân / Thạnh |  |
| 18 | Phạm Thị Lài | ĐUV, PCN. Ủy ban Kiểm tra | 0946 866 456 |  | Quốc lộ 62, ấp 1, xã Tân / Thạnh |  |
| 19 | Dương Thị Phương Trúc | ĐUV, PCT MTTQ kiêm Chủ tịch Phụ nữ | 0946 510 629 |  | Quốc lộ 62, ấp 1, xã Tân / Thạnh |  |
| 20 | Võ Tiền Phong | ĐUV, PCT MTTQ kiêm Bí thư Đoàn | 0947 347 131 |  | Quốc lộ 62, ấp 1, xã Tân / Thạnh |  |
| 21 | Nguyễn Văn Dính | ĐUV, PCT MTTQ kiêm Chủ tịch Hội Nông dân | 0916 852 993 |  | Quốc lộ 62, ấp 1, xã Tân / Thạnh |  |
| 22 | Cai Thanh Trường | PCT MTTQ kiêm Chủ tịch Hội cựu chiến binh | 0373 336 920 |  | Quốc lộ 62, ấp 1, xã Tân / Thạnh |  |
| 23 | Trương Thanh Sang | ĐUV, Phó ban Pháp chế | 0983 844 245 |  | Quốc lộ 62, ấp 1, xã Tân / Thạnh |  |
| 24 | Nguyễn Thị Ngọc Hân | ĐUV, Phó ban Kinh tế - XH | 0353 012 565 |  | Quốc lộ 62, ấp 1, xã Tân / Thạnh |  |
| 25 | Trần Thái Tòng | ĐUV, Chánh Văn phòng HĐND và UBND | 0982 644 916 |  | Quốc lộ 62, ấp 1, xã Tân / Thạnh |  |
| 26 | Phạm Nhật Tiến | Phó Chánh Văn phòng HĐND / và UBND | 0913 154 914 |  | Quốc lộ 62, ấp 1, xã Tân / Thạnh |  |
| 27 | Nguyễn Văn Chắn | ĐUV, Trưởng phòng Kinh tế | '0944 786 857 |  | Quốc lộ 62, ấp 1, xã Tân / Thạnh |  |
| 28 | Nguyễn Văn Fomal | Phó Trưởng phòng | 0972 009 398 |  | Quốc lộ 62, ấp 1, xã Tân / Thạnh |  |
| 29 | Nguyễn Ngọc Ẩn | ĐUV, Trưởng phòng Văn hóa xã hội | 0933 791 061 |  | Quốc lộ 62, ấp 1, xã Tân / Thạnh |  |
| 30 | Huỳnh Thanh Sang | Phó Trưởng phòng văn hóa - xã hội | 0946 757 070 |  | Quốc lộ 62, ấp 1, xã Tân / Thạnh |  |
| 31 | Huỳnh Văn Trung | ĐUV, Giám đốc TT cung ứng dịch vụ | 0397 774 567 |  | ấp 1, xã Tân Thạnh |  |
| 32 | Hồ Duy Thanh | ĐUV, PGĐ TT Phục vụ Hanh chính công | 0798 636 595 |  | ấp 1, xã Tân Thạnh |  |
| 33 | Trần Phước Thuận | Trưởng trạm Y tế | 0916 535 693 |  | ấp 3, xã Tân Thạnh |  |
| 34 | Lê Thị Kim Hoa | ĐUV, Hiệu trưởng Trường THCS Thị trấn | 0976 459 871 |  | ấp 1, xã Tân Thạnh |  |

### XÃ HẬU THẠNH

- Nhóm: 1
- Mã/STT nhóm: 27

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 1 | Hà Thanh Chì | UV BCH - Bí thư - CT HĐND | 0834 588 815 |  |  |  |
| 2 | Trương Thanh Nhàn | UV BCH - Phó Bí thư thường trực | 0985 929 080 |  |  |  |
| 3 | Nguyễn Thế Anh | UV BCH - CT. UBND xã | 0918 631 369 |  |  |  |
| 4 | Trần Thị Kim Duyên | UV BCH - CT. MTTQ xã | 0969 992 525 |  |  |  |
| 5 | Phan CTính | UV BCH - PCT. HĐND | 0935 192 373 |  |  |  |
| 6 | Nguyễn Thành Kha | UV BCH - PCT. UBND xã | 0942 701 508 |  |  |  |
| 7 | Nguyễn Thị Mỹ Miều | UV BCH - PCT. UBND xã | 0976 945 454 |  |  |  |
| 8 | Nguyễn Văn Thuân | UV BCH - TB XDĐ | 0937 410 091 |  |  |  |
| 9 | Huỳnh Thanh Tú | UV BCH - CN UBKT | 0985 358 261 |  |  |  |
| 10 | Lê Văn Nghệ | UV BCH - Chánh VP Đảng ủy | 0918 884 863 |  |  |  |
| 11 | Châu văn Tuyến | UV BCH - Trưởng Công an | 0913 632 054 |  |  |  |
| 12 | Trần Trung Tuyển | UV BCH - CHT. BCH Quân sự | 0977 388 184 |  |  |  |
| 13 | Nguyễn Ngọc Đỉnh | UV BCH - Chánh VP.HĐND và UBND | 0385 938027 |  |  |  |
| 14 | Nguyễn Ngọc Lanh | UV BCH - Trưởng Phòng VH-XH xã | 0983 510 109 |  |  |  |
| 15 | Phạm Văn Hữu Tiệp | UV BCH - Trưởng phòng kinh tế | 0946 603 909 |  |  |  |
| 16 | Nguyễn Kim Châu | UV BCH - GĐ TT CƯSNC xã | 0902 830 225 |  |  |  |
| 17 | Mai Hoàng Hiếu | UV BCH - PTB VH-XH HĐND | 0984 847 651 |  |  |  |
| 18 | Nguyễn Thị Thúy Liễu | UV BCH - PTB KT-NS HĐND | 0979 844 260 |  |  |  |
| 19 | Hà Thị Ngọc Nguyên | UV BCH - BT.ĐTN | 0978 438 420 |  |  |  |
| 20 | Nguyễn Minh Khá | UV BCH - CT.CCB | 0933 498 106 |  |  |  |
| 21 | Phan Thành Tâm | UV BCH - CT.CHND | 0384 840 843 |  |  |  |
| 22 | Trần Thị Mận | UV BCH - CT.HPN | 0943 279 804 |  |  |  |
| 23 | Trịnh Thị Ngọc Lý | UV BCH - PTB XDĐ | 0346 345 535 |  |  |  |
| 24 | Đoàn Văn Mạnh | UV BCH - PCN UBKT | 0833 338 772 |  |  |  |
| 25 | Lê Văn Kết | UV BCH - Phó trưởng Công an | 0978 912 017 |  |  |  |
| 26 | Nguyễn Minh Luân | UV BCH - Phó GĐ.TTPVHHC xã | 0359 307 321 |  |  |  |
| 27 | Nguyễn Văn Hồ | UV BCH - Hiệu trưởng Trường THCS-THPT | 0918 597 241 |  |  |  |
| 28 | Nguyễn Tấn Vũ | Phó CVP Đảng ủy | 0842 000 300 |  |  |  |
| 29 | Trịnh Minh Tuyến | Phó Ban xây dựng Đảng | 0373 213 319 |  |  |  |
| 30 | Nguyễn Minh Chơn | PCVP HĐND và UBND | 0394 747 625 |  |  |  |
| 31 | Nguyễn Việt Hưng | PTP Kinh tế | 0917 481 246 |  |  |  |

### XÃ NHƠN HÒA LẬP

- Nhóm: 1
- Mã/STT nhóm: 28

### ấp Kênh Nhà Thờ xã Nhơn Hòa Lập

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 1 | Lê Văn Nhãn | Bí thư | 091 - 299 - 1232 |  |  | ấp Kênh Nhà Thờ xã Nhơn Hòa Lập |
| 2 | Võ Minh Dương | Phó Bí Thư Thường trực | 091 - 889 - 7799 |  |  | ấp Kênh Nhà Thờ xã Nhơn Hòa Lập |
| 3 | Nguyễn Chí Thành | Phó Bí thư - CT UBND | 090 - 780 - 8323 |  |  | ấp Kênh Nhà Thờ xã Nhơn Hòa Lập |
| 4 | Đinh Văn Định | UV BTV - PCT UBND | 037 - 712 - 2199 |  |  | ấp Kênh Nhà Thờ xã Nhơn Hòa Lập |
| 5 | Trần Lưu Niệm | UV BTV - PCT UBND | 091 - 837 - 1757 |  |  | ấp Kênh Nhà Thờ xã Nhơn Hòa Lập |
| 6 | Ngô Phước Xuyên | CT HĐND | 098 - 343 - 7837 |  |  | ấp Kênh Nhà Thờ xã Nhơn Hòa Lập |
| 7 | Trần Thị Trúc Mai | UV BTV - TB XD Đảng | 082 - 414 - 6062 |  |  | ấp Kênh Nhà Thờ xã Nhơn Hòa Lập |
| 8 | Lê Thị Tuyết | UV BTV - TB KT Đảng | 098 - 661 - 0399 |  |  | ấp Kênh Nhà Thờ xã Nhơn Hòa Lập |
| 9 | Huỳnh Khánh Truyền | UV BTV - Trưởng Công an | 091 - 889 - 1834 |  |  | ấp Kênh Nhà Thờ xã Nhơn Hòa Lập |
| 10 | Nguyễn Thanh Linh | UV BTV - CHT QS xã | 091 - 665 - 6439 |  |  | ấp Kênh Nhà Thờ xã Nhơn Hòa Lập |
| 11 | Lê Thị Tuyết Thư | CT UB MTTQ VN xã | 085 - 745 - 7041 |  |  | ấp Kênh Nhà Thờ xã Nhơn Hòa Lập |
| 12 | Huỳnh Thị Bé Thùy | UV BCH - Chánh VP Đảng ủy | 098 - 384 - 4745 |  |  | ấp Kênh Nhà Thờ xã Nhơn Hòa Lập |
| 13 | Nguyễn Văn Ký | UV BCH - Phó Ban XD Đảng | 097 - 856 - 8467 |  |  | ấp Kênh Nhà Thờ xã Nhơn Hòa Lập |
| 14 | Nguyễn Thị Màu | UV BCH - Phó Ban XD Đảng | 078 - 643 - 9168 |  |  | ấp Kênh Nhà Thờ xã Nhơn Hòa Lập |
| 15 | Phan Hồ Đầy | UV BCH - Phó Ban KT Đảng | 081 - 959 - 4160 |  |  | ấp Kênh Nhà Thờ xã Nhơn Hòa Lập |
| 16 | Tô Thành Quốc | UVBCH - PCT UB MTTQ xã - CT Hội ND | 083 - 737 - 5909 |  |  | ấp Kênh Nhà Thờ xã Nhơn Hòa Lập |
| 17 | Đoàn Văn Mến | UVBCH - PCT UB MTTQ xã - CT Hội CCB | 094 - 222 - 8817 |  |  | ấp Kênh Nhà Thờ xã Nhơn Hòa Lập |
| 18 | Nguyễn Thị Chọn | UVBCH - PCT UB MTTQ xã - CT Hội PN | 098 - 342 - 9270 |  |  | ấp Kênh Nhà Thờ xã Nhơn Hòa Lập |
| 19 | Phạm Văn Luyến | UVBCH - PCT UB MTTQ xã - ĐTN | 096 - 248 - 2256 |  |  | ấp Kênh Nhà Thờ xã Nhơn Hòa Lập |
| 20 | Đặng Thủy Lệ | Phó Ban VHXH HĐND | 094 - 351 - 1544 |  |  | ấp Kênh Nhà Thờ xã Nhơn Hòa Lập |
| 21 | Nguyễn Mạnh Công ang | Phó Ban Kinh tế HĐND | 081- 626 -1186 |  |  | ấp Kênh Nhà Thờ xã Nhơn Hòa Lập |
| 22 | Huỳnh Thanh Phong | GĐ TT Cung ứng dịch vụ Sự nghiệp công | 091 - 690 - 9015 |  |  | ấp Kênh Nhà Thờ xã Nhơn Hòa Lập |
| 23 | Lê Quốc Khánh | UV BCH - Trưởng phòng Kinh tế | 091- 820 - 3620 |  |  | ấp Kênh Nhà Thờ xã Nhơn Hòa Lập |
| 24 | Phan Thị Tuyết Trinh | UV BCH - Trưởng phòng VHXH | 083 - 235 - 9495 |  |  | ấp Kênh Nhà Thờ xã Nhơn Hòa Lập |
| 25 | Trần Minh Nghĩa | UV BCH - CVP HĐND và UBND | 083 - 278 - 9030 |  |  | ấp Kênh Nhà Thờ xã Nhơn Hòa Lập |
| 26 | Đỗ Hoài Khanh | UV BCH - Phó trưởng Công an | 098 - 678 - 7437 |  |  | ấp Kênh Nhà Thờ xã Nhơn Hòa Lập |
| 27 | Hà Hải Ngọc | UV BCH - Phó CHT QS xã | 035 - 842 - 4898 |  |  | ấp Kênh Nhà Thờ xã Nhơn Hòa Lập |
| 28 | Nguyễn Ngân Giang | UV BCH - Phó GĐ TT HCC | 098 - 351 - 6511 |  |  | ấp Kênh Nhà Thờ xã Nhơn Hòa Lập |
| 29 | Trần Thị Anh Đào | UV BCH - Hiệu trưởng trường THCS | 094 - 476 - 8696 |  |  | ấp Kênh Nhà Thờ xã Nhơn Hòa Lập |
| 30 | Trần Văn Hoài | UVBCH - Bí thư Chi bộ ấp Nguyễn Bảo | 033 - 625 - 2024 |  |  | ấp Kênh Nhà Thờ xã Nhơn Hòa Lập |
| 31 | Đoàn Văn Coi | UVBCH - Bí thư Chi bộ ấp Kênh Chà | 098 - 811 - 6658 |  |  | ấp Kênh Nhà Thờ xã Nhơn Hòa Lập |
| 32 | Nguyễn Văn Đoàn | Phó phòng Kinh tế | 091- 403- 5003 |  |  | ấp Kênh Nhà Thờ xã Nhơn Hòa Lập |
| 33 | Trần Thị Hiền | Phó phòng VHXH | 091- 625 -1236 |  |  | ấp Kênh Nhà Thờ xã Nhơn Hòa Lập |
| 34 | Lê Thị Bích Ca | PGĐ TT Cung ứng dịch vụ Sự nghiệp công | 081 - 673 - 2007 |  |  | ấp Kênh Nhà Thờ xã Nhơn Hòa Lập |
| 35 | Huỳnh Trọng Ngân | Phó CVP HĐND và UBND | 094 - 937 - 3739 |  |  | ấp Kênh Nhà Thờ xã Nhơn Hòa Lập |

### XÃ NHƠN NINH

- Nhóm: 1
- Mã/STT nhóm: 29

### Đảng uỷ xã Nhơn Ninh

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 1 | Nguyễn Thị Trúc | Bí thư- CT HĐND | 0983 868 759 |  |  | ấp Bằng Lăng xã Nhơn Ninh |
| 2 | Đinh Văn Thiện Chí | Phó Bí thư | 0983 241 745 |  |  | ấp Bằng Lăng xã Nhơn Ninh |
| 3 | Nguyễn Xuân Tươi | UV BTV- TB Xây dựng Đảng | 0949 739 959 |  |  | ấp Tân Long xã Nhơn Ninh |
| 4 | Bùi Thị Thuý An | UV BTV- CN Uỷ Ban Kiểm Tra ĐU | 0948 890 899 |  |  | ấp Tân Long xã Nhơn Ninh |
| 5 | Lê Em | UV BCH- Phó CN UBKTĐU | 0945 226 519 |  |  | ấp Tân Long xã Nhơn Ninh |
| 6 | Võ Thanh Phương | UV BTV- CT MTTQ VN | 0949 944 879 |  |  | ấp Bằng Lăng xã Nhơn Ninh |
| 7 | Âu Hoàng Vũ | UV BCH- CVP ĐU | 0948 444 788 |  |  | ấp Bằng Lăng xã Nhơn Ninh |
| 8 | Nguyễn Minh Tân | UV BCH- PCT MTTQ VN (ND) | 0919 593 019 |  |  | ấp Bằng Lăng xã Nhơn Ninh |
| 9 | Nguyễn Thị Xuyên | UV BCH- PCT MTTQ VN (PN) | 0964 380 392 |  |  | ấp Bằng Lăng xã Nhơn Ninh |
| 10 | Đoàn Văn Kha | UV BCH-PCT MTTQ VN (ĐTN) | 0386 762 250 |  |  | ấp Bằng Lăng xã Nhơn Ninh |
| 11 | Võ Thị Ngoan | UV BCH- Phó TB Xây Dựng Đảng | 0947 749 144 |  |  | ấp Tân Long xã Nhơn Ninh |
| 12 | Huỳnh Hồng Linh | UV BCH-PCT MTTQ (HCCB) | 0973 260 174 |  |  | ấp Bằng Lăng xã Nhơn Ninh |
| 13 | Võ Huỳnh Lâm | Phó Chánh Văn phòng Đảng Uỷ | 0823 979 949 |  |  | ấp Bằng Lăng xã Nhơn Ninh |
| 14 | Võ Thị Mãi | Phó ban Xây Dựng Đảng | 0386 696 232 |  |  | ấp Tân Long xã Nhơn Ninh |
| 15 | Trần Bá Hộ | UV BCH-HT Trường THCS NN | 0829 238 287 |  |  | Hiệu trưởng trường THCS NN |

### HĐND xã Nhơn Ninh

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 1 | Đoàn Văn Liệt | UV BTV- PCT HĐND | 0949 398 489 |  |  | ấp Bằng Lăng xã Nhơn Ninh |
| 2 | Nguyễn Văn Luôn | UV BCH- Phó Ban KTNS HĐND | 0937 957 175 |  |  | ấp Bằng Lăng xã Nhơn Ninh |
| 3 | Bùi Minh Khải | UV BCH- Phó Ban VHXH HĐND | 0832 481 633 |  |  | ấp Bằng Lăng xã Nhơn Ninh |

### Ủy ban nhân dân

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 1 | Nguyễn Văn Thực | Phó Bí thư - CT UBND | 0388 446 816 |  |  | ấp Bằng Lăng xã Nhơn Ninh |
| 2 | Nguyễn Thanh Trúc | UV BTV - PCT Ủy ban nhân dân - / GĐ TT Phục vụ hành chính công | 0949 409 059 |  |  | ấp Bằng Lăng xã Nhơn Ninh |
| 3 | Nguyễn Văn Điệp | UV BTV-PCT UBND | 0978 450 750 |  |  | ấp Bằng Lăng xã Nhơn Ninh |
| 4 | Nguyễn Thanh Hậu | UV BTV- Trưởng Công an | 0903 714 957 | 02723 939 462 |  | ấp Tân Long xã Nhơn Ninh |
| 5 | Nguyễn Trường Giang | UV BTV- CHT BCH Quân sự | 0975 317 312 | 02723 815 151 |  | ấp 3 xã Nhơn Ninh |
| 6 | Lê Hoàng Em | UV BCH -CVP HĐND-UBND | 0944 315 393 |  |  | ấp Bằng Lăng xã Nhơn Ninh |
| 7 | Nguyễn Chí Nguyện | Phó Chánh VP HĐND-UBND | 0919 821 222 |  |  | ấp Bằng Lăng xã Nhơn Ninh |
| 8 | Huỳnh Văn Hồng Phim | UV BCH- Trưởng Phòng KT | 0335 644 175 |  |  | ấp Bằng Lăng xã Nhơn Ninh |
| 9 | Trần Vũ Phong | UV BCH-Trưởng Phòng VHXH | 0387 876 066 |  |  | ấp Bằng Lăng xã Nhơn Ninh |
| 10 | Nguyễn Văn Thắng | UV BCH -PGĐ TT PVHCC | 0914 838 786 |  |  | ấp Bằng Lăng xã Nhơn Ninh |
| 11 | Trần Văn Nhơn | UV BCH-GĐ TT Cung ứng DVSN Công | 0858 194 117 |  |  | ấp Bằng Lăng xã Nhơn Ninh |
| 12 | Trần Hoàng Phúc | UV BCH- PCH Trưởng BCH Quân sự | 0946 675 562 | 02723 815 151 |  | ấp 3 xã Nhơn Ninh |
| 13 | Phan Văn Sang | Phó Trưởng phòng KT | 0979 657 675 |  |  | ấp Bằng Lăng xã Nhơn Ninh |
| 14 | Nguyễn Duy Dương | UV BCH- Phó Trưởng CA | 0975 336 330 | 02723 939 462 |  | ấp Tân Long xã Nhơn Ninh |
| 15 | Phạm Thị Anh Thư | Phó Trưởng phòng VHXH | 0942 171 242 |  |  | ấp Bằng Lăng xã Nhơn Ninh |

### XÃ THẠNH HÓA

- Nhóm: 1
- Mã/STT nhóm: 30

### Đảng ủy - Địa chỉ: Ấp Tuyên Nhơn, xã Thạnh Hóa tỉnh Tây Ninh

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 1 | Hoàng Xuân Trang | Bí thư - CT HĐND | 0914 396 639 |  | truongpn@tayninh.gov.vn. |  |
| 2 | Nguyễn Quốc Đạt | Phó Bí thư xã | 0918 328 362 |  | tichnv@tayninh.gov.vn. |  |
| 3 | Huỳnh Hoa Thuấn | UV BTV - CN UBKT | 0901 623 705 |  | dienmt@tayninh.gov.vn |  |
| 4 | Trương Minh Nhẫn | UV BCH - PCN UBKT | 0949 651 965 |  |  |  |
| 5 | Nguyễn Thanh Tẩm | UV BTV - TB Xây dựng đảng | 0919 823 659 |  |  |  |
| 6 | Lê Chí Hiếu | UV BCH - PTB Xây dựng đảng | 0907 566 172 |  |  |  |
| 7 | Trương Thanh Phong | UV BCH - PTB Xây dựng đảng | 0919 337 267 |  |  |  |
| 8 | Dương Thanh Điệu | UV BCH - CVP Đảng ủy | 0982 867 538 |  |  |  |
| 9 | Ngô Lê Dũng | UV BTV - CT MTTQ xã | 0849 140 097 |  |  |  |
| 10 | Nguyễn Thị Hai | UV BCH - PCT MTTQ, CT Hội PN | 0856 062 855 |  |  |  |
| 11 | Ngô Trung Trực | UV BCH - PCT MTTQ, CT Hội ND | 0856 165 159 |  |  |  |
| 12 | Phan Thị Bạch Tuyết | UV BCH - PCT MTTQ, BT Đoàn TN | 0917 751 083 |  |  |  |
| 13 | Nguyễn Thanh Tâm | UV BCH - PCT MTTQ, CT HCCB xã | 0856 878 007 |  |  |  |

### Hội đồng nhân dân - Địa chỉ: Ấp Tuyên Nhơn, xã Thạnh Hóa, Tây Ninh

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 14 | Nguyễn Tấn Kiệt | UV BTV - PCT HĐND | 0848 949 049 |  |  |  |
| 15 | Nguyễn Bé Thùy Lê | Ban Kinh tế - HĐND | 0984 038 517 |  |  |  |
| 16 | Nguyễn Thị Chinh | Ban VHXH - HĐND | 0886 241 626 |  |  |  |

### UBND xã - ĐT bàn: 02723 857 115 - Địa chỉ: Ấp Tuyên Nhơn, xã Thạnh Hóa, Tây Ninh

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 17 | Phạm Nhật Trường | Phó Bí thư - CT UBND xã | 0971 067 067 |  |  |  |
| 18 | Nguyễn Văn Tích | UV BTV - PCT UBND - GĐ TTHCC xã | 0989 671 179 |  |  |  |
| 19 | Mã Thanh Điền | UV BTV - PCT UBND xã | 0918 393006 |  |  |  |
| 20 | Bạch Thị Chương | UV BCH - CVP HĐND và UBND | 0915 982 224 |  |  |  |
| 21 | Mai Văn Thảo | PCVP HĐND và UBND | 0909 552 456 |  |  |  |
| 22 | Võ Dương Cảnh | UV BCH - Trưởng phòng kinh tế | 0973 648 396 |  |  |  |
| 23 | Nguyễn Thị Kim Oanh | PTP kinh tế | 949144388 |  |  |  |
| 24 | Nguyễn Thị Ngọc Phương | UV BCH - TP Văn hóa - Xã hội | 0914 650 239 |  |  |  |
| 25 | Võ Hữu Triều | PTP Văn hóa - Xã hội | 0941 686 458 |  |  |  |
| 26 | Huỳnh Thị Cẩm Ngọc | UV BCH - PGĐ TT Hành chính c | 0932 841 786 |  |  |  |
| 27 | Huỳnh Quốc Thái | GĐ TT Cung ứng DVSN công | 0914 733 839 |  |  |  |
| 28 | Nguyễn Ngọc Như | PGĐ TT Cung ứng DVSN công | 0985 347 190 |  |  |  |
| 29 | Mã Thanh Thảo | UV BCH- GĐ TT Chính trị | 0823 378 378 |  |  |  |
| 30 | Phùng Thị Bích Thủy | UV BCH- Hiệu trưởng Trường THPT xã | 0944 690 076 |  |  |  |
| 31 | Cao Duy Khánh | UV BTV - Trưởng Công an | 0829 857 579 |  |  |  |
| 32 | Trần Quốc Qui | UV BCH - Phó trưởng Công an | 0919 612 396 |  |  |  |
| 33 | Mai Phát Huy | UV BTV - CHT BCH Quân sự | 0942 279 245 |  |  |  |
| 34 | Nguyễn Minh Luân | UV BCH - PCHT BCH Quân sự | 0972 007 558 |  |  |  |

### XÃ BÌNH THÀNH

- Nhóm: 1
- Mã/STT nhóm: 31

### Đảng ủy Bình Thành - Địa chỉ: Ấp Đồn A, Xã Bình Thành

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 1 | Nguyễn Trọng Cần | Bí thư Đảng ủy | 0943 950 101 |  |  |  |
| 2 | Thi Hữu Giàu | Phó Bí thư Đảng ủy | 0918 616 609 |  |  |  |
| 3 | Lữ Phương Nam | UV BTV - CN UBKT | 0906 504 159 |  |  |  |
| 4 | Nguyễn Văn Tâm | UV BCH - PCN UBKT | 0916 527 485 |  |  |  |
| 5 | Nguyễn Lê Bảo Trung | UV BTV - TB Xây dựng đảng | 0916 864 163 |  |  |  |
| 6 | Trần Thanh Mộng | UV BCH - PTB Xây dựng đảng | 0947 826 949 |  |  |  |
| 7 | Lê Văn Rựng | ĐUV - PTB PT TG & DV | 0838 029 977 |  |  |  |
| 8 | Nguyễn Thị Liếu | UV BCH - CVP Đảng ủy | 0911 685 667 |  |  |  |
| 9 | Huỳnh Thị Thái Lan | UV BTV- CT MTTQ xã | 0908 549 663 |  |  |  |
| 10 | Phạm Thị Hiếu | UV BCH - PCT MTTQ, CT Hội PN | 0947 900 350 |  |  |  |
| 11 | Nguyễn Minh Luân | UV BCH - PCT MTTQ, CT Hội ND | 0917 244 590 |  |  |  |
| 12 | Nguyễn Thị Mỹ Huệ | UV BCH - PCT MTTQ, BT Đoàn TN | 0366 931 724 |  |  |  |
| 13 | Nguyễn Văn Mẫn | UV BCH - PCT MTTQ, CT HCCB | 0813 773 750 |  |  |  |

### HĐND xã Bình Thành - Địa chỉ: Ấp Thuận Hiệp, xã Bình Thành

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 14 | Nguyễn Trọng Cần | CT HĐND - Bí Thư Đảng Ủy | 0943 950 101 |  |  |  |
| 15 | Phạm Văn Trọng | PCT HĐND | 0389 632 810 |  |  |  |
| 16 | Lữ Phương Nam | TB Kinh tế - Ngân sách HĐND | 0906 504 159 |  |  |  |
| 17 | Huỳnh Thị Xuân An | PTB KT NS - HĐND | 0947 270 946 |  |  |  |
| 18 | Lữ Quốc Kiệp | PTB VHXH - HĐND | 0938 647 499 |  |  |  |

### UBND xã Bình Thành - email: ubndbinhthanh@tayninh gov vn

### Địa chỉ: Ấp Thuận Hiệp, xã Bình Thành

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 19 | Nguyễn Văn Tèo | Phó Bí thư - CT UBND | 0832 677 474 |  |  |  |
| 20 | Nguyễn Thị Ngọc Yến | UV BTVĐU - PCT UBND | 0977 922 154 |  |  |  |
| 21 | Võ Quốc Toản | UV BTV - PCT UBND | 0822 291 081 |  |  |  |
| 22 | Hoàng Trọng Huấn | ĐUV - CVP HĐND và UBND | 0937 959 022 |  |  |  |
| 23 | Trần Thị Thẳm | PCVP HĐND và UBND | 0949 971 795 |  |  |  |
| 24 | Lê Hoàng Long | ĐUV - Trưởng phòng kinh tế | 0917 175 656 |  |  |  |
| 25 | Nguyễn Văn Hiếu | PTP kinh tế | 0977 202 878 |  |  |  |
| 26 | Võ Đình Khánh Nhật | ĐUV - TP Văn hóa - Xã hội | 0918 509 579 |  |  |  |
| 27 | Phan Hồng Tâm | PTP Văn hóa - Xã hội | 0946 220 979 |  |  |  |
| 28 | Võ Quốc Toản | GĐ TT Hành chính c(Kiêm nhiệm) | 0822 291 081 |  |  |  |
| 29 | Lê Thị Hồng Cúc | PGĐ TT Hành chính công | 0911 256 881 |  |  |  |
| 30 | Huỳnh Thanh An | PGĐ TT Cung ứng DVSN công | 0832 765 987 |  |  |  |
| 31 | Nguyễn Văn Ninh | UV BTV ĐU - Trưởng Công an | 0945 128 228 |  |  |  |
| 32 | Nguyễn Trung Lượng | ĐUV Phó trưởng Công an | 0962 200 707 |  |  |  |
| 33 | Trần Trường An | UV BTV ĐU - CHT BCH Quân sự | 0918 675 311 |  |  |  |
| 34 | Võ Thanh Triệu | ĐUV - P CHT BCHQS Xã | 0344 558 889 |  |  |  |

### XÃ THẠNH PHƯỚC

- Nhóm: 1
- Mã/STT nhóm: 32

### ấp Vàm Lớn, xã Thạnh Phước

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 1 | Nguyễn Thượng Bình | Bí thư Đảng ủy kiêm CT HĐND | 0917 076 516 |  |  | ấp Vàm Lớn, xã Thạnh Phước |
| 2 | Phan Vũ Cường | Phó Bí thư Đảng ủy | 0915 275 449 |  |  | // |
| 3 | Nguyễn Châu Kim Ngân | Phó Bí thư - CT UBND | 0916 252 639 | 02723.713.111 |  | ấp Thạnh Lập, xã Thạnh Phước |
| 4 | Nguyễn Văn Pha | UV BTV - PCT UBND | 0916 957 090 |  |  | // |
| 5 | Lê Ngọc Tường | UV BTV - PCT UBND | 0917 750 676 |  |  | // |
| 6 | Phạm Văn Sang | UV BCH - PCT HĐND | 0919 805 520 |  |  | // |
| 7 | Trần Thị Kim Hiền | PTB HĐND | 0858 343 769 |  |  | // |
| 8 | Trần Văn Hợp | PTB HĐND | 0942 910 173 |  |  | // |
| 9 | Nguyễn Duy Thoại | UV BCH - CTMTTQ | 0942 872 387 |  |  | ấp Vàm Lớn, xã Thạnh Phước |
| 10 | Trần Tuấn Nhiên | PCT.MTTQ | 0378 129 628 |  |  | // |
| 11 | Nguyễn Văn Thẳng | PCT.MTTQ | 0946 261 459 |  |  | // |
| 12 | Trần Thị Mộng | PCT.MTTQ | 0826 233 424 |  |  | // |
| 13 | Huỳnh Thanh Hùng | PCT.MTTQ | 0855 226 680 |  |  | // |
| 14 | Lê Vũ Trường Sơn | CVP Đảng ủy | 0853 997 679 |  |  | // |
| 15 | Nguyễn Thị Mai | PCVP Đảng ủy | 0942 737 668 |  |  | // |
| 16 | Nguyễn Văn Quýnh | CN UBKT | 0852 655 699 |  |  | // |
| 17 | Nguyễn Chí Trường | PCN UBKT | 0949 947 759 |  |  | // |
| 18 | Trần Văn Tính | PTB XDĐ | 0838 867 498 |  |  | // |
| 19 | Nguyễn Hoàng Vũ | PTB XDĐ | 0945 490 975 |  |  | // |
| 20 | Trần Hữu Phú | Trưởng phòng VH-XH | 0906 309 966 | 02723 713 113 |  | ấp Thạnh Lập, xã Thạnh Phước |
| 21 | Nguyễn Văn Thiết | PTP VH-XH | 0989 449 284 |  |  | // |
| 22 | Nguyễn Kinh Kha | Trưởng phòng Kinh tế | 0975 912 427 | 02723.713.112 |  | // |
| 23 | Lưu Ngọc Mỹ | PTP Kinh tế | 0833 838 337 |  |  | // |
| 24 | Phùng Văn Chuyển | GĐ TT Cung ứng dịch vụ công | 0835 835 583 | 02723.713.116 |  | Ấp Cả Sáu, xã Thạnh Phước |
| 25 | Trần Phương Thắm | PGĐ TT Cung ứng dịch vụ công | 0829 991 284 |  |  | // |
| 26 | Hà Văn Mộng | CHT BCHQS | 0949 513 513 |  |  | // |
| 27 | Trần Đường Bút | PCHT BCHQS | 0947 357 772 |  |  | // |
| 28 | Phan Văn Sớm | TCA | 0908 291 137 |  |  | ấp Vàm Lớn, xã Thạnh Phước |
| 29 | Trương Minh Dương | PTCA | 0833 252 241 |  |  | // |
| 30 | Nguyễn Văn Lợi | PTCA | 0913 503 454 |  |  | // |
| 31 | Phan Văn Khoa | PTCA | 0948 896 396 |  |  | // |
| 32 | Lê Thanh Trung | PTCA | 0978 237 789 |  |  | // |
| 33 | Trầm Văn Thuộc | PTCA | 0938 040 232 |  |  | // |
| 34 | Lê Minh Tuấn | PGĐ TTHCC | 0919 428 577 | 02723.713.114 |  | ấp Thạnh Lập, xã Thạnh Phước |
| 35 | Ngô Thanh Bình | CVP HĐND-UBND | 0946 868 013 |  |  | // |
| 36 | Nguyễn Vũ Hảo | PCVP HĐND-UBND | 0947 676 620 |  |  | // |

### XÃ TÂN TÂY

- Nhóm: 1
- Mã/STT nhóm: 33

### Ấp Cả Ràng, xã Tân Tây,

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 1 | Hồ Thị Ngọc Lan | Bí thư - CT HĐND | 0983 370 397 |  |  |  |
| 2 | Ngô Trọng Hiếu | Phó Bí thư Thường trực Đảng ủy | 0917 944 338 |  |  |  |
| 3 | Trừ Vĩnh Thăng | Phó Bí thư - CT UBND | 0909 556 455 |  |  |  |
| 4 | Nguyễn Thị Xuân Lan | UV BTV-TB Xây dựng Đảng | 0907 607 955 |  |  |  |
| 5 | Phạm Thị Mỹ Phụng | UV BTV - PCT UBND | 0977 066 372 |  |  |  |
| 6 | Trần Minh Tuấn | UV BTV - PCT UBND | 0912 0567 56 |  |  |  |
| 7 | Bùi Văn Dũng | UV BTV - PCT HĐND | 0384 529 133 |  |  |  |
| 8 | Lê Thị Kim Toàn | UV BTV - PCT HĐND - CN UBKT | 0918 891 448 |  |  |  |
| 9 | Nguyễn Lê Bảo Châu | UV BTV - CT MTTQ | 0946 624 475 |  |  |  |
| 10 | Nguyễn Khánh Hùng | UV BTV - CHT Ban chỉ huy Quân sự | 0914 918 125 |  |  |  |
| 11 | Đặng Văn Cảnh | UV BTV-Trưởng Công an | 0917 452 444 |  |  |  |
| 12 | Huỳnh Thị Nga | ĐUV - CVP Đảng ủy | 0888 999 835 |  |  |  |
| 13 | Võ Thành Kính | ĐUV - PTB XDĐ - Tuyên Giáo | 0916 228 612 |  |  |  |
| 14 | Trịnh Thị Ngọc Điệp | ĐUV - PTB XDĐ - Tổ chức | 0946 510 515 |  |  |  |
| 15 | Đỗ Minh Nhựt | ĐUV - Phó CNUBKT Đảng | 0784 703 791 |  |  |  |
| 16 | Võ Thị Non | ĐUV - Chánh VP HĐND-UBND | 0949 456 582 |  |  |  |
| 17 | Hồ Minh Cường | ĐUV - PGĐ TTPV HCC | 0988 695 635 |  | dinhvansau@tayninh.gov.vn |  |
| 18 | Nguyễn Thị Thanh Thúy | ĐUV - PCT.MTTQ - BT ĐTN | 0344 255 226 |  | namnv@tayninh.gov.vn |  |
| 19 | Lê Thị Yến Chúc | ĐUV - PCT.MTTQ - CT HLHPN | 0944 400 046 |  | quannv@tayninh.gov.vn |  |
| 20 | Nguyễn Ngọc Trăng | ĐUV - PCT.MTTQ - CT HCCB | 0842 263 264 |  | haopc@tayninh.gov.vn |  |
| 21 | Võ Thanh Bảo | ĐUV - PCT.MTTQ - CT HND | 0914 396 739 |  | bqdung@tayninh.gov.vn |  |
| 22 | Nguyễn Qui Bình | ĐUV - PBAN KT-NS HĐND | 0967 807 107 |  | huynhdung@tayninh.gov.vn |  |
| 23 | Nguyễn Việt Phúc | ĐUV - PBAN pháp chế HĐND | 0915 245 745 |  | phuocmh@tayninh.gov.vn |  |
| 24 | Tạ Văn Vàng | ĐUV - Trưởng phòng KT - NS | 0914 396 779 |  |  |  |
| 25 | Nguyễn Thị Hiếu | ĐUV - Trưởng phòng VH - XH | 0948 464 925 |  |  |  |
| 26 | Phan Thành Học | ĐUV - Phó Trưởng Công an | 0977 999 003 |  |  |  |
| 27 | Võ Nhất Y Khoa | Phó CVP Đảng ủy | 0985 876 985 |  | banchqsxathuthua@gmail.com |  |
| 28 | Nguyễn Xuân Minh | Phó Chánh VP HĐND-UBND | 0913 976 004 |  |  |  |
| 29 | Ngô Thanh Tuần | PCHT Ban chỉ huy Quân sự | 0333 113 387 |  |  |  |
| 30 | Nguyễn Bích Hằng | GĐ TTCUDVC | 0834 570 996 |  |  |  |
| 31 | Nguyễn CSơn | PTP KT - NS | 0945 770 032 |  |  |  |
| 32 | Nguyễn Thị Thu Thiệt | PTP VH - XH | 0388 651 365 |  |  |  |

> Dòng nguồn 3438: thachngocnguyen1991@gmail.com

### XÃ THỦ THỪA

- Nhóm: 1
- Mã/STT nhóm: 34
- Email: thuthao1989.99@gmail.com

### Địa chỉ số 68, đường N11, ấp 11, xã Thủ Thừa

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 1 | Đinh Văn Sáu | Bí thư Đảng uỷ - Chủ tịch HĐND | 0918 029 548 |  | nguyenkimtuyenthuthuatayninh@gmail.com |  |
| 2 | Nguyễn Văn Nam | Phó Bí thư Thường trực Đảng uỷ xã | 0399 223 222 |  | chuotlongan@gmail.com |  |
| 3 | Nguyễn Văn Quân | Phó Bí thư Đảng uỷ - Chủ tịch UBND | 0918 756 406 | 02723.864.215 | thiennm@tayninh.gov.vn |  |
| 4 | Phạm Chí Hảo | UV BTV - PCT HĐND | 0919 823 639 | 02723.864.214 | dtnhan@tayninh.gov.vn |  |
| 5 | Bùi Quang Dũng | UV BTV - PCT.UBND / GĐ TTHCC xã | 0938 214 204 | 0906 489 484 | quanvt@tayninh.gov.vn |  |
| 6 | Võ Thị Huỳnh Dung | UV BTV - PCT UBND xã | 0382.706.414 | 0906 489 484 | huynhtrang@tayninh.gov.vn |  |
| 7 | Mai Hữu Phước | UV BTV - TB Xây dựng Đảng xã | 0914.515.705 |  | ntngochan@tayninh.gov.vn |  |
| 8 | Nguyễn Văn Bảy | UV BTV - CN UBKT | 0918.782.619 |  |  |  |
| 9 | Nguyễn Thị Thu Lan | UV BTV - Chủ tịch MTTQ xã | 0783.205.171 |  |  |  |
| 10 | Lưu Đức Hưng | UV BTV - Trưởng Công an / Số 36, ấp 1, xã Thủ Thừa | 0842.789.698 | 02723.611.909 |  |  |
| 11 | Nguyễn Minh Tân | UV BTV - CHT.BCH Quân sự / TL834 ấp Bình Lương 1, xã Thủ Thừa | 0977.883.904 | 02723.864.218 | tranthianh@tayninh.gov.vn |  |
| 12 | Nguyễn Quốc Dũng | ĐUV - Phó trưởng Công an | 0945.944.017 | 0916 671 189 | ngavt@tayninh.gov.vn |  |
| 13 | Hồ Văn Trai | ĐUV - Chánh VP Đảng uỷ xã | 0989.959.853 |  | langphuong@tayninh.gov.vn |  |
| 14 | Nguyễn Ái Nhân | ĐUV - PTB Xây dựng Đảng xã | 0333.829.486 |  | leanhvu@tayninh.gov.vn |  |
| 15 | Đặng Hoàng Ân | ĐUV - PCN UBKT | 0869.483.837 |  | maihoa.56319@gmail.com |  |
| 16 | Huỳnh Thanh Vũ | ĐUV - GĐ TT Chính trị | 0933.866.787 |  | hieu.thuthua@tayninh.gov.vn |  |
| 17 | Nguyễn Ngọc Thạch | ĐUV - PCT MTQ - BT Đoàn TN | 0362.093.036 |  |  |  |
| 18 | Nguyễn Thị Thu Thảo | ĐUV - PCT MTTQ - CT Hội PN | 0915.849.099 |  |  |  |
| 19 | Nguyễn Thị Kim Tuyến | ĐUV - PCT MTTQ - CT Hội ND | 0946.800.778 |  |  |  |
| 20 | Lương Đại Long | ĐUV - Phó Ban KT - NS HĐND | 0785.449.452 |  |  |  |
| 21 | Nguyễn Minh Thiện | ĐUV - Phó Ban Văn hoá - XH HĐND | 0965.864.039 |  |  |  |
| 22 | Đỗ Thị Ngọc Hân | ĐUV - Chánh VP.HĐND và UBND | 0768.726.776 |  |  |  |
| 23 | Võ Thanh Quân | ĐUV - Trưởng phòng kinh tế | 0388.449.877 | 02723.864.289 |  |  |
| 24 | Nguyễn Thị Huỳnh Trang | ĐUV - Trưởng Phòng Văn hoá - XH | 0383.167.713 | 02723.864.296 |  |  |
| 25 | Nguyễn Thị Ngọc Hân | ĐUV - GĐ TTCUDV sự nghiệp công | 0915.408.905 | 02723.567.882 | longlx@tayninh.gov.vn |  |
| 26 | Nguyễn Thị Thuỳ Linh | Phó Chánh VP Đảng uỷ xã | 0785.940.296 |  | nguyenthitoquyen@tayninh.dcs.vn |  |
| 27 | Bùi Thanh Bình | Phó Chánh VP Đảng uỷ xã | 0919.999.120 |  |  |  |
| 28 | Nguyễn Thị Tuyết Loan | PTB Xây dựng Đảng xã | 0946.789.686 |  | thuandtt@tayninh.gov.vn |  |
| 29 | Trần Thị Ánh | Phó Chánh VP.HĐND và UBND | 0985.314.293 |  | chauhm@tayninh.gov.vn |  |
| 30 | Võ Thị Nga | PTP kinh tế | 0772.422.708 |  |  |  |
| 31 | Lê Thị Lang Phương | PTP Văn hoá - Xã hội | 0966.433.572 |  | duonghuynhhanh@tayninh / .dcs.vn |  |
| 32 | Lê Anh Vũ | Phó GĐ TT Phục vụ HCC | 0918.885.676 | 02723 611 533 | mynuongmt@gmail.com |  |
| 33 | Mai Thị Hoa | Phó GĐ TT Chính trị | 0978.456.319 |  | phuongthaomylac@gmail.com |  |
| 34 | Trương Trung Hiếu | Phó GĐ TTCUDV sự nghiệp công | 0933.772.440 |  | thanhtai072024@gmail.com |  |
| 35 | Phạm Thị Kim Hồng | Phó trưởng Công an | 0386.500.749 | 0916 671 189 | linhtrangia1510@gmail.com |  |
| 36 | Phạm Đào Tấn Nhứt | Phó trưởng Công an | 0902.047.437 | 0916 671 189 |  |  |
| 37 | Lâm Văn Lập | Phó trưởng Công an | 0974.994.492 | 0916 671 189 |  |  |
| 38 | Trần Trí Phương | Phó trưởng Công an | 0846.020.676 | 0916 671 189 | longlx@tayninh.gov.vn |  |

### XÃ MỸ AN -

- Nhóm: 1
- Mã/STT nhóm: 35

### ĐT bàn 02723 822 204 - email: xamyan@tayninh.gov.vn

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 1 | Nguyễn Ngọc Thanh | Bí thư Đảng ủy | 0909 791 582 |  |  |  |
| 2 | Phan Văn Nhuần | Phó Bí thư TT Đảng ủy - CT HĐND | 0908 696 205 |  |  |  |
| 3 | Nguyễn Hữu Đông | Phó Bí thư - CT UBND | 0946 411 105 |  |  |  |
| 4 | Trần Phan Kiều Tuyên | UV BTV - PCT HĐND | 0819 451 388 |  |  |  |
| 5 | Nguyễn Hữu Thuận | UV BCH - PCT UBND - GĐ TTPVHCC | 0912 577 585 |  |  |  |
| 6 | Nguyễn Thị Thu Hằng | UV BCH - PCT UBND | 0918 897 159 |  |  |  |
| 7 | Nguyễn Thị Mỹ Hoa | UV BTV - Trưởng BXDĐ | 0392 367 274 |  |  |  |
| 8 | Nguyễn Lĩnh | UV BTV - CN UBKT | 0938 915 870 |  |  |  |
| 9 | Bùi Thị Trúc Linh | UV BTV - CT MTTQ | 0976 223 317 |  |  |  |
| 10 | Nguyễn Hồng Phúc | UV BTV - Trưởng Công an | 0913 161 387 |  |  |  |
| 11 | Đinh Hoàng Trúc | UV BTV - CHT BCHQS | 0828 919 120 |  |  |  |
| 12 | Thái Văn Sĩ | CVP Đảng ủy | 0945 946 473 |  |  |  |
| 13 | Bùi Văn Quốc | Phó CVP Đảng ủy | 0354 845 919 |  |  |  |
| 14 | Nguyễn Tấn Y | Phó CVP Đảng ủy | 0979 733 856 |  |  |  |
| 15 | Trần Thanh Tuấn | PTB XDĐ | 0948 444 626 |  |  |  |
| 16 | Lê Thị Trà Mi | PTB XDĐ | 0349 890 868 |  |  |  |
| 17 | Lý Trọng Nghĩa | Phó CN UBKT | 0925 948 434 |  |  |  |
| 18 | Phạm Phú Nhã | CVP HĐND và UBND | 0836 696 994 |  |  |  |
| 19 | Võ Chí Tâm | TP Kinh tế | 0919 123 483 |  |  |  |
| 20 | Nguyễn Phạm Hiếu | TP VH-XH | 0908 241 061 |  |  |  |
| 21 | Nguyễn Bảo Kỳ | GĐ TT CƯ DVSNC | 0918 893 699 |  |  |  |
| 22 | Đặng Chí Tân | Phó Trưởng Công an | 0913 552 694 |  |  |  |
| 23 | Lê Minh Trí | Phó Trưởng Công an | 0983 006 839 |  |  |  |
| 24 | Nguyễn Thanh Phong | Phó CHT BCHQS | 0889 347 276 |  |  |  |
| 25 | Đặng Phước Truyền | Phó CVP HĐND và UBND | 0906 143 419 |  |  |  |
| 26 | Nguyễn Thị Yến Dung | PTP Kinh tế | 0914 518 922 |  |  |  |
| 27 | Trần Thị Châu Khoa | PTP VH-XH | 0945 981 478 |  |  |  |
| 28 | Nguyễn Hồng Thảo | PGĐ TT PVHCC | 0919 432 377 |  |  |  |
| 29 | Nguyễn Thị Thanh Vân | PCT MTTQ - CT HLHPN | 0979 726 471 |  |  |  |
| 30 | Ngô Thị Diễm Trang | PCT MTTQ - BT ĐTN | 0947 397 334 |  |  |  |
| 31 | Đỗ Hữu Huy | PCT MTTQ - CT HND | 0987 493 874 |  |  |  |
| 32 | Nguyễn Hoàng Nhung | PCT MTTQ - CT HCCB | 0949 949 884 |  |  |  |

### XÃ MỸ THẠNH

- Nhóm: 1
- Mã/STT nhóm: 36

### Đảng ủy Mỹ Thạnh - Địa chỉ: Ấp Mỹ Hòa, xã Mỹ Thạnh

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 1 | Lê Xuân Long | Bí thư | 0918 898 434 |  |  |  |
| 2 | Nguyễn Thị Tố Quyên | Phó Bí thư | 0778 781 504 |  |  |  |
| 3 | Nguyễn Hữu Khoa | UV BTV - CN UBKT | 0918 276 576 |  |  |  |
| 4 | Dương Thị Thanh Thuận | UV BCH - PCN UBKT | 0946 417 517 |  |  |  |
| 5 | Huỳnh Minh Châu | UV BTV - TB Xây dựng đảng | 0941 679 600 |  |  |  |
| 6 | Trần Thị Ngọc Điệp | UV BCH - PTB Xây dựng đảng | 0338 316 477 |  |  |  |
| 7 | Dương Huỳnh Hạnh | UV BCH - CVP Đảng ủy | 0349 805 994 |  |  |  |
| 8 | Nguyễn Thị Mỹ Nương | UV BCH - CT MTTQ | 0919 117 360 |  |  |  |
| 9 | Nguyễn Thị Phương Thảo | UV BCH - PCT MTTQ, CT Hội LHPN | 0857 595 979 |  |  |  |
| 10 | Châu Thanh Tài | UV BCH - PCT MTTQ, CT Hội ND | 0833 939 552 |  |  |  |
| 11 | Trần Gia Linh | UV BCH - PCT MTTQ, BT Đoàn TN | 0858 930 729 |  |  |  |
| 12 | Lê Văn Bảy | UV BCH - PCT MTTQ, CT Hội CCB | 0918 430 305 |  |  |  |

### Hội đồng nhân dân XÃ Mỹ Thạnh - Địa chỉ: Ấp 4, xã Mỹ Thạnh

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 13 | Lê Xuân Long | BT ĐU - CT HĐND | 0918 898 434 |  |  |  |
| 14 | Nguyễn Tấn Hôn | PCT HĐND kiêm TB / VH-XH HĐND | 0979 726 453 |  |  |  |
| 15 | Nguyễn Hữu Trí | Phó Ban VHXH - HĐND | 0948 799 889 |  |  |  |
| 16 | Lương Toàn Triệu | Phó Ban Kinh tế -Ngân sách / HĐND | 0919 809 929 |  |  |  |
| 17 | Nguyễn Hữu Khoa | TB Kinh tế- / Ngân sách HĐND | 0918 276 576 |  |  |  |

### UBND xã Mỹ Thạnh- ĐT bàn: 0272 3865 006; email: xamythanh@tayninh.gov.vn

### Địa chỉ: Ấp 4, xã Mỹ Thạnh, Tây Ninh

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 17 | Lê Hoàng Việt | Phó Bí thư - CT UBND | 0978 456 376 |  |  |  |
| 18 | Nguyễn Thế Phong | - PCT UBND | 0903 102 024 |  |  |  |
| 19 | Lê Anh Tuấn | - PCT UBND | 0834 432 556 |  |  |  |
| 20 | Nguyễn Hữu Phước | - CVP HĐND và UBND | 0965 171 698 |  |  |  |
| 21 | Nguyễn Thị Lan | PCVP HĐND và UBND | 0903 010 267 |  |  |  |
| 22 | Phạm CMười | - Trưởng phòng kinh tế | 0907 770 674 |  |  |  |
| 23 | Nguyễn Hữu Lợi | PTP kinh tế | 0907 855 733 |  |  |  |
| 24 | Lê Thanh Phong | - TP Văn hóa - Xã Hội | 0918 955 558 |  |  |  |
| 25 | Trần Anh Vũ | PTP Văn hóa - Xã Hội | 0947 000 308 |  |  |  |
| 26 | Lê Anh Tuấn | GĐ TT Hành chính công | 0834 432 556 |  |  |  |
| 27 | Nguyễn Văn Dứt | PGĐ TT Hành chính công | 0919 882 333 |  |  |  |
| 28 | Lục Thị Huệ Phương | GĐ TT Cung ứng DVSN công | 0947 819 331 |  |  |  |
| 29 | (khuyết) | PGĐ TT Cung ứng DVSN công |  |  |  |  |
| 30 | Bùi Văn Ninh | UV BCH - Trưởng Công an | 0932 125 152 |  |  |  |
| 31 | Trần Trung Hảo | Phó trưởng Công an | 0919 269 787 |  |  |  |
| 32 | Trần Văn Ửng | Phó trưởng Công an | 0937 668 538 |  |  |  |
| 33 | Trần Văn Cơ | Phó trưởng Công an | 0949 514 667 |  |  |  |
| 34 | Trần Tuấn Anh | Phó trưởng Công an | 0988 999 275 |  |  |  |
| 35 | Huỳnh Văn Truyền | Phó trưởng Công an | 0902 565 567 |  |  |  |
| 36 | Phạm Văn Hải | UV BCH- CHT BCH Quân sự | 0967 026 407 |  |  |  |
| 37 | Trương Thanh Điền | PCHT BCH Quân sự | 0948 794 282 |  |  |  |

### XÃ TÂN LONG

- Nhóm: 1
- Mã/STT nhóm: 37

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 1 | Lê Hoàng Hùng | Bí thư - CT HĐND | 0919 124 751 | 02722 228 602 |  |  |
| 2 | Phạm Minh Tâm | Phó Bí thư | 0949 653 739 | 02722 228 602 |  |  |
| 3 | Cao Lê Cẩm Bình | UV BTV - TB.XDĐ | 0778 889 998 | 02722 228 602 |  |  |
| 4 | Lê Hữu Tâm | UV BTV - CN.UBKT | 0943 627 089 | 02722 228 602 |  |  |
| 5 | Nguyễn Văn Chót | UV BTV - Phó Bí thư - CT UBND | 0919 124 655 | 02723 614 268 |  |  |
| 6 | Nguyễn Hoàng Nam | UV BTV - PCT UBND | 0908 586 029 | 02723 614 268 |  |  |
| 7 | Nguyễn Hữu Tâm | UV BTV - PCT UBND | 0919 124 761 | 02723 614 268 |  |  |
| 8 | Ngô Thị Thu Trang | UV BTV - PCT. HĐND | 0946 826 982 | 02723 614 268 |  |  |
| 9 | Ngô Tấn Tước | UV BTV - TCA | 0906 725 792 | 02723 863 813 |  |  |
| 10 | Trần Quốc Bảo | UV BTV - BCHQS | 0342 724 113 | 02723 863 322 |  |  |
| 11 | Nguyễn Văn Thêm | UV BCH - PCN.UBKT | 0913 978 766 |  |  |  |
| 12 | Lê Duy Khương | UV BCH - CT.MTTQ | 0947 960 737 |  |  |  |
| 13 | Võ Thị Huê | UV BCH - PCT.UBMTTQ kiêm CT.HLHPN | 0393 979 755 |  |  |  |
| 14 | Phạm Thị Mai Hương | UV BCH - PCT.UBMTTQ kiêm CT.HND | 0944 910 281 |  |  |  |
| 15 | Nguyễn Văn Bình | UV BCH - PCT.UBMTTQ kiêm CT.HCCB | 0944 945 910 |  |  |  |
| 16 | Cao Minh Phúc | UV BCH - PCT.UBMTTQ kiêm BTĐTN | 0792 755 373 |  |  |  |
| 17 | Lê Thanh Trường | UV BCH - Phó Ban XDĐ | 0948 278 878 |  |  |  |
| 18 | Bùi Thanh Kiệt | UV BCH - CVPĐU | 0949 949 158 |  |  |  |
| 19 | Nguyễn Thị Lệ Thu | UV BCH - PCN.UBKT | 0947 999 607 |  |  |  |
| 20 | Trần Hoài Thanh | UV BCH - CVP. HĐND-UBND | 0888 171 137 | 02723 614 268 |  |  |
| 21 | Nguyễn Thị Lam Vân | UV BCH - TP.Kinh tế | 0949 112 660 | 02723 614 268 |  |  |
| 22 | Bùi Thanh Tuấn | UV BCH - TP.VHXH | 0947 322 374 | 02723 614 268 |  |  |
| 23 | Phạm Thị Mỹ Ngọc | UV BCH - PGĐ. TTPVHCC | 0985 878 245 | 02723 863 364 |  |  |
| 24 | Nguyễn Hoàng Quân | UV BCH - PTB.KT-NS - HĐND | 0916 963 955 | 02723 614 268 |  |  |
| 25 | Mai Thị Thu Cúc | UV BCH - PTB.VHXH - HĐND | 0347 435 169 | 02723 614 268 |  |  |
| 26 | Võ Thanh Tú | UV BCH - PTCA | 0915 697 123 |  |  |  |
| 27 | Nguyễn Thị Mộng Đào | UV BCH - GĐ. TTCUDVSNC | 0914 552 669 |  |  |  |
| 28 | Nguyễn Lực Lượng | PGĐ. TTCUDVSNC | 0989 592 908 |  |  |  |
| 29 | Nguyễn Thanh Phùng | PCVP. HĐND-UBND | 0968 443 064 | 02723 614 268 |  |  |
| 30 | Huỳnh Diễm Phúc | PTP.Kinh tế | 0908 071 229 | 02723 614 268 |  |  |
| 31 | Trần Minh Kha | PTP. VHXH | 0984 463 946 | 02723 614 268 |  |  |

### XÃ MỸ QUÝ

- Nhóm: 1
- Mã/STT nhóm: 38

### Đảng ủy XÃ MỸ QUÝ - Địa chỉ: Ấp 2, xã Mỹ Quý

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 1 | Nguyễn Thanh Nguyên | Bí thư Đảng ủy, Chủ tịch HĐND | 0986 789 797 |  |  |  |
| 2 | Nguyễn Văn Son | Phó Bí thư Thường trực Đảng ủy, | 0933 574 122 |  |  |  |
| 3 | Nguyễn Văn Hiếu | UV. BTV, CN UBKT | 0983 854 560 |  |  |  |
| 4 | Hoàng Ngọc Hạnh | UV. BCH, P.CN UBKT | 0907 431 981 |  |  |  |
| 5 | Thi Thị Ngọc Hạnh | UV. BTV, TB XD Đảng | 0388 929 351 |  |  |  |
| 6 | Trần Thị Thu | UV. BCH, P. TB XDĐ | 0336 325 097 |  |  |  |
| 7 | Huỳnh Văn Thắng | UV. BCH, chánh VPĐU | 0937 426 200 |  |  |  |
| 8 | Đặng Văn Sinh | UV. BTV, Chủ tịch MTTQ | 0909 594 679 |  |  |  |
| 9 | Trương Thị Thu Trang | UV. BCH, CT. HLHPN | 0914 011 837 |  |  |  |
| 10 | Nguyễn Văn Thanh | UV. BCH, CT. HND | 0908 614 029 |  |  |  |
| 11 | Phan Minh Trường | UV. BCH, BT. ĐTN | 0367 929 262 |  |  |  |
| 12 | Phan Văn Cường | UV. BCH, CT.HCCB | 0346 550 503 |  |  |  |

### Hội đồng nhân dân XÃ MỸ QUÝ - Địa chỉ: Ấp 2, xã Mỹ Quý

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 13 | Lại Thanh Phú Quí | UV. BTV, PCT HĐND | 0937 137 625 |  |  |  |
| 14 | Nguyễn Văn Uôn | UV. BCH, PTB KT - NS HĐND | 0933 367 292 |  |  |  |
| 15 | Hồng Nhật Bình | PTB VH-XH HĐND | 0938 084 197 |  |  |  |

### UBND xã - ĐT bàn: 02723.856.111 ; email: ubndmyquy@tayninh.gov.vn

### Địa chỉ: Ấp 2, xã Mỹ Quý

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 16 | Lê Thị Kim Ngân | Phó Bí thư Đảng ủy, Chủ tịch UBND | 0914 144 889 |  |  |  |
| 17 | Lâm Văn Thà | UV. BTV, PCT UBND | 0937 480 649 |  |  |  |
| 18 | Dương Văn Lam | UV. BTV, PCT UBND | 0903 444 863 |  |  |  |
| 19 | Võ Hồng Tươi | UV. BCH, Chánh VP HĐND và UBND | 0938 284 828 |  |  |  |
| 20 | Võ Thị Cẩm Vân | PCVP HĐND và UBND | 0937 055 230 |  |  |  |
| 21 | Đặng Văn Thức | UV. BCH, Trưởng phòng Kinh tế | 0908 949 151 |  |  |  |
| 22 | Ngô Vũ Linh Vương | PTP kinh tế | 0972 005 015 |  |  |  |
| 23 | Võ Hồng Phúc | UV. BCH, Trưởng phòng VH - XH | 0949 644 477 |  |  |  |
| 24 | Trần Quốc Bảo | PTP Văn hóa - Xã hội | 0938 590 477 |  |  |  |
| 25 | Dương Văn Lam | GĐ TT Hành chính công | 0903 444 863 |  |  |  |
| 26 | Huỳnh Văn Cứng | UV. BCH, P.GĐ TTPVHCC | 0971 243 369 |  |  |  |
| 27 | Nguyễn Hoàng Vân | GĐ TT Cung ứng DVSN công | 0942 239 548 |  |  |  |
| 28 | Đỗ Thị Hồng Lệ | PGĐ TT Cung ứng DVSN công | 0906 893 166 |  |  |  |
| 29 | Nguyễn Quốc Toàn | UV. BTV, Trưởng Công an | 0937 567 479 |  |  |  |
| 30 | Huỳnh Quốc Nhanh | UV. BCH, P. Trưởng Công an | 0985 180 657 |  |  |  |
| 31 | Phạm Ngọc Sinh | UV. BTV, CHT BCH Quân sự | 0906 334 776 |  |  |  |
| 32 | Trần Văn Khiêm | UV. BCH, P.CHT BCH QS | 0395 694 778 |  |  |  |

### XÃ ĐÔNG THÀNH

- Nhóm: 1
- Mã/STT nhóm: 39

### Đảng ủy Đông Thành - Địa chỉ: số 204, Đường Châu Văn Liêm, xã ĐThành

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 1 | Lữ Minh Luân | Bí thư Đảng ủy | 0909 386 088 |  |  |  |
| 2 | Huỳnh Thị Phương Quyên | Phó Bí thư TTĐU | 0832 819 139 |  |  |  |
| 3 | Nguyễn Hữu Tình | UV BTV - CN UBKT | 0937 700 471 |  |  |  |
| 4 | Đào Văn Tuấn | ĐUV - PCN UBKT | 0907 680 252 |  |  |  |
| 5 | Huỳnh Thanh Tâm | UV BTV - TB Xây dựng đảng ĐU xã | 0972 747 578 |  |  |  |
| 6 | Nguyễn Thị Nhiều | ĐUV - PTB Xây dựng đảng ĐU xã | 0912 861 263 |  |  |  |
| 7 | Lâm Thị Tú Thi | ĐUV - CVP Đảng ủy | 0902 718 449 |  |  |  |
| 8 | Nguyễn Trung Hiếu | UV BTV - CT MTTQ xã | 0937 802 759 |  |  |  |
| 9 | Lê Thị Hồng Ân | ĐUV - PCT MTTQ, CT Hội PN | 0799 822 444 |  |  |  |
| 10 | Nguyễn Minh Luân | ĐUV - PCT MTTQ, CT Hội ND | 0976 481 682 |  |  |  |
| 11 | Nguyễn Thị Ngọc Linh | ĐUV - PCT MTTQ, BT Đoàn TN | 0332 221 231 |  |  |  |
| 12 | Nguyễn Văn Sứ | ĐUV CT. HCCB | 0975 315 925 |  |  |  |
| 13 | Hà Thị Huyện | Phó CVP Đảng uỷ | 0976 343 926 |  |  |  |

### HĐND xã Đông Thành - Địa chỉ: số 204, Đường Châu Văn Liêm, xã ĐThành

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 1 | Huỳnh Thị Phương Quyên | CT HĐND | 0832 819 139 |  |  |  |
| 2 | Nguyễn Hữu Tình | TB Kinh tế - HĐND | 0937 700 471 |  |  |  |
| 3 | Huỳnh Thanh Tâm | TB VHXH - HĐND | 0972 747 578 |  |  |  |
| 4 | Nguyễn Thị Bé Nha | PTB Kinh tế - Ngân sách HĐND | 0949 737 837 |  |  |  |
| 5 | Võ Thị Bích Thuỷ | PTB Văn hoá - Xã hội HĐND | 0933 497 975 |  |  |  |

### UBND xã Đông Thành- ĐT bàn: email: ubnddongthanh@tayninh.gov.vn

### Địa chỉ: số 204, Đường Châu Văn Liêm, xã ĐThành

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 4 | Tạ Hồng Trang | Phó Bí thư - CT UBND | 0916 782 777 |  |  |  |
| 5 | Võ Minh Trọng | UV BTV - PCT UBND | 0945 503 006 |  |  |  |
| 6 | Nguyễn Đức Uyên | ĐUV - PCT UBND | 0938 022 599 |  |  |  |
| 7 | Tô Ngọc Thuận | ĐUV - CVP HĐND và UBND | 0939 322 795 |  |  |  |
| 8 | Nguyễn Ngọc Tiếp | PCVP HĐND và UBND | 0336 902 119 |  |  |  |
| 9 | Phạm CBằng | ĐUV - Trưởng phòng kinh tế | 0979 486 898 |  |  |  |
| 10 | Nguyễn Xuân Du | PTP kinh tế | 0828 497 878 |  |  |  |
| 11 | Phạm Hồng Tuấn | ĐUV - TP Văn hóa - Xã hội | 0903 859 840 |  |  |  |
| 12 | Nguyễn Thị Bích Trâm | PTP Văn hóa - Xã hội | 0909 980 407 |  |  |  |
| 13 | Võ Minh Trọng | Kiêm GĐ TT Hành chính công | 0945 503 006 |  |  |  |
| 14 | Nguyễn Minh Trung | ĐUV - PGĐ TT Hành chính công | 0937 589 076 |  |  |  |
| 15 | Nguyễn Thành Tài | GĐ TT Cung ứng DVSN công | 0903 854 200 |  |  |  |
| 16 | Nguyễn Thị Hồng Luyn | PGĐ TT Cung ứng DVSN công | 0937 576 536 |  |  |  |
| 17 | Phan Thị Ngọc Thiểu | PGĐ TT Cung ứng DVSN công | 0936 667 342 |  |  |  |
| 18 | Nguyễn Hoài Nhân | UV BTV - Trưởng Công an | 0907 925 964 |  |  |  |
| 19 | Nguyễn Thành Phục | ĐUV - Phó Trưởng Công an | 0909 735 142 |  |  |  |
| 20 | Đỗ Văn Sơn | Phó Trưởng Công an | 0335 874 755 |  |  |  |
| 21 | Nguyễn Hoàng Châu | Phó Trưởng Công an | 0937 071 035 |  |  |  |
| 22 | Lê Hải Đăng | Phó Trưởng Công an | 0966 148 298 |  |  |  |
| 23 | Nguyễn Văn Nhả | Phó Trưởng Công an | 0932 777 235 |  |  |  |
| 24 | Nguyễn Văn Sớm | UV BTV - CHT BCH Quân sự | 0903 424 094 |  |  |  |
| 25 | Nguyễn Văn Cường | ĐUV - BCH Quân sự | 0865 214 960 |  |  |  |

### XÃ ĐỨC HUỆ

- Nhóm: 1
- Mã/STT nhóm: 40

### Email: ubndduchue@tayninh.gov.vn, Ấp Thanh Sơn, xã Đức Huệ

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 1 | Đào Ngọc Thanh | Bí thư Đảng ủy - CT HĐND | 0986 010 252 |  |  |  |
| 2 | Phạm Thị Châu Hoàng | Phó Bí thư Thường trực Đảng ủy | 0984 282 116 |  |  |  |
| 3 | Nguyễn Văn Suôn | Phó Bí thư Đảng ủy - CT UBND | 0938 264 775 |  |  |  |
| 4 | Võ THị Hồng Gấm | UV BTV - PCT HĐND | 0944 660 020 |  |  |  |
| 5 | Trần Đăng Khoa | UV BTV - PCT UBND kiêm GĐ TTPVHCC | 0915 187 881 |  |  |  |
| 6 | Lê Thị Hà Giang | UV BTV - PCT UBND | 0976 698 619 |  |  |  |
| 7 | Phan Tấn Đức | UV BTV - TB xây dựng Đảng - Đảng ủy | 0983 462 503 |  |  |  |
| 8 | Phạm Hồng Hưng | UV BCH - CN UBKT Đảng ủy | 0961 807 468 |  |  |  |
| 9 | Nguyễn Văn Cường | UV BTV - CT MTTQ | 0906 503 460 |  |  |  |
| 10 | Cao Văn Vũ | UV BTV - Trưởng Công an | 0907 553 440 |  |  |  |
| 11 | Nguyễn Nhất Linh | UV BTV - CHT Ban chỉ huy Quân sự | 0918 301 456 |  |  |  |
| 12 | Nguyễn Cẩm Tú | UV BCH - PTB VH-XH HĐND | 0333 798 240 |  |  |  |
| 13 | Nguyễn Anh Kiều | UV BCH - CVP HĐND và UBND | 0946 809 239 |  |  |  |
| 14 | Lê CLợi | UV BCH - Trưởng phòng Kinh tế | 0902 626 298 |  |  |  |
| 15 | Lê Thanh Duy | UV BCH - PGĐ TT PVHCC | 0938 777 475 |  |  |  |
| 16 | Nguyễn Văn Phú | UV BCH - Trưởng phòng Văn hóa- Xã hội | 0917 120 374 |  |  |  |
| 17 | Phạm Minh Nhựt | UV BCH - Chánh VP Đảng ủy | 0775 998 528 |  |  |  |
| 18 | Lương Hoàng Quí | UV BCH - PCN UBKT Đảng ủy | 0345 653 589 |  |  |  |
| 19 | Nguyễn Thị Ngọc Thảo | UV BCH - CT.HLHPN | 0829 860 863 |  |  |  |
| 20 | Võ Thị Quế Lâm | UV BCH - CT.HND | 0907 310 652 |  |  |  |
| 21 | Lê Văn Phước | UV BCH - BT.ĐTNCSHCM | 0974 999 330 |  |  |  |
| 22 | Lê Thanh Sơn | UV BCH - CT.HCCB | 0948 864 972 |  |  |  |
| 23 | Nguyễn Minh Tấn | UV BCH - Phó CHT/BCH Quân sự | 0935 557 277 |  |  |  |
| 24 | Đoàn Văn Ninh | UV BCH - Phó Trưởng CA | 0975 454 749 |  |  |  |
| 25 | Triệu Thanh Quan | UV BCH - PTB xây dựng Đảng Đảng ủy | 09393 17995 |  |  |  |
| 26 | Nguyễn Thị Hồng Chuyên | PTB Kinh tế - Ngân sách HĐND | 0944 354 014 |  |  |  |
| 27 | Phan Vương Pha | Phó CVP HĐND và UBND | 0889 77 7092 |  |  |  |
| 28 | Trần Minh Hiểu | PTP Kinh tế | 0919 620 065 |  |  |  |
| 29 | Phạm Huỳnh Alpha | PTP Văn hóa - Xã hội | 098 616 9816 |  |  |  |
| 30 | Lê Thanh An | Phó CVP Đảng ủy | 0879 817 799 |  |  |  |
| 31 | Nguyễn Võ Như Khoa | PTB xây dựng Đảng | 0907 692 264 |  |  |  |
| 32 | Lê Thị Cẩm Tú | Ủy viên UBKT Đảng ủy | 0984 841 583 |  |  |  |
| 33 | Võ Thành Phơ | Ủy viên UBKT Đảng ủy | 0933 366 027 |  |  |  |
| 34 | Hồ Thanh Thoại | GĐ TT Cung ứng dịch vụ sự nghiệp công | 0989 210 080 |  |  |  |
| 35 | Trần Thị Huỳnh Như | PGĐTT Cung ứng dịch vụ sự nghiệp công | 0938 149 957 |  |  |  |
| 36 | Võ Thị Phương Nhi | PGĐ TT Cung ứng dịch vụ sự nghiệp công | 0918 914 022 |  |  |  |

### XÃ HẬU NGHĨA

- Nhóm: 1
- Mã/STT nhóm: 41

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 1 | Trương Tấn Sơn | Bí thư | 0983 445 566 |  |  |  |
| 2 | Võ Văn Cấp | Phó Bí thư - CT HĐND | 0946 979 036 |  |  |  |
| 3 | Trương Minh Hoàng | Phó Bí thư - CT UBND | 0918 067 770 |  |  |  |
| 4 | Liêu Văn Bùng | UV BTV - UBKT / TB KTNS HĐND | 0908.225.630 |  |  |  |
| 5 | Trần Đăng Khoa | UV BTV - TB XDĐ | 0985.216.985 |  |  |  |
| 6 | Nguyễn Thị Kiều Oanh | UV BTV - CT MTTQ / TB VHXH HĐND | 0937.454.628 |  |  |  |
| 7 | Lê Hữu Phi | UV BTV - PCT HĐND | 0906.658.666 |  |  |  |
| 8 | Huỳnh Văn Hưng | UV BTV - PCT UBND | 0903.644.633 |  |  |  |
| 9 | Trương Thị Ngọc Giàu | UV BTV - PCT UBND | 0948.944.492 |  |  |  |
| 10 | Trần Đình Hạnh | UV BTV - Trưởng Công an | 0919.686.126 |  |  |  |
| 11 | Hà Đăng Khoa | UV BTV - CHT BCHQS | 0855.553.407 |  |  |  |
| 12 | Lê Thị Hồng Tươi | ĐUV-CVP Đảng ủy | 0972.682.656 |  |  |  |
| 13 | Nguyễn Trọng Nhân | Phó CVP Đảng ủy | 0776.156.369 |  |  |  |
| 14 | Huỳnh Thị Xuân Hồng | ĐUV, PTB XDĐ | 0933.314.330 |  |  |  |
| 15 | Lâm Quốc Kỳ | ĐUV, PCN UBKT Đảng ủy | 0902.684.151 |  |  |  |
| 16 | Trần Thị Thanh Thảo | ĐUV, GĐ TT chính trị | 0973.951.994 |  |  |  |
| 17 | Huỳnh Thị Minh Lý | ĐUV, PCT MTTQ kiêm Chủ tịch Hội ND | 0938.161.929 |  |  |  |
| 18 | Liêu Thúy Hằng | ĐUV, PCT MTTQ kiêm CT Hội PN | 0939.139.712 |  |  |  |
| 19 | Nguyễn Minh Toàn | ĐUV, PCT MTTQ kiêm Bí thư ĐTN | 0336.112.379 |  |  |  |
| 20 | Nguyễn Mạnh Tuấn | ĐUV, PCT MTTQ kiêm Chủ tịch HCCB | 0974.853.854 |  |  |  |
| 21 | Nguyễn Chí Trung | ĐUV, PTB | 0909.944.813 |  |  |  |
| 22 | Nguyễn CĐức | ĐUV, PTB | 0909.792.350 |  |  |  |
| 23 | Huỳnh Thị Hoa Lài | ĐUV- CVP HĐND và UBND | 0933.862.387 |  |  |  |
| 24 | Trần Ngọc Minh | Phó CVP HĐND và UBND | 0914.605.762 |  |  |  |
| 25 | Nguyễn Anh Đào | ĐUV, Trưởng phòng | 0909.350.490 |  |  |  |
| 26 | Thân Bảo Hưng | ĐUV, Trưởng phòng | 0908.883.296 |  |  |  |
| 27 | Nguyễn Thanh Hòa | ĐUV, Phó GĐ TT PVHCC | 0919.821.559 |  |  |  |
| 28 | Văn Thị Hồng Thắm | Phó GĐ phụ trách TT Cung ứng DVSNC | 0982.763.783 |  |  |  |

### XÃ ĐỨC HÒA

- Nhóm: 1
- Mã/STT nhóm: 42

### Đảng ủy Đức Hòa - Địa chỉ: Ấp 3A, xã Đức Hòa

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 1 | Lê Thành Phong | Bí thư | 0941 779 666 |  |  |  |
| 2 | Huỳnh Thanh An | Phó Bí thư TT ĐU - CT HĐND | 0948 838 890 |  |  |  |
| 3 | Nguyễn Thái Bình | UV BTV - CN UBKT / TB Kinh tế - HĐND | 0977 780 469 |  |  |  |
| 4 | Lê Hà Thanh Thảo | UV BCH - PCN UBKT | 0933 580 090 |  |  |  |
| 5 | Phạm Xuân Hồng | UV BTV - TB Xây dựng đảng | 0909 090 156 |  |  |  |
| 6 | Nguyễn Thị Thùy Trang | UV BCH - PTB Xây dựng đảng | 0939 057 640 |  |  |  |
| 7 | Trần Văn Toàn | UV BCH - CVP Đảng ủy | 0797 959 918 |  |  |  |
| 8 | Lê Minh Thái | UV BTV - CT MTTQ xã - TB VHXH-HĐND | 0918 085 677 |  |  |  |
| 9 | Hồ Ngọc Nở | UV BCH - PCT MTTQ, CT Hội PN | 0907 163 381 |  |  |  |
| 10 | Huỳnh Hoàng Thi | UV BCH - PCT MTTQ, CT Hội ND | 0934 089 354 |  |  |  |
| 11 | Nguyễn Minh Thuận | UV BCH - PCT MTTQ, BT Đoàn TN | 0834 560 340 |  |  |  |
| 12 | Hà Duy | UV BCH - PCT MTTQ, CT Hội CCB | 0987 947 113 |  |  |  |

### Hội đồng nhân dân - email: hdnd.duchoa@tayninh.gov.vn

### Địa chỉ: ấp 3A, xã Đức Hòa

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 13 | Trần Ngọc Nha | UV BCH - PCT HĐND | 0777 327 176 |  |  |  |
| 14 | Nguyễn Chi | UV BCH - Phó Ban Kinh tế - HĐND | 0913 180 744 |  |  |  |
| 15 | Hứa Huỳnh Lê | UV BCH - Phó Ban VHXH - HĐND | 0904 393 133 |  |  |  |

### UBND xã - ĐT bàn: 02723850131 ; email: ubndduchoa@tayninh.gov.vn

### Địa chỉ: 666 ĐT 824, Khu phố 3, xã Đức Hòa

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 16 | Lê Thị Ngọc Hoa | Phó Bí thư - CT UBND | 0786 784 139 |  |  |  |
| 17 | Huỳnh Tấn Hưng | UV BCH - PCT UBND | 0909 416 914 |  |  |  |
| 18 | Nguyễn Minh Tâm | UV BCH - PCT UBND - GĐ TT Hành chính công | 0941 687 168 |  |  |  |
| 19 | Lê Thanh Nhường | UV BCH - CVP HĐND và UBND | 0908 220 415 |  |  |  |
| 20 | Huỳnh Thị Trúc Giang | PCVP HĐND và UBND | 0396 496 317 |  |  |  |
| 21 | Đặng Văn Út | UV BCH - Trưởng phòng kinh tế | 0919 884 389 |  |  |  |
| 22 | Mai Chí Linh | PTP kinh tế | 0949 411 611 |  |  |  |
| 23 | Lê Minh Vương | UV BCH - TP Văn hóa - Xã hội | 0903 150 269 |  |  |  |
| 24 | Huỳnh Võ Duy Phương | PTP Văn hóa - Xã hội | 0966 665 065 |  |  |  |
| 25 | Phạm Bích Ngọc | PGĐ TT Hành chính công | 0977 176 779 |  |  |  |
| 26 | Nguyễn Văn Thọ | GĐ TT Cung ứng DVSN công | 0366 333 444 |  |  |  |
| 27 | Trương Hậu | PGĐ TT Cung ứng DVSN công | 0913 661 921 |  |  |  |
| 28 | Trần Thị Thanh Thoảng | PGĐ TT Cung ứng DVSN công | 0934 388 878 |  |  |  |

### Công an - ĐT bàn: 02723850700 - Địa chỉ: ấp Bình Tiền 2, xã Đức Hòa

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 29 | Võ Minh Trí | UV BTV - Trưởng Công an | 0983 314 624 |  |  |  |
| 30 | Trần Thị Thảo | Phó trưởng Công an | 0983 891 915 |  | phong_nt@tayninh.gov.vn |  |
| 31 | Nguyễn Huỳnh Thảo Sương | Phó trưởng Công an | 0942 331 212 |  | dantt.hiephoa@tayninh.gov.vn |  |
| 32 | Võ Thành Phước | Phó trưởng Công an | 0987 123 450 |  |  |  |
| 33 | Võ Văn Hiền | Phó trưởng Công an | 0964 537 773 |  |  |  |
| 34 | Nguyễn Minh Mẫn | Phó trưởng Công an | 0917 500 200 |  |  |  |

### Quân sự - Địa chỉ: ấp 3A, xã Đức Hòa

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 35 | Nguyễn Trọng Nghĩa | UV BTV - CHT BCH Quân sự | 0933 683 360 |  |  |  |
| 36 | Phạm Đăng Khoa | PCHT BCH Quân sự | 0833 323 033 |  |  |  |

### XÃ HIỆP HÒA

- Nhóm: 1
- Mã/STT nhóm: 43

### Đảng ủy Hiệp Hòa - Địa chỉ: Đường tỉnh 822, ấp Hòa Bình 1, xã Hiệp Hòa

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 1 | Trương Minh Khánh | Bí thư | 0908 053 552 |  |  |  |
| 2 | Trương Hòa Bình | Phó Bí thư - CT HĐND | 0918 070 076 |  |  |  |
| 3 | Lê Minh Đức | UV BTV - CN UBKT / TB KT - NS HĐND | 0979 167 666 |  |  |  |
| 4 | Nguyễn Văn Thành | UV BCH - PCN UBKT / TB VH-XH | 0976 506 767 |  |  |  |
| 5 | Lê Thị Thanh Thảo | UV BTV - TB Xây dựng đảng | 0908 742 297 |  |  |  |
| 6 | Nguyễn Như Ngọc | UV BCH - PTB Xây dựng đảng | 0908 082 252 |  |  |  |
| 7 | Nguyễn Thanh Phong | UV BCH - CVP Đảng ủy | 0389 999 663 |  |  |  |
| 8 | Trần Thanh Dân | UVBCH - CT MTTQ xã | 0939 111 135 |  |  |  |
| 9 | Phan Thị Ngọc Lệ | UV BCH - PCT MTTQ, CT Hội PN | 0972 465 420 |  |  |  |
| 10 | Đoàn Thị Thùy Dung | UV BCH - PCT MTTQ, CT Hội ND | 0968 894 568 |  |  |  |
| 11 | Trần Thái Sang | UV BCH - PCT MTTQ, BT Đoàn TN | 0964 945 954 |  |  |  |
| 12 | Trương Thanh Liêm | UV BCH - PCT MTTQ, Chủ tịch HCCB | 0327 726 424 |  |  |  |

### HĐND Hiệp Hòa - Địa chỉ: Đường Hãng Đường, xã Hiệp Hòa

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 13 | Trần Huy Cường | UV BTV- PCT HĐND | 0909 643 969 |  |  |  |
| 14 | Nguyễn Thị Thiện | UVBCH - Phó Ban Kinh tế - HĐND | 0908 696 005 |  |  |  |
| 15 | Lê Hạnh Vũ Xuân | UV BCH - Phó Ban VHXH - HĐND | 0974 273 319 |  |  |  |

### UBND xã - ĐT bàn: 02723897287 ; email: ubndhiephoa@tayninh.gov.vn - Địa chỉ: Đường Hãng Đường, xã Hiệp Hòa

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 16 | Châu Văn Hải | Phó Bí thư - CT UBND | 0908 776 877 |  | haicv@tayninh.gov.vn |  |
| 17 | Trần CQuyền | UV BTV - PCT UBND | 0916 799 552 |  | quyentc@tayninh.gov.vn |  |
| 18 | Nguyễn Minh Phòng | UV BTV - PCT UBND (GĐ TT PV HCC) | 0911 686 979 |  | phongnm@tayninh.gov.vn |  |
| 19 | Nguyễn Hoài Thương | UV BCH - CVP HĐND và UBND | 0909 351 689 |  | nhthuong@tayninh.gov.vn |  |
| 20 | Phan Thị Thanh Trúc | PCVP HĐND và UBND | 0935 093 778 |  | trucptt.dhoa@tayninh.gov.vn |  |
| 21 | Trương Văn Đô | UVBCH - Trưởng phòng kinh tế | 0988 218 714 |  | truongvando@longan.gov.vn |  |
| 22 | Nguyễn Bá Tòng | PTP kinh tế | 0916 277 477 |  | nbtong@longan.gov.vn |  |
| 23 | Lương Thị Quế Hương | UVBCH - TP Văn hóa - Xã hội | 0989 352 895 | ABC | ltqhuong@longan.gov.vn |  |
| 24 | Nguyễn Ngọc Bạch Hoa | PTP Văn hóa - Xã hội | 0345 191 700 |  | hoa.hiephoa@tayninh.gov.vn |  |
| 25 | Nguyễn Thị Thu Hà | UV BCH -PGD TTPVHCC | 0986 868 797 |  | ntt_ha@tayninh.gov.vn |  |
| 26 | Đào Ngọc Gấm | GĐ TT Cung ứng DVSN công | 0395 913 923 |  | gamdn.dhoa@tayninh.gov.vn |  |
| 27 | Nguyễn Văn Trường | UV BTV, Trưởng Công an | 0989 013 939 |  |  |  |
| 28 | Nguyễn Văn Hổ | UVBCH, Phó Trưởng CA | 0978 777 909 |  |  |  |
| 29 | Phan Thanh Tuấn | UV,BTV - CHT BCH QS | 0946 838 478 |  | tuanpt.hiephoa@tayninh.gov.vn |  |
| 30 | Trần Bảo Toàn | UV,BCH - PCHT BCH QS | 0389 781 010 |  |  |  |

### XÃ ĐỨC LẬP

- Nhóm: 1
- Mã/STT nhóm: 44

### Đảng ủy xã Đức Lập. - Địa chỉ: Số 702, ấp Chánh, xã Đức Lập

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 1 | Lê Huy Toàn | Bí thư | 0903 113 797 |  |  |  |
| 2 | Phùng Văn Đức | Phó Bí thư | 0918 793 248 |  |  |  |
| 3 | Trương Minh Kông | UV BTV - Chủ nhiệm UBKT ĐU | 0386 864 427 |  |  |  |
| 4 | Nguyễn Băng Châu | UV BCH - Phó Chủ nhiệm UBKT | 0908 264 269 |  |  |  |
| 5 | Nguyễn Minh Tấn | UV BTV - TB Xây dựng đảng | 0909 375 459 |  |  |  |
| 6 | Đào Văn Hùng | UV BCH - PTB Xây dựng đảng | 0909 338 664 |  |  |  |
| 7 | Lý Tuyến Lợi | UV BCH - CVP Đảng ủy | 0908 746 922 |  |  |  |
| 8 | Lê Thị Hồng Thắm | - CT MTTQ | 0918 867 770 |  |  |  |
| 9 | Nguyễn Thị Thúy Kiều | UV BCH - PCT MTTQ, CT Hội LHPN | 0908 585 928 |  |  |  |
| 10 | Trần Minh Hoàng | UV BCH - PCT MTTQ, CT Hội nông dân | 0933 324 968 |  |  |  |
| 11 | Nguyễn Khắc Mẫn | UV BCH - PCT MTTQ, BT Đoàn TN | 0868 382 041 |  |  |  |
| 12 | Châu Hồng Phát | UV BCH - PCT MTTQ, CT Hội cựu chiến binh | 0377 873 456 |  |  |  |

### HĐND xã Đức Lập.- Địa chỉ: Đường Nguyễn Văn Quá, ấp Tràm Lạc, xã Đức Lập

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 13 | Lê Huy Toàn | - CT HĐND | 0903 113 797 |  |  |  |
| 14 | Trương Minh Kông | Trưởng Ban Kinh tế - HĐND | 0386 864 427 |  |  |  |
| 15 | Lê Thị Hồng Thắm | Trưởng Ban VHXH - HĐND | 0918 867 770 |  |  |  |

### UBND xã Đức Lập - Điện thoại: 02723 849 989; email: ubndduclap@tayninh.gov.vn.

### Địa chỉ: Số 702, ấp Chánh, xã Đức Lập .

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 16 | Phan Duy Quang | Phó Bí thư - CT UBND | 0989 967 439 |  |  |  |
| 17 | Giáp Thành Công | - PCT UBND | 0989 510 977 |  |  |  |
| 18 | Lê Thị Cẩm Tú | - PCT UBND | 0933 790 679 |  |  |  |
| 19 | Phan Chí Linh | - CVP HĐND và UBND | 0933 351 679 |  |  |  |
| 20 | Lê Trường Hải | - Trưởng phòng kinh tế | 0901 686 899 |  |  |  |
| 21 | Nguyễn Huỳnh Hạnh Châu | Phó Trưởng phòng kinh tế | 0918 185 008 |  |  |  |
| 22 | Nguyễn Văn Dũng | - TP Văn hóa - Xã Hội | 0988 218 712 |  |  |  |
| 23 | Phan Thành Hưng | PTP Văn hóa - Xã hội | 0913 849 022 |  |  |  |
| 24 | Giáp Thành Công | GĐ TT Hành chính công | 0989 510 977 |  |  |  |
| 25 | Lê Thị Thu Nhàn | PGĐ TT Hành chính công | 0903 680 968 |  |  |  |
| 26 | Nguyễn Văn Ấn | GĐ TT Cung ứng DVSN công | 0983 448 033 |  |  |  |
| 27 | Nguyễn Đức Nghĩa | - Trưởng Công an | 0987 878 287 |  |  |  |
| 28 | Nguyễn Minh Triều | Phó trưởng Công an | 0984 694 588 |  |  |  |
| 29 | Trần Quốc Danh | Phó trưởng Công an | 0967 030 839 |  |  |  |
| 30 | Nguyễn Hoàng Giang | Phó trưởng Công an | 0915 699 071 |  |  |  |
| 31 | Liêu Hoàng Phúc | Phó trưởng Công an | 0394 683 389 |  |  |  |
| 32 | Dương Mạnh Thắng | Phó trưởng Công an | 0976 331 313 |  |  |  |
| 33 | Phan Thanh Trúc | - CHT BCH Quân sự | 0988 828 641 |  |  |  |
| 34 | Huỳnh Văn Là | Chức vụ đảng - CHP BCH Quân sự | 0931 200 225 |  |  |  |

### Xã Mỹ Hạnh

- Nhóm: 1
- Mã/STT nhóm: 45

### Đảng ủy MỸ HẠNH

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 1 | Phùng Cẩm Loan | Bí thư | 0933 624 956 |  |  |  |
| 2 | Trần Thị Phương | UV BTV - CN UBKT | 039 9870 780 |  |  |  |
| 3 | Bùi Văn Tài | UV BCH - PCN UBKT | 0917 788 979 |  |  |  |
| 4 | Nguyễn Chí Thành | UV BTV - TB Xây dựng đảng | 0917 293 639 |  |  |  |
| 5 | Trần Trong Nghĩa | UV BCH - PTB Xây dựng đảng | 0989 944 558 |  |  |  |
| 6 | Trần Quang Vinh | UV BCH - CVP Đảng ủy | 0909 643 949 |  |  |  |
| 7 | Lê Thị Ngọc kim | Chức vụ đảng - CT MTTQ xã | 0908 212 429 |  |  |  |
| 8 | Lê Thị Kim Thoa | UV BCH - PCT MTTQ, CT Hội PN | 0937 328 277 |  |  |  |
| 9 | Mai Ngọc Dự | UV BCH - PCT MTTQ, CT Hội ND | 0796 838 699 |  |  |  |
| 10 | Nguyễn Khắc Huy | UV BCH - PCT MTTQ, BT Đoàn TN | 0902 346 992 |  |  |  |

### HĐND MỸ HẠNH

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 11 | Nguyễn Văn Bến | Phó Bí thư - CT HĐND | 0907 970 399 |  |  |  |
| 12 | Lê Văn Tân | Đảng ủy viên-Phó CT-HĐND | 0902 077 680 |  |  |  |
| 13 | Trần Văn Tịnh | PTB Kinh tế - Ngân sách HĐND | 0933 509 278 |  |  |  |
| 14 | Nguyễn Thanh Tú | PTB VH-XH xã HĐND |  |  |  |  |

#### UBND XÃ MỸ HẠNH

- Di động: 0916 727 767

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 15 | Trần Anh Hương | Phó Bí thư - CT UBND | 0907 439 347 |  |  |  |
| 16 | Phan Xuân Trang | UV. BTV Đảng ủy - PCT UBND | 0937 780 340 |  |  |  |
| 17 | Lê Thị Ngọc Bích | Đảng ủy viên - PCT UBND | 0989 725 559 |  |  |  |
| 18 | Trần Thị Thanh Thúy | Đảng ủy viên - CVP HĐND và UBND | 0933 272 555 |  |  |  |
| 19 | Huỳnh Văn Kuônh | PCVP HĐND và UBND |  |  |  |  |

#### Phòng kinh tế MỸ HẠNH

- Di động: 0938 391 913

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 26 | Hồ Phương Bình | Đảng ủy viên - Trưởng phòng kinh tế | 0939 391 913 |  |  |  |
| 27 | Lê Văn Tài | PTP kinh tế |  |  |  |  |

#### PHÒNG Văn hóa - Xã hội MỸ HẠNH

- Di động: 0963 851 219

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 28 | Nguyễn Thị Tú Trinh | Đảng ủy viên - TP Văn hóa - Xã hội | 0963851219 |  |  |  |
| 29 | Huỳnh Văn Thanh | PTP Văn hóa - Xã hội |  |  |  |  |

### TT HÀNH CHÍNH CXÃ MỸ HẠNH

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 30 | Trần Quốc Thư | Phó GĐ TT Hành chính công |  |  |  |  |

#### TT CUNG ỨNG DVSN CXÃ MỸ HẠNH

- Di động: 0918 442 039

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 31 | Nguyễn Phúc Hương | GĐ TT Cung ứng DVSN công | 0944 250 439 |  |  |  |
| 32 | Võ Thành Trung | PGĐ TT Cung ứng DVSN công |  |  |  |  |
| 33 | Trần Quốc Thắng | UV.BTV ĐU - Trưởng Công an | 0913 150 707 | 2723850719 |  |  |

### Công an

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 34 | Cao Văn Dũng | Phó trưởng Công an | 0918 144 779 |  |  |  |
| 35 | Nguyễn Hồng Quẹo | Phó trưởng Công an | 0993 420 278 |  |  |  |
| 36 | Phan Thị Thu Hường | Phó trưởng Công an | 0828 678 345 |  |  |  |
| 37 | Trần Thuận Phát | Phó trưởng Công an | 0938 993 414 |  |  |  |
| 38 | Lê Hoàng Phong | Phó trưởng Công an | 0908 677 266 |  |  |  |

### TÊN XÃ AN NINH

- Nhóm: 1
- Mã/STT nhóm: 46

### ấp Lộc Bình, xã An Ninh

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 1 | Lê Trường Chinh | Bí thư - CT HĐND | 0949 601 789 |  |  | ấp Lộc Bình, xã An Ninh |
| 2 | Nguyễn Quốc Mẫn | Phó Bí thư Thường trực Đảng ủy | 0976 666 467 |  |  | ấp Lộc Bình, xã An Ninh |
| 3 | Phạm Hiếu Tài | Chánh Văn Phòng Đảng ủy | 0915 873 775 |  |  | ấp Lộc Bình, xã An Ninh |
| 4 | Đoàn Văn Danh | Trưởng Ban Xây dựng Đảng | 0913 180 022 |  |  | ấp Lộc Bình, xã An Ninh |
| 5 | Võ Minh Dương | PTB Xây dựng Đảng | 0776 638 334 |  |  | ấp Lộc Bình, xã An Ninh |
| 6 | Nguyễn Thị Thanh Tuyền | CN UBKT Đảng ủy | 0939 721 092 |  |  | ấp Lộc Bình, xã An Ninh |
| 7 | Lương Nguyễn Quốc Cường | Phó CN UBKT Đảng ủy | 0988 333 603 |  |  | ấp Lộc Bình, xã An Ninh |
| 8 | Lại Văn Huông | PCT HĐND xã | 0933 272 828 |  |  | ấp An Hiệp, xã An Ninh |
| 9 | Nguyễn Thị Chiến | Phó ban Văn hóa - Xã hội HĐND xã | 0383 303 032 |  |  | ấp An Hiệp, xã An Ninh |
| 10 | Phạm Tuấn Kiệt | Phó ban Kinh tế - Ngân sách HĐND xã | 0362 433 479 |  |  | ấp An Hiệp, xã An Ninh |
| 11 | Trần Văn Đạt | Chủ tịch UBND xã | 0907 554 512 |  |  | ấp An Hiệp, xã An Ninh |
| 12 | Nguyễn Thị Diệu | PCT UBND xã | 0937 841 238 |  |  | ấp An Hiệp, xã An Ninh |
| 13 | Nguyễn Thành Sơn | PCT UBND xã | 0985 345 338 |  |  | ấp An Hiệp, xã An Ninh |
| 14 | Nguyễn Thanh Hài | Chánh Văn phòng HĐND và UBND xã | 0947 536 739 |  |  | ấp An Hiệp, xã An Ninh |
| 15 | Nguyễn Thị Bé Bi | Trưởng phòng Kinh tế xã | 906520642 | ABC |  | ấp An Hiệp, xã An Ninh |
| 16 | Mang Xuân Vinh | Trưởng phòng Văn hóa - Xã hội | 0838 399 639 |  |  | ấp An Hiệp, xã An Ninh |
| 17 | Nguyễn Văn Trường | Giám đốc TT cung ứng dịch vụ sự nghiệp công xã | 0977 181 789 |  |  | ấp Lộc Bình, xã An Ninh |
| 18 | Võ Thị Kim Loan | PGĐ TT phục vụ Hành chính công xã | 0939 868 982 |  |  | ấp An Hiệp, xã An Ninh |
| 19 | Đỗ Văn Hường | CHT BCH Quân sự | 0907 570 919 |  |  | ấp An Thạnh, xã An Ninh |
| 20 | Nguyễn Thanh Tùng | Phó CHT BCH Quân sự | 0909 039 089 |  |  |  |
| 21 | Đặng Thanh Tâm | Trưởng Công an | 0938 211 677 |  |  | ấp An Hiệp, xã An Ninh |
| 22 | Ngô Thanh Phong | Chủ tịch MTTQVN xã | 0979 316 628 |  |  | ấp Lộc Bình, xã An Ninh |
| 23 | Trương Văn Minh | PCT MTTQVN xã - Chủ tịch Hội Nông dân xã | 0933 997 477 |  |  | ấp Lộc Bình, xã An Ninh |
| 24 | Trịnh Thị Hải Yến | PCT MTTQVN xã - CT Hội PN xã | 0964 456 912 |  |  | ấp Lộc Bình, xã An Ninh |
| 25 | Nguyễn Thanh Hoa | PCT MTTQVN xã - BT Đoàn TN xã | 0364 725 330 |  |  | ấp Lộc Bình, xã An Ninh |
| 26 | Võ Văn Thọ | PCT MTTQVN xã - Chủ tịch Hội CCB | 0976 924 679 |  |  | ấp Lộc Bình, xã An Ninh |

### XÃ HÒA KHÁNH

- Nhóm: 1
- Mã/STT nhóm: 47

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 1 | Vũ Hồng Hạnh | Bí thư Đảng ủy - CT.HĐND | 0909 897 779 |  |  |  |
| 2 | Nguyễn Minh Tân | Phó Bí thư Đảng ủy | 0909 492 151 |  |  |  |
| 3 | Võ Hoàng Liệu | UV.BTV-CN UBKT Đảng ủy | 0941 349 377 |  |  |  |
| 4 | Nguyễn Thị Ngọc Thúy | UV.BCH-Phó CN UBKT | 0366648349 |  |  |  |
| 5 | Nguyễn Văn Dương | UVTV - TB XD Đảng | 0986331433 |  |  |  |
| 6 | Nguyễn Văn Sù | UV.BCH-Phó Ban XD Đảng | 0866089149 |  |  |  |
| 7 | Trần Thị Kim Sa | UV.BCH-CVP Đảng ủy | 0765509189 |  |  |  |
| 8 | Trần Thị Ngọc Sương | UV.BTV-CT.MTTQ xã | 0939447878 |  |  |  |
| 9 | Nguyễn Thị Mộng Dâu | UV.BCH-Phó CT.MTTQ ( Hội PN) | 0933298150 |  |  |  |
| 10 | Trần Minh Mẫn | UV.BCH-Phó CT.MTTQ ( Hội ND) | 0977410449 |  |  |  |
| 11 | Hồ Nguyễn Thị Đăng Khoa | UV.BCH-Phó CT.MTTQ ( Bí thư Đoàn) | 0974816724 |  |  |  |
| 12 | Đặng Thái Ngọc | UV.BCH-Phó CT.MTTQ ( Hội CCB) | 0985008094 |  |  |  |
| 13 | Nguyễn Văn Hùng | UV.BTV-PCT HĐND | 0916864829 |  |  |  |
| 14 | Lại Thị Thu Hồng | UV.BCH-Ban Kinh tế HĐND | 0393906656 |  |  |  |
| 15 | Trương Văn Tuấn | UV.BCH- Ban Văn hóa HĐND | 0942622114 |  |  |  |
| 16 | Nguyễn Hoàng Vũ | P.BT Đảng ủy - CT.UBND xã | 0358089777 |  |  |  |
| 17 | Nguyễn Minh Tuấn | UVBTV- PCT UBND xã -GĐTTHCC | 0947004291 |  |  |  |
| 18 | Mai Minh Mẫn Nhuệ | UVBTV - PCT UBND xã | 0909431175 |  |  |  |
| 19 | Lại minh Đắc | UV BCH -CVP HĐND-UBND | 0908931605 |  |  |  |
| 20 | Nguyễn Văn Trung | Phó CVP HĐND-UBND | 0985180086 |  |  |  |
| 21 | Đặng Minh Tuyết | UV.BCH-Trưởng Phòng Kinh tế | 0907693497 |  |  |  |
| 22 | Huỳnh Minh Tâm | PTP Kinh tế | 0945674279 |  |  |  |
| 23 | Nguyễn Ngọc Thảo | UV.BCH-Trưởng Phòng VHXH | 0937474674 |  |  |  |
| 24 | Nguyễn Thanh Toàn | PTP VHXH | 0794740912 |  |  |  |
| 25 | Nguyễn Minh Đăng | Phó GĐ TTHCC | 0918593845 | 02723851032 |  |  |
| 26 | Trần Thị Kim Khanh | GĐ TT cung ứng DVC | 0913180054 |  |  |  |
| 27 | Nguyễn Thành Trung | UV.BTV-Trưởng Công an | 0989393978 |  |  |  |
| 28 | Mai Hữu Trí | Phó Công an | 0937670093 |  |  |  |
| 29 | Nguyễn Bảy Đỏ | UV.BTV-TB CHQS | 0933534014 |  |  |  |

### XÃ BẾN LỨC

- Nhóm: 1
- Mã/STT nhóm: 48

### Đảng ủy Bến Lức - Địa chỉ: 211, Quốc lộ 1A, ấp Bến Lức 3, xã Bến Lức

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 1 | Nguyễn Đăng Minh Xuân | Bí thư | 0903 199 972 |  |  |  |
| 2 | Phạm Văn Trài | UV BTV - CN UBKT | 0985 139 089 |  |  |  |
| 3 | Bùi Vũ Huy | UV BCH - PCN UBKT | 0984 275 664 |  |  |  |
| 4 | Nguyễn Thanh Bình | UV BTV - TB Xây dựng đảng | 0982 977 933 |  |  |  |
| 5 | Hà Văn Cảnh | UV BCH - PTB Xây dựng đảng | 0918 499 077 |  |  |  |
| 6 | Hồ Hoàng Duy Khánh | UV BCH - CVP Đảng ủy | 0933 441 012 |  |  |  |
| 7 | Nguyễn Minh Thắng | UV BTV - CT MTTQ xã | 0909 171 072 |  |  |  |
| 8 | Lê Kim Cương | UV BCH - PCT MTTQ, CT Hội PN | 0972 820 840 |  |  |  |
| 9 | Lê Minh Thưởng | UV BCH - PCT MTTQ, CT Hội ND | 0972 962 637 |  |  |  |
| 10 | Huỳnh Minh Quân | UV BCH - PCT MTTQ, BT Đoàn TN | 0949 613 949 |  |  |  |
| 11 | Bù̀i Văn Bụi | UV BCH - PCT MTTQ, CT Hội CCB | 0918 602 323 |  |  |  |

### HĐND Bến Lức - Địa chỉ: 211, Quốc lộ 1A, ấp Bến Lức 3, xã Bến Lức

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 12 | Phạm Thanh Sơn | PBT - CT HĐND | 0908 241 224 |  |  |  |
| 13 | Nguyễn Minh Hùng | UV BTV-PCT HĐND | 0918 117 899 |  |  |  |
| 14 | Lê Nguyễn Thanh Phương | Ban Kinh tế - HĐND | 0907 676 313 |  |  |  |
| 15 | Huỳnh Thị Lệ Thu | Ban VHXH - HĐND | 0908 745 809 |  |  |  |

### UBND xã Bến Lức - ĐT bàn: 02723.979.017 ;

### Địa chỉ: 211, Quốc lộ 1A, ấp Bến Lức 3, xã Bến Lức

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 16 | Nguyễn Thành Nam | Phó Bí thư - CT UBND | 0918 787 037 |  |  |  |
| 17 | Võ Minh Hải | UV BTV - PCT UBND | 0908 474 656 |  |  |  |
| 18 | Huỳnh Thị Mộng Tuyền | UV BTV - PCT UBND - GĐ TTHCC | 0914 038 898 |  |  |  |
| 19 | Lê Quốc Bảo | UV BCH - CVP HĐND và UBND | 0907 197 606 |  |  |  |
| 20 | Nguyễn Minh Thành | UV BCH - Trưởng phòng kinh tế | 0942 441 786 |  |  |  |
| 21 | Đặng Phước Khánh | PTP kinh tế | 0913 180 223 |  |  |  |
| 22 | Cao Huỳnh Hữu Nhân | UV BCH - TP Văn hóa - Xã hội | 0902 523 638 |  |  |  |
| 23 | Huỳnh Anh Tuấn | PTP Văn hóa - Xã hội | 0918 626 339 |  |  |  |
| 24 | Nguyễn Văn Vũ | PGĐ TT Hành chính công | 0918 416 309 |  |  |  |
| 25 | Phan Văn Na | UV BCH - GĐ TT Cung ứng DVSN công | 0834 783 456 |  |  |  |
| 26 | Phan CNghiệp | UV BTV - Trưởng Công an | 0933 347 677 |  |  |  |
| 27 | Nguyễn Tuấn Phú | UV BTV - CHT BCH Quân sự | 0983 908 953 |  |  |  |

### XÃ THẠNH LỢI

- Nhóm: 1
- Mã/STT nhóm: 49

### Đảng ủy - Địa chỉ: Đường số 5, Ấp 4 Lương Bình, xã Thạnh Lợi

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 1 | Phan Văn Cường | Bí thư - CT HĐND | 0914 710 672 | 02723.646 931 |  |  |
| 2 | Huỳnh Kim Thái Long | Phó Bí thư | 0908 863 085 | 02723.646 931 |  |  |
| 3 | Trần Thị Hóa | UV BTV - CN UBKT | 0843 630 209 |  |  |  |
| 4 | Nguyễn Hoàng Hải | UV BCH - PCN UBKT | 0828 786 713 |  |  |  |
| 5 | Nguyễn Thanh An | UV BTV - TB Xây dựng đảng | 0919 891 033 |  |  |  |
| 6 | Trần Thị Thùy Dương | UV BCH - PTB Xây dựng đảng | 0902 733 743 |  |  |  |
| 7 | Ngô Thị Ngọc Như | UV BCH - CVP Đảng ủy | 0384 840 007 |  |  |  |
| 8 | Ngô Văn Bình | UV BTV - CT.MTTQ | 0908 842 311 |  |  |  |
| 9 | Đặng Thị Thu Trúc | UV BCH - PCT.MTTQ kiêm CT.HLHPN | 0852 038 090 |  |  |  |
| 10 | Phạm Văn Khanh | UV BCH - PCT.MTTQ kiêm CT.HND | 0933 196 956 |  |  |  |
| 11 | Lê Thái Phong | UV BCH - PCT.MTTQ kiêm BT.ĐTNCSHCM | 0786 153 418 |  |  |  |
| 12 | Trần CTrực | UV BCH - PCT.MTTQ kiêm CT.CCB | 0889 433 660 |  |  |  |

### Hội đồng nhân dân - Địa chỉ: Đường số 5, Ấp 4 Lương Bình, xã Thạnh Lợi

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 13 | Lê Đức Tâm | UV BTV - PCT HĐND | 0908 054 454 |  |  |  |
| 14 | Trần Văn Đỏ | UV BCH - Phó ban KTNS - HĐND | 0916 818 483 |  |  |  |
| 15 | Võ Thị Trúc Giang | UV BCH - Phó ban Văn hóa - HĐND | 0914 516 183 |  |  |  |

### UBND xã - email: ubndthanhloi@tayninh.gov.vn

### Địa chỉ: Số 95, đường số 1, KDC Thạnh Lợi, xã Thạnh Lợi

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 16 | Huỳnh Thành Tâm | Phó Bí thư - CT UBND | 0933 663 683 |  |  |  |
| 17 | Huỳnh Văn Thiêm | UV BTV - PCT UBND | 0942 331 264 |  |  |  |
| 18 | Trần Ngọc Ẩn | UV BTV - PCT UBND kiêm GĐ.TTPVHCC | 0909 284 261 |  |  |  |
| 19 | Nguyễn Văn Hùng | UV BCH - Chánh VP.HĐND -UBND | 0918 654 346 |  |  |  |
| 20 | Lê Anh Kiệt | UV BCH - Trưởng phòng KT | 0915 818 095 |  |  |  |
| 21 | Nguyễn Hồng Tâm | PTP Kinh tế | 0989 813 110 |  |  |  |
| 22 | Nguyễn Triệu Kim Ngân | UV BCH - Trưởng phòng VHXH | 0914 516 157 |  |  |  |
| 23 | Bùi Minh Tuấn | PTP Văn hóa - xã hội | 0948 673 427 |  |  |  |
| 24 | Nguyễn Hoàng Hên | PGĐ - TTPVHCC | 0974 977 828 | 02723 630 456 |  |  |
| 25 | Trần Quốc Thái | UV BTV - Trưởng Công an | 0826 272 767 | 02723 646 084 |  |  |
| 26 | Huỳnh Tấn Luận | UV BCH - Phó Trưởng Công an | 0919 125 850 | 02723 646 084 |  |  |
| 27 | Phan Minh Luân | UV BTV - CHT.BCHQS | 0946 943 218 | 02723 638 009 |  |  |
| 28 | Phan Nhật Tiến | UV BCH - Phó CHT BCHQS | 0708 889 491 |  |  |  |

### XÃ BÌNH ĐỨC

- Nhóm: 1
- Mã/STT nhóm: 50

### Đảng ủy Bình Đức - Địa chỉ: Ấp Kênh Ngay, Xã Bình Đức

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 1 | Nguyễn Thị Phong Lan | UV BTV.Bí thư | 0379 459 270 |  |  |  |
| 2 | Nguyễn Hoàng Minh | UV BTV. Phó Bí thư | 0907 011 879 |  |  |  |
| 3 | Nguyễn Hoàng Giang | UV BTV. Phó Bí thư | 0937 167 468 |  |  |  |
| 4 | Phạm Thị Ngọc Phủy | UV BTV - TB XDĐ | 0972 007 647 |  |  |  |
| 5 | Phan Văn Thắng | UV BTV - CN UBNKT | 0918 856 451 |  |  |  |
| 6 | Huỳnh Tuấn Khải | ĐUV - CT UBMTTQ | 0908 917 479 |  |  |  |
| 7 | Lê Thị Phương | ĐUV - PCT UBMTTQ-CT HLHPN | 0979 764 303 |  |  |  |
| 8 | Phan Thị Thưa | ĐUV - PCT UBMTTQ-CT HND-CT CĐ | 0915 403 567 |  |  |  |
| 9 | Nguyễn Thanh Tùng | ĐUV - PCT UBMTTQ-CT HCCB | 0858 993 879 |  |  |  |
| 10 | Nguyễn Thị Hồng Thanh | ĐUV - PCT UBMTTQ-BT ĐTN | 0328 866 972 |  |  |  |
| 11 | Võ Thành Sơn | ĐUV - Chánh VPĐU | 0829 384 656 |  |  |  |
| 12 | Phan Ngọc Nhiển | ĐUV - PTB XDĐ | 0941 645 965 |  |  |  |
| 13 | Huỳnh Quốc Vương | ĐUV - Phó CN UBKT | 0367 860 506 |  |  |  |

### HĐND Bình Đức - ĐỊA CHỈ; ĐƯỜNG KÊNH MỚI, ẤP 5 THẠNH ĐỨC, XÃ BÌNH ĐỨC

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 15 | Nguyễn Hoàng Minh | ĐUV - CT HĐND | 0907 011 879 |  |  |  |
| 16 | Nguyễn Thành Lộc | UV BTV - PCT HĐND / TB KT. HĐND | 0948 444 778 |  |  |  |
| 17 | Phạm Thị Ngọc Phủy | UV BTV - TB VHXH-HĐND | 0972 007 647 |  |  |  |
| 18 | Huỳnh Thị Mỹ | ĐUV - Phó Ban KT- HĐND | 0979 130180 |  |  |  |
| 19 | Lê Thanh Cần | ĐUV.Ban VHXH - HĐND | 0846 456 355 |  |  |  |

### UBND xã Bình Đức - ĐT bàn:02723 635 335 ; email: ubnd_xabinhduc.@tayninh.gov.vn

### ĐỊA CHỈ; ĐƯỜNG KÊNH MỚI, ẤP 5 THẠNH ĐỨC, XÃ BÌNH ĐỨC

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 20 | Nguyễn Hoàng Giang | UV BTV. CT UBND xã | 0937 167 468 |  |  |  |
| 21 | Lê Phát Thái | ĐUV - PCT UBND | 0909 676 968 |  |  |  |
| 22 | Văn Thị Hồng Nga | ĐUV - PCT UBND | 0902 923 297 |  |  |  |
| 23 | Nguyễn Duy Trinh | ĐUV. CVP HĐND và UBND | 0918 977 886 |  |  |  |
| 24 | Phan Minh Trung | ĐUV. PCVP HĐND và UBND | 0908 899 975 |  |  |  |
| 25 | Văn Cao Trí Vũ | ĐUV. Trưởng phòng kinh tế | 0919 535 519 |  |  |  |
| 26 | Huỳnh Thanh Phong | ĐUV. PTP kinh tế | 0918 085 956 |  |  |  |
| 27 | Huỳnh Trọng Thanh | ĐUV. TP Văn hóa - Xã hội | 0839 839 939 |  |  |  |
| 28 | Phan Thành Tâm | PTP Văn hóa - Xã hội | 0909 600 660 |  |  |  |
| 29 | Lê Phát Thái | ĐUV. GĐ TT Hành chính công | 0909 676 968 |  |  |  |
| 30 | Nguyễn Thị Hoàng Oanh | ĐUV. PGĐ TT Hành chính công | 0786 833 255 |  |  |  |
| 31 | Nguyễn Thị Kiều Nga | ĐUV.GĐ TT Cung ứng DVSN công | 0937 074 314 |  |  |  |
| 32 | Đặng Minh Tú | UV BTV - Trưởng Công an | 0975 575 559 |  |  |  |
| 33 | Nguyễn Văn Điệp | ĐUV. Phó trưởng Công an | 0909 270 284 |  |  |  |
| 34 | Võ Đức Trí | Phó trưởng Công an | 0909 418 718 |  |  |  |
| 35 | Lê Hoàng Dan | Phó trưởng Công an | 0938 823 131 |  |  |  |
| 36 | Lê Thị Minh Xuân | Phó trưởng Công an | 0772 689 968 |  |  |  |
| 37 | Nguyễn Viết Thuần | ĐUV - Phó trưởng Công an | 0918 481 069 |  |  |  |
| 38 | Lê Hồng Phúc | ĐUV - CHT BCH Quân sự | 0856 785 608 |  |  |  |
| 39 | Dương Thái Kiều | ĐUV - PCHT BCH Quân sự | 0837 474 826 |  |  |  |

### XÃ LƯƠNG HOÀ

- Nhóm: 1
- Mã/STT nhóm: 51

### Đảng ủy Xã Lương Hoà - Địa chỉ: Số 76A, đường vào chợ Tân Bửu, Ấp 2, Xã Lương Hòa

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 1 | Lê Văn Lộc | Bí thư | 0918 856 452 |  |  |  |
| 2 | Nguyễn Anh Thư | Phó Bí thư | 0907 060 313 |  |  |  |
| 3 | Đặng Cửu Long | Phó Bí thư - CT UBND | 0918 898 169 |  |  |  |
| 4 | Nguyễn Thị Thu Kiều | UV BTV - PCT UBND | 0967 377 988 |  |  |  |
| 5 | Nguyễn Hoàng Nam | UV BTV - PCT UBND | 0937 479 767 |  |  |  |
| 6 | Nguyễn Văn Gia | UV BTV - Trưởng ban XDĐ | 0909 344 963 |  |  |  |
| 7 | Nguyễn Đình Long | UV BTV - Chủ nhiệm UBNKT | 0903 766 621 |  |  |  |
| 8 | Trần Minh Tâm | Chủ tịch UB MTTQ VN | 0836 091 213 |  |  |  |
| 9 | Trần Thị Tú Anh | PCT MTTQ - CT Hội PN | 0876 628 477 |  |  |  |
| 10 | Nguyễn Thị Ngọc Thu | PCT Thường trực MTTQ - CT Hội ND | 0987 626 171 |  |  |  |
| 11 | Trương Văn Hòa | PCT MTTQ - CT Hội CCB | 0982 800 599 |  |  |  |
| 12 | Mai Thu Diễm | PCT MTTQ - BT Đoàn TN | 0981 715 768 |  |  |  |
| 13 | Nguyễn Kim Thảo Ngân | ĐUV - Chánh VPĐU | 0346 830 797 |  |  |  |
| 14 | Lê Hữu Thiện | ĐUV - Phó Chánh VPĐU | 0918 666 784 |  |  |  |
| 15 | Trần Minh Tâm | ĐUV - Phó trưởng ban XDĐ | 0836 091 213 |  |  |  |
| 16 | Huỳnh Chí Trung | ĐUV - Phó CN UBKT | 0908 035 758 |  |  |  |

### HĐND xã Lương Hoà - Địa chỉ: Số 69, ĐT 830, Ấp 6B, Xã Lương Hoà

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 17 | Nguyễn Anh Thư | ĐUV - CT HĐND | 0907 060 313 |  |  |  |
| 18 | Nguyễn Văn Tuấn | UV BTV - PCT HĐND | 0985 740 890 |  |  |  |
| 19 | Nguyễn Văn Gia | UV BTV - Trưởng ban VHXH-HĐND | 0909 344 963 |  |  |  |
| 20 | Phạm Hoàng Minh | ĐUV - Phó Ban KTNS- HĐND | 0833 372 273 |  |  |  |
| 21 | Trương Thị Thanh Tâm | ĐUV.Ban VHXH - HĐND | 0326 841 205 |  |  |  |

### UBND Xã Lương Hoà - ĐT bàn:02723 873 064 ; email: ubnd_xalươnghoa@tayninh.gov.vn

### Địa chỉ: Số 69, ĐT 830, Ấp 6B, Xã Lương Hoà, tỉnh Tây Ninh

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 22 | Đặng Cửu Long | Phó Bí thư - CT UBND xã | 0918 898 169 |  |  |  |
| 23 | Nguyễn Hoàng Nam | ĐUV - PCT UBND | 0937 479 767 |  |  |  |
| 26 | Nguyễn Thị Thu Kiều | ĐUV - PCT UBND | 0967 377 988 |  |  |  |
| 27 | Phạm Thị Trà My | ĐUV. CVP HĐND và UBND xã | 0918 898 107 |  |  |  |
| 28 | Trần Thị Ngọc Châu | ĐUV. Trưởng phòng kinh tế xã | 0933 603 878 |  |  |  |
| 29 | Huỳnh Thanh Phong | ĐUV. Phó Trưởng phòng kinh tế xã | 0972 141 628 |  |  |  |
| 30 | Trần Thị Thùy Trang | ĐUV. TP Văn hóa - Xã hội | 0936 444 012 |  |  |  |
| 31 | Nguyễn Ngọc Huân | PTP Văn hóa - Xã hội | 0918 439 808 |  |  |  |
| 32 | Nguyễn Hoàng Nam | ĐUV. GĐ TT Hành chính công | 0937 479 767 |  |  |  |
| 33 | Huỳnh Minh Trung | ĐUV. PGĐ Trung tâm Hành chính công | 090 9676 665 |  |  |  |
| 34 | Hồ Đặng Chí Nhân | ĐUV.GĐ TT Cung ứng DVSN công | 0918 250 232 |  |  |  |

### Công an Xã Lương Hoà - ĐT bàn: 02723 634 113 / Địa chỉ: ĐT 830, Ấp 9, Xã Lương Hoà

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 35 | Nguyễn Châu Thành Luân | ĐUV - Trưởng Công an | 0983 520 207 |  |  |  |
| 36 | Hồ Minh Tân | ĐUV - Phó trưởng Công an | 0913 186 062 |  |  |  |
| 37 | Nguyễn Văn Ngọc | Phó trưởng Công an | 0972 742 288 |  |  |  |
| 38 | Đỗ Thị Thúy Hằng | Phó trưởng Công an | 0949 652 652 |  |  |  |
| 39 | Đặng Liên Việt | Phó trưởng Công an | 0918 335 373 |  |  |  |
| 40 | Phạm Tấn Huỳnh Còn | Phó trưởng Công an | 0917 211 121 |  |  |  |

### Quân sự Xã Lương Hoà - ĐT bàn: 02723 873 890 / Địa chỉ: Số 76A, đường vào chợ Tân Bửu, Ấp 2, Xã Lương Hoà

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 41 | Bùi Khương Bảo | ĐUV - CHT BAN CHQS | 0982 157 564 |  |  |  |
| 42 | Lê Thành Phát | ĐUV - PCHT BAN CHQS | 0981 863 940 |  |  |  |

### XÃ MỸ YÊN

- Nhóm: 1
- Mã/STT nhóm: 52

### ĐT bàn: 02723 643 702; 02723 870 402; email: danguyxamyyen@tayninh.gov.vn; ubnd_xamyyen@tayninh.gov.vn

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 1 | Lê Thành Út | Bí thư - CT HĐND | 0908 924 760 | 02723 643 702 |  | Ấp 5 Mỹ Yên, xã Mỹ Yên |
| 2 | Đặng Thị Cẩm Vân | Phó Bí thư | 0976 383 082 |  |  | Ấp 5 Mỹ Yên, xã Mỹ Yên |
| 3 | Nguyễn Quốc Hùng | Phó Bí thư - CT UBND | 0989 366 619 | 02723 870 402 |  | Ấp Chợ, xã Mỹ Yên |
| 4 | Nguyễn Văn Minh | UV BTV - PCT HĐND | 0937 074 365 |  |  | Ấp 5 Mỹ Yên, xã Mỹ Yên |
| 5 | Trần Thị Ánh Tuyết | UV BTV - PCT UBND | 0976 993 533 |  |  | Ấp Chợ, xã Mỹ Yên |
| 6 | Trương Trần Quốc | UV BTV - CN UBKT | 0908 988 101 |  |  | Ấp 5 Mỹ Yên, xã Mỹ Yên |
| 7 | Nguyễn Minh Trung | UV BTV - Trưởng Công an | 0916 391 079 | 02723 642 113 |  | ĐT.833B, ấp Chánh, xã Mỹ Yên |
| 8 | Nguyễn Thanh Tuân | UV BTV - CHT BCH QS | 0917 879 730 | 02723 641 593 |  | ĐT.830C, Ấp 5 Mỹ Yên, xã Mỹ Yên |
| 9 | Lê Thị Trang Thư | UV BTV - CT UB MTTQ VN | 0354 598 388 |  |  | Ấp 5 Mỹ Yên, xã Mỹ Yên |
| 10 | Lê Anh Tuấn | UV BCH - TB XDĐ | 0982 991 345 |  |  | Ấp 5 Mỹ Yên, xã Mỹ Yên |
| 11 | Đặng Hoàng Phúc | UV BCH - PCT UBND | 0918 499 887 |  |  | Ấp Chợ, xã Mỹ Yên |
| 12 | Dương Thị Thanh Thúy | UV BCH - CVP Đảng ủy | 0977 505 560 |  |  | Ấp 5 Mỹ Yên, xã Mỹ Yên |
| 13 | Phan Thị Yến Ly | UV BCH - PTB XDĐ | 0945 805 717 |  |  | Ấp 5 Mỹ Yên, xã Mỹ Yên |
| 14 | Nguyễn Thị Bích Ngọc | UV BCH - PCT UB MTTQ VN / đồng thời làm CT Hội LHPN | 0819 280 777 |  |  | Ấp 5 Mỹ Yên, xã Mỹ Yên |
| 15 | Huỳnh CHưởng | UV BCH - PCT UB MTTQ VN / đồng thời làm BT ĐTN | 0968 995 660 |  |  | Ấp 5 Mỹ Yên, xã Mỹ Yên |
| 16 | Lưu Trọng Liêm | UV BCH - PCT UB MTTQ VN / đồng thời làm CT HND | 0907 075 224 |  |  | Ấp 5 Mỹ Yên, xã Mỹ Yên |
| 17 | Huỳnh Minh Thiện | UV BCH - CVP HĐND-UBND | 0986 169 288 |  |  | Ấp Chợ, xã Mỹ Yên |
| 18 | Phạm Thanh Trí | UV BCH - TP Kinh tế | 0909 497 456 |  |  | Ấp Chợ, xã Mỹ Yên |
| 19 | Phan Quang Lành | UV BCH - TP Văn hóa - Xã hội | 0943 643 349 |  |  | Ấp Chợ, xã Mỹ Yên |
| 20 | Trần Kim Ngân | UV BCH - Phó Ban KT-NS | 0794 462 040 |  |  | Ấp 5 Mỹ Yên, xã Mỹ Yên |
| 21 | Trần Thị Tố Quyên | UV BCH - Phó Ban VH-XH | 0914 183 938 |  |  | Ấp 5 Mỹ Yên, xã Mỹ Yên |
| 22 | Hồ Quốc Kỳ | UV BCH - Phó Trưởng Công an | 0919 118 171 | 02723 642 113 |  | ĐT.833B, ấp Chánh, xã Mỹ Yên |
| 23 | Nguyễn Xuân Minh | UV BCH - PCHT BCH QS | 0898 776 669 | 02723 641 593 |  | ĐT.830C, ấp 5 Mỹ Yên, xã Mỹ Yên |
| 24 | Nguyễn Thị Yến Linh | UV BCH - HT Trường MG / Mỹ Yên | 0352 179 874 | 02723 643 627 |  | Ấp 5 Mỹ Yên, xã Mỹ Yên |
| 25 | Nguyễn Thị Thu Hà | UV BCH - HT Trường MG / Phước Lợi | 0348 827 568 | 02723 647 852 |  | Ấp 5 Phước Lợi, xã Mỹ Yên |
| 26 | Nguyễn Thanh Thái | UV BCH - HT Trường TH&THCS Nguyễn Văn Hiển | 0973 814 639 | 02723 890 456 |  | Ấp 5 Mỹ Yên, xã Mỹ Yên |
| 27 | Phạm Anh Dũng | PCVP HĐND-UBND | 0918 215 396 |  |  | Ấp Chợ, xã Mỹ Yên |
| 28 | Trần Bảo Thành | PTP Kinh tế | 0988 085 957 |  |  | Ấp Chợ, xã Mỹ Yên |
| 29 | Phạm Duy An | PTP Văn hóa - Xã hội | 0918 318 022 |  |  | Ấp Chợ, xã Mỹ Yên |
| 30 | Đặng Thanh Phương | PGĐ TT PV HCC | 0924 393 979 |  |  | Ấp Chợ, xã Mỹ Yên |
| 31 | Nguyễn Thành Nhân | PGĐ TT CUDV SNC | 0385 836 838 |  |  | Ấp 5 Phước Lợi, xã Mỹ Yên |

### XÃ CẨN ĐƯỚC

- Nhóm: 1
- Mã/STT nhóm: 53

### Số 1, đường Trần Phú, ấp 1, xã Cần Đước

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 1 | Nguyễn Tuấn Thanh | Bí thư | 903610815 | 2723681888 |  | Số 1, đường Trần Phú, ấp 1, xã Cần Đước |
| 2 | Nguyễn Hoàng Phúc | Phó Bí thư - Chủ tịch HĐND | 0911 686 357 |  |  | Số 1, đường Trần Phú, ấp 1, xã Cần Đước |
| 3 | Lê Minh Bảo | Phó Bí thư - Chủ tịch UBND xã | 0903 336 900 | 2723712767 |  | Số 1, đường Trần Phú, ấp 1, xã Cần Đước |
| 4 | Nguyễn Thị Tuyết Sương | UV BTVĐU - PCT HĐND | 0946 017 885 |  |  | Số 1, đường Trần Phú, ấp 1, xã Cần Đước |
| 5 | Võ Chí Công | UV BTVĐU - PCT UBND xã | 0908 826 397 |  |  | Số 1, đường Trần Phú, ấp 1, xã Cần Đước |
| 6 | Tô Thị Tuyết Mai | UV BTVĐU - PCT UBND xã | 773321217 |  |  | Số 1, đường Trần Phú, ấp 1, xã Cần Đước |
| 7 | Nguyễn Thị Trúc Linh | UV BTVĐU - TB Xây dựng Đảng - Kiêm TB VH -XH HĐND | 977359953 |  |  | Số 1, đường Trần Phú, ấp 1, xã Cần Đước |
| 8 | Nguyễn Thị Kim Cương | UV BTVĐU - CN UBKT Đảng ủy - Kiêm TB KT - NS HĐND | 0973 497 874 |  |  | Số 1, đường Trần Phú, ấp 1, xã Cần Đước |
| 9 | Nguyễn Hoài Phong | UV BTVĐU - Trưởng Công an | 0909 664 499 |  |  | ấp 9, xã Cần Đước |
| 10 | Ngô Văn Toàn | UV BTVĐU - CHT BCHQS xã | 775185629 |  |  | ấp 15, xã Cần Đước |
| 11 | Trương Thị Trầm Hương | ĐUV - CVP Đảng ủy | 903022774 | 2723681888 |  | Số 1, đường Trần Phú, ấp 1, xã Cần Đước |
| 12 | Võ Thanh Nghị | Phó CVP Đảng ủy | 981875922 |  |  | Số 1, đường Trần Phú, ấp 1, xã Cần Đước |
| 13 | Nguyễn Thành Trung | ĐUV - PTB Xây dựng Đảng | 797126272 |  |  | Số 1, đường Trần Phú, ấp 1, xã Cần Đước |
| 14 | Phạm Hồng Quân | ĐUV - Phó trưởng Công an | 918127203 |  |  | ấp 9, xã Cần Đước |
| 15 | Võ Phan Hiền Năng | ĐUV - PCHT BCHQS xã | 964979835 |  |  | ấp 15, xã Cần Đước |
| 16 | Trần Thị Trúc Hà | ĐUV - Hiệu trưởng Trường THCS Tân Ân | 938081939 |  |  | ấp 15, xã Cần Đước |
| 17 | Trần Ánh Hồng | ĐUV - PTB VH-XH HĐND | 907697364 |  |  | Số 1, đường Trần Phú, ấp 1, xã Cần Đước |
| 18 | Phạm Thanh Quang | ĐUV - PTB KT-NS HĐND | 982876963 |  |  | Số 1, đường Trần Phú, ấp 1, xã Cần Đước |
| 19 | Cao Thị Kim Nguyệt | ĐUV - CVP HĐND và UBND | 0908 828 025 |  |  | Số 1, đường Trần Phú, ấp 1, xã Cần Đước |
| 20 | Trần Minh Luân | PCVP HĐND và UBND | 0909 784 332 |  |  | Số 1, đường Trần Phú, ấp 1, xã Cần Đước |
| 21 | Trương Văn Thành | ĐUV - Trưởng phòng Kinh tế | 0908 302 044 |  |  | Số 1, đường Trần Phú, ấp 1, xã Cần Đước |
| 22 | Nguyễn Thị Hồng Lam | PTP Kinh tế | 0385 870 253 |  |  | Số 1, đường Trần Phú, ấp 1, xã Cần Đước |
| 23 | Hồ Thị Đoan Vân | ĐUV - Trưởng phòng Văn hóa - Xã hội | 0909 654 292 |  |  | Số 1, đường Trần Phú, ấp 1, xã Cần Đước |
| 24 | Võ Văn Sớm | PTP Văn hóa - Xã hội | 0918 898 306 |  |  | Số 1, đường Trần Phú, ấp 1, xã Cần Đước |
| 25 | Lê Minh Phụng | ĐUV - Phó GĐ TT hành chính công | 0978 785 709 |  |  | đường Trần Phú, ấp 1, xã Cần Đước |
| 26 | Phan Thị Thu Yến | GĐ TT Cung ứng Dịch vụ sự nghiệp Công | 0937 868 103 | 2723881189 |  | ấp 1, xã Cần Đước |
| 27 | Trần Nam Trung | ĐUV - Phó Chủ nhiện UBKT Đảng ủy | 918292360 |  |  | ấp 1, / xã Cần Đước |
| 28 | Ngô Thái Hồng Phong | ĐUV - GĐ TT Chính trị | 986207191 | 0723 882 181 |  | Số 88, đường Trần Hưng Đạo, ấp 5, xã Cần Đước |
| 29 | Phan Thanh Hòa | ĐUV - Chủ tịch UB MTTQVN xã | 987656971 |  |  | Số 1, đường Trần Phú, ấp 1, xã Cần Đước |
| 30 | Nguyễn Định Tường | ĐUV - PCT UB MTTQVN xã, / BT Đoàn TN xã | 375757739 |  |  | Số 1, đường Trần Phú, ấp 1, xã Cần Đước |
| 31 | Nguyễn Thị Hồng Hạnh | ĐUV - PCT UB MTTQVN xã, / Chủ tịch Hội Liên hiệp Phụ nữ xã | 907560723 |  |  | Số 1, đường Trần Phú, ấp 1, xã Cần Đước |
| 32 | Nguyễn Kim Sơn | ĐUV - PCT UB MTTQVN xã, / CT Hội ND | 907277190 |  |  | Số 1, đường Trần Phú, ấp 1, xã Cần Đước |
| 33 | Nguyễn Hoàng Chiến | ĐUV - PCT UB MTTQVN xã, / CT Hội CCB xã | 916337370 |  |  | Số 1, đường Trần Phú, ấp 1, xã Cần Đước |

### XÃ LONG CANG

- Nhóm: 1
- Mã/STT nhóm: 54

### Đảng ủy Long Cang, - Địa chỉ: Tỉnh lộ 835C, ấp 11, xã Long Cang

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 1 | Phan Nhân Duy | Bí thư | 0979 123 999 | 02723 883 321 |  |  |
| 2 | Phạm Văn Xum | Phó Bí thư Thường trực | 0918 080 829 |  |  |  |
| 3 | Quách Đăng Tùng | UV BTV - CN UBKT | 0932 702 909 |  |  |  |
| 4 | Lưu Quang Thuận | UV BCH - PCN UBKT | 0909 140 352 |  |  |  |
| 5 | Nguyễn Minh Trang | UV BTV - TB Xây dựng đảng | 0931 268 033 |  |  |  |
| 6 | Nguyễn Văn Chọn | UV BCH - PTB Xây dựng đảng | 0909 680 837 |  |  |  |
| 7 | Nguyễn Thị Như Thủy | UV BCH - CVP Đảng ủy | 0355 449 444 |  |  |  |
| 8 | Lại Thị Kim Minh | UV BTV - CT MTTQ xã | 0938 019 280 |  |  |  |
| 9 | Đoàn Hoàng Uyên | UV BCH - PCT MTTQ, CT Hội PN | 0917 056 849 |  |  |  |
| 10 | Nguyễn Tấn Minh | UV BCH - PCT MTTQ, CT Hội ND | 0347 289 789 |  |  |  |
| 11 | Đào Quốc Việt | UV BCH - PCT MTTQ, BT Đoàn TN | 0369 994 479 |  |  |  |

### Hội đồng nhân dân - Địa chỉ: ấp 1, xã Long Công ang

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 12 | Phan Nhân Duy | Bí thư Đảng ủy - CT HĐND | 0979 123 999 |  |  |  |
| 13 | Nguyễn Ngọc Thọ | UV BTV - Phó CT HĐND |  |  |  |  |
| 14 | Nguyễn Thị Phương Anh | Phó Ban Kinh tế - Ngân sách - HĐND | 0988 474 396 |  |  |  |
| 15 | Nguyễn Ngọc Hoài Em | Phó Ban VHXH - HĐND | 0773 841 915 |  |  |  |

### UBND xã - ĐT bàn: 02723 883 629 ; email: ubndlongCông ang@tayninh.gov.vn

### Địa chỉ: ấp 1, xã Long Cang

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 16 | Đặng Văn Hải | Phó Bí thư - CT UBND | 0918 589 731 |  |  |  |
| 17 | Lê Hoàng Vũ | UV BTV - PCT UBND | 0909 124 039 |  |  |  |
| 18 | Nguyễn Khắc Hoàng Nguyên | UV BTV - PCT UBND | 0907 579 888 |  |  |  |
| 19 | Phạm Văn Tám Lùng | UV BCH - CVP HĐND và UBND | 0902 325 744 |  |  |  |
| 20 | Võ Thanh Vy | PCVP HĐND và UBND | 0937 520 350 |  |  |  |
| 21 | Nguyễn Trung Kiên | UV BCH - Trưởng phòng kinh tế | 0901 446 536 |  |  |  |
| 22 | Trương Minh Phục | PTP kinh tế | 0902 734 520 |  |  |  |
| 23 | Trương Thị Ngọc Hiền | UV BCH - TP Văn hóa - Xã hội | 0773 084 531 |  |  |  |
| 24 | Trần Tấn Hiệp | PTP Văn hóa - Xã hội | 0937 252 547 |  |  |  |
| 25 | Trần Duy Khanh | PGĐ TT Hành chính công | 0949 181 371 |  |  |  |
| 26 | Nguyễn Quang Cẩm Tú | PGĐ TT Cung ứng DVSN công | 0938 515 257 |  |  |  |
| 27 | Nguyễn Thị Ngọc Phương | UV BCH - Hiệu trưởng MG Long Công ang | 0986 662 719 |  |  |  |

### Công an Long Cang,- Địa chỉ: ấp 8, xã Long CAng

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 29 | Đặng Thanh Bình | UV BTV - Trưởng Công an | 0982 501 016 |  |  |  |
| 30 | Tạ Minh Mẫn | Phó trưởng Công an | 0937 678 961 |  |  |  |
| 31 | Đỗ Kỳ Quốc | Phó trưởng Công an | 0917 676 717 |  |  |  |
| 32 | Phan Thành Vinh | Phó trưởng Công an | 0909 979 353 |  |  |  |
| 33 | Phan Anh Hào | Phó trưởng Công an | 0978 454 693 |  |  |  |
| 34 | Lê Thành Đông | Phó trưởng Công an | 0918 199 597 |  |  |  |

### BCH Quân sự Long Cang - Địa chỉ: ấp 5, xã Long Cang

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 35 | Phạm Hoàng Linh | UV BTV - CHT BCH Quân sự | 0933 214 649 |  |  |  |
| 36 | Nguyễn Minh Dũng | UV BCH - PCHT BCH Quân sự | 0947 803 897 |  |  |  |

### XÃ RẠCH KIẾN

- Nhóm: 1
- Mã/STT nhóm: 55

### Đảng ủy Rạch Kiến- Địa chỉ: Ấp 3

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 1 | Nguyễn Văn Định | UV BTV Bí thư - CT HĐND | 0776 873 509 | 3880 156 |  |  |
| 2 | Nguyễn Thị Thanh Xuân | UV BTV Phó Bí thư | 0919 397 045 |  |  |  |
| 3 | Phạm Thị Kim Tuyền | UV BTV - CN UBKT | 0908 396 183 |  |  |  |
| 4 | Đào Hoàng Anh | UV BCH - PCN UBKT | 0906 188 887 |  |  |  |
| 5 | Nguyễn Thị Mai Hương | UV BTV - TB Xây dựng đảng | 0934 047 616 |  |  |  |
| 6 | Đào CHải | PTB Xây dựng đảng | 0937 817 632 |  |  |  |
| 7 | Nguyễn Chấn Quốc | PTB Xây dựng đảng | 0933 606 628 |  |  |  |
| 8 | Lữu Minh Hoàng | UV BCH - CVP Đảng ủy | 0916 962 065 |  |  |  |
| 9 | Phạm Thị Thanh Nhã | PCVP Đảng ủy | 0949 511 959 |  |  |  |
| 10 | Võ Thị Hồng Nhung | UV BTV - CT MTTQ xã | 0937 214 106 |  |  |  |
| 11 | Nguyễn Thị Ngọc Nhanh | UV BCH - PCT MTTQ, CT Hội PN | 0349 807 125 |  |  |  |
| 12 | Trần Minh Tiến | UV BCH - PCT MTTQ, CT Hội ND | 0937 722 468 |  |  |  |
| 13 | Nguyễn Thị Bạch Mai | UV BCH - PCT MTTQ, BT Đoàn TN | 0397 474 818 |  |  |  |
| 14 | Nguyễn Văn Hòa | UV BCH - PCT MTTQ, CT HCCB xã | 0762 345 454 |  |  |  |

### Hội đồng nhân dân - Địa chỉ: Ấp 8

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 15 | Nguyễn Thị Thùy Trang | UV BTV - PCT HĐND | 0942 199 456 | 3880 209 |  |  |
| 16 | Ngô Hoàng Phúc | UV BCH Ban Văn hóa - HĐND | 0987 706223 |  |  |  |
| 17 | Phạm Trọng Đăng Thu | UV BCH Ban Kinh tế - HĐND | 0904 748 912 |  |  |  |

### UBND xã Rạch Kiến - ĐT bàn: 0273 .... ; email: ubnd….@tayninh.gov.vn

### Địa chỉ: Ấp 8

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 18 | Đỗ Hồng Đăng | UV BTV Phó Bí thư - CT UBND | 0911 682 079 | 3880 209 |  |  |
| 19 | Nguyễn Minh Tân | UV BTV - PCT UBND | 0908 447 941 |  |  |  |
| 20 | Phan Văn Thành Xuyên | UV BCH - PCT UBND | 0909 281 613 |  |  |  |
| 21 | Bùi Ngọc Quân | UV BCH - CVP HĐND và UBND | 0937 762 987 |  |  |  |
| 22 | Nguyễn Thị Ngọc Yến | PCVP HĐND và UBND | 0903 089 732 |  |  |  |
| 23 | Huỳnh Tấn Cường | UV BCH - Trưởng phòng kinh tế | 0986 821 979 |  |  |  |
| 24 | Võ Hoàng Nam | PTP kinh tế | 0777 776 319 |  |  |  |
| 25 | Nguyễn Thị Nhỉ | UV BCH - TP Văn hóa - Xã hội | 0914 467 117 |  |  |  |
| 26 | Trần Kim Hường | PTP Văn hóa - Xã hội | 0366 288 200 |  |  |  |
| 27 | Lê Thị Tuyến | UV BCH - PGĐ TT Hành chính công | 0358 033 912 |  |  |  |
| 28 | Nguyễn Duy Khánh | PGĐ TT Cung ứng DVSN công | 0797 886 499 |  |  |  |

### Công an - Địa chỉ: Ấp Long Thanh

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 29 | Lê Văn Phương | UV BTV - Trưởng Công an | 0949 945 279 | 3722336 |  |  |
| 30 | Ngô Quốc Sơn | UV BCH - Phó trưởng Công an | 0973 857 575 |  |  |  |
| 31 | Nguyễn Minh Hùng | Phó trưởng Công an | 0909 075 646 |  |  |  |
| 32 | Nguyễn Văn Đúng | Phó trưởng Công an | 0979 776636 |  |  |  |
| 33 | Nguyễn Trương Thiện | Phó trưởng Công an | 0918 460 008 |  |  |  |
| 34 | Phan Chí Thanh | Phó trưởng Công an | 0933 752 788 |  |  |  |

### Quân sự - Địa chỉ: Ấp 4

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 35 | Huỳnh Văn Tựu | UV BTV - CHT BCH Quân sự | 0986 821 931 | 3722 335 |  |  |
| 36 | Nguyễn Văn Lượm | UV BCH - PCHT BCH Quân sự | 0979 657 620 |  |  |  |

### Xã Mỹ Lệ

- Nhóm: 1
- Mã/STT nhóm: 56

#### Đảng ủy xã Mỹ Lệ - Ấp Rạch Đào, xã Mỹ Lệ

- Điện thoại cơ quan: 02723.881 304

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 1 | Đào Hữu Tấn | Bí thư | 0938 275 272 |  |  |  |
| 2 | Nguyễn Thị Kim Cương | Phó Bí thư | 0909 769 804 |  |  |  |
| 3 | Trịnh Thị Kim Quyên | UV BTV - CN UBKT ĐU xã | 0933 242 034 |  |  |  |
| 4 | Hà Anh Kiệt | UV BCH - Phó CN UBKTĐU xã | 0933 417 118 |  |  |  |
| 5 | Võ Thành Ngon | UV BTV - TB Xây dựng đảng | 0976 157 947 |  |  |  |
| 6 | Nguyễn Minh Đức | UV BCH - PTB Xây dựng đảng | 0938 388 096 |  |  |  |
| 7 | Lê Tấn Đạt | UV BCH - CVP Đảng ủy xã | 0935 176 613 |  |  |  |
| 8 | Bùi Quốc Toàn | UV BTV - CT MTTQ xã | 0987 303 829 |  |  |  |
| 9 | Võ Thị Lan Hương | UV BCH - PCT MTTQ, CT Hội LHPN xã | 0908 621 567 |  |  |  |
| 10 | Nguyễn Thị Bạch Tuyết | UV BCH - PCT MTTQ, CT Hội nông dân xã | 0392 176 742 |  |  |  |
| 11 | Nguyễn Hữu Lộc | UV BCH - PCT MTTQ, BT Đoàn TN | 0933 628 260 |  |  |  |
| 12 | Phạm Tấn Khoa | UV BCH - PCT MTTQ, CT Hội cựu chiến binh | 0962 840 017 |  |  |  |

#### HĐND- UBND xã Mỹ Lệ - Đường tỉnh 830, ấp 10, xã Mỹ Lệ

- Điện thoại cơ quan: 02723 880 097

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 1 | Phan Văn Dũng | PCT HĐND | 0933 242 939 |  |  |  |
| 2 | Lê Thị Thu Thủy | PTB Văn hoá - Xã hội | 0933 878 505 |  |  |  |
| 3 | Nguyễn Thanh Nhàn | PTB Kinh tế - Ngân sách | 0833 755 778 |  |  |  |
| 4 | Trần Thanh Diệu | Phó Bí thư - Chủ tịch UBND | 0945 839 133 |  |  |  |
| 5 | Nguyễn Anh Tuấn | PCT UBND | 0938 019 182 |  |  |  |
| 6 | Nguyễn Phúc Trường | PCT UBND | 0918 756 864 |  |  |  |
| 7 | Ngô Hoàng Nguyễn | Chánh Văn phòng HĐND và UBND | 0985 312 422 |  |  |  |
| 8 | Đặng Bách Khoa | Phó Chánh Văn phòng HĐND và UBND | 0918 616 496 |  |  |  |
| 9 | Nguyễn Thành Trung | Trưởng Phòng Kinh tế | 0937 588 300 |  |  |  |
| 10 | Lê Thị Hạnh | Phó Trưởng Phòng Kinh tế | 0986 673 356 |  |  |  |
| 11 | Phạm Văn Huyên | Trưởng Phòng Văn hóa - Xã hội | 0933 242 442 |  |  |  |
| 12 | Lương Thành Sơn | Phó Trưởng Phòng Văn hóa - Xã hội | 0907 517 134 |  |  |  |
| 13 | Nguyễn Trọng Nhân | PGĐ TT PVHCC | 0934 268 278 |  |  |  |
| 14 | Nguyễn Đức Toàn | Giám đốc TT cung ứng DVSNC | 0976 724 747 |  |  |  |
| 15 | Trung tá Bùi Minh Dũng | Trưởng Công an | 0909133577 |  |  |  |
| 16 | Thiếu tá Phạm Thế Hiển | Phó Trưởng Công an | 0901911366 |  |  |  |
| 17 | Thiếu tá Nguyễn Hữu Danh | Phó Trưởng Công an | 0949639286 |  |  |  |
| 18 | Đại úy Võ Hoài Linh | Phó Trưởng Công an | 0937778070 |  |  |  |
| 19 | Trung tá Trần An Khương | Phó Trưởng Công an | 0768636863 |  |  |  |
| 20 | Thiếu tá Lê Minh Lộc | Phó Trưởng Công an | 0938026999 |  |  |  |
| 21 | Lê Bảo Duy | CHT Ban chỉ huy Quân sự | 0963431422 |  |  |  |
| 22 | Lê Long Hồ | Phó CHT Ban chỉ huy Quân sự | 0933623407 |  |  |  |
| 23 | Nguyễn Thanh Ghi | Tợ lý Ban chỉ huy Quân sự | 0924981456 |  |  |  |
| 24 | Cổ Thị Thiên Nga | Trưởng Trạm Y tế xã | 0368818242 |  |  |  |
| 25 | Võ Thị Diệu My | Phó trưởng Trạm y tế | 0937962766 |  |  |  |

### XÃ TÂN LÂN

- Nhóm: 1
- Mã/STT nhóm: 57

### QL 50, ấp 3, xã Tân Lân

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 1 | Trần Quốc Quân | Bí thư Đảng ủy | 0917 397 307 | 02723 881 385 |  |  |
| 2 | Huỳnh Thị Kim Chi | Phó Bí thư TT ĐU - CT HĐND | 0976 422 231 | 02723 881 385 |  | QL 50, ấp 3, xã Tân Lân |
| 3 | Lê Thị Hồng Thắm | Phó Bí thư ĐU - CT UBND | 0356 056 030 | 02723 881 031 |  | QL 50 ấp Nhà Thờ, xã Tân Lân |
| 4 | Nguyễn Minh Hoàng | UV BTV - PCT HĐND | 0977 553 832 | 02723 881 031 |  | QL 50, ấp 3, xã Tân Lân |
| 5 | Đặng Vũ Khánh | UV BTV - TB xây dựng Đảng | 0909 685 791 | 02723 881 385 |  | QL 50, ấp 3, xã Tân Lân |
| 6 | Huỳnh Thanh Phong | UV BTV - CN UBKT ĐU- TB kinh tế HĐND | 0908 690 022 | 02723 881 385 |  | QL 50, ấp 3, xã Tân Lân |
| 7 | Phan Thị Hồng Diễm | UV BTV - CT.UBMTTQ Việt Nam | 0937 428 255 | 02723 881 385 |  | QL 50, ấp 3, xã Tân Lân |
| 8 | Lê Phước Chinh | UV BTV - Trưởng Công an | 0907 208 183 | 02723 882 031 |  | 89 QL 50 ấp Nhà Thờ, xã Tân Lân |
| 9 | Nguyễn Đăng Khoa | UV BTV - CHT BCH Quân sự | 0986 923 753 | 02723 881 767 |  | QL 50, ấp 3, xã Tân Lân |
| 10 | Hồ Hoàng Hưng | UVBCH - PCT UBND | 0938 859 530 | 02723 881 031 |  | QL 50 ấp Nhà Thờ, xã Tân Lân |
| 11 | Võ Nguyên Chí | UVBCH - PCT UBND | 0933 323 208 | 02723 881 031 |  | QL 50 ấp Nhà Thờ, xã Tân Lân |
| 12 | Trần Thị Mỹ Duyên | UVBCH - Phó trưởng Công an | 0977 553 832 | 02723 881 031 |  | 89 QL 50 ấp Nhà Thờ, xã Tân Lân |
| 13 | Võ Thanh Tâm | UVBCH - Phó CHT BCH Quân sự | 0906 678 586 | 02723 881 767 |  | QL 50, ấp 3, xã Tân Lân |
| 14 | Hồ Trà Vĩnh Phát | UVBCH - Trưởng Phòng Kinh tế | 0908 300 079 | 02723 881 031 |  | QL 50 ấp Nhà Thờ, xã Tân Lân |
| 15 | Phạm Quốc Khải | UVBCH - Trưởng phòng Văn hóa - Xã hội | 0903 380 218 | 02723 881 031 |  | QL 50 ấp Nhà Thờ, xã Tân Lân |
| 16 | Nguyễn Ngọc Minh | UVBCH - CVP Đảng ủy | 0979 234 560 | 02723 881 385 |  | QL 50, ấp 3, xã Tân Lân |
| 17 | Nguyễn Đăng Vinh | UVBCH - CVP HĐND và UBND | 0933 894 678 | 02723 881 031 |  | QL 50 ấp Nhà Thờ, xã Tân Lân |
| 18 | Nguyễn Duy Khanh | UVBCH - PCN UBKT ĐU | 0935 049 239 | 02723 881 385 |  | QL 50, ấp 3, xã Tân Lân |
| 19 | Nguyễn Thanh Tùng | UVBCH - PTB xây dựng đảng | 0902 408 737 | 02723 881 385 |  | QL 50, ấp 3, xã Tân Lân |
| 20 | Nguyễn Thanh Vân | UVBCH - PTB kinh tế - Ngân sách HĐND | 0378 219 419 | 02723 881 385 |  | QL 50, ấp 3, xã Tân Lân |
| 21 | Huỳnh Thị Kim Lộc | UVBCH - PCT UBMTTQ - CT Hội PN | 0914 304 218 | 02723 881 385 |  | QL 50, ấp 3, xã Tân Lân |
| 22 | Phan Tố Như | UVBCH - PCT UBMTTQ - BT Đoàn TN | 0812 727 687 | 02723 881 385 |  | QL 50, ấp 3, xã Tân Lân |
| 23 | Tạ Thanh Dũng | UVBCH - PCT UBMTTQ - CT Hội ND | 0933 818 466 | 02723 881 385 |  | QL 50, ấp 3, xã Tân Lân |
| 24 | Nguyễn Xuân Phương | UVBCH - PCT UBMTTQ - CT Hội CCB | 0328 132 839 | 02723 881 385 |  | QL 50, ấp 3, xã Tân Lân |
| 25 | Nguyễn Minh Sơn | PTP Văn hóa - Xã hội | 0909 478 335 | 02723 881 031 |  | QL 50 ấp Nhà Thờ, xã Tân Lân |
| 26 | Nguyễn Minh Hiếu | Phó GĐ TT hành chính công | 0905 164 271 | 02723 881 031 |  | QL 50 ấp Nhà Thờ, xã Tân Lân |
| 27 | Phan Thành Minh | GĐ TT cung ứng DV sự nghiệp công | 0909 753 508 | 02723 881 031 |  | QL 50 ấp Nhà Thờ, xã Tân Lân |
| 28 | Nguyễn Văn Minh | PTP Kinh tế | 0976 000 211 | 02723 881 031 |  | QL 50 ấp Nhà Thờ, xã Tân Lân |
| 29 | Lê Thị Hồng Thúy | Phó CVP HĐND và UBND | 0934 950 936 | 02723 881 031 |  | QL 50 ấp Nhà Thờ, xã Tân Lân |
| 30 | Nguyễn Thành Nam | PTB xây dựng đảng | 0902 719 238 | 02723 881 385 |  | QL 50, ấp 3, xã Tân Lân |
| 31 | Nguyễn Thị Ánh Hồng | Phó CVP Đảng ủy | 0914 390 108 | 02723 881 385 |  | QL 50, ấp 3, xã Tân Lân |

### XÃ LONG HỰU

- Nhóm: 1
- Mã/STT nhóm: 58

### Đảng ủy xã Long Hựu - Địa chỉ: ấp Tây, xã Long Hựu

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 1 | Nguyễn Minh Vương | Bí thư - Chủ tịch HĐND | 912376467 |  |  |  |
| 2 | Nguyễn Hữu Đức | Phó Bí thư | 902462265 |  |  |  |
| 3 | Đỗ Hồng Thanh | UV BTV - Chủ nhiệm UBKT ĐU xã | 933931811 |  |  |  |
| 4 | Nguyễn Hữu Ơn | UV BCH - Phó Chủ nhiệm UBKTĐU xã | 909373375 |  |  |  |
| 5 | Trần Quốc Mạnh | UV BTV - TB Xây dựng đảng | 907873009 |  |  |  |
| 6 | Nguyễn Tuấn Nhã | UV BCH - PTB Xây dựng đảng | 933401400 |  |  |  |
| 7 | Đặng Kim Quyên | UV BCH - CVP Đảng ủy xã | 823535885 |  |  |  |
| 8 | Nguyễn Đăng Khoa | UV BTV - CT MTTQ xã | 908771878 |  |  |  |
| 9 | Trần Thị Trinh | UV BCH - PCT MTTQ, CT Hội LHPN xã | 333997287 |  |  |  |
| 10 | Lê Đức Minh | UV BCH - PCT MTTQ, CT Hội nông dân xã | 902380348 |  |  |  |
| 11 | Trần Tuấn Kiệt | UV BCH - PCT MTTQ, BT Đoàn TN | 333316163 |  |  |  |
| 12 | Lê Văn Mến | UV BCH - PCT MTTQ, CT HCCB | 937627030 |  |  |  |

### Hội đồng nhân dân xã Long Hựu - Địa chỉ: ấp Cầu Ngang, xã Long Hựu

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 13 | Nguyễn Văn Khắc | UV BTV - PCT HĐND | 972699603 |  |  |  |
| 14 | Trần Thị Kim Hồng | Phó Ban Kinh tế - HĐND | 388965237 |  |  |  |
| 15 | Phạm Văn Hai | Phó Ban VHXH - HĐND | 984445614 |  |  |  |

### UBND xã - ĐT bàn:02723884012 ; email: ubndlonghuu@tayninh.gov.vn

### Địa chỉ: ấp Cầu Ngang, xã Long Hựu

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 16 | Phạm Ngọc Mai | Phó Bí thư - CT UBND | 984445614 |  |  |  |
| 17 | Huỳnh Phương Khắc Vũ | UV BCH - PCT UBND | 937836979 |  |  |  |
| 18 | Trần Thị Đăng Thuy | UV BCH - PCT UBND | 942123094 |  |  |  |
| 19 | Nguyễn Thị Bé Quyên | UV BCH - CVP HĐND và UBND xã | 384309346 |  |  |  |
| 20 | Lê Hoàng Thiện | PCVP HĐND và UBND xã | 982406107 |  |  |  |
| 21 | Nguyễn Thanh Tùng | UV BCH - Trưởng phòng kinh tế xã | 763336465 |  |  |  |
| 22 | Võ Anh Tuấn | Phó Trưởng phòng kinh tế xã | 977750017 |  |  |  |
| 23 | Nguyễn Thị Bích Vân | TP Văn hóa - Xã hội | 909671072 |  |  |  |
| 24 | Đặng Thanh Hòa | PTP Văn hóa - Xã hội | 971725139 |  |  |  |
| 25 | Nguyễn Nhựt Luân | PGĐ TT Hành chính công | 938657613 |  |  |  |
| 26 | Nguyễn Nhựt Á | PGĐ TT Cung ứng DVSN công | 902658999 |  |  |  |
| 27 | Nguyễn Gia Thái | UV BTV - Trưởng Công an | 909005032 |  |  |  |
| 28 | Nguyễn Trung Hiếu | UV BCH - Phó Trưởng Công an | 939276769 |  |  |  |
| 29 | Bùi Thanh Hưng | Phó Trưởng Công an | 979152636 |  |  |  |
| 30 | Phan Thanh Tú | Phó Trưởng Công an | 939226373 |  |  |  |
| 31 | Bùi Hoàng Thạch | Phó Trưởng Công an | 963096407 |  |  |  |
| 32 | Trương Minh Thắm | Phó Trưởng Công an | 932049919 |  |  |  |
| 33 | Bùi Thanh Sơn | UV BTV - CHT BCH Quân sự | 938592367 |  |  |  |
| 34 | Nguyễn Văn Toàn | UV BCH - PCHT BCH Quân sự | 775539519 |  |  |  |

### XÃ CẦN GIUỘC

- Nhóm: 1
- Mã/STT nhóm: 59

### Đảng ủy Cần Giuộc - Địa chỉ: Đường tránh QL 50, ấp Thanh Ba, xã Cần Giuộc

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 1 | Phạm Văn Bốn | TUV, Bí thư ĐU xã | 0976 280 779 |  |  |  |
| 2 | Võ Quốc Thanh | Phó BT Thường trực, CT HĐND | 0902 622 113 |  |  |  |
| 3 | Nguyễn Thị Phượng Loan | UV BTV ĐU, CN UBKT ĐU | 0857 722 866 |  |  |  |
| 4 | Nguyễn Thị Ngọc Thảo | ĐUV, PCN UBKT ĐU | 0907 691 445 |  |  |  |
| 5 | Nguyễn CDanh | UV BTV ĐU, Tb Xây dựng đảng | 0937 288 511 |  |  |  |
| 6 | Đặng Thị Cẩm Hồng | ĐUV, PTB Xây dựng đảng (phụ trách Tổ chức) | 0985 349 325 |  |  |  |
| 7 | Hồ Minh Trung | PTB Xây dựng đảng (phụ trách TG-DV) | 0909 781 710 |  |  |  |
| 8 | Trần Lâm Việt Trung | ĐUV, Chánh VP Đảng ủy | 0908 909 267 |  |  |  |
| 9 | Nguyễn Thị Hồng Châu | Phó Chánh VP Đảng ủy | 0934 183 167 |  |  |  |
| 10 | Nguyễn Thanh Lộc | ĐUV, Chủ tịch UB.MTTQ VN | 0906 913 113 |  |  |  |
| 11 | Dương Bích Cảm | ĐUV, PCT MTTQ - CT Hội PN | 0983 406 846 |  |  |  |
| 12 | Trần Minh Lý | ĐUV, PCT MTTQ - CT Hội ND | 0933 492 272 |  |  |  |
| 13 | Võ Thị Ngọc Kiều | ĐUV, PCT MTTQ BT Đoàn TN | 0366 961 716 |  |  |  |
| 14 | Tô Ngọc Lợi | ĐUV, PCT MTTQ - CT Hội CCB | 0902 678 720 |  |  |  |

### Hội đồng nhân dân xã - Địa chỉ: số 255 Nguyễn Thái Bình, ấp 4, xã Cần Giuộc

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 15 | Huỳnh Văn Trí | UV BTV ĐU, PCT HĐND | 0826 738 980 |  |  |  |
| 16 | Nguyễn Thị Hiền | ĐUV, PTB Kinh tế - Ngân sách | 0777 620 896 |  |  |  |
| 17 | Phạm Văn Tấn | ĐUV, PTB Văn hoá - Xã hội | 0933 878 490 |  |  |  |

### Ủy ban nhân dân xã

### ĐT bàn: 02723 2212 712; email: Công angiuoc@tayninh.gov.vn

### Địa chỉ: số 255 Nguyễn Thái Bình, ấp 4, xã Cần Giuộc

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 18 | Nguyễn Ngọc Anh | Phó BT, Chủ tịch UBND | 0909 636 545 |  |  |  |
| 19 | Võ Hữu Phước | UV BTV ĐU, Phó CT UBND / kiêm GĐ TTHCC | 0941 884 777 |  |  |  |
| 20 | Trần Võ Trí Nhân | ĐUV, Phó CT UBND | 0908 646 597 |  |  |  |
| 21 | Trương Trường Thọ | ĐUV, Chánh VP HĐND và UBND | 0938 718 470 |  |  |  |
| 22 | Nguyễn Minh Khoa | ĐUV, Trưởng Phòng Kinh tế | 0933 921 738 |  |  |  |
| 23 | Võ Hoàng Phong | PTP Kinh tế | 0855 401 064 |  |  |  |
| 24 | Võ Thị Lan Đài | ĐUV, Trưởng phòng Văn hóa - Xã hội | 0933 586 427 |  |  |  |
| 25 | Lê Thanh Vũ | PTP Văn hóa - Xã hội | 0933 892 511 |  |  |  |
| 26 | Ngô Thị Két | ĐUV, PGĐ TT Hành chính công | 0914 142 134 |  |  |  |
| 27 | Nguyễn Trọng Tài | ĐUV, GĐ TT cung ứng DVSNC | 0916 071 617 |  |  |  |
| 28 | Võ Tấn Khôi | PGĐ TT Cung ứng DVSN công |  |  |  |  |

### Công an / Địa chỉ: số 246 Nguyễn Thái Bình, ấp Hòa Thuận 1, xã Cần Giuộc

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 29 | Nguyễn Văn Được | UV BTV ĐU, Trưởng Công an | 0988 933 944 |  |  |  |
| 30 | Huỳnh Văn Chính | Phó Trưởng Công an | 0937 133 979 |  |  |  |
| 31 | Lê Tấn Nghĩa | Phó Trưởng Công an | 0907 802 777 |  |  |  |
| 32 | Ngô Tấn Phong | Phó Trưởng Công an | 0903 684 907 |  |  |  |
| 33 | Nguyễn Đức Khánh | Phó Trưởng Công an | 0916 707 247 |  |  |  |
| 34 | Nguyễn Nhật Linh | Phó Trưởng Công an | 0919 141 279 |  |  |  |

### BCH Quân sự / Địa chỉ: QL50, ấp Trị Yên, xã Cần Giuộc

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 35 | Đặng Minh Thiện | UV BTV ĐU, CHT BCH QS | 0889 220 811 |  |  |  |
| 36 | Ngô Thanh Hải | Phó CHT BCH QS | 0908 226 243 |  |  |  |

### Xã Phước Lý

- Nhóm: 1
- Mã/STT nhóm: 60

#### Địa chỉ: Số 795, đường tỉnh 835B, xã Phước Lý

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 1 | Nguyễn Hoàng Lâm | Bí thư Đảng ủy - Chủ tịch HĐND | 0908 415 484 |  |  | Số 795, đường tỉnh 835B, xã Phước Lý |
| 2 | Nguyễn Thị Thanh Tuyền | Phó Bí thư Đảng ủy | 0944 114 669 |  |  | Số 795, đường tỉnh 835B, xã Phước Lý |
| 3 | Đỗ Hiếu Trung | Phó Bí thư Đảng ủy - Chủ tịch UBND xã | 0938 218 349 | 02723 892 033 |  | Số 795, đường tỉnh 835B, xã Phước Lý |
| 4 | Nguyễn Minh Tâm | UVTV - PCT UBND xã | 0979 324 341 | 02723 892 033 |  | Số 795, đường tỉnh 835B, xã Phước Lý |
| 5 | Đặng Phước Hảo | UVTV - TB xây dựng Đảng Đảng ủy | 0768 168 943 |  |  | Số 795, đường tỉnh 835B, xã Phước Lý |
| 6 | Huỳnh Thị Tuyết Hồng | UVTV - CN UBKT Đảng ủy | 0792 243 261 |  |  | Số….., đường tỉnh 835B, xã Phước Lý |
| 7 | Nguyễn Thị Ngọc Duyên | UVTV - Chủ tịch MTTQ xã | 0911 475 999 |  |  | Số….., đường tỉnh 835B, xã Phước Lý |
| 8 | Nguyễn Dương Hải | UVTV - Trưởng Công an | 0988 934 936 | 02723 734 845 |  | Số 168, đường tỉnh 835B, xã Phước Lý |
| 9 | Lê Minh Thiện | UVTV - CHT BCH Quân sự | 0933 170 020 | 02723 734 844 |  | Số….., đường tỉnh 835B, xã Phước Lý |
| 10 | Phạm Minh Trung | ĐUV - PCT HĐND | 0777 105 524 |  |  | Số 795, đường tỉnh 835B, xã Phước Lý |
| 11 | Nguyễn Minh Vương | ĐUV - PCT UBND xã | 0933 248 245 | 02723 892 033 |  | Số 795, đường tỉnh 835B, xã Phước Lý |
| 12 | Võ Thị Hồng Phương | ĐUV - PTB Xây dựng Đảng Đảng ủy | 0913 058 512 |  |  | Số 795, đường tỉnh 835B, xã Phước Lý |
| 13 | Trần CDũng | ĐUV - PCN UBKT Đảng ủy | 0909 213 833 |  |  | Số…., đường tỉnh 835B, xã Phước Lý |
| 14 | Đoàn Thị Ngọc Diệp | ĐUV - PTB Văn hóa - Xã hội | 0938 584 147 |  |  | Số 795, đường tỉnh 835B, xã Phước Lý |
| 15 | Đặng Thị Kim Thoa | ĐUV - PTB Kinh tế - Ngân sách xã | 0937 901 545 |  |  | Số 795, đường tỉnh 835B, xã Phước Lý |
| 16 | Đoàn Quốc Thông | ĐUV - CVP Đảng ủy | 0938 668 737 |  |  | Số 795, đường tỉnh 835B, xã Phước Lý |
| 17 | Trần Minh Luân | ĐUV - CVP HĐND và UBND | 0918 888 734 | 02723 892 033 |  | Số 795, đường tỉnh 835B, xã Phước Lý |
| 18 | Nguyễn Thị Mộng Thu | ĐUV - Trưởng Phòng Văn hóa - Xã hội | 0934 290 404 |  |  | Số 795, đường tỉnh 835B, xã Phước Lý |
| 19 | Đỗ Cao Bình | ĐUV - Trưởng phòng kinh tế | 0902 385 150 |  |  | Số 795, đường tỉnh 835B, xã Phước Lý |
| 20 | Trần Tấn Giang | ĐUV - Phó GĐ TT PV hành chính cxã | 0933 039 899 |  |  | Số 795, đường tỉnh 835B, xã Phước Lý |
| 21 | Trần Tuấn Thanh | ĐUV - GĐ TT CU DV sự nghiệp công | 0904 176 735 |  |  | Số 168, đường tỉnh 835B, xã Phước Lý |
| 22 | Đặng Minh Tín | ĐUV - Phó trưởng Công an | 0908 189 496 | 02723 734 845 |  | Số 168, đường tỉnh 835B, xã Phước Lý |
| 23 | Lê Thanh Tú | ĐUV - Phó CHT Ban Chỉ huy Quân sự | 0904 761 015 | 02723 734 844 |  | Số….., đường tỉnh 835B, xã Phước Lý |
| 24 | Lại Hoàng Nam | ĐUV - PCT MTTQ xã | 0399 732 270 |  |  | Số….., đường tỉnh 835B, xã Phước Lý |
| 25 | Võ Thị Thùy Dương | ĐUV - PCT MTTQ xã | 0777947581 |  |  | Số….., đường tỉnh 835B, xã Phước Lý |
| 26 | Đoàn Thanh Phong | ĐUV - PCT MTTQ xã | 0774 672 747 |  |  | Số….., đường tỉnh 835B, xã Phước Lý |
| 27 | Trần Văn Xuân | ĐUV - PCT MTTQ xã | 0906 504 001 |  |  | Số….., đường tỉnh 835B, xã Phước Lý |
| 28 | Mai Hồng Phong | PTB Xây dựng Đảng Đảng ủy | 0987 235 177 |  |  | Số 795, đường tỉnh 835B, xã Phước Lý |
| 29 | Trần Thị Kim Tuyến | Phó CVP Đảng ủy | 0979 928 363 |  |  | Số 795, đường tỉnh 835B, xã Phước Lý |
| 30 | Phan Bảo Minh | PCVP HĐND và UBND | 0912 409 609 | 02723 892 033 |  | Số 795, đường tỉnh 835B, xã Phước Lý |
| 31 | Phạm Xuân Dũng | PTP kinh tế | 0937 290 704 |  |  | Số 795, đường tỉnh 835B, xã Phước Lý |
| 32 | Nguyễn Thị Lệ Trinh | PTP Văn hóa - Xã hội | 0386 813 609 |  |  | Số 795, đường tỉnh 835B, xã Phước Lý |
| 33 | Lê Hoàng Thơ | PGĐ TT Cung ứng DV sự nghiệp cxã | 0356 174 675 |  |  | Số 168, đường tỉnh 835B, xã Phước Lý |

### XÃ MỸ LỘC

- Nhóm: 1
- Mã/STT nhóm: 61

#### Địa chỉ: ĐT.835 xã Mỹ Lộc

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 1 | Nguyễn Phước Hùng | Bí thư | 0932 634 777 |  |  | ĐT.835 xã Mỹ Lộc |
| 2 | Trương Thị Phượng Quyên | Phó Bí thư thường trực | 0983 248 349 |  |  | ĐT.835 xã Mỹ Lộc |
| 3 | Trương Như Phong | CVP Đảng ủy | 0976339333 |  |  | ĐT.835 xã Mỹ Lộc |
| 4 | Nguyễn Anh Vũ | Phó CVP Đảng ủy | 0932823863 |  |  | ĐT.835 xã Mỹ Lộc |
| 5 | Nguyễn Tấn Phục | TB xây dựng Đảng | 0907916745 |  |  | ĐT.835 xã Mỹ Lộc |
| 6 | Nguyễn Thị Thúy Ngân | PTB xây dựng Đảng | 0767894004 |  |  | ĐT.835 xã Mỹ Lộc |
| 7 | Nguyễn Thị Thùy Vân | PTB xây dựng Đảng | 0937681361 |  |  | ĐT.835 xã Mỹ Lộc |
| 8 | Trần Thanh Quang | CN UBKT ĐU | 0907302843 |  |  | ĐT.835 xã Mỹ Lộc |
| 9 | Ngô Minh Tùng | PCN UBKT ĐU | 0707043999 |  |  | ĐT.835 xã Mỹ Lộc |
| 10 | Trần Ngọc Thùy Dương | CT UB. MTTQVN xã | 0938656128 |  |  | ĐH.19 xã Mỹ Lộc |
| 11 | Trần Thị Hồng Thủy | PCT UB.MTTQVN xã - Phụ trách Thanh niên | 0975044415 |  |  | ĐH.19 xã Mỹ Lộc |
| 12 | Võ Ngọc Huyền | PCT UB.MTTQVN xã - Phụ trách Phụ nữ | 0945667849 |  |  | ĐH.19 xã Mỹ Lộc |
| 13 | Đặng Tấn Cường | PCT UB.MTTQVN xã - Phụ trách Hội CCB | 0938848333 |  |  | ĐH.19 xã Mỹ Lộc |
| 14 | Lê Hoài Nam | PCT UB.MTTQVN xã - Phụ trách Ndân | 0932856784 |  |  | ĐH.19 xã Mỹ Lộc |
| 15 | Nguyễn Thị Xuân Thanh | PCT HĐND | 0832678162 |  |  | ĐT.835 xã Mỹ Lộc |
| 16 | Trương Hoàng Tân | PTB KT-XH | 0768895639 |  |  | ĐT.835 xã Mỹ Lộc |
| 17 | Nguyễn Thị Thúy Quyên | PTB Pháp chế | 0937431287 |  |  | ĐT.835 xã Mỹ Lộc |
| 18 | Trần Văn Ngọc Sinh | CT. UBND | 0909337223 | 02723737921 |  | ĐT.835 xã Mỹ Lộc |
| 19 | Bạch Phạm Minh Huy | Phó CT. UBND - KT | 0982787890 |  |  | ĐT.835 xã Mỹ Lộc |
| 20 | Phạm Minh Tuấn | Phó CT. UBND - VHXH | 0917122177 |  |  | ĐT.835 xã Mỹ Lộc |
| 21 | Nguyễn Trần Minh Quân | CVP HĐND và UBND | 0906091569 |  |  | ĐT.835 xã Mỹ Lộc |
| 22 | Nguyễn Thị Bích Liễu | Phó CVP HĐND và UBND | 0937379605 |  |  | ĐT.835 xã Mỹ Lộc |
| 23 | Phạm Hồng Ngọc | Trưởng Phòng Kinh tế | 0908784997 |  |  | ĐT.835 xã Mỹ Lộc |
| 24 | Nguyễn Trường Tân | PTP Kinh tế | 0908994966 |  |  | ĐT.835 xã Mỹ Lộc |
| 25 | Mai Tuấn Đạt | Trưởng Phòng Văn hóa - Xã hội | 0909923485 |  |  | ĐT.835 xã Mỹ Lộc |
| 26 | Lê Thị Mộng Cầm | PTP Văn hóa - Xã hội | 0797745456 |  |  | ĐT.835 xã Mỹ Lộc |
| 27 | Đặng Thị Mỹ Phương | PGĐ TT PV HCC | 0776232384 | 02723737921 |  | ĐT.835 xã Mỹ Lộc |
| 28 | Võ Minh Thận | Trưởng Công an | 0914403986 | 02723737639 |  | ĐH.20 xã Mỹ Lộc |
| 29 | Nguyễn Nhật Trường Huy | Chỉ huy TB chỉ huy Quân sự | 0794866154 | 02723738989 |  | ĐH.19 xã Mỹ Lộc |

### XÃ PHƯỚC VĨNH TÂY

- Nhóm: 1
- Mã/STT nhóm: 62

### Đảng ủy, các Ban đảng

### Địa chỉ: ấp Tây Phú, xã Phước Vĩnh Tây

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 1 | Huỳnh Minh Trí | Bí thư Đảng ủy xã | 0932 799 111 |  |  |  |
| 2 | Ngô Bảo Quốc | Phó Bí thư Thường trưc Đảng ủy xã | 0933 781 438 |  |  |  |
| 3 | Ngô Minh Trọng | UV BTV - CN UBKT ĐU xã | 0907 638 808 |  |  |  |
| 4 | Lâm Phú Quí | UV BCH - Phó CN UBKTĐU xã | 0902 483 628 |  |  |  |
| 5 | Đỗ Thị Thảo Phương | UV BTV - TB Xây dựng đảng xã | 0933 508 933 |  |  |  |
| 6 | Huỳnh Thị Trúc Loan | UV BCH - PTB Xây dựng đảng xã | 0938 452 353 |  |  |  |
| 7 | Đặng Hoa Bướm | UV BCH - CVP Đảng ủy xã | 0377 621 197 |  |  |  |
| 8 | Nguyễn Trần Xuân Thanh | UV BCH - CT MTTQ xã | 0914 040 814 |  |  |  |
| 9 | Hồ Thị Cúc | UV BCH - PCT MTTQVN, CT Hội LHPN xã | 0908 679 092 |  |  |  |
| 10 | Tô Hồng Nguyên | UV BCH - PCT MTTQVN, CT Hội Nông dân xã | 0919 655 443 |  |  |  |
| 11 | Phạm Duy Phương | UV BCH - PCT MTTQVN, BT Đoàn TN | 0975 547 285 |  |  |  |
| 12 | Trần Hoài Hận | UV BCH - PCT MTTQVN, CT Hội CCB | 0937 581 421 |  |  |  |

### HĐND xã Phước Vĩnh Tây

### Địa chỉ: ấp Tây Phú, xã Phước Vĩnh Tây

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 13 | Huỳnh Minh Trí | Bí thư Đảng ủy- CT HĐND | 0932 799 111 |  |  |  |
| 14 | Trương Thị Tuyết Nhung | UV BTV - PCT HĐND | 0906 849 727 |  |  |  |
| 15 | Ngô Minh Trọng | Ban Kinh tế - HĐND | 0907 638 808 |  |  |  |
| 16 | Đỗ Thị Thảo Phương | Ban VHXH - HĐND | 0933 508 933 |  |  |  |

### UBND xã - ĐT bàn: 02723876034 ; email: ubndphuocvinhtay@tayninh.gov.vn

### Địa chỉ: ấp Tây Phú, xã Phước Vĩnh Tây

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 17 | Phạm Tấn Lợi | Phó Bí thư Đảng ủy - CT UBND xã | 0902 904 141 |  |  |  |
| 18 | Lê Thị Phương Dung | UV BTV - PCT UBND xã | 0979 831 525 |  |  |  |
| 19 | Võ Phú Quốc | UV BCH - PCT UBND xã | 0983 525 091 |  |  |  |
| 20 | Lê Thanh Thuận | UV BCH - CVP HĐND và UBND xã | 0938 589 774 |  |  |  |
| 21 | Lưu Thanh Tùng | PCVP HĐND và UBND xã | 0339 509 545 |  |  |  |
| 22 | Nguyễn Hồng Tuấn | UV BCH - Trưởng phòng kinh tế xã | 0911 797 887 |  |  |  |
| 23 | Nguyễn Vũ Minh Hùng | Phó Trưởng phòng kinh tế xã | 0931 269 790 |  |  |  |
| 24 | Phùng Cẩm Loan | UV BCH - TP Văn hóa - Xã hội | 0913 828 612 |  |  |  |
| 25 | Nguyễn Ngọc Huy | PTP Văn hóa - Xã hội | 0947 351 329 |  |  |  |
| 26 | Võ Phú Quốc | GĐ TT Phục vụ Hành chính công xã | 0983 525 091 |  |  |  |
| 27 | Huỳnh Quang Lộc | PGĐ TT Phục vụ Hành chính công xã | 0907 673 915 |  |  |  |
| 28 | Phạm Quốc Tuấn | GĐ TT Cung ứng DVSN công xã | 0979 707 375 |  |  |  |
| 29 | Lê Thị Phương Thảo | PGĐ TT Cung ứng DVSN công xã | 0944 925 969 |  |  |  |
| 30 | Võ Nguyễn Anh Khoa | UV BTV - Trưởng Công an | 0964 456 868 |  |  |  |
| 31 | Lê Quang Vinh | UV BCH - Phó Trưởng Công an | 0855 989 739 |  |  |  |
| 32 | Trần Minh Phụng | Phó trưởng Công an | 0982 279 293 |  |  |  |
| 33 | Nguyễn Ngọc Tuyến | Phó trưởng Công an | 0903 390 238 |  |  |  |
| 34 | Nguyễn Thị Lệ Oanh | Phó trưởng Công an | 0918 213 712 |  |  |  |
| 35 | Nguyễn Lê Đình Duy | Phó trưởng Công an | 0918 659 609 |  |  |  |
| 36 | Trần Hoàng Tâm | UV BTV - CHT BCH Quân sự | 0969 382 183 |  |  |  |
| 37 | Trần Phan Minh Thi | UV BCH - PCHT BCH Quân sự | 0979 377 154 |  |  |  |

### XÃ TÂN TẬP

- Nhóm: 1
- Mã/STT nhóm: 63

### Đảng ủy Tân Tập - Địa chỉ: ĐT.830, xã Tân Tập

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 1 | Trần Thanh Phong | Bí thư đảng ủy - CT. HĐND | 0907 768 777 |  |  |  |
| 2 | Lê Thị Thanh Tú | Phó Bí thư thường trực Đảng ủy | 0934 081 299 |  |  |  |
| 3 | Trần Phan Minh Tiến | UV BTV - CN UBKT | 0945 472 508 |  |  |  |
| 4 | Võ Quốc Cường | UV BCH - PCN UBKT | 0903 371 547 |  |  |  |
| 5 | Nguyễn Văn Thạnh | UV BTV - TB Xây dựng đảng | 0938 350 809 |  |  |  |
| 6 | Nguyễn Ngọc Chuẩn | UV BCH - PTB Xây dựng đảng | 0938 860 783 |  |  |  |
| 7 | Đặng Thị Hải Yến | UV BCH - CVP Đảng ủy | 0937 657 949 |  |  |  |
| 8 | Võ Thị Ngọc Hương | PCVP Đảng ủy | 0902 541 920 |  |  |  |
| 9 | Tô Thị Kim Thoa | UV BCH - CT. UBMTTQ xã | 0979 991 664 |  |  |  |
| 10 | Võ Thị Như Thảo | UV BCH - PCT. UBMTTQ, CT Hội PN | 0914 200 607 |  |  |  |
| 11 | Trần Văn Thuấn | UV BCH - PCT. UBMTTQ, CT Hội ND | 0342 759 996 |  |  |  |
| 12 | Phan Thị Kiều My | UV BCH - PCT. UBMTTQ, BT Đoàn TN | 0969 938 578 |  |  |  |
| 13 | Nguyễn Tấn Thành | UV BCH - PCT. UBMTTQ, CT Hội CCB | 0364 949 804 |  |  |  |

### HĐND Tân Tập - Địa chỉ: ĐT.830, xã Tân Tập

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 14 | Nguyễn Thanh Tú | UV BCH - PCT HĐND | 0982 619 281 |  |  |  |
| 15 | Nguyễn Thị Trúc Phương | UV BCH - Ban Kinh tế - HĐND | 0984 991 289 |  |  |  |
| 16 | Lê Thị Hồng Nhung | UV BCH - Ban VHXH - HĐND | 0938 851 717 |  |  |  |

### UBND xã Tân Tập - Địa chỉ: ĐT.830, xã Tân Tập

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 17 | Nguyễn Hoài Thanh | Phó Bí thư Đảng ủy - CT. UBND | 0948 731 773 | 876 026 |  |  |
| 18 | Nguyễn Hoàng Xuân Vũ | UV. BTV - PCT. UBND | 0939 095 918 |  |  |  |
| 19 | Trần Thị Mai Xuân | UV. BTV - PCT. UBND - GĐ TT Hành chính công | 0933 227 914 |  |  |  |
| 20 | Võ Minh Hải | UV BCH - PGĐ TT Hành chính công | 0945 676 959 | 747 527 |  |  |
| 21 | Nguyễn Thị Hồng Cúc | UV BCH - CVP HĐND và UBND | 0765 320 218 |  |  |  |
| 22 | Lê Văn Nhất | PCVP HĐND và UBND | 0775 798 177 |  |  |  |
| 23 | Nguyễn Trọng Hiếu | UV BCH - Trưởng phòng kinh tế | 0908 278 968 |  |  |  |
| 24 | Trần Thị Thanh Phương | PTP kinh tế | 0918 699 804 |  |  |  |
| 25 | Lê Chí Nghĩa | UV BCH - TP Văn hóa - Xã hội | 0985 456 224 |  |  |  |
| 26 | Đỗ Thị Hồng Nhung | PTP Văn hóa - Xã hội | 0902 633 263 |  |  |  |
| 27 | Mai CVinh | UV BCH - GĐ TT Cung ứng DVSN công | 0919 848 387 |  |  |  |
| 28 | Trung tá Huỳnh Văn Kỳ | UV BTV - Trưởng Công an | 0911 313 138 | 876 657 |  |  |
| 29 | Trung tá Lê Tấn Dư | UV BCH - Phó trưởng Công an | 0792 185 631 | 876 657 |  |  |
| 30 | Trung tá Nguyễn Thị Hồng Vân | Phó trưởng Công an | 0946 697 171 | 876 657 |  |  |
| 31 | Trung tá Lê Phú Hùng | Phó trưởng Công an | 0397 700 838 | 876 657 |  |  |
| 32 | Trung tá Phan Trung Tín | Phó trưởng Công an | 0909 485 483 | 876 657 |  |  |
| 33 | Trung tá Hồ Thị Kim Phấn | Phó trưởng Công an | 0907 922 177 | 876 657 |  |  |
| 34 | Phan Thanh Bảo | UV BTV - CHT BCH Quân sự | 0964 584 118 | 896 688 |  |  |
| 35 | Nguyễn Tấn Vũ | UV BCH - PCHT BCH Quân sự | 0898 918 520 | 896 688 |  |  |

### XÃ TÂN TRỤ

- Nhóm: 1
- Mã/STT nhóm: 64

### Đảng ủy xã Tân Trụ / Địa chỉ: đường Trương Gia Mô, ấp Bình Hòa, xã Tân Trụ, tỉnh Tây Ninh

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 1 | Đặng Hoàng Tuấn | Tỉnh ủy viên, Bí thư Đảng ủy | 0918 439 530 |  |  |  |
| 2 | Tô Phi Hùng | Phó Bí thư Thường trực - Chủ tịch HĐND xã | 0829 555 739 |  |  |  |
| 3 | Trần Hữu Đên | Ủy viên Ban Thường vụ - CN UBKT - / kiêm TB Văn hóa - Xã hội HĐND | 0397 839 818 |  |  |  |
| 4 | Nguyễn Thị Kiều Sương | Phó Chủ nhiệm Ủy ban kiểm tra Đảng ủy xã | 0976 212 973 |  |  |  |
| 5 | Mai Thanh Tân | Ủy viên Ban Thường vụ - TB Xây dựng đảng - kiêm Trưởng Ban Kinh tế - Ngân sách HĐND | 0946 565 672 |  |  |  |
| 6 | Trần Công Dự | Phó Trưởng Ban Xây dựng đảng | 0815 876 877 |  |  |  |
| 7 | Trần Thị Kim Hoa | Phó Trưởng Ban Xây dựng đảng | 0353 517 429 |  |  |  |
| 8 | Lê Hoàng Hải | Chánh Văn phòng Đảng ủy xã | 0918 020 987 |  |  |  |
| 9 | Lê Thị Huỳnh Như | Phó Chánh Văn phòng Đảng ủy xã | 0384 718 784 |  |  |  |
| 10 | Nguyễn Hữu Danh | Phó Chánh Văn phòng Đảng ủy xã | 0917 676 793 |  |  |  |
| 11 | Nguyễn Thị Bích Tuyền | Ủy viên Ban Thường vụ - CT MTTQ | 0385 747 596 |  |  |  |
| 12 | Trương Thị Tuyết Mai | PCT MTTQ - phụ trách Hội PN | 0938 942 846 |  |  |  |
| 13 | Đỗ Tấn Lực | PCT MTTQ - phụ trách Hội ND | 0374 444 475 |  |  |  |
| 14 | Trần Thanh Tiến | PCT MTTQ - phụ trách Đoàn TN | 0933 064 844 |  |  |  |
| 15 | Phạm Quốc Thấy | PCT MTTQ - phụ trách Hội CCB | 0979 570 789 |  |  |  |
| 16 | Nguyễn Thanh Bình | Giám đốc Trung tâm chính trị xã | 0942 704 291 |  |  |  |

### HĐND xã TÂN TRỤ - Địa chỉ: đường Trương Gia Mô, ấp Bình Hòa, xã Tân Trụ

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 17 | Lê Hồng Hưng | Ủy viên Ban Thường vụ - PCT HĐND xã | 0384 002 630 |  |  |  |
| 18 | Phạm Thành Dự | PTB Kinh tế - Ngân sách HĐND xã | 0392 499 799 |  |  |  |
| 19 | Phan Minh Thắng | PTB Văn hóa - Xã hội HĐND xã | 0344 322 244 |  |  |  |

### UBND xã TÂN TRỤ- ĐT bàn: 02723867130; email: ubnd.....@tayninh.gov.vn

### Địa chỉ: đường Trương Gia Mô, ấp Bình Hòa, xã Tân Trụ, tỉnh Tây Ninh

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 20 | Nguyễn Thị Phúc | Phó Bí thư Đảng ủy - Chủ tịch UBND xã | 0842 239 787 |  |  |  |
| 21 | Nguyễn Chí Cường | Ủy viên BTV - Phó Chủ tịch UBND xã | 0916 744 526 |  |  |  |
| 22 | Nguyễn Hồng Dũng | Ủy viên BTV - Phó Chủ tịch UBND xã / kiêm Giám đốc Trung tâm PVHHC | 0937 475 599 |  |  |  |
| 23 | Nguyễn Văn Du | Chánh Văn phòng HĐND và UBND xã | 0938 251 774 |  |  |  |
| 24 | Nguyễn Thị Mười | Phó CVP HĐND và UBND xã | 0977 505 459 |  |  |  |
| 25 | Nguyễn Trọng Nghĩa | Trưởng phòng Kinh tế xã | 0387 518 176 |  |  |  |
| 26 | Trần Hồng Phong | Phó Trưởng phòng Kinh tế xã | 0913 167 445 |  |  |  |
| 27 | Nguyễn Thành Danh | Phó Trưởng phòng Kinh tế xã | 0976 212 642 |  |  |  |
| 28 | Trần Thanh Vân | Trưởng phòng Văn hóa - Xã hội xã | 0919 124 273 |  |  |  |
| 29 | Trương Hồng Thái | Phó Trưởng phòng Văn hóa - Xã hội xã | 0917 676 774 |  |  |  |
| 30 | Ngô Văn Đảnh | PGĐ TT phục vụ Hành chính công | 0918 756 289 |  |  |  |
| 31 | Hồ Thanh Lợi | PGĐ TT phục vụ Hành chính công | 0918 597 926 |  |  |  |

### Trung tâm cung ứng DVSN công. Địa chỉ: tỉnh lộ 833B, ấp Bình Hòa, xã Tân Trụ

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 32 | Ngô Văn Quốc | GĐ TT Cung ứng dịch vụ sự nghiệp công xã | 0918 756 263 |  |  |  |

### Công an xã. Địa chỉ: ấp Bình Điện, xã Tân Trụ, tỉnh Tây Ninh

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 33 | Nguyễn Minh Trung | Ủy viên BTV - Trưởng Công an xã | 0907 548 749 |  |  |  |
| 34 | Phạm Hoài Phong | Phó trưởng Công an xã | 0907 263 248 |  |  |  |

### Ban chỉ huy quân sự xã. Địa chỉ: ấp Bình Lãng, xã Tân Trụ, tỉnh Tây Ninh

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 35 | Nguyễn Hoàng Ân | Ủy viên BTV - CHT Ban CH Quân sự | 0353 450 042 |  |  |  |
| 36 | Trần Tuấn Dũng | Phó CHT Ban CH Quân sự | 0392 609 222 |  |  |  |

### XÃ NHỰT TẢO

- Nhóm: 1
- Mã/STT nhóm: 65

#### Địa chỉ:

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 1 | Phạm Thanh Bình | Bí thư | 0918 499 107 |  |  |  |
| 2 | Nguyễn Thanh Phú | Phó Bí thư - CT HĐND | 0849 489 969 |  |  |  |
| 3 | Trương Minh Trí | Phó Bí thư - CT UBND | 0385 295 959 |  |  |  |
| 4 | Ngô Tấn Tài | UV BTV - PCT UBND | 0918 891 235 |  |  |  |
| 5 | Nguyễn Tấn Uy | UV BTV - PCT UBND | 0914 176 006 |  |  |  |
| 6 | Đặng Thị Hoa Phượng | UV BTV - PCT HĐND | 0941 676 190 |  |  |  |
| 7 | Hồ Văn Tùng | UV BTV - CT MTTQ | 0918 589 187 |  |  |  |
| 8 | Bùi Thị Thanh Trang | UV BTV - CN UBKT | 0386 675 755 |  |  |  |
| 9 | Trần Văn Lập | UV BTV - TCA | 0982 073 359 |  |  |  |
| 10 | Phan Thanh Điền | UV BTV - CHT BCHQS | 0914 042 910 |  |  |  |
| 11 | Huỳnh Hữu Lợi | UV BCH - CVP ĐU | 0919 618 040 | 02723 886 999 |  |  |
| 12 | Nguyễn Ngọc Thanh Phương | UV BCH - PT BXĐĐ | 0909 415 919 |  |  |  |
| 13 | Trần Thị Huyền Trân | UV BCH - PT BXĐĐ | 0976 299 993 |  |  |  |
| 14 | Nguyễn Thanh Duy | UV BCH - PT BXĐĐ | 0937 611 818 |  |  |  |
| 15 | Lê Đoàn Tiến Triển | UV BCH - PCN UBKTĐU | 0977 681 122 |  |  |  |
| 16 | Nguyễn Thái Phong | UV BCH - CT HND | 0367 806 261 |  |  |  |
| 17 | Trương Thị Ngọc Trang | UV BCH - CT HLHPN | 0916 354 469 |  |  |  |
| 18 | Nguyễn Thanh Hải | UV BCH - BT ĐTNCSHCM | 0384 517 178 |  |  |  |
| 19 | Phạm Thành Huy | UV BCH - CT Hội CCB | 0919 220 939 |  |  |  |
| 20 | Lê Minh Toàn | UV BCH - CVP HĐND và UBND | 0988 645 245 |  |  |  |
| 21 | Nguyễn Quốc Thái | UV BCH - TP KT | 0916 400 535 |  |  |  |
| 22 | Nguyễn Minh Hiếu | UV BCH - TP VHXH | 0949 005 687 |  |  |  |
| 23 | Nguyễn Tấn Đạt | UV BCH - PGĐ TTPVHCC | 0913 867 155 | 02723 767 999 |  |  |
| 24 | Hồ Quốc Khánh | UV BCH - GĐ TTCUDVSNC | 0826 773 738 |  |  |  |
| 25 | Phan Quốc Tuấn | UV BCH - PB KT - NS | 0977 670 479 |  |  |  |
| 26 | Nguyễn Thanh Nhàn | UV BCH - PB VH - XH | 0969 338 370 |  |  |  |
| 27 | Nguyễn Ngọc Giao | UV BCH - PCHT BCHQS | 0902 524 734 | 02723 567 345 |  |  |
| 28 | Nguyễn Quốc Thịnh | UV BCH - PT CA | 0918 462 848 | 02723 689 339 |  |  |
| 29 | Nguyễn Trần Mỹ Tân | UV BCH - / HT Trường THPT Nguyễn Trung Trực | 0938 266 679 |  |  |  |
| 30 | Đặng Ngọc Hòa | PCVP ĐU | 0938 569 727 |  |  |  |
| 31 | Hồ Thị Cẩm Nguyên | PCVP ĐU | 0365 045 799 |  |  |  |
| 32 | Tô Quốc Phong | PCVP HĐND và UBND | 0834 787 097 |  |  |  |
| 33 | Nguyễn Phát Trung | PTP KT | 0976 280 448 |  |  |  |
| 34 | Dương Hoài Nhân | PTP VHXH | 0943 373 851 |  |  |  |
| 35 | Nguyễn Mạnh Tường | PGĐ TTCUDVSNC | 0908 094 060 |  |  |  |

### XÃ VÀM CỎ

- Nhóm: 1
- Mã/STT nhóm: 66

### Đảng ủy xã Vàm Cỏ - Địa chỉ: Hương lộ 25, ấp 1, xã Vàm Cỏ

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 1 | Trần Minh Đạt | Bí thư | 0393 811 829 |  |  |  |
| 2 | Lê Thị Hồng Thắm | Phó BT TT - Chủ tịch HĐND | 0848 653 168 |  |  |  |
| 3 | Đặng Minh Tân | UV BTV - CN UBKT | 0826 198 199 |  |  |  |
| 4 | Võ Thị Điệp | UV BCH - Phó CN UBKT | 0907 793 468 |  |  |  |
| 5 | Phạm Thị Ánh Nguyệt | UV BTV - Trưởng ban Xây dựng đảng | 0354 318 118 |  |  |  |
| 6 | Nguyễn Thị Ngọc Hoa | UV BCH - PTB Xây dựng đảng | 0379 629 137 |  |  |  |
| 7 | Lê Hoàng Thoại | UV BCH - CVP Đảng ủy xã | 0765 408 819 |  |  |  |
| 8 | Trần Thị Kim Thanh | Phó Chánh Văn phòng Đảng ủy xã | 0374 311 502 |  |  |  |
| 9 | Trần Thị Cẩm Phượng | Phó Chánh Văn phòng Đảng ủy xã | 0987 199 976 |  |  |  |
| 10 | Trần Thị Hồng Lan | UV BTV - Chủ tịch MTTQ | 0776 798 920 |  |  |  |
| 11 | Nguyễn Thị Kim Cương | UV BCH - PCT MTTQ, CT Hội Phụ nữ | 090 873 924 |  |  |  |
| 12 | Lê Văn Đức | UV BCH - PCT MTTQ, CT Hội ND | 0933 242 302 |  |  |  |
| 13 | Nguyễn Trần Huỳnh Đức | UV BCH - PCT MTTQ, BT Đoàn TN | 0898 997 307 |  |  |  |
| 14 | Lê Quốc Cường | UV BCH - PCT MTTQ, CT Hội CCB | 0933 109 361 |  |  |  |

### Hội đồng nhân dân xã Vàm Cỏ - Địa chỉ: Hương lộ 25, ấp 1, xã Vàm Cỏ

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 15 | Lê Thị Hồng Thắm | Phó Bí thư Thường trực Đảng ủy - Chủ tịch HĐND | 0848 653 168 |  |  |  |
| 16 | Trần Thanh Nhanh | UV BTV - PCT HĐND | 0823 031 838 |  |  |  |
| 17 | Đặng Minh Tân | CN UBKT Đảng ủy xã, Trưởng Ban Kinh tế - Ngân sách | 0826 198 199 |  |  |  |
| 18 | Trần Thị Hồng Lan | Chủ tịch MTTQ Việt Nam xã, Trưởng Ban Văn hóa - Xã hội | 0776 798 920 |  |  |  |
| 19 | Nguyễn Thành Trung | PTB Kinh tế - Ngân sách | 0947 427 537 |  |  |  |
| 20 | Võ Hoàng Huy | PTB Văn hóa - Xã hội | 0836 969 838 |  | hoangvo7311352@gmail.com |  |

### UBND xã Vàm Cỏ - ĐT bàn: 0272 3867248; email: ubndvamco@tayninh.gov.vn

### Địa chỉ: Hương lộ 25, ấp 1, xã Vàm Cỏ

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 21 | Đặng Văn Tây Lo | Phó Bí thư - Chủ tịch UBND | 0918 140 223 |  | lodvt@tayninh.gov.vn |  |
| 22 | Tạ Thành Bản | UV BTV - PCT UBND | 0918 058 806 |  | bantt@tayninh.gov.vn |  |
| 23 | Huỳnh Trọng Ân | UV BTV - PCT UBND | 0907 615 346 |  | anht.vamco@tayninh.gov.vn |  |
| 24 | Lê Thành Việt | Đảng ủy viên - CVP HĐND và UBND xã | 0907 191 577 |  | lethanhviet@tayninh.gov.vn |  |
| 25 | Lữ Minh Thành | PCVP HĐND và UBND xã | 0933 210 998 |  | luminhthanh@tayninh.gov.vn |  |
| 26 | Trần Thị Hồng Thúy | Đảng ủy viên - Trưởng phòng Kinh tế xã | 0363 337 445 |  | thuytth@tayninh.gov.vn |  |
| 27 | Trần Minh Tâm | Phó Trưởng phòng Kinh tế xã | 0765 163 806 |  | tranminhtam@tayninh.gov.vn |  |
| 28 | Nguyễn Thị Ngọc Vệ | ĐUV - Trưởng phòng Văn hóa - Xã hội | 0365 135 329 |  | ventn@tayninh.gov.vn |  |
| 29 | Lê Trung Hậu | Phó Trưởng phòng Văn hóa - Xã hội | 0905 165 550 |  | lthau@tayninh.gov.vn |  |
| 30 | Huỳnh Trọng Ân | PCT UBND - Giám đốc TT Phục vụ Hành chính công | 0907 615 346 |  | anht.vamco@tayninh.gov.vn |  |
| 31 | Trần Nhân Vị | PGĐ TT Hành chính công | 0909 810 350 |  | tvnhan@tayninh.gov.vn |  |
| 32 | Đỗ Hữu Thiện | Giám đốc TT Cung ứng DVSN công | 0974 213 253 |  | dohuuthien82@gmail.com |  |
| 33 | Nguyễn Hồng Lân | UV BTV - Trưởng Công an | 0979 625 950 | 02723 723 999 |  |  |
| 34 | Phan Minh Triền | Phó Trưởng Công an | 0902 418 717 |  |  |  |
| 35 | Nguyễn Đăng Khôi | Phó Trưởng Công an | 0985 537 837 |  |  |  |
| 36 | Hà Long Giang | Phó Trưởng Công an | 0919 340 132 |  |  |  |
| 37 | Châu Ngọc Phong | Phó Trưởng Công an | 0908 348 716 |  |  |  |
| 38 | Nguyễn Mai Thu Nga | Phó Trưởng Công an | 0934 155 591 |  |  |  |
| 39 | Phạm Công Danh | UV BTV - CHT BCH Quân sự | 0937 038 460 | 0272 3818 777 | Phamcongdanh09111991@gmail.com |  |
| 41 | Võ Trí Bình | Phó CHT BCH Quân sự | 0949 797 149 |  | tribinh50615@gmail.com |  |

### XÃ TẦM VU

- Nhóm: 1
- Mã/STT nhóm: 67

### Đảng ủy Tầm Vu - ĐT bàn: 02723 877 055; email: danguyxatamvu@tayninh.dcs.vn

### Địa chỉ: Đường Đỗ Tường Tự, ấp Trường Xuân, xã Tầm Vu

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 1 | Lê Quốc Dũng | Bí thư | 0903 654 333 |  |  |  |
| 2 | Nguyễn CTrạng | Phó Bí thư thường trực | 0903 654 333 |  |  |  |
| 3 | Nguyễn Thị Ngọc Trầm | UV BTV - CN UBKT | 0918 808 739 |  |  |  |
| 4 | Bùi Văn Thạch | UV BCH - PCN UBKT | 0942 188 281 |  |  |  |
| 5 | Nguyễn Thanh Hiền | UV BTV - TB Xây dựng đảng | 0947 067 509 |  |  |  |
| 6 | Châu Văn Cấp | UV BCH - PTB Xây dựng đảng | 0908 343 550 |  |  |  |
| 7 | Nguyễn Thành Học | UV BCH - CVP Đảng ủy | 0913 818 588 |  |  |  |
| 8 | Nguyễn Phước Hải | UV BTV - CT MTTQ xã | 0327 616 668 |  |  |  |
| 9 | Huỳnh Thị Anh Đào | UV BCH - PCT MTTQ, CT Hội ND | 0857 849 879 |  |  |  |
| 10 | Trương Hoàng Đầy | UV BCH - PCT MTTQ, CT Hội CCB | 0865 228 635 |  |  |  |
| 11 | Nguyễn Thị Thanh Lan | UV BCH - PCT MTTQ, BT Đoàn TN | 0835 119 409 |  |  |  |
| 12 | Nguyễn Thị Xuân Hương | UV BCH - PCT MTTQ, CT Hội PN | 0915 053 056 |  |  |  |

### Hội đồng nhân dân xã Tầm Vu - ĐT bàn: 02723 877 060; email: hdndtamvu@tayninh.gov.vn

### Địa chỉ: Đường Đỗ Tường Tự, ấp Trường Xuân, xã Tầm Vu

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 13 | Nguyễn CTrạng | PBT thường trực - CT HĐND | 0919 124 718 |  |  |  |
| 14 | Nguyễn Minh Trung | UVTV, PCT HĐND | 0942 298 788 |  |  |  |
| 15 | Nguyễn Thị Ngọc Trầm | UV BTV - TB KT-NS HĐND | 0918 808 739 |  |  |  |
| 16 | Nguyễn Thanh Hiền | UV BTV - TB VHXH HĐND | 0947 067 509 |  |  |  |
| 17 | Huỳnh Văn Quốc | UV BCH, PT Ban KT-NS HĐND | 0985 767 010 |  |  |  |
| 18 | Trương Văn Toàn | UV BCH, PT Ban VHXH HĐND | 0941 486 832 |  |  |  |

### UBND xã Tầm Vu - ĐT bàn: 02723 877 060; email: ubndtamvu@tayninh.gov.vn

### Địa chỉ: Đường Đỗ Tường Tự, ấp Trường Xuân, xã Tầm Vu

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 19 | Phạm Văn Thật | Phó Bí thư - CT UBND | 0918 671 467 |  |  |  |
| 20 | Võ Văn Cần | UV BTV, PCT UBND | 0917 530 133 |  |  |  |
| 21 | Nguyễn Thị Bích Tuyền | UV BTV, PCT UBND | 0908 598 229 |  |  |  |
| 22 | Trần Thị Kim Cương | UV BCH - CVP HĐND và UBND | 0827 986 607 |  |  |  |
| 23 | Nguyễn Văn Vô | PCVP HĐND và UBND | 0865 264 009 |  |  |  |
| 24 | Võ Lê Đại Hưng | UV BCH, Trưởng phòng Kinh tế | 0916 658 875 |  |  |  |
| 25 | Nguyễn Vũ Phong | PTP Kinh tế | 0918 314 279 |  |  |  |
| 26 | Nguyễn Thị Kim Yến | UV BCH, Trưởng phòng VH- XH | 0942 700 759 | ABC |  |  |
| 27 | Trần Chí Bằng | PTP VH-XH | 0989 719 703 |  |  |  |
| 28 | Nguyễn Tuấn Anh | UV BCH, PGĐ TT PVHCC | 0376 406 585 |  |  |  |
| 29 | Trần Thanh Minh | UV BCH, GĐ TT Chính trị | 0949 865 981 |  |  |  |
| 30 | Nguyễn Thị Yến | UV BCH, GĐ TT CUDVSNC | 0911 206 707 |  |  |  |
| 31 | Phạm Ngọc Điền | UV BTV, Trưởng Công an | 0905 480 398 |  |  |  |
| 32 | Phạm Thanh An | UV BCH, Phó Trưởng Công an | 0918 185 887 |  |  |  |
| 33 | Trương Quang Minh | Phó Trưởng Công an | 0918 637 675 |  |  |  |
| 34 | Trương Văn Quang | Phó Trưởng Công an | 0989 757 798 |  |  |  |
| 35 | Đặng Văn Nghiệm | Phó Trưởng Công an | 0913 999 849 |  |  |  |
| 36 | Võ Phạm Minh Hòa | Phó Trưởng Công an | 0988 216 625 |  |  |  |
| 37 | Phan Đức Thiện | UV BTV, CHT BCH Quân sự | 0943 832 262 |  |  |  |
| 38 | Cao Hoài Thân | UV BCH, Phó CHT BCH Quân sự | 0583 375 968 |  |  |  |

### Xã Thuận Mỹ

- Nhóm: 1
- Mã/STT nhóm: 68

### Đảng ủy Thuận Mỹ - Địa chỉ: Ấp Thanh Tân, xã Thuận Mỹ

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 1 | Nguyễn Văn Khải | Bí thư - Chủ tịch HĐND | 0912 817 936 |  |  |  |
| 2 | Phạm Văn Lành | Phó Bí thư Thường trực Đảng ủy | 0354 606 778 |  |  |  |
| 3 | Trần Quang Minh | UV BTV - CN UBKT | 0834 986 869 |  |  |  |
| 4 | Phan Thị Mộng Thường | UV BCH - PCN UBKT | 0948 446 228 |  |  |  |
| 5 | Nguyễn Thanh Tùng | UV BTV - TB Xây dựng đảng | 0363 755 220 |  |  |  |
| 6 | Kiều ĐSang | UV BCH - PTB Xây dựng đảng | 0848 710 939 |  |  |  |
| 7 | Đỗ Minh Xuân | UV BCH - CVP Đảng ủy | 0978 454 289 |  |  |  |
| 8 | Trần Thị Ngà | UV BTV - CT MTTQ xã | 0823 745 103 |  |  |  |
| 9 | Nguyễn Thị Mỹ Dung | UV BCH - PCT MTTQ, CT Hội PN | 0946 254 848 |  |  |  |
| 10 | Huỳnh Mai Trường Hận | UV BCH - PCT MTTQ, CT Hội ND | 0987 022 246 |  |  |  |
| 11 | Nguyễn Duy Đức Lin | UV BCH - PCT MTTQ, BT Đoàn TN | 0969 909 691 |  |  |  |
| 12 | Võ Nguyễn Thanh Năng | UV BCH - PCT MTTQ, CT Hội CCB | 0333 282 860 |  |  |  |

### Hội đồng nhân dân xã Thuận Mỹ - Địa chỉ: Ấp Thanh Tân, xã Thuận Mỹ

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 13 | Võ Thành Hôn | UVBTV - PCT HĐND | 0345 143 211 |  |  |  |
| 14 | Nguyễn Văn Cảm | Phó Ban Kinh tế - Ngân sách HĐND | 0987 240 464 |  |  |  |
| 15 | Lê Thị Tố Quyên | Phó Ban Văn hóa - Xã hội HĐND | 0358 273 592 |  |  |  |

### UBND xã Thuận Mỹ - SĐT 0272 3879 016. Email: ubndthuanmy@tayninh.gov.vn

### Địa chỉ: Ấp Bình Trị 1, xã Thuận Mỹ

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 16 | Nguyễn Thành Hiếu | Phó Bí thư - CT UBND xã | 0916 432 409 |  |  |  |
| 17 | Đỗ Thành Hải | UV BTV - PCT UBND - GĐ TT Hành chính cxã | 0919 820 897 |  |  |  |
| 18 | Đỗ Thế Ngân | UV BTV - PCT UBND xã | 0978 454 089 |  |  |  |
| 19 | Lương Sơn Đậm | UV BCH - CVP HĐND và UBND | 0392 652 952 |  |  |  |
| 20 | Huỳnh Danh Dự | PCVP HĐND và UBND | 0949 022 229 |  |  |  |
| 21 | Trần Lâm Duy Linh | UV BCH - Trưởng phòng kinh tế | 0919 743 853 |  |  |  |
| 22 | Huỳnh Thiện Phương | PTP kinh tế | 0909 262 427 |  |  |  |
| 23 | Nguyễn Thị Tất Cả | UV BCH - Trưởng Phòng Văn hóa - Xã hội | 0933 988 427 | ABC |  |  |
| 24 | Phạm Hùng Sang | PTP VH-XH kiêm GĐ TT Cung ứng DVSN cxã | 0984 947 674 |  |  |  |
| 25 | Nguyễn Hữu Đăng Nguyên | PGĐ TT Cung ứng DVSN cxã | 0843 130 297 |  |  |  |
| 26 | Đỗ Minh Hà | UV BCH - PGĐ TT Hành chính cxã | 0336 401 450 |  |  |  |
| 27 | Nguyễn Quốc Tiềm | UV BTV - Trưởng Công an | 0937 307 073 |  |  |  |
| 28 | Nguyễn An Toàn | UV BCH Phó trưởng Công an | 0909 767 227 |  |  |  |
| 29 | Hồ Thanh Vũ | UV BTV - CHT BCH Quân sự | 0907 426 218 |  |  |  |
| 30 | Nguyễn Phan Vương | UV BCH - CHT BCH Quân sự | 0964 300 090 |  |  |  |

### XÃ AN LỤC LONG

- Nhóm: 1
- Mã/STT nhóm: 69

### Đảng ủy An Lục Long - Địa chỉ: Ấp Lộ Đá, xã An Lục Long

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 1 | Nguyễn Thị Út Thủy | Bí thư Đảng ủy | 0918 976 597 |  |  |  |
| 2 | Trần Hoàng Sang | UV BTV - CN UBKT | 0818 871 819 |  |  |  |
| 3 | Huỳnh Thái Thanh | UV BCH - PCN UBKT | 0935 106 237 |  |  |  |
| 4 | Lê Thị Thu Vân | UV BTV - TB Xây dựng đảng | 0836 134 179 |  |  |  |
| 5 | Trương Thị Non | UV BCH - PTB Xây dựng đảng | 0819 287 449 |  |  |  |
| 6 | Đỗ Phúc Hậu | UV BCH - CVP Đảng ủy | 0939 327 879 |  |  |  |
| 7 | Nguyễn Ngọc Qui | Phó CVP Đảng ủy | 0949 948 099 |  |  |  |
| 8 | Đỗ Tấn Đạt | UV BTV - CT MTTQ | 0988 216 405 |  |  |  |
| 9 | Ung Thị Hải Quyên | UV BCH - PCT MTTQ, CT Hội PN | 0349 806 127 |  |  |  |
| 10 | Trần Kim Vân | UV BCH - PCT MTTQ, CT Hội ND | 0976 167 451 |  |  |  |
| 11 | Đỗ Phú Vinh | UV BCH - PCT MTTQ, BT Đoàn TN | 0932 007 776 |  |  |  |
| 12 | Lê Văn Thương | UV BCH - PCT MTTQ, CT Hội CCB | 0819 002 357 |  |  |  |

### Hội đồng nhân dân xã An Lục Long - Địa chỉ: Ấp Long Thành, xã An Lục Long

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 13 | Nguyễn Văn Dự | Phó Bí thư - CT HĐND | 0919 274 481 |  |  |  |
| 14 | Nguyễn Thị Thanh Hà | UV BTV - PCT HĐND | 0333 495 688 |  |  |  |
| 15 | Phan Hoàng Phương | UV BCH - PTB KT-NS HĐND | 0918 021 020 |  |  |  |
| 16 | Nguyễn Văn Minh | UV BCH - PTB VH- XH HĐND | 0812 233 444 |  |  |  |

### Ủy ban nhân dân xã - ĐT bàn: 02723 679 234; email: ubndanluclong@tayninh.gov.vn

### Địa chỉ: Ấp Long Thành, xã An Lục Long

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 17 | Hà Minh Tuấn | Phó Bí thư - CT UBND | 0987 304 108 |  |  |  |
| 18 | Nguyễn Trung Rở | UV BTV - PCT UBND | 0973 406 664 |  |  |  |
| 19 | Châu Văn Thêm | UV BTV - PCT UBND | 0979 393 319 |  |  |  |
| 20 | Phan Lê Thị Thanh Xuân | UV BCH - CVP HĐND và UBND | 0949 544 154 |  |  |  |
| 21 | Huỳnh Thuận | PCVP HĐND và UBND | 0852 626 362 |  |  |  |
| 22 | Đoàn Bảo An | UV BCH - Trưởng phòng kinh tế | 0339 502 156 |  |  |  |
| 23 | Nguyễn Duy Phương | PTP Kinh tế | 0917 669 866 |  |  |  |
| 24 | Lê Thị Ngọc Giàu | UV BCH - TP Văn hóa - Xã hội | 0355 979 686 | ABC |  |  |
| 25 | Nguyễn Thị Phương Thúy | PTP Văn hóa - Xã hội | 0858 127 278 |  |  |  |
| 26 | Nguyễn Văn Sen | UV BCH - PGĐ TT PVHCC | 0888 016 727 | 02723 877 077 |  |  |
| 27 | Bùi Mạnh Tấn | PGĐ TT Cung ứng DVSN công | 0943 125 939 |  |  |  |
| 28 | Huỳnh CĐức | UVBTV - Trưởng Công an | 0918 266 196 | 02723 888 060 |  |  |
| 29 | Huỳnh Lê Duy Phương | UV BCH - Phó trưởng Công an | 0973 959 699 | 02723 888 060 |  |  |
| 30 | Nguyễn Hoàng Lộc | UV BTV - CHT BCH Quân sự | 0388 759 940 | 02723 667 155 |  |  |
| 31 | Nguyễn Ngọc Qui | UV BCH PCHT BCH Quân sự | 0383 323 508 | 02723 667 155 |  |  |

### Xã Vĩnh Công

- Nhóm: 1
- Mã/STT nhóm: 70

### Đảng ủy Vĩnh Công - Địa chỉ: Đường 827B, ấp Kỳ Châu, xã Vĩnh Công

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 1 | Nguyễn Thị Diễm Quỳnh | Bí thư | 0985 445 433 |  |  |  |
| 2 | Trần Ngọc Minh | Phó Bí thư | 0909 826 247 |  |  |  |
| 3 | Trương Thị Phương Thảo | UV BTV - CN UBKT | 0942 287 286 |  |  |  |
| 4 | Trương Quốc Trung | UV BCH - PCN UBKT | 0911 489 090 |  |  |  |
| 5 | Nguyễn Thị Thùy Ngân | UV BTV - TB Xây dựng đảng | 0986 238 487 |  |  |  |
| 6 | Lê Thị Hồng Nghiệm | UV BCH - PTB Xây dựng đảng | 0985 493 122 |  |  |  |
| 7 | Châu Văn Bình | UV BCH - CVP Đảng ủy | 0989 959 810 | 02723 662 892 |  |  |
| 8 | Võ Thành Thật | Chức vụ đảng - CT MTTQ xã | 0947 115 275 |  |  |  |
| 9 | Trần Ngọc Lê Như Ngân | UV BCH - PCT MTTQ, CT Hội PN | 0824 117 979 |  |  |  |
| 10 | Nguyễn Hoàng Hải | UV BCH - PCT MTTQ, CT Hội ND | 0937 015 944 |  |  |  |
| 11 | Nguyễn Thanh Nhàng | UV BCH - PCT MTTQ, BT Đoàn TN | 0366 757 753 |  |  |  |
| 12 | Huỳnh Văn Sỹ | UV BCH- PCT.MTTQ- Hội CCB | 0355 874 254 |  |  |  |

### Hội đồng nhân dân xã Vĩnh Công

### Địa chỉ: Đường 827, ấp 2, xã Vĩnh Công

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 13 | Võ Thành Long | Chức vụ Đảng - CT HĐND | 0828 939 678 |  |  |  |
| 14 | Nguyễn Lê Trường | Ban Kinh tế - HĐND | 0983 669 315 |  |  |  |
| 15 | Nguyễn Văn Luyến | Ban VHXH - HĐND | 0354 053 431 |  |  |  |

### UBND xã - ĐT bàn: 02723 877 097; email: ubndxvcchauthanh@tayninh.gov.vn

### Địa chỉ: Đường 827, ấp 8, xã Vĩnh Công

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 16 | Nguyễn Minh Châu | Phó Bí thư - CT UBND | 0902 523 323 |  |  |  |
| 17 | Nguyễn Văn Phú | Chức vụ đảng - PCT UBND | 0919 612 188 |  |  |  |
| 18 | Nguyễn Ngọc Thảo Sương | Chức vụ đảng - PCT UBND | 0908 352 288 |  |  |  |
| 19 | Trần Tấn Vĩnh | Chức vụ đảng - CVP HĐND và UBND | 0914 710 280 |  |  |  |
| 20 | Trần Việt Trung | PCVP HĐND và UBND | 0918 447 673 |  |  |  |
| 21 | Phan Đại Bảo | Chức vụ đảng - Trưởng phòng kinh tế | 0906 204 368 |  |  |  |
| 22 | Nguyễn Thành Trung | PTP kinh tế | 0835 202 132 |  |  |  |
| 23 | Lê Thị Bích Ngọc | Chức vụ đảng - TP Văn hóa - Xã hội | 0396 989 168 | ABC |  |  |
| 24 | Nguyễn Văn Ngọc Ba | PTP Văn hóa - Xã hội | 0943 491 955 |  |  |  |
| 25 | Nguyễn Văn Phú | GĐ TT Hành chính công | 0919 612 188 |  |  |  |
| 26 | Lê Thị Kim Ngân | PGĐ TT Hành chính công | 0946 628 059 |  |  |  |
| 27 | Đinh Văn Thủy | GĐ TT Cung ứng DVSN công | 0917 136 807 |  |  |  |
| 28 | Trần Vũ Bằng | Chức vụ đảng - Trưởng Công an | 0977 084 984 |  |  |  |
| 29 | Nguyễn Tuyền Phong | Phó trưởng Công an | 0817 109 233 |  |  |  |
| 30 | Huỳnh Phúc Thái | Phó trưởng Công an | 0906 309 837 |  |  |  |
| 31 | Đặng Thành Minh | Phó trưởng Công an | 0976 171 469 |  |  |  |
| 32 | Nguyễn Văn Nhật | Phó trưởng Công an | 0982 229 622 |  |  |  |
| 33 | Lê Đình Chi | Phó trưởng Công an | 0853 312 949 |  |  |  |
| 34 | Huỳnh Văn Phú | Chức vụ đảng - CHT BCH Quân sự | 0852 390 039 |  |  |  |
| 35 | Nguyễn Minh Phụng | Chức vụ đảng - Phó CHT BCH Quân sự | 0852 002 428 |  |  |  |

### Xã Tân Biên

- Nhóm: 1
- Mã/STT nhóm: 71

### Đảng ủy Tân Biên - Địa chỉ: số 95 đường Nguyễn Chí Thanh, khu phố 2, xã Tân Biên

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 1 | Lê Long Giang | Bí thư, Chủ tịch HĐND | 0949 118 116 |  |  |  |
| 2 | Hà Văn Đông | Phó Bí thư | 0911 135 858 |  |  |  |
| 3 | Trần Thị Trường An | UV BTV - CN UBKT / TB Kinh tế - Ngân sách HĐND | 0393 888 997 |  |  |  |
| 4 | Trần Thị Thùy Ninh | UV BCH - PCN UBKT | 0906 311 465 |  |  |  |
| 5 | Nguyễn Thanh Bình | UV BTV - TB Xây dựng đảng / TB Văn hóa - Xã hội HĐND | 0938 909 998 |  |  |  |
| 6 | Trần Thị Oanh Kiều | UV BCH - PTB Xây dựng đảng | 0945 058 148 |  |  |  |
| 7 | Nguyễn Quốc Toàn | UV BCH - CVP Đảng ủy | 0983 326 254 |  |  |  |
| 8 | Nguyễn Bảo Thọ | Phó CVP Đảng ủy | 0918 375 151 |  |  |  |
| 9 | Trần Chí Tâm | UV BTV - Chủ tịch MTTQ | 0933 777 177 |  |  |  |
| 10 | Trương Thị Kim Xanh | UV BCH - PCT MTTQ, CT Hội PN | 0942 753 131 |  |  |  |
| 11 | Nguyễn Chí Công | UV BCH - PCT MTTQ, CT Hội ND | 0983 874 345 / 0913 874 010 |  |  |  |
| 12 | Nguyễn Thị Thắm | UV BCH - PCT MTTQ, BT Đoàn TN | 0941 731 372 |  |  |  |
| 13 | Nguyễn Thành Trung | PCT MTTQ, CT Hội CCB | 0976 768 555 |  |  |  |

### HĐND Tân Biên - Địa chỉ: số 99 đường Nguyễn Chí Thanh, khu phố 7, xã Tân Biên

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 14 | Phan Thị Tố Nga | UV BTV - PCT HĐND | 0919 112 772 |  |  |  |
| 15 | Võ Thị Hương | Phó Ban Kinh tế - Ngân sách | 0398 830 883 / 0825 847 787 |  |  |  |
| 16 | Nguyễn Thị Yến Nhi | Phó Ban Văn hóa - Xã hội | 0393 143 082 / 0877 202 627 |  |  |  |

### UBND xã Tân Biên ; email: ubndtanbien@tayninh.gov.vn

### Địa chỉ: số 99 đường Nguyễn Chí Thanh, khu phố 7, xã Tân Biên

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 17 | Đoàn Thị Minh Thanh | Phó Bí thư - CT UBND | 0918 746 955 |  | thanhdtm@tayninh.gov.vn |  |
| 18 | Trần Đức Tuấn | UV BTV - PCT UBND | 0834 499 993 |  | tuantd@tayninh.gov.vn |  |
| 19 | Nguyễn Văn Hiếu | UV BCH - CVP HĐND và UBND | 0975 012 062 |  | nguyenvanhieu@tayninh.gov.vn |  |
| 20 | Nguyễn Thị Tình | PCVP HĐND và UBND | 0944 317 775 |  | nguyenthitinh@tayninh.gov.vn |  |
| 21 | Hồ Hải Quốc Khương | UV BCH - Trưởng phòng kinh tế | 0909 974 874 |  | quockhuong@tayninh.gov.vn |  |
| 22 | Nguyễn Thị Hồng Ngọc | PTP kinh tế | 0389 609 017 |  | ngthihongngoc@tayninh.gov.vn |  |
| 23 | Nguyễn Thị Hải | UV BCH - TP Văn hóa - Xã hội | 0912 346 765 |  | hainttb@tayninh.gov.vn |  |
| 24 | Võ Văn Tịnh | PTP Văn hóa - Xã hội | 0888 705 268 |  | vovantinh@tayninh.gov.vn |  |
| 25 | Phạm Thị Minh | PGĐ TT Hành chính công | 0963 292 979 |  | thiminh1987@tayninh.gov.vn |  |

### TT Cung ứng dịch vụ sự nghiệp công - Địa chỉ: số 131 đường Nguyễn Chí Thanh, khu phố 7, xã Tân Biên

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 26 | Lê Hoàng Vũ | GĐ TT Cung ứng DVSN công | 0962 052 057 |  | hoangvu1987@tayninh.gov.vn |  |
| 27 | Nguyễn Văn Xô | PGĐ TT Cung ứng DVSN công | 0913 884 811 |  | vanxo1972@tayninh.gov.vn |  |

### Ban Quản lý dự án xã Tân Biên - Địa chỉ: số 62 đường Phạm Hùng, khu phố 1, xã Tân Biên

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 28 | Nguyễn Trọng Thành | PGĐ Ban Quản lý dự án | 0909 777 193 |  | 072077003929@tayninh.gov.vn |  |

### Công an Tân Biên - Địa chỉ: số 43 đường Nguyễn Duy Trinh, khu phố 3, xã Tân Biên

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 29 | Trung tá Trần Đức Cương | UV BTV - Trưởng Công an | 0833 211 999 |  |  |  |
| 30 | Trung tá Ngô Thị Hiền | UV BCH - Phó trưởng Công an | 0913 560 118 |  |  |  |
| 31 | Trung tá Nguyễn Trọng Nghĩa | Phó trưởng Công an | 0937 122 167 |  |  |  |
| 32 | Trung tá Phạm Đức Hạnh | Phó trưởng Công an | 0979 000 900 |  |  |  |
| 33 | Thiếu tá Nguyễn Viết Tuân | Phó trưởng Công an | 0982 990 034 |  |  |  |

### Ban Chỉ huy Quân sư xã - Địa chỉ: số 21 đường Nguyễn Văn Linh, khu phố 3, xã Tân Biên

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 34 | Nguyễn Trung Kiên | UV BTV - CHT BCH Quân sự | 0974 960 331 |  |  |  |
| 35 | Lê Quốc Hưng | UV BCH - Phó CHT BCH Quân sự | 0918 040 527 |  |  |  |

### Xã Tân Lập

- Nhóm: 1
- Mã/STT nhóm: 72

#### Tổ 14, ấp Tân Hòa, xã Tân Lập

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 1 | Nguyễn Trọng Tấn | Bí thư Đảng ủy - CT HĐND | 0918 099 012 |  |  |  |
| 2 | Trịnh Hoài Phong | Phó Bí thư - CT MTTQ VN XÃ | 0918 359 888 |  |  |  |
| 3 | Nguyễn Thị Nga | Phó Bí thư - Chủ tịch UBND | 0908 933 695 |  |  |  |
| 4 | Tạ Thanh Bình | TVĐU- Trưởng Công an | 0949 602 444 |  |  |  |
| 5 | Nguyễn Quốc Dũng | TVĐU- CHT BCH Quân sự | 0985 134 431 |  |  |  |
| 6 | Nguyễn Thị Thanh | TVĐU- Trưởng BXDĐ, / TB Kinh tế - Ngân sách HĐND | 0349 793 089 |  |  |  |
| 7 | Đặng Tuyết Mai | TVĐU- CN UBKT, / TB Văn hóa - Xã hội HĐND | 0935 529 610 |  |  |  |
| 8 | Nguyễn Thị Cúc | TVĐU- PCT HĐND | 0914 541 424 |  |  |  |
| 9 | Nguyễn Hải Ninh | TVĐU- PCT UBND xã | 0844 775 757 |  |  |  |
| 10 | Nguyễn Văn Thạnh | ĐUV- PCT Uỷ ban nhân dân | 0907 367 627 |  |  |  |
| 11 | Nguyễn Thị Tươi | ĐUV- PTB Xây dựng Đảng | 0975 099 510 |  |  |  |
| 12 | Bùi Thanh Phong | ĐUV- PCN Ủy ban Kiểm tra Đảng ủy | 0985 585 385 |  |  |  |
| 13 | Trần Thị Ngân | ĐUV- CVP ĐU | 0918 837 559 |  |  |  |
| 14 | Nguyễn Việt Hùng | ĐUV- CVP HĐND-UBND | 0988 414 889 |  |  |  |
| 15 | Lê Ngọc Bích | ĐUV- Trưởng Phòng Kinh tế. | 0987 268 565 |  |  |  |
| 16 | Nguyễn Chí Sang | ĐUV- Trưởng Phòng Văn hoá - Xã hội | 0913 107 415 |  |  |  |
| 17 | Trần Thị Thúy Hằng | ĐUV- Phó Công an | 0907 235 353 |  |  |  |
| 18 | Trần Quyết Thắng | ĐUV- PCT MTTQ - BT Đoàn TN | 0913 757 773 |  |  |  |
| 19 | Nguyễn Thị Thảo | ĐUV- PCT MTTQ - CT Hội PN | 0943 842 123 |  |  |  |
| 20 | Đỗ Quang Hạnh | ĐUV - PCT TT MTTQ - CT Hội ND | 0919 113 820 |  |  |  |

#### Cao Thị Cẩm Nhung

- Chức vụ/ghi chú: Phó CVP Đảng ủy
- Di động: 0912 012 590

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 21 | Lê Văn Chẩn | Phó CVP | 0988 320 884 |  |  |  |
| 22 | Nguyễn Huy Giang | PTP KT | 0907 997 480 |  |  |  |
| 23 | Nguyễn Đức Thắng | Phó Trường phòng VH-XH | 0985 081 212 |  |  |  |
| 24 | Thành Phạm Lê Duy | Phó GĐ TT PV Hành chính công | 0327 208 848 |  |  |  |
| 25 | Phan Thị Thanh Nhã | GĐ TT Cung ứng sự nghiệp công | 0942 272 865 |  |  |  |
| 26 | Nguyễn Văn Bình | Phó GĐ TT Cung ứng sự nghiệp công | 0854 003 838 |  |  |  |

### XÃ THẠNH BÌNH

- Nhóm: 1
- Mã/STT nhóm: 73

### Đảng ủy Thạnh Bình - Địa chỉ: ấp Sân Bay, Thạnh Bình

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 1 | Đàm Văn Cường | Bí thư - CT HĐND | 0907 252 599 |  |  |  |
| 2 | Trần Thị Ánh Tuyết | Phó Bí thư - CT MTTQVN | 0987 049 049 |  |  |  |
| 3 | Nguyễn Văn Biên | UV BTV - CN UBKT, kiêm TB KT - HĐND | 0913 988 870 |  |  |  |
| 4 | Thái Hoàng Anh | UV BCH - PCN UBKT | 0918 297 232 |  |  |  |
| 5 | Lương Minh Hiếu | UV BTV - TB Xây dựng đảng, kiêm TB VHXH - HĐND | 0944 114 993 |  |  |  |
| 6 | Cao Hoàng Mạnh | UV BCH - PTB Xây dựng đảng | 0938 712 660 |  |  |  |
| 7 | Nguyễn Văn Nghĩa | UV BCH - CVP Đảng ủy | 0919 005 215 |  |  |  |
| 8 | Lê Kim Thủy | PCVP Đảng ủy | 0914 386 045 |  |  |  |
| 9 | Trần Thị Thu Thủy | UV BCH - PCT MTTQVN, CT Hội PN | 0389 288 388 |  |  |  |
| 10 | Nguyễn Văn Giàu | UV BCH - PCT MTTQVN, CT Hội ND | 0917 414 066 |  |  |  |
| 11 | Khưu Trọng Nghĩa | UV BCH - PCT MTTQVN, BT Đoàn TN | 0357 131 993 |  |  |  |
| 12 | Mai Hoàng Cầu | PCT MTTQVN, CT Hội CCB xã | 0977 204 362 |  |  |  |

### Hội đồng nhân dân xã Thạnh Bình - Địa chỉ: Ấp Thạnh Lợi, xã Thạnh Bình

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 13 | Trần Thị Mi Na | UV BTV - PCT HĐND | 0913 671 622 |  |  |  |
| 14 | Phạm Thị Thu Hồng | Phó Ban Kinh tế - HĐND | 0918 757 257 |  |  |  |
| 15 | Ngô Huỳnh Gấm | Phó Ban VHXH - HĐND | 0334 189 380 |  |  |  |

### UBND xã Thạnh Bình - ĐT bàn: 02763 740 120 ; email: ubndthanhbinh@tayninh.gov.vn

### Địa chỉ: Ấp Thạnh Lợi, xã Thạnh Bình

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 16 | Võ Hoàng Duy | Phó Bí thư - CT UBND | 0917 828 448 |  |  |  |
| 17 | Nguyễn Thanh Hùng | UV BTV - PCT UBND | 0888 412 039 |  |  |  |
| 18 | Lê Đỗ Thuận | UV BCH - PCT UBND, kiêm GĐ TT Hành chính Công | 0975 409 803 |  |  |  |
| 19 | Nguyễn Thị Thu Hiền | UV BCH - CVP HĐND và UBND | 0934 039 379 |  |  |  |
| 20 | Lại Hồng Phút | PCVP HĐND và UBND | 0386 164 703 |  |  |  |
| 21 | Phạm Văn Hùng | UV BCH - Trưởng phòng kinh tế | 0937 664 969 |  |  |  |
| 22 | Nguyễn Thị Phượng | PTP kinh tế | 0912 750 803 |  |  |  |
| 23 | Nguyễn Chí Bình | Chức vụ đảng - TP Văn hóa - Xã hội | 0949 170 942 |  |  |  |
| 24 | Hoàng CQuý | PTP Văn hóa - Xã hội | 0974 133 304 |  |  |  |
| 26 | Nguyễn Tri Phương | PGĐ TT Hành chính công | 0913 855 016 |  |  |  |
| 27 | Nguyễn Thị Oanh Thu | GĐ TT Cung ứng DVSN công | 0915 747 009 |  |  |  |
| 28 | Nguyễn Vân Cường | PGĐ TT Cung ứng DVSN công | 0918 658 404 |  |  |  |

### Công an Thạnh Bình - ĐT bàn: 02763 740 130 ; email:

### Địa chỉ: Ấp Thạnh Lợi, xã Thạnh Bình

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 29 | Nguyễn Thanh Bình | UV BTV - Trưởng Công an | 0917 173 686 |  |  |  |
| 30 | Võ Thị Bích Trâm | UV BCH - Phó trưởng Công an | 0797 478 585 |  |  |  |
| 31 | Ngô Hoàng Nam | Phó trưởng Công an | 0989 293 978 |  |  |  |
| 32 | Nguyễn Thế Giang | Phó trưởng Công an | 0917 113 600 |  |  |  |
| 33 | Nguyễn Văn Nam | Phó trưởng Công an | 0969 889 786 |  |  |  |
| 34 | Nguyễn Vũ Tuân Linh | Phó trưởng Công an | 0914 870 3710 |  |  |  |

### BCH Quân sự Thạnh Bình - ĐT bàn:………. ; email:

### Địa chỉ: Ấp Cầu, xã Thạnh Bình, Tây Ninh

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 35 | Nguyễn Văn Lâm | UV BTV - CHT BCH Quân sự | 0375 931 725 |  |  |  |

### XÃ TRÀ VONG

- Nhóm: 1
- Mã/STT nhóm: 74

### QL 22B, ấp Suối Đình, xã Trà Vong

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 1 | Kim Thị Minh | Bí thư Đảng ủy - CT HĐND xã | 0944125348 |  |  |  |
| 2 | Nguyễn Thị Thu Yên | Phó Bí thư Thường trực Đảng ủy | 0987 889 607 |  |  | QL 22B, ấp Suối Đình, xã Trà Vong |
| 3 | Đào Văn Sớt | Phó Bí thư - CT UBND | 0982 744 116 |  |  | QL 22B, ấp Thanh Hòa, xã Trà Vong |
| 4 | Phạm Thanh Danh | UV BTV - PCT UBND | 0973 732 737 |  |  | QL 22B, ấp Thanh Hòa, xã Trà Vong |
| 5 | Nguyễn Thanh Xuân | UV BTV - PCT HĐND | 0982 404 060 |  |  | QL 22B, ấp Thanh Hòa, xã Trà Vong |
| 6 | Lê Thị Hương | UV BTV - CN UBKT | 0933 486 801 |  |  | QL 22B, ấp Suối Đình, xã Trà Vong |
| 7 | Đồng Thanh Tùng | UV BTV - Trưởng Ban XD Đảng | 0913 343 738 |  |  | QL 22B, ấp Suối Đình, xã Trà Vong |
| 8 | Huỳnh Trung Dũng | UV BTV - Trưởng Công an | 0979 700 009 |  |  | ĐT781B, ấp Gò Đá, xã Trà Vong |
| 9 | Võ Văn Cảnh | UV BTV - CHT BCH QS xã |  |  |  | ĐT781B, ấp Gò Đá, xã Trà Vong |
| 10 | Trần Thị Hồng Minh | UV BCH - PCT UBND xã | 0975 332 877 |  |  | QL 22B, ấp Thanh Hòa, xã Trà Vong |
| 11 | Lê Văn Bài | UV BCH - Chánh văn phòng Đảng ủy | 0919 118 428 |  |  | QL 22B, ấp Suối Đình, xã Trà Vong |
| 12 | Nguyễn Thị Như Anh | UV BCH - CVP HĐND và UBND | 0918 859 485 |  |  | QL 22B, ấp Thanh Hòa, xã Trà Vong |
| 13 | Đặng Thanh Nghiêm | Đào Văn Sớt, Chủ tịch UBND xã | 0982 179 949 |  |  | QL 22B, ấp Thanh Hòa, xã Trà Vong |
| 14 | Nguyễn Thái Súng | UV BCH - Trưởng Phòng VH XH | 0908 043 789 |  |  | QL 22B, ấp Thanh Hòa, xã Trà Vong |
| 15 | Nguyễn Thanh Bình | UV BCH - PTB XD Đảng | 0904 477 222 |  |  | QL 22B, ấp Suối Đình, xã Trà Vong |
| 16 | Phạm Thị Huyền | UV BCH - Phó CN UBKT | 0915 377 469 |  |  | QL 22B, ấp Suối Đình, xã Trà Vong |
| 17 | Phạm Hoàng Thiện | UV BCH - BT Đoàn TN | 0913 884 722 |  |  | QL 22B, ấp Suối Đình, xã Trà Vong |
| 18 | Nguyễn Thanh Vàng | UV BCH - CT Hội ND | 0973 678 456 |  |  | QL 22B, ấp Suối Đình, xã Trà Vong |
| 19 | Nguyễn Thị Thúy Hằng | UV BCH - Chủ tịch Hội LHPN | 0938 909 555 |  |  | QL 22B, ấp Suối Đình, xã Trà Vong |
| 20 | Trần Định Quán | UV BCH - Phó Trưởng Công an | 0949 974 788 |  |  | ĐT781B, ấp Gò Đá, xã Trà Vong |
| 21 | Hồ Tấn Lực | Phó Chánh VP HĐND và UBND xã | 0909 449 232 |  |  | QL 22B, ấp Thanh Hòa, xã Trà Vong |
| 22 | Nguyễn Thị Trà Giang | Phó trưởng Phòng KT | 0976 521 387 |  |  | QL 22B, ấp Thanh Hòa, xã Trà Vong |
| 23 | Võ Văn Thái | Phó Trưởng Phòng VH XH | 0972 064 754 |  |  | QL 22B, ấp Thanh Hòa, xã Trà Vong |
| 24 | Nguyễn Thanh Thủy | PGĐ TT phục vụ HCC xã | 0983 444 154 |  |  | QL 22B, ấp Thanh Hòa, xã Trà Vong |
| 25 | Dương Thị Ánh | Giám đốc TT Cung ứng DVSNC xã | 0949 118 481 |  |  | QL 22B, ấp Thanh Hòa, xã Trà Vong |
| 26 | Đỗ Ngọc Sơn | PGĐ TT Cung ứng DVSNC | 0335 356 767 |  |  | QL 22B, ấp Thanh Hòa, xã Trà Vong |

### XÃ TÂN CHÂU

- Nhóm: 1
- Mã/STT nhóm: 75

#### Địa chỉ: số 217, đường Lê Duẩn, KP3, xã Tân Châu

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 1 | Trần Thị Thanh Hằng | Bí thư-CT.HĐND | 0977 806 551 | 3875 659 |  |  |
| 2 | Võ Thành Công | Phó Bí thư | 0917 791 091 |  |  |  |
| 3 | Nguyễn Việt Anh Thư | Phó Bí thư - CT UBND | 0902 828 077 |  |  |  |
| 4 | Phạm Vũ Tùng | UVBTV-TB xây dựng đảng xã | 0384 025 734 |  |  |  |
| 5 | Nguyễn Thị Thùy Dương | UVBTV-TB UBKT xã | 0333 503 577 |  |  |  |
| 6 | Nguyễn Hưng Thái Dương | UVBTV-PCT.HĐND | 0918 457 667 |  |  |  |
| 7 | Hoàng Bá Trình | UVBTV-PCT.UBND xã | 0919 058 076 |  |  |  |
| 8 | Vũ Đức Hải | UVBCH-PCT.UBND xã | 0908 317 557 |  |  |  |
| 9 | Nguyễn Xuân Tiến | UVBCH-Chánh Vp UBND-HĐND | 0911 924 488 |  |  |  |
| 10 | Nguyễn Thị Kim Dung | UVBCH-Trưởng phòng kinh tế | 0947 436 486 |  |  |  |
| 11 | Lê Trương Quỳnh Như | UVBCH-Trưởng phòng văn hóa - Xã hội | 0355 818 102 |  |  |  |
| 12 | Lê Thị Phương Thảo | UVBCH-Chánh Vp Đảng ủy | 0988 022 644 |  |  |  |
| 13 | Nguyễn Xuân Kha | UVBCH-GĐ TT Chính trị Tân Châu | 0909 019 036 |  |  |  |
| 14 | Đinh Thị Thu Trang | UVBCH-PTB Xây dựng đảng xã | 0902 871 422 |  |  |  |
| 15 | Nguyễn Thị Kim Xa | UVBCH-PTB UBKT xã | 0918 431 948 |  |  |  |
| 16 | Nguyễn Thị Thúy Hằng | UVBCH-PCT.MTTQ, CT. Hội PN | 0965 477 503 |  |  |  |
| 17 | Nguyễn CThức | UVBCH-PCT.MTTQ, CT Hội ND | 0984 123 586 |  |  |  |
| 18 | Cao Thị Loan Anh | UVBCH-PCT.MTTQ, BT ĐTN xã | 0985 548 590 |  |  |  |
| 19 | Nguyễn Thanh Ngọc | UVBTV-Trưởng Công an | 0913 678 642 |  |  |  |
| 20 | Bùi Văn Thanh | UVBCH-Phó trưởng Công an | 0908 055 551 |  |  |  |
| 21 | Phan Thế Chung | UVBTV- CHTB CH Quân sự | 0867 777 088 |  |  |  |
| 22 | Nguyễn Thành Thế | UVBCH-CH phó Ban CH Quân sự | 0968 174 717 |  |  |  |
| 23 | Nguyễn Thị Minh Nguyệt | GĐ TT CU dịch vụ sự nghiệp công | 0965 439 486 |  |  |  |
| 24 | Hoàng Thị Xuân | Phó GĐ TT phục vụ HCC | 0963 334 698 |  |  |  |

### XÃ TÂN ĐÔNG

- Nhóm: 1
- Mã/STT nhóm: 76

#### Ấp Tân Dũng, xã Tân Đông

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 1 | Nguyễn Thái Bình | Bí thư | 0908 969 693 | 02767 511 83 |  |  |
| 2 | Lê thoại Anh | Phó Bí thư - CT UBND | 0973 553 793 | 02763 751 126 |  | UBND xã Tân Đông: Tổ 16, ấp ĐTiến, xã Tân Đông |
| 3 | Nguyễn Đình Du | Phó BT Thường trực - CT UB.MTTQ | 0919 066 277 |  |  |  |
| 4 | Nguyễn Văn Thượng | Phó CT HĐND | 0888 220 394 |  |  |  |
| 5 | Nguyễn Thị Như Thơ | UV BTV - PCT UBND | 0385 703 718 |  |  |  |
| 6 | Cao Xuân Đức | UV BTV- Chủ nhệm UBKT Đảng ủy | 0988 515 151 |  |  |  |
| 7 | Võ Văn Hoa Vinh | UV BTV- TB Xây dựng Đảng | 0919 215 229 |  |  |  |
| 8 | Đặng Tuấn Anh | UV BTV- Trưởng Công an | 0909 456 588 |  |  |  |
| 9 | Hồ Thanh Nhật | UV BTV- CHT BCH QS | 0357 417 338 |  |  |  |
| 10 | Đinh Văn Minh | UV BCH - Chánh VP Đảng ủy | 0949 699 435 |  |  |  |
| 11 | Nguyễn Thanh Hải | UV BCH - Phó TB Xây dựng Đảng | 0983 935 566 |  |  |  |
| 12 | Nguyễn Đăng Hợp | UV BCH - Phó Chủ nhệm UBKT | 0949 044 025 |  |  |  |
| 13 | Lê Minh Nghĩa | UV BCH - Phó trưởng Công an | 0909 898 977 |  |  |  |
| 14 | Liêu Hồng Phong | UV BCH - Chánh VP HĐND- UBND | 0919 720 582 |  |  |  |
| 15 | Nguyễn Thị Huyền | UV BCH - Trưởng Phòng VH - XH | 0988 306 004 |  |  |  |
| 16 | Nguyễn Thị Nhung | UV BCH - Trưởng Phòng Kinh tế | 0972 672 654 |  |  |  |
| 17 | Quách Thị Tình | UV BCH - PCT MTTQ, CT Hội PN | 0964 001 427 |  |  |  |
| 18 | Nguyễn Sĩ Phú | UV BCH - PCT MTTQ, BT ĐTN | 0944 828 768 |  |  |  |
| 19 | Nguyễn Thanh Hồng | UV BCH - PCT MTTQ, CT Hội ND | 0988 810 133 |  |  |  |

### XÃ TÂN HÒA

- Nhóm: 1
- Mã/STT nhóm: 77

### Đảng ủy Tân Hòa - Địa chỉ: đường 794, ấp 2, xã Tân Hòa

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 1 | Lý Trung Đông | Bí thư | 0918 132 613 |  |  |  |
| 2 | Bùi Trọng Bình | Phó Bí thư | 0917 618 007 |  |  |  |
| 3 | Phạm Ngọc Phong | UV BTV - CN UBKT | 0949 584 466 |  |  |  |
| 4 | Đinh Văn Hiệp | UV BCH - PCN UBKT | 0977 453 742 |  |  |  |
| 5 | Nguyễn Văn Quyết | UV BTV - TB Xây dựng đảng | 0983 269 743 |  |  |  |
| 6 | Phạm An Thuận | UV BCH - PTB Xây dựng đảng | 0971 637 071 |  |  |  |
| 7 | Đỗ Thị Thanh Tuyền | UV BCH - CVP Đảng ủy | 0988 808 916 |  |  |  |
| 8 | Bùi Trọng Bình | Phó Bí thư - CT MTTQ xã | 0917 618 007 |  |  |  |
| 9 | Lê Thị Nhung | UV BCH - PCT MTTQ, CT Hội PN | 0986 172 956 |  |  |  |
| 10 | Nguyễn Văn Minh | UV BCH - PCT MTTQ, CT Hội ND | 0914 251 316 |  |  |  |
| 11 | Võ Tấn Đạt | UV BCH - PCT MTTQ, BT Đoàn TN | 0332 847 233 |  |  |  |
| 12 | Đỗ Ngọc Lưu | UV BCH - PCT MTTQ, CT Hội Cựu Chiến Binh | 0979 750 635 |  |  |  |

### HĐND Tân Hòa - Địa chỉ: đường 794, ấp 2, xã Tân Hòa

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 13 | Lý Trung Đông | Bí thư - CT HĐND | 0918 132 613 |  |  |  |
| 14 | Nguyễn Văn Quyết | UV BTV - TB Kinh tế - HĐND | 0983 269 743 |  |  |  |
| 15 | Phạm Ngọc Phong | UV BTV - TB VHXH - HĐND | 0949 584 466 |  |  |  |

### UBND xã Tân Hòa ; email: ubndtanhoa@tayninh.gov.vn / Địa chỉ: đường 794, ấp 2, xã Tân Hòa

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 16 | Nguyễn Văn Lai | Phó Bí thư - CT UBND | 0983 063 064 |  |  |  |
| 17 | Vũ Văn Minh | UV BTV - PCT UBND | 0973 344 333 |  |  |  |

#### 18

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 19 | Nguyễn Thanh Tùng | UV BCH - CVP HĐND và UBND | 0947 050 691 |  |  |  |

#### 20

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 21 | Lương Hiền Thảo | UV BCH - Trưởng phòng kinh tế | 0986 352 339 |  |  |  |

#### 22

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 23 | Nguyễn Văn Trọng | UV BCH - TP Văn hóa - Xã hội | 0943 032 152 |  |  |  |

#### 24

#### 25

#### 26

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 27 | Nguyễn Như Ty | GĐ TT Cung ứng DVSN công | 0949 043 986 |  |  |  |

#### 28

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 29 | Nguyễn Duy Tân | UV BTV - Trưởng Công an | 0974 549 162 |  |  |  |
| 30 | Nguyễn Văn Hạnh | UV BCH Phó trưởng Công an | 0989 225 113 |  |  |  |
| 31 | Nguyễn Hoàng Minh | Phó trưởng Công an | 0911 700 399 |  |  |  |
| 32 | Dương Hoàng Quốc | Phó trưởng Công an | 0948 845 392 |  |  |  |
| 33 | Nguyễn Thanh Dương | Phó trưởng Công an | 0987 864 757 |  |  |  |
| 34 | Nguyễn Văn Phương | Phó trưởng Công an | 0913 884 863 |  |  |  |
| 31 | Nguyễn Thanh Tâm | UV BTV - CHT BCH Quân sự | 0962 311 852 |  |  |  |

### XÃ TÂN HỘI

- Nhóm: 1
- Mã/STT nhóm: 78

### Đảng ủy - Địa chỉ: ĐT.785, ấp Thạnh An, xã Tân Hội

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 1 | Lê Anh Tâm | Bí thư | 0933 774 357 |  |  |  |
| 2 | Nguyễn Xuân Chiến | Phó Bí thư | 0984 268 669 |  |  |  |
| 3 | Hoàng Văn Hữu | UV BTV - CN UBKT | 0971 505 051 |  |  |  |
| 4 | Nguyễn Văn Thường | UV BCH - PCN UBKT | 0969 656 151 |  |  |  |
| 5 | Đinh Thị Ngọc Thu | UV BTV - TB Xây dựng đảng | 0986 340 352 |  |  |  |
| 6 | Nguyễn Minh Dương | UV BCH - PTB Xây dựng đảng | 0979 139 005 |  |  |  |
| 7 | Thân Đặng Quang Sang | UV BCH - CVP Đảng ủy | 0918 239 446 |  |  |  |
| 8 | Nguyễn Xuân Chiến | Phó Bí thư thường trực - CT MTTQ | 0984 268 669 |  |  |  |
| 9 | Đoàn Thanh Minh | UV BCH - PCT MTTQ, CT Cđoàn xã | 0814 400 885 |  |  |  |
| 10 | Trần Khánh Dư | UV BCH - PCT MTTQ, CT Hội ND | 0978 285 628 |  |  |  |
| 11 | Nguyễn Văn Hưng | UV BCH - PCT MTTQ, BT Đoàn TN | 0963 314 424 |  |  |  |
| 12 | Lý Thị Mỹ Diệu | UV BCH - PCT MTTQ, CT Hội PN | 0985 586 895 |  |  |  |
| 13 | Lê Tân Tiến | PCT MTTQ, CT Hội CCB | 0983 487 278 |  |  |  |

### Hội đồng nhân dân - Địa chỉ: ĐT.785, ấp Hội An, xã Tân Hội

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 14 | Lê Anh Tâm | Bí thư - CT HĐND | 0933 774 357 |  |  |  |
| 15 | Võ Thị Ngọc Hân | UV BTV - PCT HĐND | 0977 402 605 |  |  |  |
| 16 | Đinh Thị Ngọc Thu | UV BTV - CN UBKT - TB Kinh tế - HĐND | 0986 340 352 |  |  |  |
| 17 | Nguyễn Minh Đức | PTB Kinh tế - HĐND | 0336 855 152 |  |  |  |
| 18 | Hoàng Văn Hữu | UV BTV - CN UBKT - TB VHXH - HĐND | 0971 505 051 |  |  |  |
| 18 | Vũ Thị Phương Lan | PTB VHXH - HĐND | 0944 411 185 |  |  |  |

### UBND xã - ĐT bàn: 02763 751 028; email: ubndtanhoi@tayninh.gov.vn

### Địa chỉ: ĐT.785, ấp Hội An, xã Tân Hội

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 19 | Nguyễn Thị Phượng | Phó Bí thư - CT UBND | 0919 995 458 |  |  |  |
| 20 | Trương Thị Thu Trang | UV BTV - PCT UBND | 0779 402 605 |  |  |  |
| 21 | Đỗ Minh Triệu | UV BCH - PCT UBND | 0912 847 600 |  |  |  |
| 22 | Hoàng CTụy | UV BCH - CVP HĐND và UBND | 0975 261 057 | 02763 751 028 |  |  |
| 23 | Danh Ngọc Ảnh | UV BCH - Trưởng phòng kinh tế | 0908 253 787 |  |  |  |
| 24 | Trần Tấn Sung | UV BCH - TP Văn hóa - Xã hội | 0913 194 381 |  |  |  |
| 25 | Đỗ Minh Triệu | GĐ TT Hành chính công | 0912 847 600 |  |  |  |
| 26 | Lâm Quang Hiền | GĐ TT Cung ứng DVSN công | 0983 512 352 |  |  |  |
| 27 | Trần Văn Lam | UV BTV - Trưởng Công an | 0977 348 477 |  |  |  |
| 28 | Hà Quốc Cường | UV BCH - Phó trưởng Công an | 0977 141 484 |  |  |  |
| 29 | Nguyễn Hoài Nam | UV BTV - CHT BCH Quân sự | 0987 950 535 |  |  |  |

### XÃ TÂN PHÚ

- Nhóm: 1
- Mã/STT nhóm: 79

### Đảng ủy Tân Phú - Địa chỉ: ấp Tân Hòa, xã Tân Phú

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 1 | Nguyễn Thị Thu Vân | Bí thư | 0906 821 976 |  |  |  |
| 2 | Phan Thị Mỹ Trinh | Phó Bí thư - CT MTTQ xã | 0982 905 518 |  |  |  |
| 3 | Nguyễn Mạnh Hải | UV BTV - CN UBKT | 0919 598 184 |  | manhhai1979@tayninh.gov.vn |  |
| 4 | Trương Thị Hây | UV BCH - PCN UBKT | 0916 686 282 |  |  |  |
| 5 | Nguyễn Thụy Phương Quyên | UV BTV - TB Xây dựng đảng | 0936 482 757 |  | phuongquyen1983@tayninh.gov.vn |  |
| 6 | Phạm Văn Cường | UV BCH - PTB Xây dựng đảng | 0977 112 434 |  |  |  |
| 7 | Lê Thị Ngọc Thúy | UV BCH - CVP Đảng ủy | 0976 484 144 |  |  |  |
| 9 | Lê Thị Ry | UV BCH - PCT MTTQ, CT Hội PN | 0947 753 536 |  |  |  |
| 10 | khuyết | UV BCH - PCT MTTQ, CT Hội ND |  |  |  |  |
| 11 | Đỗ Đình Tánh | UV BCH - PCT MTTQ, BT Đoàn TN | 0384 998 809 |  |  |  |

### Hội đồng nhân dân xã Tân Phú - Địa chỉ: ấp Tân Tây, xã Tân Phú

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 13 | Nguyễn Thị Thu Vân | Bí thư - CT HĐND | 0906 821 976 |  |  |  |

#### Hồ Khánh Dung

- Chức vụ/ghi chú: UV BTV - PCT HĐND
- Di động: 0913 955 983
- Điện thoại cơ quan: 02763 753 824
- Email: khanhdung1981@tayninh.gov.vn

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 14 | Nguyễn Minh Hùng | Ban Kinh tế - HĐND | 0937137554 |  | minhhung1983@tayninh.gov.vn |  |
| 15 | Trần Hoàng Dưỡng | Ban VHXH - HĐND | 0978159758 |  | hoangduong1983@tayninh.gov.vn |  |

### UBND xã Tân Phú - ĐT bàn: 02763 753 824 ; email: ubnd….@tayninh.gov.vn / Địa chỉ: ấp Tân Tây, xã Tân Phú

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 16 | Trần Văn Cương | Phó Bí thư - CT UBND | 0969 635 179 | 02763 753 824 | vancuong1981@tayninh.gov.vn |  |
| 17 | Nguyễn Hoàng Vũ | UVBTV - PCT UBND | 0918 431 396 | 02763 753 824 | hoangvu1980@tayninh.gov.vn |  |
| 18 | Nguyễn Thị Kiều Oanh | UV BCH - PCT UBND | 0982 516 661 | 02763 753 824 | kieuoanh1977@tayninh.gov.vn |  |
| 19 | Mai Thị Kim Thanh | UV BCH - CVP HĐND và UBND | 0973 809 199 | 02763 753 824 | kimthanh1981@tayninh.gov.vn |  |
| 20 | khuyết | PCVP HĐND và UBND |  |  |  |  |
| 21 | Phan Thị Huyền Linh | UV BCH - Trưởng phòng kinh tế | 0977 050 346 | 02763 753 824 | huyenlinh1983@tayninh.gov.vn |  |
| 22 | khuyết | PTP kinh tế |  |  |  |  |
| 23 | Nguyễn Tuấn Sinh | UV BCH - TP Văn hóa - Xã hội | 0977 977 622 | 02763 753 824 | tuansinh1984@tayninh.gov.vn |  |
| 24 | khuyết | PTP Văn hóa - Xã hội |  |  |  |  |
| 25 | Nguyễn Thị Kiều Oanh | GĐ TT Hành chính công | 0982 516 661 | 02763 753 824 | kieuoanh1977@tayninh.gov.vn |  |
| 26 | Lưu Thị Dịu | PGĐ TT Hành chính công | 0385 837 570 | 02763 753 824 | thidiu1989@tayninh.gov.vn |  |
| 27 | Hà Thị Huệ | GĐ TT Cung ứng DVSN công | 0987 626 473 |  | thihue1974@tayninh.gov.vn |  |
| 28 | khuyết | PGĐ TT Cung ứng DVSN công |  |  |  |  |
| 29 | Ngô Trường An | UVBTV - Trưởng Công an | 0929 399 699 | 02763 753 236 |  |  |
| 30 | Thiệu Văn Việt | Phó trưởng Công an | 0947 153 307 | 02763 753 236 |  |  |
| 31 | Võ Quang Sang | UV BTV - CHT BCH Quân sự | 0973 878 270 | 02763 759 432 |  |  |

### XÃ TÂN THÀNH

- Nhóm: 1
- Mã/STT nhóm: 80

### Đảng ủy Tân Thành - Địa chỉ: 45, Đường 795, Ấp 4, xã Tân Thành, Tây Ninh

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 1 | Nguyễn Thị Trúc Mai | Bí thư | 0987 408 841 | 02763 752 966 |  |  |
| 2 | Nguyễn Thị Kim Ngọc | Phó Bí thư | 0987 205 207 |  | ngocntk1@tayninh.gov.vn |  |
| 3 | Trần Hồng Chánh | UV BTV - CN UBKT | 0917 877 775 |  | hongchanh1980@tayninh.gov.vn |  |
| 4 | Nguyễn Thanh Cường | UV BCH - PCN UBKT | 0908 035 121 |  |  |  |
| 5 | Võ Thị Thu Sương | UV BTV - TB Xây dựng đảng | 0399 778 891 |  | thusuong1984@tayninh.gov.vn |  |
| 6 | Dương Thị Vất | UV BCH - PTB Xây dựng đảng | 0834 004 757 |  |  |  |
| 7 | Hà Huy Châu | UV BCH - CVP Đảng ủy | 0982 752 836 |  |  |  |
| 8 | Lê Hữu Phúc | Phó Bí thư - CT MTTQ | 0919 137 757 |  |  |  |
| 9 | Phạm Thị Kim Hoàng | UV BCH - PCT MTTQ, CT Hội PN | 0988 944 333 |  |  |  |
| 10 | Phan Văn The | UV BCH - PCT MTTQ, CT Hội ND | 0972 964 829 |  |  |  |
| 11 | Nguyễn Hoài Thuơng | UV BCH - PCT MTTQ, BT Đoàn TN | 0986 253 022 |  |  |  |
| 12 | Thái Minh Nhựt | UV BCH - PCT MTTQ, CT Hội CCB | 0987 846 792 |  |  |  |

### HĐND Tân Thành - Địa chỉ:45, Đường 795, Ấp 4, xã Tân Thành, Tây Ninh

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 13 | Nguyễn Thị Trúc Mai | Bí thư - CT HĐND | 0987 408 841 |  |  |  |
| 14 | Lê Chí Thời | PCT HĐND | 0984 543 774 |  | thoilc@tayninh.gov.vn |  |
| 15 | Nguyễn Thị Hường | Ban Kinh tế - HĐND | 0947 844 140 |  | thihuong1982@tayninh.gov.vn |  |
| 16 | Hồ Thị Duyên | Ban VHXH - HĐND | 0982 100 244 |  | thiduyen1975@tayninh.gov.vn |  |

### UBND xã Tân Thành- ĐT bàn: 02763 752 295; email: ubnd….@tayninh.gov.vn / 45, Đường 795, Ấp 4, xã Tân Thành, Tây Ninh

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 17 | Nguyễn Thị Kim Ngọc | Phó Bí thư - CT UBND | 0987 205 207 |  | ngocntk1@tayninh.gov.vn |  |
| 18 | Trần Hữu Tiến | - PCT UBND | 0942 391 215 |  | huutien@tayninh.gov.vn |  |
| 19 | Đoàn Thị Ngọc Trâm | - CVP HĐND và UBND | 0986 228 996 |  | dtntram@tayninh.gov.vn |  |
| 20 | Nguyễn Hữu Hoà | - Trưởng phòng kinh tế | 0937 804 186 |  | huuhoa1986@tayninh.gov.vn |  |
| 21 | Trần Đình Thi | - TP Văn hóa - Xã hội | 0971 865 353 |  | thitd@tayninh.gov.vn |  |
| 22 | Trần Hữu Tiến | GĐ TT Hành chính công | 0942 391 215 |  | huutien@tayninh.gov.vn |  |
| 23 | Đặng Ngọc Nam | PGĐ TT Hành chính công | 0986 303 364 |  | ngocnam1983@tayninh.gov.vn |  |
| 24 | Trịnh Đình Hà | GĐ TT Cung ứng DVSN công | 0974 642 067 |  | dinhha1986@tayninh.gov.vn |  |
| 25 | Lại Văn Tới | - Trưởng Công an | 0911 975 337 |  |  |  |
| 26 | Võ Thị Thùy Trang | Phó trưởng Công an | 0973 716 679 |  |  |  |
| 27 | Lê Bá Hân | Phó trưởng Công an | 0982 195 977 |  |  |  |
| 28 | Ngô Đức Trọng | Phó trưởng Công an | 0984 519 883 |  |  |  |
| 29 | Phạm Tuấn Kiệt | Phó trưởng Công an | 0977 393 878 |  |  |  |
| 30 | Nguyễn Đình Tám | Phó trưởng Công an | 0945 060 992 |  |  |  |
| 31 | Nguyễn Thanh Hoàng | - CHT BCH Quân sự | 0968 781 139 |  |  |  |

### XÃ HƯNG THUẬN

- Nhóm: 1
- Mã/STT nhóm: 81

#### ĐẢNG ỦY - MTTQ XÃ HƯNG THUẬN:

#### Địa chỉ: Đường 789 ấp Bùng Binh, xã Hưng Thuận

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 1 | Hà Minh Dảo | Bí thư Đảng ủy-CTHĐND | 0913 137 084 |  |  |  |
| 2 | Nguyễn Thanh Hải | Phó BT Thường trực-CT.MTTQ | 0917 445 579 |  |  |  |
| 4 | Trần Quang Minh | UV.BTV-Trưởng Ban Xây dựng Đảng | 0989 079 116 |  |  |  |
| 5 | Phạm Văn Sĩ | UV.BTV-CN.UBKT Đảng ủy | 0915 435 292 |  |  |  |
| 6 | Phạm Văn Hà | UV.BCH-PTB Xây dựng Đảng | 0979 792 333 |  |  |  |
| 7 | Ngô Văn Dố | UV.BCH-Phó CN.UBKT Đảng ủy | 0985 229 923 | Trưởng phòng VHTT |  |  |
| 8 | Đặng Hoàng Vỹ | UV.BCH-Chánh VP Đảng ủy | 0961 230 153 |  |  |  |
| 9 | Nguyễn Thanh Bình | UV.BCH,PCT.UBMTTQ đồng thời BT xã đoàn | 0913 179 192 |  |  |  |
| 10 | Đỗ Thị Thúy An | UV.BCH,PCT.UBMTTQ, CTHLHPN xã | 0918 511 255 |  |  |  |
| 11 | Nguyễn Quốc Quân | UV.BCH,PCT.UBMTTQ đồng thời CTHND | 0909 490 282 |  |  |  |

#### HĐND XÃ HƯNG THUẬN:

#### Địa chỉ: Đường 789 ấp Sóc Lào, xã Hưng Thuận

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 12 | Tô Thanh Tài | UV. BTV - Phó CT.HĐND | 0918 669 887 |  |  |  |
| 13 | Nguyễn Văn Hưng | Phó Ban KTNSHĐND | 0969 898 454 |  |  |  |
| 14 | Lê Minh Tấn | Phó Ban VH-XH.HĐND | 0986 552 191 |  |  |  |

#### UBND XÃ HƯNG THUẬN:

#### Địa chỉ: Đường 789 ấp Sóc Lào, xã Hưng Thuận

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 15 | Đặng Thị Ngọc Hà | Phó Bí thư - CT UBND | 0946 888 419 |  |  |  |
| 16 | Ngô Thị Ngọc Lý | UV. BTV - PCT UBND-GĐTTPVHCC | 0917 462 898 |  |  |  |
| 17 | Trần Văn Thi | UV. BTV - Trưởng Công an | 0913 884 652 |  |  |  |
| 18 | Nguyễn Hoàng Trọng | UV. BTV - BCHQS xã | 0918 119 712 |  |  |  |
| 19 | Nguyễn Công Đoàn | UV.BCH-Phó CT UBND xã | 0918 722 818 |  |  |  |
| 20 | Nguyễn Hữu Tâm | UV.BCH-Chánh VP UBND | 0937 783 123 |  |  |  |
| 21 | Phan Văn Tuấn | UV.BCH-Trưởng Phòng VH-XH | 0946 704 747 | Chuyển công tác |  |  |
| 22 | Nguyễn Hoàng Anh | UV.BCH-Trưởng Phòng kinh tế | 0902 412 149 |  |  |  |
| 23 | Lê Nguyên Soái | UV.BCH,Phó Trưởng Công an | 0919 868 892 |  |  |  |
| 24 | Nguyễn Vương Phương Thảo | Phó GĐTTCUDVC | 0937 338 619 |  |  |  |
| 25 | Nguyễn Thị Hồng | Phó GĐTTPVHCC | 0937 511 203 |  |  |  |
| 26 | Nguyễn Thị Kim Hạnh | Phó Chánh VP UBND | 0907 358 458 |  |  |  |
| 27 | Bùi Văn Quý | Phó Trưởng Công an | 0937 200 060 |  |  |  |
| 28 | Trần Thị Hờ | Phó Trưởng Công an | 0919 215 467 |  |  |  |
| 29 | Trần Trung Hiếu | Phó Trưởng Công an | 0901 537 294 |  |  |  |
| 30 | Nguyễn Văn Tú | Phó Trưởng Công an | 0981 049 379 |  |  |  |

### XÃ PHƯỚC CHỈ

- Nhóm: 1
- Mã/STT nhóm: 82

### Đảng ủy xã Phước Chỉ - Địa chỉ: ấp Phước Đông, xã Phước Chỉ

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 1 | Nguyễn Thanh Cường | Bí thư Đảng ủy | 0908 310 090 |  |  |  |
| 2 | Nguyễn Văn Ngách | Phó Bí thư thường trực - CT UBMTTQVN Xã | 0913 133 883 |  |  |  |
| 3 | Nguyễn Tuấn Thanh | UV BTV - Chủ nhiệm UBKT ĐU xã | 0932 129 578 |  |  |  |
| 4 | Trịnh Minh Phước | UV BCH - Phó Chủ nhiệm UBKTĐU xã | 0917 948 852 |  |  |  |
| 5 | Lê Thị Ngọc Lan | UV BTV - TB Xây dựng đảng | 0919 470 467 |  |  |  |
| 6 | Bùi Văn Riêng | UV BCH - PTB Xây dựng đảng | 0933 624 112 |  |  |  |
| 7 | Võ Công Nhân | UV BCH - CVP Đảng ủy xã | 0386 677 121 |  |  |  |
| 8 | Nguyễn Văn Ngách | PBT TT - CT MTTQ xã | 0913 133 883 |  | PBT thường trực kiêm nhiệm |  |
| 9 | Thi Thị Bé Loan | UV BCH - PCT MTTQ, CT Hội PN | 0979 305 848 |  |  |  |
| 10 | Nguyễn Viết Kiên | UV BCH - PCT MTTQ, CT Hội ND | 0916 386 192 |  |  |  |

#### 11

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 12 | Hồ Văn Trường | PCT MTTQ, CT Hội CCB | 0939 259 171 |  |  |  |

### HĐND xã Phước Chỉ - Địa chỉ: ấp Bình Hòa, xã Phước Chỉ

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 13 | Nguyễn Thanh Cường | BÍ THƯ - CT HĐND | 0908 310 090 |  |  |  |
| 14 | Dương Nguyễn Vũ Hải | UVBTV PCT HĐND | 0909 831 635 |  |  |  |
| 15 | Nguyễn Tuấn Thanh | UV BTV Trưởng Ban Kinh tế - HĐND | 0932 129 578 |  |  |  |
| 16 | Nguyễn Minh Vương | Phó Trưởng Ban Kinh tế - HĐND | 0975 882 112 |  |  |  |
| 17 | Lê Thị Ngọc Lan | UV BTV Trưởng Ban VHXH - HĐND | 0919 470 467 |  |  |  |
| 18 | Nguyễn Văn Sim | Phó Trưởng Ban VHXH - HĐND | 0935 150 580 |  |  |  |

### UBND xã - ĐT bàn: …... ; email: ubndphuocchi@tayninh.gov.vn

### Địa chỉ: ấp Bình Hòa, xã Phước Chỉ

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 19 | Bùi Tiến Thành | Phó Bí thư - CT UBND | 0948 730 208 |  |  |  |
| 20 | Trần Minh Tùng | UV BTV - PCT UBND | 0888 661 914 |  |  |  |
| 21 | Trần Thiện Thông | UV BCH - PCT UBND | 0984 989 553 |  |  |  |
| 22 | Đặng Thụy Khánh Ly | UV BCH - CVP HĐND và UBND xã | 0944 317 347 |  |  |  |
| 23 | Biện Duy Thanh | PCVP HĐND và UBND xã | 0903 439 138 |  |  |  |
| 24 | Lê Thanh Dương | UV BCH - Trưởng phòng kinh tế xã | 0918 226 669 |  |  |  |

#### 25

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 26 | Trần Bùi Thúy Loan | UV BCH - TP Văn hóa - Xã Hội xã | 0903 018 856 | ABC |  |  |
| 27 | Bùi Văn Tâm | PTP Văn hóa - Xã Hội xã | 0974 524 717 |  |  |  |
| 28 | Trần Minh Tùng | Phó Chủ tịch Ủy ban nhân dân xã / kiêm GĐ TT Hành chính công | 0888 661 914 |  |  |  |

#### 29

#### 30

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 31 | Nguyễn Phước Nhiên | PGĐ TT Cung ứng DVSN công | 0909 391 560 |  |  |  |
| 32 | Trịnh Xuân Cẩn | UV BTV - Trưởng Công an xã | 0976 344 329 |  |  |  |
| 33 | VõHoàng Để | UV BCH - Phó trưởng Công an xã | 0972 666 452 |  |  |  |
| 34 | Nguyễn Khánh Đăng | Phó trưởng Công an xã | 0917 399 292 |  |  |  |
| 35 | Nguyễn Hồng Hà | Phó trưởng Công an xã | 0918 288 337 |  |  |  |
| 36 | Nguyễn Thành Lợi | Phó trưởng Công an xã | 0944 389 767 |  |  |  |
| 37 | Nguyễn Trần Vũ | Phó trưởng Công an xã | 0916 770 876 |  |  |  |
| 38 | Nguyễn Trung Thành | UB BTV - CHT Ban CHQS xã | 0966 495 777 |  |  |  |

### XÃ BẾN CẦU

- Nhóm: 1
- Mã/STT nhóm: 83

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 1 | Phan Văn Hoà | Bí thư Đảng uỷ, Chủ tịch HĐND | 0918 138 954 |  |  |  |
| 2 | Hoàng Thị Thu Hiền | Phó Bí thư Thường trực Đảng uỷ | 0866 133 113 |  |  |  |
| 3 | Hồ Võ Thái Bình | Phó Bí thư Đảng uỷ, Chủ tịch Uỷ ban nhân dân xã. | 0834 932 101 |  |  |  |
| 4 | Trịnh Văn Đồng | UVBTV Đảng uỷ, PCT Uỷ ban nhân dân | 0913 107 476 |  |  |  |
| 5 | Nguyễn Thúy Tâm | UVBTV Đảng uỷ, TB Xây dựng Đảng. | 0983 633 652 |  |  |  |
| 6 | Trần Thị Bích Liên | UVBTV Đảng uỷ, CN UBKT Đảng uỷ. | 0913 637 524 |  |  |  |
| 7 | Trần Thị Ngọc Trinh | UVBTV Đảng uỷ, PCT HĐND | 0947 878 729 |  |  |  |
| 8 | Nguyễn Ngọc Quỳnh Thư | UVBTV Đảng uỷ, PCT Uỷ ban nhân dân, Kiêm GĐ TTPVHCC | 0975 045 252 |  |  |  |
| 9 | Lê Hoàng Quy | UVBTV Đảng uỷ, Chủ tịch MTTQ Việt Nam xã. | 0984 657 890 |  |  |  |
| 10 | Lê Thị Phương Nam | UVBTV Đảng uỷ, Trưởng Công an | 0908 527 857 |  |  |  |
| 11 | Trần Minh Tâm | UVBTV Đảng uỷ, Chỉ huy TB chỉ huy Quân sự | 0395 916 377 |  |  |  |
| 12 | Lê Thị Diễm | UVBCH Đảng bộ, CVP Đảng ủy | 0946 611 284 |  |  |  |
| 13 | Lê Diệu Linh | UVBCH Đảng bộ, GĐ TTCT | 0835 923 092 |  |  |  |
| 14 | Ngô Hoàng Minh | UVBCH Đảng bộ, PTB Xây dựng Đảng | 0949 969 333 |  |  |  |
| 15 | Nguyễn Kim Ngân | UVBCH Đảng bộ, PCN Uỷ Ban Kiểm tra Đảng uỷ. | 0379 740 667 |  |  |  |
| 16 | Phan Thị Thanh Nhàn | UVBCH Đảng bộ, PCT MTTQ (Phụ trách HPN) | 0979 286 705 |  |  |  |
| 17 | Trần Diễm Phúc | UVBCH Đảng bộ, PCT MTTQ (Phụ trách Đoàn Thanh niên) | 0393 395 071 |  |  |  |
| 18 | Nguyễn Thái Bình | UVBCH Đảng bộ, PCT MTTQ (Phụ trách HND) | 0387 299 290 |  |  |  |
| 19 | Trần Văn Tèo | UVBCH Đảng bộ, PCT MTTQ (Phụ trách Liên đoàn LĐ) | 0919 542 754 |  |  |  |
| 20 | Đặng CDanh | UVBCH Đảng bộ, Phó trưởng Công an | 0919 006 792 |  |  |  |
| 21 | Trần Nam Biên | UVBCH Đảng bộ, Phó Chỉ huy TB Chỉ huy Quân sự | 0385 608 745 |  |  |  |
| 22 | Nguyễn Thành Văn | UVBCH Đảng bộ, CVP HĐND&UBND xã | 0388 559 028 |  |  |  |
| 23 | Huỳnh Thị Thuỳ Trang | P.CVP HĐND&UBND xã | 0918 850 133 |  |  |  |
| 24 | Võ Thành Hưng | UVBCH Đảng bộ, Trưởng phòng VH-XH | 0918 204 231 |  |  |  |
| 25 | Lê Hồng Phong | P.Trưởng phòng VH-XH | 0917 627 792 |  |  |  |
| 26 | Đỗ Quang Trường | UVBCH Đảng bộ, Trưởng phòng Kinh tế | 0889 558 588 |  |  |  |
| 27 | Trần Minh Cường | P.Trưởng phòng Kinh tế | 0909 722 157 |  |  |  |
| 28 | Trần Ngọc Phương | Phó GĐ TT Phục vụ hành chính công | 0988 205 301 |  |  |  |

### XÃ LONG THUẬN

- Nhóm: 1
- Mã/STT nhóm: 84

#### I. Ban chấp hành Đảng ủy Long Thuận

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 1 | Nguyễn Tuấn Khanh | Bí thư-CT HĐND | 0907 680 505 |  |  |  |
| 2 | Trần Hải Sơn | Phó Bí thư TT | 0917 418 266 |  |  |  |
| 3 | Nguyễn Thị Mai | Phó Bí thư-CT UBND | 0918 567 157 |  |  |  |
| 4 | Nguyễn Thái Bảo | UV BTV-TB XDĐ | 0911 779 099 |  |  |  |
| 5 | Ngô Hoàng Cương | UV BTV-CN UBKT | 0918 556 248 |  |  |  |
| 6 | Phạm Hồng Hiển | UV BTV-CT UBMTTQ | 0918 380 749 |  |  |  |
| 7 | Nguyễn Hoài Phương | UV BTV-PCT HĐND | 0967 118 092 |  |  |  |
| 8 | Đỗ Hoàng Khải | UV BTV-PCT UBND | 0919 014 572 |  |  |  |
| 9 | Trần Thị Tánh | UV BTV-PCT UBND | 0919 542 657 |  |  |  |
| 10 | Võ Minh Trung | UV BTV-Trưởng CA | 0907 108 679 |  |  |  |
| 11 | Nguyễn Văn Bình (QS) | UV BTV-CHT BCHQS | 0949 043 666 |  |  |  |
| 12 | Đặng Hồng Anh | UV BCH -CVP Đảng ủy | 0837 834 837 |  |  |  |
| 13 | Trần Minh Kha | UV BCH -PTB Xây dựng Đảng | 0909 113 144 |  |  |  |
| 14 | Nguyễn Văn Đạt | UV BCH -PCN UBKT | 0989 350 352 |  |  |  |
| 15 | Võ Thị Thanh | UV BCH -CVP HĐND và UBND | 0979 783 344 |  |  |  |
| 16 | Nguyễn Văn Hướng | UV BCH -Trưởng Phòng KT | 0977 473 783 |  |  |  |
| 17 | Nguyễn Văn Bình (P.VH-XH) | UV BCH -Trưởng PVH | 0986 714 627 |  |  |  |
| 18 | Đặng Minh Khai | UV BCH -Phó Trưởng Công an | 0944 222 232 |  |  |  |
| 19 | Phan Văn Việt | UV BCH - PCT MTTQ, BT Đoàn TN | 0865 770 252 |  |  |  |
| 20 | Trịnh Thị Ngọc Quí | UV BCH - PCT MTTQ, CT Hội PN | 0977 940 049 |  |  |  |
| 21 | Lê Văn Rang | UV BCH - PCT MTTQ, CT Hội ND | 0915 360 768 |  |  |  |

#### II. Cấp phó của các phòng, TT thuộc UBND xã

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 1 | Bùi Thanh Phương | PGĐ TT phục vụ hành chính công | 0938 118 654 |  |  |  |
| 2 | Hồ Thanh Hải | PTP VHXH | 0986 658 330 |  |  |  |
| 3 | Trần Văn Cương | PTP Kinh tế | 0909 884 223 |  |  |  |
| 4 | Võ Minh Thảo | Phó CVP HĐND và UBND | 986544064 |  |  |  |

### XÃ LONG CHỮ

- Nhóm: 1
- Mã/STT nhóm: 85

### Đảng ủy Long Chữ - Địa chỉ: ấp Long Châu, xã Long Chữ

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 1 | Nguyễn Thị Thúy Nga | Bí thư | 933060365 |  |  |  |
| 2 | Lưu Hữu Phước | Phó Bí thư | 842523979 |  |  |  |
| 3 | Hồ Thanh Tuấn | UV BTV - CN UBKT | 947208955 |  |  |  |
| 4 | Trần Phương Tùng | UV BCH - PCN UBKT | 917477815 |  |  |  |
| 5 | Trần Văn Thành | PCN UBKT | 834747459 |  |  |  |
| 6 | Nguyễn Thị Kim Tuyến | UV BTV - TB Xây dựng đảng | 944316613 |  |  |  |
| 7 | Lê Minh Hoàng | UV BCH - PTB Xây dựng đảng | 919025777 |  |  |  |
| 8 | Châu Khắc Khoa | UV BCH - CVP Đảng ủy | 399153431 |  |  |  |
| 9 | Dương Hòa Nhã | Phó CVP Đảng ủy | 972423082 |  |  |  |
| 10 | Huỳnh Thiện Khiêm | UV BTV - CT MTTQ xã | 964566844 |  |  |  |
| 11 | Trần Thị Bé Ngoan | UV BCH - PCT MTTQ, CT Hội PN | 386534850 |  |  |  |
| 12 | Phạm Văn Phú | UV BCH - PCT MTTQ, CT Hội ND | 971700792 |  |  |  |
| 13 | Đặng Thị Hiếu Ngọc | UV BCH - PCT MTTQ, BT Đoàn TN | 976911457 |  |  |  |
| 14 | Đỗ Văn Sẽ | PCT MTTQ, CT Hội CCB | 976170222 |  |  |  |

### HĐND Long Chữ - Địa chỉ: ấp Long Hoà, xã Long Chữ

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 15 | Nguyễn Thị Thúy Nga | Bí Thư Đảng uỷ - CT HĐND | 933060365 |  |  |  |
| 16 | Đỗ Kim Hoà | UV BTV - Phó CT.HĐND | 944397797 |  |  |  |
| 17 | Hồ Thanh Tuấn | TB Kinh tế ngân sách- HĐND | 947208955 |  |  |  |
| 18 | Trần Chì | Phó Ban Kinh tế ngân sách- HĐND | 985648864 |  |  |  |
| 19 | Nguyễn Thị Kim Tuyến | TB VHXH - HĐND | 944316613 |  |  |  |
| 20 | Cao Trần Phụng Ngọc | Phó Ban VHXH - HĐND | 356927070 |  |  |  |

### UBND xã Long Chữ - Địa chỉ: ấp Long Hoà, xã Long Chữ

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 21 | Phạm Thanh Tuấn | Phó Bí thư - CT UBND | 913647968 |  |  |  |
| 22 | Nguyễn Thành Thông | UV BTV - PCT UBND | 0986 172 012 |  |  |  |
| 23 | Nguyễn Tấn Phúc | UV BTV - PCT UBND | 906695536 |  |  |  |
| 24 | Huỳnh Văn Mẫn | UV BCH - CVP HĐND và UBND | 918005873 |  |  |  |
| 25 | Phạm Hửu Hiền | PCVP HĐND và UBND | 377899739 |  |  |  |
| 26 | Trần Văn Chỉa | UV BCH - Trưởng phòng kinh tế | 906751234 |  |  |  |
| 27 | Hồ Thanh Phong | PTP kinh tế | 849546568 |  |  |  |
| 28 | Nguyễn Văn Phước | UV BCH - TP Văn hóa - Xã hội | 916670557 |  |  |  |
| 29 | Nguyễn Thị Kim Hoa | PTP Văn hóa - Xã hội | 374792830 |  |  |  |
| 30 | Nguyễn Thành Thông | GĐ TT Hành chính c(kiêm nhiệm) | 986172012 |  |  |  |
| 31 | Phạm Văn Thanh | PGĐ TT Hành chính công | 979671092 |  |  |  |

### Công an Long Chữ - Địa chỉ: ấp Phước Đông, xã Long Chữ

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 32 | Huỳnh Phủ Ngọc Vui | UV BTV - Trưởng Công an | 945352752 |  |  |  |
| 33 | Hồ Duy Khanh | Phó trưởng Công an | 974333739 |  |  |  |
| 34 | Phạm Thanh Cường | Phó trưởng Công an | 919495992 |  |  |  |
| 35 | Nguyễn Văn Chí | Phó trưởng Công an | 913305262 |  |  |  |
| 36 | Phạm Thanh Liêm | Phó trưởng Công an | 944811872 |  |  |  |
| 37 | Tạ Hồng Thái | Phó trưởng Công an | 792034228 |  |  |  |

### BCH Quân sự Long Chữ - Địa chỉ: ấp Long Châu, xã Long Chữ

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 38 | Nguyễn Chí Hoà | UV BTV - CHT BCHQS sự xã | 987327187 |  |  |  |

### XÃ PHƯỚC THẠNH

- Nhóm: 1
- Mã/STT nhóm: 86

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 1 | Phạm Thị Thúy Hằng | Bí thư Đảng ủy - CT HĐND xã | 0916 686 668 |  |  |  |
| 2 | Đỗ Minh Tâm | Phó Bí thư Thường trực Đảng ủy xã | 0933 816 689 |  |  |  |
| 3 | Trần Lĩnh Du | Phó Bí thư - CT UBND xã | 0978 875 205 |  |  |  |
| 4 | Huỳnh Việt Sơn | UV BTV - PCT UBND xã | 0919 283 565 |  |  |  |
| 5 | Tôn Nữ Ngọc Hằng | UV BTV - PCT UBND xã | 0915 404 030 |  |  |  |
| 6 | Nguyễn Văn Thiệu | UV BCH -Trưởng Ban Xây dựng Đảng | 0943 990 220 |  |  |  |
| 7 | Nguyễn Hữu Nghĩa | UV BCH - Phó trưởng Ban Xây dựng Đảng | 0936 543 177 |  |  |  |
| 8 | Huỳnh Thị Phương Loan | Chủ nhiệm UBKT | 0902 413 029 |  |  |  |
| 9 | Đỗ Anh Kiệt | UV BCH - PCN UBKT | 0919 002 898 |  |  |  |
| 10 | Mai Thị Cẩm Thơ | UV BCH - Chánh Văn phòng Đảng ủy | 0907 044 621 |  |  |  |
| 11 | Huỳnh Trung Hiếu | UV BCH - PCT.HĐND | 0982 341 794 |  |  |  |
| 12 | Nguyễn Văn Tuyển | UV BCH - Trưởng Phòng Kinh tế | 0902 440 722 |  |  |  |
| 13 | Bùi Thị Thanh Giang | UV BCH - Chánh VP HĐND và UBND | 0398 512 542 |  |  |  |
| 14 | Tô Thanh Hiền | UV BCH - Trưởng Phòng VH-XH | 077 565 165 |  |  |  |
| 15 | Phan Thị Kiên | UV BCH - CT MTTQ | 0977 932 615 |  |  |  |
| 16 | Nguyễn Lê Công Phương | UV BCH - PCT MTTQ (Kiêm BT ĐTN) | 0384 574 190 |  |  |  |
| 17 | Nguyễn Thị Kim Diễm | UV BCH - PCT MTTQ (Kiêm CT HPN) | 0937 618 668 |  |  |  |
| 18 | Võ Thị Thanh Thảo | UV BCH -PCT MTTQ (Kiêm CT HND) | 0943 715 457 |  |  |  |
| 19 | Phạm Minh Duy | UV BTV - Chỉ huy trưởng Quân sự | 0916 452 996 |  |  |  |
| 20 | Nguyễn Phong Vinh | UV BTV - Trưởng Công an | 0909 395 314 |  |  |  |
| 21 | Trần Thị Kim Tiến | UV BCH - Công an | 0942 624 868 |  |  |  |
| 22 | Phan Văn Thảo | Giám đốc Trung tâm cung ứng dịch vụ sự nghiệp công | 0919 542 214 |  |  |  |
| 23 | Lê Thị Bích Ngọc | Phó trưởng Ban Kinh tế - Ngân sách, HĐND | 0918 049 055 |  |  |  |
| 24 | Trần Thị Thu Hồng | Phó trưởng ban Văn hóa - Xã hội, HĐND | 0904 474 498 |  |  |  |
| 25 | Phạm Minh Tiển | Phó Chánh VP HĐND và UBND | 0984 644 380 |  |  |  |
| 26 | Bùi Thị Trúc Giang | Phó trưởng phòng Kinh tế | 0932 626 779 |  |  |  |
| 27 | Võ Chí Thanh | Phó trưởng phòng Văn hóa - Xã hội | 0988 453 335 |  |  |  |
| 28 | Trần Minh Quang | PCT MTTQ (Kiêm CT Hội CCB) | 0986 349 066 |  |  |  |

### XÃ THẠNH ĐỨC

- Nhóm: 1
- Mã/STT nhóm: 87

#### Đảng ủy Thạnh Đức - Địa chỉ: Ấp Cẩm Thắng, xã Thạnh Đức

- Email: thaibinh1975@tayninh.gov.vn

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 1 | Phạm Vũ Anh Thi | Bí thư | 0915 401 556 |  | vanttb@tayninh.gov.vn |  |
| 2 | Nguyễn Thái Quân | Phó Bí thư - Kiêm CT.MTTQVN xã | 0368 492 293 |  | nhantv@tayninh.gov.vm |  |
| 3 | Phạm Thị Hồng hạnh | UV BTV - CN UBKT | 0933 031 844 |  | thungv@tayninh.gov.vn |  |
| 4 | Lê Xuân Lành | UV BCH - PCN UBKT | 0909 193 860 |  | bichtuyen@tayninh.gov.vn |  |
| 5 | Huỳnh Thị Mỹ Phương | UV BTV - TB Xây dựng đảng | 0973 464 584 |  | ducduy1982@tayninh.gov.vn |  |
| 6 | Huỳnh Thị Tú Uyên | UV BCH - PTB Xây dựng đảng | 0987 432 239 |  | vantan1973@tayninh.gov.vn |  |
| 7 | Tô Thị Yến Nhi | UV BCH - CVP Đảng ủy | 0886 773 792 |  | kimcuong1992@tayninh.gov.vn |  |
| 8 | Nguyễn Thị Phương Linh | UV BCH - PCT MTTQ, CT Hội PN | 0338 639 752 |  | bengoan1985@tayninh.gov.vn |  |
| 9 | Trương Hữu Tín | UV BCH - PCT MTTQ, CT Hội ND | 0919 627 662 |  | thedung1984@tayninh.gov.vm |  |
| 10 | Lê Minh Tân | UV BCH - PCT MTTQ, BT Đoàn TN | 0366 112 612 |  |  |  |
| 11 | Võ Thị Ngọc Hiếu | PCVP Đảng ủy | 0949 295 857 |  |  |  |

#### 12

### HĐND Thạnh Đức - Địa chỉ: Ấp Trà Võ, xã Thạnh Đức

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 13 | Võ Duy Linh | UVBTV - PCT HĐND | 0918 482 111 |  |  |  |
| 14 | Nguyễn Trung Thái | Ban Kinh tế - HĐND | 0919 720 472 |  |  |  |
| 15 | Hồ Văn Thẳng | Ban VHXH - HĐND | 0919 720 472 |  |  |  |

### UBND xã - Địa chỉ: Ấp Trà Võ, Xã Thạnh Đức, Tây Ninh

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 16 | Nguyễn Thái Bình | Phó Bí thư - CT UBND | 0822 102 666 |  |  |  |
| 17 | Trần Thị Bích Vân | UVBTV- PCT UBND-GĐTT Cung ứng DVSN công | 0919 237 456 |  |  |  |
| 18 | Trần Văn Nhân | UVBTV - PCT UBND-GĐTT Hành chính công | 0913 010 008 |  |  |  |
| 19 | Hồ Văn Thưng | UVBCH - CVP HĐND và UBND | 0917 733 331 |  |  |  |
| 20 | Lê Thị Bích Tuyền | PCVP HĐND và UBND | 0913 659 430 |  |  |  |
| 21 | Đoàn Đức Duy | UVBCH - Trưởng phòng kinh tế | 0983 957 489 |  |  |  |
| 22 | Phan Văn Tân | PTP kinh tế | 0902 510 168 |  |  |  |
| 23 | Lê Đỗ Kim Cương | UVBCH - TP Văn hóa - Xã hội | 0986 115 363 |  |  |  |
| 24 | Bùi Thị Bé Ngoan | PTP Văn hóa - Xã hội | 0979 278 597 |  |  |  |
| 25 | Đoàn Thế Dũng | PGĐ TT Hành chính công | 0926 587 286 |  |  |  |
| 26 | Nguyễn Đoàn Dũng | UVBTV- Trưởng Công an | 0797 252 789 |  |  |  |
| 27 | Nguyễn Văn Sỹ | UVBCH-Phó trưởng Công an | 0913 765 990 |  |  |  |
| 28 | Nguyễn Đình Trung | UVBTV - CHT BCH Quân sự | 0985 189 518 |  |  |  |
| 29 | Huỳnh Văn Giỏi | UVBCH-CHP BCH Quân sự | 0977 670 848 |  |  |  |

### XÃ TRUÔNG MÍT

- Nhóm: 1
- Mã/STT nhóm: 88

### Đảng ủy xã Truông Mít - Địa chỉ: số 473 đường ĐT.784, ấp Thuận An, xã Truông Mít

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 1 | Dương Văn Ư | Bí thư Đảng ủy - CT HĐND xã | 0913 884 145 |  | udv@tayninh.dcs.vn |  |
| 2 | Huỳnh Thị Ái Lê | Phó Bí thư - CT UBMTTTQ xã | 0984 997 611 |  | lehta@tayninh.dcs.vn |  |
| 3 | Trần Thị Thanh Kiều | UV BTV - CN UBKT ĐU xã | 0912 547 620 |  | kieuttt@tayninh.dcs.vn |  |
| 4 | Lê Hoàng Duy | UV BCH - Phó CN UBKTĐU xã | 0913 884 392 |  | duylh@tayninh.dcs.vn |  |
| 5 | Phan Ngọc Hồi | UV BTV - TB Xây dựng Đảng | 0979 356 588 |  | hoipn@tayninh.dcs.vn |  |
| 6 | Huỳnh Trung Nghĩa | UV BCH - PTB Xây dựng đảng | 0988 721 939 |  | nghiaht@tayninh.dcs.vn |  |
| 7 | Lê Thanh Dũng | UV BCH - CVP Đảng ủy xã | 0918 052 992 |  | dunglt@tayninh.dcs.vn |  |
| 8 | Nguyễn Thị Ngọc Giàu | PCVP Đảng ủy xã | 0945 258 166 |  | giauntn@tayninh.dcs.vn |  |
| 9 | Đỗ Thị Kim Quyên | UV BCH - PCT MTTQ, CT Hội LHPN xã | 0342 461 385 |  | doquyen3637@gmail.com |  |
| 10 | Lê Văn Lộc | UV BCH - PCT MTTQ, CT Hội nông dân xã | 0339 914 899 |  |  |  |
| 11 | Nguyễn Thị Tuyết Nhi | UV BCH - PCT MTTQ, / BT Đoàn TN | 0345 003 118 |  |  |  |
| 12 | Tô Văn Cảnh | PCT.MTTQ, Chủ tịch Hội CCB xã | 0919 194 239 |  |  |  |

### HĐND xã - Địa chỉ: Đường ĐT.782, ấp 7, xã Truông Mít

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 13 | Phan Thị Anh Thư | UV.BTV - PCT HĐND | 0913 733 729 |  | thupta.truongmit@tayninh.gov.vn |  |
| 14 | Lê Công Minh | Trưởng Ban Kinh tế - Ngân sách HĐND xã | 0933 928 192 |  | minhlc.truongmit@tayninh.gov.vn |  |
| 15 | Phạm Văn Trương | Trưởng Ban Văn hóa - Xã hội HĐND | 0972 052 269 |  | truongpv.truongmit@tayninh.gov.vn |  |

### UBND xã; email: ubndtruongmit@tayninh.gov.vn - Địa chỉ: Đường ĐT.782, ấp 7, xã Truông Mít

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 16 | Phạm Quang Định | Phó Bí thư - CT UBND xã | 0989 979 357 |  | dinhpq@tayninh.gov.vn |  |
| 17 | Nguyễn Thị Hiệp | UV.BCH - PCT UBND (kiêm giám đốc TT cung ứng dịch vụ sự nghiệp công) | 0973 564 652 |  | hiepnt1@tayninh.gov.vn |  |
| 18 | Nguyễn Thị Thanh Thủy | UV.BCH - PCT UBND (kiêm giám đốc TT phục vụ hành chính công) | 0913 626 424 |  | thanhthuy1982@tayninh.gov.vn |  |
| 19 | Nguyễn Thị Thùy Dung | UV.BCH - CVP HĐND và UBND xã | 0938 282 465 |  | thuydung1983@tayninh.gov.vn |  |
| 20 | Võ Thị Trúc Huỳnh | PCVP HĐND và UBND xã | 0909 638 003 |  | truchuynh1987@taynih.gov.vn |  |
| 21 | Võ Ngọc Tuyền | UV.BCH - Trưởng phòng kinh tế xã | 0986 172 710 |  | tuyennv@tayninh.gov.vn |  |
| 22 | Nguyễn Duy Khánh | Phó Trưởng phòng Kinh tế xã | 0937 777 439 |  | duykhanh1984@tayninh.gov.vn |  |
| 23 | Đỗ Văn Trắng | UV.BCH - Trưởng phòng Văn hóa - Xã hội | 0918 005 235 |  | vantrang1980@tayninh.gov.vn |  |
| 24 | Huỳnh Văn Tài | PTP Văn hóa - Xã hội | 0834 004 828 |  | vantai1983@tayninh.gov.vn |  |
| 25 | Lê Thanh Tùng | PGĐ TT phục vụ Hành chính công | 0974 333 440 |  | thanhtung1980@tayninh.gov.vn |  |
| 26 | Hà Minh Quí | UV.BTV - Trưởng Công an | 0901 232 636 |  | csdtd20shaminhqui@gmail.com |  |
| 27 | Nguyễn Văn Tuấn | Phó trưởng Công an | 0938 081 645 |  |  |  |
| 28 | Huỳnh Hữu Nghĩa | Phó trưởng Công an | 0918 161 188 |  |  |  |
| 29 | Ngô Quốc | Phó trưởng Công an | 0967 851 852 |  | ngoquoc158@gmail.com |  |
| 30 | Võ Châu Thanh | Phó trưởng Công an | 0933 815 339 |  |  |  |
| 31 | Dương Thành Duy | Phó trưởng Công an | 0902 934 359 |  | duongthanhduy89@gmail.com |  |
| 32 | Nguyễn Duy Khánh | UV.BTV - CHT BCH Quân sự | '0974 467 197 |  |  |  |
| 33 | Nguyễn Văn Nguyên | Phó CHT BCH Quân sự | 0563 691 258 |  |  |  |

### XÃ PHƯỚC VINH

- Nhóm: 1
- Mã/STT nhóm: 89

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 1 | Phan Thị Hồng Đào | Bí thư Đảng uỷ, Chủ tịch MTTQ xã | 0913 884 307 |  |  |  |
| 2 | Vương Thị Hồng Loan | Phó Bí thư Đảng ủy,Chủ tịch Mặt trận tổ quốc Việt Nam xã | 0986 343 205 |  |  |  |
| 3 | Nguyễn Văn Cường | Phó Bí thư Đảng ủy, Chủ tịch Ủy ban nhân dân xã | 0909383797 |  |  |  |
| 4 | Nguyễn Tất Linh | Ủy viên BTV Đảng ủy, PCT Uỷ ban nhân dân xã | 0909971644 |  |  |  |
| 5 | Lê Thị Tuyết Nhung | Ủy viên BTV Đảng ủy, CN Uỷ ban kiểm tra Đảng ủy | 0982726939 |  |  |  |
| 6 | Trương Hùng Phong | Ủy viên BTV Đảng ủy, Trưởng Ban xây dựng Đảng | 0845127788 |  |  |  |
| 7 | Nguyễn Thanh Hùng | Ủy viên BTV Đảng ủy, PCT Hội đồng nhân dân xã | 0906751751 |  |  |  |
| 8 | Nguyễn Văn Luận | Ủy viên BTV Đảng ủy, Trưởng Công an | 0968850905 |  |  |  |
| 9 | Lê Văn Nhỏ | Ủy viên BTV Đảng ủy, Trưởng BCH Quân sự | 0913132309 |  |  |  |
| 10 | Trần Thị Khánh Tâm | Ủy viên BCH, PCT Uỷ ban nhân dân xã | 0949466890 |  |  |  |
| 11 | Trần Quang Vinh | Ủy viên BCH, Chánh văn phòng Đảng ủy | 0815880868 |  |  |  |
| 12 | Lê Xuân Hồng | Ủy viên BCH, Chánh Văn phòng HĐND - UBND xã | 0978664640 |  |  |  |
| 13 | Nguyễn Chí Dũng | Ủy viên BCH, Trưởng phòng Kinh tế | 0919199653 |  |  |  |
| 14 | Trịnh Xuân Hà | Ủy viên BCH, Trưởng phòng Văn hóa - Xã hội | 0943522202 |  |  |  |
| 15 | Lê Thành Trung | Ủy viên BCH, Phó CN Ủy ban Kiểm tra Đảng ủy | 0917066446 |  |  |  |
| 16 | Trì Tấn Phát | Ủy viên BCH, PTB xây dựng Đảng | 0888755252 |  |  |  |
| 17 | Nguyễn Minh Tuấn | Ủy viên BCH, Phó Trưởng Công an | 0918091825 |  |  |  |
| 18 | Trần Thị Loan | Ủy viên BCH, PCT thường trực MTTQ, Chủ tịch Hội Liên hiệp phụ nữ xã | 0919196656 |  |  |  |
| 19 | Trần Minh Thành | Ủy viên BCH, PCT MTTQ, BT Đoàn TN xã | 0353465903 |  |  |  |
| 20 | Huỳnh Văn Lễ | Ủy viên BCH, PCT MTTQ, CT Hội ND | 0888730777 |  |  |  |
| 21 | Huỳnh Thị Cẩm Nhung | Phó Chánh Văn phòng Đảng ủy xã Phước Vinh | 0367474169 |  |  |  |
| 22 | Trì Tấn Phát | PTB xây dựng Đảng ủy xã Phước Vinh | 0888755252 |  |  |  |
| 23 | Lê Minh Hưng | Phó CN UBKT Đảng ủy xã Phước Vinh | 0987953965 |  |  |  |
| 24 | Trần CDanh | Ủy viên UBKT Đảng ủy xã Phước Vinh | 0941801088 |  |  |  |
| 25 | Đặng Đại Ngà | PTB Kinh tế - Ngân sách của Hội đồng nhân dân xã Phước Vinh | 0918957588 |  |  |  |
| 26 | Lâm Hữu Thế | PTB Văn hóa - Xã hội của Hội đồng nhân dân xã Phước Vinh | 0857528786 |  |  |  |
| 27 | Đinh Thanh Nhàn | Phó Chánh Văn phòng UBND xã Phước Vinh | 0942656492 |  |  |  |
| 28 | Phùng Thị Mai Huyền | Phó Trưởng phòng Văn hoá - xã hội UBND xã Phước Vinh | 0906608661 |  |  |  |
| 29 | Nguyễn Trọng Hiệp | PGĐ TT Hành chính c xã Phước Vinh | 0394523177 |  |  |  |
| 30 | Nguyễn Minh Tuấn | Phó Trưởng Công an xã Phước Vinh | 0918091825 |  |  |  |
| 31 | Nguyễn Thành Danh | PCT Uỷ ban Mặt trận Tổ quốc xã/Chủ tịch Hội CCB | 0973553101 |  |  |  |

### XÃ NINH ĐIỀN

- Nhóm: 1
- Mã/STT nhóm: 90

### Đảng ủy Ninh Điền - Địa chỉ: Tổ 12, ấp Thành Tây, xã Ninh Điền

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 1 | Trần Thị Ngọc Nương | Bí thư | 0919 572 616 |  |  |  |
| 2 | Lê Thanh Hòa | Phó Bí thư | 0989 974 194 |  |  |  |
| 3 | Đặng Hồng Nhã | UV BTV - CN UBKT | 0919 406 708 |  |  |  |
| 4 | Nguyễn Thúy Lời | ĐUV - PCN UBKT | 0986 709 310 |  |  |  |
| 5 | Hồ Ngọc Bảo | UV BTV - TB Xây dựng đảng | 0947 810 997 |  |  |  |
| 6 | Hồ Văn Giang | ĐUV - PTB Xây dựng đảng | 0909 626 238 |  |  |  |
| 7 | Bùi Tuấn Anh | ĐUV - CVP Đảng ủy | 0937 218 305 |  |  |  |
| 8 | Lê Thanh Hòa | Phó Bí Thư - CT MTTQ xã | 0989 974 194 |  |  |  |
| 9 | Nguyễn Thị Hồng Phượng | ĐUV - PCT MTTQ, CT Hội PN | 0384 371 884 |  |  |  |
| 10 | Giáp Bình Minh | ĐUV - PCT MTTQ, CT Hội ND | 0983 595 532 |  |  |  |
| 11 | Dương Hoàng Phúc | ĐUV - PCT MTTQ, BT Đoàn TN | 0355 886 993 |  |  |  |
| 12 | Nguyễn Thị Hồng Nhung | PCVP Đảng ủy | 0911 929 960 |  |  |  |
| 13 | Trần Lê Duy | PCN UBKT | 0908 841 714 |  |  |  |

### HĐND Ninh Điền - Địa chỉ:Tổ 12, ấp Thành Tây, xã Ninh Điền

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 14 | Trần Thị Ngọc Nương | Bí thư - CT HĐND | 0919 572 616 |  |  |  |
| 15 | Nguyễn Thị Đức Diệu | UV BTVĐU, PCT HĐND | 0972 705 757 |  |  |  |
| 16 | Nguyễn Thái Bình | Phó Ban Kinh tế - HĐND | 0913 661 107 |  |  |  |
| 17 | Nguyễn Thanh Tùng | Phó Ban VHXH - HĐND | 0943 430 952 |  |  |  |

### UBND xã - ĐT bàn: 02763 783 217 ; email: ubndninhdien@tayninh.gov.vn

### Địa chỉ: Tổ 12, ấp Thành Tây, xã Ninh Điền

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 18 | Đỗ Thành Trung | Phó Bí thư - CT UBND | 0913 636 209 |  |  |  |
| 19 | Trần Thế Hiệp | UV BTVĐU - PCT UBND | 0933 819 975 |  |  |  |
| 20 | Phạm Thanh Phong | UV BTVĐU - PCT UBND | 0913 429 539 |  |  |  |
| 21 | Thái Trung Nhân | ĐUV - CVP HĐND và UBND | 0918 474 007 |  |  |  |
| 22 | Nguyễn Chí Linh | PCVP HĐND và UBND | 0909 381 544 |  |  |  |
| 23 | Nguyễn Minh Lý | ĐUV - Trưởng phòng kinh tế | 0848 525 252 |  |  |  |
| 24 | Thái Thị Thu Trang | PTP kinh tế | 0368 332 900 |  |  |  |
| 25 | Nguyễn Quốc Tuấn | ĐUV- TP Văn hóa - Xã hội | 0937 556 747 |  |  |  |
| 26 | Đặng Đình Lâm | PTP Văn hóa - Xã hội | 0983 783 050 |  |  |  |
| 27 | Phạm Thanh Phong | GĐ TT Hành chính công | 0913 429 539 |  |  |  |
| 28 | Giang Cẩm Lìn | PGĐ TT Hành chính công | 0961 464 857 |  |  |  |
| 29 | Nguyễn Quốc Tuấn | GĐ TT Cung ứng DVSN công | 0937 556 747 |  |  |  |
| 30 | Trần Quốc Thanh | UV BTVĐU - Trưởng Công an | 0919 030 919 |  |  |  |
| 31 | Đoàn Xuân Hiếu | Phó trưởng Công an | 0918 840 067 |  |  |  |
| 32 | Tô Thanh Đồng | UV BTVĐU - CHT BCH Quân sự | 0984 110 624 |  |  |  |

### XÃ HÒA HỘI

- Nhóm: 1
- Mã/STT nhóm: 91

### Đảng ủy Hòa Hội - Địa chỉ: ấp Bến Cầu xã Hòa Hội tỉnh Tây Ninh

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 1 | Nguyễn Thị Thanh Sơn | Bí thư |  |  |  |  |
| 2 | Nguyễn Trung Hiếu | Phó Bí thư |  |  |  |  |
| 3 | Nguyễn Nhật Lê Vinh | UV BTV - CN UBKT |  |  |  |  |
| 4 | Lê Văn Hồng | UV BCH - PCN UBKT |  |  |  |  |
| 5 | Đoàn Thị Hồng | UV BTV - TB Xây dựng đảng |  |  |  |  |
| 6 | Nguyễn Hoàng Hiếu | UV BCH - PTB Xây dựng đảng |  |  |  |  |
| 7 | Lê Trung Hiếu | UV BCH - CVP Đảng ủy |  |  |  |  |
| 8 | Trương Thị Hồng Hạnh | Chức vụ đảng - CT MTTQ xã |  |  |  |  |
| 9 | Nguyễn Thị Kim Tuyến | UV BCH - PCT MTTQ, CT Hội PN |  |  |  |  |
| 10 | Phạm Đình Lâm | UV BCH - PCT MTTQ, CT Hội ND |  |  |  |  |
| 11 | Trương Duy hải | UV BCH - PCT MTTQ, BT Đoàn TN |  |  |  |  |

#### 12

### HĐND Hòa Hội - Địa chỉ: ấp Bến Cầu xã Hòa Hội tỉnh Tây Ninh

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 13 | Nguyễn Thị Thanh Sơn | Bí thư Đảng ủy - CT HĐND |  |  |  |  |
| 14 | Lê Hữu Nghị | PCT HĐND |  |  |  |  |
| 15 | Nguyễn Tấn Đạt | Ban Kinh tế - HĐND |  |  |  |  |
| 16 | Nguyễn Thị Bé Quyr6n | Ban VHXH - HĐND |  |  |  |  |

### UBND xã - ĐT bàn: 02763784103; email: ubnd….@tayninh.gov.vn

### Địa chỉ: ấp Hiệp Phước xã Hòa Hội

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 17 | Nguyễn Đồng Dũng | Phó Bí thư - CT UBND | 0974 094 794 |  |  |  |
| 18 | Triệu Nguyên Đáng | UVBTV - PCT UBND | 0966 938 939 |  |  |  |
| 19 | Trần Thế Anh | UBBTV - PCT UBND | 0918 475 930 |  |  |  |
| 20 | Huỳnh Thu Tâm | UVBCH - CVP HĐND và UBND | 0987 616 099 |  |  |  |
| 21 | Lê Văn Phước | PCVP HĐND và UBND | 0977 757 349 |  |  |  |
| 22 | Nguyễn Văn Hạt | UVBCH - Trưởng phòng kinh tế | 0918 861 825 |  |  |  |
| 23 | Trần Việt Hậu | PTP kinh tế | 0917 542 343 |  |  |  |
| 24 | Võ Minh Nhật | UVBCH - TP Văn hóa - Xã hội | 0822 000 082 |  |  |  |
| 25 | Hoàng Sỹ Trương | PTP Văn hóa - Xã hội | 0977 177 227 |  |  |  |
| 26 | Trần Thế Anh | GĐ TT Hành chính công | 0918 475 930 |  |  |  |
| 27 | Lâm Văn Xây | PGĐ TT Hành chính công | 0988 252 399 |  |  |  |
| 28 | Võ Minh Nhật | GĐ TT Cung ứng DVSN công | 0822 000 082 |  |  |  |

#### 29

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 30 | Nguyễn Văn Tâm | UV BTV- Trưởng Công an | 0972 273 273 |  |  |  |
| 31 | Nguyễn Quốc Hải | UVBCH - Phó trưởng Công an | 0913 523 877 |  |  |  |
| 32 | Kim Hoàng Kha | UV BTV - CHT BCH Quân sự | 0978 837 159 |  |  |  |

### XÃ HẢO ĐƯỚC

- Nhóm: 1
- Mã/STT nhóm: 92

### Đảng ủy Hảo Đước - Địa chỉ: Xóm Mới 1, Hảo Đước

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 1 | Nguyễn Thị Chi | Bí thư | 0988 292 090 |  |  |  |
| 2 | Nguyễn Tiến Hưng | Phó Bí thư | 0916 522 792 |  |  |  |
| 3 | Đặng Thị Hồng Sa | UV BTV - CN UBKT | 0937 054 800 |  |  |  |
| 4 | Lương Thanh Tâm | UV BCH - PCN UBKT | 0933227426 |  |  |  |
| 5 | Nguyễn Văn Đạt | UV BTV - TB Xây dựng đảng | 0917230235 |  |  |  |
| 6 | Nguyễn Thị Ngọc Oanh | UV BCH - PTB Xây dựng đảng | 0366649676 |  |  |  |
| 7 | Nguyễn Thị Hữu Phúc | UV BCH - CVP Đảng ủy | 0364463819 |  |  |  |
| 8 | Lê Thị Kim Oanh | Chức vụ đảng - CT MTTQ xã | 0982634463 |  |  |  |
| 9 | Võ Thị Huỳnh Giao | UV BCH - PCT MTTQ, CT Hội PN | 0919269009 |  |  |  |
| 10 | Trần Thị Thanh Nga | UV BCH - PCT MTTQ, CT Hội ND | 0987223543 |  |  |  |
| 11 | Nguyễn Thành Năng | UV BCH - PCT MTTQ, BT Đoàn TN | 0975557790 |  |  |  |

#### 12

### HĐND Hảo Đước - Địa chỉ: Tổ 1, ấp Sân Lễ, xã Hảo Đước

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 13 | Nguyễn Thị Chi | Chức vụ Đảng - CT HĐND | 0988292090 |  |  |  |
| 14 | Đạng Thị Hồng Sa | Ban Kinh tế - HĐND | 0937054800 |  |  |  |
| 15 | Nguyễn Văn Đạt | Ban VHXH - HĐND | 0917230235 |  |  |  |

### UBND xã - ĐT bàn: 02763782139 ; email: ubndhaoduoc@tayninh.gov.vn

### Địa chỉ: Tổ 1, ấp Sân Lễ, xã Hảo Đước

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 16 | Nguyễn Thanh Đại | Phó Bí thư - CT UBND | 0978 132 413 |  |  |  |
| 17 | Nguyễn Trọng Tài | Chức vụ đảng - PCT UBND | 0913 823 019 |  |  |  |
| 18 | Lê Đức Lập | Chức vụ đảng - PCT UBND | 0975 295 458 |  |  |  |
| 19 | Lưu Xuân Đạt | Chức vụ đảng - CVP HĐND và UBND | 0917185739 |  |  |  |
| 20 | Lê Thị Thu Trang | PCVP HĐND và UBND | 0917400442 |  |  |  |
| 21 | Thái Thị Ngọc Hân | Chức vụ đảng - Trưởng phòng kinh tế | 0903730598 |  |  |  |
| 22 | Nguyễn Đình Việt Khánh | PTP kinh tế | 0933959915 |  |  |  |
| 23 | Lê Văn Lân | Chức vụ đảng - TP Văn hóa - Xã hội | 0917697112 |  |  |  |
| 24 | Nguyễn Thanh Liêm | PTP Văn hóa - Xã hội | 0914 803 382 |  |  |  |
| 25 | Nguyễn Trọng Tài | GĐ TT Hành chính c(kiêm) | 0913 823 019 |  |  |  |
| 26 | Nguyễn Văn Trung | PGĐ TT Hành chính công | 0912649739 |  |  |  |
| 27 | Lê Đức Lập | GĐ TT Cung ứng DVSN c(kiêm) | 0975295458 |  |  |  |

#### 28

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 29 | Trần Thanh Tâm | Chức vụ đảng - Trưởng Công an | 0982567343 |  |  |  |
| 30 | Lê Minh Trí | Phó trưởng Công an | 0941313286 |  |  |  |
| 31 | Trịnh Văn Tâm | Phó trưởng Công an | 0943086792 |  |  |  |
| 32 | Nguyễn Lê Hùng Dũng | Phó trưởng Công an | 0918101300 |  |  |  |
| 33 | Lê CDanh | Phó trưởng Công an | 0913955966 |  |  |  |
| 34 | Nguyễn Thị Ngọc Thủy | Phó trưởng Công an | 0918718192 |  |  |  |
| 35 | Nguyễn Thành Hưng | Chức vụ đảng - CHT BCH Quân sự | 0983530152 |  |  |  |

### XÃ CHÂU THÀNH ĐT bàn 02763 878 121; email: ubndchauthanh@tayninh.gov.vn Website, Zalo (nếu có)

- Nhóm: 1
- Mã/STT nhóm: 93

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 1 | Lê Ngọc Ẩn | Bí thư - CT HĐND | 0983 187 594 | 3878 152 |  | Đường Hoàng Lê Kha, xã Châu Thành, tỉnh TN |
| 2 | Phạm Thị Bạch Huệ | Phó Bí thư Thường trực Đảng ủy | 0975 862 151 |  |  | // |
| 3 | Võ Thị Ánh Hậu | Phó Bí thư - CT UBND | 0908 698 066 | 3878 121 |  | Số 935, Đường Hoàng Lê Kha, xã Châu Thành |
| 4 | Nguyễn Thị Diễm Kiều | UV BTV - Trưởng ban Xây dựng Đảng | 0974 467 381 |  |  | Đường Hoàng Lê Kha, xã Châu Thành, tỉnh TN |
| 5 | Nguyễn Thị Thanh Thảo | UV BTV - Chủ nhiệm UBKT Đảng ủy | 0974 466 759 |  |  | // |
| 6 | Lâm Minh Lâm | UV BTV - Chủ tịch Ủy ban Mặt trận Tổ quốc Việt Nam | 0933 720 042 |  |  | // |
| 7 | Lê Thị Thu Hương | PCT HĐND | 0913 326 650 |  |  | Số 935, Đường Hoàng Lê Kha, xã Châu Thành |
| 8 | Ngô Thanh Bình | UV BTV - PCT UBND | 0908 321 007 |  |  | // |
| 9 | Đặng Hoàng Trung | UV BTV - PCT UBND | 0935 927 336 |  |  | // |
| 10 | Dương Tấn Toàn | UV BTV - Trưởng Công an | 0913 909 887 / 0977 421 767 | 3878 564 |  | Tỉnh lộ 781, Khu phố 3, / xã Châu Thành, tỉnh TN |
| 11 | Võ Vũ Tuân | UV BTV - CHT Ban Chỉ huy Quân sự | 0792 118 910 |  |  | Đường 781, xã Châu Thành, tỉnh TN |
| 12 | Hà Thị Nhàn | UV BCH - Chánh Văn phòng HĐND và UBND | 0944 761 731 |  |  | Số 935, Đường Hoàng Lê Kha, xã Châu Thành |
| 13 | Nguyễn Thu Hiền | UV BCH - Trưởng phòng Kinh tế | 0917 286 223 |  |  | // |
| 14 | Nguyễn Thị Linh | UV BCH - Trưởng phòng Văn hóa - Xã hội | 0977 393 872 |  |  | // |
| 15 | Lâm Thị Phương Thảo | UV BCH - Chánh Văn phòng Đảng ủy | 0987 900 722 |  |  | Đường Hoàng Lê Kha, xã Châu Thành, tỉnh TN |
| 16 | Đào Thị Thanh Nga | UV BCH - Giám đốc TT Bồi dưỡng Chính trị | 0917 385 865 |  |  | Ấp Suối Dộp, xã Châu Thành, tỉnh TN |
| 17 | Phạm Thị Phương Thảo | UV BCH - Phó Chủ nhiệm Ủy ban Kiểm tra Đảng ủy | 0913 955 440 |  |  | Đường Hoàng Lê Kha, xã Châu Thành, tỉnh TN |
| 18 | Nguyễn Thị Mộng Tuyền | UV BCH - PTB Xây dựng Đảng | 0919 923 019 |  |  | // |
| 19 | Lê Ngọc Minh Hùng | UV BCH - Phó CT UBMT TQVN - kiêm BT Đoàn TN | 0908 655 881 |  |  | // |
| 20 | Võ Thị Thúy Nga | UV BCH - Phó CT UBMT TQVN - kiêm Chủ tịch Hội Liên hiệp Phụ nữ | 0944 900 456 |  |  | // |
| 21 | Dương Thanh Phong | UV BCH - Phó CT UBMT TQVN - kiêm Chủ tịch Hội Nông dân | 0933 411 262 |  |  | // |
| 22 | Ngô Thị Hồng Liên | UV BCH - Phó Trưởng Công an | 0936 152 182 |  |  | Tỉnh lộ 781, Khu phố 3, / xã Châu Thành, tỉnh TN |
| 23 | Trần Ngọc Búp | Phó Chánh Văn phòng HĐND và UBND | 0908 583 431 |  |  | Số 935, Đường Hoàng Lê Kha, xã Châu Thành |
| 24 | Đào Huy Đạt | Phó Trưởng phòng Văn hóa - Xã hội | 0902 400 034 |  |  | // |
| 25 | Nguyễn Thị Xuân Hồng | Phó Trưởng phòng Kinh tế | 0909 670 097 |  |  | // |
| 26 | Lương Thị Ngọc Nhung | PGĐ TT Phục vụ Hành chính công | 0975 023 383 | 3790 222 |  | // |
| 27 | La Văn Lợi | Giám đốc TT cung ứng dịch vụ sự nghiệp công | 0988 170 316 | 3878 130 |  | Đường Tua Hai, Khu phố 1, xã Châu Thành, tỉnh TN |

### XÃ DƯƠNG MINH CHÂU

- Nhóm: 1
- Mã/STT nhóm: 94

#### 257 Nguyễn Chí Thanh, xã Dương Minh Châu

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 1 | Huỳnh Vương Hiếu | Bí thư - CT HĐND | 0976 484 879 |  |  |  |
| 2 | Trần Huỳnh Thanh | Phó Bí thư thường trực | 0989 049 352 |  |  |  |
| 3 | Đinh Thế Trọng | Phó Bí thư - CT UBND | 0942 750 645 |  |  |  |
| 4 | Huỳnh Trung Tài | UV BTV - Trưởng BXD Đảng ủy | 0906 981 543 |  |  |  |
| 5 | Trần Thạch Cương | UV BTV - CN UBKT Đảng ủy | 0977 605 364 |  |  |  |
| 6 | Phạm Ngô Phúc Nguyên | UV BTV - CT. MTTQ | 0937 212 920 |  |  |  |
| 7 | Châu Ngọc Bích | UV BTV - PCT. UBND | 0919 600 733 |  |  |  |
| 8 | Ngô Vũ Bảo | UV BTV - Trưởng Công an | 0982 864 557 |  |  |  |
| 9 | Nguyễn Văn Ngà | UV BTV CHT BCHQS xã | 0975 345 097 |  |  |  |
| 10 | Võ Thị Thanh Hằng | UV BCH - CVP Đảng ủy | 0915 770 757 |  |  |  |
| 11 | Đinh Quốc Huy | UV BCH - CVP UBND | 0916 640 118 |  |  |  |
| 12 | Nguyễn Thị Hạnh Duyên | UV BCH - Trưởng phòng VHXH | 0942 774 838 |  |  |  |
| 13 | Mai Thị Yến Trang | UV BCH - Trưởng Phòng KT | 0827 854 887 |  |  |  |
| 14 | Nguyễn Thị Anh Thư | UV BCH - Phó Trưởng BXD Đảng | 0914 610 004 |  |  |  |
| 15 | Nguyễn Tấn Phát | UV BCH - GĐ TT chính trị | 0973 726 396 |  |  |  |
| 16 | Lý Thị Anh Thư | UV BCH - PCN UBKT Đảng | 0914 610 004 |  |  |  |
| 17 | Nguyễn Văn Thắng | UV BCH - Phó Trưởng Công an | 0913 383 957 |  |  |  |
| 18 | Nguyễn Thị Thanh Bình | UV BCH - CT. HLHPN | 0965 615 619 |  |  |  |
| 19 | Nguyễn Văn Hồng | UV BCH - CT. HND | 0909 444152 |  |  |  |
| 20 | Nguyễn Thanh Lộc | UV BCH - Phó CHT BCHQS | 0966 097 314 |  |  |  |
| 21 | Bành Minh Lợi | PTP KT | 0978 931 938 |  |  |  |
| 22 | Trần Văn Chiến | PTP VHXH | 0977 831 496 |  |  |  |
| 23 | Lý Thị Thắm | Phó GĐ TTPVHCC | 0976 447 408 |  |  |  |
| 24 | Nguyễn Thành Trung | GĐ TTCUDVC / Ấp 1, đường Nguyễn Bính | 0976 162 092 |  |  |  |
| 25 | Châu Thị Ngọc Hoa | Phó GĐ TTCUDVC | 0941 628 336 |  |  |  |

### XÃ CẦU KHỞI

- Nhóm: 1
- Mã/STT nhóm: 95

#### ĐT bàn 02763 773 823; email: ubndcaukhoi-dmc@tayninh.gov.vn

#### Đảng ủy và các Ban

#### Địa chỉ:

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 1 | Nguyễn Thị Thu Hương | Bí thư - CT.HĐND | 0918 383 787 |  |  |  |
| 2 | Trần Thị Thu Hiền | Phó Bí thư - CT UB.MTTQ | 0834 150 781 |  |  |  |
| 4 | Lê Khắc Điệp | UVBTV - Trưởng Ban Xây dựng Đảng | 0979 902 189 |  |  |  |
| 16 | Thi Khắc Huy | PTB Xây dựng Đảng | 0969 495 797 |  |  |  |
| 5 | Võ Ngọc Thiên Kim | UVBTV - CN UBKT Đảng uỷ xã | 0907 367 626 |  |  |  |
| 17 | Lý Thị Minh Kiều | Phó CN UBKT Đảng uỷ xã | 0975 376 716 |  |  |  |
| 15 | Nguyễn Hồng Thái | Chánh VP Đảng uỷ | 0933 337 707 |  |  |  |
| 18 | Nguyễn Chí Thanh | PCT MTTQ, Bí thư ĐTN xã | 0972 777 857 |  |  |  |
| 19 | Lê Thị Mỹ Lệ | PCT MTTQ, CT Hội PN | 0946 603 314 |  |  |  |
| 20 | Lê Minh Thưởng | PCT MTTQ, Chủ tịch Hội Nông dân xã | 0914 773 533 |  |  |  |

#### Hội đồng nhân dân và UBND

#### Địa chỉ:

#### Nguyễn Thị Thu Hương

- Chức vụ/ghi chú: Bí thư - CT.HĐND
- Di động: 0918 383 787

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 6 | Đỗ Diệp Tuyền | UVBTV - PCT HĐND xã | 0972 966 990 |  |  |  |
| 7 | Hà Duy Thanh | UVBTV- PCT UBND xã | 0902 585 779 |  |  |  |
| 3 | Lê Minh Trung | Phó Bí thư - CT UBND | 0943 871 007 |  |  |  |
| 10 | Lê Khắc Lộc | PCT UBND xã | 0913 987 545 |  |  |  |
| 11 | Nguyễn Hùng Cứ | Phó Trưởng Công an | 0792 969 986 |  |  |  |
| 12 | Lê Minh Phương | Chánh VP.HĐND và UBND xã | 0398 962 753 |  |  |  |
| 13 | Phạm Vũ Nguyệt Thu | Trưởng Phòng Kinh tế | 0818 667 985 |  |  |  |
| 14 | Nguyễn Quốc Cường | Trưởng Phòng Văn hóa - Xã hội | 0913 449 331 |  |  |  |
| 8 | Văn Minh Trí | UVBTV- Trưởng Công an | 0945 259 929 |  |  |  |
| 9 | Nguyễn Tuấn Anh | UVBTV - CHT BCHQS | 0818 888 550 |  |  |  |

### XÃ LỘC NINH

- Nhóm: 1
- Mã/STT nhóm: 96

### Đảng ủy Lộc Ninh - Địa chỉ: số 1481, ấp Phước Lộc, xã Lộc Ninh

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 1 | Đặng Thanh Liêm | Bí thư | 0918 074 380 |  |  |  |
| 2 | Đỗ Tài Công | Phó Bí thư Thường trực | 0913 877 415 |  |  |  |
| 3 | Trần Lê Nhật Thanh | UV BTV - CN UBKT | 0919 111 957 |  |  |  |
| 4 | Nguyễn Vũ Mạnh | UV BCH - PCN UBKT | 0888 126 970 |  |  |  |
| 5 | Đỗ Tuấn Kiệt | PCN UBKT | 0343 575 685 |  |  |  |
| 6 | Tô Minh Tâm | UV BTV - TB Xây dựng đảng | 0912 990 856 |  |  |  |
| 7 | Huỳnh Anh Hy | UV BCH - PTB Xây dựng đảng | 0938 316 274 |  |  |  |
| 8 | Đào Quốc Trọng | UV BCH - CVP Đảng ủy | 0973 359 655 |  |  |  |
| 9 | Nguyễn Minh Kha | Phó CVP Đảng uỷ | 0986 416 784 |  |  |  |
| 10 | Huỳnh Trung Tấn | UV BTV - Chủ tịch MTTQ xã | 0946 456 585 |  |  |  |
| 11 | Nguyễn Thị Thuý Oanh | UV BCH - PCT MTTQ, CT Hội PN | 0989 919 006 |  |  |  |
| 12 | Võ Văn Hứng | UV BCH - PCT MTTQ, CT Hội ND | 0973 396 787 |  |  |  |
| 13 | Lâm Thị Phụng | UV BCH - PCT MTTQ, BT Đoàn TN | 0979 049 893 |  |  |  |

### HĐND Lộc Ninh - Địa chỉ: số 498, ấp Lộc Tân, xã Lộc Ninh

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 14 | Đỗ Thị Thanh Loan | UV BTV - PCT HĐND | 0941 412 587 |  |  |  |
| 15 | Nguyễn Hữu Dư | Ban Kinh tế - HĐND | 0386 883 567 |  |  |  |
| 16 | Trần Ngọc Điệp | Ban VHXH - HĐND | 0964 922 719 |  |  |  |

### UBND xã Lộc Ninh- ĐT bàn: 02763.724.108 ; email: ubndlocninh@tayninh.gov.vn -

### Địa chỉ: số 498, ấp Lộc Tân, xã Lộc Ninh

| STT | Họ và tên | Chức vụ | Di động | Điện thoại cơ quan | Email | Địa chỉ |
|---:|---|---|---|---|---|---|
| 17 | Nguyễn Hoài Phương | Phó Bí thư - CT UBND | 0918 779 300 |  |  |  |
| 18 | Nguyễn Văn Dũng | UV BTV - PCT UBND - kiêm GĐ TT Hành chính công | 0984 791 540 |  |  |  |
| 19 | Đặng Thị Huệ | UV BTV - PCT UBND | 0987 439 696 |  |  |  |
| 20 | Trần Duy Phương | UV BCH - CVP HĐND và UBND | 0339 003 498 |  |  |  |
| 21 | Nguyễn Thị Thu Hà | PCVP HĐND và UBND | 0985 985 044 |  |  |  |
| 22 | Nguyễn Đình Hiển | UV BCH - Trưởng phòng kinh tế | 0917 985 524 |  |  |  |
| 23 | Nguyễn Minh Toàn | PTP kinh tế | 0974 565 754 |  |  |  |
| 24 | Nguyễn Thị Thuý Oanh | UV BCH - TP Văn hóa - Xã hội | 0947 528 423 |  |  |  |
| 25 | Nguyễn Thị Thương | PTP Văn hóa - Xã hội | 0948 902 408 |  |  |  |
| 27 | Lê Hồng Thịnh | PGĐ TT Hành chính công | 0916 934 443 |  |  |  |
| 28 | Đỗ Hoàng Phúc | GĐ TT Cung ứng DVSN công | 0946 601 270 |  |  |  |
| 29 | Nguyễn Văn Vệ | PGĐ TT Cung ứng DVSN công | 0382 668 680 |  |  |  |
| 30 | Nguyễn Hồng Phong | UV BTV - Trưởng Công an | 0918 383 494 |  |  |  |
| 31 | Nguyễn Xuân Thắng | UV BCH - Phó trưởng Công an | 0909 717 867 |  |  |  |
| 32 | Nguyễn Quốc Hùng | Phó trưởng Công an | 0947 507 080 |  |  |  |
| 33 | Lê Trọng Nghĩa | Phó trưởng Công an | 0973 303 030 |  |  |  |
| 34 | Phạm Tử Khang | Phó trưởng Công an | 0973 317 799 |  |  |  |
| 35 | Tạ Văn Phúc | Phó trưởng Công an | 0962 577 270 |  |  |  |
| 36 | Nguyễn Trọng Tải | UV BTV - CHT BCH Quân sự | 0985 722 883 |  |  |  |
| 37 | Hoàng Ngọc Bá Khương | UV BCH - Phó CHT BCH Quân sự | 096 681 3054 |  |  |  |

# 5. Từ khóa RAG

`danh bạ điện thoại Tây Ninh`, `số điện thoại`, `di động`, `điện thoại cơ quan`, `email`, `địa chỉ`, `chức vụ`, `cơ quan`, `Tỉnh ủy`, `UBND tỉnh`, `Sở ngành`, `xã phường`, `cơ quan ngành dọc`

# 6. Ghi chú chất lượng dữ liệu

- Tài liệu phản ánh đúng dữ liệu workbook nguồn, không tự xác minh hoặc cập nhật từ nguồn ngoài.
- Cách viết tên người, chức danh, tên cơ quan và số liên hệ được giữ nguyên tối đa để tránh sai lệch.
- Ô trống không được tự điền.
- Khi sử dụng cho danh sách liên hệ chính thức, nên rà soát lại với cơ quan quản lý danh bạ.