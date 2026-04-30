# Task 18: Centralized Logging

# Step 1

Set up centralized logging with VPC Flow Logs, CloudTrail, and ALB access logs stored in a single S3 bucket.

![Centralized Logs Bucket](../images/Task18/CentralizedLog.png)

# Step 2

Created an Application Load Balancer with access logging enabled.

![ALB](../images/Task18/Alb.png)

# Step 3

Enabled CloudTrail for API activity logging across the account.

![CloudTrail](../images/Task18/CloudTrail.png)

# Step 4

Configured VPC Flow Logs to capture network traffic information.

![VPC Flow Log](../images/Task18/VpcFlowLog.png)

# Step 5

Verified all logs are being stored in the centralized S3 bucket.

![S3 Bucket](../images/Task18/S3.png)

# Step 6

Configured lifecycle rules on the logs bucket for automatic archival and deletion.

![Lifecycle Rule](../images/Task18/LifecycleRule.png)
