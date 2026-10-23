
# AWS ALB and EC2 High Availability Lab

## Overview
Deploy two Ubuntu EC2 web servers behind an AWS
Application Load Balancer (ALB).

## Technologies
- AWS EC2
- Application Load Balancer
- Ubuntu
- Apache HTTP Server
- Security Groups
- Target Group Health Checks

## Architecture
The ALB routes HTTP requests to healthy EC2 targets.
Each web server displays its hostname and private IP.

## Project Goals
- Deploy web servers across Availability Zones.
- Configure load balancing and health checks.
- Troubleshoot HTTP connectivity.
- Apply AWS security-group best practices.
- Document deployment and cleanup steps.

## Future Improvements
- Provision infrastructure using Terraform.
- Add GitHub Actions validation.
- Configure CloudWatch monitoring and alarms.
