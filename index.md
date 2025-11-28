# Gaetano Vespero – CI/CD & AI Automation Engineer

Welcome to my technical portfolio.  
I design and implement **reliable CI/CD pipelines**, **Docker-based workflows**, and **AI-assisted automation** using GitHub Actions, GitLab CI, Docker, and GitHub Models.

---

## 🔧 Core Skills

- CI/CD: GitHub Actions, GitLab CI
- Languages: Python, Bash
- Containers: Docker, multi-stage builds
- QA: Pytest, Pylint, Mypy, pip-audit
- AI: GitHub Models (LLMs), Azure AI Inference
- Practices: code quality gates, automated testing, DevOps mindset

---

## 📁 Featured Projects

### 1. GitHub Actions CI/CD Template

**Repository:** [ci-cd-template-github-actions](https://github.com/gaetanovespero81/ci-cd-template-github-actions)  

A reusable CI/CD template for Python projects running on GitHub Actions.

- Linting with **Pylint**
- Type checking with **Mypy**
- Unit tests with **Pytest** and JUnit reports
- Virtualenv and dependency management
- Clean workflow structure for production-grade pipelines

---

### 2. Full GitLab CI Pipeline

**Repository:** [gitlab-ci-complete-pipeline](https://gitlab.com/gaetanovespero81/gitlab-ci-complete-pipeline)  

A complete GitLab CI pipeline demonstrating staged quality checks for Python.

- Stages: **lint → type-check → test → build → security**
- Pylint, Mypy, Pytest, pip-audit integration
- Artifacts and caching configured
- Rules for merge requests and main branch protection

---

### 3. Docker Multi-stage Build

**Repository:** [docker-multistage-example](https://github.com/gaetanovespero81/docker-multistage-example)  

A minimal yet realistic example of a **multi-stage Dockerfile** with CI validation.

- Builder + runtime stages for smaller images
- GitHub Actions workflow that:
  - builds the image
  - runs a container
  - validates the output
- Solid starting point for container-based pipelines

---

### 4. AI Code Review Bot

**Repository:** [ai-code-review-bot](https://github.com/gaetanovespero81/ai-code-review-bot)  

An AI-powered code review system that comments on Pull Requests automatically.

- Integrates **GitHub Actions** with **GitHub Models** (LLM: `openai/gpt-4o-mini`)
- Extracts PR diffs and generates structured AI reviews
- Posts feedback directly on the PR
- Stores a detailed review report as an artifact (`ai_review.md`)
- Includes a local Python tool (`bot/review.py`) for manual diff review
- Uses a secure PAT with `models:read` (valid until **25 November 2026**)

---

## 🎯 What I Focus On

- Making pipelines **reliable, fast and readable**
- Adding **AI assistance** where it increases productivity (not just “because AI”)
- Ensuring code quality with automated checks
- Keeping repositories and workflows **well-documented** for teams and hiring managers

---

## 📫 Contact

If you are interested in CI/CD, DevOps or AI automation use cases,  
feel free to reach out via GitHub.

> This portfolio is continuously evolving as I experiment with new workflows, tools and AI integrations.
