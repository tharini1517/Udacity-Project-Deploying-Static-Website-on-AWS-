Udacity Project: Deploying a Static Website on AWS

This project showcases the process of deploying a static website on Amazon Web Services (AWS) by leveraging S3 (Simple Storage Service) for hosting, CloudFront for content distribution, and IAM (Identity and Access Management) for secure access control. It demonstrates hands-on experience in cloud architecture, web hosting, and AWS service integration as part of my Udacity Cloud DevOps Engineer Nanodegree.

🚀 AWS Services Used 🗂️ Amazon S3 (Simple Storage Service)

Used to host the static website files including HTML, CSS, JavaScript, and image assets.

Enabled Static Website Hosting on the S3 bucket, making the site accessible through a public endpoint.

Configured the bucket policy to allow public read access for website content while keeping other permissions restricted.

Verified accessibility via the S3 website endpoint.

🌍 Amazon CloudFront (Content Delivery Network)

Configured a CloudFront distribution to deliver the website globally with low latency and high transfer speed.

Set the S3 bucket (website endpoint) as the origin for CloudFront.

Implemented HTTP to HTTPS redirection for secure communication.

Tested the CloudFront domain URL to ensure successful content delivery and caching.

🔐 AWS IAM (Identity and Access Management)

Created and managed IAM policies to control access to the S3 bucket.

Used IAM roles and permissions to grant CloudFront access to the S3 origin securely.

Ensured best security practices by disabling public write access and managing object access through policies.

🌐 Hosted URLs

S3 Website Endpoint: http://my-984728487926-bucket.s3-website-us-east-1.amazonaws.com

CloudFront Distribution: https://d1c26g0h4bdk4g.cloudfront.net/

The CloudFront URL provides global access to the website via AWS edge locations, ensuring fast load times for users worldwide.

🧩 Steps Implemented

Created an S3 Bucket and named it using the AWS account ID for uniqueness.

Uploaded website files (HTML, CSS, JS, images) to the S3 bucket.

Enabled Static Website Hosting on the bucket and noted the endpoint.

Configured Bucket Policy to allow public read access for website content.

Created a CloudFront Distribution with the S3 website endpoint as the origin.

Linked CloudFront with IAM permissions for secure access.

Tested both endpoints (S3 and CloudFront) to ensure proper functioning and availability.

Validated Deployment using web browser tests and AWS Console verification.

📸 Project Deliverables (Screenshots)

S3 Bucket Creation – Proof of successful bucket setup.

File Upload to S3 – Verification of website files added to the bucket.

Bucket Policy Configuration – JSON policy granting read permissions.

IAM Role/Policy Setup – Security configuration for controlled access.

S3 Static Website Configuration – Screenshot of hosting settings enabled.

CloudFront Distribution Setup – Deployed distribution with status “Enabled.”

Live Website Preview – Final running website accessible through CloudFront.

💡 Project Outcome

By completing this project, I successfully:

Hosted a fully functional static website using AWS services.

Integrated CloudFront CDN to improve performance and reliability.

Applied IAM-based access control to secure cloud resources.

Gained practical understanding of cloud deployment workflows, policy management, and content delivery architecture in AWS.
