# CloudFormation create stack
aws cloudformation create-stack --stack-name dev-network-infra-pf --template-body file://network-infra.yml --parameters file://dev-parameter-file.json
# Delete stack
aws cloudformation delete-stack \
    --stack-name dev-network-infra-pf