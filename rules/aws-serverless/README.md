# AWS Serverless (Lambda, SAM, DynamoDB)

Cursor rules for building serverless applications with AWS Lambda, API Gateway, DynamoDB, and SAM.

## Covers
- Lambda handler design (thin handlers, typed events, response formatting)
- DynamoDB (single-table design, GSIs, TTL, optimistic locking)
- SAM template patterns (globals, resource references, parameter overrides)
- API Gateway (HTTP API v2, authorizers, CORS, throttling)
- Error handling (custom errors, DLQ, retry with backoff)
- Logging with AWS Lambda Powertools
- Testing with aws-sdk-client-mock and SAM local
- Security (least-privilege IAM, KMS, Secrets Manager)

## Usage
```bash
cp .cursorrules /path/to/your/serverless-project/.cursorrules
```
