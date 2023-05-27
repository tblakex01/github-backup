
## AWS Resources

### AWS Config

- **Config Rule:** `s3-bucket-public-read-prohibited`
- **Config Rule:** `s3-bucket-public-write-prohibited`

### AWS Lambda

- **Function:** `trigger_macie_job`
- **Execution Role:** `NoteableBackupRole`
- **Role Policy:** `allow-config-invoke`

### AWS CloudWatch Events

- **Rule:** `config-change-trigger-macie-job`
- **Target:** `trigger_macie_job` (Lambda function)

### AWS Macie

- **Job:** `macie-job`
- **S3 Bucket:** `macie-sensitive-data-bucket` (for sensitive data discovery results)
