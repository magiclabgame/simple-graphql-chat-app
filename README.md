# Simple GraphQL Chat App

We can use Aws Cloudformation for deployment. 
```
aws cloudformation deploy --template-file ./cloudformation.yml --stack-name SimpleChatApp --capabilities CAPABILITY_NAMED_IAM
```


## Features
- Aws AppSync
- GraphQL
- Serverless
- Dynamodb Expired Messages