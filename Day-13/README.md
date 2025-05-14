boto 3
example - create s3 bucket
come in edit mode to see proper syntax
first do aws configure

import boto3
client = boto3.client('s3')
response = client.create_bucket(
    Bucket='name_of_bucket',
)        

