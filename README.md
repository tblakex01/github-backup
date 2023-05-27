
# AWS IaC CI/CD Project

This project was entirely developed using ChatGPT and the Noteable plugin. It demonstrates the implementation of:

- Generation of IaC for a CI/CD pipeline (CloudFormation, CodePipeline and CodeBuild)
- Deploying the IaC using the AWS Python SDK  (boto3)
- Deploying code to GitHub using the GitHub API.
- Creation of a GitHub README.md.

## Donation Button

If you find this project useful, you can support its development by making a donation. Think of it as buying me a coffee. Click on the button below to make a donation. You can choose an amount between 1 and 99.

[![Donate with Stripe](https://img.shields.io/badge/Donate%20with-Stripe-blue.svg)](https://buy.stripe.com/00g14peASeEd7xCcMM)

<img src="https://github.com/matthewhand/stripe-payment/raw/main/qr_00g14peASeEd7xCcMM.png" width="150" />

## [Notebook Analysis](notebook-analysis.md)

## [AWS Resources](aws-resources.md)

## TODO

- [x] Generate CloudFormation template for the CodeBuild project
- [x] Deploy the CodeBuild project using boto3
- [x] Update the CodeBuild project to use valid S3 buckets
- [x] Create the S3 buckets using boto3
- [x] Update the CodeBuild project to use the correct service role
- [x] Update the CodeBuild project to use the correct source and artifact types
- [x] Check the status and logs of the CodePipeline and CodeBuild resources
- [x] Update the CodeBuild project to use the correct project name
- [x] Update the CodeBuild project to use the correct artifact override
- [x] Update the CodePipeline to use the correct build project
- [x] Update the README.md file to reflect the progress

- [x] Macie Scan
- [x] Deploy the CI/CD pipeline
- [x] Configure SNS notification for Macie detections (configured to send findings to Security Hub)

## Notebooks

The files in the 'notebooks' folder are the raw files created by ChatGPT. They contain the Python code that was executed to develop this project.

![Human AI Conflict](https://github.com/matthewhand/stripe-payment/raw/main/human_ai_conflict.png)

The image above represents the symbiotic relationship between human and machine.

*"Imagination is not limited by what is, but rather, inspired by what could be." - Unknown


