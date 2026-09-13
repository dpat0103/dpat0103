<div align="center">

# Hey, I'm Dhruv 👋

### Software Engineer · Backend · Platform · Data Systems

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=16&pause=1200&color=6366F1&center=true&vCenter=true&width=650&lines=Backend+Systems+%C2%B7+APIs+%C2%B7+Data+Pipelines+%C2%B7+Cloud;Python+%C2%B7+TypeScript+%C2%B7+SQL+%C2%B7+GCP+%C2%B7+AWS;Building+software+for+real+operational+problems" alt="Typing SVG" />

<br>

[![LinkedIn](https://img.shields.io/badge/LinkedIn-6366F1?style=flat-square\&logo=linkedin\&logoColor=white)](https://linkedin.com/in/dpat0103)
[![Email](https://img.shields.io/badge/Email-EC4899?style=flat-square\&logo=gmail\&logoColor=white)](mailto:dpatel8825@gmail.com)

</div>

---

## 👨‍💻 About Me

I'm a Rutgers Computer Science graduate focused on building **backend services, integrations, data pipelines, and cloud-based systems**.

Across two engineering terms at **UPS**, I worked on enterprise identity and integration systems involving **Microsoft Entra ID, SCIM, Flask APIs, BigQuery, GCP Cloud Run, SailPoint IIQ, and Dayforce**.

Outside of work, I build systems around problems I find interesting — from monitoring API reliability to tracking Rutgers course availability for hundreds of students.

Currently interested in **backend, platform, cloud, and data-focused software engineering**.

---

## ⚡ Featured Engineering

<table>
<tr>
<td width="50%" valign="top">

### 🔭 IntegrationOps

**API Reliability & Integration Monitoring Platform**

Backend monitoring system designed to detect failures across external API integrations and automate the incident lifecycle.

**Highlights**

* Classifies **8 API failure modes**
* Opens incidents after **3 consecutive failures**
* Idempotent health checks and configurable SLOs
* Tracks availability, **P95 latency**, and recovery
* Prometheus metrics + Grafana dashboards
* Redis-backed Celery workers and scheduled checks
* Slack notifications for operational events
* **21 automated tests**

**Architecture**

`FastAPI` → `PostgreSQL`
`Celery Beat` → `Redis` → `Celery Workers`
`Prometheus` → `Grafana`

**Stack**

`Python` `FastAPI` `Celery` `PostgreSQL` `Redis` `Docker` `Prometheus` `Grafana`

</td>
<td width="50%" valign="top">

### 🎓 RU SnipeZ

**Rutgers Course Availability Monitor**

Built and operated a course monitoring system used by **550+ Rutgers students**.

**Highlights**

* Tracks **25,000+ course sections**
* Delivers sub-second availability alerts
* Automated course extraction and ETL workflows
* Deployed and maintained on AWS EC2
* Supported production users for ~18 months
* Independently handled uptime, failures, and user issues

Built because registering for a full Rutgers course shouldn't require refreshing WebReg all day.

**Stack**

`Python` `Flask` `Selenium` `BeautifulSoup` `SQLite` `AWS EC2`

</td>
</tr>
</table>

---

## 🧩 More Engineering Work

<table>
<tr>
<td width="50%" valign="top">

### 🗺️ CivicLens

**New Jersey Municipal Intelligence Platform**

Transforms fragmented public datasets into comparable statistics and searchable information across **all 564 New Jersey municipalities**.

Processes data spanning **2019–2023** across **13 municipal metrics**.

Open-ended questions use hybrid **BM25 + dense vector retrieval with reciprocal-rank fusion**, while numeric questions route directly to SQL.

**Stack**

`Python` `FastAPI` `PostgreSQL` `SQLAlchemy` `Next.js` `TypeScript`

[🌐 Live Application](https://civic-lens-khaki.vercel.app/) · [💻 Repository](https://github.com/dpat0103/CivicLens)

</td>
<td width="50%" valign="top">

### 🚗 DealSense

**Vehicle Market Intelligence Platform**

VIN-driven analysis system that evaluates used vehicles against comparable inventory and current market conditions.

Built around third-party API orchestration, vehicle normalization, normalized search fingerprints, DB-backed caching, and defensive handling of sparse upstream data.

Supports comparable searches across **25, 50, and 100-mile radiuses**.

**Stack**

`TypeScript` `Next.js` `React` `SQL` `Cloudflare D1` `Drizzle ORM`

</td>
</tr>
</table>

---

## 🏢 Production Experience

### UPS — Software Engineering Co-Op & Software Engineering Intern

Across two engineering terms at UPS, I worked on enterprise backend, identity, and integration systems.

* Built a **SCIM provisioning pipeline integrated with Microsoft Entra ID**, replacing hourly role synchronization with near-real-time access provisioning.
* Designed hash-based change detection over BigQuery permissions data, reducing synchronization query time from **1.8s → 0.6s** while maintaining an auditable provisioning history.
* Built a containerized **Flask REST API** and deployed it to **GCP Cloud Run** through a Jenkins CI/CD pipeline.
* Developed a scheduled Python service reconciling approximately **1,000 employee access records daily** across SailPoint IIQ and Dayforce.
* Built unit and integration tests covering reconciliation logic, malformed data, authentication failures, and upstream API errors.

---

## 🛠️ Technical Toolkit

**Languages**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square\&logo=python\&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square\&logo=typescript\&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square\&logo=javascript\&logoColor=black)
![SQL](https://img.shields.io/badge/SQL-336791?style=flat-square\&logo=postgresql\&logoColor=white)
![Shell](https://img.shields.io/badge/Shell-4EAA25?style=flat-square\&logo=gnubash\&logoColor=white)

**Backend & APIs**

![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square\&logo=fastapi\&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-000000?style=flat-square\&logo=flask\&logoColor=white)
![SQLAlchemy](https://img.shields.io/badge/SQLAlchemy-D71F00?style=flat-square\&logo=sqlalchemy\&logoColor=white)
![REST](https://img.shields.io/badge/REST_APIs-6366F1?style=flat-square)

**Data**

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square\&logo=postgresql\&logoColor=white)
![BigQuery](https://img.shields.io/badge/BigQuery-669DF6?style=flat-square\&logo=googlebigquery\&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square\&logo=redis\&logoColor=white)

**Cloud & Infrastructure**

![GCP](https://img.shields.io/badge/Google_Cloud-4285F4?style=flat-square\&logo=googlecloud\&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square\&logo=amazonwebservices\&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square\&logo=docker\&logoColor=white)
![Terraform](https://img.shields.io/badge/Terraform-844FBA?style=flat-square\&logo=terraform\&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square\&logo=linux\&logoColor=black)
![Jenkins](https://img.shields.io/badge/Jenkins-D24939?style=flat-square\&logo=jenkins\&logoColor=white)

**Reliability & Testing**

![PyTest](https://img.shields.io/badge/PyTest-0A9EDC?style=flat-square\&logo=pytest\&logoColor=white)
![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=flat-square\&logo=prometheus\&logoColor=white)
![Grafana](https://img.shields.io/badge/Grafana-F46800?style=flat-square\&logo=grafana\&logoColor=white)
![CI/CD](https://img.shields.io/badge/CI%2FCD-6366F1?style=flat-square)

---

## 📋 Background

|    |                                                           |
| :- | :-------------------------------------------------------- |
| 🎓 | **B.A. Computer Science** · Rutgers University · May 2025 |
| 💼 | **Software Engineering Co-Op** · UPS                      |
| 💼 | **Software Engineering Intern** · UPS                     |
| 📍 | New Jersey                                                |
| 🎯 | Backend · Platform · Cloud · Data Engineering             |
| 🔨 | Currently building and improving IntegrationOps           |

---

<div align="center">

### Let's Connect

I'm always interested in discussing backend systems, infrastructure, APIs, cars, or interesting engineering problems.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-6366F1?style=for-the-badge\&logo=linkedin\&logoColor=white)](https://linkedin.com/in/dpat0103)
[![Email](https://img.shields.io/badge/Email-Reach_Out-EC4899?style=for-the-badge\&logo=gmail\&logoColor=white)](mailto:dpatel8825@gmail.com)

</div>
