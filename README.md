# MiuPhotoBooth Android Lite

Kênh tải APK chính thức. Mã nguồn ứng dụng được quản lý riêng.

## Tải ứng dụng

**[Tải Android 1.1.1](https://github.com/Yukimura434/MiuPhotoBooth-Android/releases/download/android-v1.1.1/MiuPhotoBooth-Android-1.1.1.apk)** · [Ghi chú phát hành](https://github.com/Yukimura434/MiuPhotoBooth-Android/releases/tag/android-v1.1.1)

- Android 10 trở lên, ARM64; bản Release tối ưu.
- Cài nâng cấp trực tiếp, giữ dữ liệu và cài đặt, không cần gỡ bản cũ.
- Canon Fit giữ JPEG gốc và căn giữa; Canon Fill gửi JPEG trực tiếp với vùng bù đã hiệu chỉnh, không qua PDF/PWG.
- Canon Fill dùng lệnh Fill, căn giữa và đặt bốn lề IPP bằng 0.
- Hàng đợi giữ cố định máy in, tùy chọn và số bản đã chọn, kể cả sau khi khởi động lại.
- Mã QR nhận ảnh offline ngắn hơn, dễ quét hơn và vẫn mở được mã từ các bản cũ.
- Giữ nguyên luồng chụp, xử lý ảnh, Canon và Epson trực tiếp của 1.1.0.

Bản 1.1.1 (versionCode 10018): 157 kiểm thử ứng dụng và 9 kiểm thử ESC/P-R đạt; lint Release không có lỗi. APK dùng cùng chứng thư với 1.1.0 để nâng cấp tại chỗ. Chín thư viện native giữ nguyên từng byte; quá trình đóng gói không gửi thêm lệnh in vật lý.

APK và SHA256SUMS.txt nằm tại trang phát hành. Mã nguồn tương ứng của các thư viện native không đổi nằm trong `native-sources.zip` của bản 1.1.0. Các bản cũ được giữ trong lịch sử.
