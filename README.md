# Simple GraphQL Chat App

We can use Aws Cloudformation for deployment. 
```
aws cloudformation deploy --template-file ./cloudformation.yml --stack-name SimpleChatApp --capabilities CAPABILITY_NAMED_IAM
```

> We need a lambda function for authentication user. The userId returned from the function here will be the userId that we will use in graphql queries. 

> Docs: https://aws.amazon.com/blogs/mobile/appsync-lambda-auth/

## Features
- Aws AppSync
- GraphQL
- Serverless
- Dynamodb Expired Messages