# 🚀 First GitHub Actions Workflow

This repository demonstrates my **first hands-on experience with GitHub Actions**, focusing on understanding how **CI workflows** work in real projects.

The goal of this project is to learn:
- How GitHub Actions are triggered
- How workflows are structured
- How automation fits into modern DevOps practices

---

## 📌 What This Repository Covers

- ✅ Creating a GitHub Actions workflow
- ✅ Understanding `main.yml` structure
- ✅ Running jobs on push and pull request events
- ✅ Using GitHub-hosted runners
- ✅ Basic CI automation concepts

---

## 🧠 Why GitHub Actions?

GitHub Actions allows developers to **automate workflows directly inside GitHub**, such as:
- Continuous Integration (CI)
- Automated testing
- Code linting
- Build & deployment pipelines

This repository serves as my **starting point in DevOps**, helping me understand automation before moving to more advanced CI/CD setups.

---

## ⚙️ Workflow Overview

The workflow in this repository:
- Triggers on **push** (and/or pull request)
- Runs on a **GitHub-hosted runner**
- Executes basic steps like:
  - Checking out the repository
  - Running sample commands/scripts

This helps build a strong foundation for future pipelines involving:
- Docker
- Testing frameworks
- Deployment automation

---

## 📂 Repository Structure

```text
.
├── .github
│   └── workflows
│       └── main.yml
├── README.md
