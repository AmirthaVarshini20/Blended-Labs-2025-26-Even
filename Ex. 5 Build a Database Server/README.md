# Lab 5 – Build a Database Server (AWS)

## Author

* **Name**: AMIRTHA VARSHINI V
* **Register Number**: 212224040021

---

## Objective

The objective of this experiment is to understand how to deploy and configure a database server in AWS. This lab focuses on launching an EC2 instance, installing a database management system (DBMS), configuring basic database settings, creating a sample database, and validating connectivity to the database server.

---

## Prerequisites

* Basic understanding of cloud computing concepts
* AWS account or AWS Academy Lab access
* An existing VPC and EC2 knowledge (from previous labs)
* Basic knowledge of Linux commands and SQL

---

## Tools Used

* AWS Management Console
* Amazon EC2
* Security Groups
* SSH Client (Terminal / PuTTY)
* MySQL / MariaDB / PostgreSQL (any one)

---

## Tasks Performed

### Task 1: Launch EC2 Instance for Database Server

Launch a new EC2 instance using Amazon Linux 2 AMI. Select an appropriate instance type and configure key pair and security group.

---

### Task 2: Configure Security Group for Database Access

Modify the security group to allow:

* SSH (Port 22) for remote access
* Database port (e.g., MySQL – 3306 or PostgreSQL – 5432)

---

### Task 3: Connect to EC2 Instance

Connect to the EC2 instance using SSH from your local machine.

---

### Task 4: Install Database Server

Install a database server software such as MySQL, MariaDB, or PostgreSQL on the EC2 instance using package manager commands.

---

### Task 5: Start and Configure Database Service

Start the database service and configure basic settings such as root password and user privileges.

---

### Task 6: Create a Sample Database

Create a sample database and a table inside it. Insert a few records into the table.

---

### Task 7: Test Database Connectivity

Test the database server by connecting to it locally or remotely and performing basic SQL queries.

---

## Workflow (Student Explanation)

1. Create a Security Group for RDS
2. Create a DB Subnet Group
3. Launch an RDS MySQL DB Instance
4. Configure Connectivity and Security
5. Connect Web App to Database and Test

---

## Output Screenshots (Attach 3)

### Screenshot 1: EC2 Instance for Database Server


<img width="1363" height="766" alt="Screenshot 2026-03-18 154017" src="https://github.com/user-attachments/assets/cdd5c97d-3608-4cb3-80cd-8166c1711193" />



---

### Screenshot 2: Database Service Running


<img width="1356" height="767" alt="Screenshot 2026-03-18 161157" src="https://github.com/user-attachments/assets/c7be480e-3701-4758-84ef-effc047556a7" />


---

### Screenshot 3: Sample Database and Table


![WhatsApp Image 2026-03-19 at 9 32 07 AM](https://github.com/user-attachments/assets/cb32ba4e-9259-4872-843f-74cfdd2f3e4c)


---

## Result

This experiment demonstrated how to build a database server in AWS using an EC2 instance. By installing and configuring a DBMS, creating a sample database, and testing connectivity, the fundamentals of hosting and managing a cloud-based database server were understood.
