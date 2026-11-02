# MOHUL ROY CHOWDHURY

**Computer Science Student | Backend Engineering | Full-Stack Development**

I build backend systems and full-stack applications, with a focus on performance, correctness, and clean architecture. I work comfortably from low-level storage internals up to production-style web platforms.

---

## ABOUT ME

- Third-year Computer Science student based in Kolkata, India
- Interested in database internals, backend architecture, and scalable web systems
- Enjoy building things from first principles to understand how they really work
- Continuously learning, with a focus on systems programming and data-intensive applications

---

## TECH STACK

**Languages**

![Java](https://img.shields.io/badge/Java_21-ED8B00?style=flat-square&logo=openjdk&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![C](https://img.shields.io/badge/C-A8B9CC?style=flat-square&logo=c&logoColor=black)
![Lua](https://img.shields.io/badge/Lua-2C2D72?style=flat-square&logo=lua&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript_ES6+-F7DF1E?style=flat-square&logo=javascript&logoColor=black)

**Backend & Security**

![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white)
![Spring](https://img.shields.io/badge/Spring_Framework-6DB33F?style=flat-square&logo=spring&logoColor=white)
![JWT](https://img.shields.io/badge/JWT_Auth-000000?style=flat-square&logo=jsonwebtokens&logoColor=white)
![REST](https://img.shields.io/badge/REST_APIs-009688?style=flat-square)

**Frontend**

![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white)

**Databases & Caching**

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)

**DevOps & Tooling**

![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white)
![Maven](https://img.shields.io/badge/Maven-C71A36?style=flat-square&logo=apachemaven&logoColor=white)
![IntelliJ IDEA](https://img.shields.io/badge/IntelliJ_IDEA-000000?style=flat-square&logo=intellijidea&logoColor=white)
![VS Code](https://img.shields.io/badge/VS_Code-007ACC?style=flat-square&logo=visualstudiocode&logoColor=white)

**Data & Analysis**

![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=flat-square&logo=jupyter&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-11557C?style=flat-square)

---

## FEATURED PROJECTS

### JaveDB: Embedded Key-Value Database (LSM-Tree)

A lightweight embedded database built from scratch in **Java 21**, using an LSM-tree inspired storage engine. Includes a Write-Ahead Log for crash recovery, a MemTable, immutable SSTables, Bloom filters, sparse indexing, tombstone deletions, and automatic compaction, plus an interactive CLI with a runtime dashboard, health monitor, and built-in benchmark suite.

**Highlights:** WAL durability and recovery • Bloom filter + sparse index lookups • Automatic SSTable compaction • Built-in observability

| Benchmark (local machine) | Throughput |
|---|---|
| PUT (10,000 ops) | ~227,000 ops/sec |
| GET (10,000 ops) | ~2.6M ops/sec |
| Stress test (25,000 ops) | ~361,000 ops/sec |

**Stack:** Java 21 • Maven

[View Project](https://github.com/mo5ul/JaveDB)

---

### TicketForge: Seat Reservation & Ticketing Platform

> 🚧 **In active development**

A full-stack seat-booking platform (BookMyShow-style, scoped down) focused on correctness under concurrency: seats are held for 10 minutes, then confirmed after payment, and no seat can ever be double-booked.

**Planned highlights**
- JWT authentication with role-based access (`USER`, `ADMIN`) and refresh tokens
- Event, venue, and seat inventory management with admin CRUD
- Expiring seat holds with a scheduled job that releases them
- Razorpay payment integration (test mode) with an idempotent webhook
- Redis-backed caching and rate limiting
- Async email confirmations using a transactional outbox pattern
- Concurrency testing: 200 threads racing for one seat, asserting exactly one succeeds
- Testcontainers integration tests, k6 load testing, GitHub Actions CI
- React + TypeScript frontend with an interactive seat map, hold countdown, and admin panel

**Stack:** Java 21 • Spring Boot 3 • PostgreSQL • Redis • React • TypeScript • Docker

[View Project](https://github.com/mo5ul/TicketForge)

---

## CURRENTLY LEARNING

C • C++ • Database Internals • System Design

---

## CONNECT

📧 [Email](mailto:mohulrc@gmail.com)
🔗 [LinkedIn](https://www.linkedin.com/in/mohul-roy-chowdhury-374b79326)
