# 🧪 Professional Testing Guide — QA Engineer (Selenium)

---

## 🎯 Overview

**Author: Artur Felipe Albuquerque Portela** — candidate for the **QA Engineer (Selenium)** position presented by Match Profiler for the client **Natixis**.  
This document describes the QA process applied in banking and **Trade Finance** products, using **structured methodology, Selenium-based automation, AI-assisted productivity, and API contract validation** to ensure quality and predictable deliveries.

---

## 🎯 Objective

Ensure that key flows such as **login and authentication**, **payments and transfers**, **identity and document checks**, and **trade operations (letters of credit, guarantees)** are tested end-to-end with focus on:

- ✅ **Security and compliance** (avoid financial or regulatory issues).  
- ✅ **Predictable deliveries** (confidence in every release).  
- ✅ **Productivity** (automation and AI to reduce repetitive work).  
- ✅ **Stable integrations** (Contract Analyzer to prevent API failures).  

---

## 🔑 Work Structure

### 1. Planning
- Collect requirements following the **SDLC (Software Development Life Cycle)**.  
- Align with **Natixis stakeholders** (business, product, QA).  
- Identify **critical flows**: login, payments, document checks, trade finance.  
- Write scenarios in **BDD/Gherkin** (easy to adapt to Cucumber).  
- Prioritize by **risk and financial impact**.  

📊 **Time for this stage:** typically 3–5 business days depending on scope.  

---

### 2. Automation
- Build end-to-end test flows with **Selenium (Java)**.  
- Validate data consistency with **SQL**.  
- Run **mass actions** when needed (e.g., multiple authorizations or transfers), applying the concept of **RPA (UiPath)** to reduce effort and ensure consistency.  
- Create **simple PowerShell scripts** to speed up runs and connect to pipelines.  

📊 **Expected results:**  
- Around **25–40% reduction** in time spent on repetitive regression testing.  
- Significant decrease in repeated failures in flows already automated.  

---

### 3. Execution
- Run tests locally and in **CI/CD pipelines** (Jenkins, GitHub Actions).  
- **Smoke tests after deploy** to confirm login and payments right away.  
- **Contract Analyzer** in the pipeline for critical APIs:  
  - Compares API specs (e.g., payments, transactions).  
  - Creates automatic risk reports.  
  - **Blocks pipeline** if there is a high-risk change with no mitigation.  
- Use of **AI agents** to:  
  - create repetitive test cases,  
  - summarize reports,  
  - keep documentation updated.  

📊 **Proven impact:**  
- AI saves **20–30%** of the time usually spent on documentation and reporting.  
- Contract Analyzer reduces risk of silent API-breaking changes to near **0% in covered contracts**.  

---

### 4. Evidence and Reporting
- **Automatic screenshots and logs**.  
- **Visual reports** with Allure/ExtentReports.  
- Documentation stored in **Confluence**, visible to the team.  
- Clear and traceable feedback with productivity metrics.  
- **Bug classification and prioritization**: always give higher priority to issues in **critical flows** (payments, login) or **edge cases** that affect system reliability.  

📊 **Quality metrics:**  
- **70–85% coverage** on critical flows depending on maturity of the product.  
- **MTTD (Mean Time to Detect):** critical bugs found usually within minutes to a few hours after execution.  
- **MTTR (Mean Time to Repair):** average fix time targeted within 1–2 days for critical bugs.  

---

## 📊 Testing Pyramid

- **Base** → quick checks of rules and essential data.  
- **Integration** → APIs and database working together.  
- **Contracts** → **Contract Analyzer** makes sure API changes do not break external systems.  
- **End-to-End** → Selenium covers login, payments, KYC, and trade operations.  
- **Robustness** → samples of performance (response times) and security checks.  
- **Monitoring** → automatic healthchecks and alerts after each deploy.  

👉 This order follows **best practice**: avoid waste, cut rework, and focus on value.  

---

## 🔎 Where most tests will be

In Natixis Trade Finance, more test volume is expected in:  
- **Automated UI regression** for critical flows.  
- **SQL checks** for consistency between UI and data.  
- **Mass actions** for batch authorizations and queries.  
- **Operation queries/monitoring** (history, states, filters).  

---

## 🛡️ Data Security

- Use of **test data** with **masked PII**.  
- Evidence (screenshots, logs) follows the **minimum necessary rule**, avoiding data exposure.  

---

## 🧰 Tools

| Category               | Main Tools                             |
|------------------------|----------------------------------------|
| UI Automation          | **Selenium WebDriver (Java)**          |
| Data Validation        | **SQL**                                |
| Continuous Integration | Jenkins, GitHub Actions                |
| Reporting              | Allure, ExtentReports, Confluence      |
| Management             | Git, GitHub, Jira, Trello              |
| API Validation         | **Contract Analyzer (.NET)**           |

---

## 🔚 Closing

This approach is a **flexible skeleton**: it can be used **from the start of a project** or adapted to products already in progress.  
It is **reusable and adjustable** to the needs of each development team and the priorities of each product.  
This ensures fast value at the beginning and allows the testing strategy to evolve with the client and the banking sector.  

---

📌 **Artur Felipe Albuquerque Portela**  
📍 Póvoa de Lanhoso, Braga – Portugal  
📧 arturengqa@gmail.com | 📱 +351 932 508 100  
🔗 GitHub: [github.com/ArturMoco](https://github.com/ArturMoco)  
