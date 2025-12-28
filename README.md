# GitHub Actions – Hands-on Practice Repository

This repository contains my **hands-on practice and experiments with GitHub Actions**, based on a complete course that covers GitHub Actions from fundamentals to advanced workflow concepts.

The goal of this repo is to **understand GitHub Actions beyond just CI/CD**, and learn how workflows, jobs, steps, triggers, and commands actually work in real scenarios.

---

## What This Repository Covers

Throughout this repository, I implemented and tested the following GitHub Actions concepts:

### GitHub Actions Overview
- Why GitHub Actions is **more than just CI/CD**
- High-level architecture of GitHub Actions
- Understanding workflows, runners, jobs, and steps

## Workflows & YAML Basics
- Writing GitHub Actions workflows using **YAML**
- Understanding:
  - `name`
  - `on`
  - `jobs`
  - `steps`
- YAML syntax essentials:
  - indentation
  - lists
  - maps
  - expressions

---

## Triggers (Events)
Implemented and tested multiple workflow triggers:

- **Webhook triggers**
  - `push`
  - `pull_request`

- **Scheduled triggers**
  - `schedule` using cron expressions

- **Manual triggers**
  - `workflow_dispatch`

---

## Jobs & Steps
- Defining multiple jobs
- Running jobs on different runners
- Understanding job isolation
- Sequential vs parallel jobs
- Step execution flow

---

## Actions
- Using built-in actions
- Using marketplace actions
- `uses` vs `run`
- Reusable actions concept

---

## Commands & Expressions
- GitHub Actions expressions:
  - `${{ }}` syntax
  - Contexts (`github`, `env`, `jobs`, `steps`)
- Conditional execution using `if`
- Environment variables

---

## Workflow Commands
- Workflow commands such as:
  - setting environment variables
  - logging
  - controlling workflow behavior
- Understanding how commands affect the runner during execution

---

## Purpose of This Repository
- Practice GitHub Actions hands-on
- Build a strong foundation for:
  - CI/CD pipelines
  - DevOps concepts
  - Automation workflows
- Serve as a **reference repo** for future projects

---

## Status
✅ Actively tested  
✅ Educational purpose  
✅ Ready for extension with real CI/CD pipelines

---

## Notes
This repository focuses on **learning and understanding**, not on a specific production application.  
Future improvements may include:
- Real project CI/CD pipelines
- Multi-environment deployments
- Advanced job orchestration

---

Happy Automating 🚀
