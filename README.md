# AWS Ventura Cloudformation Project

## AWS Cloudformation CLI Commands
- **AWS CLI Documentation:**  https://docs.aws.amazon.com/cli/latest/reference/cloudformation/create-stack.html
 
- **Create Stack Commands:** 
aws cloudformation create-stack \
--stack-name Ventura-Prod-Env-Infra \
--template-body file://Ventura-Prod-Env-Infra.yaml \
--parameters file://Ventura-Prod-Env-Infra-Parameter-file.json