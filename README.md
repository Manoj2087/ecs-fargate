
# Create Stack
```
aws cloudformation create-stack --stack-name myteststack \
--template-body file://fargate-cluster.yaml \
--parameters \
ParameterKey=ProjectName,ParameterValue=test \
--profile dev \
--region ap-southeast-2
```
# Delete Stack
```
aws cloudformation delete-stack \
--stack-name myteststack \
--profile dev \
--region ap-southeast-2
```
# docker pull nginx
```
docker image pull nginx:stable-alpine
docker image pull nginx

```
