# [Nhóm 32] AI Trợ lý Nội bộ - Ngày Tổng Kết Phase 1

## 📌 Tổng quan dự án
Hệ thống **Enterprise Knowledge RAG Chatbot** hỗ trợ nhân viên tra cứu quy trình, chính sách nội bộ một cách thông minh.  
Dự án tập trung giải quyết bài toán **bảo mật dữ liệu doanh nghiệp** và **tối ưu hóa chi phí vận hành LLM** thông qua các kỹ thuật:
- Semantic Caching  
- Prompt Compression  

---

## 👥 Thành viên & Vai trò

Dựa trên cấu trúc 5 vai trò cốt lõi của bài lab, đây là phân công cho nhóm:

| Họ và tên           | Mã sinh viên | Vai trò |
|--------------------|-------------|--------|
| Phạm Minh Khôi     | 2A202600262 | Product Lead (Phân tích nghiệp vụ & nội dung) |
| Trần Sỹ Minh Quân  | 2A202600308 | Technical Architect (Thiết kế hệ thống & Hybrid Cloud) |
| Vũ Đức Minh        | 2A202600439 | Cost Lead (Ước lượng Token & Tối ưu chi phí) |
| Nguyễn Thế Anh     | 2A202600207 | Reliability Lead (Xử lý sự cố & Kế hoạch dự phòng) |
| Ngô Quang Tăng     | 2A202600478 | Presenter (Thuyết trình & Giải đáp Q&A) |

---

## 📂 Tài liệu dự án
- Hồ sơ Worksheet (0-5): [https://docs.google.com/document/d/1aYr9wery0PsZEFlduUkruXlDuCeG_VV88xmqPdrTEPQ/edit?tab=t.sw4fe2qsg4ne]

---

## 🚀 Điểm nhấn kỹ thuật (Phase 1)

- **Mô hình triển khai**: Hybrid  
  - Dữ liệu lưu **On-prem**
  - Xử lý LLM qua **Cloud**

- **Chiến lược tối ưu**:  
  - Sử dụng **Semantic Caching** để giảm ~80% chi phí cho các câu hỏi trùng lặp  

- **Độ tin cậy**:  
  - Thiết lập cơ chế **Circuit Breaker**  
  - Sử dụng **Fallback Model** khi API nhà cung cấp gặp sự cố  
