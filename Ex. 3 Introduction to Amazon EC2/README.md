# Lab 3 – Introduction to Amazon Elastic Compute Cloud (EC2)

## Author

* **Name**: AMIRTHA VARSHINI.V
* **Register Number**: 212224040021

---

## Objective

The objective of this experiment is to understand the fundamentals of Amazon Elastic Compute Cloud (EC2). This lab focuses on launching and managing a virtual server, understanding instance types and AMIs, connecting to an EC2 instance, monitoring its status, and performing basic instance operations such as start, stop, and terminate.

---

## Prerequisites

* Basic understanding of cloud computing concepts
* AWS account or AWS Academy Lab access
* Web browser with internet connectivity
* Basic knowledge of Linux commands (optional)

---

## Tools Used

* AWS Management Console
* Amazon EC2
* Key Pair
* Security Group
* SSH Client (PuTTY / Terminal)

---

## Tasks Performed

### Task 1: Explore Amazon EC2 Dashboard

Explore the EC2 service dashboard in the AWS Management Console. Observe the different sections such as Instances, AMIs, Instance Types, Key Pairs, Security Groups, and Elastic IPs.

---

### Task 2: Launch an EC2 Instance

Launch a new EC2 instance using Amazon Linux 2 AMI. Select an appropriate instance type (t2.micro) under the free tier. Configure basic settings such as instance name, key pair, and security group.

---

### Task 3: Configure Security Group

Configure a security group to allow inbound access:

* SSH (Port 22) from your IP address
* HTTP (Port 80) from anywhere (0.0.0.0/0)

This security group acts as a firewall for the instance.

---

### Task 4: Connect to EC2 Instance

Connect to the running EC2 instance using SSH. Use the downloaded key pair and connect via terminal or PuTTY.

For Amazon Linux:

```
ssh -i "keyname.pem" ec2-user@<Public-IP>
```

---

### Task 5: Perform Basic Instance Operations

Perform the following operations from the EC2 console:

* Stop the instance
* Start the instance
* Reboot the instance

Observe the state changes of the instance.

---

### Task 6: Monitor EC2 Instance

Monitor the EC2 instance using the Monitoring tab. Observe metrics such as CPU utilization, network in/out, and instance status checks.

---

### Task 7: Terminate EC2 Instance

Terminate the EC2 instance after completing the experiment to avoid unnecessary AWS charges.

---

## Workflow (Student Explanation)

1. Log in to the AWS Management Console and navigate to the EC2 Dashboard to explore sections such as Instances, AMIs, Instance Types, Key Pairs, Security Groups, and Elastic IPs.
2. Launch a new EC2 instance using Amazon Linux 2 AMI, select the t2.micro instance type, configure the instance name, create/select a key pair, and configure the security group.
3. Configure the Security Group to allow inbound SSH (Port 22) from my IP address and HTTP (Port 80) from anywhere (0.0.0.0/0).
4. Connect to the running EC2 instance using SSH with the downloaded key pair and perform basic instance operations such as stop, start, and reboot from the EC2 console.
5. Monitor the EC2 instance using the Monitoring tab to observe performance metrics, and finally terminate the instance after completing the experiment.

---

## Output Screenshots (Attach 3)

### Screenshot 1: EC2 Dashboard / Instance List

<img width="1264" height="655" alt="image" src="https://github.com/user-attachments/assets/61afb658-24cb-40dc-822f-e138c80439da" />


---

### Screenshot 2: SSH Connection to Instance

<img width="1267" height="661" alt="image" src="https://github.com/user-attachments/assets/a208620d-6755-4087-a327-6a1f5b61b4a0" />



---

### Screenshot 3: Instance Monitoring / Status

<img width="1261" height="656" alt="image" src="https://github.com/user-attachments/assets/56558905-2cc0-452d-85ac-f8cf706b2901" />


---

## Result 

This experiment provided hands-on experience with Amazon EC2 by demonstrating how to launch, connect, manage, and monitor a virtual server in AWS. It helped in understanding the concept of Infrastructure as a Service (IaaS) and how compute resources can be provisioned and controlled on demand in the cloud.
