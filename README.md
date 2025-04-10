1.

Create an IAM user and attach a custom policy that satisfy the below condition.
    a. The user should only have access to see the list of files on any bucket name that has the word spark-job in s3. 
    b. The user should be able to delete any file in the bucket spark-job-data-input in the folder dumps except for the files that ends with csv.


2.

Using the same user created above, create another custom-policy that will allow the user to only
    a. Create an IAM user if the word engineer starts it. Basically if the user creates a user called daniel for example, 
       the user should get permission denied, but when the user creates the user like this engineer_daniel, it should be created.


3.
List the ARN format/pattern for the below list of AWS resources;
S3 accesspoint
S3 bucket
S3 storagelensgroup
S3 object
IAM mfa
IAM role
IAM user
EC2 elastic-ip
EC2 fleet
EC2 instance
EC2  image
