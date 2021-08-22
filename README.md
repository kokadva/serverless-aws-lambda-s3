# serverless-aws-lambda-s3

Example project on how to setup aws lambda with api gateway which saves the data to S3 with serverless

### Setup Serverless CLI:
1. Run `npm install -g serverless`
2. Configure credentials: `sls config credentials --provider aws --key <KEY> --secret <SECRET>` (Create IAM user with programattic access, full permissions on lambda, S3 and Cloud formation, once created you'll be able to get a `key` and a `secret`)

### Serverless configuration:


Author: Konstantine Dvalishvili
