# Step 1

Created an EC2 instance with Ubuntu 24.04 LTS and t3.micro instance type. Configured the instance in the appropriate VPC and availability zone with public IP assignment enabled.

![Create EC2](../images/Task3/1_create_ec2.png)

# Step 2

Installed a web application on the EC2 instance. Connected via SSH and set up the necessary dependencies and application files for the web server.

![Install Web App](../images/Task3/2_install_webapp.png)

# Step 3

Added custom application files and configuration to the web server. Configured the web application files and permissions to ensure proper deployment.

![Add Files](../images/Task3/3_add_files.png)

# Step 4

Created a Launch Template from the configured EC2 instance. This template captures the instance configuration, including AMI, instance type, security groups, and custom user data scripts.

![Launch Template](../images/Task3/4_launch_template.png)

# Step 5

Configured an Auto Scaling Group using the Launch Template. Set up scaling policies with minimum, maximum, and desired capacity to automatically manage multiple instances based on demand.

![Auto Scaling Group](../images/Task3/5_autoscaling_group.png)
