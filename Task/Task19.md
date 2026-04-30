# Task 19: WAF (Web Application Firewall)

# Step 1

Created a WAF Web ACL with SQL injection protection, rate limiting, and geo-blocking rules.

![WAF Web ACL](../images/Task19/Waf.png)

# Step 2

Configured all WAF rules including SQL injection, rate limiting, and geo-blocking.

![Rules](../images/Task19/Rules.png)

# Step 3

Viewed the SQL injection rule details using AWS Managed Rules.

![SQL Rule](../images/Task19/SqlRule.png)

# Step 4

Configured the rate limiting rule to block IPs exceeding 100 requests per 5 minutes.

![Rate Limiting](../images/Task19/Rate.png)

# Step 5

Set up geo-blocking to restrict traffic from specific countries.

![Geo Blocking](../images/Task19/Geo.png)

# Step 6

Associated the WAF Web ACL with the Application Load Balancer.

![Associated Resources](../images/Task19/Resource.png)

# Step 7

Verified the WAF overview dashboard showing all rules and metrics.

![Overview](../images/Task19/Overview.png)
