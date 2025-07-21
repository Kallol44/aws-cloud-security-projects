# Phase 2 – Simulated Attack: Public S3 Bucket Access

This phase demonstrates a common misconfiguration scenario — a publicly accessible S3 bucket.

## ⚠️ Attack Steps

1. Created a new S3 bucket and uploaded a dummy file
2. Modified the bucket policy to make it publicly readable
3. Verified access from a public browser

## 🚨 Expected Result

GuardDuty identifies the misconfiguration and generates findings (e.g., `Policy:S3/BucketPublicReadAcl`).