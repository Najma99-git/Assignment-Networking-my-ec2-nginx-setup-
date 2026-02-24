# EC2 + NGINX Setup with Custom Domain

This project demonstrates how to set up an EC2 instance on AWS, install NGINX as a web server, and link a custom domain using Cloudflare. The steps are documented and visualized to make it easy to follow.

## Table of Contents
- [Overview](#overview)
- [Prerequisites](#prerequisites)
- [Steps](#steps)
  - [1. EC2 Setup](#1-ec2-setup)
  - [2. NGINX Setup](#2-nginx-setup)
  - [3. DNS Configuration](#3-dns-configuration)
- [Screenshots](#screenshots)
- [Scripts](#scripts)

## Overview
This repository contains a step-by-step guide to setting up an EC2 instance with NGINX and linking a custom domain via Cloudflare.

## Prerequisites
- AWS account
- Cloudflare account
- Domain name

## Steps

### 1. EC2 Setup
- Launch an EC2 instance.
- Connect to your instance via SSH.
- Install the required software.



### 2. NGINX Setup
- Install NGINX on the EC2 instance.
- Configure NGINX to serve content.

### 3. DNS Configuration
- Use Cloudflare to manage your domain's DNS.
- Set up A records to point to your EC2 instance.

## Screenshots
1. EC2 instance creation
2. NGINX setup on EC2
3. Cloudflare DNS configuration

## Scripts
- `setup-nginx.sh`: A script for automating NGINX setup.
