---
title: "Worklog Tuần 12"
date: 2024-01-01
weight: 12
chapter: false
pre: " <b> 1.12. </b> "
---

### Mục tiêu tuần 12:
* Hoàn thiện AWS Data Pipeline và Dashboard của Đồ án tốt nghiệp.
* Hoàn tất kiểm thử, tài liệu hóa và tổng kết đồ án trước khi kết thúc kỳ thực tập.

### Các công việc đã triển khai trong tuần này:
| Thứ | Công việc                                                                                                                                                 | Ngày bắt đầu | Ngày hoàn thành |
| --- | ------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------ | --------------- |
| Thứ 2 | Triển khai **Amazon Kinesis Data Firehose**. Viết hàm **AWS Lambda** Processor để làm sạch dữ liệu log và định tuyến vào S3 Data Lake.                    | 06/07/2026   | 06/07/2026      |
| Thứ 3 | Cấu hình **Amazon Athena**, tạo External Tables trỏ tới S3 và kiểm thử câu lệnh SQL. Kích hoạt **GuardDuty** để phát hiện mối đe dọa.                     | 07/07/2026   | 07/07/2026      |
| Thứ 4 | Thiết lập **Lookout for Metrics** đọc dữ liệu từ S3 để nhận diện bất thường tự động. Khởi tạo Backend (Node.js/Express) và tích hợp AWS SDK.               | 08/07/2026   | 08/07/2026      |
| Thứ 5 | Xây dựng giao diện Frontend Dashboard (React/Vue), kết nối API Backend để hiển thị lưu lượng mạng và cảnh báo bảo mật, kiểm thử luồng dữ liệu end-to-end. | 09/07/2026   | 09/07/2026      |
| Thứ 6 | Tối ưu hóa UI/UX Dashboard và tinh chỉnh truy vấn Athena để tối ưu chi phí. Hoàn thiện tài liệu và sơ đồ kiến trúc (Draw.io), tổng kết kỳ thực tập.        | 10/07/2026   | 10/07/2026  |

### Kết quả đạt được tuần 12:
* Xây dựng hoàn chỉnh pipeline dữ liệu AWS Serverless: **Kinesis → Lambda → S3 → Athena**.
* Kích hoạt khả năng phát hiện mối đe dọa và bất thường bằng AI với **GuardDuty** và **Lookout for Metrics**.
* Phát triển Backend Node.js/Express tích hợp AWS SDK để truy vấn Athena và lấy cảnh báo bảo mật.
* Hoàn thiện Frontend Dashboard hiển thị biểu đồ lưu lượng mạng và cảnh báo bảo mật theo thời gian thực.
* Hoàn tất kiểm thử end-to-end toàn bộ luồng dữ liệu, từ thu thập log đến hiển thị trên dashboard.
* Hoàn thiện toàn bộ tài liệu và sơ đồ kiến trúc, hoàn thành Đồ án tốt nghiệp đúng thời hạn kết thúc thực tập.