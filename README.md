# 🧮 Calculator Desktop App

Ứng dụng **Calculator** viết bằng **ElectronJS**, giao diện đơn giản, dễ sử dụng.  
App được build từ phiên bản web (HTML/CSS/JS) và đóng gói thành ứng dụng desktop.

---

## 🚀 Tính năng
- Giao diện thân thiện như máy tính bỏ túi.
- Các phép tính cơ bản: cộng, trừ, nhân, chia.
- Nút `=` hiển thị kết quả.
- Hỗ trợ nhập số và toán tử liên tiếp.
- Xóa một ký tự (`⌫`) hoặc toàn bộ (`C`).

---

## 📂 Cấu trúc dự án

calculator/  
│── dist/ # App đã build sẵn (chạy trực tiếp trong Windows)  
│── index.html # Giao diện chính (HTML/CSS/JS)  
│── main.js # Điểm khởi chạy Electron  
│── preload.js # Script preload cho Electron  
│── package.json # Cấu hình Electron/Node  
│── README.md # Hướng dẫn sử dụng


---

## 🔧 Cách sử dụng

###  1. Clone repo
```bash
git clone https://github.com/quan334/calculator.git
cd calculator
```
### 2. Chạy app ngay (Windows)
- Mở thư mục `dist/win-unpacked`
- Chạy file `calculator.exe`

## 💻 Dành cho Developer (muốn sửa code & build lại)

Nếu bạn muốn chỉnh sửa code hoặc build lại app:

```bash
npm install
npm start
```

Build lại app:
```bash
npx electron-builder
```
## 📥 Download

