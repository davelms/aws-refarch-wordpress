# Highly Available Wordpress on AWS

Originally sourced from [aws-samples/aws-refarch-wordpress](https://github.com/aws-samples/aws-refarch-wordpress), see original [license](LICENSE.txt).

```shell
aws cloudformation create-stack \
 --stack-name WordPress \
 --template-body file://templates/master.yaml \
 --parameters file://params.json \
 --capabilities CAPABILITY_IAM \
 --disable-rollback \
 --region us-east-1 \
 --output json
 ```
 