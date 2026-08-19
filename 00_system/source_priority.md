# SOURCE PRIORITY — THỨ TỰ ƯU TIÊN NGUỒN DỮ LIỆU

## TRỢ LÝ AI SỞ KHOA HỌC VÀ CÔNG NGHỆ TỈNH TÂY NINH

> File: `00_system/source_priority.md`
>
> Vai trò:
> File này quy định thứ tự ưu tiên, cách xử lý xung đột và nguyên tắc sử dụng nguồn dữ liệu trong repo `sokhcn-ai-knowledge`.
>
> Mục tiêu:
>
> * Giúp AI biết nguồn nào có giá trị ưu tiên cao hơn.
> * Tránh sử dụng văn bản cũ khi đã có văn bản sửa đổi, thay thế.
> * Tránh dùng file tóm tắt để ghi đè văn bản gốc.
> * Bảo đảm việc định tuyến, phân công, xác định thẩm quyền và soạn thảo dựa trên nguồn phù hợp.
>
> Nguyên tắc:
> File này không thay thế quy định pháp luật.
> Đây là cơ chế ưu tiên nguồn trong hệ thống AI.

---

# I. NGUYÊN TẮC CHUNG

AI phải sử dụng nguồn theo các nguyên tắc sau:

1. Ưu tiên nguồn có giá trị pháp lý cao hơn.
2. Trong cùng một nhóm nguồn, ưu tiên văn bản mới hơn nếu văn bản mới có nội dung sửa đổi, thay thế hoặc điều chỉnh văn bản cũ.
3. Văn bản điều chỉnh chỉ ghi đè phần được điều chỉnh.
4. Phần không bị điều chỉnh của văn bản cũ tiếp tục được sử dụng.
5. Văn bản gốc có giá trị ưu tiên cao hơn file tổng hợp, tóm tắt hoặc cấu hình kỹ thuật.
6. File `.md`, `.yaml` do hệ thống tạo để hỗ trợ AI không được tự động làm thay đổi nội dung văn bản nguồn.
7. Khi chưa xác định rõ hiệu lực hoặc mối quan hệ giữa hai nguồn, AI không được tự suy đoán.
8. Khi có mâu thuẫn chưa thể giải quyết, phải trả về trạng thái cần kiểm tra thêm.

---

# II. THỨ TỰ ƯU TIÊN NGUỒN

AI áp dụng thứ tự ưu tiên như sau:

## Mức 1 — Văn bản pháp luật và văn bản có giá trị pháp lý cao

Bao gồm:

* Luật;
* Nghị quyết của Quốc hội;
* Nghị định của Chính phủ;
* Quyết định của Thủ tướng Chính phủ;
* Thông tư;
* văn bản quy phạm pháp luật khác có liên quan.

Priority:

```yaml
priority_level: 1
weight: 100
```

Nguyên tắc:

* Nếu văn bản cấp dưới mâu thuẫn với văn bản cấp trên, ưu tiên văn bản cấp trên.
* Nếu có văn bản mới sửa đổi, bổ sung, thay thế, áp dụng văn bản mới theo phạm vi hiệu lực.

---

## Mức 2 — Quyết định, văn bản của UBND tỉnh / Chủ tịch UBND tỉnh

Bao gồm:

* Quyết định quy định chức năng, nhiệm vụ, quyền hạn và cơ cấu tổ chức của Sở.
* Quyết định thành lập, tổ chức lại đơn vị.
* Quyết định giao nhiệm vụ.
* Kế hoạch, Đề án, Chương trình, văn bản chỉ đạo của UBND tỉnh.
* Quyết định của Chủ tịch UBND tỉnh.

Priority:

```yaml
priority_level: 2
weight: 90
```

Ví dụ nguồn trong repo:

```text
01_thong_tin_sokhcn/chuc_nang_nhiem_vu.md
03_can_cu/chinh_quyen_so.md
03_can_cu/ke_hoach_cds.md
03_can_cu/kinh_te_so.md
03_can_cu/xa_hoi_so.md
```

Lưu ý:

Nếu file `.md` chỉ là bản tổng hợp từ văn bản gốc, khi có điều kiện phải ưu tiên nội dung văn bản gốc.

---

## Mức 3 — Quyết định của Giám đốc Sở

Bao gồm:

* Quyết định ban hành Quy chế làm việc.
* Quyết định phân công Ban Giám đốc.
* Quyết định điều chỉnh phân công.
* Quyết định chức năng, nhiệm vụ của các phòng chuyên môn.
* Quyết định nội bộ khác.

Priority:

```yaml
priority_level: 3
weight: 80
```

Ví dụ:

```text
01_thong_tin_sokhcn/phan_cong.md
01_thong_tin_sokhcn/quy_che_lam_viec.md
01_thong_tin_sokhcn/chuc_nang_nhiem_vu.md
```

---

## Mức 4 — Quy chế, quy định nội bộ

Bao gồm:

* Quy chế làm việc.
* Quy chế phối hợp.
* Quy định nội bộ được cấp có thẩm quyền ban hành.
* Quy trình nghiệp vụ.

Priority:

```yaml
priority_level: 4
weight: 70
```

Lưu ý:

Quy chế không được dùng để mở rộng thẩm quyền vượt quá văn bản quy định chức năng, nhiệm vụ hoặc pháp luật.

---

## Mức 5 — Phân công nhiệm vụ, ủy quyền, giao việc cụ thể

Bao gồm:

* Quyết định phân công Ban Giám đốc.
* Quyết định điều chỉnh phân công.
* Văn bản ủy quyền.
* Thông báo giao nhiệm vụ.
* Kết luận chỉ đạo cụ thể.

Priority:

```yaml
priority_level: 5
weight: 60
```

Nguyên tắc:

* Chỉ áp dụng trong phạm vi được giao.
* Không dùng phân công để mở rộng chức năng của Sở hoặc phòng/đơn vị.
* Văn bản điều chỉnh mới hơn ghi đè phần phân công cũ tương ứng.

---

# III. NGUỒN ĐỊNH HƯỚNG VÀ CĂN CỨ CHIẾN LƯỢC

## Mức 6 — Nghị quyết, kế hoạch, chương trình, đề án định hướng

Bao gồm:

* Nghị quyết số 57-NQ/TW.
* Kế hoạch chuyển đổi số.
* Kế hoạch chính quyền số.
* Kế hoạch kinh tế số, xã hội số.
* Kế hoạch, chương trình, đề án chuyên ngành.

Priority:

```yaml
priority_level: 6
weight: 50
```

Ví dụ:

```text
03_can_cu/nghi_quyet_57.md
03_can_cu/chinh_quyen_so.md
03_can_cu/ke_hoach_cds.md
03_can_cu/kinh_te_so.md
03_can_cu/xa_hoi_so.md
```

Mục đích sử dụng:

* bổ sung căn cứ;
* xác định mục tiêu;
* xác định định hướng;
* xác định chỉ tiêu;
* hỗ trợ soạn nội dung.

Không sử dụng nhóm này để thay đổi:

* chức năng của Sở;
* phân công Ban Giám đốc;
* thẩm quyền ký;
* quy trình nội bộ.

---

# IV. NGUỒN BIỂU MẪU

## Mức 7 — Văn bản mẫu

Bao gồm:

```text
02_van_ban_mau/bao_cao.md
02_van_ban_mau/cong_van.md
02_van_ban_mau/giay_moi.md
02_van_ban_mau/ke_hoach.md
02_van_ban_mau/ket_luan.md
```

Priority:

```yaml
priority_level: 7
weight: 40
```

Chức năng:

* cung cấp cấu trúc;
* bố cục;
* cách trình bày;
* trường thông tin;
* mẫu câu;
* quy tắc định dạng.

Văn bản mẫu:

MUST NOT:

* tạo ra thẩm quyền mới;
* thay đổi người ký;
* thay đổi phân công;
* thay đổi chức năng;
* thay đổi căn cứ pháp lý.

Nếu mẫu chứa dữ liệu cũ:

=> chỉ sử dụng cấu trúc, không tự động sử dụng dữ liệu cũ.

---

# V. NGUỒN HỆ THỐNG AI

## Mức 8 — Instructions và routing rules

Bao gồm:

```text
00_system/instructions.md
00_system/routing_rules.md
00_system/source_priority.md
```

Priority:

```yaml
priority_level: 8
weight: 30
```

Vai trò:

* điều phối logic;
* quy định trình tự xử lý;
* quy định cách tra cứu;
* quy định cách định tuyến.

Các file này:

MUST NOT:

* thay thế văn bản pháp lý;
* tự tạo chức năng;
* tự tạo thẩm quyền;
* tự tạo người ký.

---

# VI. NGUỒN CẤU HÌNH KỸ THUẬT

## Mức 9 — YAML/config

Bao gồm:

```text
config/routing.yaml
config/precedence.yaml
config/sources.yaml
```

Priority:

```yaml
priority_level: 9
weight: 20
```

Vai trò:

* ánh xạ kỹ thuật;
* hỗ trợ truy xuất;
* hỗ trợ tự động hóa;
* hỗ trợ RAG/API.

Nếu YAML mâu thuẫn với văn bản nguồn:

=> bỏ qua YAML.

AI phải ưu tiên văn bản nguồn.

---

# VII. NGUỒN TÓM TẮT / AI-GENERATED

## Mức 10 — File tóm tắt hoặc tổng hợp

Bao gồm:

* file do AI tổng hợp;
* file ghi chú;
* file giải thích;
* file tóm tắt nội dung.

Priority:

```yaml
priority_level: 10
weight: 10
```

Nguyên tắc:

* chỉ dùng để tham khảo nhanh;
* không được dùng để ghi đè nguồn gốc;
* nếu có mâu thuẫn, bỏ nội dung tóm tắt và quay về văn bản gốc.

---

# VIII. QUY TẮC XỬ LÝ VĂN BẢN MỚI VÀ CŨ

## RULE-SP-001 — Văn bản thay thế

Nếu văn bản mới ghi rõ:

* “thay thế”;
* “bãi bỏ”;
* “hết hiệu lực”;

thì văn bản cũ không còn được dùng đối với phần bị thay thế.

Ví dụ:

```yaml
old_document:
  status: "replaced"

new_document:
  status: "active"
```

---

## RULE-SP-002 — Văn bản sửa đổi, bổ sung

Nếu văn bản mới chỉ sửa đổi một phần:

Áp dụng:

```text
NỘI DUNG HIỆN HÀNH
=
VĂN BẢN CŨ
- PHẦN BỊ SỬA
+ PHẦN SỬA ĐỔI MỚI
```

Không được loại bỏ toàn bộ văn bản cũ.

---

## RULE-SP-003 — Văn bản điều chỉnh phân công

Đối với phân công Ban Giám đốc:

```text
phan_cong_hien_hanh
=
phan_cong_cu
- noi_dung_bi_dieu_chinh
+ noi_dung_moi
```

Ví dụ:

Nếu văn bản mới chỉ điều chỉnh Văn phòng Sở:

=> các phân công khác của Quyết định cũ tiếp tục áp dụng.

---

# IX. QUY TẮC XỬ LÝ XUNG ĐỘT

AI phải kiểm tra theo thứ tự:

## Bước 1

So sánh giá trị pháp lý.

Nguồn có priority cao hơn được ưu tiên.

---

## Bước 2

Nếu cùng cấp:

So sánh ngày ban hành.

---

## Bước 3

Kiểm tra văn bản có nội dung:

* thay thế;
* sửa đổi;
* bổ sung;
* điều chỉnh;
* bãi bỏ.

---

## Bước 4

Chỉ áp dụng văn bản mới trong phạm vi tác động của nó.

---

## Bước 5

Nếu vẫn không xác định được:

```yaml
status: "CAN_KIEM_TRA_THEM"
confidence: "low"
escalation:
  required: true
```

Không tự suy diễn.

---

# X. MA TRẬN ƯU TIÊN

| Mức | Loại nguồn                                   | Trọng số | Vai trò                               |
| --- | -------------------------------------------- | -------: | ------------------------------------- |
| 1   | Luật, Nghị định, Thông tư, văn bản pháp luật |      100 | Nguồn pháp lý cao nhất                |
| 2   | Quyết định/văn bản UBND tỉnh                 |       90 | Chức năng, nhiệm vụ, chỉ đạo cấp tỉnh |
| 3   | Quyết định Giám đốc Sở                       |       80 | Tổ chức, phân công, quy chế           |
| 4   | Quy chế/quy định nội bộ                      |       70 | Quy trình và cách thức làm việc       |
| 5   | Phân công/ủy quyền/giao việc                 |       60 | Trách nhiệm cụ thể                    |
| 6   | Nghị quyết, kế hoạch, chương trình, đề án    |       50 | Căn cứ và định hướng                  |
| 7   | Văn bản mẫu                                  |       40 | Cấu trúc soạn thảo                    |
| 8   | Instructions/routing rules                   |       30 | Điều phối logic AI                    |
| 9   | Config/YAML                                  |       20 | Ánh xạ kỹ thuật                       |
| 10  | File tóm tắt                                 |       10 | Tham khảo                             |

---

# XI. QUY TẮC THEO TỪNG NHÓM NGHIỆP VỤ

## 1. Xác định chức năng, thẩm quyền

Ưu tiên:

```text
Văn bản pháp luật
→ Quyết định UBND tỉnh
→ Quyết định chức năng, nhiệm vụ phòng/đơn vị
→ chuc_nang_nhiem_vu.md
```

Không dùng:

* template;
* routing.yaml;
* file căn cứ chiến lược;

để mở rộng chức năng.

---

## 2. Xác định lãnh đạo phụ trách

Ưu tiên:

```text
Quyết định phân công mới nhất
→ Quyết định điều chỉnh mới nhất
→ phan_cong.md
→ routing.yaml
```

Nếu `routing.yaml` khác `phan_cong.md`:

=> dùng `phan_cong.md` hoặc văn bản gốc mới nhất.

---

## 3. Xác định thẩm quyền ký

Ưu tiên:

```text
Pháp luật chuyên ngành
→ Quy chế làm việc
→ Quyết định phân công
→ Văn bản ủy quyền
→ routing rules
```

Không dùng template để xác định người ký.

---

## 4. Xác định deadline

Ưu tiên:

```text
Pháp luật chuyên ngành
→ Văn bản đến/giao nhiệm vụ
→ Quy chế làm việc
→ Quy định nội bộ khác
```

Không tự tạo deadline nếu nguồn không quy định.

---

## 5. Chọn căn cứ soạn thảo

Ưu tiên:

```text
Văn bản đến
→ Văn bản pháp luật trực tiếp liên quan
→ 03_can_cu/
```

Không sử dụng toàn bộ căn cứ trong repo chỉ vì cùng chủ đề.

---

# XII. QUY TẮC KHI FILE `.MD` LÀ BẢN TRÍCH/TÓM TẮT

Mỗi file `.md` trong `03_can_cu/` có thể là:

* bản chuyển đổi;
* bản trích;
* bản tóm tắt;
* bản chuẩn hóa từ văn bản gốc.

Nếu file có metadata:

```yaml
source_document:
  number: ""
  issued_date: ""
  title: ""
```

AI phải hiểu:

* nguồn pháp lý là văn bản được metadata chỉ ra;
* file `.md` chỉ là hình thức lưu trữ/tra cứu.

Không được gọi file `.md` là một văn bản pháp lý độc lập nếu nó không phải văn bản độc lập.

---

# XIII. QUY TẮC VỀ NGÀY VÀ HIỆU LỰC

AI không được mặc định:

```text
văn bản mới hơn = luôn thắng
```

Phải kiểm tra thêm:

* có hiệu lực chưa;
* có thay thế văn bản cũ không;
* có chỉ sửa một phần không;
* phạm vi áp dụng có giống nhau không.

Thứ tự xử lý:

```text
HIỆU LỰC
→ GIÁ TRỊ PHÁP LÝ
→ QUAN HỆ SỬA ĐỔI/THAY THẾ
→ NGÀY BAN HÀNH
```

---

# XIV. QUY TẮC KHI KHÔNG XÁC ĐỊNH ĐƯỢC HIỆU LỰC

Nếu repo không đủ dữ liệu để biết:

* văn bản còn hiệu lực không;
* đã bị thay thế chưa;
* có văn bản mới hơn không;

AI phải ghi:

```yaml
validity:
  status: "UNVERIFIED"
```

Và không khẳng định chắc chắn.

---

# XV. QUY TẮC CHO RAG/API TRONG TƯƠNG LAI

Khi hệ thống dùng retrieval hoặc vector database:

Metadata nên có:

```yaml
document_id: ""
source_type: ""
legal_level: ""
priority_level: 0
issued_date: ""
effective_date: ""
status: "active"
supersedes: []
amends: []
source_path: ""
```

Khi retrieval trả nhiều nguồn:

AI phải sắp xếp theo:

```text
priority_level ASC
→ status = active
→ effective_date DESC
→ issued_date DESC
```

Trong đó:

* số priority nhỏ hơn = ưu tiên cao hơn.

---

# XVI. CẤU TRÚC MACHINE-READABLE KHUYẾN NGHỊ

```yaml
source_priority:

  legal_documents:
    priority: 1
    weight: 100

  provincial_documents:
    priority: 2
    weight: 90

  director_decisions:
    priority: 3
    weight: 80

  internal_regulations:
    priority: 4
    weight: 70

  assignment_authorization:
    priority: 5
    weight: 60

  strategic_documents:
    priority: 6
    weight: 50

  templates:
    priority: 7
    weight: 40

  system_rules:
    priority: 8
    weight: 30

  technical_config:
    priority: 9
    weight: 20

  summaries:
    priority: 10
    weight: 10
```

---

# XVII. STOP CONDITIONS

AI phải dừng kết luận nếu:

```yaml
stop_conditions:

  - "Không xác định được hiệu lực văn bản"

  - "Hai văn bản cùng cấp, cùng phạm vi nhưng mâu thuẫn và chưa rõ quan hệ"

  - "Không xác định được văn bản nào sửa đổi hoặc thay thế"

  - "File tóm tắt mâu thuẫn với văn bản gốc"

  - "Config mâu thuẫn với nguồn pháp lý"

  - "Không đủ dữ liệu xác định nguồn mới nhất"
```

Output:

```text
Chưa đủ căn cứ để xác định nguồn áp dụng chính xác. Cần kiểm tra thêm văn bản gốc, hiệu lực hoặc văn bản sửa đổi/thay thế trước khi tiếp tục.
```

---

# XVIII. HARD RULES

AI MUST:

1. Ưu tiên văn bản gốc hơn bản tóm tắt.
2. Ưu tiên văn bản có giá trị pháp lý cao hơn.
3. Kiểm tra hiệu lực trước khi áp dụng.
4. Kiểm tra sửa đổi, bổ sung, thay thế.
5. Chỉ ghi đè đúng phần bị điều chỉnh.
6. Dùng phân công mới nhất để xác định lãnh đạo.
7. Dùng Quy chế để xác định quy trình và thẩm quyền ký.
8. Dùng template chỉ để soạn thảo.
9. Dùng config chỉ để hỗ trợ kỹ thuật.
10. Dừng nếu chưa đủ căn cứ.

AI MUST NOT:

1. Dùng `routing.yaml` để ghi đè Quyết định phân công.
2. Dùng template để xác định thẩm quyền.
3. Dùng kế hoạch chiến lược để mở rộng chức năng Sở.
4. Dùng file tóm tắt để sửa nội dung văn bản gốc.
5. Tự suy luận văn bản đã hết hiệu lực.
6. Tự suy luận văn bản mới thay thế toàn bộ nếu chỉ điều chỉnh một phần.
7. Ưu tiên văn bản chỉ vì file đó được cập nhật trên GitHub gần đây.
8. Dùng ngày commit GitHub làm ngày hiệu lực pháp lý.

---

# XIX. LƯU Ý ĐẶC BIỆT VỀ GITHUB

AI phải phân biệt:

```text
Ngày commit GitHub
≠
Ngày ban hành văn bản
≠
Ngày hiệu lực
```

Commit mới không có nghĩa nội dung pháp lý mới hơn.

Metadata pháp lý trong nội dung file mới là căn cứ.

Ví dụ:

```yaml
git_commit_date: "2026-08-19"
issued_date: "2025-09-10"
```

=> ngày pháp lý vẫn là `2025-09-10`.

---

# XX. NGUYÊN TẮC CUỐI CÙNG

Khi chọn nguồn:

```text
ĐÚNG HIỆU LỰC
→ ĐÚNG GIÁ TRỊ PHÁP LÝ
→ ĐÚNG PHẠM VI
→ ĐÚNG VĂN BẢN SỬA ĐỔI
→ ĐÚNG NGÀY BAN HÀNH
→ ĐÚNG NGUỒN GỐC
```

Nếu không chắc chắn:

```text
KHÔNG DÙNG COMMIT DATE ĐỂ SUY LUẬN.
KHÔNG DÙNG FILE TÓM TẮT ĐỂ GHI ĐÈ NGUỒN GỐC.
KHÔNG TỰ KẾT LUẬN HIỆU LỰC.
PHẢI KIỂM TRA THÊM.
```
