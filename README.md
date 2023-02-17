SaaS Portal with Amazon AppStream 2.0 Project

Created a software as a service (SaaS) portal for customers interested in creating an account and signing up for a web-based software subscription using Amazon S3, Amazon SES, Amazon Cognito, Amazon API Gateway, AWS Lambda, and Amazon AppStream 2.0.

Step-by-Step Formation:
1. Select a Region
2. Create a new Amazon S3 bucket
3. Upload assets to the S3 bucket
4. Enable static website hosting for s3 bucket
5. Enable public read access for the s3 bucket
6. Add and Verify the sample email address identified in Amazon SES
7. Create an Amazon Cognito user pool
8. Add an app client to the user pool
9. Specify a custom FROM email address
10. Create an IAM policy for a custom IAM role
11. Create an IAM service role that allows the Lambda function to call AWS services
12. Create and configure the Lambda function
13. Create a New REST API
14. Configure API Getaway for Lambda integration
15. Update the web configuration files in the S3 bucket
16. Test setup by launching the website, registering as a user, and verifying to sign in to access the AppStream 2.0 streaming URL
