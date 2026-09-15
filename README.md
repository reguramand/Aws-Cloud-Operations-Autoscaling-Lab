# AWS Cloud Operations & Auto Scaling Lab

## Overview

This project demonstrates a production-style AWS environment using:

* Application Load Balancer (ALB)
* EC2 Auto Scaling Group (ASG)
* CloudWatch Alarms
* Amazon SNS
* AWS Systems Manager (SSM)

## Objective

Automatically scale EC2 instances when CPU utilization exceeds 70%, notify administrators using SNS, and validate traffic distribution through an Application Load Balancer.

## AWS Services Used

* Amazon EC2
* Application Load Balancer
* Target Groups
* Auto Scaling Groups
* Launch Templates
* CloudWatch
* Amazon SNS
* AWS Systems Manager
* IAM

## Results

* CloudWatch alarm triggered successfully
* SNS email notification received
* Auto Scaling Group increased capacity automatically
* New EC2 instance launched and became healthy
* Session Manager access validated
* ALB traffic verified on newly launched instance

## Status

✅ Completed and Tested
