# AWS Lambda API – Serverless Application

A serverless REST API using:
•⁠  ⁠AWS Lambda
•⁠  ⁠API Gateway
•⁠  ⁠DynamoDB
•⁠  ⁠Deployed using AWS SAM

## Structure:
•⁠  ⁠⁠ template.yaml ⁠: AWS SAM template
•⁠  ⁠⁠ src/ ⁠: Lambda functions
•⁠  ⁠⁠ tests/ ⁠: Unit tests

## Deployment:
```bash
sam build
sam deploy --guided
