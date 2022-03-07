# Lambda DLQ

This project creates:
- Lambda DLQ;
- SQS Queue;

## Execute the lambda function asynchronous 

aws lambda invoke \
    --function-name ${FunctionName} \
    --invocation-type Event \
    --payload '{}' \
    response.json