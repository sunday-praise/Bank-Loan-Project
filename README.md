# Bank Loan Data Analysis Project (Finance Domain)

## 📌 Project Overview
This end-to-end data analysis project focuses on monitoring, assessing, and visualizing a bank's lending portfolio performance. The analysis is split into two primary Business Requirement Documents (BRDs): managing core high-level lending KPIs (including asset health categorization) and developing specialized trend break-downs for deep-dive regional and structural portfolio insights.

---

## 📊 Business Requirement Document 1: Summary Dashboard

### 1. Key Performance Indicators (KPIs)
The primary objective is to track and monitor critical financial health indicators on a total scale as well as a Month-to-Date (MTD) basis:

*   **Total Loan Applications:** Calculate the total volume of loan requests received during the specified period, alongside tracking **MTD Loan Applications** to capture recent demand trends.
*   **Total Funded Amount:** Measure the cumulative capital disbursed as loans, keeping strict track of the **MTD Total Funded Amount** to monitor asset deployment.
*   **Total Amount Received:** Track all cash inflows back from borrowers to evaluate bank cash flow, debt servicing, and liquidity via the **MTD Total Amount Received** metric.
*   **Average Interest Rate:** Calculate the weighted average interest rate across the entire portfolio to map out the overall cost of capital and margin generation.
*   **Average Debt-to-Income Ratio (DTI):** Compute the average DTI across borrowers to gauge systemic financial risk and consumer credit health.

### 2. Credit Quality Segments: Good Loans vs. Bad Loans
To properly assess risk concentration, loans must be categorized dynamically into asset health buckets:

#### Good Loans (Performing Assets)
*   Good Loan Application Percentage
*   Total Good Loan Applications
*   Good Loan Total Funded Amount
*   Good Loan Total Received Amount

#### Bad Loans (Non-Performing / High-Risk Assets)
*   Bad Loan Application Percentage
*   Total Bad Loan Applications
*   Bad Loan Total Funded Amount
*   Bad Loan Total Received Amount

---

## 📈 Business Requirement Document 2: Data Visualization & Granular Trends
To uncover underlying portfolio movements, seasonal factors, and demographic risks, data must be broken down across the following structures:

1.  **Monthly Trends by Issue Date (Line / Area Chart):** Maps out historical seasonality, origination acceleration, and long-term trend lines in credit activities.
2.  **Regional Analysis by State (Horizontal Bar Chart):** Identifies geographical clusters with heavy credit exposure and addresses cross-state economic disparities.
3.  **Loan Term Analysis (Donut Chart):** Examines the underlying duration risk by breaking down distributions between short-term and long-term maturities.
4.  **Employment History Length Analysis (Bar Chart):** Evaluates how borrower career stability impacts application approvals and funding trends.
5.  **Loan Purpose Breakdown (Bar Chart):** Details the primary drivers motivating consumer borrowing (e.g., debt consolidation, home improvement, small business).
6.  **Home Ownership Impact Analysis (Treemap / Heatmap):** Uncovers hierarchical structures revealing how collateral status (renting, owning, mortgaging) influences loan ticket sizes and defaults.

> **Note on Chart Metrics:** Every structural segment breakdown listed above must display three standardized core tracking dimensions: **Total Loan Applications**, **Total Funded Amount**, and **Total Amount Received**.
