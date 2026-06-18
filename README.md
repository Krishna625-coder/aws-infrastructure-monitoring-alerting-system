# AWS Infrastructure Monitoring & Alerting System

## Project Overview
Built a real-time infrastructure monitoring and alerting solution using AWS services.

## Services Used
- Amazon EC2
- Amazon CloudWatch
- Amazon SNS
- Application Insights
- Ubuntu Linux

## Architecture

EC2 Instance
↓
CloudWatch Alarm
↓
Amazon SNS
↓
Email Notification

## Implementation Steps

1. Launched EC2 Ubuntu Instance
2. Configured CloudWatch CPU Utilization Alarm
3. Created SNS Topic and Email Subscription
4. Connected CloudWatch Alarm with SNS Topic
5. Generated CPU Load using Stress Tool
6. Received Email Alert Notification

## Commands Used

```bash
sudo apt update
sudo apt install stress -y
stress --cpu 2 --timeout 300
