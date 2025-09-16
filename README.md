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
### 2. Cài đặt dependencies
```bash
npm install
```

### 3.Chạy app:
```bash
npm start
```
---
## 📦 Build ứng dụng (tạo file .exe)
Cài electron-builder:
```bash
npm install --save-dev electron-builder
```
Chạy build:
```bash
npx electron-builder
```
File cài đặt `.exe` sẽ nằm trong thư mục `dist/win-unpacked/`.

## 📥 Download app
`https://github.com/quan334/calculator/releases/download/v1.0.0/calculator.exe`
