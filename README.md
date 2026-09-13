# 👋🏾 Moses Jasi

### Senior Product Engineer · FinTech · Backend · AI Engineering

> **Building financial infrastructure, intelligent systems, and products that solve real-world problems.**

I’m a **Senior Product Engineer** focused on building production-grade systems across **payments, financial infrastructure, backend architecture, and AI-powered applications**.

My work spans the full product lifecycle — from understanding the business problem and designing the architecture to writing the APIs, integrating external providers, deploying the system, monitoring it, and making sure it continues working when things go wrong.

📍 **Lusaka, Zambia**

[![Portfolio](https://img.shields.io/badge/🌐_Portfolio-111827?style=for-the-badge)](https://next-js-portifolio-nine.vercel.app/)
[![GitHub](https://img.shields.io/badge/GitHub-111827?style=for-the-badge\&logo=github\&logoColor=white)](https://github.com/mosesjust2016)
[![Email](https://img.shields.io/badge/Email-111827?style=for-the-badge\&logo=gmail\&logoColor=white)](mailto:mjjustme26@gmail.com)

---

## 🧭 What I Do

<table>
<tr>
<td width="25%" align="center">

### 💳

### FinTech

Payments
Mobile Money
Settlement
Wallets
Reconciliation

</td>

<td width="25%" align="center">

### ⚙️

### Backend

APIs
Microservices
Distributed Systems
Event Driven
Architecture

</td>

<td width="25%" align="center">

### 🤖

### AI Engineering

AI Agents
LLMs
RAG
Automation
Tool Calling

</td>

<td width="25%" align="center">

### 🚀

### Product

Architecture
Product Thinking
Delivery
Automation
Problem Solving

</td>
</tr>
</table>

---

# 💳 FinTech & Payments

I build the infrastructure behind digital payments in African markets.

My experience includes **mobile money integrations, payment gateways, merchant platforms, USSD systems, settlement infrastructure, wallets and reconciliation systems.**

### Payment architecture

```text
                         ┌─────────────────┐
                         │     Customer    │
                         └────────┬────────┘
                                  │
                                  ▼
                    ┌─────────────────────────┐
                    │    Mobile Money / USSD  │
                    └────────────┬────────────┘
                                 │
                                 ▼
                    ┌─────────────────────────┐
                    │     Payment Gateway     │
                    └────────────┬────────────┘
                                 │
                 ┌───────────────┼───────────────┐
                 ▼               ▼               ▼
            Collections      Wallets        Disbursements
                 │               │               │
                 └───────────────┼───────────────┘
                                 │
                                 ▼
                       ┌──────────────────┐
                       │    Settlement    │
                       └────────┬─────────┘
                                │
                                ▼
                       ┌──────────────────┐
                       │  Reconciliation  │
                       └──────────────────┘
```

### Areas I've worked in

* 📱 MTN MoMo
* 📱 Airtel Money
* 📱 Zamtel
* 🔗 Payment gateway integrations
* 💰 Collections & disbursements
* 🧾 Payment links
* 🔲 QR payments
* 💸 Bulk payouts
* ↩️ Refunds
* 🏦 Merchant wallets
* 🔐 KYC & merchant onboarding
* 🔄 Transaction reconciliation
* 📊 Financial reporting
* 📞 USSD gateway architecture

---

# 🌍 Settlement & Cross-Border Payments

One of the areas I'm particularly interested in is **cross-border financial infrastructure in Africa**.

I've worked on settlement infrastructure for cross-border freight corridors in Southern Africa, exploring stablecoin rails to reduce the complexity and settlement time between currencies.

```text
                    CORRIDOR A
                         │
                         ▼
                  ┌──────────────┐
                  │     Payer    │
                  └──────┬───────┘
                         │
                         ▼
               ┌────────────────────┐
               │  Settlement Switch │
               └─────────┬──────────┘
                         │
              ┌──────────┼──────────┐
              ▼          ▼          ▼
          Local FI   Stablecoin   FX / Liquidity
              │       Settlement       │
              │          │             │
              └──────────┼─────────────┘
                         │
                         ▼
                  ┌──────────────┐
                  │     Payee    │
                  └──────────────┘
                         │
                         ▼
                    CORRIDOR B
```

### The goal

**Faster settlement · Lower costs · Better reconciliation · Programmable infrastructure**

---

# 🤖 AI Engineering

I'm building toward a future where **AI isn't just a chatbot sitting beside a product — it's part of the product's workflow.**

I'm particularly interested in:

* 🧠 AI Agents
* 🔎 Retrieval-Augmented Generation
* 🛠️ Tool Calling
* 📄 Document Processing
* 🔄 Intelligent Workflows
* 🤖 Autonomous Business Processes
* 🧩 Multi-step Agents
* 🔐 Human-in-the-loop systems
* 📊 AI Observability

### Agent architecture

```text
                         ┌───────────────┐
                         │     User      │
                         └───────┬───────┘
                                 │
                                 ▼
                       ┌──────────────────┐
                       │    AI Agent      │
                       └────────┬─────────┘
                                │
              ┌─────────────────┼──────────────────┐
              ▼                 ▼                  ▼
         Retrieve Data      Call Tools        Understand
              │                 │                Intent
              └─────────────────┼──────────────────┘
                                │
                                ▼
                       ┌──────────────────┐
                       │ Execute Workflow │
                       └────────┬─────────┘
                                │
                                ▼
                       ┌──────────────────┐
                       │ Validate Result  │
                       └────────┬─────────┘
                                │
                                ▼
                             Outcome
```

---

# 🏗️ Backend Engineering

Backend engineering is at the core of my work.

I build systems around:

**APIs · Microservices · Event-driven architecture · Distributed systems · Authentication · Authorization · Databases · Messaging · Integrations**

I particularly enjoy designing systems where multiple services and external providers need to work together reliably.

### Engineering priorities

```text
Reliability
     ↓
Correctness
     ↓
Security
     ↓
Observability
     ↓
Scalability
     ↓
Performance
```

---

# 🧠 Engineering Philosophy

## I care about the failure path.

In payments, the happy path is easy.

The real engineering challenge is:

```text
Request
   ↓
Timeout
   ↓
Retry
   ↓
Duplicate
   ↓
Provider Callback
   ↓
Partial Failure
   ↓
Reconciliation
```

That's why I favour:

* Explicit state machines
* Idempotency
* Transactional boundaries
* Durable messaging
* Transactional outbox patterns
* Callback replay handling
* Duplicate suppression
* Strong audit trails
* Observable workflows
* Reconciliation-first architecture

The system should always be able to answer:

> **What happened to this transaction, why did it happen, and where is the money now?**

---

# 🔐 Security & Compliance

I've worked with security controls relevant to production payment infrastructure, including:

* PCI DSS v4.0
* ISO 27001 controls
* mTLS
* Secrets management
* Audit trails
* Role-based access control
* API security
* Authentication & authorization
* Transaction monitoring

I'm also familiar with the Zambian regulatory environment, including:

**Bank of Zambia · ZICTA · Data Protection Act 2021**

---

# 🚀 Selected Projects

| Project             | Description                                                                                        |
| ------------------- | -------------------------------------------------------------------------------------------------- |
| 💰 **FinanceOS**    | Accounting SaaS with mobile money wallet integration, ledgers, reconciliation and payment capture. |
| 📲 **NagOS**        | Collections and reminder automation platform for scheduled outreach and payment follow-up.         |
| 🏦 **VillageVault** | Digital village banking platform for group savings, contributions and payout cycles.               |
| 💳 **SpendWise**    | Personal finance platform with mobile money transaction ingestion.                                 |
| 📣 **OmniReach**    | Multi-channel messaging and outreach platform.                                                     |
| 🏥 **Digital Care** | Digital platform focused on managing and delivering care-related services.                         |

> Public repositories will be linked here as they become available.

---

# 🛠️ Technology

### Languages

![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square\&logo=openjdk\&logoColor=white)
![C#](https://img.shields.io/badge/C%23-512BD4?style=flat-square\&logo=csharp\&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square\&logo=python\&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square\&logo=typescript\&logoColor=white)
![PHP](https://img.shields.io/badge/PHP-777BB4?style=flat-square\&logo=php\&logoColor=white)
![Dart](https://img.shields.io/badge/Dart-0175C2?style=flat-square\&logo=dart\&logoColor=white)

### Frameworks

![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=flat-square\&logo=springboot\&logoColor=white)
![.NET](https://img.shields.io/badge/.NET-512BD4?style=flat-square\&logo=dotnet\&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square\&logo=nodedotjs\&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-000000?style=flat-square\&logo=flask\&logoColor=white)
![Laravel](https://img.shields.io/badge/Laravel-FF2D20?style=flat-square\&logo=laravel\&logoColor=white)
![Flutter](https://img.shields.io/badge/Flutter-02569B?style=flat-square\&logo=flutter\&logoColor=white)

### Data

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-336791?style=flat-square\&logo=postgresql\&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square\&logo=mysql\&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat-square\&logo=mongodb\&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square\&logo=redis\&logoColor=white)

### Infrastructure

![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square\&logo=docker\&logoColor=white)
![RabbitMQ](https://img.shields.io/badge/RabbitMQ-FF6600?style=flat-square\&logo=rabbitmq\&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square\&logo=linux\&logoColor=black)
![Nginx](https://img.shields.io/badge/Nginx-009639?style=flat-square\&logo=nginx\&logoColor=white)

---

# 📊 GitHub Activity

<p align="center">

<a href="https://github.com/mosesjust2016">
<img src="https://github-readme-stats.vercel.app/api?username=mosesjust2016&show_icons=true&count_private=true&hide_border=true&theme=transparent" height="165"/>
</a>

<a href="https://github.com/mosesjust2016">
<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=mosesjust2016&layout=compact&hide_border=true&theme=transparent" height="165"/>
</a>

</p>

---

# 📚 Documentation & Architecture

I believe documentation is part of engineering.

I document systems so that the architecture can be understood by:

* Engineers
* Product teams
* Operations teams
* Compliance teams
* Business stakeholders

Typical documentation includes:

* Architecture diagrams
* API contracts
* Sequence diagrams
* Database models
* Payment flows
* Failure scenarios
* Integration specifications
* Deployment procedures
* Reconciliation processes

---

# 🔭 Currently

I'm currently focused on building:

### 💳 Payment Infrastructure

Payment gateways, wallets, collections, disbursements and reconciliation.

### 🌍 Cross-Border Settlement

Infrastructure for faster and more programmable settlement across African markets.

### 🤖 AI-Powered Systems

AI agents, intelligent workflows and automation integrated into real products.

### 🚀 SaaS Products

Products around accounting, collections, savings, communications and business automation.

---

# 🤝 Open To

I'm interested in working with teams building:

**FinTech · Payments · AI · SaaS · African Financial Infrastructure · Developer Platforms · Automation**

I'm open to:

* Senior Software Engineer roles
* Senior Product Engineer roles
* Backend Engineering
* Payments Engineering
* FinTech Engineering
* AI Engineering
* Platform Engineering
* Technical Leadership
* Architecture & System Design
* Product Engineering

---

# 📫 Let's Build

If you're building something ambitious around **payments, financial infrastructure, AI or software products**, I'd be happy to connect.

**Portfolio**
https://next-js-portifolio-nine.vercel.app/

**GitHub**
https://github.com/mosesjust2016

**Email**
[mjjustme26@gmail.com](mailto:mjjustme26@gmail.com)

---

<p align="center">

### ⚡ Build products. Engineer for failure. Ship what matters.

</p>
