🚀 Day 5 - AWS & DevOps Challenge : Secure Object Access with Pre-Signed URLs! 🔥
Today, I created an S3 bucket, uploaded an object, and generated a pre-signed URL valid for 10 minutes. This allows temporary, secure access to the object via a URL—without making the bucket public!
Steps to Generate a Pre-Signed URL in AWS S3 (Using AWS Console)
 1️⃣ Go to the AWS S3 Console and navigate to your S3 bucket.
 2️⃣ Select the object (file) you want to share.
 3️⃣ Click on Actions and select Create presigned URL.
 4️⃣ Choose the expiration time (e.g., 10 minutes).
 5️⃣ Click Create and copy the generated URL.
 6️⃣ Share the URL – Anyone with the link can access the object within the validity period.
 7️⃣ Once expired, the URL becomes invalid, ensuring security.

Why use Pre-Signed URLs?
 ✅ Secure Access Control – Grant temporary access without exposing credentials
 ✅ Time-Limited Access – Restrict access duration for better security
 ✅ No Public Exposure – Keep your S3 bucket private while sharing files
 ✅ Flexible Permissions – Control read/write access per URL
