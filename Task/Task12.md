# Task 12: RDS MySQL Deployment

# Step 1

Launched an RDS MySQL instance in a private subnet with db.t3.micro instance class.

![DB List](../images/Task12/DbList.png)

# Step 2

Configured the RDS instance settings including engine version, storage, and backup retention.

![Configuration](../images/Task12/Configuration.png)

# Step 3

Created a DB Subnet Group spanning two availability zones for the RDS instance.

![DB Subnet Group](../images/Task12/DbSubnet.png)

# Step 4

Verified connectivity and security settings on the RDS instance.

![Connectivity Tab](../images/Task12/ConnectivityTab.png)

# Step 5

Checked the maintenance and backup configuration for automated backups.

![Maintenance Tab](../images/Task12/MaintainceTab.png)

# Step 6

Launched an EC2 instance to connect to the RDS database from within the VPC.

![EC2 Instance](../images/Task12/Ec2.png)
