# Lab 6 – Scale and Load Balance Your Architecture

## Title

Scale and Load Balance Your Architecture
Author : NAVEEN KUMAR E
Reg no : 212224230181
Date : 18.3.26

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

1.Review Existing Architecture – Examine the previously created Amazon EC2 application setup and understand how the current infrastructure works. 

2.Create Launch Template – Configure a launch template specifying the AMI, instance type, security group, and user data for EC2 instances. 

3.Set Up Auto Scaling Group – Create an Auto Scaling Group using the launch template and define the minimum, maximum, and desired instance capacity. 

4.Configure Application Load Balancer – Set up an AWS Application Load Balancer and create target groups to distribute incoming traffic across EC2 instances. 

5.Attach and Test Scaling – Connect the Auto Scaling Group to the load balancer target group, configure CPU-based scaling policies using Amazon CloudWatch, and test by generating traffic to observe load balancing and automatic scaling.



---

## Output Screenshots 
<img width="1919" height="984" alt="Screenshot 2026-03-18 134022" src="https://github.com/user-attachments/assets/822a7bf1-744d-487d-b901-d04f3aac21a5" />

<img width="1919" height="976" alt="Screenshot 2026-03-18 134543" src="https://github.com/user-attachments/assets/6198b9a1-e580-4617-a28c-f7984576bd8b" />

<img width="1919" height="901" alt="Screenshot 2026-03-18 135730" src="https://github.com/user-attachments/assets/535cdc38-8452-45b6-acc8-7a6a1af31df7" />

<img width="1754" height="822" alt="Screenshot 2026-03-18 140000" src="https://github.com/user-attachments/assets/a323a93d-03c2-4605-b09b-2b8446a866a9" />

---


## Result

This experiment demonstrated how to build a scalable and fault-tolerant cloud architecture using Auto Scaling Groups and Elastic Load Balancing. The system automatically adjusted resources based on workload and ensured continuous service availability by distributing traffic across multiple instances.
