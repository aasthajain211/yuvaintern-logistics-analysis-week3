# YuvaIntern Logistics Data Analyst Internship - Week 3 Task

## 🚀 Project Overview
This repository contains the advanced Exploratory Data Analysis (EDA) and visualization deliverables for **Week 3** of the Logistics Data Analyst Internship at YuvaIntern. Building seamlessly upon the synchronized network architecture (Task 1) and data preprocessing pipeline (Task 2), this module translates raw operational shipment records into high-value supply chain intelligence and actionable business recommendations.

---

## 🌐 Synchronized Network Architecture & Scope
To maintain 100% synchronization across all internship milestones, this project adheres to the standardized global framework:
* **Global Hubs:** London, Singapore, Tokyo, New York, Rotterdam, and Shanghai.
* **Authorized Transport Modes:** AIR, OCEAN, ROAD, and RAIL.
* **Target Variable:** Delivery Status (`Delayed` vs. `On-Time`).
* **Sample Size:** 5,000+ simulated global records (evaluated on a 1,000-record representative analytical sample).

---

## 📊 Exploratory Data Analysis (EDA) & Statistical Summary
Rigorous statistical computations were executed using Python (`pandas`, `numpy`) to evaluate central tendencies and dispersion metrics:
* **Planned Duration:** Mean = 12.94 days | Median = 13.00 days | Std = 6.69 | Min = 2.00 | Max = 24.00.
* **Actual Duration:** Mean = 7.99 days | Median = 6.16 days | Std = 5.90 | Min = 2.00 | Max = 40.43.
* **Shipment Weight:** Mean = 4,991.10 KG | Median = 4,997.78 KG | Std = 1,985.14 | Min = -982.27 (Treated/Cleaned) | Max = 12,852.48.

---

## 📈 Visualizations & Analytical Insights
Four specialized visualizations were engineered using `matplotlib` and `seaborn` to uncover operational bottlenecks:
1. **Figure 1 (Comparative Distribution of Planned vs. Actual Transit Durations):** Highlights a prominent right-tailed skew where actual delivery times stretch up to 40.43 days, revealing unexpected operational delays that violate contractual SLAs.
2. **Figure 2 (Transit Duration Variance Across Authorized Transport Modes):** Demonstrates that ocean freight experiences higher median transit durations and wider interquartile dispersions due to port congestion, whereas air transport remains tight, rapid, and predictable.
3. **Figure 3 (Correlation Matrix of Supply Chain Metrics):** Confirms near-zero linear correlation ($r = 0.04$) between shipment weight and actual delivery duration, proving that cargo weight does not directly dictate transit time bottlenecks.
4. **Figure 4 (Delivery Status Proportions Across Global Dispatch Hubs):** Maps regional delay frequencies, identifying high-congestion maritime ports (Rotterdam and Shanghai) relative to agile aviation hubs.

---

## 💡 Strategic Recommendations for Management
* **Dynamic Safety Stock Buffers:** Increase inventory safety stock levels by 15% at high-congestion marine ports (Rotterdam and Shanghai) to absorb extended maritime lead times
