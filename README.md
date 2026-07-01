# AWS-Cloud-Infrastructure-Project

## Overview

This repository contains my Cloud Computing course project completed at the German International University (GIU). The project demonstrates the design and deployment of a cloud-based web application using Amazon Web Services (AWS). It covers networking, compute resources, storage, database integration, monitoring, and scalable cloud infrastructure.

The project was implemented using multiple AWS services to create a secure and functional cloud environment for a PHP web application connected to a MySQL database.

---

## Project Objectives

The main objectives of this project were to:

- Design a secure cloud network using AWS.
- Deploy a web application on Amazon EC2.
- Configure cloud storage using Amazon S3.
- Integrate a MySQL database hosted on Amazon RDS.
- Implement Auto Scaling and monitoring using Amazon CloudWatch.
- Gain practical experience with core AWS cloud services.

---

## AWS Services Used

- Amazon EC2
- Amazon VPC
- Amazon RDS
- Amazon S3
- Amazon CloudWatch
- Auto Scaling
- Launch Templates
- Internet Gateway
- Route Tables
- Public and Private Subnets

---

## Project Implementation

The project includes the following tasks:

- Created a Virtual Private Cloud (VPC).
- Configured two public subnets and one private subnet.
- Created and associated route tables.
- Configured an Internet Gateway for public access.
- Created an EC2 Launch Template.
- Launched an EC2 instance using the template.
- Created and configured an Amazon RDS database.
- Created an Amazon S3 bucket to host static assets.
- Configured access permissions for the S3 bucket.
- Developed a PHP web application connected to the RDS database.
- Configured Auto Scaling.
- Configured CloudWatch monitoring and CPU utilization alerts.

---

## Web Application

The deployed application was developed using PHP and includes the following components:

- User registration
- User sign-in
- Database connectivity
- User validation
- Static assets served from Amazon S3

The application consists of:

- `index.php`
- `add_users.php`
- `check_signin.php`

---

## Database

The project uses Amazon RDS to host a MySQL database.

The implementation includes:

- Creation of the `users_db` database
- Creation of the `users` table
- Insertion of sample records
- Connection between the PHP application and the database

---

## Monitoring

Amazon CloudWatch was configured to provide basic monitoring of the deployed EC2 instance and generate alerts based on CPU utilization.

---

## Documentation

The complete project documentation, including implementation steps and screenshots, is available in the following file:

- `AWS_CLOUD_PROJECT.pdf`

---

## Technologies Used

- Amazon Web Services (AWS)
- PHP
- MySQL
- Amazon EC2
- Amazon RDS
- Amazon S3
- Amazon VPC
- Amazon CloudWatch

---

## Learning Outcomes

This project provided practical experience in:

- Cloud infrastructure design
- AWS networking
- Virtual machine deployment
- Database integration
- Cloud storage
- Infrastructure monitoring
- Scalable cloud architecture
- Web application deployment

---

## Author

**Maryam Nasser**

Business Informatics Student

German International University (GIU)
