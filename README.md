# cloud-resume-challenge
AWS Cloud Resume Challenge - Static website hosted on S3 with CloudFront, Route 53, Lambda, and DynamoDB
A personal resume website built and deployed on AWS as part of the 
[Cloud Resume Challenge](https://cloudresumechallenge.dev/).

## 🌐 Live Site
[www.boujeebee.com](https://www.boujeebee.com)

## 🛠️ AWS Services Used
- **S3** - Static website hosting
- **CloudFront** - Content delivery network (CDN)
- **ACM** - SSL/TLS certificate for HTTPS
- **Route 53** - Custom domain DNS management
- **Lambda** - Serverless visitor counter function
- **DynamoDB** - Visitor count database

## 📋 Project Overview
This project is a static resume website hosted entirely on AWS. 
The site is served securely over HTTPS using CloudFront and ACM, 
with a custom domain managed through Route 53. It includes a 
visitor counter powered by Lambda and DynamoDB.

## 🚀 What I Learned
- How to host a static website on AWS S3
- How to set up a CloudFront distribution
- How to configure a custom domain with Route 53
- How to secure a website with an SSL certificate using ACM
- How to build a serverless function with Lambda
- How to store and retrieve data with DynamoDB
