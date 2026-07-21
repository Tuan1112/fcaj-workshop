---
title: "Worklog Tuần 5"
date: 2024-01-01
weight: 5
chapter: false
pre: " <b> 1.5. </b> "
---

### Mục tiêu tuần 5:
* Đào sâu vào các best practices về **Security** trong module Optimizing the system.

### Các công việc đã triển khai trong tuần này:
| Thứ | Công việc | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu |
| --- | --- | --- | --- | --- |
| Thứ 2 | - Kích hoạt **AWS Security Hub** và bật các security standards (CIS, AWS Foundational) <br> - Xem các findings được tổng hợp từ nhiều dịch vụ <br> - Ưu tiên xử lý theo mức độ nghiêm trọng | 18/05/2026 | 18/05/2026 | <https://000018.awsstudygroup.com> |
| Thứ 3 | - Tạo Web ACL trong **AWS WAF** <br> - Cấu hình rule chống SQL injection và rate limiting <br> - Gắn Web ACL vào Application Load Balancer | 19/05/2026 | 19/05/2026 | <https://000026.awsstudygroup.com> |
| Thứ 4 | - Tạo Customer Managed Key (CMK) trong **AWS KMS** <br> - Mã hóa và giải mã dữ liệu mẫu bằng key <br> - Cấu hình key policy để giới hạn quyền sử dụng | 20/05/2026 | 20/05/2026 | <https://000033.awsstudygroup.com> |
| Thứ 5 | - Kích hoạt **Amazon GuardDuty** <br> - Xem các finding mẫu và mức độ nghiêm trọng <br> - Cấu hình thông báo cho các finding nghiêm trọng cao | 21/05/2026 | 21/05/2026 | <https://000098.awsstudygroup.com> |
| Thứ 6 | - Tạo S3 Gateway **VPC Endpoint** <br> - Cập nhật route table để định tuyến traffic S3 riêng tư <br> - Kiểm tra truy cập S3 không đi qua internet công cộng | 22/05/2026 | 22/05/2026 | <https://000111.awsstudygroup.com> |

### Kết quả đạt được tuần 5:
* Tổng hợp các phát hiện bảo mật trên nhiều tài khoản với **Security Hub**.
* Bảo vệ ứng dụng web khỏi các lỗ hổng phổ biến bằng rule của **AWS WAF**.
* Quản lý khóa mã hóa và mã hóa dữ liệu lưu trữ với **KMS**.
* Phát hiện hoạt động bất thường và mối đe dọa tiềm ẩn với **GuardDuty**.
* Truy cập **S3** riêng tư từ VPC bằng **Interface/Gateway Endpoints**.