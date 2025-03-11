# AWS RDS MySQL Lab: Setting Up and Connecting a Database

## Overview
This lab demonstrates how to set up an AWS RDS MySQL instance and connect it to a web application. The process involves configuring security groups, networking, and database connectivity to ensure high availability. 

## Objectives
By completing this lab, I was able to:
- Launch an Amazon RDS DB instance with high availability.
- Configure security groups to allow web server connections.
- Interact with the database through a web application.

## Key Tasks Completed:
1. Created a security group to allow database access from a web server.
  
  ![Security Group](https://github.com/WinnieMadikizella/AWS-Lab-Building-a-DB-Server-and-Connecting-It-to-a-Web-App/blob/main/images/images/DB%20Security%20Group.JPG) 

2. Configured a DB subnet group with multiple availability zones.

  ![Subnet group](https://github.com/WinnieMadikizella/AWS-Lab-Building-a-DB-Server-and-Connecting-It-to-a-Web-App/blob/main/images/images/Subnet%20group.JPG)
  
3. Launched an Amazon RDS MySQL instance with a Multi-AZ setup.

   ![Database Creation](https://github.com/WinnieMadikizella/AWS-Lab-Building-a-DB-Server-and-Connecting-It-to-a-Web-App/blob/main/images/images/Database%20Creation.JPG)

   ![RDS Connectivity Details](https://github.com/WinnieMadikizella/AWS-Lab-Building-a-DB-Server-and-Connecting-It-to-a-Web-App/blob/main/images/images/RDS%20Connectivity%20Details.JPG)
   
5. Connected a web application to the database and verified data persistence.

   ![Database Connection fields](https://github.com/WinnieMadikizella/AWS-Lab-Building-a-DB-Server-and-Connecting-It-to-a-Web-App/blob/main/images/images/Database%20Connection%20fields.JPG)

   ![Address book running successfully](https://github.com/WinnieMadikizella/AWS-Lab-Building-a-DB-Server-and-Connecting-It-to-a-Web-App/blob/main/images/images/Address%20book%20running%20successfully.JPG) 

## Conclusion
This hands-on experience reinforced best practices in cloud database management, security configurations, and scalability in AWS.
