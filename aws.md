# S3
Create bucket
```aws s3api create-bucket --bucket example.com --create-bucket-configuration '{"LocationConstraint": "eu-west-1"}'```
Add a policy to bucket
```aws s3api put-bucket-policy --bucket example.com --policy file://policy.json```
Copy file to bucket
```aws s3 cp index.html s3://example.com```
