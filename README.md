<h1 align="center">Hi, I'm Syed Asad Ahmad 👋</h1>

<p align="center">
  <b>Backend Engineering</b> · <b>Distributed Systems</b> · <b>DevOps &amp; Cloud</b> · <b>Data Engineering</b> · <b>AI / ML</b>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Backend-Engineering-339933?style=for-the-badge" alt="Backend Engineering" />
  <img src="https://img.shields.io/badge/AWS-Cloud-232F3E?style=for-the-badge&logo=amazonwebservices&logoColor=FF9900" alt="AWS Cloud" />
  <img src="https://img.shields.io/badge/DevOps-Terraform-7B42BC?style=for-the-badge&logo=terraform&logoColor=white" alt="DevOps and Terraform" />
  <img src="https://img.shields.io/badge/AI%2FML-Learning-412991?style=for-the-badge" alt="AI and Machine Learning" />
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/sysedasad/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
  <a href="https://github.com/SyedAsad108"><img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub" /></a>
</p>

---

## 💫 About Me

I'm a **B.Tech Information Technology student** focused on backend engineering and the systems behind modern applications.

I enjoy working close to the infrastructure — designing APIs, modelling data, connecting distributed services, building event-driven systems, and automating infrastructure and deployments.

**Current focus:**

- ⚙️ &nbsp;**Backend Engineering &amp; Distributed Systems**
- ☁️ &nbsp;**AWS &amp; Cloud-Native Architecture**
- 🔄 &nbsp;**DevOps, CI/CD &amp; Infrastructure as Code**
- 📊 &nbsp;**Data Engineering &amp; Streaming Pipelines**
- 🤖 &nbsp;**Artificial Intelligence &amp; Machine Learning**

I like understanding **how systems actually work** — how requests move through services, how data is stored and processed, how services communicate asynchronously, how infrastructure is provisioned, and how architectural decisions affect scalability and reliability.

Currently expanding into **AI/ML**, while strengthening my foundations in Python, algorithms, system design, and deep learning.

---

## 🚀 Featured Projects

### 🧠 IncidentGraph — AI-Assisted Incident Investigation Platform

An incident investigation and correlation platform designed to help engineers move from **CloudWatch alarms → correlated evidence → investigation reports**. It combines AWS observability, deterministic correlation, workload-aware context, and optional AI reasoning through Amazon Bedrock or Gemini.

**Highlights**

- 🚨 Detects infrastructure incidents from **CloudWatch Alarm state changes**
- 🔗 Correlates metrics, logs, deployments, topology, and historical incidents
- 🤖 AI-assisted investigation using **Amazon Bedrock / Gemini**
- 🛠️ Tool-based investigation with metrics, logs, topology, runbooks, and incident history
- 📚 Workload-aware architecture using configurable service and dependency definitions
- 🧪 Includes a dedicated **IncidentGraph Lab** for failure injection and load testing
- 💬 Uses a serverless real-time chat system as a reference workload
- 🏗️ Infrastructure managed with **Terraform**

<details>
<summary><b>Architecture</b></summary>

```text
CloudWatch Alarm
       │
       ▼
   EventBridge
       │
       ▼
Incident Detector
       │
       ▼
    DynamoDB
       │
       ▼
Investigation Agent
       │
       ├── Metrics
       ├── Logs
       ├── Deployments
       ├── Topology
       ├── History
       └── Runbooks
       │
       ▼
Bedrock / Gemini
       │
       ▼
Investigation Report
       │
       ▼
   Next.js UI
```

</details>

**Tech:** `AWS` `Lambda` `CloudWatch` `EventBridge` `DynamoDB` `Bedrock` `Gemini` `Terraform` `Next.js` `Node.js`

---

### 🏭 AutoForge — Smart Manufacturing Data Intelligence Platform

A cloud-native **Industry 4.0 data platform** that simulates a 24-machine manufacturing plant and processes industrial telemetry through an event-driven streaming and data-lake pipeline.

| Metric                      |            Value |
| :-------------------------- | ---------------: |
| 🏭  Machines simulated      |           **24** |
| 📊  Sensor events processed |        **243K+** |
| ⚡  Data pipeline            | **Event-driven** |
| 🏗️  Infrastructure         |    **Terraform** |

<details>
<summary><b>Architecture</b></summary>

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
     ┌────┴────┐
     ▼         ▼
  S3 Raw   Quarantine
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

</details>

**Highlights**

* Asynchronous Python simulator generating stateful telemetry from **24 industrial machines**
* Streaming ingestion through **Amazon Kinesis**
* Lambda-based validation, anomaly tagging, and diagnostic enrichment
* Raw and curated **S3 data lake** architecture
* PySpark ETL pipelines with **AWS Glue**
* Partitioned **Parquet** datasets optimized for Athena queries
* Analytics APIs built with **FastAPI**
* React-based factory dashboard / digital twin
* Infrastructure provisioned using **Terraform**
* Local development environment supported through **Docker Compose**

**Tech:** `Python` `FastAPI` `Kinesis` `Lambda` `S3` `Glue` `Athena` `Terraform` `React` `Docker`

---

### ☁️ VideoTube DevOps — Full-Stack Application & Cloud CI/CD

A full-stack video platform deployed on AWS with infrastructure-as-code and an automated **GitHub Actions CI/CD pipeline**.

<details>
<summary><b>Deployment Architecture</b></summary>

```text
              GitHub
                 │
                 ▼
        GitHub Actions CI/CD
                 │
        ┌────────┼────────┐
        ▼        ▼        ▼
     Backend  Frontend  Terraform
        │        │
        ▼        ▼
       ECR       S3
        │         │
        ▼         ▼
       ECS     CloudFront
        │
        ▼
       ALB
        │
        ▼
     Express API
        │
        ▼
    MongoDB Atlas
```

</details>

**Highlights**

* React + Vite frontend with **Express.js** backend
* Containerized backend deployed through **Amazon ECS**
* Docker images built and pushed to **Amazon ECR**
* Static frontend hosted on **Amazon S3 + CloudFront**
* Automated CI/CD using **GitHub Actions**
* AWS authentication through **OIDC**
* Terraform-managed AWS infrastructure
* Automated backend health checks and ECS deployment verification
* Separate CI stages for backend tests, frontend builds, and Terraform validation

**Tech:** `React` `Vite` `Node.js` `Express.js` `MongoDB` `Docker` `ECS` `ECR` `S3` `CloudFront` `Terraform` `GitHub Actions`

---

### 💬 Serverless Real-Time Chat

A cloud-native real-time messaging application built around **WebSockets and AWS serverless services**.

<details>
<summary><b>Architecture</b></summary>

```text
        Next.js Client
             │
       ┌─────┴─────┐
       ▼           ▼
   HTTP API    WebSocket API
       │           │
       ▼           ▼
    Lambda      Lambda
       │           │
       ▼           ▼
   DynamoDB   API Gateway
                   │
                   ▼
              Connected
               Clients
```

</details>

**Highlights**

* Real-time communication using **API Gateway WebSockets**
* Lambda handlers for connection, disconnection, authentication, and messaging
* JWT-based authentication
* WebSocket connection tracking in **DynamoDB**
* Real-time message broadcasting through the API Gateway Management API
* Fully serverless backend architecture

**Tech:** `Next.js` `React` `TypeScript` `AWS Lambda` `API Gateway` `WebSockets` `DynamoDB` `JWT`

---

## 🛠️ Technical Stack

### ⚙️ Backend

<p>
  <img src="https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white" alt="Node.js" />
  <img src="https://img.shields.io/badge/Express.js-000000?style=for-the-badge&logo=express&logoColor=white" alt="Express.js" />
  <img src="https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white" alt="FastAPI" />
  <img src="https://img.shields.io/badge/REST_APIs-005571?style=for-the-badge" alt="REST APIs" />
  <img src="https://img.shields.io/badge/WebSockets-010101?style=for-the-badge" alt="WebSockets" />
</p>

### ☁️ Cloud & DevOps

<p>
  <img src="https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazonwebservices&logoColor=FF9900" alt="AWS" />
  <img src="https://img.shields.io/badge/Terraform-7B42BC?style=for-the-badge&logo=terraform&logoColor=white" alt="Terraform" />
  <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" alt="Docker" />
  <img src="https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white" alt="GitHub Actions" />
</p>

`EC2` `ECS` `ECR` `S3` `CloudFront` `Lambda` `API Gateway` `DynamoDB` `Kinesis` `Glue` `Athena` `SNS` `SQS` `IAM` `CloudWatch` `EventBridge`

### 📊 Data & Databases

<p>
  <img src="https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white" alt="MongoDB" />
  <img src="https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white" alt="MySQL" />
  <img src="https://img.shields.io/badge/Amazon_Athena-232F3E?style=for-the-badge&logo=amazonwebservices&logoColor=FF9900" alt="Amazon Athena" />
  <img src="https://img.shields.io/badge/AWS_Glue-232F3E?style=for-the-badge&logo=amazonwebservices&logoColor=FF9900" alt="AWS Glue" />
</p>

### 💻 Languages

<p>
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python" />
  <img src="https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white" alt="Java" />
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" alt="JavaScript" />
  <img src="https://img.shields.io/badge/C-A8B9CC?style=for-the-badge&logo=c&logoColor=black" alt="C" />
</p>

### 🎨 Frontend

<p>
  <img src="https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB" alt="React" />
  <img src="https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white" alt="Next.js" />
  <img src="https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white" alt="Tailwind CSS" />
</p>

---

## ☁️ AWS Certifications

<p align="center">
  <img src="https://img.shields.io/badge/AWS_Certified-Data_Engineer_Associate-232F3E?style=for-the-badge&logo=amazonwebservices&logoColor=FF9900" alt="AWS Certified Data Engineer - Associate" />
  <img src="https://img.shields.io/badge/AWS_Certified-Developer_Associate-232F3E?style=for-the-badge&logo=amazonwebservices&logoColor=FF9900" alt="AWS Certified Developer - Associate" />
  <img src="https://img.shields.io/badge/AWS_Certified-AI_Practitioner-232F3E?style=for-the-badge&logo=amazonwebservices&logoColor=FF9900" alt="AWS Certified AI Practitioner" />
  <img src="https://img.shields.io/badge/AWS_Certified-Cloud_Practitioner-232F3E?style=for-the-badge&logo=amazonwebservices&logoColor=FF9900" alt="AWS Certified Cloud Practitioner" />
</p>

---

## 🧠 Currently Learning

| 🤖 AI / ML | ⚙️ Systems &amp; Backend | 🚀 DevOps &amp; Cloud |
| :--- | :--- | :--- |
| Neural networks | Data structures &amp; algorithms | AWS architecture |
| Computational graphs | System design | Terraform |
| Backpropagation | Distributed systems | Docker |
| Gradient descent | Event-driven architecture | CI/CD |
| PyTorch | Backend architecture | Infrastructure as Code |
| Deep learning | Database design | Cloud-native systems |
| LLMs &amp; generative AI | Scalable applications | Observability |

Currently working through the fundamentals of **neural networks and deep learning**, focusing on the mathematics, computational graphs, gradients, and backpropagation behind the abstractions rather than treating ML frameworks as black boxes.

<!--
  OPTIONAL — WakaTime coding activity.
  Replace USERNAME and SHARE_ID with your own WakaTime share URL, then uncomment.

<p align="center">
  <img src="https://wakatime.com/share/@USERNAME/SHARE_ID.svg" height="450" alt="WakaTime Coding Activity" />
</p>
-->

---

## 📫 Connect With Me

<p align="center">
  <a href="https://www.linkedin.com/in/sysedasad/"><img src="https://img.shields.io/badge/LinkedIn-Syed_Asad_Ahmad-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
  <a href="https://github.com/SyedAsad108"><img src="https://img.shields.io/badge/GitHub-SyedAsad108-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub" /></a>
</p>

<p align="center"><i>Building systems. Understanding the fundamentals. Shipping software.</i></p>
