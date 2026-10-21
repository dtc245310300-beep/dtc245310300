# Website quảng bá sản phẩm bằng WordPress

## 1. Mục tiêu
Xây dựng website quảng bá sản phẩm sử dụng WordPress,
MySQL, phpMyAdmin và Nginx Reverse Proxy.

## 2. Công nghệ
- WordPress
- MySQL
- phpMyAdmin
- Docker Compose
- Nginx

## 3. Khởi động dự án
1. Tạo file .env dựa trên .env.example.
2. Điền các mật khẩu riêng.
3. Chạy:
   sudo docker compose config -q
   sudo docker compose up -d

## 4. Truy cập
- Website: http://localhost
- phpMyAdmin: http://127.0.0.1:8081

## 5. Bảo mật
- Không công khai cổng MySQL.
- Giới hạn phpMyAdmin vào localhost.
- Sử dụng file .env để lưu mật khẩu.
- Nginx cấu hình security headers.
