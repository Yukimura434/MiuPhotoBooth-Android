# MiuPhotoBooth Android Lite

Kênh tải APK chính thức của MiuPhotoBooth Lite. Mã nguồn ứng dụng được quản lý riêng.

## Tải ứng dụng

**[Tải Android Lite 1.0.1](https://github.com/Yukimura434/MiuPhotoBooth-Android/releases/download/android-v1.0.1/MiuPhotoBooth-Android-1.0.1.apk)** · [Ghi chú phát hành](https://github.com/Yukimura434/MiuPhotoBooth-Android/releases/tag/android-v1.0.1)

- Android 10 trở lên, ARM64; bản Release tối ưu, tắt chế độ debug.
- Giữ nguyên chữ ký hiện có để nâng cấp mà không cần gỡ bản cũ.
- Ưu tiên gửi lệnh in trước khi upload cho nhân viên, sự kiện, PTB và SelfBooth; giữ kiểm tra quyền/hạn mức.
- Mở đầy đủ các màn hình khi đăng nhập sự kiện; chọn số bản in theo hạn mức còn lại.
- Cho phép chọn PhotoBooth để mở máy ảnh USB. Nếu Thư viện đang là mặc định, hãy xóa lựa chọn mặc định đó trong cài đặt ứng dụng.
- APK, SHA256SUMS.txt và mã nguồn thư viện native nguồn mở có tại trang phát hành.

Bản 1.0.1 (versionCode 10001) sửa vòng đời camera, giữ phiên và ảnh khi xoay màn hình, tạm dừng live view/đếm ngược khi xuống nền, và ngăn gửi trùng lệnh in khi bộ quản lý được tạo lại. Bao gồm sửa in không viền và bố trí thư viện frame có dữ liệu khi xoay. Đã qua 81 kiểm thử đơn vị, lint không có lỗi; bộ kiểm thử trên tablet xác nhận 20 lần xoay, đóng luồng Camera2 và một lệnh in qua máy chủ thử nghiệm. Trên tablet SM-T735 với Canon, nhịp hiển thị đạt 29,41 FPS trước xoay, 29,25 FPS sau 20 lần xoay và 28,94 FPS sau xuống nền/mở lại (mỗi lượt khoảng 20 giây). Bản nâng cấp giữ nguyên 143 tệp dữ liệu. Kiểm tra ngắn hạn không thay thế đánh giá chạy liên tục nhiều giờ hay in giấy thực tế. Các bản cũ được giữ trong lịch sử phát hành.
