# localstack
localstack commends


aws --endpoint-url=http://localhost:4566 s3api create-bucket --bucket config-bucket --region eu-west-2
aws --endpoint-url=http://localhost:4566 cp ./file.txt s3://my-bucket/file.txt

