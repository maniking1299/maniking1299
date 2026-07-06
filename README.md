<div align="center">
<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f0c29,50:302b63,100:24243e&height=220&section=header&text=Manish%20Kumar&fontSize=48&fontColor=ffffff&animation=fadeIn&fontAlignY=38&desc=Java%20Backend%20Developer%20%7C%20Building%20Scalable%20Backend%20Systems&descAlignY=58&descSize=18" width="100%"/>
<a href="https://git.io/typing-svg">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=24&duration=3000&pause=1000&color=A78BFA&center=true&vCenter=true&width=650&lines=Java+21+%7C+Spring+Boot+%7C+PostgreSQL;Backend+Engineer+in+Progress;Building+VDeploy+%E2%80%94+a+Self-Hosted+Deployment+Platform;Solved+200%2B+DSA+Problems+on+LeetCode;Actively+Seeking+Backend+Internship+Opportunities" alt="Typing SVG" />
</a>
<br/><br/>
 
<img src="https://img.shields.io/badge/B.Tech_CSE-Quantum_University-6D28D9?style=for-the-badge&logo=studyverse&logoColor=white"/>
<img src="https://img.shields.io/badge/Graduating-2027-7C3AED?style=for-the-badge"/>
<img src="https://img.shields.io/badge/Location-Roorkee%2C_India-8B5CF6?style=for-the-badge&logo=googlemaps&logoColor=white"/>
<br/><br/>
 
<a href="https://github.com/maniking1299"><img src="https://img.shields.io/badge/Portfolio-4C1D95?style=for-the-badge&logo=vercel&logoColor=white"/></a>
<a href="https://linkedin.com/in/manishkumar1299"><img src="https://img.shields.io/badge/LinkedIn-5B21B6?style=for-the-badge&logo=linkedin&logoColor=white"/></a>
<a href="mailto:kumarmanish20052004@gmail.com"><img src="https://img.shields.io/badge/Email-6D28D9?style=for-the-badge&logo=gmail&logoColor=white"/></a>
<a href="https://github.com/maniking1299"><img src="https://img.shields.io/badge/GitHub-4C1D95?style=for-the-badge&logo=github&logoColor=white"/></a>
 
<br/><br/>
 
<img src="https://komarev.com/ghpvc/?username=maniking1299&color=8B5CF6&style=flat-square&label=PROFILE+VIEWS"/>
<img src="https://img.shields.io/github/followers/maniking1299?color=A78BFA&style=flat-square&label=FOLLOWERS"/>
<img src="https://img.shields.io/github/stars/maniking1299?color=7C3AED&style=flat-square&label=STARS"/>
</div>
<br/>
---
 
### 📌 About Me
 
```yaml
name: "Manish Kumar"
role: "Backend Developer (Java / Spring Boot)"
education: "B.Tech CSE, Quantum University, Roorkee — CGPA 7.97/10 (2023-2027)"
focus: ["Backend Engineering", "Distributed Systems Basics", "DSA in Java"]
philosophy: "Ship real systems, debug them for real, and write about the bugs — not just the features."
```
 
Backend-focused Computer Science student building real systems with Java and Spring Boot. I enjoy designing reliable backend services, debugging concurrency issues, and understanding why systems fail—not just making them work. Currently building VDeploy, a self-hosted deployment platform running on AWS EC2 while preparing for backend engineering roles.
 
**🎯 Open To:** Java Backend Internships (India) · Product-based engineering teams · Long-term goal: backend roles in Japan & Southeast Asia
 
---
 
### 🛠️ Tech Stack
 
<div align="center">
**Languages**
 
<img src="https://skillicons.dev/icons?i=java"/> <img src="https://skillicons.dev/icons?i=js"/>
 
**Backend & APIs**
 
<img src="https://skillicons.dev/icons?i=spring"/> <img src="https://skillicons.dev/icons?i=nodejs"/> <img src="https://skillicons.dev/icons?i=express"/>
 
`Spring Boot` `Spring Security` `JWT` `BCrypt` `REST APIs`
 
**Databases & ORM**
 
<img src="https://skillicons.dev/icons?i=postgres"/> <img src="https://skillicons.dev/icons?i=mongodb"/>
 
`JPA / Hibernate` `Mongoose`
 
**Cloud, DevOps & Tooling**
 
<img src="https://skillicons.dev/icons?i=aws"/> <img src="https://skillicons.dev/icons?i=docker"/> <img src="https://skillicons.dev/icons?i=git"/> <img src="https://skillicons.dev/icons?i=github"/> <img src="https://skillicons.dev/icons?i=postman"/>
 
`Maven` `Lombok` `SLF4J` `AWS EC2` `AWS S3`
 
**Computer Science Fundamentals**
 
`Data Structures & Algorithms` `Object-Oriented Programming` `DBMS` `Operating Systems` `Computer Networks`
 
</div>
---
 
### 💡 Engineering Focus Areas
 
| Area | Current Depth | Notes |
|---|---|---|
| **Backend Systems** | Building | Async pipelines, state machines, persistent job tracking in Spring Boot |
| **Data Structures & Algorithms** | Strong | 200+ LeetCode problems solved in Java, working through Striver's DSA sheet |
| **Cloud Deployment** | Hands-on | Deployed & manage a live service on AWS EC2 (systemd, Elastic IP) |
| **Full-Stack Fundamentals** | Working Knowledge | MVC, auth (Passport.js/JWT), MongoDB & PostgreSQL from WanderLust + VDeploy |
| **Trading Systems (personal interest)** | Learning | Studying market structure via a rules-based technical methodology, in practice-only phase |
 
---
 
### 🚀 Featured Projects
 
<details>
<summary><b>🔷 VDeploy — Self-Hosted Cloud Deployment Platform</b></summary>
<br/>
A backend platform that automates repository cloning, Docker builds, artifact storage, and deployment tracking — deployed live and running on AWS EC2, serving my own portfolio deployment as proof of end-to-end functionality.
 
| Category | Details |
|---|---|
| **Stack** | Java 21, Spring Boot, Spring Security (JWT), PostgreSQL, JPA/Hibernate, Docker (via ProcessBuilder), AWS EC2 & S3 |
| **Architecture** | Async job pipeline using `LinkedBlockingQueue` + background worker threads for non-blocking deployment processing |
| **State Management** | Deployment lifecycle state machine: `QUEUED → RUNNING → SUCCESS → FAILED`, persisted via Spring Data JPA |
| **Reliability** | `StartupReconciliationService` — recovers orphaned `RUNNING` deployments left in an inconsistent state after a JVM restart |
| **Real Bugs Fixed** | Diagnosed and resolved a stdout stream deadlock in subprocess handling, added a missing `waitFor()` timeout to prevent hung deployments |
| **Status** | Live on AWS EC2 (Ubuntu, `ap-south-1`), managed as a systemd service |
| **Repository** | [github.com/maniking1299](https://github.com/maniking1299) |
 
VDeploy exists because I wanted a backend project where the interesting part isn't the CRUD, it's the failure modes — what happens when a deployment process hangs, when the server restarts mid-job, when a stream doesn't close cleanly. Solving those is what this project is actually about.
 
</details>
<details>
<summary><b>🔷 WanderLust — Airbnb-Style Property Listing Platform</b></summary>
<br/>
My first full-stack project, built to understand the full request lifecycle from routing to persistence to auth — before specializing into Java/Spring Boot.
 
| Category | Details |
|---|---|
| **Stack** | Node.js, Express.js, MongoDB, Mongoose, EJS, Passport.js |
| **Features** | RESTful CRUD for property listings with nested reviews |
| **Auth** | Passport.js (Local Strategy), BCrypt password hashing, session management, HTTP-only cookies |
| **Architecture** | MVC pattern, modular Express Router, centralized async error-handling middleware |
| **Repository** | [github.com/maniking1299](https://github.com/maniking1299) |
 
WanderLust predates my Java focus but I keep it front and center because it's honest proof I understand full-stack fundamentals — not just the Spring Boot side of the world.
 
</details>
---
 
### 📍 Current Status
 
> I don't have prior internship experience yet — I'm actively applying for my first Java backend internship rather than claiming one I haven't done. Everything above reflects real, verifiable project work.
 
---
 
### 🏆 Achievements
 
<div align="center">
| Recognition | Details |
|---|---|
| 🧩 **200+ DSA Problems** | Solved on LeetCode using Java, working through Striver's DSA Sheet |
| 🌐 **Deloitte Australia Job Simulation** | Completed via Forage, June 2025 |
| ☁️ **Live Production Deployment** | Self-built and self-hosted VDeploy running on AWS EC2 |
 
</div>
---
 
### 👨‍💻 Coding Profiles
 
<div align="center">
<a href="https://leetcode.com/"><img src="https://img.shields.io/badge/LeetCode-200%2B_Solved-FFA116?style=for-the-badge&logo=leetcode&logoColor=white"/></a>
 
</div>
---
 
## 📊 GitHub Metrics

<div align="center">

<img src="https://raw.githubusercontent.com/maniking1299/maniking1299/main/github-metrics.svg" width="100%"/>

</div>

---
 
### 📈 Contribution Activity
 
<div align="center">
<img src="https://github-readme-activity-graph.vercel.app/graph?username=maniking1299&theme=tokyo-night&hide_border=true&bg_color=0D1117&color=A78BFA&line=8B5CF6&point=C9D1D9" width="95%"/>
</div>
---
 
### 🐍 Contribution Snake
 
<div align="center">
<img src="https://raw.githubusercontent.com/maniking1299/maniking1299/output/github-contribution-grid-snake-dark.svg" width="95%"/>
</div>
---
 
### 🎯 Current Focus
 
```yaml
learning:
  - "Advanced Spring Boot patterns & concurrency in Java"
  - "Redis caching & Spring STOMP / WebSocket streaming"
  - "Flyway-based schema migrations"
 
building:
  - "Paper-trading simulation platform (order execution engine, P&L state machine)"
  - "Sharpening VDeploy with production-grade observability"
 
exploring:
  - "Backend engineering culture at product-based companies in Japan & SE Asia"
 
open_to:
  - "Java Backend Internships (India, remote)"
  - "Referrals & mentorship from backend engineers"
```
 
---
 
### 📫 Connect With Me
 
<div align="center">
<a href="mailto:kumarmanish20052004@gmail.com"><img src="https://img.shields.io/badge/kumarmanish20052004@gmail.com-6D28D9?style=for-the-badge&logo=gmail&logoColor=white"/></a>
<a href="https://linkedin.com/in/manishkumar1299"><img src="https://img.shields.io/badge/manishkumar1299-5B21B6?style=for-the-badge&logo=linkedin&logoColor=white"/></a>
<a href="https://github.com/maniking1299"><img src="https://img.shields.io/badge/maniking1299-4C1D95?style=for-the-badge&logo=github&logoColor=white"/></a>
 
</div>
---
 
<div align="center">
*"Build it, break it, understand why it broke — then ship it."*
 
<img src="https://capsule-render.vercel.app/api?type=waving&color=0:24243e,50:302b63,100:0f0c29&height=120&section=footer" width="100%"/>
</div>
 
