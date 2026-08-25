# Lab 6 – Scale and Load Balance Your Architecture

## Title

Scale and Load Balance Your Architecture
Author : Kanishka.V   
Reg no : 212224100030
Date : 25/08/2026

---

## Objective

The objective of this lab is to understand how to design a scalable and highly available architecture on AWS using Auto Scaling and Elastic Load Balancing. This experiment focuses on distributing incoming traffic across multiple EC2 instances, automatically scaling resources based on demand, and validating fault tolerance.

---

## Prerequisites

* Basic knowledge of Amazon EC2 and VPC
* Completion of previous labs (IAM, EC2, EBS, Database Server)
* AWS Academy Lab access
* Stable internet connection

---

## Tools Used

* AWS Management Console
* Amazon EC2
* Elastic Load Balancer (ELB / ALB)
* Auto Scaling Groups (ASG)
* Amazon CloudWatch

---

## Tasks Performed

### Task 1: Review Existing Architecture

Students review the existing EC2-based application architecture created in previous experiments.

### Task 2: Create a Launch Template

Students create a launch template that defines the EC2 instance configuration including AMI, instance type, security group, and user data.

### Task 3: Create an Auto Scaling Group

Students create an Auto Scaling Group using the launch template and configure minimum, maximum, and desired instance capacity.

### Task 4: Configure an Application Load Balancer

Students create an Application Load Balancer and configure target groups for routing traffic to EC2 instances.

### Task 5: Register Auto Scaling Group with Load Balancer

Students attach the Auto Scaling Group to the target group of the load balancer.

### Task 6: Configure Scaling Policies

Students configure scaling policies based on CPU utilization using Amazon CloudWatch alarms.

### Task 7: Test Load Balancing and Scaling

Students test the setup by generating traffic and observing automatic scaling and load distribution.

---

## Workflow (To be filled by Student)

1. Review the existing EC2 architecture.
2. Create a Launch Template.
3. Create an Auto Scaling Group.
4. Configure minimum, maximum, and desired instances.
5. Create an Application Load Balancer.
6. Create and configure a Target Group.
7. Attach the Auto Scaling Group to the Target Group.
8. Configure CPU-based scaling policies using CloudWatch.
9. Generate traffic to test the application.
10. Monitor load distribution and automatic scaling.


## Output Screenshots 

<img width="1917" height="1093" alt="Screenshot 2026-08-25 210731" src="https://github.com/user-attachments/assets/0b969ba9-dc83-42fc-a80f-10d4555a67d5" />
<img width="1917" height="1083" alt="Screenshot 2026-08-25 211039" src="https://github.com/user-attachments/assets/4a08e2e0-a2b7-4764-b646-22aa7e15b91f" />
<img width="1917" height="1087" alt="Screenshot 2026-08-25 211459" src="https://github.com/user-attachments/assets/7bfc15b5-3a3e-4e2d-a45d-a6910bce2ca6" />
<img width="1917" height="1092" alt="Screenshot 2026-08-25 212332" src="https://github.com/user-attachments/assets/4802592b-8a09-4376-9027-63319717cb05" />
<img width="1917" height="1087" alt="Screenshot 2026-08-25 215709" src="https://github.com/user-attachments/assets/933a5f5e-9890-4118-992a-e6e9613a2205" />
<img width="1917" height="1083" alt="Screenshot 2026-08-25 213537" src="https://github.com/user-attachments/assets/47abf521-babe-4584-93ff-800fbaaaf962" />



## Result

This experiment demonstrated how to build a scalable and fault-tolerant cloud architecture using Auto Scaling Groups and Elastic Load Balancing. The system automatically adjusted resources based on workload and ensured continuous service availability by distributing traffic across multiple instances.
