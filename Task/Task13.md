# Task 13: Disaster Recovery Setup

# Step 1

Created source and destination S3 buckets for cross-region replication.

![Buckets](../images/Task13/Buckets.png)

# Step 2

Configured S3 replication rules to replicate objects from source to destination bucket.

![Replication Rule](../images/Task13/ReplicationRule.png)

# Step 3

Launched the RDS primary MySQL instance in the primary region.

![Primary Instance](../images/Task13/PrimaryIns.png)

# Step 4

Created a cross-region read replica of the RDS instance in the DR region.

![Replica](../images/Task13/Replica.png)

# Step 5

Created an AMI backup of the EC2 app server for disaster recovery.

![AMI Backup](../images/Task13/Ami.png)
