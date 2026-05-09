<div align="center">

# Joseph · WildRelation

**IT Support · Data Engineering · Backend Systems · Stockholm**

[![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)](https://python.org)
[![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)](https://java.com)
[![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)](https://fastapi.tiangolo.com)
[![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=for-the-badge&logo=springboot&logoColor=white)](https://spring.io/projects/spring-boot)
[![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)](https://docker.com)
[![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white)](https://postgresql.org)
[![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)](https://kernel.org)

</div>

---

<div align="center">

![snake](https://raw.githubusercontent.com/WildRelation/WildRelation/output/github-contribution-grid-snake-dark.svg)

</div>

## Open to

> **Seeking IT Support summer internship (2026)** — I enjoy helping users solve technical problems and have hands-on experience with Linux, Windows, networking and hardware. Available weeks 27–33, Stockholm.

---

## What I build

I focus on **data infrastructure** and **backend APIs** — systems that store, process and expose data at scale. Currently building lakehouse architectures with DuckDB and exploring ML pipelines end-to-end.

```
CSV / raw data  →  DuckLake (DuckDB + Parquet)  →  REST API  →  Predictions
```

---

## Featured project

### [ducklake-access-manager](https://github.com/WildRelation/ducklake-access-manager)

A self-service web portal for automatic credential generation and access management for DuckLake (PostgreSQL + Garage S3) on KTH Cloud. Instead of manually distributing credentials, users visit the web UI and get a ready-to-run DuckDB connection script in seconds.

```
User visits web UI  →  selects bucket & permissions  →  gets DuckDB script
                                                              ↓
                                              runs inside cbhcloud deployment
                                              (JupyterLab / VS Code / Python)
```

| Layer | Tech |
|---|---|
| Backend | Java (Spring Boot) |
| Frontend | HTML / CSS |
| Catalog (metadata) | PostgreSQL |
| Object storage | Garage (S3-compatible) |
| Container runtime | Docker |
| Deployment | KTH Cloud (cbhcloud) |

**Highlights**
- Zero-touch credential generation — no manual admin steps
- Live at `ducklake-access-manager.app.cloud.cbh.kth.se`
- Role-based bucket access (read / read-write)
- Generates ready-to-paste DuckDB connection scripts

---

## Stack

```python
languages  = ["Python", "Java", "C"]
databases  = ["PostgreSQL", "DuckDB", "MinIO (S3)"]
frameworks = ["FastAPI", "Spring Boot"]
infra      = ["Docker", "Docker Compose", "GitHub Actions", "GHCR"]
data       = ["DuckLake", "Parquet", "Pandas", "scikit-learn"]
support    = ["Linux (Arch/Ubuntu)", "Windows 10/11", "Networking", "Hardware troubleshooting"]
```

---

## GitHub stats

<div align="center">

![WildRelation's stats](https://github-readme-stats.vercel.app/api?username=WildRelation&show_icons=true&theme=dark&hide_border=true&count_private=true)

![Top langs](https://github-readme-stats.vercel.app/api/top-langs/?username=WildRelation&layout=compact&theme=dark&hide_border=true)

</div>

---

<div align="center">

Stockholm, Sweden &nbsp;·&nbsp; joseph.solsol@hotmail.com

</div>

---
