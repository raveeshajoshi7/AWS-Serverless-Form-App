# AWS-Serverless-Form-App
Serverless web application using AWS Lambda, API Gateway, DynamoDB, S3, and CloudFront
# 🚀 Serverless Web Application on AWS

## 📌 Project Overview

This project demonstrates a fully serverless web application built using AWS services. Users can submit messages through a frontend interface, which are processed via API Gateway and stored in DynamoDB.

---

## 🏗️ Architecture

Frontend (HTML - S3 + CloudFront)
⬇️
API Gateway
⬇️
AWS Lambda
⬇️
DynamoDB

---

## 🛠️ Services Used

* Amazon S3 (Static Hosting)
* Amazon CloudFront (CDN)
* Amazon API Gateway
* AWS Lambda
* Amazon DynamoDB
* Amazon CloudWatch

---

## 🚀 Features

* Serverless architecture (no servers to manage)
* Secure S3 bucket with CloudFront OAC
* REST API integration
* Data storage using NoSQL database
* CORS handling for frontend-backend communication

---

## 🧪 Sample Request

```json
{
  "name": "Raveesha",
  "message": "Testing serverless application"
}
```

---

## 📊 Sample Logs (CloudWatch)

START RequestId: ...
Data saved successfully
END RequestId: ...

---

## ⚡ Challenges Faced

* CORS errors while connecting frontend with API Gateway
* Handling OPTIONS preflight requests
* Fixing 403 Forbidden error in CloudFront
* Configuring secure access between S3 and CloudFront

---

## 💡 Learnings

* Hands-on experience with serverless architecture
* Debugging using CloudWatch logs
* Understanding AWS networking and security
* Real-world deployment experience

---

## 👩‍💻 Author

Raveesha Joshi
