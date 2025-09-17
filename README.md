<h2 align="center">
    <a href="https://dainam.edu.vn/vi/khoa-cong-nghe-thong-tin">
    🎓 Faculty of Information Technology (DaiNam University)
    </a>
</h2>
<h2 align="center">
   GAME OẲN TÙ TÌ TCP
</h2>
<div align="center">
    <p align="center">
        <img src="docs/aiotlab_logo.png" alt="AIoTLab Logo" width="170"/>
        <img src="docs/fitdnu_logo.png" alt="AIoTLab Logo" width="180"/>
        <img src="docs/dnu_logo.png" alt="DaiNam University Logo" width="200"/>
    </p>

[![AIoTLab](https://img.shields.io/badge/AIoTLab-green?style=for-the-badge)](https://www.facebook.com/DNUAIoTLab)
[![Faculty of Information Technology](https://img.shields.io/badge/Faculty%20of%20Information%20Technology-blue?style=for-the-badge)](https://dainam.edu.vn/vi/khoa-cong-nghe-thong-tin)
[![DaiNam University](https://img.shields.io/badge/DaiNam%20University-orange?style=for-the-badge)](https://dainam.edu.vn)

</div>
📘 1. Giới thiệu Hệ thống được xây dựng nhằm mô phỏng trò chơi Oẳn Tù Tì (Rock–Paper–Scissors) giữa hai người chơi thông qua Java TCP Socket.
Gồm 2 phần:

Máy chủ (Server): quản lý tài khoản, kết nối, ghép cặp, xử lý trận đấu, lưu lịch sử, bảng xếp hạng.
Máy khách (Client): giao diện Swing thân thiện, cho phép đăng nhập, chơi, xem lịch sử, thoát phòng.
👉 Ưu điểm:

Kết nối TCP ổn định.
Giao diện trực quan, dùng emoji ✊✋✌.
Có lưu lịch sử và bảng xếp hạng.
Hỗ trợ thoát phòng an toàn.
🛠 2. Công nghệ sử dụng

Ngôn ngữ: Java (JDK 17+ / JDK 21)
Giao diện: Java Swing
Kết nối: TCP Socket
Lưu trữ: File txt, csv
IDE khuyến nghị: Eclipse IDE
📸 3. Ảnh giao diện

🔑 Đăng nhập Giao diện đăng nhập

🎮 Chơi game Giao diện chơi 📂 Lịch sử Lịch sử trận đấu 🏆 Bảng xếp hạng Bảng xếp hạng

🚀 4. Cài đặt & chạy

Cài JDK 17+ (hoặc JDK 21).
Clone hoặc copy project về máy.
Mở project trong Eclipse.
Chạy Server: may_chu/UngDungMayChu.java.
Chạy Client: khach_hang/UngDungKhach.java (mở 2 client để test).
Tài khoản lưu tại db/taikhoan.txt, lịch sử lưu tại db/lichsu.csv.
📦 LTM (thư mục gốc của project)

khach_hang/ (code phía client)

UngDungKhach.java → chạy client (main)

GiaoDienTroChoi.java → giao diện Swing

KetNoiKhach.java → xử lý kết nối TCP

TienIch.java → tiện ích (hash mật khẩu, hỗ trợ)

may_chu/ (code phía server)

UngDungMayChu.java → chạy server (main)

XuLyKhach.java → xử lý kết nối từng client

QuanLyTroChoi.java → quản lý logic ghép phòng & trận

XuLyLuotChoi.java → xử lý luật oẳn tù tì

QuanLyTaiKhoan.java → quản lý tài khoản (đăng ký, lưu file)

QuanLyLichSu.java → quản lý lịch sử và bảng xếp hạng

db/ (thư mục lưu trữ dữ liệu)

taikhoan.txt → lưu tài khoản (username:hash)

lichsu.csv → lưu lịch sử trận đấu

assets/ (ảnh giao diện để chèn README)

login.png

game.png

history.png

leaderboard.png

README.md (file mô tả project) 🏆 6. Các tính năng chính

🔒 Đăng ký / Đăng nhập (hash mật khẩu SHA-256).
👫 Ghép cặp tự động giữa 2 người chơi.
✊✋✌ Chơi Oẳn Tù Tì với kết quả trực quan (emoji + màu sắc).
📜 Lưu lịch sử đầy đủ vào file CSV.
🏆 Bảng xếp hạng từ lịch sử thực tế.
🚪 Hỗ trợ thoát phòng.
✍️ Sinh viên thực hiện: Nguyễn Việt Ninh – CNTT 16-04
📅 Môn học: Lập trình mạng (LTM)
