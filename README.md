# aws-cloudformation-templates

## Validate Template

```
aws cloudformation validate-template \
    --template-body file://templates/vpc-with-two-public-subnet.yaml \
    --profile <profile-name> \
    --region <region-name>
```

## Create Stack

```
aws cloudformation create-stack \
                   --stack-name <stack_name> \
                   --template-body file://templates/<file_name>.yaml \
                   --region us-east-1 \
                   --profile <profile-name>

```

## Update Stack

```
aws cloudformation update-stack \ 
    --stack-name <stack_name> \ 
    --template-body file://<file_path> \
    --region us-east-1 \
    --profile bc-sandbox-admin
```


## Delete Stack

```
aws cloudformation delete-stack --stack-name <stack_name>
```

## Templates

- [VPC](./templates/vpc.yaml)
- [VPC With Two Public Subnet](./templates/vpc-with-two-public-subnet.yaml)
- [VPC With Two Public Subnet and Internet Gateway with Public Route Table](./templates/vpc-two-public-subnet-internet-gateway-and-public-route-table.yaml)
