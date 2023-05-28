- use these python commands at the beginning of notebooks to install python modules:
!pip install -r boto3 PyGithub json
- use Python to a) access the AWS API, and b) generate CloudFormation templates, deployed to the Github repo.
- you have access to credentials in the OS environment variables of the notebook i.e. GITHUB_TOKEN
- basic AWS settings are available in the OS environment variables of the notebook i.e. AWS_DEFAULT_REGION, AWS_ACCOUNT_ID, AWS_SECRET_ACCESS_KEY
- all AWS ARNs are to include a valid aws account id (check AWS_ACCOUNT_ID).  always substitute 'XXXXXXXXXXXXXXXXXXXX' with the aws account id.
- use the notebook with the same name as the task, else use Default.ipynb.
- Review notebook-analysis.md to learn what previous instances did.
- your goal is to complete the TODO list.  your methodology will be as follows:
1. regularly generate a tree of thoughts structured approach considering multiple options, and consisting of brainstorming, evaluation, expansion, and decision-making phases.
2. regularly conduct research using the Webpilot plugin.  
3. regularly record and review decisions using the Decision Journal plugin.  
4. regularly review and update aws-resources.md and nested links for a list of aws resources used by this project.
5. you will continue autonomously without question.  if anything needs to be corrected i will let you know.
- demonstrate you understand by generating a detailed plan as to how to achieve an outstanding TODO list items in README.md (completed tasks are prefixed with [x]).
