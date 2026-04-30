# Task 11: EC2 Monitoring with CloudWatch and SNS

# Step 1

Launched an EC2 instance with detailed monitoring enabled.

![EC2 Instance](../images/Task11/Ec2.png)

# Step 2

Enabled detailed monitoring on the EC2 instance for 1-minute interval metrics.

![Detailed Monitoring](../images/Task11/DetailedMonitoring.png)

# Step 3

Created CloudWatch alarms for high CPU utilization and 5xx errors.

![Alarms](../images/Task11/Alarms.png)

# Step 4

Configured the high CPU alarm to trigger when CPU exceeds 80%.

![High CPU Alarm](../images/Task11/HighCpu.png)

# Step 5

Set up 5xx error alarm on the Application Load Balancer.

![5XX Alarm](../images/Task11/5XX.png)

# Step 6

Created an SNS topic for alert notifications.

![SNS Topics](../images/Task11/Topics.png)

# Step 7

Verified the ALB is running and associated with the monitoring setup.

![Load Balancer](../images/Task11/Lb.png)
