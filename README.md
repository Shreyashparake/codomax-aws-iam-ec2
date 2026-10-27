
# Codomax Internship — Module 2: AWS IAM & EC2

## Project Overview
Deployed a static website on an Ubuntu EC2 instance using Apache HTTP Server.

## AWS Services
- Amazon EC2 — virtual server hosting
- AWS IAM — identity and access management
- Amazon VPC — network environment
- EC2 Security Groups — inbound traffic control

## Architecture

Visitor's Browser
      |
      | HTTP (Port 80)
      v
EC2 Security Group
      |
      v
Ubuntu EC2 Instance
      |
      v
Apache Web Server
      |
      v
index.html

## Implementation
1. Launched an Ubuntu EC2 instance in ap-south-1.
2. Configured a key pair and security group.
3. Allowed HTTP access on port 80.
4. Connected to the instance.
5. Installed and enabled Apache.
6. Deployed a static HTML page.
7. Verified Apache and tested the website using the public IPv4 address.

## Website
Live URL: http://13.239.138.135/

## Security Notes
- SSH access should be restricted to the administrator's IP.
- Root access keys should not be created.
- IAM permissions should follow least privilege.
- Do not commit private keys, passwords, or AWS credentials.

## Evidence
See the screenshots/ folder for deployment evidence.

## Technologies
AWS EC2 | Ubuntu | Apache | HTML | AWS IAM

## Internship
Codomax — Module 2: AWS IAM & EC2
