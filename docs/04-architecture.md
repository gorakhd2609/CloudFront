# CloudFront Architecture

User → Edge Location → CloudFront → Origin

## Origin Types:
- S3 Bucket
- EC2 Instance
- Load Balancer
- External Server

## Flow:
1. User request
2. Nearest edge location
3. Check cache
4. Fetch from origin if needed
5. Store in cache
