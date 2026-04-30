# Task 14: Hub-and-Spoke VPC Architecture

# Step 1

Created three VPCs — Hub, Spoke1, and Spoke2 — for the hub-and-spoke architecture.

![VPCs](../images/Task14/Vpc.png)

# Step 2

Established VPC Peering connections between Hub-Spoke1 and Hub-Spoke2.

![Peering Connections](../images/Task14/Peering.png)

# Step 3

Configured the Hub route table with routes to both spoke VPCs via peering connections.

![Hub Route Table](../images/Task14/Route_Hub.png)

# Step 4

Configured the Spoke route tables with routes back to the Hub VPC.

![Spoke Route Table](../images/Task14/Route_Spoke.png)

# Step 5

Verified all route tables are correctly associated with the proper subnets.

![Route Tables](../images/Task14/Rt.png)

# Step 6

Tested connectivity by pinging from Spoke1 to Hub — ping was successful.

![Spoke1 to Hub Ping](../images/Task14/1%20To%20Hub%20ping.png)

# Step 7

Tested connectivity from Spoke1 to Spoke2 — ping failed as expected since spokes cannot communicate directly.

![Spoke1 to Spoke2 Ping](../images/Task14/1%20to%20Spoke2.png)
