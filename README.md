# Grow-Tutors
# AWS Static Business Website

## 1. Business Problem

Grow Tutors requires an affordable and reliable
website to provide information about its tutoring services.

The business does not want to maintain physical servers.

## 2. Proposed Solution


A static cloud-hosted website demonstrating the use of
Amazon S3 and Amazon CloudFront.

The solution allows the business to host its website files
in AWS without managing a traditional web server.

## AWS Services

- Amazon S3
- Amazon CloudFront
- Amazon CloudWatch
- AWS Budgets

## Architecture

User
 ↓
CloudFront
 ↓
S3
 ↓
Website

## Monitoring

CloudWatch is used to monitor CloudFront requests
and error rates.

## Cost Monitoring

AWS Budgets is used to monitor AWS spending.

## What I Learned

- Hosting a static website using S3
- Configuring CloudFront
- Understanding origins
- CloudFront caching
- Cache invalidation
- Monitoring CloudFront using CloudWatch
- Troubleshooting a 504 Gateway Timeout
- Monitoring AWS costs
