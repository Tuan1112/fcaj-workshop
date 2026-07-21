---
title: "Worklog Tuần 3"
date: 2024-01-01
weight: 3
chapter: false
pre: " <b> 1.3. </b> "
---

### Mục tiêu tuần 3:
* Tìm hiểu module **Migrate to AWS** và bắt đầu module **Optimizing the system** (nhánh Operations).

### Các công việc đã triển khai trong tuần này:
| Thứ | Công việc | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu |
| --- | --- | --- | --- | --- |
| Thứ 2 | - Chuẩn bị VM image nguồn để di chuyển <br> - Import VM vào AWS bằng **VM Import/Export** để tạo AMI tùy chỉnh <br> - Khởi tạo EC2 instance từ AMI đã import | 04/05/2026 | 04/05/2026 | <https://000014.awsstudygroup.com> |
| Thứ 3 | - Chuyển đổi schema database bằng **AWS Schema Conversion Tool (SCT)** <br> - Tạo replication task trong **AWS DMS** <br> - Di chuyển dữ liệu mẫu và kiểm thử database đích | 05/05/2026 | 05/05/2026 | <https://000043.awsstudygroup.com> |
| Thứ 4 | - Cài đặt replication agent cho **AWS Elastic Disaster Recovery** <br> - Cấu hình recovery plan và launch settings <br> - Thực hiện test failover để kiểm tra recovery time | 06/05/2026 | 06/05/2026 | <https://000100.awsstudygroup.com> |
| Thứ 5 | - Tạo hàm **AWS Lambda** và cấu hình trigger từ S3 event <br> - Viết và kiểm thử logic tự động hóa serverless <br> - Xem execution log trên CloudWatch | 07/05/2026 | 07/05/2026 | <https://000022.awsstudygroup.com> |
| Thứ 6 | - Viết template **AWS CloudFormation** (YAML) <br> - Deploy stack và kiểm tra tài nguyên được tạo <br> - Thực hành update và rollback stack | 08/05/2026 | 08/05/2026 | <https://000037.awsstudygroup.com> |

### Kết quả đạt được tuần 3:
* Học cách di chuyển VM on-premises lên AWS bằng **VM Import/Export**.
* Thực hành di chuyển database engine bằng **DMS** và chuyển đổi schema bằng **SCT**.
* Hiểu chiến lược khắc phục thảm họa và failover với **AWS Elastic Disaster Recovery**.
* Xây dựng workflow tự động hóa serverless với trigger của **AWS Lambda**.
* Triển khai hạ tầng theo hướng khai báo (declarative) bằng template **CloudFormation**.