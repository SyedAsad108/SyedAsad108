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

### 🏭 AutoForge — Smart Manufacturing Data Intelligence Platform

A cloud-native industrial telemetry platform built around an **event-driven data pipeline**. AutoForge simulates a factory environment, generates machine telemetry, processes it through a streaming and ETL pipeline, and exposes operational insights through a React dashboard.

| Metric | Value |
| :--- | ---: |
| 🏭 &nbsp;Machines simulated | **24** |
| 📊 &nbsp;Sensor events processed | **243K+** |
| ⚡ &nbsp;Architecture | **Event-driven** |
| 🏗️ &nbsp;Infrastructure | **Terraform** |

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

</details>

**Highlights**

- Asynchronous Python factory simulator generating telemetry from 24 industrial machines
- Real-time telemetry ingestion with **Amazon Kinesis**
- Lambda-based telemetry validation and anomaly detection
- S3-based raw and curated data lake
- ETL pipelines built with **AWS Glue**
- Curated datasets queried through **Amazon Athena**
- Analytics APIs built with **FastAPI**
- React dashboard for machine health and operational insights
- Infrastructure provisioned with **Terraform**

**Tech:** `Python` `FastAPI` `Kinesis` `Lambda` `S3` `Glue` `Athena` `Terraform` `React` `Docker`

---

### 🔐 SecureShare — Secure File Upload &amp; Sharing System

A backend-focused file-sharing system designed around secure, direct object-storage transfers.

**Key features**

- Direct client-to-S3 uploads using **pre-signed URLs**
- Backend-controlled authorization
- Time-limited file access
- Least-privilege **IAM** policies
- REST APIs for user and file operations
- Separation of application traffic from large file transfers

**Tech:** `Node.js` `Express.js` `React` `MongoDB` `Amazon S3` `AWS IAM`

---

### 💬 Serverless Real-Time Chat

A real-time messaging system built around **WebSockets and AWS serverless infrastructure**.

<details>
<summary><b>Architecture</b></summary>

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

</details>

**Highlights**

- Real-time WebSocket communication and connection management
- Real-time message delivery with persistence
- JWT-based authentication
- DynamoDB data modelling
- Fully serverless backend architecture

**Tech:** `Node.js` `React` `AWS Lambda` `API Gateway` `WebSockets` `DynamoDB`

---

## 🛠️ Technical Stack

**⚙️ Backend**

<p>
  <img src="https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white" alt="Node.js" />
  <img src="https://img.shields.io/badge/Express.js-000000?style=for-the-badge&logo=express&logoColor=white" alt="Express.js" />
  <img src="https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white" alt="FastAPI" />
  <img src="https://img.shields.io/badge/REST_APIs-005571?style=for-the-badge" alt="REST APIs" />
  <img src="https://img.shields.io/badge/WebSockets-010101?style=for-the-badge" alt="WebSockets" />
</p>

**☁️ Cloud &amp; DevOps**

<p>
  <img src="https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazonwebservices&logoColor=FF9900" alt="AWS" />
  <img src="https://img.shields.io/badge/Terraform-7B42BC?style=for-the-badge&logo=terraform&logoColor=white" alt="Terraform" />
  <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" alt="Docker" />
  <img src="https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white" alt="GitHub Actions" />
</p>

`EC2` `S3` `Lambda` `API Gateway` `DynamoDB` `Kinesis` `Glue` `Athena` `SNS` `SQS` `IAM` `CloudWatch`

**📊 Data &amp; Databases**

<p>
  <img src="https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white" alt="MongoDB" />
  <img src="https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white" alt="MySQL" />
  <img src="https://img.shields.io/badge/Amazon_Athena-232F3E?style=for-the-badge&logo=amazonwebservices&logoColor=FF9900" alt="Amazon Athena" />
  <img src="https://img.shields.io/badge/AWS_Glue-232F3E?style=for-the-badge&logo=amazonwebservices&logoColor=FF9900" alt="AWS Glue" />
</p>

**💻 Languages**

<p>
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python" />
  <img src="https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white" alt="Java" />
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" alt="JavaScript" />
  <img src="https://img.shields.io/badge/C-A8B9CC?style=for-the-badge&logo=c&logoColor=black" alt="C" />
</p>

**🎨 Frontend**

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

---

## 📈 GitHub Activity

<p align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=SyedAsad108&theme=tokyo-night&hide_border=true" width="95%" alt="GitHub Contribution Graph" />
</p>

<!--
  OPTIONAL — self-hosted stats cards.
  Uncomment only after a GitHub Actions workflow generates
  profile/stats.svg and profile/top-langs.svg in this repository.
  Until those files exist, these images render as broken links.

<p align="center">
  <img src="./profile/stats.svg" height="180" alt="GitHub Statistics" />
  <img src="./profile/top-langs.svg" height="180" alt="Top Languages" />
</p>
-->

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
