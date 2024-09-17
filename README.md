Static Website Hosted on AWS S3

Overview
This repository contains the source code for a static website hosted on Amazon S3. The website is accessible via a custom domain managed by Amazon Route 53, and deployments are automated using GitHub Actions.

Live Demo
Check out the live website at: http://staticwebsite-s3.s3-website.ap-south-1.amazonaws.com

Technologies Used
Amazon S3: For hosting the static website.
Amazon Route 53: For domain management and DNS routing.

Setup Instructions
Initialize Your Repository:

Create a new repository on GitHub and clone it to your local machine:
git init
git remote add origin https://github.com/monicaseby/static_website_s3.git
Add the Project Files:
Copy the project files into your local repository directory.

Commit and Push:
Add, commit, and push the files to your GitHub repository:
git add .
git commit -m "Initial commit with static website files"
git push -u origin main

Configure S3 for Static Website Hosting:
Set up an S3 bucket to host your static site. Enable static website hosting and make sure to configure permissions for public access.

Set Up Route 53:
Create a hosted zone for your domain in Route 53.
Create an alias record pointing to your S3 bucket.
