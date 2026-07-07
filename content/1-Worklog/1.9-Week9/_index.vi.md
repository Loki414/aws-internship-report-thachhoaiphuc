---
title: "Worklog Tuần 9"
date: 2024-01-01
weight: 9
chapter: false
pre: " <b> 1.9. </b> "
---

### Mục tiêu tuần 9:

* Bắt đầu triển khai dự án **SmartHospital P2TB** — hệ thống quản lý bệnh viện trên AWS Serverless.
* Phân tích trải nghiệm người dùng và thiết kế kiến trúc frontend theo vai trò Bệnh nhân / Bác sĩ.
* Chuẩn bị nền tảng thiết kế hồ sơ bệnh án, mapping dữ liệu và quy ước hiển thị CCCD.

### Các công việc cần triển khai trong tuần này:

| Thứ | Công việc | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu |
| --- | --- | --- | --- | --- |
| 2 | - Phân tích trải nghiệm người dùng cho Bệnh nhân và Bác sĩ <br>&emsp; + Xác định màn hình: đăng nhập, đăng ký, dashboard <br>&emsp; + Đặt lịch khám, thông tin cá nhân, hồ sơ bệnh án <br>&emsp; + Xét nghiệm, hóa đơn, hàng chờ khám, phiếu khám, đơn thuốc | 15/06/2026 | 15/06/2026 | SmartHospital P2TB – Proposal |
| 3 | - Thiết kế route frontend theo vai trò <br>&emsp; + Bệnh nhân → cổng bệnh nhân sau đăng nhập <br>&emsp; + Bác sĩ → giao diện bác sĩ <br>&emsp; + Sidebar/menu phù hợp nghiệp vụ từng vai trò | 16/06/2026 | 16/06/2026 | SmartHospital P2TB – Proposal |
| 4 | - Thiết kế bố cục hồ sơ bệnh án <br>&emsp; + Một bệnh nhân – một quyển hồ sơ, nhiều trang/sự kiện y tế <br>&emsp; + Lịch khám, phiếu khám, xét nghiệm, đơn thuốc, hóa đơn, tài liệu y tế | 17/06/2026 | 17/06/2026 | SmartHospital P2TB – Proposal |
| 5 | - Xác định dữ liệu frontend cần lấy từ backend <br>&emsp; + patient/doctor profile, appointments, medical record <br>&emsp; + examinations, prescriptions, lab results, invoices <br>&emsp; + ledger verification result | 18/06/2026 | 18/06/2026 | SmartHospital P2TB – API spec |
| 6 | - Lên kế hoạch xử lý trạng thái UI: loading, empty, API error, token hết hạn <br>- Chuẩn hóa quy ước hiển thị CCCD/recordId trên UI <br>- Tổng hợp tuần 9 | 19/06/2026 | 19/06/2026 | SmartHospital P2TB – Proposal |

### Kết quả đạt được tuần 9:

* Hoàn thành phân tích UX và danh sách màn hình cho hai vai trò Bệnh nhân và Bác sĩ.

* Thiết kế route frontend và cấu trúc menu theo vai trò.

* Xác định mô hình hồ sơ bệnh án dạng timeline và mapping dữ liệu frontend–backend.

* Chuẩn hóa quy ước hiển thị CCCD/recordId, tránh lệch mã giữa các trang.

* Lên kế hoạch xử lý các trạng thái UI quan trọng (loading, empty, error, token expired, blockchain chưa có block, thanh toán chờ gateway).
