# Image-Rekognition-with-AWS-Rekognition

## Project Overview
This project is designed to implement an image recognition system using AWS Rekognition, Lambda, and IAM. The system is capable of detecting and analyzing human and cat faces from uploaded images, providing a robust, scalable solution for image analysis.

## Features
Face Detection: Identifies and differentiates between human and cat faces.
Serverless Architecture: Utilizes AWS Lambda for backend processing to manage image uploads and recognition tasks.
Secure Access: Integrates IAM for secure role-based access to AWS services.
Automated Workflow: Automates the entire process from image upload to recognition using AWS services.

## Prerequisites
AWS Account
Basic knowledge of AWS Rekognition, Lambda, and IAM
Node.js or Python (for Lambda function development)
AWS CLI installed and configured on your machine

## Setup Instructions
1. Create an S3 Bucket
Create an S3 bucket to store the images you want to analyze.
Set up the appropriate permissions to allow the Lambda function to access the bucket.
2. Configure AWS Rekognition
Use AWS Rekognition to create a collection that will store the detected faces.
3. Develop the Lambda Function
Write a Lambda function in Node.js or Python to process images uploaded to the S3 bucket.
The function should call AWS Rekognition to detect and analyze faces.
Ensure the Lambda function has the necessary permissions via IAM roles.
4. Set Up IAM Roles
Create IAM roles and policies that grant the Lambda function access to the S3 bucket and Rekognition service.
Attach these roles to your Lambda function.
5. Deploy and Test
Deploy the Lambda function and test it by uploading images to the S3 bucket.
Monitor the output in CloudWatch to verify successful recognition.

    ## How It Works
Image Upload: Upload an image containing a human face or cat face to the S3 bucket.
Lambda Trigger: The upload triggers the Lambda function.
Image Processing: The Lambda function processes the image using AWS Rekognition.
Face Recognition: AWS Rekognition analyzes the image, detects faces, and returns the results.
Result Handling: The results are logged or processed further as needed.

## Contributing
Contributions are welcome! Please feel free to submit issues and pull requests for any improvements or new features.

## Document
i have uploaded a word file which contains the step for the project configuration.
