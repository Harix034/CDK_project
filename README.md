# AWS CDK + AWS CodePipeline Assignment

## **Objective**
This project demonstrates the use of AWS Cloud Development Kit (CDK) to programmatically create AWS resources and set up a Continuous Integration/Continuous Deployment (CI/CD) pipeline using AWS CodePipeline. The project includes the creation of the following resources:

1. **Amazon S3 Bucket**: To store static files or artifacts.
2. **AWS Lambda Function**: A serverless function triggered by an event.
3. **Amazon DynamoDB Table**: For basic CRUD operations.

## **Project Structure**
- **`lib/`**: Contains the CDK stack definition for creating AWS resources.
  - **`my-cdk-project-stack.ts`**: Defines the S3 bucket, Lambda function, and DynamoDB table.
- **`buildspec.yml`**: Configuration file for AWS CodeBuild to synthesize and deploy the CDK stack.
- **`cdk.json`**: Specifies the entry point for the CDK app.
- **`package.json`**: Contains dependencies and scripts for the project.
- **`README.md`**: This file, providing an overview of the project.

## **Setup Instructions**
### Prerequisites
- An active AWS account.
- AWS CLI installed and configured.
- AWS CDK installed (`npm install -g aws-cdk`).
- Node.js runtime (v18.x or later).

### Steps to Run
1. **Clone the Repository**
   ```bash
   git clone <repository-url>
   cd my-cdk-project
