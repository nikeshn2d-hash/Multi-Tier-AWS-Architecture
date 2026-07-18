# AWS-Multi-Tier-E-Commerce-Web-Application

## Overview

This project demonstrates the deployment of a highly available, secure, and scalable multi-tier web application architecture on AWS.

The infrastructure includes:

- Amazon VPC
- Public and Private Subnets
- Internet Gateway
- NAT Gateway
- Application Load Balancer
- EC2 Auto Scaling Group
- Amazon RDS (MySQL)
- IAM Roles
- Security Groups
- Amazon CloudWatch Monitoring

## Architecture
<img width="1536" height="1024" alt="Architecture" src="https://github.com/user-attachments/assets/82a94e7f-b726-4cc9-b0a3-dcef39eeb612" />

## AWS Services Used

- Amazon VPC
- EC2
- ALB
- Auto Scaling
- Amazon RDS
- IAM
- CloudWatch
- Security Groups
- Route Tables
- NAT Gateway

## Deployment Steps

- Created a custom VPC
- Created public and private subnets
- Configured Internet Gateway
- Configured NAT Gateway
- Created Security Groups
- Launched EC2 instances
- Created Target Group
- Created Application Load Balancer
- Configured Auto Scaling Group
- Created Amazon RDS
- Configured CloudWatch
- Tested high availability

## Security

- Database deployed in a private subnet
- Security Groups configured using least privilege
- IAM Roles attached to EC2
- Internet access only through ALB
