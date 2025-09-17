<h2 align="center">
    <a href="https://dainam.edu.vn/vi/khoa-cong-nghe-thong-tin">
    🎓 Khoa Công nghệ Thông tin – Trường Đại học Đại Nam
    </a>
</h2>

<h2 align="center">
   🕹️ GAME OẲN TÙ TÌ ONLINE (TCP SOCKET + JAVA SWING)
</h2>

<div align="center">
    <p align="center">
        <img src="assets/logo_aiotlab.png" alt="AIoTLab Logo" width="160"/>
        <img src="assets/logo_fit.png" alt="FIT DNU Logo" width="160"/>
        <img src="assets/logo_dnu.png" alt="DaiNam University Logo" width="200"/>
    </p>

[![AIoTLab](https://img.shields.io/badge/AIoTLab-green?style=for-the-badge)](https://www.facebook.com/DNUAIoTLab)
[![Faculty of Information Technology](https://img.shields.io/badge/FIT-DaiNam-blue?style=for-the-badge)](https://dainam.edu.vn/vi/khoa-cong-nghe-thong-tin)
[![University](https://img.shields.io/badge/DaiNam%20University-orange?style=for-the-badge)](https://dainam.edu.vn)

</div>

---

## 📘 1. Giới thiệu  

Hệ thống được xây dựng nhằm mô phỏng **trò chơi Oẳn Tù Tì (Rock – Paper – Scissors)** giữa hai người chơi thông qua **Java TCP Socket**.  

Gồm 2 thành phần chính:  

- **Máy chủ (Server)** 🖥️  
   - Quản lý tài khoản, kết nối, ghép cặp.  
   - Xử lý trận đấu, lưu lịch sử, bảng xếp hạng.  

- **Máy khách (Client)** 💻  
   - Giao diện Swing trực quan, thân thiện.  
   - Cho phép đăng ký / đăng nhập, chơi, xem lịch sử, thoát phòng.  

👉 **Ưu điểm nổi bật:**  
✅ Kết nối TCP ổn định  
✅ Giao diện trực quan, có emoji ✊✋✌ và màu sắc  
✅ Lưu lịch sử & bảng xếp hạng thực tế  
✅ Hỗ trợ thoát phòng an toàn  

---

## 🛠 2. Công nghệ sử dụng  

- Ngôn ngữ: **Java** (JDK 17+ / JDK 21)  
- Giao diện: **Java Swing**  
- Giao tiếp: **TCP Socket**  
- Lưu trữ: **File txt, csv**  
- IDE khuyến nghị: **Eclipse IDE**  

---

## 📸 3. Ảnh giao diện  

### 🔑 Đăng nhập  
<img src="assets/login.png" alt="Giao diện đăng nhập" width="600"/>

### 🎮 Chơi game  
<img src="assets/game.png" alt="Giao diện chơi game" width="600"/>

### 📂 Lịch sử  
<img src="assets/history.png" alt="Lịch sử trận đấu" width="600"/>

### 🏆 Bảng xếp hạng  
<img src="assets/leaderboard.png" alt="Bảng xếp hạng" width="600"/>

---

## 🚀 4. Cài đặt & chạy  

1. **Cài đặt môi trường**  
   - JDK 17+ (hoặc JDK 21).  
   - IDE: Eclipse / IntelliJ / NetBeans.  

2. **Clone project**  
   ```bash
   git clone https://github.com/nhinhnhinh/LTM-1604-D09-Game-TCP.git
   cd LTM-1604-D09-Game-TCP
Chạy chương trình

Server: may_chu/UngDungMayChu.java

Client: khach_hang/UngDungKhach.java (mở 2 client để test).

Dữ liệu

Tài khoản lưu tại: db/taikhoan.txt

Lịch sử trận đấu lưu tại: db/lichsu.csv

📂 5. Cấu trúc thư mục

📦 LTM (thư mục gốc)

khach_hang/ (code phía client)

UngDungKhach.java → chạy client (main)

GiaoDienTroChoi.java → giao diện Swing

KetNoiKhach.java → xử lý kết nối TCP

TienIch.java → tiện ích (hash mật khẩu)

may_chu/ (code phía server)

UngDungMayChu.java → chạy server (main)

XuLyKhach.java → xử lý kết nối client

QuanLyTroChoi.java → quản lý logic game

XuLyLuotChoi.java → luật oẳn tù tì

QuanLyTaiKhoan.java → quản lý tài khoản

QuanLyLichSu.java → quản lý lịch sử + leaderboard

db/ (lưu trữ dữ liệu)

taikhoan.txt → lưu tài khoản (username:hash)

lichsu.csv → lưu lịch sử trận đấu

assets/ (ảnh giao diện README)

login.png, game.png, history.png, leaderboard.png

README.md → mô tả project

🏆 6. Các tính năng chính

🔒 Đăng ký / Đăng nhập (hash mật khẩu SHA-256).

👫 Ghép cặp tự động giữa 2 người chơi.

✊✋✌ Chơi Oẳn Tù Tì với kết quả trực quan (emoji + màu sắc).

📜 Lưu lịch sử đầy đủ vào file CSV.

🏆 Bảng xếp hạng dựa trên dữ liệu lịch sử.

🚪 Thoát phòng an toàn.

✍️ 7. Thông tin

Sinh viên thực hiện: Nguyễn Việt Ninh – CNTT 16-04

Môn học: Lập trình mạng (LTM)

Trường: Đại học Đại Nam
