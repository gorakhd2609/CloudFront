# How CloudFront Works

1. User sends request via URL (image/file/website)
2. DNS routes request to nearest edge location
3. CloudFront checks cache

## Cache Hit
If content exists in cache:
→ Delivered immediately to user

## Cache Miss
If content not found:
→ Request forwarded to origin server (S3 / EC2 / HTTP server)

## Retrieval
Origin sends data → CloudFront caches it → User receives response
