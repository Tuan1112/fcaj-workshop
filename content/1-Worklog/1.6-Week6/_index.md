---
title: "Week 6 Worklog"
date: 2024-01-01
weight: 6
chapter: false
pre: " <b> 1.6. </b> "
---

### Week 6 Objectives:
* Study **Reliability** patterns and start **Containerization** basics.

### Tasks carried out this week:
| Day | Task | Start Date | Completion Date | Reference Material |
| --- | --- | --- | --- | --- |
| Mon | - Created a backup plan and backup vault in **AWS Backup** <br> - Applied the plan to EC2 and RDS resources <br> - Performed a test restore from a backup recovery point | 25/05/2026 | 25/05/2026 | <https://000013.awsstudygroup.com> |
| Tue | - Created a **VPC Peering** connection between two VPCs <br> - Updated route tables on both sides <br> - Tested connectivity between instances across the peered VPCs | 26/05/2026 | 26/05/2026 | <https://000019.awsstudygroup.com> |
| Wed | - Created an **AWS Transit Gateway** <br> - Attached multiple VPCs to the Transit Gateway <br> - Configured routing to simplify multi-VPC connectivity | 27/05/2026 | 27/05/2026 | <https://000020.awsstudygroup.com> |
| Thu | - Created an **Amazon SQS** queue and an **Amazon SNS** topic <br> - Subscribed the queue to the topic (fan-out pattern) <br> - Tested asynchronous message delivery end-to-end | 28/05/2026 | 28/05/2026 | <https://000077.awsstudygroup.com> |
| Fri | - Installed **Docker** and built a custom image from a Dockerfile <br> - Ran and tested the containerized application locally <br> - Pushed the image to a container registry | 29/05/2026 | 29/05/2026 | <https://000015.awsstudygroup.com> |

### Week 6 Achievements:
* Centralized backup policies across resources using **AWS Backup**.
* Connected two VPCs directly with **VPC Peering**.
* Simplified multi-VPC connectivity at scale using **Transit Gateway**.
* Built decoupled, asynchronous communication with **SQS** queues and **SNS** topics.
* Packaged an application into containers using **Docker** fundamentals.