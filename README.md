<h1 align="center">Hi there 👋, I'm Yash</h1>
<h3 align="center">Backend Engineer | Workflow Orchestration | Distributed Systems | Python & Go</h3>

<p align="center">
I build the parts of a system that have to be <b>right</b>, not just fast — workflow engines,
async data layers, streaming pipelines, and the compilers and schedulers underneath them.
</p>

<p align="center">
  <a href="https://yashbjoshi-portfolio.netlify.app/"><img src="https://img.shields.io/badge/Portfolio%20%E2%86%97-7C5CFF?style=for-the-badge&logo=data:image/svg%2Bxml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCIgZmlsbD0ibm9uZSIgc3Ryb2tlPSJ3aGl0ZSIgc3Ryb2tlLXdpZHRoPSIyIj48Y2lyY2xlIGN4PSIxMiIgY3k9IjEyIiByPSI5Ii8+PHBhdGggZD0iTTMgMTJoMThNMTIgM2ExNSAxNSAwIDAgMSAwIDE4YTE1IDE1IDAgMCAxIDAtMTgiLz48L3N2Zz4=&logoColor=white" alt="Portfolio" /></a>
  <a href="https://www.linkedin.com/in/yash-b-joshi/"><img src="https://img.shields.io/badge/LinkedIn%20%E2%86%97-0D0F17?style=for-the-badge&logo=data:image/svg%2Bxml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCIgZmlsbD0id2hpdGUiPjxwYXRoIGQ9Ik0yMC40NDcgMjAuNDUyaC0zLjU1NHYtNS41NjljMC0xLjMyOC0uMDI3LTMuMDM3LTEuODUyLTMuMDM3LTEuODUzIDAtMi4xMzYgMS40NDUtMi4xMzYgMi45Mzl2NS42NjdIOS4zNTFWOWgzLjQxNHYxLjU2MWguMDQ2Yy40NzctLjkgMS42MzctMS44NSAzLjM3LTEuODUgMy42MDEgMCA0LjI2NyAyLjM3IDQuMjY3IDUuNDU1djYuMjg2ek01LjMzNyA3LjQzM2MtMS4xNDQgMC0yLjA2My0uOTI2LTIuMDYzLTIuMDY1IDAtMS4xMzguOTItMi4wNjMgMi4wNjMtMi4wNjMgMS4xNCAwIDIuMDY0LjkyNSAyLjA2NCAyLjA2MyAwIDEuMTM5LS45MjUgMi4wNjUtMi4wNjQgMi4wNjV6bTEuNzgyIDEzLjAxOUgzLjU1NVY5aDMuNTY0djExLjQ1MnpNMjIuMjI1IDBIMS43NzFDLjc5MiAwIDAgLjc3NCAwIDEuNzI5djIwLjU0MkMwIDIzLjIyNy43OTIgMjQgMS43NzEgMjRoMjAuNDUxQzIzLjIgMjQgMjQgMjMuMjI3IDI0IDIyLjI3MVYxLjcyOUMyNCAuNzc0IDIzLjIgMCAyMi4yMjIgMGguMDAzeiIvPjwvc3ZnPg==" alt="LinkedIn" /></a>
  <a href="https://twitter.com/_YashBJoshi"><img src="https://img.shields.io/badge/Twitter%20%E2%86%97-0D0F17?style=for-the-badge&logo=x&logoColor=white" alt="Twitter" /></a>
</p>

---

## 🌍 Open Source

<table>
  <tr>
    <td><img src="https://raw.githubusercontent.com/zigflow/zigflow/main/designs/z-logo.png" width="140" alt="Zigflow"></td>
    <td>
      <b><a href="https://github.com/zigflow/zigflow">zigflow/zigflow</a></b>: declarative YAML workflows on Temporal, with no SDK boilerplate.<br><br>
      Zigflow compiles a workflow written in YAML (the CNCF Open Workflow Specification) into a full Temporal workflow, with retries, state management and deterministic execution. Teams get Temporal's durability without writing Go, Java or TypeScript workflow code.<br><br>
      🛠️ <b>Maintainer</b> since October 2026: reviewing PRs, keeping CI and dependencies healthy, and driving the road to v1.<br><br>
      <a href="https://github.com/zigflow/zigflow/pulls?q=is%3Apr+is%3Amerged+author%3AYJ-928"><img src="https://img.shields.io/github/issues-search/zigflow/zigflow?query=is%3Apr%20is%3Amerged%20author%3AYJ-928&label=merged%20PRs&color=2ea44f" alt="Merged PRs"></a>
    </td>
  </tr>
</table>

**Highlights**
- **[#615](https://github.com/zigflow/zigflow/pull/615): activity inputs resolved in the workflow.** Every step now receives, and history records, the exact values the workflow computed, so a run can be debugged from its history alone.
- **[#623](https://github.com/zigflow/zigflow/pull/623): unblocked the project's CI.** A CVE in `golang.org/x/net` had failed the image scan on `main` and on every open PR for two days. The fix brought builds and image publishing back to green.
- **[#591](https://github.com/zigflow/zigflow/pull/591): cancelling a workflow now stops it.** A fork waits for its branches to be cancelled instead of returning while they keep running.

<!-- oss-contributions-ledger:start -->
**12 merged pull requests** across **2 repositories**, and **3 issues** reported. Took part in **9 discussions**. Reviewed **2 pull requests**.

Latest merged:

- [zigflow/zigflow#637](https://github.com/zigflow/zigflow/pull/637): fix(do): register every task list that runs as its own workflow (2026-10-23)
- [zigflow/zigflow#638](https://github.com/zigflow/zigflow/pull/638): fix(tasks)!: set the error instance to a JSON Pointer to the task (2026-10-23)
- [zigflow/zigflow#626](https://github.com/zigflow/zigflow/pull/626): refactor!: remove the GetVersion gates for activity inputs and activity names (2026-10-12)
<!-- oss-contributions-ledger:end -->

Full record: [CONTRIBUTIONS.md](CONTRIBUTIONS.md)

---

## 🧠 What I Work On

- ⚙️ **Workflow orchestration & durable execution** — Temporal, compensation, state you can reason about a week later
- 🧩 **Compilers & DSLs** — graph traversal, lowering, validation, normalisation; the interesting bits are all edge cases
- ⚡ **Async Python at the data layer** — SQLAlchemy 2.0, connection lifecycle, migration discipline
- 🕐 **Scheduling correctness** — recurrence rules, occurrence generation, timezone-aware scheduling
- 🔐 **Auth & access control** — asymmetric JWT, centralised verification, RBAC that holds at the fifth service
- 🎥 **Real-time media** — RTSP, HLS, WebRTC, and the bandwidth arithmetic behind choosing between them
- 🔍 **Observability of distributed work** — tracing an execution back to the intent that produced it

---

## 💻 Tech Stack

**Languages & Frameworks**

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Go](https://img.shields.io/badge/Go-00ADD8?style=for-the-badge&logo=go&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-005571?style=for-the-badge&logo=fastapi&logoColor=white)
![Django](https://img.shields.io/badge/Django-092E20?style=for-the-badge&logo=django&logoColor=white)
![DRF](https://img.shields.io/badge/DRF-ff1709?style=for-the-badge&logo=django&logoColor=white)

**Orchestration & Data**

![Temporal](https://img.shields.io/badge/Temporal-000000?style=for-the-badge&logo=temporal&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-336791?style=for-the-badge&logo=postgresql&logoColor=white)
![SQLAlchemy](https://img.shields.io/badge/SQLAlchemy_2.0-D71F00?style=for-the-badge&logo=sqlalchemy&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white)
![GraphQL](https://img.shields.io/badge/GraphQL-E10098?style=for-the-badge&logo=graphql&logoColor=white)

**Infrastructure**

![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazon-aws&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)

**Media & Protocols**

![FFmpeg](https://img.shields.io/badge/FFmpeg-007808?style=for-the-badge&logo=ffmpeg&logoColor=white)
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=for-the-badge&logo=opencv&logoColor=white)
![WebRTC](https://img.shields.io/badge/WebRTC-333333?style=for-the-badge&logo=webrtc&logoColor=white)

---

## 🎯 Currently

- 🔭 Deep in **workflow orchestration** — compilers, durable execution, making failures legible
- 🐹 Learning **Go** properly, mostly by fixing things in a runtime written in it
- 🌍 **Contributing upstream** instead of carrying patches locally
- ✍️ Getting better at the non-code half — design ownership, root-cause analysis, and writing things down

---

## 📊 Language Breakdown

<p align="left">
  <img height="180" src="profile-summary-card-output/tokyonight/1-repos-per-language.svg" alt="Top languages by repo" />
  <img height="180" src="profile-summary-card-output/tokyonight/2-most-commit-language.svg" alt="Top languages by commit" />
</p>

---

## 👯 Open to Collaborate On

🐍 Python backend & distributed systems · ⚙️ Workflow orchestration & Temporal · 🧩 Compilers, DSLs and developer tooling · 🌍 Open source

---

<div align="center">

**Backend Engineering · Workflow Orchestration · Distributed Systems**

![Profile Views](https://hits.sh/github.com/YJ-928.svg?style=for-the-badge&label=Profile%20views&color=8b5cf6)

</div>
