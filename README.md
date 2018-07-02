# serverless-api-test

1. Install Serverless Framework
```
$ npm install -g serverless
```

2. Create a new handler based on AWS NodeJS template
```
$ serverless create -t aws-nodejs
```

3. Update your serverless.yml according to your needs

4. Configure your AWS Credentials
```
$ serverless config credentials --provider aws --key {key} --secret {secret}
```

5. Deploy
```
$ serverless deploy
```