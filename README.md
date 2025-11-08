# DevSecOps Awareness Project (CI/CD + Static Code Analysis)

[![CI Pipeline](https://github.com/ayesha2124/simple-api/actions/workflows/ci.yml/badge.svg)](https://github.com/ayesha2124/simple-api/actions/workflows/ci.yml)
[![CodeQL Analysis](https://github.com/ayesha2124/simple-api/actions/workflows/codeql.yml/badge.svg)](https://github.com/ayesha2124/simple-api/actions/workflows/codeql.yml)
[![Secret Scanning Workflow](https://github.com/ayesha2124/simple-api/actions/workflows/secret-scan.yml/badge.svg)](https://github.com/ayesha2124/simple-api/actions/workflows/secret-scan.yml)

---

##  Overview  
This repository demonstrates a **secure and automated CI/CD pipeline** setup for a simple API project.  

---
## Objective
- Demonstrate DevSecOps principles by setting up automated CI/CD pipelines for a Node.js API.
- Implement quality gates including linting, automated testing, static code analysis, and secret scanning.
- Ensure secure and reliable software delivery through automated validation at every code change.

---

##  Features  
-  Code Quality checks using **ESLint**  
-  **CodeQL Analysis** for vulnerability detection  
-  **Secret Scanning** with TruffleHog  
-  **Automated Testing** via GitHub Actions  

---

## Setup Steps
1. **Clone the repository**
```bash
git clone https://github.com/ayesha2124/simple-api
cd simple-api
npm install
Run API locally

bash
Copy code
node src/index.js
Access endpoint: http://localhost:3000/health

Run tests locally

bash
Copy code
npm test

---
##  Workflows  
| Workflow | Purpose |
|-----------|----------|
| **CI Pipeline** | Runs lint and test steps |
| **CodeQL Analysis** | Scans for code vulnerabilities |
| **Secret Scanning** | Detects exposed secrets or tokens |

---

##Challenges / Learnings

Configuring CodeQL correctly to scan Node.js code required careful setup.

Integrating multiple automated checks in a single workflow took debugging of triggers.

Ensuring secret scanning blocks commits without affecting normal pushes was tricky.

Learned how automated DevSecOps pipelines improve code reliability and security.

---

##  Tech Stack  
- **Node.js**  
- **GitHub Actions**  
- **ESLint**  
- **TruffleHog**  
- **CodeQL**

---

 **All workflows are currently passing successfully!**
