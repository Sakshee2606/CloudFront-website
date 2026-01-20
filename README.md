# Static website hosting with AWS CloudFront by Sakshee Jain

This project demonstrates how to host a static website using:
- Amazon s3 (private bucket)
- Amazon CloudFront (CDN)
- AWS free tier plan

## Features
- Bucket created using Amazon s3
- HTTPS enables via CloudFront
- Secured access using Origin Access Control (OAC)
- Static Assets (HTML, images)

### Architecture

User-> CloudFront-> s3

#### Procedure to deploy
- Upload files in the Amazon s3 bucket
- Create a CloudFront Distribution
- Attach bucket policy for Origin Access Control (OAC)

- Access the website via CloudFront domain
