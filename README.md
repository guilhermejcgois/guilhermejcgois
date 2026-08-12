<h1 align="center">Guilherme Gois</h1>

<p align="center">
  <strong>Backend · Cloud · DevOps · Software Engineering</strong><br/>
  I build, deploy, and troubleshoot production software.
</p>

<p align="center">
  <code>Node.js / NestJS</code> · <code>AWS / Terraform</code> · <code>Docker</code> · <code>PostgreSQL</code> · <code>CI/CD</code> · <code>Observability</code>
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/guilhermejcgois/">
    <img alt="LinkedIn" src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"/>
  </a>
  <a href="mailto:guilhermejcgois@outlook.com">
    <img alt="Email" src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white"/>
  </a>
</p>

<p align="center">
  <sub>Tech Lead @ <b>Monte Bravo</b> · São Paulo, Brazil</sub>
</p>

---

## About

Tech Lead with hands-on experience designing production systems, cloud infrastructure, engineering standards, and developer workflows. I lead teams and ship code — not one or the other.

Currently building backend services, cloud infrastructure, and internal tooling at [Monte Bravo](https://github.com/MonteBravo).

---

## What I deliver

| Area | Capabilities |
|------|-------------|
| **Backend** | REST/GraphQL APIs, event-driven architecture, message brokers, NestJS, Node.js, Python |
| **Cloud & Infra** | AWS (ECS/Fargate, RDS, S3, IAM), Terraform, Docker, networking |
| **CI/CD** | GitHub Actions, automated releases, branching strategies, deployment pipelines |
| **Observability** | Health checks, metrics endpoints, structured logging, monitoring |
| **Data** | PostgreSQL, MongoDB, migrations, Airflow + DBT pipelines |
| **Engineering** | Architecture decisions (ADRs), code review standards, monorepo strategy (Nx), DX tooling |

---

## How I work

- **ADR before code** — if I can't explain the decision in 3 paragraphs, I don't build it
- **PRs under 400 lines** — beyond that, I stack
- **CI is non-negotiable** — lint + type-check + test before any merge
- **Observability first** — if there's no metric, it's not in prod
- **Runbooks for every critical path** — not tribal knowledge

---

## Featured projects

| Project | What it demonstrates |
|---------|---------------------|
| [tf-flask-fargate](https://github.com/guilhermejcgois/tf-flask-fargate) | AWS ECS/Fargate + Terraform IaC + GitHub Actions CI/CD pipeline |
| [automatic-releasing-workflow](https://github.com/guilhermejcgois/automatic-releasing-workflow) | Automated release & hotfix workflows with GitHub Actions, tags, and changelogs |
| [sre-prova-nivel1](https://github.com/guilhermejcgois/sre-prova-nivel1) | Docker deploy/rollback scripts + health checks + metrics endpoint + CI |
| [feedcli](https://github.com/guilhermejcgois/feedcli) | Python CLI tool — RSS reader with rich terminal UI, semantic-release, pytest |
| [dotfiles](https://github.com/guilhermejcgois/dotfiles) | Dev environment as code — Zsh, yadm, Kiro steering files, multi-OS bootstrap |

---

## Tech stack

```
Backend:      Node.js, NestJS, Python, Flask, REST, GraphQL, RabbitMQ
Cloud:        AWS (ECS, Fargate, RDS, S3, IAM), Terraform, Docker
CI/CD:        GitHub Actions, semantic-release, changesets
Data:         PostgreSQL, MongoDB, Airflow, DBT
Frontend:     Angular, React, Next.js, TypeScript, Storybook
Tooling:      Nx monorepo, pnpm, Volta, Vitest, Playwright, ESLint, Prettier
```

---

## Tooling philosophy

| Layer | Choice |
|-------|--------|
| Runtime | Node via Volta/fnm, Python via uv |
| Package manager | pnpm (lockfile + workspaces) |
| Monorepo | Nx (cache, affected, boundary lint) |
| Quality | ESLint + Prettier, tsc strict, Vitest/Jest, Playwright/Cypress |
| CI | GitHub Actions with lint → type-check → test → build gates |
| Release | Changesets or semantic-release, automated changelog |
| Containers | Docker multi-stage builds, devcontainers |

---

## Contact

- **LinkedIn:** [guilhermejcgois](https://www.linkedin.com/in/guilhermejcgois/)
- **Email:** [guilhermejcgois@outlook.com](mailto:guilhermejcgois@outlook.com)

---

<sub>Solid engineering, clear decisions, reliable delivery. Let's talk.</sub>
