<h1 align="center">Syed Asad Ahmad</h1>

<p align="center">
  <b>Cloud &amp; Backend Engineering</b> · <b>Data Engineering</b> · <b>AI Engineering</b>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazonwebservices&logoColor=FF9900" alt="AWS" />
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python" />
  <img src="https://img.shields.io/badge/Terraform-7B42BC?style=for-the-badge&logo=terraform&logoColor=white" alt="Terraform" />
  <img src="https://img.shields.io/badge/Serverless-FD5750?style=for-the-badge&logo=awslambda&logoColor=white" alt="Serverless" />
</p>

---

## About Me

I'm a **B.Tech Information Technology student** interested in building and understanding the systems behind modern software.

My primary focus is **cloud and backend engineering**, with hands-on experience building applications around AWS, event-driven architectures, serverless systems, data pipelines, and infrastructure as code.

I'm particularly interested in:

- **Cloud Engineering &amp; AWS**
- **Backend &amp; Distributed Systems**
- **Data Engineering**
- **Infrastructure as Code &amp; DevOps**
- **Artificial Intelligence &amp; Machine Learning**

I like understanding what happens beyond the application layer — how services communicate, how data flows through a system, how infrastructure is provisioned, how systems scale, and how architectural decisions affect performance and reliability.

Currently, I'm expanding into **AI engineering**, while strengthening my foundations in Python, algorithms, backend development, system design, and deep learning.

---

## AWS Certifications

<p align="center">
  <img src="https://img.shields.io/badge/AWS_Certified-Data_Engineer_Associate-232F3E?style=for-the-badge&logo=amazonwebservices&logoColor=FF9900" alt="AWS Certified Data Engineer - Associate" />
  <img src="https://img.shields.io/badge/AWS_Certified-Developer_Associate-232F3E?style=for-the-badge&logo=amazonwebservices&logoColor=FF9900" alt="AWS Certified Developer - Associate" />
  <img src="https://img.shields.io/badge/AWS_Certified-AI_Practitioner-232F3E?style=for-the-badge&logo=amazonwebservices&logoColor=FF9900" alt="AWS Certified AI Practitioner" />
  <img src="https://img.shields.io/badge/AWS_Certified-Cloud_Practitioner-232F3E?style=for-the-badge&logo=amazonwebservices&logoColor=FF9900" alt="AWS Certified Cloud Practitioner" />
</p>

---

## Featured Projects

### AutoForge — Smart Manufacturing Data Intelligence Platform

A **cloud-native industrial telemetry and analytics platform** built around an event-driven data pipeline. AutoForge simulates a factory environment, continuously generates machine telemetry, processes the data through a streaming pipeline, and exposes operational insights through a web dashboard.

<table>
  <tr>
    <td><b>Machines simulated</b></td>
    <td>24</td>
  </tr>
  <tr>
    <td><b>Sensor events processed</b></td>
    <td>243K+</td>
  </tr>
  <tr>
    <td><b>Pipeline</b></td>
    <td>Streaming ingest → validation → data lake → ETL → analytics</td>
  </tr>
</table>

**What I built**

- Asynchronous Python factory simulator generating telemetry from 24 industrial machines
- Real-time ingestion with **Amazon Kinesis**
- **Lambda**-based telemetry validation and anomaly detection
- **Amazon S3** data lake for raw telemetry
- ETL pipelines with **AWS Glue** producing curated, analytics-ready datasets
- Ad-hoc querying over curated data with **Amazon Athena**
- Analytics APIs with **FastAPI** and a **React** dashboard for machine health and operational insights
- Infrastructure provisioned with **Terraform**

**Architecture**

```text
IoT Simulator → FastAPI → Kinesis → Lambda → S3 (raw)
                                               │
                                               ▼
     React Dashboard ← FastAPI APIs ← Athena ← S3 (curated) ← Glue
```

**Tech:** `Python` `FastAPI` `Kinesis` `Lambda` `S3` `Glue` `Athena` `Terraform` `React` `Docker`

---

### SecureShare — Secure File Upload &amp; Sharing

A secure cloud-based file-sharing application designed around **direct object-storage uploads** and controlled file access.

**Key concepts**

- Direct client-to-S3 uploads using **pre-signed URLs**
- Backend-controlled authorization and time-limited file access
- Least-privilege **IAM** policies
- REST APIs for user and file operations
- Separation of application traffic from large file transfers

**Tech:** `React` `Node.js` `Express.js` `MongoDB` `Amazon S3` `AWS IAM`

---

### Serverless Real-Time Chat

A real-time messaging application built on **AWS serverless and WebSocket infrastructure**.

**Architecture**

```text
React Client → API Gateway (WebSocket) → Lambda → DynamoDB
```

**Implemented**

- Real-time WebSocket communication and connection management
- Message persistence and DynamoDB data modelling
- JWT-based authentication
- Fully serverless backend architecture

**Tech:** `React` `Node.js` `Lambda` `API Gateway` `WebSockets` `DynamoDB`

---

## Technical Stack

**Cloud &amp; Infrastructure**

<p>
  <img src="https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazonwebservices&logoColor=FF9900" alt="AWS" />
  <img src="https://img.shields.io/badge/Terraform-7B42BC?style=for-the-badge&logo=terraform&logoColor=white" alt="Terraform" />
  <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" alt="Docker" />
  <img src="https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white" alt="GitHub Actions" />
</p>

`EC2` `S3` `Lambda` `API Gateway` `DynamoDB` `Kinesis` `Glue` `Athena` `SNS` `SQS` `CloudWatch` `IAM`

**Backend &amp; Data**

<p>
  <img src="https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white" alt="Node.js" />
  <img src="https://img.shields.io/badge/Express.js-000000?style=for-the-badge&logo=express&logoColor=white" alt="Express.js" />
  <img src="https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white" alt="FastAPI" />
  <img src="https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white" alt="MongoDB" />
  <img src="https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white" alt="MySQL" />
</p>

**Languages**

<p>
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python" />
  <img src="https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white" alt="Java" />
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" alt="JavaScript" />
  <img src="https://img.shields.io/badge/C-A8B9CC?style=for-the-badge&logo=c&logoColor=black" alt="C" />
</p>

**Frontend**

<p>
  <img src="https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB" alt="React" />
  <img src="https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white" alt="Next.js" />
  <img src="https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white" alt="Tailwind CSS" />
</p>

---

## Currently Learning

<table>
  <tr>
    <th align="left">AI Engineering</th>
    <th align="left">Cloud &amp; Systems</th>
    <th align="left">Software Engineering</th>
  </tr>
  <tr valign="top">
    <td>
      Neural networks<br />
      Computational graphs<br />
      Forward &amp; backward propagation<br />
      Gradient descent &amp; backpropagation<br />
      PyTorch &amp; deep learning<br />
      LLMs &amp; generative AI
    </td>
    <td>
      AWS architecture<br />
      Terraform &amp; IaC<br />
      Docker &amp; containerization<br />
      CI/CD<br />
      Distributed systems<br />
      Event-driven architecture &amp; system design
    </td>
    <td>
      Data structures &amp; algorithms<br />
      Backend engineering<br />
      Python<br />
      Database design<br />
      Scalable application architecture
    </td>
  </tr>
</table>

Currently working through the fundamentals of **neural networks and deep learning**, focusing on the mathematics and implementation behind the abstractions rather than treating ML frameworks as black boxes.

---

## Engineering Interests

<p align="center">
  <img src="https://img.shields.io/badge/Cloud_Architecture-232F3E?style=for-the-badge" alt="Cloud Architecture" />
  <img src="https://img.shields.io/badge/Distributed_Systems-444444?style=for-the-badge" alt="Distributed Systems" />
  <img src="https://img.shields.io/badge/Event--Driven_Architecture-555555?style=for-the-badge" alt="Event-Driven Architecture" />
  <img src="https://img.shields.io/badge/Serverless-FF5757?style=for-the-badge" alt="Serverless" />
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Data_Engineering-1F6FEB?style=for-the-badge" alt="Data Engineering" />
  <img src="https://img.shields.io/badge/Infrastructure_as_Code-5835CC?style=for-the-badge" alt="Infrastructure as Code" />
  <img src="https://img.shields.io/badge/Backend_Engineering-339933?style=for-the-badge" alt="Backend Engineering" />
  <img src="https://img.shields.io/badge/System_Design-444444?style=for-the-badge" alt="System Design" />
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Artificial_Intelligence-412991?style=for-the-badge" alt="Artificial Intelligence" />
  <img src="https://img.shields.io/badge/Machine_Learning-FF6F00?style=for-the-badge" alt="Machine Learning" />
</p>

---

## GitHub Activity

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=SyedAsad108&show_icons=true&theme=tokyonight&hide_border=true&count_private=true" width="48%" alt="GitHub Statistics" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=SyedAsad108&layout=compact&theme=tokyonight&hide_border=true&langs_count=8" width="48%" alt="Most Used Languages" />
</p>

<p align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=SyedAsad108&theme=tokyo-night&hide_border=true" width="98%" alt="GitHub Contribution Graph" />
</p>

<p align="center"><sub>Language statistics are generated automatically from my public GitHub repositories.</sub></p>

---

## Connect With Me

<p align="center">
  <a href="https://www.linkedin.com/in/sysedasad/">
    <img src="https://img.shields.io/badge/LinkedIn-Syed_Asad_Ahmad-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" />
  </a>
  <a href="https://github.com/SyedAsad108">
    <img src="https://img.shields.io/badge/GitHub-SyedAsad108-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub" />
  </a>
</p>

<p align="center"><i>Building systems, learning the fundamentals, and turning ideas into working software.</i></p>
