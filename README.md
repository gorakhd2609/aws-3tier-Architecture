# AWS 3-Tier Web Architecture

## Project Overview

Designed and deployed a scalable and secure 3-Tier Web Architecture on AWS. The application was hosted on Amazon EC2 instances behind an Application Load Balancer, with Amazon RDS used as the database layer. The infrastructure was configured within a custom VPC following security and high-availability best practices.

## Architecture Components

### Presentation Layer
- Application Load Balancer (ALB)
- Public Subnets

### Application Layer
- Amazon EC2 Instances
- Auto Scaling Group
- Private/Public Subnets

### Database Layer
- Amazon RDS
- Private Subnets

## AWS Services Used

- Amazon EC2
- Application Load Balancer (ALB)
- Amazon RDS
- Amazon VPC
- Auto Scaling
- Security Groups
- Internet Gateway
- Route Tables
- CloudWatch

## Key Features

- Highly Available Architecture
- Load Balancing Across Instances
- Auto Scaling for Traffic Handling
- Secure Network Segmentation
- Managed Database Service
- Monitoring and Performance Tracking

## Project Workflow

1. Created a custom VPC.
2. Configured public and private subnets.
3. Launched EC2 instances for the application layer.
4. Configured an Application Load Balancer.
5. Created an Auto Scaling Group.
6. Deployed the web application.
7. Configured Amazon RDS for database connectivity.
8. Applied Security Groups and network rules.
9. Verified application accessibility and failover behavior.

## Architecture Diagram

Add your architecture diagram image here.

## Project Outcome

Successfully deployed a secure, scalable, and highly available web application using AWS cloud services while implementing industry-standard 3-tier architecture principles.

## Skills Demonstrated

- AWS Cloud Infrastructure
- Networking (VPC, Subnets, Route Tables)
- Load Balancing
- Auto Scaling
- Database Management
- Cloud Security
- High Availability Design
