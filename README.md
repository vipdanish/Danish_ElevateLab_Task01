### 📂 Simple File Upload App with Node.js + CI/CD Pipeline
##### A simple Node.js App in which you can upload file.   
##### Enhanced with a CI/CD pipeline using GitHub Actions + Docker + DockerHub.
---
### 📌 Objective
Set up a CI/CD pipeline using GitHub Actions to build, test, and deploy a Node.js web application.

This project is dedicated to **Elevate Labs** as part of the **DevOps Internship — Task 1**.

---
### ▶️ Run Locally
```bash
git clone https://github.com/Majidkn/nodejs-simple-file-upload.git
cd nodejs-simple-file-upload
npm install
npm start
````

Open in browser → `http://localhost:3000`

---

### 🐳 Docker Support

```bash
# Build Docker image
docker build -t file-upload-app .

# Run container
docker run -p 3000:3000 file-upload-app
```

---

### ⚙️ CI/CD Pipeline

* Defined in `.github/workflows/main.yml`
* Trigger: push to `main` branch
* Steps:

  1. Checkout repository
  2. Install dependencies & run tests
  3. Build Docker image
  4. Push Docker image to DockerHub

---

### 🎯 Outcome

By completing this task, I:

* Learned how to automate the build, test, and deployment process using GitHub Actions
* Gained hands-on experience with Docker containerization
* Understood the complete CI/CD workflow for a real Node.js application



