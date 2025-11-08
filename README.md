# DevSecOps Awareness Project (CI/CD + Static Code Analysis)

[![CI Pipeline](https://github.com/ayesha2124/simple-api/actions/workflows/ci.yml/badge.svg)](https://github.com/ayesha2124/simple-api/actions/workflows/ci.yml)
[![CodeQL Analysis](https://github.com/ayesha2124/simple-api/actions/workflows/codeql.yml/badge.svg)](https://github.com/ayesha2124/simple-api/actions/workflows/codeql.yml)
[![Secret Scanning Workflow](https://github.com/ayesha2124/simple-api/actions/workflows/secret-scan.yml/badge.svg)](https://github.com/ayesha2124/simple-api/actions/workflows/secret-scan.yml)

---

videodemo: https://drive.google.com/file/d/1OIx3Ay2lgBfes9GFVlxkhwdLS9Tnfsdx/view?usp=drive_link

---

## Overview
This repository demonstrates a **secure and automated CI/CD pipeline** setup for a simple Node.js API project.

---

## Objective
- Demonstrate DevSecOps principles by setting up automated CI/CD pipelines for a Node.js API.  
- Implement quality gates including linting, automated testing, static code analysis, and secret scanning.  
- Ensure secure and reliable software delivery through automated validation at every code change.

---

## Features
- **Code Quality Checks** using ESLint  
- **Automated Testing** via GitHub Actions and Supertest  
- **Static Code Analysis** using CodeQL  
- **Secret Scanning** with TruffleHog  

---

## Setup Steps
1. **Clone the repository**

git clone https://github.com/ayesha2124/simple-api
cd simple-api
npm install
Run API locally

bash
Copy code
node src/index.js
Run tests locally

bash
Copy code
npm test
Workflows
Workflow	Purpose
CI Pipeline	Runs linting and test steps automatically
CodeQL Analysis	Scans the codebase for vulnerabilities
Secret Scanning	Detects exposed secrets or API tokens

---

## Challenges 

Configuring CodeQL correctly to scan Node.js code required careful setup.

Integrating multiple automated checks in a single workflow required debugging triggers.

Ensuring secret scanning blocks commits without affecting normal pushes was tricky.

Learned how automated DevSecOps pipelines improve code reliability and security.

---

## Tech Stack

Node.js

GitHub Actions

ESLint

TruffleHog

CodeQL

---

## Reflection

Learned the importance of automated testing, code quality, and security checks, and handling serverless function responses effectively.

---


All workflows are currently passing successfully!














