# Task 17: RDS Read Replica

# Step 1

Created an RDS MySQL primary instance and a read replica for read/write traffic separation.

![Databases](../images/Task17/Databases.png)

# Step 2

Configured the primary RDS instance with automated backups and encryption.

![Primary](../images/Task17/Primary.png)

# Step 3

Created the read replica that replicates data from the primary instance.

![Replica](../images/Task17/Replica.png)

# Step 4

Launched an EC2 app server that routes write traffic to primary and read traffic to the replica.

![EC2 Instance](../images/Task17/Ec2.png)
