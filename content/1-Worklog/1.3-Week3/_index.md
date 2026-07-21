---
title: "Week 3 Worklog"
date: 2024-01-01
weight: 3
chapter: false
pre: " <b> 1.3. </b> "
---

### Week 3 Objectives:
* Explore the **Migrate to AWS** module and begin the **Optimizing the system** module (Operations track).

### Tasks carried out this week:
| Day | Task | Start Date | Completion Date | Reference Material |
| --- | --- | --- | --- | --- |
| Mon | - Prepared a source VM image for migration <br> - Imported the VM into AWS using **VM Import/Export** to create a custom AMI <br> - Launched an EC2 instance from the imported AMI | 04/05/2026 | 04/05/2026 | <https://000014.awsstudygroup.com> |
| Tue | - Converted the database schema using the **AWS Schema Conversion Tool (SCT)** <br> - Created a replication task in **AWS DMS** <br> - Migrated sample data and validated the target database | 05/05/2026 | 05/05/2026 | <https://000043.awsstudygroup.com> |
| Wed | - Installed the replication agent for **AWS Elastic Disaster Recovery** <br> - Configured a recovery plan and launch settings <br> - Performed a test failover to validate recovery time | 06/05/2026 | 06/05/2026 | <https://000100.awsstudygroup.com> |
| Thu | - Created an **AWS Lambda** function and configured an S3 event trigger <br> - Wrote and tested serverless automation logic <br> - Reviewed execution logs in CloudWatch | 07/05/2026 | 07/05/2026 | <https://000022.awsstudygroup.com> |
| Fri | - Wrote an **AWS CloudFormation** template (YAML) <br> - Deployed the stack and verified resource creation <br> - Practiced updating and rolling back a stack | 08/05/2026 | 08/05/2026 | <https://000037.awsstudygroup.com> |

### Week 3 Achievements:
* Learned how to migrate on-premises VMs to AWS using **VM Import/Export**.
* Practiced migrating a database engine using **DMS** and converting schema with **SCT**.
* Understood disaster recovery strategy and failover using **AWS Elastic Disaster Recovery**.
* Built serverless automation workflows with **AWS Lambda** triggers.
* Provisioned infrastructure declaratively using **CloudFormation** templates.