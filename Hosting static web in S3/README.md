# 🟢 Hosting a Static Website on AWS S3

This project demonstrates how to host a static website using **Amazon S3 (Simple Storage Service)**. It covers all steps from bucket creation to public access and website hosting.

## 🔧 Steps to Host Website on AWS S3

### 1. ✅ Create an S3 Bucket
- Go to the AWS Management Console
- Navigate to **S3**
- Click **Create bucket**
- Set a unique bucket name (e.g., `satyamadhu--busala`)
- Uncheck **Block all public access**
- Acknowledge the warning

### 2. 📂 Upload Your Website Files
- Upload your static files (`index.html`, `style.css`, etc.) to the bucket

### 3. 🔓 Make Your Bucket Objects Public
- Go to the **Actions** tab
- Click **Make as public ACL**:
  
### 4. 🌐 Enable Static Website Hosting
- Go to **Properties** tab of the bucket
- Scroll down to **Static website hosting**
- Choose **Enable**
- Enter `index.html` as the index document
- Optionally set an error document like `error.html`
- Save changes
### 5. 🌍 Access Your Website
In the **Properties** tab, under **Static website hosting**, you'll see a **Bucket website endpoint**
- Copy the URL
- Paste it in your web browser
  
 ### 📝 Notes
- Make sure all files are in the root of the bucket unless you're using folders
- S3 buckets must have unique names globally

## 🖼️ Screenshots

### 1. Create S3 Bucket  
![Create Bucket](https://github.com/SatyamadhuBusala/aws-S3/blob/main/Hosting%20static%20web%20in%20S3/img/S3-bucket.png)

---

### 2. Make Objects Public  
![Make Public](https://github.com/SatyamadhuBusala/aws-S3/blob/main/Hosting%20static%20web%20in%20S3/img/make%20as%20public.png)

---

### 3. Enable Static Website Hosting  
![Enable Hosting](https://github.com/SatyamadhuBusala/aws-S3/blob/main/Hosting%20static%20web%20in%20S3/img/static%20web%20enable.png)

---
### 4. Final output  
![Upload Files](https://github.com/SatyamadhuBusala/aws-S3/blob/main/Hosting%20static%20web%20in%20S3/img/final%20output.png)


