# PyImageRekognition

## Image Rekongition using AWS S3, AWS Lambda, AWS Rekognition

### what you need: AWS account - basic free 

1. Navigate to aws IAM (identity and management access)

2. Create a IAM > Access Management > Roles > Create role with 2 permissions (AWSLambdaExecute & AmazonRekognitionFullAccess)

3. Create AWS S3 Bucket - change Default encryption to enable and leave Encryption key type as Amazon S3 key (SSE-S3)

4. Upload an image to S3 Bucket

5. Create Lambda function > Runtime Python 3.6 > Chnage default execution role to the role you created in step 2

6. Write Lambda function to in Rekognition on your image in S3 Bucket

