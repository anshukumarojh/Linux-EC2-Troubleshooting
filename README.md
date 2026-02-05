# Linux & EC2 Troubleshooting + Monitoring (AWS)

## Overview
This project demonstrates real-world Linux and AWS EC2 troubleshooting scenarios commonly faced in cloud support roles. The goal is to identify issues, analyze logs, and resolve problems while maintaining system availability.

## Technologies Used
- AWS EC2 (Amazon Linux 2)
- Linux
- Apache (httpd)
- AWS CloudWatch

## Project Architecture
User → Internet → Security Group → EC2 (Amazon Linux) → Apache Web Server

## Troubleshooting Scenarios

### 1. Website Down (Apache Service Stopped)
- Identified service failure using `systemctl`
- Restarted Apache service

### 2. Port Access Issue
- Removed HTTP (port 80) rule from security group
- Diagnosed connectivity issue and restored access

### 3. Permission Issue
- Simulated permission errors on `/var/www/html`
- Fixed using correct Linux permissions

### 4. Disk Full Issue
- Created large temporary files to simulate disk exhaustion
- Analyzed disk usage using `df -h`
- Cleaned up unused files

### 5. Log Analysis
- Analyzed Apache error logs for root cause identification

## Monitoring
- Enabled EC2 detailed monitoring
- Configured CloudWatch alarm for CPU utilization

## Key Learnings
- Linux troubleshooting and log analysis
## Screenshots

<img width="1919" height="1198" alt="Ec-2" src="https://github.com/user-attachments/assets/cd72fa2f-0826-495a-81e4-6a2737ad1237" />
<img width="1912" height="1194" alt="Apache2" src="https://github.com/user-attachments/assets/e43658fb-fb2a-40c5-8759-1ae1b76976e2" />
