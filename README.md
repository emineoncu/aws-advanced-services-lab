
# AWS Advanced Services Lab

Hands-on AWS project simulating real-world Cloud Support tasks involving advanced services such as DNS management, messaging systems, and data analytics.

Route53, SQS, SNS, and data processing using AWS tools.

---

## Overview
This project simulates a real-world event-driven architecture where SNS publishes events and SQS processes them asynchronously.

It demonstrates advanced AWS cloud support skills including DNS routing with Route53, messaging systems using SNS and SQS, and data querying with Athena.

---

## Architecture

- Route53 → routes traffic to application endpoints  
- SNS → publishes messages to subscribers  
- SQS → receives and stores messages for processing  
- Athena → queries and analyzes data stored in S3  
---
## What I Built
- Configured Route53 hosted zones and DNS routing
- Created SQS queue for message processing
- Set up SNS topic for notifications
- Connected SNS to SQS for message delivery
- Queried data using Athena from S3
- Tested message flow between services

---

## AWS Services Used
- Route53
- SQS
- SNS
- Athena

---

## Key Cloud Support Skills Demonstrated
- DNS configuration and domain routing
- Messaging systems and asynchronous communication
- Data querying and analysis
- Understanding of distributed cloud services
- Troubleshooting message delivery issues

---

## Screenshots

### Route53 DNS Configuration
<img width="1357" height="582" alt="image" src="https://github.com/user-attachments/assets/ec89e34c-2abe-4a96-a8b0-175092bbae79" />

### SQS Queue
<img width="1676" height="863" alt="image" src="https://github.com/user-attachments/assets/603b921f-b0df-4b64-a04d-d1d759cbd605" />

### SNS Topic
<img width="1671" height="801" alt="image" src="https://github.com/user-attachments/assets/de6047cb-54a7-47be-8886-70507da00927" />

### Athena Query Results
<img width="508" height="589" alt="image" src="https://github.com/user-attachments/assets/3a5acf7c-1e50-48d6-8459-5ca4fbdba8fe" />

---

## Troubleshooting & Lessons Learned
- Fixed DNS resolution issues in Route53
- Resolved message delivery failures between SNS and SQS
- Learned how to query structured data using Athena
- Understood how distributed services communicate in AWS

## Project Documentation

- [Route53 Configuration](https://github.com/user-attachments/files/26069901/aws-route53-global-infra.pdf)
- [Data Analytics](https://github.com/user-attachments/files/26069909/aws-data-analytics-athena.pdf)
  
- [Messaging Setup](https://github.com/user-attachments/files/26069912/aws-messaging-sqs-sns.pdf)
  
