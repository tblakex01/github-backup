
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

## TODO

- Macie Scan
- Deploy the CI/CD pipeline

## Notebooks

The files in the 'notebooks' folder are the raw files created by ChatGPT. They contain the Python code that was executed to develop this project.

![Human AI Conflict](https://github.com/matthewhand/stripe-payment/raw/main/human_ai_conflict.png)

The image above represents the symbiotic relationship between human and machine.

*"Imagination is not limited by what is, but rather, inspired by what could be." - Unknown


## Notebook Analysis

Here is a summary of the analysis of the notebooks in the project:

1. 'CombineCloudFormationResources (1).ipynb': This notebook contains code for defining CloudFormation resources related to the 'GithubBackupPipelineRole', an IAM Role with permissions for Amazon S3, AWS CodeBuild, and AWS Lambda.

2. 'CombineCloudFormationResources.ipynb': This notebook does not contain any executed code cells. It seems like this notebook was created but not used.

3. 'GenerateCloudFormationTemplate.ipynb': This notebook is used for generating a CloudFormation template for an EC2 instance, writing it to a file, and then uploading that file to an S3 bucket. The code cells have not been executed in this notebook.

4. 'Github_Module_Installation (1).ipynb' and 'Github_Module_Installation.ipynb': These notebooks are identical and are used for installing the 'genai' and 'PyGithub' Python packages, loading the 'genai' extension, and interacting with the GitHub API to list the contents of the 'notebooks' directory in the 'matthewhand/github-backup' repository. The code cells have not been executed in these notebooks.

5. 'My First Notebook.ipynb': This notebook does not contain any executed code cells.

There is no 'DeployCloudFormationStack.ipynb' notebook in the current directory, contrary to what was expected.
