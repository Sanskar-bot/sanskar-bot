<!-- ============================================================
     Sanskar Phougat — GitHub Profile README
     Repo: Sanskar-bot/Sanskar-bot/README.md
     ============================================================ -->

<div align="center">

```
╔══════════════════════════════════════════════════════════════╗
║                                                              ║
║   S A N S K A R   P H O U G A T                             ║
║   ─────────────────────────────                             ║
║   Security Engineer  ·  Cryptography  ·  Backend Systems    ║
║   B.Tech ECE @ JIIT Noida  ·  Class of 2027                 ║
║                                                              ║
╚══════════════════════════════════════════════════════════════╝
```

[![Typing SVG](https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=16&duration=3000&pause=1000&color=00D9FF&center=true&vCenter=true&multiline=true&repeat=true&width=600&height=80&lines=Breaking+encryption+so+you+don't+have+to.;RSA+%7C+AES-GCM+%7C+MITM+%7C+Threat+Modelling;Building+systems+that+assume+breach.)](https://git.io/typing-svg)

<br/>

[![LinkedIn](https://img.shields.io/badge/LinkedIn-sanskar--phougat-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/sanskar-phougat)
[![GitHub](https://img.shields.io/badge/GitHub-Sanskar--bot-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Sanskar-bot)
[![TryHackMe](https://img.shields.io/badge/TryHackMe-Top_15%25_Globally-212C42?style=for-the-badge&logo=tryhackme&logoColor=red)](https://tryhackme.com/p/Sanskar2003)
[![Mail](https://img.shields.io/badge/Email-sanskarphougat2004@gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:sanskarphougat2004@gmail.com)

</div>

---

## `whoami`

```python
sanskar = {
    "role"        : "Security-focused Backend Engineer",
    "education"   : "B.Tech ECE @ JIIT Noida (2023 – 2027)",
    "location"    : "Noida, Uttar Pradesh, India",
    "focus"       : ["Applied Cryptography", "Secure Systems", "Backend Engineering"],
    "building"    : "Systems that assume breach — encrypt everything, trust nothing.",
    "teaching"    : "Cryptography Workshop Instructor @ AI Tronics Society (40+ students)",
    "open_to"     : "Cybersecurity / Security-focused SWE Internships",
}
```

> I build systems where security isn't bolted on — it's the architecture.
> RSA key swaps, AES-GCM session interception, zero plaintext at rest.
> If it can be broken, I want to break it first.

---

## `cat projects.txt`

<table>
<tr>
<td width="50%" valign="top">

### 🔐 E2E Encryption Attack Lab
**`Python · mitmproxy · Burp Suite · Wireshark · Flask`**

A 3-act live demonstration of why encryption alone isn't enough.

| Act | What MITM sees |
|-----|---------------|
| Plaintext chat | Every message |
| RSA + AES-GCM (unverified) | Full plaintext via key swap |
| + Fingerprint verification | **Nothing — session aborts** |

Built for CyberPeace Foundation assignment. Features a live attacker dashboard (Flask API + real-time feed), `threading.Event`-based session pairing, and mitmproxy professional tool integration.

[![Repo](https://img.shields.io/badge/View_Repo-181717?style=flat-square&logo=github)](https://github.com/Sanskar-bot/E2E-Encryption-Attack-Lab)

</td>
<td width="50%" valign="top">

### 🏥 SecureHealth — Decentralized Medical Records
**`Flask · AES-256-GCM · RSA-2048 · Windows DPAPI · GitHub Actions`**

Zero-trust medical data platform. Client-side encryption enforced — server never sees plaintext. Hybrid RSA+AES key wrapping with OS-backed private key storage (Windows DPAPI) to eliminate key exfiltration vectors.

- 3 microservices with custom middleware
- Time-bound access tokens
- 85%+ integration test coverage
- Zero plaintext exposure at rest

[![Repo](https://img.shields.io/badge/View_Repo-181717?style=flat-square&logo=github)](https://github.com/Sanskar-bot/medical-data-decentralisation)

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 🎯 PhishGuard — Real-Time URL Threat Detection
**`Python · ML · PostgreSQL · REST API · CI/CD`**

Real-time phishing detection engine with async ML inference pipeline.

```
Accuracy    : 90% on 500+ samples
Latency     : < 80ms p99
Uptime      : 99.9% under load testing
OSINT       : 15+ email header parameters
```

Partitioned PostgreSQL audit tables, stateless architecture for horizontal scaling, automated OSINT-based domain/IP reputation checks.

[![Repo](https://img.shields.io/badge/View_Repo-181717?style=flat-square&logo=github)](https://github.com/Sanskar-bot/PhishingCheck4U)

</td>
<td width="50%" valign="top">

### 📹 VaultStream — Encrypted Media Storage
**`Python · AES-256 · RSA · Docker · Cloud`**

AES-256/RSA hybrid encryption platform for media files up to 500MB.

```
Latency     : sub-100ms p99
Coverage    : 85%+ unit + integration tests
Exposure    : zero plaintext at rest
Access      : key-scoped per session
```

Chunked streaming pipeline with cloud-backed storage and Docker-containerized deployment.

[![Repo](https://img.shields.io/badge/View_Repo-181717?style=flat-square&logo=github)](https://github.com/Sanskar-bot/secure-media-encryption)

</td>
</tr>
<tr>
<td width="50%" valign="top">

### ⚙️ TaskFlow — Task Management REST API
**`Java · Spring Boot · PostgreSQL · PL/SQL · JUnit 5 · GitHub Actions`**

Production-grade CRUD API with JWT auth, layered OOP architecture, and stored procedures in PL/SQL.

- SQL query optimization via execution plans + index tuning
- CI/CD pipeline with GitHub Actions
- 80%+ code coverage across 15+ test suites (JUnit 5 + Mockito)

[![Repo](https://img.shields.io/badge/View_Repo-181717?style=flat-square&logo=github)](https://github.com/Sanskar-bot)

</td>
<td width="50%" valign="top">

### 📓 Daily Learning Log
**`Markdown · Consistency · Growth`**

A public daily log of everything I learn — tracked every day since April 2026.

Each entry documents: what I learned, what I built, challenges solved, open questions, and resources used. Not a highlight reel — a honest engineering journal.

```
Entries     : 17+ days and counting
Topics      : Cryptography, Backend, Security, 
              Mobile Comms, Salesforce, Interviews
Format      : Structured markdown with stats tables
```

[![Repo](https://img.shields.io/badge/View_Log-181717?style=flat-square&logo=github)](https://github.com/Sanskar-bot/Daily-Learnings)

</td>
</tr>
</table>

---

## `cat skills.json`

```json
{
  "languages"     : ["Python", "Java", "C++", "SQL", "JavaScript"],
  "frameworks"    : ["Spring Boot", "Flask", "REST APIs", "React.js"],
  "cryptography"  : ["AES-256-GCM", "RSA-2048", "SHA-256 Fingerprinting",
                     "Hybrid Encryption", "Key Wrapping", "Secure Key Derivation"],
  "security_tools": ["Burp Suite", "Wireshark", "Metasploit", "mitmproxy",
                     "Nmap", "FFUF", "Splunk SIEM", "OWASP Top 10"],
  "databases"     : ["PostgreSQL", "MySQL", "MongoDB", "Redis", "SQLite", "PL/SQL"],
  "cloud_devops"  : ["AWS (EC2, S3)", "Docker", "GitHub Actions", "CI/CD", "Linux"],
  "testing"       : ["JUnit 5", "Mockito", "Postman", "REST API Testing"],
  "concepts"      : ["STRIDE Threat Modelling", "Zero-Trust Architecture",
                     "MITM Attack Simulation", "CIA Triad", "TOFU",
                     "System Design", "Microservices", "ACID", "OOP Design Patterns"]
}
```

---

## `./certifications --list`

| Certificate | Issuer | Focus |
|-------------|--------|-------|
| Google Cybersecurity Professional Certificate | Google | Networking, threat analysis, Linux, SOC workflows |
| AWS Cloud Practitioner Essentials | Amazon Web Services | Compute, networking, storage, IAM |
| TryHackMe — Junior Security Professional | TryHackMe | OWASP Top 10, web exploitation, CTF · **Top 15% globally** |
| Salesforce Trailhead | Salesforce | Data modeling, platform basics, AI fundamentals |

---

## `./leadership --verbose`

```
Position   : Technical Head — AI Tronics Society, JIIT Noida
Duration   : August 2023 – Present

Delivered  : Applied Cryptography Workshop (AES-256, RSA-2048, padding oracle attacks)
Audience   : 40+ students
Also ran   : Semester-wide workshops on Python, Git, DSA, and Cryptography for 100+ students
Method     : Agile sprint model with per-cycle feedback loops
```

---

## `git log --oneline --graph`

<div align="center">

![GitHub Stats](https://github-readme-stats.vercel.app/api?username=Sanskar-bot&show_icons=true&theme=dark&hide_border=true&bg_color=0d1117&title_color=00d9ff&icon_color=00d9ff&text_color=ffffff&rank_icon=github)

![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=Sanskar-bot&layout=compact&theme=dark&hide_border=true&bg_color=0d1117&title_color=00d9ff&text_color=ffffff)

![GitHub Streak](https://streak-stats.demolab.com?user=Sanskar-bot&theme=dark&hide_border=true&background=0d1117&ring=00d9ff&fire=00d9ff&currStreakLabel=00d9ff)

</div>

---

## `./philosophy.sh`

```bash
#!/bin/bash
# My approach to security engineering

echo "Encrypt everything."
echo "Verify keys out-of-band."
echo "Assume the network is hostile."
echo "Log everything, expose nothing."
echo "A system that can be broken will be broken."
echo "Break it first."
```

---

<div align="center">

```
┌─────────────────────────────────────────────────────────────┐
│  Actively seeking: Cybersecurity / Security SWE Internship  │
│  Available: Immediately · Location: Noida, India / Remote   │
│  Contact: sanskarphougat2004@gmail.com                      │
└─────────────────────────────────────────────────────────────┘
```

![Visitor Count](https://komarev.com/ghpvc/?username=Sanskar-bot&style=flat-square&color=00d9ff&label=Profile+Views)

*"The algorithm is public. Only the key is secret." — Kerckhoffs's Principle*

</div>
