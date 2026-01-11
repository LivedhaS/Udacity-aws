## Static Website Hosting on AWS

Project Overview:
This project demonstrates how to host a static website on Amazon Web Services (AWS) using S3 and CloudFront. The website consists only of HTML, CSS, and JavaScript files and does not require any server-side processing.

AWS Services Used:

* Amazon S3 (Simple Storage Service)
* Amazon CloudFront
* AWS IAM (for bucket access policy)

Bucket Details:
Bucket Name:
my-asiazgje3n7of3rq2fij-bucket

Region:
us-east-1 (N. Virginia)

Static Website Hosting:
Static website hosting is enabled on the S3 bucket.
The index document is set to:
index.html

S3 Website Endpoint:
[http://my-asiazgje3n7of3rq2fij-bucket.s3-website-us-east-1.amazonaws.com](http://my-asiazgje3n7of3rq2fij-bucket.s3-website-us-east-1.amazonaws.com)

CloudFront Distribution:
A CloudFront distribution was created to improve content delivery speed and availability.

CloudFront Domain Name:
[https://d1hn9r68w7ueho.cloudfront.net](https://d1hn9r68w7ueho.cloudfront.net)

Permissions and Security:

* Public read access is enabled using a bucket policy.
* Block Public Access settings were disabled to allow website access.
* No WAF or paid security plans were enabled.

Project Status:
The static website is successfully deployed and accessible using both the S3 website endpoint and the CloudFront distribution URL.

Additional Notes:
This project was completed using an AWS VocLabs student environment with restricted permissions, so paid security services were not enabled.
