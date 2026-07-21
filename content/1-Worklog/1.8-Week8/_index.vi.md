---
title: "Worklog Tuần 8"
date: 2024-01-01
weight: 8
chapter: false
pre: " <b> 1.8. </b> "
---

### Mục tiêu tuần 8:
* Bắt đầu module **Application Modernization**, tập trung vào series Serverless DevAx.

### Các công việc đã triển khai trong tuần này:
| Thứ | Công việc | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu |
| --- | --- | --- | --- | --- |
| Thứ 2 | - Phân tích một ứng dụng monolithic mẫu <br> - Xác định ranh giới service bằng phân tích domain <br> - Lập kế hoạch phân rã theo từng bước | 08/06/2026 | 08/06/2026 | <https://000050.awsstudygroup.com> |
| Thứ 3 | - Xây dựng pipeline CI/CD riêng cho một microservice <br> - Tự động hóa các bước build, test, deploy <br> - Kiểm tra release độc lập không ảnh hưởng service khác | 09/06/2026 | 09/06/2026 | <https://000051.awsstudygroup.com> |
| Thứ 4 | - Triển khai thành phần microservice và expose qua API Gateway <br> - Kiểm thử giao tiếp giữa các service <br> - Xem xét tính cách ly (isolation) và fault tolerance | 10/06/2026 | 10/06/2026 | <https://000052.awsstudygroup.com> |
| Thứ 5 | - Cấu hình **Amazon EventBridge**/SNS để định tuyến event <br> - Triển khai mô hình publish/subscribe giữa các service <br> - Kiểm thử giao tiếp decoupled end-to-end | 11/06/2026 | 11/06/2026 | <https://000054.awsstudygroup.com> |
| Thứ 6 | - Thiết lập **Amazon Cognito** để xác thực người dùng <br> - Triển khai luồng login/token cho SPA <br> - Bảo vệ các API call bằng JWT token | 12/06/2026 | 12/06/2026 | <https://000055.awsstudygroup.com> |

### Kết quả đạt được tuần 8:
* Hiểu quy trình và thách thức khi phân rã một ứng dụng monolithic.
* Tự động hóa việc release microservice thông qua pipeline CI/CD.
* Xây dựng các thành phần microservice độc lập giao tiếp qua API/event.
* Áp dụng pattern event-driven để tách rời (decouple) các service.
* Triển khai luồng xác thực cho Single Page Application (SPA).