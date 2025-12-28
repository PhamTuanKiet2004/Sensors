# Thực hành 1: Máy Đo Chuyển Động (Motion Tracker)
Nhiệm vụ: Xây dựng ứng dụng đếm số lần "Nhảy" (Jump) hoặc "Lắc mạnh" (Shake) dựa trên gia tốc kế người dùng (UserAccelerometer).

Nguyên lý ứng dụng
Sử dụng UserAccelerometer để loại bỏ trọng lực. Nếu dùng Accelerometer thường, bạn phải tự trừ đi 9.8 m/s² (rất phức tạp vì hướng trọng lực thay đổi khi xoay máy).
Phát hiện đỉnh (Peak Detection): Khi gia tốc vượt ngưỡng (Threshold), ghi nhận sự kiện.

## Getting Started

This project is a starting point for a Flutter application.

A few resources to get you started if this is your first Flutter project:

- [Lab: Write your first Flutter app](https://docs.flutter.dev/get-started/codelab)
- [Cookbook: Useful Flutter samples](https://docs.flutter.dev/cookbook)

For help getting started with Flutter development, view the
[online documentation](https://docs.flutter.dev/), which offers tutorials,
samples, guidance on mobile development, and a full API reference.
