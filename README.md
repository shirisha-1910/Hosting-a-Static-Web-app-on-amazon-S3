# Hosting a Static Web-app on amazon-S3


# Project Name: Static Website Hosting on Amazon S3

## Project Overview
Welcome to the Static Website Hosting on Amazon S3 project! The aim of this project is to demonstrate how to host a static web application on Amazon S3, using a temperature converter as an example. This project showcases the process of hosting a static web application on Amazon S3, providing a reliable and scalable platform for web hosting.

## Project Code
You can find the code for this project in the `CFK` directory:
- [Project Code](CFK/temp.html)

## Hosting on Amazon S3
Follow these steps to host your static web application on Amazon S3:

1. **Create an S3 Bucket**: 
   - Log in to the AWS Management Console and navigate to the S3 service.
   - Click on "Create bucket" and provide a unique bucket name.
   - Choose the AWS region for our bucket and leave other settings as default.
   - Click "Create bucket" to create the bucket.

2. **Configure Bucket for Website Hosting**:
   - Select the newly created bucket from the S3 dashboard.
   - Go to the "Properties" tab and click on "Static website hosting".
   - Choose "Use this bucket to host a website" and enter `temp.html` (or our desired main HTML file) as the Index document.
   - Click "Save changes" to configure the bucket for website hosting.

3. **Upload Website Files**:
   - In the S3 dashboard, select the bucket which we have created.
   - Click on "Upload" and select the files from our project directory, including HTML, CSS, JavaScript, and any other assets.
   - Once the files are uploaded, make sure to select them and click "Next" to proceed.
   - Leave the permissions settings as default and click "Next" again.
   - Click "Upload" to upload the files to our bucket.

4. **Set Permissions**:
   - After uploading the files, select them in the bucket.
   - Click on the "Actions" dropdown and choose "Make public" to grant public read access to our website files.
   - Confirm the action to make the files public.

5. **Test Your Website**:
   - Once the files are uploaded, navigate to the bucket URL or the website endpoint provided in the bucket properties.
   - Test your website to ensure that it functions correctly and that all assets are loading properly.

6. **Finalization**:
   - Make any final adjustments or configurations as needed to ensure that the website functions correctly.
   - Our static web application is now successfully hosted on Amazon S3!

