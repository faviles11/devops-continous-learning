## Explain the concept of state locking in Terraform. Why is it important, and how can you handle locking conflicts?

- State locking prevents corruption in the state file.

- Useful in real-world production environments when the state file is stored remotely.

### Remote backends examples:

- AWS S3 Bucket, enable locking with DynamoDB.

- Azure Blob Storage, enable locking with blob permissions / locks.

[text](https://developer.hashicorp.com/terraform/language/backend/remote)
