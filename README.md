

```
aws configure set aws_access_key_id ..
aws configure set aws_secret_access_key ...
aws configure set default.region us-east-1

$ aws lambda list-functions
```

```
$ cd hello
$ zip function.zip lambda_function.py
$ aws lambda update-function-code --function-name hello --zip-file fileb://function.zip 
```

