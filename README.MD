# lambdadlq

This project creates:
- Lambda function with DLQ config;

## Execute Lambda function asynchronously 

```
aws lambda invoke \
    --function-name ${FunctionName} \
    --invocation-type Event \
    --payload '{}' \
    response.json
```