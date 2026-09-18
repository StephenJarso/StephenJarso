# Hi, I'm Stephen Jarso 👋

## Backend engineer building dependable systems for real-world problems

I design and ship production-minded software across backend engineering, developer tooling, payments, security, and AI-assisted workflows. My strongest work sits at the intersection of reliable APIs, resilient data systems, and products that help people make better decisions.

> **Currently focused on:** ApplyCanary, a job-search and interview assistant; secure_push, a commit-time security scanner; and Karada, a Lightning Network escrow engine for emerging-market commerce.

[![Open to work](https://img.shields.io/badge/Open%20to-full--time%20%2F%20contract-1D9E75?style=flat-square)](mailto:stephenjacob815@gmail.com)

- 🔧 Backend systems, payment integrations, security tooling, and distributed workflows
- 🧠 AI products with human review, truthfulness checks, and useful fallbacks
- 🧩 Full-stack when needed: React, Next.js, Vue, and Flutter
- 🌍 Based in Nairobi, Kenya · open to remote opportunities and interesting collaborations

---

## Featured project: ApplyCanary

[![ApplyCanary](https://img.shields.io/badge/Live%20demo-Visit%20ApplyCanary-1D9E75?style=flat-square)](https://frontend-xi-seven-1v1qypqssw.vercel.app) [![Source](https://img.shields.io/badge/Source-GitHub-181717?logo=github&logoColor=white&style=flat-square)](https://github.com/StephenJarso/applycanary)

**ApplyCanary** is an agentic job-search assistant that finds and scores roles, truthfully tailors applications, and helps candidates practise interviews out loud. It is designed around persistent memory so coaching improves across sessions instead of resetting every time.

### The engineering story

- **Discovery:** Connects to company ATS boards and aggregators, deduplicates cross-posted roles, and searches for roles based on a candidate's actual titles, skills, and GitHub evidence.
- **Grounded applications:** Combines deterministic filters with LLM reasoning, then runs a truth-check pass so generated CV claims remain backed by real experience.
- **Voice interview coaching:** Uses Amazon Transcribe and Polly when configured, with browser speech fallbacks for local development.
- **Durable memory:** Stores interview state and semantic memories in CockroachDB using native vectors and distributed indexes.
- **Resilient operations:** Runs with AWS services in production but degrades gracefully to local inference, browser speech, SQLite, and heuristic behavior during development.

**Impact:** This architecture turns a fragmented job hunt into a repeatable, evidence-based workflow while keeping safety boundaries in code rather than relying only on prompts.

**Stack:** Python, FastAPI, React, TypeScript, CockroachDB, SQLModel, AWS Bedrock, Polly, Transcribe, S3, ECS/Fargate, Docker, Vercel.

[Read the architecture and setup guide →](https://github.com/StephenJarso/applycanary#readme)

---

## Other selected work

- **[secure_push](https://github.com/StephenJarso/secure_push)** — Developer-first security scanner that catches secrets, risky configuration, and unsafe AI-generated code at commit time and in CI.
- **[karada](https://github.com/StephenJarso/karada)** — Programmable Lightning Network escrow engine using HODL invoices and courier-data oracles for emerging-market commerce.
- **[kinga](https://github.com/StephenJarso/kinga)** — Anticipatory-action trigger and activation engine that turns early-warning thresholds into tracked, auditable action.

---

## Technical toolkit

| Area | Tools |
| --- | --- |
| **Backend** | Go, Python, FastAPI, REST APIs, background workers, distributed systems |
| **Frontend** | TypeScript, JavaScript, React, Next.js, Vue, Flutter |
| **Data** | PostgreSQL, CockroachDB, MySQL, SQLite, Firebase, vector search |
| **Cloud & delivery** | AWS, ECS/Fargate, S3, Docker, Vercel, GitHub Actions |
| **AI & voice** | Bedrock, LLM provider fallbacks, embeddings, Amazon Polly, Transcribe |
| **Quality & security** | Pytest, Ruff, CI/CD, secret scanning, truthfulness gates, least-privilege IAM |

---

## Case study: building ApplyCanary around trust

**Challenge:** Job seekers need speed, but automated applications can easily produce generic or inaccurate claims.

**Approach:** I split the pipeline into deterministic checks and model-assisted reasoning. Candidate evidence is used to ground tailoring, and a separate truth-check gate blocks unsupported claims before an application can proceed. Interview sessions are persisted as both transactional state and semantic memory, allowing coaching to build over time.

**Result:** A working MVP with job discovery, scoring, resume tailoring, interview coaching, email alerts, persistent memory, local fallbacks, and an explicit manual-review boundary for submission. The system currently includes a broad automated test suite covering auth, ATS flows, deduplication, truth checking, vector search, memory, discovery, email, and LLM fallback behavior.

---

## Open-source contributions

### Go source tree

- [CL 807420](https://go-review.googlesource.com/c/go/+/807420) — `cmd/compile`: corrected typographical errors in comments
- [CL 807600](https://go-review.googlesource.com/c/go/+/807600) — `go/types`, `cmd/compile`: used slices and `cmp` instead of `sort`
- [CL 799721](https://go-review.googlesource.com/c/go/+/799721) — corrected an arm64 SSA comment

### Other merged work

- [alibaba/open-code-review #590](https://github.com/alibaba/open-code-review/pull/590) — comprehensive `resume.go` test coverage
- [Flying-Tea-Squad/chama-application #56](https://github.com/Flying-Tea-Squad/chama-application/pull/56) and [#59](https://github.com/Flying-Tea-Squad/chama-application/pull/59) — SMS-provider authentication work
- [odingaval/veryfy #5](https://github.com/odingaval/veryfy/pull/5) — license-type dropdown visibility fix
- [firstcontributions/first-contributions #119079](https://github.com/firstcontributions/first-contributions/pull/119079) — contributor listing update

---

## GitHub activity

[![Profile details](https://raw.githubusercontent.com/StephenJarso/StephenJarso/main/profile-summary-card-output/2077/0-profile-details.svg)](https://github.com/vn7n24fzkq/github-profile-summary-cards)

[![Repositories by language](https://raw.githubusercontent.com/StephenJarso/StephenJarso/main/profile-summary-card-output/2077/1-repos-per-language.svg)](https://github.com/vn7n24fzkq/github-profile-summary-cards)
[![Most committed language](https://raw.githubusercontent.com/StephenJarso/StephenJarso/main/profile-summary-card-output/2077/2-most-commit-language.svg)](https://github.com/vn7n24fzkq/github-profile-summary-cards)

[![GitHub stats](https://github-readme-stats.vercel.app/api?username=StephenJarso&show_icons=true&theme=react&hide_border=true&rank_icon=github)](https://github.com/StephenJarso)
[![Top languages](https://github-readme-stats.vercel.app/api/top-langs/?username=StephenJarso&layout=compact&theme=react&hide_border=true)](https://github.com/StephenJarso)

---

## Contact and availability

I am open to backend, platform, security, and AI-product opportunities, including remote roles and contract collaborations.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?logo=linkedin&logoColor=white)](https://www.linkedin.com/in/stephenjarso/)
[![Email](https://img.shields.io/badge/Email-D14836?logo=gmail&logoColor=white)](mailto:stephenjacob815@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-181717?logo=github&logoColor=white)](https://github.com/StephenJarso)

---

<sub>Profile statistics are refreshed automatically from genuine repository activity. Automation in this repository only commits when generated assets actually change; it does not create artificial activity.</sub>
