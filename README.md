# AWS Multi-Tier Web Application Deployment

## Project Overview

This project demonstrates a Multi-Tier Web Application deployed on AWS.

### Architecture

![Architecture](screenshots/architecture-diagram.png)

---

## AWS Services Used

- Amazon EC2
- Amazon RDS MySQL
- Application Load Balancer (ALB)
- Security Groups
- VPC

---

## EC2 Instances

![EC2](screenshots/ec2-instances.png)

Frontend and Backend servers deployed on Amazon EC2.

---

## Amazon RDS

![RDS](screenshots/rds-database.png)

MySQL database hosted on Amazon RDS.

---

## Application Load Balancer

![ALB](screenshots/load-balancer-active.png)

Internet-facing Application Load Balancer.

---

## Target Group Health

![Target Group](screenshots/target-group-healthy.png)

Healthy target registered with ALB.

---

## Frontend Output

![Nginx](screenshots/nginx-homepage.png)

Nginx web server running successfully.

---

## Architecture Flow

User → ALB → Frontend EC2 (Nginx) → Backend EC2 (Flask) → Amazon RDS (MySQL)

---

## Outcome

Successfully deployed and tested a Multi-Tier Web Application on AWS.