boto 3
example - create s3 bucket
first do aws configure

import boto3
client = boto3.client('s3')
response = client.create_bucket(
    Bucket='name_of_bucket',
                

