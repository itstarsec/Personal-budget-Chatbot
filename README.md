# Quản lý chi tiêu cá nhân trong tháng với Chatbot
- Dự án sử dụng 325 dòng code Python.
- Chức năng đa dạng, linh hoạt để tương tác với bot.
## Hướng dẫn cài đặt Chatbot:
### Bước 1: Cài đặt virtualenv
Nếu bạn chưa cài đặt virtualenv, bạn có thể cài đặt nó bằng pip:
```
pip install virtualenv
```

### Bước 2: Tạo một môi trường ảo
Đầu tiên, di chuyển đến thư mục bạn muốn tạo môi trường ảo và chạy lệnh sau:
```
virtualenv budget
```
Ở đây, myenv là tên bạn muốn đặt cho môi trường ảo. Thay thế nó bằng bất kỳ tên nào bạn muốn.

### Bước 3: Kích hoạt môi trường ảo
Sử dụng lệnh sau để kích hoạt môi trường ảo:
```
source budget/bin/activate
```
### Bước 4: Cài đặt các gói cần thiết
Bây giờ bạn có thể cài đặt các gói Python cần thiết vào môi trường ảo này bằng pip:
```
pip install python-telegram-bot==13.13
```

### Bước 5: Chạy mã Python ở chế độ nền
Để chạy mã Python ở chế độ nền, bạn có thể sử dụng nohup. Ví dụ:

```
nohup python budget.py &
```
### Bước 6: Tắt môi trường ảo
Sau khi bạn đã hoàn thành công việc, bạn có thể tắt môi trường ảo bằng cách gõ:

```
deactivate
```
Điều này sẽ đưa bạn trở lại môi trường Python toàn cục.

# Vậy là bạn đã triển khai Budget Chatbot thành công trên Ubuntu 💰.
