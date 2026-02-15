# AwasAI – System Architecture (AI for Bharat Submission)

## High-Level Architecture

Frontend:
- React / Next.js Responsive Web Application

Backend:
- Node.js / Express API Layer

Database:
- PostgreSQL (deployable on AWS RDS or cloud-managed service)

Cloud Infrastructure (AWS-Oriented Design):

- Amazon EC2 for application hosting
- Amazon S3 for image storage
- Amazon CloudFront for CDN
- Amazon RDS for relational database
- Amazon Cognito for authentication
- Amazon SageMaker for AI model hosting
- AWS Lambda for serverless AI processing
- AWS API Gateway for secure API exposure

---

## Core System Modules

### 1. Authentication & Verification Service
- Amazon Cognito for user management
- Identity verification workflow
- Secure login and role-based access

### 2. AI Recommendation Engine
- Hosted using Amazon SageMaker
- Personalized stay suggestions
- Adaptive learning model

### 3. Itinerary Generation Engine
- AWS Lambda-based processing
- Generates optimized day-wise travel plan
- Uses user preferences & location inputs

### 4. Booking Management Module
- Availability tracking
- Booking confirmation workflow
- Secure payment gateway integration

### 5. Shared Living Module
- Monthly rental listing system
- Roommate matching logic
- Application and approval workflow

### 6. Fraud Detection & Trust Layer
- Behavioral anomaly detection
- Trust scoring algorithm
- Report & moderation system

---

## Scalability Strategy

- Auto Scaling Groups
- Elastic Load Balancer
- Microservices-ready architecture
- Cloud-native deployment model

---

## Security & Compliance

- Encrypted passwords
- Secure API access via API Gateway
- IAM role-based access control
- Data privacy compliance
- Secure storage policies

---

## Deployment Model

- CI/CD ready
- Containerization compatible
- Cloud-agnostic adaptable architecture
