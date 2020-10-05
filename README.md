# aws-cloudformation-templates

## Create Stack
```
aws cloudformation create-stack \
                   --stack-name <stack_name> \
                   --template-body file://templates/<file_name>.yaml \
                   --region us-east-1 \
                   --profile <profile-name>

```

## Delete Stack
```
aws cloudformation delete-stack --stack-name <stack_name>
```

## Templates
- [Create A VPC](./templates/vpc.yaml)

