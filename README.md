# AWS IaC CI/CD Project

This project was entirely developed using ChatGPT and the Noteable plugin. It demonstrates the implementation of:

- Generation of IaC for a CI/CD pipeline (CloudFormation, CodePipeline and CodeBuild)
- Deploying the IaC using the AWS Python SDK  (boto3)
- Deploying code to GitHub using the GitHub API.
- Creation of a GitHub documents i.e. README.md.
- Configuring AWS Security Services i.e. Macie, Security Hub, Config.

*"Imagination is not limited by what is, but rather, inspired by what could be." - Unknown

## Donation Button

If you find this project useful, you can support its development by making a donation. Think of it as buying me a coffee. Click on the button below to make a donation. You can choose an amount between 1 and 99.

[![Donate with Stripe](https://img.shields.io/badge/Donate%20with-Stripe-blue.svg)](https://buy.stripe.com/00g14peASeEd7xCcMM)

<img src="https://github.com/matthewhand/stripe-payment/raw/main/qr_00g14peASeEd7xCcMM.png" width="150" />

## [Notebook Analysis](notebook-analysis.md)

## [AWS Resources](aws-resources.md)

## [Hints for ChatGPT](hints-for-chatgpt.md)

## TODO

- [x] Create an AWS Config rule that checks whether S3 buckets allow public read access.
- [x] Create an AWS Config rule that checks whether S3 buckets allow public write access.
- [x] Create a Lambda function that is triggered when AWS Config detects a configuration change.
- [x] Add a policy to the Lambda function's execution role that allows AWS Config to invoke the function.
- [x] Create a CloudWatch Events rule that triggers the Lambda function when AWS Config detects a configuration change.
- [x] Create a Macie job that scans the S3 bucket for sensitive data when the Lambda function is triggered.
- [ ] Deploy FalconLM chatbot.
  - [ ] Execute falconlm-deploy.py.
  - [ ] validate it is working.
  - [ ] generate dozens of prompts to test the falconlm chatbot.
  - [ ] produce a report of the falconlm chatbot responses.
  - [ ] shutdown the falconlm chatbot.
- [ ] Address all Security Hub findings.
  - [ ] Retrieve list of Security Hub findings and for each create a TODO list task to address
- [ ] Retrieve list of SageMaker examples from here https://github.com/huggingface/notebooks/tree/main/sagemaker and for each create a TODO list task to deploy the example
