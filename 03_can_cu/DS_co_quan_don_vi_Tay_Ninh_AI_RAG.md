---
title: "Danh sách cơ quan, đơn vị trên địa bàn tỉnh Tây Ninh"
document_type: "Danh mục cơ quan, đơn vị"
source_file: "DS co quan, don vi tren dia ban tinh(1).xlsx"
source_sheet: "Sheet 1"
total_entities: 111
local_governments: 96
communes: 82
wards: 14
provincial_departments_agencies: 15
ai_ready: true
rag_ready: true
---

# DANH SÁCH CƠ QUAN, ĐƠN VỊ TRÊN ĐỊA BÀN TỈNH TÂY NINH

> **Nguyên tắc biên tập cho AI/RAG:** Tên cơ quan, đơn vị được giữ nguyên theo bảng Excel nguồn. Không tự sửa chính tả, dấu câu, tên gọi hoặc suy diễn cơ cấu tổ chức ngoài dữ liệu gốc. Các mã `LOCAL-*` và `PROV-*` chỉ là mã kỹ thuật bổ sung để AI/RAG định danh ổn định, không phải mã hành chính chính thức.

# 1. Thông tin tổng quan

- Tổng số cơ quan, đơn vị: **111**.
- Nhóm xã/phường: **96** đơn vị.
  - UBND xã: **82**.
  - UBND phường: **14**.
- Nhóm sở, ngành tỉnh: **15** đơn vị.

# 2. Cấu trúc dữ liệu nguồn

| Trường | Ý nghĩa |
|---|---|
| Số thứ tự | Số thứ tự trong từng nhóm của bảng nguồn |
| Nhóm cơ quan, đơn vị | Phân nhóm `xã; phường` hoặc `sở; ngành tỉnh` |
| Tên cơ quan, đơn vị | Tên đơn vị theo bảng nguồn |

> **Lưu ý:** Cột `Số thứ tự` được đánh lại từ 1 khi chuyển sang nhóm `sở; ngành tỉnh`; vì vậy không sử dụng riêng số thứ tự nguồn làm khóa duy nhất. Khi định danh, dùng kết hợp nhóm + số thứ tự hoặc mã kỹ thuật trong file Markdown này.

# 3. Danh sách UBND xã, phường

| Mã AI/RAG | STT nguồn | Loại | Tên cơ quan, đơn vị |
|---|---:|---|---|
| LOCAL-001 | 1 | xã | UBND xã Tân Lập |
| LOCAL-002 | 2 | xã | UBND xã Phước Vinh |
| LOCAL-003 | 3 | xã | UBND xã Trà Vong |
| LOCAL-004 | 4 | xã | UBND xã Hậu Nghĩa |
| LOCAL-005 | 5 | xã | UBND xã Long Chữ |
| LOCAL-006 | 6 | xã | UBND xã Mỹ An |
| LOCAL-007 | 7 | xã | UBND xã Hảo Đước |
| LOCAL-008 | 8 | xã | UBND xã Mỹ Thạnh |
| LOCAL-009 | 9 | phường | UBND phường Gò Dầu |
| LOCAL-010 | 10 | xã | UBND xã Tân Đông |
| LOCAL-011 | 11 | phường | UBND phường An Tịnh |
| LOCAL-012 | 12 | phường | UBND phường Ninh Thạnh |
| LOCAL-013 | 13 | xã | UBND xã Hưng Điền |
| LOCAL-014 | 14 | xã | UBND xã Lộc Ninh |
| LOCAL-015 | 15 | xã | UBND xã Mỹ Hạnh |
| LOCAL-016 | 16 | xã | UBND xã Mỹ Lệ |
| LOCAL-017 | 17 | xã | UBND xã Tân Biên |
| LOCAL-018 | 18 | xã | UBND xã Thạnh Bình |
| LOCAL-019 | 19 | xã | UBND xã Thạnh Phước |
| LOCAL-020 | 20 | xã | UBND xã Vĩnh Thạnh |
| LOCAL-021 | 21 | xã | UBND xã Nhơn Ninh |
| LOCAL-022 | 22 | xã | UBND xã Thuận Mỹ |
| LOCAL-023 | 23 | xã | UBND xã Tân Lân |
| LOCAL-024 | 24 | phường | UBND phường Gia Lộc |
| LOCAL-025 | 25 | xã | UBND xã Tân Phú |
| LOCAL-026 | 26 | xã | UBND xã Long Hựu |
| LOCAL-027 | 27 | phường | UBND phường Bình Minh |
| LOCAL-028 | 28 | xã | UBND xã Cần Đước |
| LOCAL-029 | 29 | xã | UBND xã An Lục Long |
| LOCAL-030 | 30 | phường | UBND phường Kiến Tường |
| LOCAL-031 | 31 | xã | UBND xã Đức Hòa |
| LOCAL-032 | 32 | xã | UBND xã Thạnh Đức |
| LOCAL-033 | 33 | xã | UBND xã Mỹ Quý |
| LOCAL-034 | 34 | xã | UBND xã Long Thuận |
| LOCAL-035 | 35 | xã | UBND xã Bến Lức |
| LOCAL-036 | 36 | xã | UBND xã Bình Hiệp |
| LOCAL-037 | 37 | phường | UBND phường Trảng Bàng |
| LOCAL-038 | 38 | xã | UBND xã Phước Thạnh |
| LOCAL-039 | 39 | xã | UBND xã Tân Tập |
| LOCAL-040 | 40 | xã | UBND xã Thạnh Lợi |
| LOCAL-041 | 41 | xã | UBND xã Bến Cầu |
| LOCAL-042 | 42 | xã | UBND xã Bình Hòa |
| LOCAL-043 | 43 | xã | UBND xã Lương Hòa |
| LOCAL-044 | 44 | xã | UBND xã Tân Hòa |
| LOCAL-045 | 45 | xã | UBND xã Bình Thạnh |
| LOCAL-046 | 46 | xã | UBND xã Long Cang |
| LOCAL-047 | 47 | phường | UBND phường Thanh Điền |
| LOCAL-048 | 48 | xã | UBND xã Dương Minh Châu |
| LOCAL-049 | 49 | xã | UBND xã Cần Giuộc |
| LOCAL-050 | 50 | xã | UBND xã Mỹ Yên |
| LOCAL-051 | 51 | xã | UBND xã Mộc Hóa |
| LOCAL-052 | 52 | xã | UBND xã Tầm Vu |
| LOCAL-053 | 53 | xã | UBND xã Truông Mít |
| LOCAL-054 | 54 | xã | UBND xã Ninh Điền |
| LOCAL-055 | 55 | xã | UBND xã Hậu Thạnh |
| LOCAL-056 | 56 | phường | UBND phường Tân Ninh |
| LOCAL-057 | 57 | xã | UBND xã Đông Thạnh |
| LOCAL-058 | 58 | xã | UBND xã Hiệp Hòa |
| LOCAL-059 | 59 | phường | UBND phường Tân An |
| LOCAL-060 | 60 | phường | UBND phường Long Hoa |
| LOCAL-061 | 61 | phường | UBND phường Hòa Thành |
| LOCAL-062 | 62 | xã | UBND xã Hòa Khánh |
| LOCAL-063 | 63 | xã | UBND xã Vĩnh Châu |
| LOCAL-064 | 64 | xã | UBND xã Vĩnh Công |
| LOCAL-065 | 65 | xã | UBND xã Rạch Kiến |
| LOCAL-066 | 66 | phường | UBND phường Long An |
| LOCAL-067 | 67 | xã | UBND xã Phước Lý |
| LOCAL-068 | 68 | xã | UBND xã Tân Thạnh |
| LOCAL-069 | 69 | xã | UBND xã Tân Hưng |
| LOCAL-070 | 70 | xã | UBND xã Tuyên Bình |
| LOCAL-071 | 71 | xã | UBND xã Tân Thành |
| LOCAL-072 | 72 | xã | UBND xã Tân Tây |
| LOCAL-073 | 73 | xã | UBND xã Khánh Hưng |
| LOCAL-074 | 74 | xã | UBND xã Đức Huệ |
| LOCAL-075 | 75 | xã | UBND xã Mỹ Lộc |
| LOCAL-076 | 76 | xã | UBND xã Vĩnh Hưng |
| LOCAL-077 | 77 | xã | UBND xã Thủ Thừa |
| LOCAL-078 | 78 | xã | UBND xã Đức Lập |
| LOCAL-079 | 79 | xã | UBND xã Vàm Cỏ |
| LOCAL-080 | 80 | phường | UBND phường Khánh Hậu |
| LOCAL-081 | 81 | xã | UBND xã Tuyên Thạnh |
| LOCAL-082 | 82 | xã | UBND xã Nhựt Tảo |
| LOCAL-083 | 83 | xã | UBND xã Tân Trụ |
| LOCAL-084 | 84 | xã | UBND xã Thạnh Hóa |
| LOCAL-085 | 85 | xã | UBND xã Nhơn Hòa Lập |
| LOCAL-086 | 86 | xã | UBND xã Tân Long |
| LOCAL-087 | 87 | xã | UBND xã Tân Châu |
| LOCAL-088 | 88 | xã | UBND xã Phước Chỉ |
| LOCAL-089 | 89 | xã | UBND xã Bình Đức |
| LOCAL-090 | 90 | xã | UBND xã Châu Thành |
| LOCAL-091 | 91 | xã | UBND xã Hòa Hội |
| LOCAL-092 | 92 | xã | UBND xã Hưng Thuận |
| LOCAL-093 | 93 | xã | UBND xã Phước Vinh Tây |
| LOCAL-094 | 94 | xã | UBND xã Tân Hội |
| LOCAL-095 | 95 | xã | UBND xã Cầu Khởi |
| LOCAL-096 | 96 | xã | UBND xã An Ninh |

# 4. Danh sách sở, ngành tỉnh

| Mã AI/RAG | STT nguồn | Nhóm | Tên cơ quan, đơn vị |
|---|---:|---|---|
| PROV-001 | 1 | sở; ngành tỉnh | Thanh tra tỉnh |
| PROV-002 | 2 | sở; ngành tỉnh | Sở Giáo dục và Đào tạo |
| PROV-003 | 3 | sở; ngành tỉnh | Sở Tư pháp |
| PROV-004 | 4 | sở; ngành tỉnh | Sở Ngoại vụ |
| PROV-005 | 5 | sở; ngành tỉnh | Sở Công Thương |
| PROV-006 | 6 | sở; ngành tỉnh | Sở Nội vụ |
| PROV-007 | 7 | sở; ngành tỉnh | Sở Tài chính |
| PROV-008 | 8 | sở; ngành tỉnh | Sở Văn hóa; Thể thao và Du lịch |
| PROV-009 | 9 | sở; ngành tỉnh | Sở Khoa học và Công nghệ |
| PROV-010 | 10 | sở; ngành tỉnh | Sở Xây dựng |
| PROV-011 | 11 | sở; ngành tỉnh | Văn phòng Ủy ban nhân dân tỉnh |
| PROV-012 | 12 | sở; ngành tỉnh | Sở Y tế |
| PROV-013 | 13 | sở; ngành tỉnh | Sở Nông nghiệp và Môi trường |
| PROV-014 | 14 | sở; ngành tỉnh | Ban Quản lý Khu kinh tế |
| PROV-015 | 15 | sở; ngành tỉnh | Sở Dân tộc và Tôn giáo |

# 5. Bản ghi thực thể phục vụ AI/RAG

Các bản ghi dưới đây giúp AI truy xuất theo từng thực thể độc lập, tránh phụ thuộc vào việc phân mảnh bảng Markdown.

## LOCAL-001 — UBND xã Tân Lập

- `source_index`: 1
- `group`: xã; phường
- `entity_type`: xã
- `official_name`: UBND xã Tân Lập
- `search_name`: xã Tân Lập
- `administrative_level`: cấp xã

## LOCAL-002 — UBND xã Phước Vinh

- `source_index`: 2
- `group`: xã; phường
- `entity_type`: xã
- `official_name`: UBND xã Phước Vinh
- `search_name`: xã Phước Vinh
- `administrative_level`: cấp xã

## LOCAL-003 — UBND xã Trà Vong

- `source_index`: 3
- `group`: xã; phường
- `entity_type`: xã
- `official_name`: UBND xã Trà Vong
- `search_name`: xã Trà Vong
- `administrative_level`: cấp xã

## LOCAL-004 — UBND xã Hậu Nghĩa

- `source_index`: 4
- `group`: xã; phường
- `entity_type`: xã
- `official_name`: UBND xã Hậu Nghĩa
- `search_name`: xã Hậu Nghĩa
- `administrative_level`: cấp xã

## LOCAL-005 — UBND xã Long Chữ

- `source_index`: 5
- `group`: xã; phường
- `entity_type`: xã
- `official_name`: UBND xã Long Chữ
- `search_name`: xã Long Chữ
- `administrative_level`: cấp xã

## LOCAL-006 — UBND xã Mỹ An

- `source_index`: 6
- `group`: xã; phường
- `entity_type`: xã
- `official_name`: UBND xã Mỹ An
- `search_name`: xã Mỹ An
- `administrative_level`: cấp xã

## LOCAL-007 — UBND xã Hảo Đước

- `source_index`: 7
- `group`: xã; phường
- `entity_type`: xã
- `official_name`: UBND xã Hảo Đước
- `search_name`: xã Hảo Đước
- `administrative_level`: cấp xã

## LOCAL-008 — UBND xã Mỹ Thạnh

- `source_index`: 8
- `group`: xã; phường
- `entity_type`: xã
- `official_name`: UBND xã Mỹ Thạnh
- `search_name`: xã Mỹ Thạnh
- `administrative_level`: cấp xã

## LOCAL-009 — UBND phường Gò Dầu

- `source_index`: 9
- `group`: xã; phường
- `entity_type`: phường
- `official_name`: UBND phường Gò Dầu
- `search_name`: phường Gò Dầu
- `administrative_level`: cấp xã

## LOCAL-010 — UBND xã Tân Đông

- `source_index`: 10
- `group`: xã; phường
- `entity_type`: xã
- `official_name`: UBND xã Tân Đông
- `search_name`: xã Tân Đông
- `administrative_level`: cấp xã

## LOCAL-011 — UBND phường An Tịnh

- `source_index`: 11
- `group`: xã; phường
- `entity_type`: phường
- `official_name`: UBND phường An Tịnh
- `search_name`: phường An Tịnh
- `administrative_level`: cấp xã

## LOCAL-012 — UBND phường Ninh Thạnh

- `source_index`: 12
- `group`: xã; phường
- `entity_type`: phường
- `official_name`: UBND phường Ninh Thạnh
- `search_name`: phường Ninh Thạnh
- `administrative_level`: cấp xã

## LOCAL-013 — UBND xã Hưng Điền

- `source_index`: 13
- `group`: xã; phường
- `entity_type`: xã
- `official_name`: UBND xã Hưng Điền
- `search_name`: xã Hưng Điền
- `administrative_level`: cấp xã

## LOCAL-014 — UBND xã Lộc Ninh

- `source_index`: 14
- `group`: xã; phường
- `entity_type`: xã
- `official_name`: UBND xã Lộc Ninh
- `search_name`: xã Lộc Ninh
- `administrative_level`: cấp xã

## LOCAL-015 — UBND xã Mỹ Hạnh

- `source_index`: 15
- `group`: xã; phường
- `entity_type`: xã
- `official_name`: UBND xã Mỹ Hạnh
- `search_name`: xã Mỹ Hạnh
- `administrative_level`: cấp xã

## LOCAL-016 — UBND xã Mỹ Lệ

- `source_index`: 16
- `group`: xã; phường
- `entity_type`: xã
- `official_name`: UBND xã Mỹ Lệ
- `search_name`: xã Mỹ Lệ
- `administrative_level`: cấp xã

## LOCAL-017 — UBND xã Tân Biên

- `source_index`: 17
- `group`: xã; phường
- `entity_type`: xã
- `official_name`: UBND xã Tân Biên
- `search_name`: xã Tân Biên
- `administrative_level`: cấp xã

## LOCAL-018 — UBND xã Thạnh Bình

- `source_index`: 18
- `group`: xã; phường
- `entity_type`: xã
- `official_name`: UBND xã Thạnh Bình
- `search_name`: xã Thạnh Bình
- `administrative_level`: cấp xã

## LOCAL-019 — UBND xã Thạnh Phước

- `source_index`: 19
- `group`: xã; phường
- `entity_type`: xã
- `official_name`: UBND xã Thạnh Phước
- `search_name`: xã Thạnh Phước
- `administrative_level`: cấp xã

## LOCAL-020 — UBND xã Vĩnh Thạnh

- `source_index`: 20
- `group`: xã; phường
- `entity_type`: xã
- `official_name`: UBND xã Vĩnh Thạnh
- `search_name`: xã Vĩnh Thạnh
- `administrative_level`: cấp xã

## LOCAL-021 — UBND xã Nhơn Ninh

- `source_index`: 21
- `group`: xã; phường
- `entity_type`: xã
- `official_name`: UBND xã Nhơn Ninh
- `search_name`: xã Nhơn Ninh
- `administrative_level`: cấp xã

## LOCAL-022 — UBND xã Thuận Mỹ

- `source_index`: 22
- `group`: xã; phường
- `entity_type`: xã
- `official_name`: UBND xã Thuận Mỹ
- `search_name`: xã Thuận Mỹ
- `administrative_level`: cấp xã

## LOCAL-023 — UBND xã Tân Lân

- `source_index`: 23
- `group`: xã; phường
- `entity_type`: xã
- `official_name`: UBND xã Tân Lân
- `search_name`: xã Tân Lân
- `administrative_level`: cấp xã

## LOCAL-024 — UBND phường Gia Lộc

- `source_index`: 24
- `group`: xã; phường
- `entity_type`: phường
- `official_name`: UBND phường Gia Lộc
- `search_name`: phường Gia Lộc
- `administrative_level`: cấp xã

## LOCAL-025 — UBND xã Tân Phú

- `source_index`: 25
- `group`: xã; phường
- `entity_type`: xã
- `official_name`: UBND xã Tân Phú
- `search_name`: xã Tân Phú
- `administrative_level`: cấp xã

## LOCAL-026 — UBND xã Long Hựu

- `source_index`: 26
- `group`: xã; phường
- `entity_type`: xã
- `official_name`: UBND xã Long Hựu
- `search_name`: xã Long Hựu
- `administrative_level`: cấp xã

## LOCAL-027 — UBND phường Bình Minh

- `source_index`: 27
- `group`: xã; phường
- `entity_type`: phường
- `official_name`: UBND phường Bình Minh
- `search_name`: phường Bình Minh
- `administrative_level`: cấp xã

## LOCAL-028 — UBND xã Cần Đước

- `source_index`: 28
- `group`: xã; phường
- `entity_type`: xã
- `official_name`: UBND xã Cần Đước
- `search_name`: xã Cần Đước
- `administrative_level`: cấp xã

## LOCAL-029 — UBND xã An Lục Long

- `source_index`: 29
- `group`: xã; phường
- `entity_type`: xã
- `official_name`: UBND xã An Lục Long
- `search_name`: xã An Lục Long
- `administrative_level`: cấp xã

## LOCAL-030 — UBND phường Kiến Tường

- `source_index`: 30
- `group`: xã; phường
- `entity_type`: phường
- `official_name`: UBND phường Kiến Tường
- `search_name`: phường Kiến Tường
- `administrative_level`: cấp xã

## LOCAL-031 — UBND xã Đức Hòa

- `source_index`: 31
- `group`: xã; phường
- `entity_type`: xã
- `official_name`: UBND xã Đức Hòa
- `search_name`: xã Đức Hòa
- `administrative_level`: cấp xã

## LOCAL-032 — UBND xã Thạnh Đức

- `source_index`: 32
- `group`: xã; phường
- `entity_type`: xã
- `official_name`: UBND xã Thạnh Đức
- `search_name`: xã Thạnh Đức
- `administrative_level`: cấp xã

## LOCAL-033 — UBND xã Mỹ Quý

- `source_index`: 33
- `group`: xã; phường
- `entity_type`: xã
- `official_name`: UBND xã Mỹ Quý
- `search_name`: xã Mỹ Quý
- `administrative_level`: cấp xã

## LOCAL-034 — UBND xã Long Thuận

- `source_index`: 34
- `group`: xã; phường
- `entity_type`: xã
- `official_name`: UBND xã Long Thuận
- `search_name`: xã Long Thuận
- `administrative_level`: cấp xã

## LOCAL-035 — UBND xã Bến Lức

- `source_index`: 35
- `group`: xã; phường
- `entity_type`: xã
- `official_name`: UBND xã Bến Lức
- `search_name`: xã Bến Lức
- `administrative_level`: cấp xã

## LOCAL-036 — UBND xã Bình Hiệp

- `source_index`: 36
- `group`: xã; phường
- `entity_type`: xã
- `official_name`: UBND xã Bình Hiệp
- `search_name`: xã Bình Hiệp
- `administrative_level`: cấp xã

## LOCAL-037 — UBND phường Trảng Bàng

- `source_index`: 37
- `group`: xã; phường
- `entity_type`: phường
- `official_name`: UBND phường Trảng Bàng
- `search_name`: phường Trảng Bàng
- `administrative_level`: cấp xã

## LOCAL-038 — UBND xã Phước Thạnh

- `source_index`: 38
- `group`: xã; phường
- `entity_type`: xã
- `official_name`: UBND xã Phước Thạnh
- `search_name`: xã Phước Thạnh
- `administrative_level`: cấp xã

## LOCAL-039 — UBND xã Tân Tập

- `source_index`: 39
- `group`: xã; phường
- `entity_type`: xã
- `official_name`: UBND xã Tân Tập
- `search_name`: xã Tân Tập
- `administrative_level`: cấp xã

## LOCAL-040 — UBND xã Thạnh Lợi

- `source_index`: 40
- `group`: xã; phường
- `entity_type`: xã
- `official_name`: UBND xã Thạnh Lợi
- `search_name`: xã Thạnh Lợi
- `administrative_level`: cấp xã

## LOCAL-041 — UBND xã Bến Cầu

- `source_index`: 41
- `group`: xã; phường
- `entity_type`: xã
- `official_name`: UBND xã Bến Cầu
- `search_name`: xã Bến Cầu
- `administrative_level`: cấp xã

## LOCAL-042 — UBND xã Bình Hòa

- `source_index`: 42
- `group`: xã; phường
- `entity_type`: xã
- `official_name`: UBND xã Bình Hòa
- `search_name`: xã Bình Hòa
- `administrative_level`: cấp xã

## LOCAL-043 — UBND xã Lương Hòa

- `source_index`: 43
- `group`: xã; phường
- `entity_type`: xã
- `official_name`: UBND xã Lương Hòa
- `search_name`: xã Lương Hòa
- `administrative_level`: cấp xã

## LOCAL-044 — UBND xã Tân Hòa

- `source_index`: 44
- `group`: xã; phường
- `entity_type`: xã
- `official_name`: UBND xã Tân Hòa
- `search_name`: xã Tân Hòa
- `administrative_level`: cấp xã

## LOCAL-045 — UBND xã Bình Thạnh

- `source_index`: 45
- `group`: xã; phường
- `entity_type`: xã
- `official_name`: UBND xã Bình Thạnh
- `search_name`: xã Bình Thạnh
- `administrative_level`: cấp xã

## LOCAL-046 — UBND xã Long Cang

- `source_index`: 46
- `group`: xã; phường
- `entity_type`: xã
- `official_name`: UBND xã Long Cang
- `search_name`: xã Long Cang
- `administrative_level`: cấp xã

## LOCAL-047 — UBND phường Thanh Điền

- `source_index`: 47
- `group`: xã; phường
- `entity_type`: phường
- `official_name`: UBND phường Thanh Điền
- `search_name`: phường Thanh Điền
- `administrative_level`: cấp xã

## LOCAL-048 — UBND xã Dương Minh Châu

- `source_index`: 48
- `group`: xã; phường
- `entity_type`: xã
- `official_name`: UBND xã Dương Minh Châu
- `search_name`: xã Dương Minh Châu
- `administrative_level`: cấp xã

## LOCAL-049 — UBND xã Cần Giuộc

- `source_index`: 49
- `group`: xã; phường
- `entity_type`: xã
- `official_name`: UBND xã Cần Giuộc
- `search_name`: xã Cần Giuộc
- `administrative_level`: cấp xã

## LOCAL-050 — UBND xã Mỹ Yên

- `source_index`: 50
- `group`: xã; phường
- `entity_type`: xã
- `official_name`: UBND xã Mỹ Yên
- `search_name`: xã Mỹ Yên
- `administrative_level`: cấp xã

## LOCAL-051 — UBND xã Mộc Hóa

- `source_index`: 51
- `group`: xã; phường
- `entity_type`: xã
- `official_name`: UBND xã Mộc Hóa
- `search_name`: xã Mộc Hóa
- `administrative_level`: cấp xã

## LOCAL-052 — UBND xã Tầm Vu

- `source_index`: 52
- `group`: xã; phường
- `entity_type`: xã
- `official_name`: UBND xã Tầm Vu
- `search_name`: xã Tầm Vu
- `administrative_level`: cấp xã

## LOCAL-053 — UBND xã Truông Mít

- `source_index`: 53
- `group`: xã; phường
- `entity_type`: xã
- `official_name`: UBND xã Truông Mít
- `search_name`: xã Truông Mít
- `administrative_level`: cấp xã

## LOCAL-054 — UBND xã Ninh Điền

- `source_index`: 54
- `group`: xã; phường
- `entity_type`: xã
- `official_name`: UBND xã Ninh Điền
- `search_name`: xã Ninh Điền
- `administrative_level`: cấp xã

## LOCAL-055 — UBND xã Hậu Thạnh

- `source_index`: 55
- `group`: xã; phường
- `entity_type`: xã
- `official_name`: UBND xã Hậu Thạnh
- `search_name`: xã Hậu Thạnh
- `administrative_level`: cấp xã

## LOCAL-056 — UBND phường Tân Ninh

- `source_index`: 56
- `group`: xã; phường
- `entity_type`: phường
- `official_name`: UBND phường Tân Ninh
- `search_name`: phường Tân Ninh
- `administrative_level`: cấp xã

## LOCAL-057 — UBND xã Đông Thạnh

- `source_index`: 57
- `group`: xã; phường
- `entity_type`: xã
- `official_name`: UBND xã Đông Thạnh
- `search_name`: xã Đông Thạnh
- `administrative_level`: cấp xã

## LOCAL-058 — UBND xã Hiệp Hòa

- `source_index`: 58
- `group`: xã; phường
- `entity_type`: xã
- `official_name`: UBND xã Hiệp Hòa
- `search_name`: xã Hiệp Hòa
- `administrative_level`: cấp xã

## LOCAL-059 — UBND phường Tân An

- `source_index`: 59
- `group`: xã; phường
- `entity_type`: phường
- `official_name`: UBND phường Tân An
- `search_name`: phường Tân An
- `administrative_level`: cấp xã

## LOCAL-060 — UBND phường Long Hoa

- `source_index`: 60
- `group`: xã; phường
- `entity_type`: phường
- `official_name`: UBND phường Long Hoa
- `search_name`: phường Long Hoa
- `administrative_level`: cấp xã

## LOCAL-061 — UBND phường Hòa Thành

- `source_index`: 61
- `group`: xã; phường
- `entity_type`: phường
- `official_name`: UBND phường Hòa Thành
- `search_name`: phường Hòa Thành
- `administrative_level`: cấp xã

## LOCAL-062 — UBND xã Hòa Khánh

- `source_index`: 62
- `group`: xã; phường
- `entity_type`: xã
- `official_name`: UBND xã Hòa Khánh
- `search_name`: xã Hòa Khánh
- `administrative_level`: cấp xã

## LOCAL-063 — UBND xã Vĩnh Châu

- `source_index`: 63
- `group`: xã; phường
- `entity_type`: xã
- `official_name`: UBND xã Vĩnh Châu
- `search_name`: xã Vĩnh Châu
- `administrative_level`: cấp xã

## LOCAL-064 — UBND xã Vĩnh Công

- `source_index`: 64
- `group`: xã; phường
- `entity_type`: xã
- `official_name`: UBND xã Vĩnh Công
- `search_name`: xã Vĩnh Công
- `administrative_level`: cấp xã

## LOCAL-065 — UBND xã Rạch Kiến

- `source_index`: 65
- `group`: xã; phường
- `entity_type`: xã
- `official_name`: UBND xã Rạch Kiến
- `search_name`: xã Rạch Kiến
- `administrative_level`: cấp xã

## LOCAL-066 — UBND phường Long An

- `source_index`: 66
- `group`: xã; phường
- `entity_type`: phường
- `official_name`: UBND phường Long An
- `search_name`: phường Long An
- `administrative_level`: cấp xã

## LOCAL-067 — UBND xã Phước Lý

- `source_index`: 67
- `group`: xã; phường
- `entity_type`: xã
- `official_name`: UBND xã Phước Lý
- `search_name`: xã Phước Lý
- `administrative_level`: cấp xã

## LOCAL-068 — UBND xã Tân Thạnh

- `source_index`: 68
- `group`: xã; phường
- `entity_type`: xã
- `official_name`: UBND xã Tân Thạnh
- `search_name`: xã Tân Thạnh
- `administrative_level`: cấp xã

## LOCAL-069 — UBND xã Tân Hưng

- `source_index`: 69
- `group`: xã; phường
- `entity_type`: xã
- `official_name`: UBND xã Tân Hưng
- `search_name`: xã Tân Hưng
- `administrative_level`: cấp xã

## LOCAL-070 — UBND xã Tuyên Bình

- `source_index`: 70
- `group`: xã; phường
- `entity_type`: xã
- `official_name`: UBND xã Tuyên Bình
- `search_name`: xã Tuyên Bình
- `administrative_level`: cấp xã

## LOCAL-071 — UBND xã Tân Thành

- `source_index`: 71
- `group`: xã; phường
- `entity_type`: xã
- `official_name`: UBND xã Tân Thành
- `search_name`: xã Tân Thành
- `administrative_level`: cấp xã

## LOCAL-072 — UBND xã Tân Tây

- `source_index`: 72
- `group`: xã; phường
- `entity_type`: xã
- `official_name`: UBND xã Tân Tây
- `search_name`: xã Tân Tây
- `administrative_level`: cấp xã

## LOCAL-073 — UBND xã Khánh Hưng

- `source_index`: 73
- `group`: xã; phường
- `entity_type`: xã
- `official_name`: UBND xã Khánh Hưng
- `search_name`: xã Khánh Hưng
- `administrative_level`: cấp xã

## LOCAL-074 — UBND xã Đức Huệ

- `source_index`: 74
- `group`: xã; phường
- `entity_type`: xã
- `official_name`: UBND xã Đức Huệ
- `search_name`: xã Đức Huệ
- `administrative_level`: cấp xã

## LOCAL-075 — UBND xã Mỹ Lộc

- `source_index`: 75
- `group`: xã; phường
- `entity_type`: xã
- `official_name`: UBND xã Mỹ Lộc
- `search_name`: xã Mỹ Lộc
- `administrative_level`: cấp xã

## LOCAL-076 — UBND xã Vĩnh Hưng

- `source_index`: 76
- `group`: xã; phường
- `entity_type`: xã
- `official_name`: UBND xã Vĩnh Hưng
- `search_name`: xã Vĩnh Hưng
- `administrative_level`: cấp xã

## LOCAL-077 — UBND xã Thủ Thừa

- `source_index`: 77
- `group`: xã; phường
- `entity_type`: xã
- `official_name`: UBND xã Thủ Thừa
- `search_name`: xã Thủ Thừa
- `administrative_level`: cấp xã

## LOCAL-078 — UBND xã Đức Lập

- `source_index`: 78
- `group`: xã; phường
- `entity_type`: xã
- `official_name`: UBND xã Đức Lập
- `search_name`: xã Đức Lập
- `administrative_level`: cấp xã

## LOCAL-079 — UBND xã Vàm Cỏ

- `source_index`: 79
- `group`: xã; phường
- `entity_type`: xã
- `official_name`: UBND xã Vàm Cỏ
- `search_name`: xã Vàm Cỏ
- `administrative_level`: cấp xã

## LOCAL-080 — UBND phường Khánh Hậu

- `source_index`: 80
- `group`: xã; phường
- `entity_type`: phường
- `official_name`: UBND phường Khánh Hậu
- `search_name`: phường Khánh Hậu
- `administrative_level`: cấp xã

## LOCAL-081 — UBND xã Tuyên Thạnh

- `source_index`: 81
- `group`: xã; phường
- `entity_type`: xã
- `official_name`: UBND xã Tuyên Thạnh
- `search_name`: xã Tuyên Thạnh
- `administrative_level`: cấp xã

## LOCAL-082 — UBND xã Nhựt Tảo

- `source_index`: 82
- `group`: xã; phường
- `entity_type`: xã
- `official_name`: UBND xã Nhựt Tảo
- `search_name`: xã Nhựt Tảo
- `administrative_level`: cấp xã

## LOCAL-083 — UBND xã Tân Trụ

- `source_index`: 83
- `group`: xã; phường
- `entity_type`: xã
- `official_name`: UBND xã Tân Trụ
- `search_name`: xã Tân Trụ
- `administrative_level`: cấp xã

## LOCAL-084 — UBND xã Thạnh Hóa

- `source_index`: 84
- `group`: xã; phường
- `entity_type`: xã
- `official_name`: UBND xã Thạnh Hóa
- `search_name`: xã Thạnh Hóa
- `administrative_level`: cấp xã

## LOCAL-085 — UBND xã Nhơn Hòa Lập

- `source_index`: 85
- `group`: xã; phường
- `entity_type`: xã
- `official_name`: UBND xã Nhơn Hòa Lập
- `search_name`: xã Nhơn Hòa Lập
- `administrative_level`: cấp xã

## LOCAL-086 — UBND xã Tân Long

- `source_index`: 86
- `group`: xã; phường
- `entity_type`: xã
- `official_name`: UBND xã Tân Long
- `search_name`: xã Tân Long
- `administrative_level`: cấp xã

## LOCAL-087 — UBND xã Tân Châu

- `source_index`: 87
- `group`: xã; phường
- `entity_type`: xã
- `official_name`: UBND xã Tân Châu
- `search_name`: xã Tân Châu
- `administrative_level`: cấp xã

## LOCAL-088 — UBND xã Phước Chỉ

- `source_index`: 88
- `group`: xã; phường
- `entity_type`: xã
- `official_name`: UBND xã Phước Chỉ
- `search_name`: xã Phước Chỉ
- `administrative_level`: cấp xã

## LOCAL-089 — UBND xã Bình Đức

- `source_index`: 89
- `group`: xã; phường
- `entity_type`: xã
- `official_name`: UBND xã Bình Đức
- `search_name`: xã Bình Đức
- `administrative_level`: cấp xã

## LOCAL-090 — UBND xã Châu Thành

- `source_index`: 90
- `group`: xã; phường
- `entity_type`: xã
- `official_name`: UBND xã Châu Thành
- `search_name`: xã Châu Thành
- `administrative_level`: cấp xã

## LOCAL-091 — UBND xã Hòa Hội

- `source_index`: 91
- `group`: xã; phường
- `entity_type`: xã
- `official_name`: UBND xã Hòa Hội
- `search_name`: xã Hòa Hội
- `administrative_level`: cấp xã

## LOCAL-092 — UBND xã Hưng Thuận

- `source_index`: 92
- `group`: xã; phường
- `entity_type`: xã
- `official_name`: UBND xã Hưng Thuận
- `search_name`: xã Hưng Thuận
- `administrative_level`: cấp xã

## LOCAL-093 — UBND xã Phước Vinh Tây

- `source_index`: 93
- `group`: xã; phường
- `entity_type`: xã
- `official_name`: UBND xã Phước Vinh Tây
- `search_name`: xã Phước Vinh Tây
- `administrative_level`: cấp xã

## LOCAL-094 — UBND xã Tân Hội

- `source_index`: 94
- `group`: xã; phường
- `entity_type`: xã
- `official_name`: UBND xã Tân Hội
- `search_name`: xã Tân Hội
- `administrative_level`: cấp xã

## LOCAL-095 — UBND xã Cầu Khởi

- `source_index`: 95
- `group`: xã; phường
- `entity_type`: xã
- `official_name`: UBND xã Cầu Khởi
- `search_name`: xã Cầu Khởi
- `administrative_level`: cấp xã

## LOCAL-096 — UBND xã An Ninh

- `source_index`: 96
- `group`: xã; phường
- `entity_type`: xã
- `official_name`: UBND xã An Ninh
- `search_name`: xã An Ninh
- `administrative_level`: cấp xã

## PROV-001 — Thanh tra tỉnh

- `source_index`: 1
- `group`: sở; ngành tỉnh
- `entity_type`: cơ quan cấp tỉnh
- `official_name`: Thanh tra tỉnh
- `search_name`: Thanh tra tỉnh
- `administrative_level`: cấp tỉnh

## PROV-002 — Sở Giáo dục và Đào tạo

- `source_index`: 2
- `group`: sở; ngành tỉnh
- `entity_type`: cơ quan cấp tỉnh
- `official_name`: Sở Giáo dục và Đào tạo
- `search_name`: Sở Giáo dục và Đào tạo
- `administrative_level`: cấp tỉnh

## PROV-003 — Sở Tư pháp

- `source_index`: 3
- `group`: sở; ngành tỉnh
- `entity_type`: cơ quan cấp tỉnh
- `official_name`: Sở Tư pháp
- `search_name`: Sở Tư pháp
- `administrative_level`: cấp tỉnh

## PROV-004 — Sở Ngoại vụ

- `source_index`: 4
- `group`: sở; ngành tỉnh
- `entity_type`: cơ quan cấp tỉnh
- `official_name`: Sở Ngoại vụ
- `search_name`: Sở Ngoại vụ
- `administrative_level`: cấp tỉnh

## PROV-005 — Sở Công Thương

- `source_index`: 5
- `group`: sở; ngành tỉnh
- `entity_type`: cơ quan cấp tỉnh
- `official_name`: Sở Công Thương
- `search_name`: Sở Công Thương
- `administrative_level`: cấp tỉnh

## PROV-006 — Sở Nội vụ

- `source_index`: 6
- `group`: sở; ngành tỉnh
- `entity_type`: cơ quan cấp tỉnh
- `official_name`: Sở Nội vụ
- `search_name`: Sở Nội vụ
- `administrative_level`: cấp tỉnh

## PROV-007 — Sở Tài chính

- `source_index`: 7
- `group`: sở; ngành tỉnh
- `entity_type`: cơ quan cấp tỉnh
- `official_name`: Sở Tài chính
- `search_name`: Sở Tài chính
- `administrative_level`: cấp tỉnh

## PROV-008 — Sở Văn hóa; Thể thao và Du lịch

- `source_index`: 8
- `group`: sở; ngành tỉnh
- `entity_type`: cơ quan cấp tỉnh
- `official_name`: Sở Văn hóa; Thể thao và Du lịch
- `search_name`: Sở Văn hóa; Thể thao và Du lịch
- `administrative_level`: cấp tỉnh

## PROV-009 — Sở Khoa học và Công nghệ

- `source_index`: 9
- `group`: sở; ngành tỉnh
- `entity_type`: cơ quan cấp tỉnh
- `official_name`: Sở Khoa học và Công nghệ
- `search_name`: Sở Khoa học và Công nghệ
- `administrative_level`: cấp tỉnh

## PROV-010 — Sở Xây dựng

- `source_index`: 10
- `group`: sở; ngành tỉnh
- `entity_type`: cơ quan cấp tỉnh
- `official_name`: Sở Xây dựng
- `search_name`: Sở Xây dựng
- `administrative_level`: cấp tỉnh

## PROV-011 — Văn phòng Ủy ban nhân dân tỉnh

- `source_index`: 11
- `group`: sở; ngành tỉnh
- `entity_type`: cơ quan cấp tỉnh
- `official_name`: Văn phòng Ủy ban nhân dân tỉnh
- `search_name`: Văn phòng Ủy ban nhân dân tỉnh
- `administrative_level`: cấp tỉnh

## PROV-012 — Sở Y tế

- `source_index`: 12
- `group`: sở; ngành tỉnh
- `entity_type`: cơ quan cấp tỉnh
- `official_name`: Sở Y tế
- `search_name`: Sở Y tế
- `administrative_level`: cấp tỉnh

## PROV-013 — Sở Nông nghiệp và Môi trường

- `source_index`: 13
- `group`: sở; ngành tỉnh
- `entity_type`: cơ quan cấp tỉnh
- `official_name`: Sở Nông nghiệp và Môi trường
- `search_name`: Sở Nông nghiệp và Môi trường
- `administrative_level`: cấp tỉnh

## PROV-014 — Ban Quản lý Khu kinh tế

- `source_index`: 14
- `group`: sở; ngành tỉnh
- `entity_type`: cơ quan cấp tỉnh
- `official_name`: Ban Quản lý Khu kinh tế
- `search_name`: Ban Quản lý Khu kinh tế
- `administrative_level`: cấp tỉnh

## PROV-015 — Sở Dân tộc và Tôn giáo

- `source_index`: 15
- `group`: sở; ngành tỉnh
- `entity_type`: cơ quan cấp tỉnh
- `official_name`: Sở Dân tộc và Tôn giáo
- `search_name`: Sở Dân tộc và Tôn giáo
- `administrative_level`: cấp tỉnh

# 6. Quy tắc tra cứu cho AI

1. Khi người dùng hỏi một cơ quan/đơn vị có nằm trong danh sách hay không, so khớp trước hết với `official_name`.
2. Với UBND cấp xã, có thể nhận diện bằng `search_name` không có tiền tố `UBND`, nhưng khi trả lời tên chính thức phải dùng `official_name`.
3. Không gộp hoặc đổi tên đơn vị nếu file nguồn chưa thể hiện việc đổi tên.
4. Không dùng số thứ tự nguồn làm định danh duy nhất vì số thứ tự được lặp lại giữa hai nhóm.
5. Nếu người dùng hỏi số lượng đơn vị: toàn bộ danh sách có 111 đơn vị; nhóm xã/phường có 96; trong đó 82 xã và 14 phường; nhóm sở, ngành tỉnh có 15.
6. Nếu một tên trong dữ liệu nguồn có dấu câu hoặc cách viết bất thường, giữ nguyên khi trích dẫn từ danh mục; chỉ chuẩn hóa khi người dùng yêu cầu hiệu chỉnh dữ liệu.
7. Danh mục này chỉ xác nhận **tên và nhóm cơ quan/đơn vị**; không suy diễn địa chỉ, người đứng đầu, chức năng, thẩm quyền hoặc thông tin liên hệ nếu không có nguồn khác.

# 7. Từ khóa RAG

`Tây Ninh`, `danh sách cơ quan`, `danh sách đơn vị`, `UBND xã`, `UBND phường`, `sở ngành tỉnh`, `cơ quan cấp tỉnh`, `cấp xã`, `cơ quan đơn vị Tây Ninh`
