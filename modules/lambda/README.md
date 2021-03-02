# AWS API Document Terraform module

Terraform module which creates a Lambda with a ready-to-use NodeJS source code to handle
DOCX document generation on AWS.

## Usage

```hcl
module "lambda-api-document" {
  source = "genstackio/layer-api-document/aws//modules/lambda"

  name   = "my-lambda-api-document"
}
```
