# IBus-Unikey 0.7.0 Beta 1 – GTK Preferences Fix for Ubuntu 26.04

Bản IBus-Unikey gốc trên Ubuntu 26.04 gặp lỗi biên dịch khiến giao diện Preferences không thể kết nối với các hàm xử lý. Vì vậy, người dùng không thể lưu thay đổi kiểu gõ (Telex/VNI), bảng mã và nút Close cũng không hoạt động.

Bản này được biên dịch lại từ mã nguồn gốc, bổ sung tùy chọn -rdynamic để khắc phục lỗi trên.

Chức năng gõ tiếng Việt được giữ nguyên, chỉ sửa lỗi giao diện cấu hình.

Đây là bản vá không chính thức dành cho Ubuntu 26.04 (AMD64).
