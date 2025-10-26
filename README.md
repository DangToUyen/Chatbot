# 🌸 Cô Uyên – Trợ lý học tập Tin học lớp 3 🤖

Một ứng dụng **chatbot giáo dục thân thiện** được xây dựng bằng **Streamlit**, tích hợp **Google Generative AI (Gemini)** và **Google Sheets** để giúp học sinh tiểu học ôn tập Tin học lớp 3 một cách nhẹ nhàng và vui vẻ 💻🌼

---

## 🚀 Tính năng nổi bật

### 💬 Trò chuyện thân thiện
- Học sinh có thể nói chuyện trực tiếp với “**Cô Uyên**” bằng ngôn ngữ tự nhiên.
- Cô giảng giải dễ hiểu, dùng ngôn từ dịu dàng, phù hợp với học sinh lớp 3.
- Có thể hỏi bài, ôn tập kiến thức, hoặc trò chuyện thân mật như với cô giáo thật 💗

### 📜 Lưu & xem lại lịch sử
- Mọi cuộc trò chuyện được **ghi lại vào Google Sheet**.
- Học sinh có thể xem lại **toàn bộ lịch sử trò chuyện của mình** hoặc **toàn bộ lớp**.
- Có thể **tải lịch sử học tập** dưới dạng:
  - 📄 CSV (UTF-8 chuẩn tiếng Việt)
  - 📘 Excel (.xlsx)

### ☁️ Giao diện thân thiện
- Thiết kế **trực quan, dễ thương, màu sắc dịu nhẹ**.
- Hình nền động và hiệu ứng trong suốt giúp học sinh cảm thấy như đang học cùng cô thật 🌈

---

## 🧰 Công nghệ sử dụng

| Thành phần | Mô tả |
|-------------|-------|
| **Streamlit** | Xây dựng giao diện web thân thiện, dễ triển khai |
| **Google Generative AI (Gemini)** | Cung cấp trí tuệ nhân tạo trò chuyện tự nhiên |
| **Google Sheets (GSpread)** | Lưu và truy xuất lịch sử trò chuyện |
| **Pandas** | Xử lý dữ liệu lịch sử và xuất file CSV/Excel |
| **XlsxWriter / OpenPyXL** | Xuất file Excel |
| **Python 3.10+** | Ngôn ngữ lập trình chính |

---

## ⚙️ Cài đặt và chạy ứng dụng

### 1️⃣ Clone dự án
```bash
git clone https://github.com/<tên-tài-khoản>/chatbot-co-uyen.git
cd chatbot-co-uyen
