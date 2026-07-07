---
title: "Worklog Tuần 10"
date: 2024-01-01
weight: 10
chapter: false
pre: " <b> 1.10. </b> "
---

### Mục tiêu tuần 10:

* Xây dựng giao diện bệnh nhân và bác sĩ cơ bản cho SmartHospital P2TB.
* Triển khai frontend service layer gọi API backend (React/Vite).
* Kiểm thử với dữ liệu seed và sửa lỗi mapping dữ liệu frontend–backend.

### Các công việc cần triển khai trong tuần này:

| Thứ | Công việc | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu |
| --- | --- | --- | --- | --- |
| 2 | - Xây dựng giao diện bệnh nhân cơ bản <br>&emsp; + Trang thông tin cá nhân, cập nhật liên hệ <br>&emsp; + Hiển thị CCCD, ngày sinh, giới tính, địa chỉ, BHYT <br>&emsp; + Trạng thái dữ liệu từ Cognito/backend | 22/06/2026 | 22/06/2026 | SmartHospital P2TB – Frontend |
| 3 | - Xây dựng giao diện đặt lịch khám cho bệnh nhân <br>&emsp; + Chọn khoa, bác sĩ, ngày, ca/giờ khám <br>&emsp; + Gửi yêu cầu đặt lịch <br>&emsp; + Hiển thị danh sách lịch hẹn hiện có | 23/06/2026 | 23/06/2026 | SmartHospital P2TB – Frontend |
| 4 | - Xây dựng giao diện bác sĩ cơ bản <br>&emsp; + Dashboard bác sĩ, danh sách lịch khám/hàng chờ <br>&emsp; + Thông tin bệnh nhân, tìm kiếm theo CCCD <br>&emsp; + Mở hồ sơ bệnh án chuẩn bị lập phiếu khám | 24/06/2026 | 24/06/2026 | SmartHospital P2TB – Frontend |
| 5 | - Xây dựng frontend service gọi API backend <br>&emsp; + Chuẩn hóa Authorization token <br>&emsp; + Xử lý lỗi 401/403, response rỗng <br>&emsp; + Map dữ liệu backend sang component UI | 25/06/2026 | 25/06/2026 | SmartHospital P2TB – API spec |
| 6 | - Kiểm thử frontend với dữ liệu seed ban đầu <br>- Sửa lỗi mapping (patientId/maBN, recordId/maHSBA, doctorName/hoTen) <br>- Sửa lỗi UI: refresh CloudFront, route sai, menu sai vai trò, form không reset | 26/06/2026 | 26/06/2026 | SmartHospital P2TB – Frontend |

### Kết quả đạt được tuần 10:

* Hoàn thành giao diện bệnh nhân: thông tin cá nhân và đặt lịch khám.

* Hoàn thành giao diện bác sĩ cơ bản: dashboard, hàng chờ, tìm kiếm CCCD.

* Triển khai frontend service layer với xử lý token và lỗi API chuẩn hóa.

* Phát hiện và sửa các lỗi mapping dữ liệu giữa backend và frontend.

* Khắc phục lỗi UX: route sai vai trò, trang không load sau refresh CloudFront.
