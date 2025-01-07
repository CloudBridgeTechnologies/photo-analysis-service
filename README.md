### AWS SAM and Serverless.com Lambda S3 Demonstration

This project demonstrates how we can deploy a simple application using AWS SAM and [Serverless Framework](https://serverless.com/).

This application is a simple Lambda function written in NodeJs that responds to events in an S3 bucket. The event is a photo upload and it will trigger an Amazon Rekognition to anaylze the photo.

### Folder Structure

```

AWS_SAM
└── src
    └── lib
serverless_com
└── src
    └── lib
    serverless.yml
.gitignore
```
