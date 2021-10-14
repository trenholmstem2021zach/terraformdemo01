# terraform-tutorial

# Lambda Example

This examples shows how to deploy an AWS Lambda function using Terraform only.

To run, configure your AWS provider as described in https://www.terraform.io/docs/providers/aws/index.html

FIRST AWS CLI Setup
aws configure
aws lambda list-functions

Running the example

run `terraform init` to initialize.

#Save the runnable plan
terraform plan -out run.tf

#apply - execute plan
terraform apply run.tf

run `terraform apply` to see it work.

run `terraform destroy` to clean up.
