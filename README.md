# AWS S3 + CloudFront Static Website Hosting
Built and deployed a static website using Amazon S3 and CloudFront for secure, scalable, and high-performance content delivery.


**Project Overview**
This project demonstrates how to host a static website using Amazon S3 and deliver content securely through Amazon CloudFront.
The website files (HTML, CSS, and JavaScript) are stored in an S3 bucket, while CloudFront is used as a Content Delivery Network (CDN) to provide faster content delivery, HTTPS support, and secure access to the website.
________________________________________
**Architecture**
User
  ↓
CloudFront
  ↓
Amazon S3 Bucket
________________________________________
**AWS Services Used**
•	Amazon S3
•	Amazon CloudFront
•	Origin Access Control (OAC)
•	AWS IAM
________________________________________
**Features**
•	Static website hosting using Amazon S3
•	Global content delivery using CloudFront
•	Secure access with Origin Access Control (OAC)
•	HTTPS support through CloudFront
•	Improved website performance using CDN caching
•	Private S3 bucket access through CloudFront
________________________________________
**Project Steps**
1. Created an Amazon S3 Bucket
•	Created an S3 bucket to store website files.
•	Uploaded HTML, CSS, and JavaScript files.
2. Enabled Static Website Hosting
•	Configured S3 bucket for static website hosting.
•	Defined the index document as index.html.
3. Created a CloudFront Distribution
•	Created a CloudFront distribution.
•	Connected the S3 bucket as the origin.
4. Configured Origin Access Control (OAC)
•	Created and attached an Origin Access Control.
•	Allowed CloudFront to securely access the S3 bucket.
5. Updated Bucket Policy
•	Added permissions allowing CloudFront to access S3 objects.
•	Restricted direct public access to bucket content.
6. Tested Website Access
•	Verified website accessibility through the CloudFront URL.
•	Confirmed content delivery through CloudFront.
________________________________________
**Project Structure**
aws-s3-cloudfront-static-website/
│
├── index.html
├── style.css
├── script.js
├── screenshots/
│   ├── s3-bucket.png
│   ├── cloudfront-distribution.png
│   └── website-output.png
│
└── README.md
________________________________________
**Skills Learned**
•	Amazon S3 Bucket Management
•	Static Website Hosting
•	CloudFront CDN Configuration
•	Origin Access Control (OAC)
•	Bucket Policy Management
•	Content Delivery Networks (CDN)
•	AWS Security Best Practices
________________________________________
**Challenges Faced**
•	Troubleshooting S3 object access permissions.
•	Configuring bucket policies for CloudFront access.
•	Resolving CloudFront “Access Denied” errors.
•	Understanding OAC and secure S3 access.
________________________________________
**Outcome**
Successfully hosted a static website using Amazon S3 and Amazon CloudFront with secure access configuration and global content delivery.
________________________________________
**Author**
Ekanath Anehosur
Cloud & DevOps Enthusiast
