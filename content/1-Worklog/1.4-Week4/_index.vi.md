---
title: "Worklog Tuần 4"
date: 2024-01-01
weight: 4
chapter: false
pre: " <b> 1.4. </b> "
---

### Mục tiêu tuần 4:
* Tiếp tục module **Optimizing the system**: best practices về Operations và Security.

### Các công việc đã triển khai trong tuần này:
| Thứ | Công việc | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu |
| --- | --- | --- | --- | --- |
| Thứ 2 | - Cài đặt SSM Agent trên các instance được quản lý <br> - Chạy automation document của **AWS Systems Manager** <br> - Thực hành patch management trên nhiều instance | 11/05/2026 | 11/05/2026 | <https://000031.awsstudygroup.com> |
| Thứ 3 | - Cấu hình IAM permission cho **Session Manager** <br> - Kết nối EC2 instance mà không cần mở port SSH hoặc dùng key pair <br> - Tìm hiểu các tùy chọn ghi log session | 12/05/2026 | 12/05/2026 | <https://000058.awsstudygroup.com> |
| Thứ 4 | - Khởi tạo project **AWS CDK** <br> - Viết stack hạ tầng dưới dạng code (TypeScript/Python) <br> - Deploy và destroy stack qua CDK CLI | 13/05/2026 | 13/05/2026 | <https://000038.awsstudygroup.com> |
| Thứ 5 | - Tạo policy **IAM Permission Boundary** <br> - Gắn boundary vào role dùng để phân quyền quản trị <br> - Kiểm thử boundary giới hạn đúng quyền hiệu lực | 14/05/2026 | 14/05/2026 | <https://000030.awsstudygroup.com> |
| Thứ 6 | - Lưu credentials của ứng dụng vào **AWS Secrets Manager** <br> - Cấu hình rotation tự động cho secret <br> - Truy xuất secret bằng AWS SDK trong code | 15/05/2026 | 15/05/2026 | <https://000096.awsstudygroup.com> |

### Kết quả đạt được tuần 4:
* Sử dụng **Systems Manager** để tự động hóa việc patch và cấu hình trên nhiều instance.
* Truy cập EC2 instance an toàn qua **Session Manager**, không cần mở port SSH.
* Viết hạ tầng dưới dạng code thực sự bằng **AWS CDK**.
* Áp dụng **IAM Permission Boundaries** để phân quyền tạo role một cách an toàn.
* Quản lý và luân chuyển (rotate) credentials nhạy cảm với **AWS Secrets Manager**.