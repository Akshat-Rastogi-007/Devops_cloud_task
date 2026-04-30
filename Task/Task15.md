# Task 15: Private EC2 with S3 Access via VPC Endpoint

# Step 1

Created a VPC Gateway Endpoint for S3 so the private EC2 can access S3 without internet.

![VPC Endpoint](../images/Task15/VpcEndpoint.png)

# Step 2

Launched EC2 instances — a bastion in public subnet and a private instance with no internet access.

![EC2 Instances](../images/Task15/Ec2.png)

# Step 3

Verified the private route table has the S3 endpoint route but no internet route.

![Route Table](../images/Task15/Rt.png)
