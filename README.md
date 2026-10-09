<!--
**Slimcent/Slimcent** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->


# Hi, I'm Obinna Achara

Backend Software Engineer focused on building reliable, maintainable and scalable backend systems with **C#, ASP.NET Core, Python and FastAPI**.

My work and projects focus on backend architecture, distributed systems, asynchronous processing, API design, observability, authentication, payments and data-intensive applications.

I currently work at the **Paderborn Center for Parallel Computing (PC²)**.

---

## Current Focus

### FlowForge

I am currently building **FlowForge**, a backend platform for workflow execution and distributed job processing.

The project is being developed incrementally, with the core execution platform coming first before higher-level document intelligence features are added.

Current roadmap:

```
FlowForge Core
    ↓
Workflow execution
    ↓
RabbitMQ + worker processing
    ↓
Retries and reliability
    ↓
Stable FlowForge API
    ↓
Document Intelligence Platform
    ↓
Integration with FlowForge
    ↓
Python / FastAPI document worker
```

The goal is to build a system where workflows can be created, executed and processed asynchronously across workers, with reliability, retries and clear execution state.

The later document intelligence layer will run on top of the same execution infrastructure instead of being built as a separate isolated application.

Technologies and concepts involved include:

- ASP.NET Core
- SQL Server
- Entity Framework Core
- RabbitMQ
- background workers
- distributed job execution
- retry handling
- workflow state management
- REST APIs
- Python
- FastAPI
- document-processing workers

---

## Featured Project

### Online Voting System

[Repository](https://github.com/Slimcent/Online_Voting_Sys) · [Live API](https://online-voting-api.runasp.net/swagger/index.html)

A backend election platform built with **ASP.NET Core, Entity Framework Core and SQL Server**.

The system covers the main election lifecycle:

```
Election Setup
    ↓
Election Positions
    ↓
Candidate Applications
    ↓
Application Payments
    ↓
Administrative Review
    ↓
Contestants
    ↓
Voter Registration
    ↓
Secure Voting
    ↓
Voting History
    ↓
Election Results
```

The backend also includes:

- JWT authentication
- refresh-token rotation
- role and claims authorization
- payment processing
- payment idempotency
- background processing
- caching
- audit trails
- centralized Swagger documentation
- OpenTelemetry instrumentation
- Prometheus metrics
- Grafana dashboards
- Tempo distributed tracing
- NLog application logging

The project follows a layered service architecture with thin controllers, service interfaces and implementations, repositories, Unit of Work and infrastructure abstractions.

---

## Backend Engineering

My main areas of interest include:

- Backend architecture
- Distributed systems
- REST API design
- Event-driven systems
- Background processing
- Message queues
- Authentication and authorization
- Payments
- Caching
- Observability
- Database design
- Reliability and retry strategies
- Testing
- System design

---

## Technologies

**Languages**

- C#
- Python
- SQL

**Backend**

- ASP.NET Core
- FastAPI
- Entity Framework Core
- SQLAlchemy

**Data**

- SQL Server
- PostgreSQL
- MySQL
- MongoDB
- Redis

**Messaging and Processing**

- RabbitMQ
- Background workers
- Asynchronous processing

**Observability**

- OpenTelemetry
- Prometheus
- Grafana
- Tempo
- NLog

**Engineering Tools**

- Docker
- Git
- GitHub
- Swagger / OpenAPI
- xUnit
- Moq

---

## Other Projects

### Financial Application

[Repository](https://github.com/Slimcent/Financial_Application)

A Python banking application using SQLAlchemy and MySQL with account management, transfers, transaction processing and asynchronous database operations.

### CountryRegion

[Repository](https://github.com/Slimcent/CountryRegion)

A C# backend project focused on geographical and regional data management.

### Penguins Classifier

[Repository](https://github.com/Slimcent/Penguis_Classifier)

A machine-learning project using K-Nearest Neighbors to classify penguin species from physical characteristics.

---

## What I'm Working Toward

I am building projects that demonstrate more than CRUD APIs.

My current focus is on systems that involve:

- multiple services or workers;
- asynchronous processing;
- message-driven communication;
- reliability and retries;
- observability;
- real-world domain workflows;
- clear architectural boundaries.

---

## Contact

GitHub: [@Slimcent](https://github.com/Slimcent)

---

<p align="center">
  Backend engineering • Distributed systems • APIs • Reliability • Observability
</p>
