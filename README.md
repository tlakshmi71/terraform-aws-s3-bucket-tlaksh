# terraform-aws-s3-bucket

A simple Terraform module to create an AWS S3 bucket.

## Usage

```hcl
module "s3_bucket" {
  source      = "policy-as-code-training/s3-bucket-tlaksh/aws"
  bucket_name = "my-tlaksh-bucket"
}
``` 