# Pet-Shop-AWS-Project
Hosting website on AWS. Beginner level project.

🌐 AWS Static Website Hosting Project
📌 Project Overview

This project demonstrates how to host a static website (HTML, CSS, JS files) using Amazon Web Services (AWS).
By leveraging AWS services like S3 (Simple Storage Service) and CloudFront, you can build a scalable, secure, and cost-effective hosting solution.

It is an ideal beginner project for learning AWS cloud fundamentals and understanding how modern web hosting works without traditional servers.

🛠 Services Used

Amazon S3 → Stores and serves static website files.
IAM → Create user with permission
AWS CLI → Command-line tool for uploading and managing files easily.
🚀 Features

Host HTML, CSS, JS, and media files.
Publicly accessible website endpoint via AWS.
Low-cost and serverless (uses AWS Free Tier).
📂 Project Structure

pet-shop/
-- index.html # Main homepage -- style.css # Stylesheet -- script.js # JavaScript

🔑 Steps to Recreate

Create an S3 Bucket

Must be a unique name (e.g., my-aws-static-site).
Enable Static Website Hosting in Properties.
Upload Files

Upload index.html, CSS, and JS to the bucket.
Ensure permissions allow public read access.
Set Bucket Policy

Public Access → Off
Under the bucket → Properties → Static web hosting → Enable → index.html
Dashboard → Go into the bucket → Permission → Off
Permission → Edit object ownership → Enabled
Objects → Select folder/file → Actions → Make public using ACL
💻 Access Website

Find the S3 Website Endpoint in bucket properties.

Example:

http://pet-shop-bucket05.s3-website.ap-south-1.amazonaws.com image

(Optional) Add CloudFront for HTTPS + CDN Create CloudFront distribution.

Use S3 bucket as origin. Attach an SSL certificate via AWS Certificate Manager.

📈 Future Enhancements

Automate deployment using GitHub Actions.
Add custom domain with Route 53.
Integrate CI/CD pipeline for auto-updates.
