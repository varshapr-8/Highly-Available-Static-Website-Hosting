<h1 align="center">SECURE & SCALABLE STATIC WEBSITE HOSTING ON AWS</h1>

### Solution Architecture & Strategic Design:   
In today’s digital landscape, businesses and individuals require reliable, 
secure, and globally accessible web platforms to establish their online presence. 
Traditional hosting solutions often involve complex infrastructure management and 
higher costs, making them less efficient for static websites. 
This project, “Secure & Scalable Static Website Hosting on AWS”, addresses these 
challenges by leveraging Amazon Web Services to deliver a cost-effective, highly 
available, and secure hosting solution. Using Amazon S3, Route 53, AWS Certificate 
Manager, and Amazon CloudFront, the system provides end-to-end infrastructure for 
hosting static content with custom domain integration, DNS management, and global 
content delivery. 
By implementing SSL/TLS certificates and CloudFront caching policies, the project 
ensures secure communication, compliance with modern standards, and optimized 
performance across regions. The result is a professional-grade static website that 
demonstrates practical skills in cloud infrastructure setup, domain management, and 
performance optimization.

---

### Architecture Components
Storage: Amazon S3 (Simple Storage Service) used for hosting the website’s static assets (HTML, CSS, JS).

Content Delivery: Amazon CloudFront (CDN) configured to cache content at edge locations worldwide to reduce latency.

DNS Management: Amazon Route 53 utilized for domain registration and routing traffic to the CloudFront distribution.

Security: AWS Certificate Manager (ACM) for HTTPS/SSL encryption and S3 Bucket Policies for controlled access.

---

### Technical Implementation Workflow: 
* Import a domain name on AWS 
* Create a hosted zone and manage its DNS records; 
* Create S3 Buckets to host website pages; 
* Configure Route 53 to link the domain name to the website; 
* Create an SSL certificate for the website using AWS Certificate Manager (ACM); 
* Create CloudFront distributions to secure the website in HTTPS.

### Technology Ecosystem: 
*  Amazon S3 – Static website hosting and storage. 
*  Amazon Route 53 – DNS management and domain integration. 
* AWS Certificate Manager (ACM) – SSL/TLS certificate generation. 
* Amazon CloudFront – Content delivery network (CDN) for global distribution.

Technical Documentation (PDF)
For a detailed walkthrough, including screenshots of the AWS Console, step-by-step configurations, and troubleshooting logs, please refer to the full report:

[👉 Click here to view the full Project Documentation (PDF)](AWS_StaticWebsite_Project.pdf)

### Key Performance & Security Milestones
* Successfully deployed a secure, globally accessible static website using AWS 
services. 
* The website is hosted on Amazon S3 with a custom domain 
(varshacloud.online). 
* Route 53 DNS records correctly link the domain to the hosting bucket. 
* SSL/TLS certificate from AWS Certificate Manager ensures encrypted HTTPS 
communication. 
* CloudFront distribution delivers content with low latency and optimized 
performance worldwide.

### Demonstrated practical skills in:
*  Cloud infrastructure setup (S3, Route 53, CloudFront, ACM). 
* Domain integration and DNS management. 
* Security implementation with SSL/TLS. 
* Performance optimization using CDN caching.
