
# EC2 + NGINX + Custom Domain (Cloudflare)

## Overview
I deployed a web server on AWS EC2, installed NGINX, and connected a custom domain using Cloudflare DNS.

## What I Learned
- Launching and connecting to an EC2 instance (SSH)
- Installing and verifying NGINX
- DNS records and Cloudflare configuration (A records, propagation)
- Troubleshooting access issues

## Architecture
User → DNS (Cloudflare) → Public IP (EC2) → NGINX → Web Page

## Evidence
- Screenshots: see /screenshots
- Step-by-step notes: see /docs and /setup

## Quick Verification
- `curl -I http://infonmohamed.com/`
- `systemctl status nginx`
=======
# Assignment-Networking-my-ec2-nginx-setup-
EC2 instance setup with NGINX and custom domain

