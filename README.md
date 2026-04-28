

````markdown
# 🚀 SERN_TQcare

**SERN_TQcare** là repository trung tâm (hub) của dự án, dùng để điều hướng và quản lý tổng thể hệ thống.  
Dự án được tách thành 2 repository riêng biệt nhằm đảm bảo **dễ bảo trì, mở rộng và phát triển độc lập**.

---

## 📦 Repository Structure

### 🔹 Frontend (ReactJS)
Chứa toàn bộ giao diện người dùng và logic phía client.

👉 https://github.com/Quangcntt1210/SERN_TQcare_ReactJS.git

---

### 🔹 Backend (NodeJS)
Chứa API, xử lý nghiệp vụ và kết nối cơ sở dữ liệu.

👉 https://github.com/Quangcntt1210/SERN_TQcare_NodeJS.git

---

### 🔹 This Repository (SERN_TQcare)
- Đóng vai trò **entry point**
- Điều hướng đến frontend & backend
- Quản lý tổng thể dự án

---

## ⚙️ Tech Stack

- **Frontend**: ReactJS, Redux, SCSS
- **Backend**: NodeJS, ExpressJS
- **Database**: MySQL / Sequelize ORM

---

## 🚀 How to Run the Project

### 1️⃣ Run Backend

```bash
git clone https://github.com/Quangcntt1210/SERN_TQcare_NodeJS.git
cd SERN_TQcare_NodeJS
npm install
npm run dev
````

📌 Backend cần chạy trước để cung cấp API.

---

### 2️⃣ Run Frontend

```bash
git clone https://github.com/Quangcntt1210/SERN_TQcare_ReactJS.git
cd SERN_TQcare_ReactJS
npm install
npm start
```

📌 Frontend mặc định chạy tại:

```
http://localhost:3000
```

---

## 🔗 System Flow

```
[ ReactJS Client ]  →  [ NodeJS API Server ]  →  [ Database ]
```

---

## ⚙️ Environment Configuration (Backend)

Tạo file `.env` trong thư mục backend với nội dung ví dụ:

```env
PORT=8080
DB_HOST=localhost
DB_USER=root
DB_PASSWORD=your_password
DB_NAME=sern_tqcare
JWT_SECRET=your_secret_key
```

📌 Điều chỉnh theo cấu hình máy của bạn.

---

## 📁 Suggested Folder Structure

### Frontend

```
src/
 ├── components/
 ├── containers/
 ├── services/
 ├── store/
 ├── assets/
 └── utils/
```

### Backend

```
src/
 ├── controllers/
 ├── services/
 ├── models/
 ├── routes/
 ├── config/
 └── migrations/
```

---


## 📌 Notes

* Dự án đang trong quá trình phát triển
* Một số tính năng có thể chưa hoàn thiện
* Backend cần cấu hình `.env` trước khi chạy
* Đảm bảo database đã được tạo trước

---

## 📄 License

🚧 Chưa cập nhật (sẽ bổ sung trong thời gian tới)

---

## 👨‍💻 Author

**Quangcntt1210**

---


## 💡 Tips

* Luôn chạy backend trước frontend
* Kiểm tra port backend (tránh conflict)
* Sử dụng Postman để test API
* Debug bằng console/log nếu gặp lỗi

---

🔥 *Happy Coding!*

```
```
