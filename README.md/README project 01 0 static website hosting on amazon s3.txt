# AWS Project 01 - Static Website Hosting on Amazon S3

## Project Overview

I created and deployed a static website using Amazon S3.

## AWS Services Used

- Amazon S3
- Static Website Hosting
- Bucket Policy
- Public Access Settings

## Architecture

```text
User
  |
  v
S3 Website Endpoint
  |
  v
Amazon S3 Bucket
  |
  v
index.html
```

## How It Works

1. The user opens the S3 website endpoint.
2. Amazon S3 receives the website request.
3. The S3 bucket retrieves the `index.html` file.
4. The website appears in the user’s browser.

## Steps Completed

1. Created an Amazon S3 bucket.
2. Uploaded the `index.html` file.
3. Enabled Static Website Hosting.
4. Configured public access.
5. Added a bucket policy.
6. Opened and tested the live website.

## Result

Successfully deployed my first static website using Amazon S3.
