# 🎉 YourEventSpace - Event Booking Web Application

YourEventSpace is a serverless event booking website built using **HTML, CSS, JavaScript**, and deployed on **AWS S3** with **CI/CD powered by GitHub Actions**.

---

## 🌐 Live Website

👉 [Click here to visit the live site](https://youreventspace-frontend.s3.ap-south-1.amazonaws.com/index.html)

---

## 💡 Features

- 🎈 Filter events by category, date, and price
- 📋 Dynamic pricing page with Stripe (test)
- 📩 Contact form with AWS Lambda & SES email trigger
- 🔐 User authentication using AWS Cognito
- ⚙️ Fully automated CI/CD pipeline with GitHub Actions

---

## 🚀 CI/CD Pipeline (GitHub → AWS S3)

Every time I push code to this GitHub repository:
1. GitHub Actions triggers the deployment.
2. Code is automatically uploaded to my S3 bucket.
3. Website gets updated live with no manual effort.

---

## 🧰 Tech Stack

- **Frontend:** HTML, CSS, JavaScript (Vanilla)
- **Cloud:** AWS S3, Lambda, SES, API Gateway, Cognito
- **CI/CD:** GitHub Actions → S3 Deployment

---

## 🛠️ How to Run Locally

```bash
git clone https://github.com/Tunai24/youreventspace.git
cd youreventspace
open index.html in browser
