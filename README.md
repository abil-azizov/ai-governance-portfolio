# AI Governance & Risk Management Portfolio
**Abil Azizov** | Product Compliance, Trust & Safety & AI Governance  
[LinkedIn](https://www.linkedin.com/in/abil-azizov/) • [Email](mailto:abil.azizov@gmail.com)

> *Disclaimer: Fictionalised case study based on generalised professional experience. Contains no confidential information of any current or former employer.*

---

## Case Study 1: E-Bike Compliance Classifier (EU Marketplace)
**Date:** November 2026 | **Frameworks:** EU AI Act, DSA, P2B Regulation, GPSR, GDPR, ISO/IEC 42001, ISO/IEC 23894, NIST AI RMF

This project is a full AI risk assessment of a supervised machine learning model that automatically restricts non-compliant e-bikes on a Polish online marketplace (1,000,000 products in scope).

* **11** risks identified across the ML lifecycle
* **5 → 0** Critical risks before vs. after controls
* **24** preventive, detective, and corrective controls designed

### The Business Problem
The model restricts roughly 2,000 products per month with zero human pre-review. At 88% recall, it misses an estimated 3,600 unsafe e-bikes, while a single faulty rule update wrongly restricted 1,000 listings across 300 sellers.

### Key Governance Insight
Wrongful restrictions generate immediate seller complaints, whereas missed unsafe e-bikes stay invisible until a battery fire or crash occurs. Therefore, a **95% minimum recall floor** must be owned and approved by business leadership rather than left as an engineering default.

### Portfolio Artifacts

| Document | Description | Link |
| :--- | :--- | :--- |
| **00. Case Study Overview** | One-page executive summary of the problem, method, and results | [View PDF](./00-case-study-overview.pdf) |
| **01. AI Risk Assessment** | Full 10-page assessment: lifecycle, legal classification, criteria, 11 risks, and scoring | [View PDF](./01-ai-risk-assessment.pdf) |
| **02. AI Risk Register** | Complete register of 11 risks, inherent/residual scores, 24 controls, owners, and due dates | [View PDF](./02-ai-risk-register.pdf) |
| **03. Audit Finding F-01** | Targeted audit report on SQL/ETL scoping gaps (`kW`/`mph`) with 3 SMART actions | [View PDF](./03-audit-finding-f01.pdf) |
| **04. Regulatory Applicability Memo** | Legal analysis covering EU AI Act minimal-risk status and DSA, P2B, GPSR, and GDPR duties | [View PDF](./04-regulatory-applicability-memo.pdf) |
| **05. AI System Card** | Standardized one-page AI inventory entry | [View PDF](./05-ai-system-card.pdf) |
