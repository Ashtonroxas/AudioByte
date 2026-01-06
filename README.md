# Services Used

**AWS Lambda** - Serverless management for Upload, List, Delete handlers.

**Amazon S3** - Storage for music files with presigned URLs

**Amazon DynamoDB** - Using NoSQL database for storing music metadata

**AWS AppSync** - Managed GraphQL API with real-time capabilities

**Amazon Cognito** -User authentication and identity management for each songs.

**AWS CloudWatch** - Monitoring, logging, and dashboards.

**AWS IAM** - identity and access management with least-privilege policies

**AWS CDK** - Infrastructure (in code) for automated deployment


# To Set up

cd Infrastructure

pip install -r requirements.txt

pip install -r requirements-dev.txt

cdk deploy

cd ..

cd Frontend

npm install

npm run dev

# AudioByte
