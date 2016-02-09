# AWS-DynamoDB
Dockerfile to host the local version of AWS's DynamoDB

# To Build
The latest DynamoDB is pulled to ensure the latest is always available:

```
docker build -t upmcenterprises/aws-dynamodb .
```

# To Run
```
docker run -d -p 8000 upmcenterprises/aws-dynamodb
```

# Reference

http://docs.aws.amazon.com/amazondynamodb/latest/developerguide/Tools.DynamoDBLocal.html
