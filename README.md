# AWS Multi-Tier Web Application Deployment

## Project Overview

This project demonstrates a Multi-Tier Web Application deployed on AWS.

### Architecture

<img width="1536" height="1024" alt="01_architecture-diagram png" src="https://github.com/user-attachments/assets/9aa85ea5-b76f-4339-9568-32012bbb081b" />

---

## AWS Services Used

- Amazon EC2
- Amazon RDS MySQL
- Application Load Balancer (ALB)
- Security Groups
- VPC

---

## EC2 Instances

<img width="1366" height="768" alt="02_ec2-instances" src="https://github.com/user-attachments/assets/2d397a11-bd3f-498a-a1b1-f7276cedfcae" />


Frontend and Backend servers deployed on Amazon EC2.

---

## Amazon RDS

<img width="1366" height="768" alt="03_rds-database_03" src="https://github.com/user-attachments/assets/b9324198-dcde-48c8-b244-2b7415bb8644" />


MySQL database hosted on Amazon RDS.

---

## Application Load Balancer

<img width="1366" height="768" alt="04_load-balancer-active" src="https://github.com/user-attachments/assets/dbd4d76b-76f9-4d4d-9c3f-ea811451bab5" />


Internet-facing Application Load Balancer.

---

## Target Group Health

<img width="1366" height="685" alt="05_target-group-healthy" src="https://github.com/user-attachments/assets/cb2cc7f7-ebed-4768-80f4-7b201aa29630" />


Healthy target registered with ALB.

---

## Frontend Output

<img width="1366" height="768" alt="06_nginx-homepage" src="https://github.com/user-attachments/assets/d5269289-640a-47d7-8123-86c9d1f7fcfd" />


Nginx web server running successfully.

---

## Architecture Flow

User → ALB → Frontend EC2 (Nginx) → Backend EC2 (Flask) → Amazon RDS (MySQL)

---

## Outcome

Successfully deployed and tested a Multi-Tier Web Application on AWS.
