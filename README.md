# ☁️ AWS-Projects

Welcome to my AWS Projects repository! This collection showcases practical projects I've built while preparing for the **AWS Certified Cloud Practitioner** exam. Each project demonstrates the use of core AWS services to solve real-world problems and gain hands-on experience with cloud computing.

---

## 📚 About

I am currently learning AWS and preparing for the **AWS Certified Cloud Practitioner** certification. These projects are part of my journey to:
- Build a strong foundation in cloud concepts
- Gain hands-on experience with core AWS services
- Understand real-world cloud architecture and deployment practices

---

## 🚀 Projects

### 🌐 1. Automated AWS Receipt Processing System
- **Description:** Built a serverless receipt processing system that extracts, stores, and emails data from uploaded receipts.
- How it Works:

User uploads a receipt image to Amazon S3

An S3 trigger invokes a Lambda function

Lambda calls Amazon Textract to extract text data from the receipt

Extracted data is structured and sent back to Lambda

Lambda stores the data in Amazon DynamoDB

Lambda also sends an email with the processed data via Amazon SES
- **AWS Services:** S3, Lambda, Textract, DynamoDB, SES
- **Skills Gained:** Event-driven serverless architecture, text extraction with Textract, working with structured data, email notifications using SES
