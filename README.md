           AWS EC2 Web Server Project
           📌 Project Overview
This project demonstrates how I launched and configured an AWS EC2 instance to host a live website using Linux and a web server.
               🛠 Technologies Used
        AWS EC2
        Ubuntu Linux
        Security Groups
        Apache/Nginx
        SSH
        GitHub
              
              📂 Project Steps

 Launch EC2 Instance
Logged into AWS Console
Selected Ubuntu AMI
Chose t2.micro instance
Created key pair
Configured security group

 Configure Security Group
Allowed:
SSH (Port 22)
HTTP (Port 80)
HTTPS (Port 443)

 Connect to EC2
Used SSH to connect:

Install Web Server
For Apache:
Bash
sudo yum update -y
sudo yum install httpd -y
Deploy Website
Added HTML files
Restarted web server
Accessed website using EC2 public IP
📸 Screenshots
EC2 Instance Running
(Add image here)
Security Group Configuration
(Add image here)
Live Website
(Add image here)
✅ Outcome
Successfully deployed a live website on an AWS EC2 instance accessible through a browser.
📚 Lessons Learned
How EC2 works
Linux server management
Security group configuration
Hosting websites in AWS
