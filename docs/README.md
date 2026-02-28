setup-guide.md

# EC2, NGINX, and Cloudflare Setup Guide

This document provides detailed steps for setting up the EC2 instance, installing NGINX, and configuring Cloudflare DNS.

## 1. Launch EC2 Instance
Instructions for launching the EC2 instance will go here.
1. Go to the EC2 Dashboard in AWS.
2. Click on "Launch Instance".
3. Select the **Amazon Linux 2 AMI** and choose **t2.micro** as the instance type.
4. Configure security groups to allow **SSH (port 22)** and **HTTP (port 80)**.
5. Launch the instance and connect via SSH using the following command:
   ```bash
    ssh -i "path/to/tango-98.pem" ec2-user@16.171.17.175
