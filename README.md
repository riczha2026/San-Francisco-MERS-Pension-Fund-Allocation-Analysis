# 📈 San Francisco MERS Pension Fund Allocation Analysis

## Overview


This project, completed as part of my **Financial Market Risk and Modeling course at UC Santa Barbara**, analyzes a hypothetical asset allocation strategy for San Francisco’s **Municipal Employees’ Retirement System (MERS)**. The analysis draws from **historical data provided by the course professor** and uses simulation outputs from the **AIRG Economic Scenario Generator (ESG)**.

The study is motivated by **unusual losses in 2022** and **elevated volatility from 2023–2024**, which raised concerns about the fund’s long-term solvency. At the time of analysis, the MERS fund is assumed to be valued at **$525 million**, following a traditional **60/40 portfolio** (60% U.S. large-cap equities / 40% fixed income).

To enhance the fund’s resilience, our client is considering a **$175 million top-up using COVID relief funds**, bringing the total fund value to **$700 million**. This addition allows for more conservative investment strategies that aim to minimize **insolvency risk** while maintaining strong, risk-adjusted performance.

Using the AIRG ESG, we test various allocation strategies over a **30-year horizon**, evaluating them on:
- **Insolvency risk**
- **Expected surplus**
- **Sharpe ratio** (risk-adjusted return)


---

## 📌 Key Findings

- **2022 Losses:** The fund experienced sporadic losses (≥15%), which pose serious risks to liquidity and solvency.
- **2023–2024 Volatility:** Prolonged market uncertainty contributed to sustained high volatility, increasing downside risk.
- **Rare Event Probability:** Our ESG model estimates only a **1.51% chance** of such high annual losses under a standard 60/40 portfolio, reinforcing the rarity of these events.

---

## 📊 Allocation Strategy Recommendations

### Without COVID Fund Top-Up ($525M Fund Size)
- **Recommended Allocation:** **45% Equity / 55% Fixed Income**
- **Rationale:**  
  - Lowest projected insolvency risk  
  - Strong 30-year surplus projections  
  - Solid Sharpe ratio performance  
  - Meets long-term obligations with reduced risk exposure  

### With $175M COVID Relief Top-Up ($700M Total Fund Size)
- **Recommended Allocation:** **30% Equity / 70% Fixed Income**
- **Rationale:**  
  - Insolvency risk drops to near **0.3%**  
  - Sharpe ratios improve significantly across all allocations  
  - Offers **highest risk-adjusted return** while maintaining long-term sustainability

---

## ✅ Conclusion

By tailoring the MERS fund’s asset allocation in response to extreme market events, this report presents a **realistic and data-driven approach** to improve fund performance, protect against insolvency, and ensure future pension obligations are met **(with or without) supplemental funding**.

---

## 🔧 Tools & Methods
- **AIRG Economic Scenario Generator**
- Historical stress testing
- Risk-adjusted performance metrics (Sharpe Ratio)
- Insolvency probability modeling
- R
- Excel


