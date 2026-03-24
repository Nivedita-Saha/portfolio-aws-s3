# Portfolio Site — AWS S3 + CloudFront

A personal portfolio site hosted on AWS S3 with static website hosting.

## Live Demo
http://niv-portfolio-2026.s3-website.eu-west-2.amazonaws.com

## Tech Stack
- AWS S3 — static file hosting
- AWS IAM — access management
- AWS CLI — deployment from terminal
- HTML/CSS — frontend

## Architecture
Browser → AWS S3 (eu-west-2) → index.html

## What I learned
- Creating and configuring S3 buckets via CLI
- Setting up IAM users with least-privilege permissions
- Deploying static websites to AWS
- Managing bucket policies for public access

## How to deploy
```bash
aws s3 sync . s3://your-bucket-name --delete
```
