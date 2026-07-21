---
title: "Worklog Tuần 6"
date: 2024-01-01
weight: 6
chapter: false
pre: " <b> 1.6. </b> "
---

### Mục tiêu tuần 6:
* Tìm hiểu các mô hình **Reliability** và bắt đầu kiến thức nền tảng về **Container hóa**.

### Các công việc đã triển khai trong tuần này:
| Thứ | Công việc | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu |
| --- | --- | --- | --- | --- |
| Thứ 2 | - Tạo backup plan và backup vault trong **AWS Backup** <br> - Áp dụng plan cho tài nguyên EC2 và RDS <br> - Thực hiện test restore từ một recovery point | 25/05/2026 | 25/05/2026 | <https://000013.awsstudygroup.com> |
| Thứ 3 | - Tạo kết nối **VPC Peering** giữa hai VPC <br> - Cập nhật route table ở cả hai phía <br> - Kiểm thử kết nối giữa các instance qua VPC peering | 26/05/2026 | 26/05/2026 | <https://000019.awsstudygroup.com> |
| Thứ 4 | - Tạo **AWS Transit Gateway** <br> - Gắn nhiều VPC vào Transit Gateway <br> - Cấu hình routing để đơn giản hóa kết nối nhiều VPC | 27/05/2026 | 27/05/2026 | <https://000020.awsstudygroup.com> |
| Thứ 5 | - Tạo queue **Amazon SQS** và topic **Amazon SNS** <br> - Subscribe queue vào topic (mô hình fan-out) <br> - Kiểm thử truyền message bất đồng bộ end-to-end | 28/05/2026 | 28/05/2026 | <https://000077.awsstudygroup.com> |
| Thứ 6 | - Cài đặt **Docker** và build image tùy chỉnh từ Dockerfile <br> - Chạy và kiểm thử ứng dụng container hóa cục bộ <br> - Push image lên container registry | 29/05/2026 | 29/05/2026 | <https://000015.awsstudygroup.com> |

### Kết quả đạt được tuần 6:
* Tập trung hóa chính sách backup cho nhiều tài nguyên bằng **AWS Backup**.
* Kết nối trực tiếp hai VPC với nhau bằng **VPC Peering**.
* Đơn giản hóa kết nối nhiều VPC ở quy mô lớn bằng **Transit Gateway**.
* Xây dựng giao tiếp bất đồng bộ, tách rời (decoupled) với queue của **SQS** và topic của **SNS**.
* Đóng gói ứng dụng vào container bằng kiến thức nền tảng của **Docker**.