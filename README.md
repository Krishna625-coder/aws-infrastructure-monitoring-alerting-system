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
stress --cpu 2 --timeout 300<img width="1366" height="728" alt="10" src="https://github.com/user-attachments/assets/31f69c6b-86ff-41a0-8f56-7483965f4fa0" />
<img width="1366" height="728" alt="9" src="https://github.com/user-attachments/assets/b8c73222-a886-41eb-a50f-7ca540f5ba20" />
<img width="1366" height="728" alt="8" src="https://github.com/user-attachments/assets/0d4877b4-10ac-4a82-b68b-49a725b17510" />
<img width="1366" height="728" alt="7" src="https://github.com/user-attachments/assets/76906f93-f3e6-4599-9b5c-4fce81f6654d" />
<img width="1366" height="728" alt="6" src="https://github.com/user-attachments/assets/5012c97e-baed-4c55-9a26-aa06b083e254" />
<img width="1366" height="728" alt="5" src="https://github.com/user-attachments/assets/6828d905-915e-409a-9850-9db6a273a8ee" />
<img width="1366" height="728" alt="4" src="https://github.com/user-attachments/assets/1686a6ee-da0c-458a-97df-1731056b098e" />
<img width="1366" height="728" alt="3" src="https://github.com/user-attachments/assets/46fdb37b-a56e-4d76-a06c-5b811381f42b" />
<img width="1366" height="728" alt="2" src="https://github.com/user-attachments/assets/1ec82e9f-b03e-4e89-abbc-ceb9b2939c40" />
<img width="1366" height="728" alt="1" src="https://github.com/user-attachments/assets/73de0c3c-3740-441d-a7a6-40cedc123626" />
