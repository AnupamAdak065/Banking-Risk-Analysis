# 🏦 Banking Risk & Portfolio Analysis Report

## 📌 Table of Contents

* [1. Introduction](#1-introduction)
* [2. Dataset Information](#2-dataset-information)
* [3. Tools & Technologies](#3-tools--technologies)
* [4. Key Calculations & KPIs](#4-key-calculations--kpis)
* [5. Detailed Observations](#5-detailed-observations)
* [6. Recommendations](#6-recommendations)
* [7. Dashboard Previews](#7-dashboard-previews)
* [8. Conclusion](#8-conclusion)

---

## 1. Introduction

This report outlines the technical workflow and key business insights derived from the banking dataset[cite: 3]. Structured to demonstrate data wrangling, exploratory data analysis (EDA), and clear business intuition, this project provides data-driven insights to help stakeholders optimize risk management and customer segmentation strategies[cite: 3].

**Primary Objectives:**

* Analyze demographic, income, and geographic distributions across the bank's clientele[cite: 3, 4].
* Evaluate loan performance, business lending, and credit card balances across risk categories and engagement timeframes[cite: 3, 4].
* Investigate deposit behaviors, savings/checking breakdowns, and asset ownership[cite: 3, 4].
* Build a multi-page interactive Power BI dashboard suite for executive oversight and granular client drill-downs[cite: 3, 4].

---

## 2. Dataset Information

* **Data Footprint:** The dataset consists of 3,000 unique client records across 25 distinct attributes[cite: 3, 4].
* **Data Quality & Cleaning:** An initial inspection confirmed a pristine dataset with exactly zero missing values across all columns[cite: 3, 4]. The `Joined Bank` column was successfully parsed from a standard object to a `datetime64[ns]` format to enable time-series analysis[cite: 3, 4].

**Feature Engineering:**

* To improve business segmentation, a new feature named `Income Category` was created[cite: 3, 4]. Estimated Income was bucketed into three distinct tiers:
* **Low:** < $100,000[cite: 3, 4]
* **Medium:** $100,000 to $300,000[cite: 3, 4]
* **High:** > $300,000[cite: 3, 4]



---

## 3. Tools & Technologies

* **Python:** Relies heavily on `pandas` and `numpy` for data manipulation, alongside `matplotlib`, `seaborn`, and `plotly` for advanced data visualization[cite: 3, 4].
* **Power BI:** Interactive data modeling, DAX measures, and dashboard visualization[cite: 3, 4].
* **Excel:** Initial data validation and quick dataset validation[cite: 3, 4].

---

## 4. Key Calculations & KPIs

| Metric | Value |
| --- | --- |
| **Total Clients** | 2,940 - 2,913  |
| **Total Portfolio Loans** | $4.38B |
| **Total Bank Deposits** | $3.77B |
| **Bank Loan** | $1.77B |
| **Business Lending** | $2.60B |
| **Checking Account Amount** | $963.28M |
| **Saving Account Amount** | $698.73M |

> 💡 **Key Highlight:** The institution manages a robust portfolio with multi-billion-dollar exposures across corporate lending and core deposits, skewing heavily toward lower risk weightings.

---

## 5. Detailed Observations

1. **Income Distribution:** The majority of the client base falls into the Medium income tier (1,517 clients), followed by Low (1,027), and High (456)[cite: 3, 4]. The overall estimated income spans a wide range, from $15,919.48 up to a maximum of $522,330.26[cite: 3, 4].
2. **Age Profile & Demographics:** The average client age is approximately 51 years old[cite: 3, 4]. The bank serves a broad demographic, with the youngest client being 17 and the oldest at 85[cite: 3, 4]. Gender is evenly split, comprising 1,512 females (GenderId 2) and 1,488 males (GenderId 1)[cite: 3, 4].
3. **Geographic & Nationality Split:** European clients represent the largest segment of the portfolio (1,309 clients)[cite: 3, 4]. This is followed by Asian (754), American (507), Australian (254), and African (176) nationalities[cite: 3, 4].
4. **Risk & Account Segmentation:**
* The portfolio skews toward lower risk[cite: 3, 4]. Clients are predominantly assigned a Risk Weighting of 2 (1,222 clients) or 1 (836 clients)[cite: 3, 4]. Only 160 clients fall into the highest risk category of 5[cite: 3, 4].
* A significant portion of the base (1,476 clients) operates under a 'High' fee structure[cite: 3, 4]. In terms of loyalty classifications, 'Jade' is the most common (1,331 clients), followed by 'Silver' (767) and 'Gold' (585)[cite: 3, 4]. 'Platinum' is the most exclusive tier, held by 317 clients[cite: 3, 4].


5. **Asset, Property, & Credit Utilization:**
* Real estate exposure is evenly distributed across the client base[cite: 3, 4]. 777 clients own 2 properties, 776 own 1 property, 742 own 3 properties, and 705 currently do not own any properties[cite: 3, 4].
* The majority of clients (1,922) hold only 1 credit card, while 765 clients hold 2, and 313 clients hold 3[cite: 3, 4]. The average credit card balance across the portfolio sits at $3,176.20[cite: 3, 4].



---

## 6. Recommendations

* **Portfolio Risk Management:** Maintain strict oversight on the small high-risk cohort while capitalizing on the stable, conservative baseline portfolio.
* **Targeted Cross-Selling:** Leverage high checking and savings account balances to cross-sell wealth management and investment products to single-card or multi-property owners.

---

## 7. Dashboard Previews


### 1️⃣ Loan Analysis

![Banling - Loan Dashboard](Dashboard/2.%20loan_analysis.jpg)

### 2️⃣ Deposit Analysis

![Banking - Deposit Dashboard](Dashboard/3.%20deposit_analysis.jpg)


---

## 8. Conclusion

This project outlines a complete technical workflow and business intelligence overview of the banking dataset[cite: 3, 4]. By combining exploratory data analysis with interactive Power BI dashboards, the portfolio highlights robust demographic trends, conservative risk profiles, and actionable areas for financial growth[cite: 3, 4].

---

## Author & Contact

**Anupam Adak**

Data Analyst[cite: 3, 4]

📧 Email: anupamadak6295@gmail.com[cite: 3, 4]

🔗 [LinkedIn Profile](www.linkedin.com/in/anupam-adak-3601091a3)
