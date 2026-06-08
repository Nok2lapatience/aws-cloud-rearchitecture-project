# AWS Cloud Re-Architecture Project

## Overview

This project demonstrates the re-architecture of a traditional multi-tier web application into a scalable, highly available, cloud-native solution on AWS.

The objective was to reduce operational overhead, improve scalability, automate deployments, and increase business continuity using managed AWS services.

---

## Architecture Components

### Compute Layer

* AWS Elastic Beanstalk
* Auto Scaling
* EC2 Instances

### Database Layer

* Amazon RDS (MySQL)

### Caching Layer

* Amazon ElastiCache (Memcached)

### Messaging Layer

* Amazon MQ (RabbitMQ)

### Storage Layer

* Amazon S3

### Networking & Security

* VPC
* Security Groups
* Application Load Balancer
* SSL/TLS Certificates

### DNS & Content Delivery

* Amazon Route 53
* Amazon CloudFront

---

## Architecture Flow

Users → CloudFront → Route53 → Application Load Balancer → Elastic Beanstalk → RDS

Elastic Beanstalk → Amazon MQ

Elastic Beanstalk → ElastiCache

Elastic Beanstalk → S3

---

## AWS Services Used

| Service           | Purpose                |
| ----------------- | ---------------------- |
| Elastic Beanstalk | Application Deployment |
| EC2               | Compute Resources      |
| RDS MySQL         | Managed Database       |
| ElastiCache       | Application Caching    |
| Amazon MQ         | Message Broker         |
| Route 53          | DNS Management         |
| CloudFront        | Content Delivery       |
| ALB               | Load Balancing         |
| ACM               | SSL Certificates       |
| S3                | Artifact Storage       |

---

## Key Achievements

* Implemented highly available architecture
* Automated application deployments
* Improved scalability using Auto Scaling
* Reduced infrastructure management overhead
* Implemented secure HTTPS communication
* Improved application performance through caching
* Enabled reliable messaging between services

---

## Skills Demonstrated

* AWS Architecture Design
* Cloud Migration
* Infrastructure Modernization
* Elastic Beanstalk Deployments
* Route 53 DNS Management
* CloudFront Configuration
* RDS Administration
* Amazon MQ Integration
* Load Balancer Configuration
* SSL/TLS Implementation
* Troubleshooting and Monitoring

---

## Outcome

The application was successfully transformed into a cloud-native architecture capable of supporting higher availability, improved performance, and simplified operational management.

