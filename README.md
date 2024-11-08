# 📦 Hướng dẫn thiết lập dự án

## 🚀 Bắt đầu

Trước tiên, hãy clone dự án về máy của bạn:

```bash
git clone https://github.com/HieuNguyen3112/OpenSource-final.git
```

🔧 Thiết lập môi trường

Mở thư mục dự án vừa tải về.
Kiểm tra tập tin .env và cập nhật thông tin đăng nhập cơ sở dữ liệu.

Tạo cơ sở dữ liệu MySQL theo các thông tin có sẵn trong tệp .env.

Tôi khuyên bạn nên sử dụng XAMPP có PHP từ 7.1 -> 7.3 để không bị xung đột phiên bản khi thiết lập MySQL

⚙️ Cài đặt các gói phụ thuộc

Mở Terminal hoặc Command Prompt và chạy lệnh sau:

```bash
composer install
```
📊 Thiết lập cơ sở dữ liệu

Chạy lệnh để di chuyển các bảng:

```bash
php artisan migrate
```
Chạy seeder để điền dữ liệu mẫu:
```bash
php artisan db:seed
```
Tạo khóa ứng dụng:
```bash
php artisan key:generate
```
▶️ Chạy dự án

Sau khi hoàn tất các bước trên, khởi chạy dự án bằng lệnh:
```bash
php artisan serve
```
🌐 Truy cập vào URL:

```bash
http://127.0.0.1:8000
```
📋 Thông tin đăng nhập

Tất cả các thông tin đăng nhập được cung cấp trong thư mục:
```bash
[01 LOGIN DETAILS & PROJECT INFO.txt]
```
🔍 Hãy kiểm tra và sử dụng chúng để truy cập vào hệ thống.
💡 Ghi chú: Nếu gặp vấn đề trong quá trình cài đặt, vui lòng kiểm tra lại cấu hình môi trường và đảm bảo rằng bạn đã cài đặt PHP, Composer, và MySQL.



