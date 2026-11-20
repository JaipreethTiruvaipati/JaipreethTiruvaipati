<div align="center">

# Hey, I'm Jaipreeth 👋

<a href="https://jaipreethtsrls.vercel.app">
  <img src="https://readme-typing-svg.demolab.com/?font=Fira+Code&weight=500&size=20&duration=3200&pause=900&color=00ADD8&center=true&vCenter=true&width=640&lines=Backend+engineer+%C2%B7+Go+%C2%B7+TypeScript+%C2%B7+AWS;I+rebuild+infrastructure+to+see+how+it+works;Built+a+Redis+server+from+scratch+in+Go;Open+to+SDE+roles+%C2%B7+can+join+immediately" alt="Typing intro" />
</a>

<p>
  <a href="https://jaipreethtsrls.vercel.app"><img src="https://img.shields.io/badge/Portfolio-00ADD8?style=for-the-badge&logo=vercel&logoColor=white" alt="Portfolio" /></a>
  <a href="https://www.linkedin.com/in/jaipreethtiruvaipati/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
  <a href="https://x.com/TSRLS_Jaipreeth"><img src="https://img.shields.io/badge/X-000000?style=for-the-badge&logo=x&logoColor=white" alt="X" /></a>
  <a href="https://leetcode.com/u/Tiruvaipati_Jaipreeth/"><img src="https://img.shields.io/badge/LeetCode_Knight-1884-FFA116?style=for-the-badge&logo=leetcode&logoColor=white" alt="LeetCode" /></a>
  <a href="https://codeforces.com/profile/shambho_jp_17"><img src="https://img.shields.io/badge/Codeforces-Specialist-1F8ACB?style=for-the-badge&logo=codeforces&logoColor=white" alt="Codeforces" /></a>
  <a href="mailto:jaipreeth17programming@gmail.com"><img src="https://img.shields.io/badge/Email-me-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" /></a>
</p>

</div>

```go
type Engineer struct {
    Name       string
    Studying   string
    Focus      []string
    Shipped    []string
    LookingFor string
}

var me = Engineer{
    Name:       "Jaipreeth Tiruvaipati",
    Studying:   "B.Tech Mathematics & Computing, IIIT Gwalior '27 (CGPA 9.39, Batch Rank 1)",
    Focus:      []string{"backend", "distributed systems", "concurrency", "databases"},
    Shipped:    []string{"Flagright (YC W22)", "Acadza", "C3iHub, IIT Kanpur"},
    LookingFor: "SDE / backend roles, full-time or internship, remote or on-site",
}
```

---

## 🔨 Things I've built

### [MyRedis](https://github.com/JaipreethTiruvaipati/REDIS) · a Redis server from scratch · [live console ↗](https://redis-chi.vercel.app)

A friend got asked "how does Redis work inside?" in an interview. I didn't know either, so I wrote one.

- Goroutine-per-connection TCP server with a hand-written RESP parser
- **40+ commands** over 5 data structures, with strict TTL expiry
- Hybrid sorted set for **O(log N)** rank queries
- MULTI/EXEC transactions and channel-driven blocking `BLPOP` / `XREAD`
- React + TypeScript console that shows each request moving through the server

`Go` `TCP` `RESP` `goroutines` `ACL`

### [Pebble](https://github.com/JaipreethTiruvaipati/Pebble) · your impulse buys, quietly invested

Upload a UPI receipt. Pebble scores each item for impulsiveness, and the penalty goes into ETF, gold and bond portfolios.

- **7 Go microservices** on RabbitMQ topic exchanges with auto-bound dead-letter queues
- Google Vision OCR → Gemini scoring, with a Redis hash cache (7-day TTL) so nothing gets scored twice
- RS256 JWT auth and a Redis token-bucket rate limiter at 100 req/min

`Go` `PostgreSQL` `Redis` `RabbitMQ` `Gemini` `AWS`

### More builds

| Project | What it does |
|---|---|
| [**Tripora**](https://github.com/JaipreethTiruvaipati/cabflow) | Job scheduler on a 3+ node cluster. Kill or freeze any node and no job is lost, no alert is sent twice. Go + PostgreSQL only. |
| [**CONTRAST**](https://github.com/JaipreethTiruvaipati/Contrast) | Scans SafeTensors model files for tampering without executing them. Outputs JSON, SARIF and CycloneDX ML-BOM. |
| [**InferenceGym**](https://github.com/JaipreethTiruvaipati/InferenceGym) | RL environment for LLM-serving decisions. |

---

## 💼 Where I've worked

| Company | Role | What I did |
|---|---|---|
| **Flagright (YC W22)** · Sep–Nov 2026 | Software Developer Intern | Backend for an AML compliance platform: transaction monitoring, sanctions screening, rule evaluation. TypeScript, AWS, DynamoDB, ClickHouse, OpenSearch. |
| **Acadza** · Feb–Apr 2026 | Software Engineering Intern | AI ingestion pipeline that cut cost per question **85%** (₹10 → ₹1.5). Equation accuracy **40% → 92%**, duplicate precision **78% → 94%** across 50K+ questions. |
| **C3iHub, IIT Kanpur** · May–Aug 2025 | Software Developer Intern | Go backend for blockchain-backed credential verification covering 10K+ student records, with role-based JWT auth and a PostgreSQL schema tuned for fast lookups. |

---

## 🌍 Open source: unitaryHACK 2026 ($600, 3 bounties)

- **[Piquasso #598](https://github.com/Budapest-Quantum-Computing-Group/piquasso/pull/598)**: `density_matrix` rebuilt on a shared Hermite recurrence, **250–400x faster**
- **[Clifft #132](https://github.com/unitaryfoundation/clifft/pull/132)**: phase-polynomial T-count optimization pass, runtime cut from 20 s to 35 ms during review
- **[Quantum Universal Education #59](https://github.com/Quantum-Universal-Education/Quantum-Universal-Education.github.io/pull/59)**: benchmarking tutorial across Qiskit, Cirq, PennyLane, Qibo and Braket

---

## 🏆 Competitive programming

- **Meta Hacker Cup 2025**: global rank 1,253 (top 9%), qualified for Round 2
- **LeetCode Knight** (1884), peak global ranks 285 and 292 in biweekly contests, 1100+ problems solved
- **Codeforces Specialist** (max 1450)

---

## 🧰 Tools

<p align="center">
  <img src="https://skillicons.dev/icons?i=go,ts,js,py,cpp,postgres,redis,rabbitmq,dynamodb,aws,docker,githubactions,git,linux,react&perline=15" alt="Go, TypeScript, JavaScript, Python, C++, PostgreSQL, Redis, RabbitMQ, DynamoDB, AWS, Docker, GitHub Actions, Git, Linux, React" />
</p>

<div align="center">

**Hiring for backend? I can start right away.** [Say hi →](mailto:jaipreeth17programming@gmail.com)

</div>
