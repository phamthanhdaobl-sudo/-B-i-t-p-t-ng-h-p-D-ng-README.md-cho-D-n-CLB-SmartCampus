# 🎓 SmartCampus

SmartCampus là ứng dụng di động **tiện lợi** giúp sinh viên PTIT tra cứu lịch học, phòng trống và nhận *thông báo mới nhất* từ nhà trường.

## ✨ Tính năng đã hoàn thành

- Tra cứu lịch học theo mã sinh viên
  - Ghi chú: Sinh viên tra cứu lịch học bằng mã sinh viên.
- Xem danh sách phòng trống theo tòa nhà
  - Ghi chú: Danh sách phòng trống được xem theo từng tòa nhà.

[Trang chủ CLB Lập trình PTIT](https://clblaptrinh.ptit.edu.vn)

![Logo SmartCampus](https://placehold.co/240x120/2563eb/ffffff?text=SmartCampus)

> ⚠️ SmartCampus đang trong giai đoạn phát triển và chưa được sử dụng cho mục đích chính thức.

---

## 🚀 Cài đặt và chạy dự án

Sao chép dự án về máy, cài đặt các gói phụ thuộc và khởi động ứng dụng bằng các lệnh sau:

```bash
git clone https://github.com/clb-lap-trinh/smartcampus.git
npm install
npm start
```

## ✅ Tiến độ phát triển

- [x] Tra cứu lịch học theo mã sinh viên
- [x] Xem danh sách phòng trống theo tòa nhà
- [ ] Thông báo đẩy (push notification)
- [ ] Đăng nhập bằng tài khoản trường

## 📦 Thư viện đang sử dụng

| Thư viện | Phiên bản | Mục đích |
|:---|:---:|:---|
| React Native | 0.74 | Xây giao diện đa nền tảng iOS/Android |
| Axios | 1.6 | Gọi API lấy dữ liệu lịch học |

## Ghi chú ôn tập

Trong Markdown, thêm dấu gạch chéo ngược trước ký tự đặc biệt để hiển thị nguyên văn: `\*` hiển thị thành \* và `\#` hiển thị thành \#.

### Phần 4 – Bẫy cú pháp

Đoạn Markdown ban đầu có đúng hai lỗi cú pháp:

1. **Bảng thiếu dòng phân cách:** Sau dòng tiêu đề bảng phải có dòng phân cách dùng dấu gạch ngang, chẳng hạn `| --- | --- |`.
2. **Task List thiếu khoảng trắng:** Cần có một dấu cách sau dấu `-`, viết `- [x]` và `- [ ]`, không viết `-[x]` hoặc `-[ ]`.

Đoạn đã sửa:

| Tính năng | Trạng thái |
| --- | --- |
| Tra cứu lịch học | Xong |
| Push notification | Đang làm |

- [x] Tra cứu lịch học
- [ ] Push notification
