# aws-s3-static-website-hosting
aws-s3-static-website-hosting

1. Create an s3 bucket with a unique name.
   
2. In properties, enable static website hosting, write the name of the index document (default: index.html), in our case it is (demo.techapricate.click.html). The file is attached in the repo here.

3. Disable "Edit Block Public Access settings" for your bucket.
   
   ![image](https://github.com/user-attachments/assets/8493f66b-c6a1-41a5-9d6b-c2c32352bddc)

4. Add a bucket policy to allow public read access to all the content within the bucket (attached in the repo).

5. Test the S3 Bucket Endpoint on a browser.

