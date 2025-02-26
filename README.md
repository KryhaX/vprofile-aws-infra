# DevOps Project - AWS Infrastructure for vProfile Application  

## Overview  
This project is an implementation of the **vProfile** application infrastructure, primarily focused on setting up and configuring all components on **AWS**. The infrastructure was designed to support a web application using various AWS services and best DevOps practices.  

## Infrastructure Setup  

![image](https://github.com/user-attachments/assets/9739f540-f298-4e55-95d3-3ebf58b1658a)
The infrastructure was built using AWS services and includes the following components:  
- **Domain Management:** Configured a custom domain `vprofileapp.krystianwierciak.pl` using **GoDaddy DNS**.  
- **SSL Certificate:** Integrated **AWS Certificate Manager** to secure HTTPS connections.  
- **Load Balancer:** Deployed an **Application Load Balancer** to distribute traffic efficiently.  
- **Compute Instances:** Used **AWS EC2 Instances** for running Apache Tomcat, MySQL, RabbitMQ, and Memcached.  
- **Auto Scaling:** Configured **AWS Auto Scaling** to handle dynamic workload adjustments.  
- **Networking & Security:** Applied **Security Groups** and **VPC settings** to secure traffic flow.  
- **Storage & DNS:** Integrated **Amazon S3** for static content storage and **Amazon Route 53** for internal DNS resolution.  

## Reference Project  
The infrastructure setup was based on the **vProfile Project**: [hkhcoder/vprofile-project](https://github.com/hkhcoder/vprofile-project).  
However, my primary focus was on deploying and configuring the entire AWS infrastructure to support the application under my custom domain.  

## Status  
Due to AWS cost considerations, the project has been removed from AWS. However, the entire source code and configurations remain available, making it fully deployable whenever needed.  

## Future Improvements  
- Implementing **Infrastructure as Code (IaC)** using **Terraform** or **AWS CloudFormation**.    


# Prerequisites
#
- JDK 11 
- Maven 3 
- MySQL 8

# Technologies 
- Spring MVC
- Spring Security
- Spring Data JPA
- Maven
- JSP
- Tomcat
- MySQL
- Memcached
- Rabbitmq
- ElasticSearch
# Database
Here,we used Mysql DB 
sql dump file:
- /src/main/resources/db_backup.sql
- db_backup.sql file is a mysql dump file.we have to import this dump to mysql db server
- > mysql -u <user_name> -p accounts < db_backup.sql


