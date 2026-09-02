# Edufin_Portfolio_Risk_Analysis
A SQL-driven investigation into loan portfolio risk for EduFin, uncovering default patterns, high-risk customer segments, and the underwriting failure behind a fast-escalating credit crisis.

---

## 🧭 Overview

EduFin's loan portfolio was showing signs of rising defaults. This project investigates the portfolio end-to-end using SQL on Databricks — starting from overall portfolio health, drilling into *who* is defaulting and *why*, then tracing *when* the problem began and how fast it accelerated — to convert raw loan and customer data into a prioritized action plan for the business.

**Objective:** Identify default patterns, high-risk customer segments, and the key factors driving portfolio risk.

---

## 🔑 Key Areas of Analysis

- Portfolio Health Analysis
- Customer Risk Analysis
- Time Trend Analysis
- Business Problem Solving
- Identifying High-Risk Segments
- Converting data into actionable business recommendations

---

## 🛠️ Key Skills & Tools

| Category | Details |
|---|---|
| Query Engine | SQL, Databricks |
| Analysis Type | Data Analysis, Business Analytics, Risk Analysis |
| Approach | Data-Driven Decision Making |

---

## 📅 Investigation Breakdown

### Portfolio Health

| Metric | Value |
|---|---|
| Total Portfolio | ₹204.82 Cr |
| Default Exposure | ₹35.18 Cr |
| Default Rate | **11.8% (High)** |
| Concentration Risk | Large loans (>₹6L): 18% default rate — outsized contribution |
| Root Cause | Lending policy failure after migration → underwriting gaps |

### Customer Risk

| Dimension | Finding |
|---|---|
| Credit Score | Low CIBIL (<650) → highest default contribution |
| Age Band | Borrowers 31–35 show elevated defaults |
| Income | Income < ₹3L correlated with higher default probability |
| Highest-Risk Segment | Students, unemployed, income < ₹3L — priority for collections & remediation |

### Time Trend Analysis

| Metric | Finding |
|---|---|
| Acceleration | Default spike begins **Aug 2022** |
| Crisis Threshold | Crossed **Oct 2022** (>10% default rate) |
| Avg. Time-to-Default | ~223–224 days |
| Financial Impact | Exposure escalated to **₹944.38 Cr by Jun 2023** |
| Data Limitation | No reliable payment transaction history for several institutions (National Law School of India, Visvesvaraya Technological University, Birla Institute of Applied Sciences, Regional Management Institute) → limited behavioral signals, affecting predictive accuracy |

---

## ✅ Final Recommendations

| Action | Detail |
|---|---|
| **Pause & Contain** | Freeze high-risk lending; review exceptions within 72 hours |
| **Recovery Sprint** | Prioritize recovery of ₹35.18 Cr through collections and legal action |
| **Policy & Controls** | Restore underwriting rules and enforce automated credit gates |
| **Monitor & Predict** | Deploy early-warning analytics and strengthen payment history feeds |

---

## 📌 Summary

The investigation traced EduFin's rising defaults to an underwriting gap introduced after a system migration, concentrated in large loans and low-CIBIL, low-income borrowers. Defaults accelerated sharply from August 2022, crossing a crisis threshold by October 2022, with cumulative exposure reaching ₹944.38 Cr by mid-2023. The recommended response combines an immediate lending freeze, focused recovery efforts, restored underwriting controls, and predictive monitoring to prevent recurrence.

---

## 📂 Project Type

Guided individual case study (SQL/Databricks only) on a real production-scale loan dataset, covering SQL, Data Quality, Risk Assessment, and Business Analysis.

---

## Author
**Anwesha Abantika**
