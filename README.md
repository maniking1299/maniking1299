# Manish Kumar

**Java Backend Developer** · B.Tech CSE @ Quantum University, Roorkee (2027)

I build backend systems — REST APIs, async job processors, containerized deployment pipelines.

---

## 🚀 VDeploy — Deployment Automation Platform

> A Vercel-inspired platform built entirely in Java. Submit a GitHub repo → get a live deployment.

**What it does:**
Users provide a GitHub repo URL, build command, and output directory.
VDeploy clones the repo, runs the build inside a Docker container, uploads output to AWS S3, and serves the app via Nginx at a unique URL.

**Technical decisions worth noting:**

| Decision | Why |
|---|---|
| `LinkedBlockingQueue` for job processing | Decouples API from slow deployment execution. API returns immediately, worker processes async. |
| Docker via `ProcessBuilder` | Isolates each build. One failing deployment can't affect others. |
| PostgreSQL state machine | Deployment moves through `QUEUED → RUNNING → SUCCESS → FAILED`. Reliable tracking, easy debugging. |
| Stateless JWT auth | No server-side session state. Scales horizontally without sticky sessions. |

**Stack:** Java 21 · Spring Boot 3.5 · Spring Security · JWT · PostgreSQL · JPA/Hibernate · Docker · AWS S3 · Nginx · Maven

🔗 [View Repository](https://github.com/maniking1299/Vercel-Clone)
🔗 [Live](http://13.235.27.137:8080)
---

## 🛠️ Tech Stack

```
Languages      Java 21 (primary) · JavaScript · SQL
Backend        Spring Boot 3.5 · Spring Security · REST APIs · Node.js · Express.js  
Auth           JWT · BCrypt · Passport.js
Databases      PostgreSQL · MongoDB · JPA/Hibernate · Mongoose
DevOps         Docker · AWS S3 · AWS EC2 · Nginx
Tools          Maven · Lombok · Slf4j · Git · Postman · IntelliJ IDEA
CS             DSA · OOP · DBMS · OS · Computer Networks
```

---

## 📂 Other Projects

**WanderLust** — Airbnb-style property listing platform
Node.js · Express.js · MongoDB · Passport.js · MVC · RESTful CRUD
🔗 [Repository](https://github.com/maniking1299/WanderLust)


---

## 📬 Contact

- 📧 kumarmanish20052004@gmail.com
- 💼 [LinkedIn](https://www.linkedin.com/in/manishkumar1299)

**Open to SDE internships — Java backend Developer**
