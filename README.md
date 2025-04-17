# 💰 Salary Calculator (Gross to Net)

Ứng dụng web đơn giản dùng FastAPI để tính lương **Gross → Net** tại Việt Nam.  
Giao diện thân thiện, dễ dùng, có thể chạy cục bộ hoặc deploy bằng Docker.

---

## 🚀 Tính năng

- ✅ Nhập lương Gross → Tính lương Net
- ✅ Tự động tính BHXH, BHYT, BHTN, Thuế TNCN
- ✅ Giao diện frontend HTML/JS
- ✅ API hỗ trợ POST /calculate-net

---

## 🛠️ Cách chạy ứng dụng

### ✅ Yêu cầu:
- Python 3.10+
- pip

---

### 📦 1. Tạo môi trường ảo (khuyên dùng)

```bash
python -m venv venv
venv\\Scripts\\activate          # Trên Windows
# hoặc:
source venv/bin/activate         # Trên macOS/Linux


cài đặt thư viện
pip install fastapi uvicorn pydantic


chạy ứng dụng


uvicorn src.cat.api.main:app --reload
Mở trình duyệt truy cập: 👉 http://127.0.0.1:8000

