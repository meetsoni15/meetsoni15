<img src="assets/header.svg" alt="Meet Soni — Backend, Cloud &amp; IoT Engineer" width="100%">

<p align="center">
  <a href="https://meetsoni.me"><b>Portfolio</b></a> &nbsp;·&nbsp;
  <a href="https://meetsoni.me/blog"><b>Writing</b></a> &nbsp;·&nbsp;
  <a href="https://www.linkedin.com/in/meetsoni1511"><b>LinkedIn</b></a> &nbsp;·&nbsp;
  <a href="https://www.credly.com/badges/8f8bd291-ef49-442d-9438-1a6b989b2fac"><b>CKA</b></a> &nbsp;·&nbsp;
  <a href="mailto:meet@meetsoni.me"><b>Email</b></a>
</p>

<br>

I write Go, run it on Kubernetes, and build the React front ends that sit on top. I've shipped
IoT systems that stream live video out of emergency callboxes, search platforms that query
hundreds of millions of records, and terminal tools for problems that annoyed me enough to fix.
Certified Kubernetes Administrator. These days I lead a small team, which means I write less
code and think harder about the code that gets written.

<br>

## What I can build

<img src="assets/architecture.svg" alt="Systems I build end to end: devices and edge with IoT callboxes and MQTT, ingest with API Gateway and Lambda, processing with Go services and queues, data with PostgreSQL and vector search, interface with React and Next.js — all on Kubernetes" width="100%">

Most engineers own one column of that diagram. I've shipped all five — the callbox on the wall,
the Lambda that catches its telemetry, the Go worker that processes it, the database it lands
in, and the dashboard someone actually looks at.

<br>

## Currently building

**[trending-radar](https://github.com/meetsoni15/trending-radar)** — a radar for new GitHub repos
that rebuilds itself every Monday from a GitHub Action. No manual curation: it queries the Search
API for repos created in the last seven days across AI tooling, security, developer tools, and
infrastructure, then rewrites its own README with the results. I got tired of finding good
projects three months late.

## Projects

<table>
<tr>
  <td width="200"><b><a href="https://github.com/meetsoni15/trending-radar">trending-radar</a></b></td>
  <td>Self-updating list of new and trending GitHub repos, refreshed weekly by a GitHub Action</td>
  <td width="150"><sub><code>Go</code> <code>Actions</code></sub></td>
</tr>
<tr>
  <td><b><a href="https://github.com/meetsoni15/gitcinema">gitcinema</a></b></td>
  <td>Step through your git history like a movie — live file changes, author characters, and a timeline scrubber</td>
  <td><sub><code>Go</code> <code>Bubble Tea</code></sub></td>
</tr>
<tr>
  <td><b><a href="https://github.com/meetsoni15/noisemap">noisemap</a></b></td>
  <td>Finds your codebase's riskiest files by combining cyclomatic complexity with git churn, then draws the heatmap in your terminal</td>
  <td><sub><code>Go</code> <code>AST</code></sub></td>
</tr>
<tr>
  <td><b><a href="https://github.com/meetsoni15/Vault-API-Filecoin">Vault-API-Filecoin</a></b></td>
  <td>HTTP API serving unlockable content out of an immutable Filecoin-backed store</td>
  <td><sub><code>Go</code> <code>Filecoin</code></sub></td>
</tr>
<tr>
  <td><b><a href="https://github.com/meetsoni15/go-lambda-scraper">go-lambda-scraper</a></b></td>
  <td>Rotating-IP scraping infrastructure spread across multi-region AWS Lambda</td>
  <td><sub><code>Go</code> <code>Terraform</code></sub></td>
</tr>
<tr>
  <td><b><a href="https://github.com/meetsoni15/Go-Web-Testify">Go-Web-Testify</a></b></td>
  <td>Unit-testing patterns for Go web applications</td>
  <td><sub><code>Go</code> <code>Testify</code></sub></td>
</tr>
<tr>
  <td><b><a href="https://github.com/meetsoni15/Dodge-the-Falling-Blocks">Dodge-the-Falling-Blocks</a></b></td>
  <td>An arcade game, because not everything needs a business case</td>
  <td><sub><code>Go</code> <code>Raylib</code></sub></td>
</tr>
</table>

<br>

<img src="assets/stack.svg" alt="What I work with — backend and cloud: Go, Kubernetes, Docker, Helm, Terraform, AWS, Linux, Nginx; data and observability: PostgreSQL, MongoDB, Redis, MySQL, Prometheus, Grafana, Python, Bash; frontend: React, Next.js, TypeScript, Tailwind, Sass, JavaScript, HTML5, Vite" width="100%">

<br>

## Shipped in production

- **An emergency callbox network.** IoT devices talking to AWS serverless — ingestion, routing, and notifications out to authorities when someone presses the button.
- **A personal-security app** with live video streaming, recording, and real-time monitoring on AWS.
- **75 Python microservices consolidated into one Go monorepo**, driven by a single config file.
- **Search across hundreds of millions of records** — PostgreSQL functions that take new query shapes without a redeploy, plus vector search with scalable metadata.
- **Queue-driven pipelines** that replaced synchronous execution: concurrency control, retries that back off, and workers that say when they're degrading instead of after they're down.
- **Tracing across every service in the org**, so debugging stopped being archaeology.
- **The front ends too** — React dashboards for the people who have to operate all of the above, and [meetsoni.me](https://meetsoni.me), built with React and Vite.

<br>

<img src="assets/opensource.svg" alt="Open source: 18 public repositories, 222 commits, first push 2017, 81.8% Go" width="100%">

<br>

## Writing

- [**Go Internals: The Runtime Deep Dive Most Developers Miss**](https://meetsoni.me/blog/go-internals-runtime-deep-dive) — the M-P-G scheduler, escape analysis, and GC tuning
- [**Advanced Go Concurrency Patterns**](https://meetsoni.me/blog/go-concurrency-patterns-advanced) — worker pools, fan-in/fan-out, and how not to leak goroutines
- [**noisemap — Visualize Your Codebase's Riskiest Files**](https://meetsoni.me/blog/noisemap-codebase-risk-heatmap) — why complexity × churn predicts where bugs live
- [**Dependency Injection in Go**](https://meetsoni.me/blog/go-dependency-injection-patterns) — interfaces, constructors, and when not to bother
- [**Go's `defer` Keyword**](https://meetsoni.me/blog/go-defer-keyword-deep-dive) — LIFO ordering and the argument-evaluation gotcha

<br>

<img src="assets/journey.svg" alt="Timeline: 2017 first job in support engineering, 2018 in-house ERP, 2019 product work, 2022 all-in on Go, 2024 technical lead, 2026 leading a team and CKA certified" width="100%">

<br>

---

<p align="center">
  <sub>Always up for a conversation about Go, Kubernetes, IoT, or platform architecture — <a href="mailto:meet@meetsoni.me">meet@meetsoni.me</a></sub>
</p>
