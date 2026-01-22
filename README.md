# Retirement-Fund-Tracker-Monte-Carlo-Simulation-Excel-
Excel-based financial analytics project using Monte Carlo simulation to evaluate retirement fund sustainability under salary growth, market volatility, inflation, and longevity risk. Combines investment analysis, risk modeling, and data-driven decision making for real-world financial planning.

## Overview
This project uses **Microsoft Excel** to design and evaluate a long-term **retirement planning and superannuation strategy** using **Monte Carlo simulation**.

The model focuses on:
- Data correctness and transparency  
- Reproducible financial modeling  
- Clear analytical reasoning under uncertainty  

It simulates salary growth, investment returns, inflation-adjusted expenses, emergency savings, and retirement withdrawals to assess whether a structured investment strategy can support a financially secure retirement.

---

## Problem Statement
The objective of this analysis is to determine whether an individual’s **current and adjusted superannuation strategy** is sufficient to meet long-term retirement goals under realistic uncertainty.

### Specifically
**Decision needed:**  
Assess whether the retirement corpus will be adequate to sustain living expenses throughout retirement.

**Who the analysis is for:**  
A 30-year-old professional in the tech industry planning to retire at age 65.

**Constraints:**
- Long-term forecasting uncertainty  
- Market volatility  
- Simplified tax and life-event assumptions  
- Excel-based implementation (no external databases)

---

## Data Description
The dataset used in this project is **synthetic and model-generated**, designed to reflect realistic financial behavior.

- **Time horizon:** Age 30 to Age 82  
- **Granularity:** Annual projections  

### Key Inputs
- Salary and salary growth rate  
- Investment returns and volatility by fund type  
- Contribution rates (employee + employer)  
- Inflation rate  
- Living expenses  

### Key Outputs
- Superannuation balance over time  
- Emergency fund accumulation  
- Retirement withdrawal sustainability  

No external personal data is used.

---

## Data Preparation
Data preparation is embedded directly within the Excel model:

- Centralized inputs in clearly labeled assumption cells  
- Consistent units and formats applied across all sheets  
- Derived fields created for:
  - Annual salary  
  - Contributions  
  - Fund-level returns  
  - Inflation-adjusted expenses  
- Randomized values generated using probabilistic distributions to ensure reproducibility across simulations  

---

## Analysis Methodology
A **Monte Carlo simulation** drives the analysis to capture uncertainty in income, markets, and inflation.

- **Simulation runs:** 1,000 iterations  
- **Salary growth:** Modeled using a normal distribution  
- **Investment returns:** Simulated per fund using expected return and volatility  
- **Portfolio returns:** Weighted by dynamic asset allocation  
- **Expenses:** Grown annually using an inflation assumption  

### Retirement Phase
- Portfolio reallocated to low-risk assets  
- Annual withdrawals applied to meet living expenses  

This approach produces a **distribution of outcomes** rather than a single deterministic forecast.

---

## Excel Techniques Used
The following Excel features are used in the model:

- **Advanced formulas:**
  - `NORM.INV`
  - `RAND`
  - Compound growth formulas  
- Structured assumption tables  
- Pivot tables for summarizing simulation outcomes  
- Conditional formatting for scenario highlighting  
- Named ranges for key inputs  
- Scenario comparison using summary statistics (minimum / average / maximum)  

Only native Excel functionality was used (no macros or VBA).

---

## Results and Insights
Key findings from the analysis include:

- Average projected superannuation balance at retirement (age 65): **~NZD 1.5 million**
- Emergency savings accumulated from surplus income: **~NZD 2.7 million**
- Conservative post-retirement allocation significantly improves fund sustainability
- Retirement plan remains viable through age 82, aligning with average life expectancy

### Key Takeaways
- Importance of early contributions  
- Power of long-term compounding  
- Value of dynamic asset allocation  
- Need for risk management near retirement  

---

## Deliverables
This repository contains:

- **Excel workbook** with:
  - Input assumptions  
  - Monte Carlo simulation engine  
  - Fund allocation logic  
  - Retirement projections  
- **Written report** explaining:
  - Assumptions  
  - Methodology  
  - Results and recommendations  
- **README.md** documenting the analytical approach  

---

## Limitations
- No taxation applied to salary or investment returns  
- No job loss or significant life events modeled  
- Inflation assumed to follow a stable long-term rate  
- Healthcare and extreme longevity risks not explicitly modeled  
- Excel performance limits the number of simulations compared to programming languages  

---

## Future Improvements
Potential enhancements include:

- Migrating simulations to Python for scalability  
- Adding Power BI or Tableau dashboards  
- Modeling healthcare and long-term care costs  
- Incorporating taxation and policy changes  
- Automated rebalancing logic  
- Sensitivity analysis across alternative inflation scenarios  

---

## How to Use
1. Open the Excel workbook  
2. Start with the **Assumptions / Inputs** sheet  
3. Review the **Simulation** and **Projection** sheets  
4. Refer to the report for interpretation and conclusions  
5. Modify inputs to test alternative scenarios  
