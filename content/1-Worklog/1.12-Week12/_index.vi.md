---
title: "Worklog Tuần 12"
date: 2024-01-01
weight: 12
chapter: false
pre: " <b> 1.12. </b> "
---

### Mục tiêu tuần 12:

* Bổ sung giao diện kiểm tra blockchain trong hồ sơ bệnh án.
* Kiểm thử toàn bộ luồng bệnh nhân và bác sĩ trên CloudFront.
* Hoàn thiện dự án SmartHospital P2TB và chuẩn bị báo cáo thực tập.

### Các công việc cần triển khai trong tuần này:

| Thứ | Công việc | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu |
| --- | --- | --- | --- | --- |
| 2 | - Bổ sung giao diện kiểm tra blockchain trong hồ sơ bệnh án <br>&emsp; + Trạng thái VALID/INVALID/NO_LEDGER_DATA <br>&emsp; + Số block, hash cuối, lỗi block, transactionHash AMB/Ethereum, blockNumber | 06/07/2026 | 06/07/2026 | SmartHospital P2TB – Blockchain |
| 3 | - Kiểm thử UI blockchain sau reset dataset và backfill ledger <br>&emsp; + Giải thích INVALID khi dữ liệu bị sửa hoặc ledger cũ chưa xóa sau reset | 07/07/2026 | 07/07/2026 | SmartHospital P2TB – Blockchain |
| 4 | - Kiểm thử toàn bộ luồng bệnh nhân trên CloudFront <br>&emsp; + Đăng nhập, thông tin cá nhân, đặt lịch, hồ sơ bệnh án <br>&emsp; + Phiếu khám, đơn thuốc, xét nghiệm, hóa đơn, thanh toán thật | 08/07/2026 | 08/07/2026 | SmartHospital P2TB – E2E test |
| 5 | - Kiểm thử toàn bộ luồng bác sĩ <br>&emsp; + Đăng nhập, hàng chờ khám, tìm hồ sơ bằng CCCD <br>&emsp; + Lập phiếu khám, kê đơn, tạo yêu cầu xét nghiệm <br>&emsp; + Kiểm tra dữ liệu sau lưu xuất hiện trong hồ sơ bệnh án | 09/07/2026 | 09/07/2026 | SmartHospital P2TB – E2E test |
| 6 | - Sửa lỗi giao diện cuối cùng (layout, bảng hóa đơn, nút thanh toán, blockchain message, CloudFront cache) <br>- Chuẩn bị ảnh minh chứng và mô tả công việc cho báo cáo <br>- Tổng kết dự án SmartHospital P2TB | 10/07/2026 | 10/07/2026 | SmartHospital P2TB – Report |

### Kết quả đạt được tuần 12:

* Hoàn thiện giao diện kiểm tra blockchain với trạng thái VALID/INVALID/NO_LEDGER_DATA.

* Kiểm thử thành công luồng bệnh nhân và bác sĩ end-to-end trên CloudFront.

* Sửa các lỗi UI cuối cùng: cache CloudFront, localStorage, layout hồ sơ bệnh án.

* Chuẩn bị ảnh minh chứng báo cáo: đặt lịch, timeline hồ sơ, thanh toán thật, kiểm tra blockchain, đồng bộ CCCD.

* Hoàn thành dự án SmartHospital P2TB trong 4 tuần triển khai (tuần 9–12).
