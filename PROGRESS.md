# Progress Tracker

## Completed ✅

- [x] AWS S3
- [x] Lambda CloudWatch Log Group
- [x] Lambda IAM Role

## Pending 🏗️

- [ ] Add the inline policy to the Lambda IAM Role

```json
{
      "Effect": "Allow",
      "Action": [
        "s3-object-lambda:WriteGetObjectResponse"
      ],
      "Resource": "*"
    }
```

- [ ] S3 Object Lambda
- [ ] CloudFront Distribution
