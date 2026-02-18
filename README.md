# GenAI Serverless Exam Generator

## Overview
This project demonstrates how to build a **Serverless Generative AI Application** on AWS that automatically generates exams from lecture content. It leverages **Amazon Bedrock** for large language models (LLMs) and **AWS Lambda** for serverless compute, deployed using the **AWS Serverless Application Model (AWS SAM)**.

Educators can upload lecture files (PDFs), and the system generates multiple-choice and true/false questions. Learners can then take these exams via a simple UI, with immediate feedback.

## Architecture
- **Amazon Bedrock** – Access to foundation models like Anthropic Claude 3.5 Sonnet and Amazon Nova Pro
- **AWS Lambda** – Exam generation and exam-taking functions
- **AWS Fargate + Streamlit** – Frontend UI for educators and learners
- **Amazon S3** – Storage for lecture files and generated question banks
- **Amazon API Gateway & Load Balancer** – API management and traffic distribution

## Features
- Automated exam generation from lecture PDFs
- Multiple-choice and true/false question formats
- Chain-of-Thought prompting for better reasoning
- Immediate learner feedback
- Serverless, scalable, and cost-efficient architecture

## Learning Outcomes
- Architecting serverless GenAI applications on AWS
- Customizing Lambda functions to interact with Bedrock models
- Best practices in prompt engineering (including Chain-of-Thought prompting)
- Deploying with AWS SAM and integrating multiple AWS services

## Benefits
- Saves educators time in creating high-quality assessments
- Provides scalable, automated exam generation
- Demonstrates practical use of Generative AI in education
---

### 🚀 Quick Start
Follow the workshop guide to deploy using AWS SAM and test locally with Streamlit:
https://catalog.us-east-1.prod.workshops.aws/workshops/14e795ec-e566-4a34-855b-aa6019e54dd8/en-US
---
