# 📊 Balance Sheet & Profit–Loss Dashboard – PT Wira Cipta Perkasa (2024–2025)

An **Excel-based financial monitoring system** built to simplify reporting and monitoring for the 2024–2025 period.  
The workbook consolidates transactional data, aggregates accounts by **Chart of Accounts (COA)**, and produces periodic **Balance Sheet** and **Profit & Loss** reports together with five bank-aligned financial ratios: **performance, solvency, liquidity, profitability,** and **efficiency**.

---

## 🔎 Project Objectives
- Automate aggregation and consolidation of financial postings by **COA**.  
- Produce ready-to-use monthly and year-to-date **Balance Sheet** and **Profit & Loss** reports.  
- Calculate five core financial ratios aligned with standard bank reporting.  
- Reduce manual steps in monthly close and make monitoring repeatable, auditable, and easy to hand over.  
- Keep the solution fully inside the Excel ecosystem (Power Query + formulas).

---

## 🛠 Tools
`Excel` • `Power Query` (Get & Transform)

---

## 🧭 Process Overview (high-level)

1. **Data ingestion (ETL)**  
   Power Query loads GL exports, sub-ledgers, and manual journals from a folder, standardizes column names and date formats, and applies basic validation.

2. **COA mapping & normalization**  
   A master COA table maps GL codes to reporting buckets (GL → subgroup → report line) to support multi-level aggregation.

3. **Transformations & business logic**  
   Implement currency normalization, period tagging (month/quarter/YTD), reclassification rules, and derived measures (e.g., accruals).

4. **Ratio calculations**  
   Compute five bank-aligned ratios with transparent formulas and show numerator/denominator sources on the dashboard.

5. **Report templates & interactivity**  
   Pre-built Monthly P&L, Balance Sheet, and Ratio Dashboard with filters (period, entity, department) for interactive review inside Excel.

6. **Quality control & documentation**  
   Built-in checks (balance tests, reconciliation rows), exceptions log, and README/guide sheet describing data sources and COA rules.

7. **Handover**  
   Workbook delivered with a short user guide covering query refresh, COA updates, and the monthly routine.

---

## ✅ Deliverables
- Single Excel workbook including:
  - Power Query ETL layer  
  - COA master mapping sheet  
  - Transaction staging & validated datasets  
  - Balance Sheet & Profit–Loss templates  
  - Ratio Dashboard (performance, solvency, liquidity, profitability, efficiency)  
  - README & short user guide

---

## 📷 Preview (click to view)

<table>
<tr>
<td align="center"><img src="https://raw.githubusercontent.com/rizalarb/Balance-Sheet-and-Profit-Loss-Dashboard/master/Balance.png" width="260"/><br><sub>Balance Sheet (aggregated by COA)</sub></td>
<td align="center"><img src="https://raw.githubusercontent.com/rizalarb/Balance-Sheet-and-Profit-Loss-Dashboard/master/Profit%20And%20Loss.png" width="260"/><br><sub>Profit & Loss (period comparatives)</sub></td>
<td align="center"><img src="https://raw.githubusercontent.com/rizalarb/Balance-Sheet-and-Profit-Loss-Dashboard/master/Ratio%20And%20EBITDA.png" width="260"/><br><sub>Ratio Dashboard (EBITDA & bank-aligned ratios)</sub></td>
</tr>
<tr>
<td align="center"><img src="https://raw.githubusercontent.com/rizalarb/Balance-Sheet-and-Profit-Loss-Dashboard/master/Unit%20Business.png" width="260"/><br><sub>Unit / Business Segment View</sub></td>
</tr>
</table>

---

## 📌 Notes for HR / Hiring Managers
- Demonstrates **end-to-end process design** (ETL → mapping → reporting) executed within Excel.  
- Emphasizes **repeatability**, **auditability** (COA mapping & checks), and clear documentation for handover to finance teams.
  
**Download workbook (raw .xlsx)**  
[📥 DASHBOARD Financial Statment.xlsx](https://raw.githubusercontent.com/rizalarb/Balance-Sheet-and-Profit-Loss-Dashboard/master/DASHBOARD%20Financial%20Statment.xlsx)

[Back to Top](#ahmad-rizal-bayhaqi--data-analyst--visualization-specialist)
