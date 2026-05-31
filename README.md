# Hey, I'm Abdulmujeeb Uthman 👋

**Fullstack Developer · Application Security Engineer**

I build, break, and harden web systems. My focus sits at the intersection of backend engineering and security — writing production-grade APIs with security baked in from the start, not bolted on at the end.

---

## 🔐 What I Do

- **Secure Backend Engineering** — Node.js, Express, REST APIs with auth, RBAC, and rate limiting
- **Application Security** — OWASP Top 10, JWT hardening, brute-force protection, token rotation
- **Security Tooling** — Python scripts for recon, enumeration, and vulnerability scanning
- **Offensive Security Practice** — HackTheBox · TryHackMe · Exploitation writeups

---

## ⚙️ Tech Stack

**Languages:** JavaScript (Node.js) · Python
**Backend:** Express.js · REST APIs · MongoDB · Mongoose
**Auth & Security:** JWT · bcryptjs · Helmet · express-rate-limit · RBAC
**Tools:** Git · GitHub · Bash · Linux · Wireshark · Nmap

---

## 🚀 Shipped Projects

### 🔐 [Secure Auth API](https://github.com/DevwithMujeeb/secure-auth-api)

Production-grade authentication REST API built as a security lab/demo.

- JWT access tokens (15min) + refresh token rotation (7 days)
- Role-based access control — `user`, `moderator`, `admin`
- Brute-force protection — account lockout after 5 failed attempts
- IP-based rate limiting on all auth endpoints
- Secure password reset via email with SHA-256 hashed tokens
- httpOnly cookie storage · Helmet security headers

`Node.js` `Express` `MongoDB` `JWT` `bcryptjs` `Nodemailer`

---

### 🔓 [Vulnerable Web Lab](https://github.com/DevwithMujeeb/vulnerable-web-lab)

Intentionally vulnerable web app covering OWASP Top 10 — exploit each vulnerability, then see the patch.

- NoSQL Injection — bypass login with MongoDB `$ne` operator
- XSS — inject JavaScript that executes in the browser
- Broken Authentication — brute-force with no lockout
- IDOR — access any user's private data by changing an ID
- Security Misconfiguration — extract stack traces, API keys, server config
- Sensitive Data Exposure — plain text vs bcrypt hashed passwords side by side

`Node.js` `Express` `MongoDB` `bcryptjs` `OWASP Top 10`

---

### 🛠️ [Security Tools](https://github.com/DevwithMujeeb/security-tools)

Python CLI security tools for recon and analysis.

- Port Scanner — TCP port scanner with service detection and configurable timeout
- Subdomain Enumerator — wordlist-based discovery with HTTPS support and results export
- JWT Analyzer — decode, inspect, check expiry, and flag weak algorithms from the CLI

`Python` `requests` `colorama` `JWT` `Recon`

---

## 🚧 In Progress

| Project                 | Description                                    | Status   |
| ----------------------- | ---------------------------------------------- | -------- |
| 📘 CTF Writeups         | HackTheBox & TryHackMe methodology docs        | Building |
| 🌐 Secure Fullstack App | React + Node.js with integrated security layer | Building |

---

## 📈 Current Focus

- Production-grade secure system design
- Web exploitation techniques & CVE analysis
- DevSecOps mindset — shifting security left in CI/CD pipelines
- Building toward **Application Security** and **Security Engineering** roles

---

## 📫 Let's Connect

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Abdulmujeeb%20Uthman-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/abdulmujeeb-uthman/)
[![X](https://img.shields.io/badge/X-JeebExplains-111111?style=flat&logo=x&logoColor=white)](https://x.com/JeebExplains)
[![Instagram](https://img.shields.io/badge/Instagram-vortex__node-E4405F?style=flat&logo=instagram&logoColor=white)](https://www.instagram.com/vortex_node/)
[![Reddit](https://img.shields.io/badge/Reddit-DevwithMujeeb-FF4500?style=flat&logo=reddit&logoColor=white)](https://www.reddit.com/user/DevwithMujeeb/)
