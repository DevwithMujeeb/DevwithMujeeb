# Hey, I'm Abdulmujeeb Uthman 👋

**Fullstack Developer · Application Security Engineer**

I build, break, and harden web systems. My focus sits at the intersection of backend engineering and security — writing production-grade APIs with security baked in from the start, not bolted on at the end.

---

## 🔐 What I Do

- **Secure Backend Engineering** — Node.js, Express, REST APIs with auth, RBAC, and rate limiting
- **Application Security** — OWASP Top 10, JWT hardening, brute-force protection, token rotation
- **Security Tooling** — Python scripts for recon, enumeration, and vulnerability scanning
- **Offensive Security Practice** — HackTheBox · Exploitation writeups

---

## ⚙️ Tech Stack

**Languages & Runtime**

[![Languages](https://skillicons.dev/icons?i=js,python,nodejs,react)](https://skillicons.dev)

**Backend & Databases**

[![Backend](https://skillicons.dev/icons?i=express,mongodb)](https://skillicons.dev)

**Security & Auth**

![JWT](https://img.shields.io/badge/JWT-black?style=flat&logo=jsonwebtokens&logoColor=white)
![bcryptjs](https://img.shields.io/badge/bcryptjs-338?style=flat&logoColor=white)
![Helmet](https://img.shields.io/badge/Helmet.js-333?style=flat&logoColor=white)
![RBAC](https://img.shields.io/badge/RBAC-555?style=flat&logoColor=white)
![Rate Limiting](https://img.shields.io/badge/Rate_Limiting-555?style=flat&logoColor=white)

**Tools**

[![Tools](https://skillicons.dev/icons?i=git,github,bash,linux)](https://skillicons.dev)
![Wireshark](https://img.shields.io/badge/Wireshark-1679A7?style=flat&logo=wireshark&logoColor=white)
![Nmap](https://img.shields.io/badge/Nmap-0E83CD?style=flat&logo=nmap&logoColor=white)

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

### 🔒 [SecureTeam](https://github.com/DevwithMujeeb/secureteam) · [Live Demo](https://secureteam.netlify.app)

Secure RBAC-based team and project management app — security is the core design constraint, not an afterthought.

- Two-layer RBAC — org-level roles + explicit project membership, enforced independently
- JWT access/refresh rotation with httpOnly cookies + token version-based revocation
- Brute-force protection — account lockout (5 attempts) + IP rate limiting, two independent layers
- Atomic registration — User + Organization + Membership created in a single MongoDB transaction
- Full audit logging — every privileged action recorded with actor, target, metadata, timestamp
- Input validation + NoSQL injection sanitization on every write endpoint
- OWASP Top 10 documented — see [SECURITY.md](https://github.com/DevwithMujeeb/secureteam/blob/main/SECURITY.md)

`Node.js` `Express` `MongoDB` `React` `Tailwind` `JWT` `RBAC` `express-validator`

---

## 🚧 In Progress

| Project         | Description                             | Status   |
| --------------- | --------------------------------------- | -------- |
| 📘 CTF Writeups | HackTheBox & TryHackMe methodology docs | Building |

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
