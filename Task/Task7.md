# Task 7: S3 Lifecycle Rules

# Step 1

Created an S3 bucket with lifecycle rules applied to uploads/* prefix.

![Bucket](../images/Task7/Bucket.png)

# Step 2

Configured lifecycle rule: 30 days to Standard-IA, 90 days to Glacier, 365 days to Delete.

![Management Tab](../images/Task7/ManagmentTab.png)

# Step 3

Enabled versioning on the bucket to support lifecycle transitions.

![Versioning](../images/Task7/Version.png)

# Step 4

Verified the bucket policy is correctly configured alongside the lifecycle rules.

![Policy](../images/Task7/Policy.png)
