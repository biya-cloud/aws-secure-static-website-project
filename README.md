# AWS Secure Static Website Project

A hands-on AWS project demonstrating secure static website hosting using Amazon S3 and Amazon CloudFront.

## Project Overview

In this project, I built and deployed a static website using Amazon S3 and Amazon CloudFront.

The S3 bucket is kept private, while CloudFront securely accesses the S3 content using Origin Access Control (OAC).

## AWS Services Used

- **Amazon S3** — Stores the static website files
- **Amazon CloudFront** — Provides CDN delivery and HTTPS
- **Origin Access Control (OAC)** — Secures CloudFront access to the private S3 bucket
- **AWS IAM** — Demonstrates least-privilege access
- **AWS Budgets** — Helps monitor AWS spending
- **Amazon CloudWatch** — Provides monitoring and metrics

## Architecture

User
↓
Amazon CloudFront
↓
Origin Access Control (OAC)
↓
Private Amazon S3 Bucket
↓
index.html

## Security

- S3 public access is blocked.
- S3 ACLs are disabled.
- S3 Versioning is enabled.
- CloudFront uses Origin Access Control.
- IAM policy follows the principle of least privilege.
- AWS Budgets is configured for cost monitoring.

## Website

The website is delivered through Amazon CloudFront using HTTPS.

**Live Website:**  
https://d3m574mej2lhk4.cloudfront.net

## What I Practiced

- Creating and configuring an S3 bucket
- Uploading and managing website files
- Configuring CloudFront
- Using Origin Access Control
- Creating an IAM least-privilege policy
- Configuring AWS Budgets
- Viewing CloudFront and CloudWatch monitoring
- Using GitHub to document an AWS project

## Project Outcome

This project gave me practical experience with AWS storage, CDN, security, IAM permissions, monitoring, and cost management.

It also helped me understand how multiple AWS services work together to deliver a secure static website.

## Author

AWS Cloud Learning Project
