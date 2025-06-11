# Student Data Serverless App

A fully serverless web application built on AWS to store and retrieve student data, using:

- **Amazon S3** (static site hosting)
- **AWS Lambda** (Python 3.12 functions)
- **Amazon API Gateway** (REST API)
- **Amazon DynamoDB** (NoSQL DB)
- **IAM Roles** (for secure access)

---

## 🚀 Architecture Overview

![Architecture Diagram]![image](https://github.com/user-attachments/assets/bb6caa59-f624-4e04-8791-00514649a435)


**User Flow:**

1. Frontend JavaScript (hosted on S3) calls a REST API.
2. API Gateway triggers Lambda functions.
3. Lambda functions interact with DynamoDB to fetch or insert student data.

---

## 📂 Project Structure

