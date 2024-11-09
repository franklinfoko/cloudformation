# cloudformation
## To validate template
```
aws cloudformation validate-template --template-body file://main.yml
```
## To create stack
```
aws cloudformation create-stack --stack-name MyStackName --template-body file://main.yml --capabilities CAPABILITY_NAMED_IAM
```

## To update stack
```
aws cloudformation update-stack --stack-name MyStackName --template-body file://main.yml --capabilities CAPABILITY_NAMED_IAM
```