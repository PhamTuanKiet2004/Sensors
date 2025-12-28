# Thực hành 1: Máy Đo Chuyển Động (Motion Tracker)
Nhiệm vụ: Xây dựng ứng dụng đếm số lần "Nhảy" (Jump) hoặc "Lắc mạnh" (Shake) dựa trên gia tốc kế người dùng (UserAccelerometer).

Nguyên lý ứng dụng
Sử dụng UserAccelerometer để loại bỏ trọng lực. Nếu dùng Accelerometer thường, bạn phải tự trừ đi 9.8 m/s² (rất phức tạp vì hướng trọng lực thay đổi khi xoay máy).
Phát hiện đỉnh (Peak Detection): Khi gia tốc vượt ngưỡng (Threshold), ghi nhận sự kiện.

