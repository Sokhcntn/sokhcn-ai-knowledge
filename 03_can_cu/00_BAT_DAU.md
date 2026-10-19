# HỆ THỐNG VĂN BẢN TÂY NINH — KHO TRI THỨC MARKDOWN CHO RAG

- Thư mục Google Drive nguồn: https://drive.google.com/drive/folders/1DldfXOF3W-gHlfFK0ioyj1Qy3933Sy35?usp=sharing
- Số lượng: **88 PDF nguồn**, **818 trang** (tính theo số trang PDF).
- Tài liệu trích xuất chữ trực tiếp: **73**; tài liệu cần kiểm chứng OCR: **15**.
- Thời điểm lập bộ tư liệu: 19/10/2026.

## Nguyên tắc biên tập

1. **Không tạo thêm chủ trương, chỉ tiêu, nhiệm vụ, thời hạn hoặc số liệu.** Nội dung các văn bản được trích từ PDF; không tổng hợp số liệu bằng phép tính mới và không tự hợp nhất những kỳ thống kê khác nhau.
2. Phân nhóm chỉ nhằm **tổ chức kho tri thức**, không khẳng định cơ quan chủ trì hay trạng thái hiệu lực pháp lý của văn bản.
3. Mỗi tài liệu có `id`, tên PDF, URL gốc và các mốc trang `[VB-xxx, tr. N]`. Khi trả lời, hệ thống RAG phải nêu ID, trang và tham chiếu PDF nguồn.
4. Tài liệu có cờ `OCR_cần_đối_chiếu` phải mở PDF gốc để xác nhận trích dẫn, đặc biệt với **số liệu, tên riêng, căn cứ, số văn bản, ngày tháng và phụ lục bảng**.
5. Trường số ký hiệu hoặc ngày trích từ **tên tệp** được ghi rõ nguồn; không được coi là nội dung đã xác minh nếu lớp chữ gốc khác hoặc không đọc được.
6. Đoạn trích trong các bảng tra cứu chỉ là **bản sao nguyên văn từ kết quả trích xuất**, không phải nội dung diễn giải mới. Chúng cần được đọc trong ngữ cảnh toàn văn.
7. Cần kiểm tra quyền công bố và bảo mật tài liệu trước khi đưa vào repository GitHub công khai.

## Các tệp chỉ mục

- [01_DANH_MUC_NGUON.md](01_DANH_MUC_NGUON.md) — đầy đủ 88 văn bản với nguồn và trạng thái đọc.
- [02_CHU_TRUONG_KET_LUAN.md](02_CHU_TRUONG_KET_LUAN.md) — chỉ mục văn bản chủ trương, nghị quyết, kết luận, thông báo.
- [03_TRA_CUU_NHIEM_VU.md](03_TRA_CUU_NHIEM_VU.md) — các đoạn chữ gốc chứa nội dung giao việc, chủ trì, phối hợp hoặc thời hạn.
- [04_TRA_CUU_CHI_TIEU_SO_LIEU.md](04_TRA_CUU_CHI_TIEU_SO_LIEU.md) — chỉ mục đoạn nguyên văn có chỉ tiêu/số liệu; không tái tính toán.
- [05_NHOM_KE_HOACH.md](05_NHOM_KE_HOACH.md) — chỉ mục các kế hoạch theo chủ đề.
- [06_VAN_BAN_VA_PHU_LUC.md](06_VAN_BAN_VA_PHU_LUC.md) — các tệp có tiền tố văn bản chung.
- [07_CANH_BAO_CHAT_LUONG.md](07_CANH_BAO_CHAT_LUONG.md) — nguồn cần đối chiếu OCR, bảng biểu và phạm vi dữ liệu.

## Phân nhóm tài liệu

- **Chủ trương, nghị quyết, thông báo kết luận**: 10 văn bản — [`tai_lieu/01_CHU_TRUONG_KET_LUAN`](tai_lieu/01_CHU_TRUONG_KET_LUAN/).
- **Chương trình công tác, điều hành và phân công**: 11 văn bản — [`tai_lieu/02_CHUONG_TRINH_DIEU_HANH`](tai_lieu/02_CHUONG_TRINH_DIEU_HANH/).
- **Khoa học, công nghệ, đổi mới sáng tạo**: 23 văn bản — [`tai_lieu/03_KHOA_HOC_CONG_NGHE_DMST`](tai_lieu/03_KHOA_HOC_CONG_NGHE_DMST/).
- **Chuyển đổi số, dữ liệu, hạ tầng số, an toàn thông tin**: 19 văn bản — [`tai_lieu/04_CHUYEN_DOI_SO_DU_LIEU_ATTT`](tai_lieu/04_CHUYEN_DOI_SO_DU_LIEU_ATTT/).
- **Kinh tế, đầu tư, doanh nghiệp, thương mại**: 18 văn bản — [`tai_lieu/05_KINH_TE_DAU_TU_DOANH_NGHIEP`](tai_lieu/05_KINH_TE_DAU_TU_DOANH_NGHIEP/).
- **Nhân lực, đào tạo, văn hóa, xã hội và thi đua**: 7 văn bản — [`tai_lieu/06_NHAN_LUC_VAN_HOA_XA_HOI`](tai_lieu/06_NHAN_LUC_VAN_HOA_XA_HOI/).
- **Văn bản và kế hoạch khác**: 0 văn bản — [`tai_lieu/07_KE_HOACH_KHAC`](tai_lieu/07_KE_HOACH_KHAC/).

Các liên kết nguồn trực tiếp đều là liên kết Google Drive của bản PDF tương ứng. Việc tạo tệp Markdown này không thay đổi, không ghi đè các nguồn Google Drive.
