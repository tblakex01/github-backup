
# Github Backup

This repository contains a Python script that backs up a Github repository to an S3 bucket.

## TODO

- [x] Create an AWS Config rule that checks whether S3 buckets allow public read access.
- [x] Create an AWS Config rule that checks whether S3 buckets allow public write access.
- [x] Create a Lambda function that is triggered when AWS Config detects a configuration change.
- [x] Add a policy to the Lambda function's execution role that allows AWS Config to invoke the function.
- [x] Create a CloudWatch Events rule that triggers the Lambda function when AWS Config detects a configuration change.
- [x] Create a Macie job that scans the S3 bucket for sensitive data when the Lambda function is triggered.
- [ ] Update 'aws-resources.md' in the Github repo to include these new AWS resources.
