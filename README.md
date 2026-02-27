
# EC2 + NGINX + Custom Domain (Cloudflare)

## Overview
This project demonstrates how to deploy a web server on AWS EC2, configure NGINX as a web server, and connect a custom domain through Cloudflare DNS. The goal is to set up a fully functional web server that can serve static content to users through a custom domain.

## What I Learned
- Launching and connecting to an EC2 instance via SSH
- Installing and configuring NGINX on an EC2 instance
- Setting up DNS records (A records) and managing domain settings using Cloudflare
- Troubleshooting and verifying DNS propagation and web server status

## Architecture
The architecture for this project is as follows:

1. **User → DNS (Cloudflare)**: The user’s browser queries the DNS system for the domain name (e.g., infonmohamed.com).
2. **DNS → Public IP (EC2)**: Cloudflare routes the request to the EC2 instance's public IP.
3. **EC2 → NGINX**: The EC2 instance runs NGINX, which serves static web content (HTML files).
4. **NGINX → Web Page**: NGINX serves the web page to the user’s browser.

This flow ensures that the user can access the website hosted on EC2 via a custom domain (infonmohamed.com), utilizing Cloudflare for DNS and traffic management.

## Evidence
- **Screenshots**: All relevant screenshots are stored in the `/screenshots` directory. These include:
  - EC2 instance creation
  - NGINX configuration and status
  - DNS records in Cloudflare
  - Verification that the website is live

- **Step-by-step Notes**: Detailed setup steps and troubleshooting are available in the `/docs/setup_steps.md` file.

You can view the relevant screenshots and follow along with the setup process.

## Quick Verification
To verify that the EC2 instance is up and running:

1. **Check the website** using `curl`:
   ```bash
   curl -I http://infonmohamed.com
   To verify that the EC2 instance is up and running:
systemctl status nginx

# Assignment-Networking-my-ec2-nginx-setup-
EC2 instance setup with NGINX and custom domain

