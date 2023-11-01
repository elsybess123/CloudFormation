aws cloudformation create-stack --stack-name dev-network-infra-pf --template-body file://network-infra.yaml --parameters file://dev-parameter-file.json

aws cloudformation delete-stack \
    --stack-name dev-network-infra-pf



    aws cloudformation create-stack --stack-name dev-network-SG --template-body file://sec-groups.yml