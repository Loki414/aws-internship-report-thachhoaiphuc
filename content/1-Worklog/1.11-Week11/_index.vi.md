---
title: "Worklog Tuần 11"
date: 2024-01-01
weight: 11
chapter: false
pre: " <b> 1.11. </b> "
---

### Mục tiêu tuần 11:

* Hoàn thiện giao diện hồ sơ bệnh án dạng timeline cho bệnh nhân.
* Hoàn thiện luồng bác sĩ lập phiếu khám, kê đơn và yêu cầu xét nghiệm.
* Triển khai giao diện hóa đơn và thanh toán VNPay/MoMo.

### Các công việc cần triển khai trong tuần này:

| Thứ | Công việc | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu |
| --- | --- | --- | --- | --- |
| 2 | - Hoàn thiện giao diện hồ sơ bệnh án bệnh nhân <br>&emsp; + Hiển thị mã hồ sơ theo CCCD, thông tin bệnh nhân <br>&emsp; + Tóm tắt lịch sử bệnh, thống kê đợt khám/phiếu khám/đơn thuốc/xét nghiệm | 29/06/2026 | 29/06/2026 | SmartHospital P2TB – Frontend |
| 3 | - Hoàn thiện timeline hồ sơ bệnh án theo đợt khám/ngày khám <br>&emsp; + Thẻ lịch khám, phiếu khám, xét nghiệm, đơn thuốc, hóa đơn <br>&emsp; + Bật/tắt bộ lọc theo loại sự kiện và theo ngày | 30/06/2026 | 30/06/2026 | SmartHospital P2TB – Frontend |
| 4 | - Sửa lỗi lệch thông tin hồ sơ giữa tiêu đề và chi tiết phiếu khám/xét nghiệm/đơn thuốc <br>&emsp; + Ưu tiên recordId/medicalRecordId/citizenId dạng CCCD trên toàn bộ component | 01/07/2026 | 01/07/2026 | SmartHospital P2TB – Frontend |
| 5 | - Hoàn thiện giao diện bác sĩ lập phiếu khám <br>&emsp; + Chọn bệnh nhân/hồ sơ bằng CCCD <br>&emsp; + Nhập triệu chứng, chẩn đoán, lời dặn <br>&emsp; + Tạo phiếu khám, kê đơn thuốc, yêu cầu xét nghiệm qua API | 02/07/2026 | 02/07/2026 | SmartHospital P2TB – API spec |
| 6 | - Hoàn thiện giao diện hóa đơn và thanh toán bệnh nhân <br>&emsp; + Hóa đơn chờ/đã thanh toán, chi tiết hóa đơn <br>&emsp; + Chuyển sang VNPay/MoMo theo paymentUrl <br>- UI nhận kết quả thanh toán sau returnUrl, reload hóa đơn từ backend | 03/07/2026 | 03/07/2026 | SmartHospital P2TB – Payment |

### Kết quả đạt được tuần 11:

* Hoàn thiện hồ sơ bệnh án dạng timeline với bộ lọc theo loại sự kiện và ngày.

* Đồng bộ recordId/CCCD trên toàn bộ component, sửa lỗi lệch thông tin hồ sơ.

* Hoàn thiện luồng bác sĩ: lập phiếu khám, kê đơn, tạo yêu cầu xét nghiệm.

* Triển khai thanh toán thật qua VNPay/MoMo với xử lý kết quả returnUrl/callback.
