<h1 align="center">Jair Paredes Altamirano</h1>

<p align="center">
  <b>Backend-focused Full Stack Developer</b> · Node.js · NestJS · TypeScript · Microservices<br/>
  Ambato, Ecuador (UTC-5) · Working remotely with US teams
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/jiir-coon-dev"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
  <a href="mailto:jparedes1270@gmail.com"><img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/></a>
</p>

---

## About me

I'm a backend-focused developer with 2+ years of experience building production microservices. I currently work fully remote for a Miami-based POS platform. There I own the messaging service (Telnyx) and the third-party ordering integrations (Deliverect, OrderOut).

- I design services with **hexagonal architecture**, **Kafka**, **BullMQ** and **Redis**.
- I care about measurable performance: startup times, query latency and stable systems under load.
- I work async and documentation-first across US time zones.
- I build AI-powered features and use **Claude Code** every day.
- Spanish (native) · English (C1)

## Highlights

| Impact | Result |
|---|---|
| Service cold start | **13.77 s → 6.10 s** (-55.7%) |
| Service warm start | **12.79 s → 4.97 s** (-61.1%) |
| Heavy SQL query | **5 min → < 10 s** (>96% faster) |
| Physical inventory count (AI voice system) | **3 days → 1 day** |
| Promotion setup (ERP campaign engine) | about **1 minute** per campaign |

## What I'm working on

- **Telnyx messaging microservice (NestJS):** the company's first fully decoupled service without Kafka. It includes toll-free number certification, resend control and abuse protection.
- **Ordering integrations:** I'm technical lead for the Deliverect integration. I also led the refactor that lets it accept any external provider, such as OrderOut.
- **Platform stability:** fixing concurrent processes, adding Redis caching, stress testing, and merging microservices to remove a Kafka anti-pattern.

## Tech stack

**Backend**
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white)
![NestJS](https://img.shields.io/badge/NestJS-E0234E?style=flat-square&logo=nestjs&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Express](https://img.shields.io/badge/Express-000000?style=flat-square&logo=express&logoColor=white)
![.NET](https://img.shields.io/badge/.NET_Core-512BD4?style=flat-square&logo=dotnet&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)

**Messaging, queues and data**
![Kafka](https://img.shields.io/badge/Kafka-231F20?style=flat-square&logo=apachekafka&logoColor=white)
![BullMQ](https://img.shields.io/badge/BullMQ-DC382D?style=flat-square&logo=redis&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white)
![MariaDB](https://img.shields.io/badge/MariaDB-003545?style=flat-square&logo=mariadb&logoColor=white)
![Oracle](https://img.shields.io/badge/Oracle-F80000?style=flat-square&logo=oracle&logoColor=white)
![DynamoDB](https://img.shields.io/badge/DynamoDB-4053D6?style=flat-square&logo=amazondynamodb&logoColor=white)

**Frontend and mobile**
![Angular](https://img.shields.io/badge/Angular-DD0031?style=flat-square&logo=angular&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![React Native](https://img.shields.io/badge/React_Native-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![Flutter](https://img.shields.io/badge/Flutter-02569B?style=flat-square&logo=flutter&logoColor=white)
![Electron](https://img.shields.io/badge/Electron-47848F?style=flat-square&logo=electron&logoColor=white)
![Three.js](https://img.shields.io/badge/Three.js-000000?style=flat-square&logo=threedotjs&logoColor=white)

**DevOps, cloud and quality**
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Nginx](https://img.shields.io/badge/Nginx-009639?style=flat-square&logo=nginx&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonwebservices&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)
![Jenkins](https://img.shields.io/badge/Jenkins-D24939?style=flat-square&logo=jenkins&logoColor=white)
![Jest](https://img.shields.io/badge/Jest-C21325?style=flat-square&logo=jest&logoColor=white)
![Gatling](https://img.shields.io/badge/Gatling-FF9E2A?style=flat-square&logo=gatling&logoColor=white)

**AI and automation**
![Claude](https://img.shields.io/badge/Claude_Code-D97757?style=flat-square&logo=claude&logoColor=white)
![Gemini](https://img.shields.io/badge/Gemini_API-8E75B2?style=flat-square&logo=googlegemini&logoColor=white)
![n8n](https://img.shields.io/badge/n8n-EA4B71?style=flat-square&logo=n8n&logoColor=white)
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=flat-square&logo=opencv&logoColor=white)
![MediaPipe](https://img.shields.io/badge/MediaPipe-0097A7?style=flat-square&logo=google&logoColor=white)

**Integrations:** Telnyx · Deliverect · OrderOut · Olo · Payphone · WhatsApp Business · OAuth 2 · JWT

## Selected projects

| Project | Description | Stack |
|---|---|---|
| **AI Voice Inventory System** | Inventory system with an AI voice module that parses spoken counts. It cut physical counts from 3 days to 1 and keeps a full audit trail. | Node.js · PostgreSQL · React · React Native · n8n · Gemini API |
| **Ticketing Backend** | Ticket sales and validation with Payphone payments. It uses pessimistic locks to prevent double-spend, plus rate limiting and timing-attack defenses. | NestJS · PostgreSQL |
| **Smart CRM** | CRM with n8n automation, WhatsApp Business messaging and sales-rep performance analytics. | React · Node.js · n8n |
| **ERP Campaign & Inventory Engine** | A configurable promotion engine and a warehouse module with real-time stock traceability. | Angular · NestJS · .NET Core · BullMQ |
| **3D Taekwondo Body Tracking** (thesis) | Multi-camera 3D body tracking for automatic analysis of kicking technique. | Python · OpenCV · MediaPipe · YOLO-Pose · Electron · Three.js |

## Experience

- **Full Stack Developer (Backend focus)**, Juvo Systems. Remote, Miami. *Nov 2025 – Present*
- **Full Stack Developer**, Setcasoft (ERP software). Ambato, Ecuador. *Jan 2024 – Jun 2025*

## Education

**Software Engineering**, Universidad Técnica de Ambato (2021 – 2026)

---

<p align="center">
  <i>Open to remote backend and full stack roles. Let's build something reliable.</i>
</p>
