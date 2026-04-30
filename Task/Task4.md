# Task 4: S3 Bucket with Public and Private Access

# Step 1

Created an S3 bucket where only /images/* is publicly readable and all other objects remain private.

![Bucket](../images/Task4/BucketSS.png)

# Step 2

Configured bucket policy to allow public read access only for the /images/* prefix.

![Bucket Policy](../images/Task4/BucketPolicy.png)

# Step 3

Verified that objects under /images/* are publicly accessible.

![Public Access](../images/Task4/public.png)

# Step 4

Confirmed that objects outside /images/* remain private and return Access Denied.

![Private Access](../images/Task4/Private.png)
