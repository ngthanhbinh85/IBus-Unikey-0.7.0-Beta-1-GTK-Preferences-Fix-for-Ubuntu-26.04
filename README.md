# IBus-Unikey 0.7.0 Beta 1 – GTK Preferences Fix for Ubuntu 26.04

Bản IBus-Unikey gốc trên Ubuntu 26.04 gặp lỗi biên dịch khiến giao diện Preferences không thể kết nối với các hàm xử lý. Vì vậy, người dùng không thể lưu thay đổi kiểu gõ (Telex/VNI), bảng mã,... và nút Close cũng không hoạt động.

Bản này được biên dịch lại từ mã nguồn gốc để dùng tạm trong thời gian chờ nhà cung cung phát hành bản vá chính thức.

Chức năng gõ tiếng Việt được giữ nguyên, chỉ sửa lỗi giao diện cấu hình.

Đây là bản vá không chính thức dành cho Ubuntu 26.04 (AMD64). Tôi không giữ bản quyền nào.

## Cài đặt

Download và chạy trong Terminal:

```bash
sudo apt install './ibus-unikey_0.7.0~beta1-3_amd64.deb'
```

Nếu máy đã cài IBus-Unikey cùng phiên bản hoặc bị báo:

```bash
ibus-unikey is already the newest version (0.7.0~beta1-3).
```

Dùng:

```bash
sudo apt install --reinstall './ibus-unikey_0.7.0~beta1-3_amd64.deb'
```
