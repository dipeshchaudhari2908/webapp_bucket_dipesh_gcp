# webapp_bucket_dipesh_gcp
Simple fully functional website hosted on GCP bucket

# Static Website Hosting on Google Cloud Storage

## 📌 Project Overview
This project demonstrates how to deploy a fully functional static website using **Google Cloud Storage (GCS)**.  
It highlights foundational cloud skills, including object storage usage, IAM configuration, static web hosting.

The website is built using simple **HTML/CSS** and hosted directly from a GCS bucket configured for public access.

---

## 🚀 Features
- Static website built using HTML5 & CSS3  
- Hosted fully on Google Cloud Storage  
- Public read access via IAM policies  
- Configured index and 404 pages  


---

## 🛠️ Tech Stack
- **Google Cloud Storage**
- **Google Cloud IAM**
- **HTML5**
- **CSS3**

---

## 📂 Project Structure

---

## 📝 Steps to Deploy

### 1️⃣ Create a Google Cloud Storage Bucket
- Go to **Cloud Storage → Buckets**
- Click **Create Bucket**
- Select:
  - Unique bucket name  
  - Region of choice  
  - Standard storage class

### 2️⃣ Enable Bucket for Website Hosting
Under **Bucket → Website configuration**:
- Set **Main Page** → `index.html`
- Set **Not Found Page** → `404.html`

### 3️⃣ Upload Website Files
Upload:
- `index.html`  
- `404.html`  
- `styles.css` and assets  

### 4️⃣ Set Public Access Permissions, you will find in the Bucket -> Permission -> Grant Access -> 
Grant public read access:
- IAM(New Prinicipals) → `allUsers` → Role: *Storage Object Viewer*
- OR use **Public Access → Fine-grained permissions**

### 5️⃣ Get website URL 
- go to the bucket
- Find the index.html page click on it
- and copy the public URL and paste it into any browser. 



