# 📈 San Francisco MERS Pension Fund Allocation Analysis

## Overview


This project analyzes a hypothetical asset allocation strategy of San Francisco’s **Municipal Employees’ Retirement System (MERS)**, particularly in light of unusual losses in **2022** and elevated volatility from **2023–2024**. The MERS fund, currently valued at **$525 million**, follows a traditional **60/40 portfolio** (60% U.S. large-cap equities / 40% fixed income).

To strengthen the fund’s resilience, our client is considering a **$175 million top-up** using **COVID relief funds**. This top-up increases the total fund value to **$700 million** and opens the door to more conservative allocation strategies that reduce insolvency risk while optimizing long-term performance.

We use the **AIRG Economic Scenario Generator (ESG)** to test portfolio allocations over a 30-year horizon, focusing on:
- Insolvency risk
- Expected surplus
- Sharpe ratio (risk-adjusted returns)

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


