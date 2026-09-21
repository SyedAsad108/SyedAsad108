## 👨‍💻 About Me

I'm a **B.Tech Information Technology student** interested in building and understanding the systems behind modern software.

My primary focus is **cloud and backend engineering**, with hands-on experience building applications around AWS, event-driven architectures, serverless systems, data pipelines, and infrastructure as code.

I'm particularly interested in:

* ☁️ **Cloud Engineering & AWS**
* ⚙️ **Backend & Distributed Systems**
* 📊 **Data Engineering**
* 🏗️ **Infrastructure as Code & DevOps**
* 🤖 **Artificial Intelligence & Machine Learning**

I like understanding what happens beyond the application layer — **how services communicate, how data flows through a system, how infrastructure is provisioned, how systems scale, and how different architectural decisions affect performance and reliability.**

Currently, I'm expanding into **AI engineering**, while strengthening my foundations in **Python, algorithms, backend development, system design, and deep learning**.

---

## ☁️ AWS Certifications

<p align="center">
  <img src="https://img.shields.io/badge/AWS_Certified-Data_Engineer_Associate-232F3E?style=for-the-badge&logo=amazon-aws&logoColor=white" />
  <img src="https://img.shields.io/badge/AWS_Certified-Developer_Associate-232F3E?style=for-the-badge&logo=amazon-aws&logoColor=white" />
  <img src="https://img.shields.io/badge/AWS_Certified-AI_Practitioner-232F3E?style=for-the-badge&logo=amazon-aws&logoColor=white" />
  <img src="https://img.shields.io/badge/AWS_Certified-Cloud_Practitioner-232F3E?style=for-the-badge&logo=amazon-aws&logoColor=white" />
</p>

---

# 🚀 Featured Projects

## 🏭 AutoForge — Smart Manufacturing Data Intelligence Platform

A **cloud-native industrial telemetry and analytics platform** built around an event-driven data pipeline.

AutoForge simulates a factory environment, continuously generates machine telemetry, processes the data through a streaming pipeline, and exposes operational insights through a web dashboard.

### What I built

* Simulated telemetry from **24 industrial machines**
* Processed **243K+ sensor events**
* Built an asynchronous Python-based factory simulator
* Implemented real-time ingestion using **Amazon Kinesis**
* Added Lambda-based telemetry validation and anomaly detection
* Designed an **Amazon S3 data lake** for raw telemetry
* Built ETL pipelines using **AWS Glue**
* Created curated, analytics-ready datasets
* Queried telemetry using **Amazon Athena**
* Built analytics APIs using **FastAPI**
* Developed a React dashboard for machine health and operational insights
* Provisioned infrastructure using **Terraform**

### Architecture

```text
Industrial IoT Simulator
        │
        ▼
   FastAPI Backend
        │
        ▼
   Amazon Kinesis
        │
        ▼
      Lambda
        │
        ▼
     S3 Raw
        │
        ▼
    AWS Glue
        │
        ▼
  S3 Curated
        │
        ▼
    Athena
        │
        ▼
   FastAPI APIs
        │
        ▼
   React Dashboard
```

**Tech:** `Python` `FastAPI` `Kinesis` `Lambda` `S3` `Glue` `Athena` `Terraform` `React` `Docker`

---

## 🔐 SecureShare — Secure File Upload & Sharing

A secure cloud-based file-sharing application designed around **direct object-storage uploads** and controlled file access.

### Key concepts

* Direct client-to-S3 uploads using **pre-signed URLs**
* Backend-controlled authorization
* Time-limited file access
* Least-privilege IAM policies
* REST APIs for users and file operations
* Separation of application traffic from large file transfers

**Tech:** `React` `Node.js` `Express.js` `MongoDB` `Amazon S3` `AWS IAM`

---

## 💬 Serverless Real-Time Chat

A real-time messaging application built using **AWS serverless and WebSocket infrastructure**.

### Architecture

```text
React Client
     │
     ▼
API Gateway WebSocket
     │
     ▼
   Lambda
     │
     ▼
  DynamoDB
```

### Implemented

* Real-time WebSocket communication
* WebSocket connection management
* Message persistence
* JWT-based authentication
* DynamoDB data modelling
* Serverless backend architecture
* Real-time message delivery

**Tech:** `React` `Node.js` `Lambda` `API Gateway` `WebSockets` `DynamoDB`

---

# 🛠️ Technical Stack

### ☁️ Cloud & Infrastructure

<p>
<img src="https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazon-aws&logoColor=FF9900" />
<img src="https://img.shields.io/badge/Terraform-5835CC?style=for-the-badge&logo=terraform&logoColor=white" />
<img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" />
<img src="https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=github-actions&logoColor=white" />
</p>

**AWS:** `EC2` `S3` `Lambda` `API Gateway` `DynamoDB` `Kinesis` `Glue` `Athena` `SNS` `SQS` `CloudWatch` `IAM`

### ⚙️ Backend & Data

<p>
<img src="https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white" />
<img src="https://img.shields.io/badge/Express.js-000000?style=for-the-badge&logo=express&logoColor=white" />
<img src="https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white" />
<img src="https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white" />
<img src="https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white" />
</p>

### 💻 Languages

<p>
<img src="https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white" />
<img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" />
<img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" />
<img src="https://img.shields.io/badge/C-A8B9CC?style=for-the-badge&logo=c&logoColor=black" />
</p>

### 🎨 Frontend

<p>
<img src="https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB" />
<img src="https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=next.js&logoColor=white" />
<img src="https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=for-the-badge&logo=tailwind-css&logoColor=white" />
</p>

---

# 📊 Languages

<p align="center">
  <img
    src="https://github-readme-stats.vercel.app/api/top-langs/?username=SyedAsad108&layout=compact&theme=tokyonight&hide_border=true&langs_count=8"
    width="55%"
    alt="Most Used Languages"
  />
</p>

> Language statistics are automatically generated from my GitHub repositories.

---

# 🧠 Currently Learning

### 🤖 AI Engineering

* Neural Networks
* Computational Graphs
* Forward & Backward Propagation
* Gradient Descent
* Backpropagation
* PyTorch
* Deep Learning
* LLMs & Generative AI

### ☁️ Cloud & Systems

* AWS Architecture
* Terraform & Infrastructure as Code
* Docker & Containerization
* CI/CD
* Distributed Systems
* Event-Driven Architecture
* System Design

### 💻 Software Engineering

* Data Structures & Algorithms
* Backend Engineering
* Python
* Database Design
* Scalable Application Architecture

Currently working through the fundamentals of **neural networks and deep learning**, with a focus on understanding the mathematics and implementation behind the abstractions rather than treating ML frameworks as black boxes.

---

# 🏗️ Engineering Interests

<p align="center">
  <img src="https://img.shields.io/badge/Cloud_Architecture-232F3E?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Distributed_Systems-444444?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Event--Driven_Architecture-555555?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Serverless-FF5757?style=for-the-badge" />
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Data_Engineering-1F6FEB?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Infrastructure_as_Code-5835CC?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Backend_Engineering-339933?style=for-the-badge" />
  <img src="https://img.shields.io/badge/System_Design-444444?style=for-the-badge" />
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Artificial_Intelligence-412991?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Machine_Learning-FF6F00?style=for-the-badge" />
</p>

---

# 📈 GitHub Activity

<p align="center">
  <img
    src="https://github-readme-stats.vercel.app/api?username=SyedAsad108&show_icons=true&theme=tokyonight&hide_border=true&count_private=true"
    width="48%"
    alt="GitHub Statistics"
  />

<img
 src="https://github-readme-stats.vercel.app/api/top-langs/?username=SyedAsad108&layout=compact&theme=tokyonight&hide_border=true&langs_count=8"
 width="48%"
 alt="Top Languages"
/>

</p>

<p align="center">
  <img
    src="https://github-readme-activity-graph.vercel.app/graph?username=SyedAsad108&theme=tokyo-night&hide_border=true&bg_color=1a1b27"
    width="100%"
    alt="GitHub Contribution Graph"
  />
</p>

---

# 📫 Connect With Me

<p align="center">
  <a href="https://www.linkedin.com/in/sysedasad/">
    <img src="https://img.shields.io/badge/LinkedIn-Syed_Asad_Ahmad-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" />
  </a>

  <a href="https://github.com/SyedAsad108">
    <img src="https://img.shields.io/badge/GitHub-SyedAsad108-181717?style=for-the-badge&logo=github&logoColor=white" />
  </a>
</p>

<p align="center">
  <i>Building systems, learning the fundamentals, and turning ideas into working software.</i>
</p>
