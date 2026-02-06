# Skinfinity – AI-Powered Skin Care Consultant (System Design Project)

Skinfinity is an academic system analysis and design project that proposes an AI-powered skincare consultation platform. The project focuses on **requirements engineering, user-centric design, cloud-based system architecture, security, scalability, and agile delivery**, rather than on production-ready code.

**Course:** Advanced System Analysis & Design  
**Institution:** University of South Florida – Muma College of Business

---

## Project Overview
The skincare industry offers an overwhelming number of products and conflicting recommendations, making it difficult for users to identify routines that suit their individual skin needs. Skinfinity addresses this problem by proposing an AI-driven platform that analyzes facial images and user-provided data to deliver **personalized skincare insights and recommendations**.

The system is designed as a **secure, scalable, cloud-native microservices architecture** that supports AI analysis, user profiles, product recommendations, and dermatologist consultations.

---

## Objectives
- Reduce trial-and-error in skincare routines through AI-driven analysis
- Provide personalized, data-driven skincare recommendations
- Support scalable deployment using cloud-based microservices
- Ensure strong security and privacy controls for sensitive user data
- Deliver an intuitive, mobile-friendly user experience

---

## Key System Features
- AI-based facial image analysis (acne, dryness, pigmentation, redness)
- Personalized skincare product and routine recommendations
- User profile and questionnaire-driven customization
- Dermatologist consultation booking
- Progress tracking over time
- Secure payment processing for premium services

---

## System Architecture
Skinfinity is designed using a **microservices-based architecture** deployed on AWS. Each core function is implemented as an independent service with its own database and API.

**Architecture Highlights**
- API Gateway for request routing
- Independent services for:
  - User Profile Management
  - Image Analysis
  - Recommendation Engine
  - Product Catalog
  - Consultation Booking
  - Payment Processing
  - Progress Tracking
  - Notifications & Feedback
- Event-driven communication using RabbitMQ / Kafka
- Serverless components (AWS Lambda) for background processing

---

## Technology Stack (Proposed)
- **Backend:** Java (Spring Boot)
- **AI / ML:** Python (Scikit-Learn, TensorFlow)
- **Frontend:** Angular (TypeScript)
- **Databases:** PostgreSQL (AWS RDS), MongoDB Atlas, DynamoDB
- **Cloud & DevOps:** AWS (S3, ECS, Lambda, API Gateway, IAM)
- **Messaging:** RabbitMQ / Kafka
- **Security:** OAuth 2.0, JWT, AES-256 encryption, AWS IAM

---

## Security & Scalability
- End-to-end encryption for data at rest and in transit
- Role-based access control (RBAC)
- Web application firewall (AWS WAF)
- Auto-scaling and load balancing
- Containerization with Docker and Kubernetes
- Fault-tolerant, highly available architecture

---

## Agile Delivery Approach
- Scrum-based Agile methodology
- 2-week sprint cycles
- Iterative prototyping and continuous feedback
- Tools used: JIRA, GitHub, Zoom
- Sprint focus areas included authentication, AI analysis, recommendations, and performance optimization

---

## Repository Contents
- `docs/Skinfinity_Final_Project_Report.pdf` — Comprehensive system analysis, architecture design, and project documentation

---

## Notes
This repository represents **system design and architectural planning** only.  
It does not include production code or trained AI models.

---

## Team & Contributions
Team project completed as part of the Advanced System Analysis & Design course. Contributions included requirements analysis, system architecture design, security planning, scalability strategy, UX considerations, and documentation.

---

## Design & Prototype Links

The following Figma links showcase the user-centric design process for the Skinfinity application, including wireframes, high-fidelity designs, and an interactive prototype.

- **Low-Fidelity Design:**  
  https://www.figma.com/design/jttruvRwnI6KY20s2IuT0U/Skinfinity--User-Centric-Design?node-id=0-1&p=f&t=jTspkFt1l8Bdq50e-0

- **High-Fidelity Design:**  
  https://www.figma.com/design/jttruvRwnI6KY20s2IuT0U/Skinfinity--User-Centric-Design?node-id=1-2&p=f&t=jTspkFt1l8Bdq50e-0

- **Interactive High-Fidelity Prototype:**  
  https://www.figma.com/proto/jttruvRwnI6KY20s2IuT0U/Skinfinity--User-Centric-Design?node-id=122-2&p=f&t=HDdB0IGMZAVH3FnF-1&scaling=scale-down&content-scaling=fixed&page-id=1%3A2&starting-point-node-id=122%3A2


---

## License
This project is licensed under the MIT License.
