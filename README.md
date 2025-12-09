# Iran Pharmaceutical Supply Chain Intelligence (TTAC Analysis)

> **Project Status:** 🟢 Active | **Phase:** Research & Roadmap  
> **Domain:** Healthcare Supply Chain, Crisis Management, Pharmacoeconomics

## 📖 The Vision
The Iranian pharmaceutical market has faced unique challenges regarding supply chain continuity, due to sanctions, inflations and COVID-19 pandemic relying on a mix of domestic production, Recorded, and  "Foriyati" (Emergency) imports. This project aims to use data from the **TTAC (Iran Food & Drug Administration)** to move beyond simple reporting and uncover the *root causes* of drug shortages.

My goal is to transition the system from **"Reactive Crisis Management"** to **"Proactive Predictive Safety."**

---

## 🗺️ The Research Roadmap
This analysis is divided into three strategic pillars, addressing 12 critical questions about the healthcare system's resilience.

### 🏛️ Pillar 1: The Crisis Response Engine (Operational Efficiency)
*Focus: Evaluating how the government and supply chain react when a shortage hits.*

* **1. The "Rescue Lag":** Quantifying the time delta between the detection of a shortage (Sales < Threshold) and the arrival of the first Emergency Import.
* **2. Band-Aid vs. Cure:** Performing survival analysis on emergency imports. Do they fix the market permanently, or do we see a cycle of *Shortage → Foriyati → Shortage*?
* **3. The Race:** In a shortage, who responds faster and more effectively: Emergency Importers or Domestic Manufacturers?
* **4. The Waste Metric:** Comparison of Supplier vs. Distributor data to measure how many emergency drugs remain unsold in warehouses (Dead Stock).

### 🧠 Pillar 2: Market Dynamics & Behavioral Science
*Focus: How physicians and patients adapt to supply shocks.*

* **5. Substitution Analysis (Case Study: Warfarin):** Do shortages of a specific drug trigger a statistically significant switch to functional substitutes (e.g., Warfarin → Rivaroxaban)?
* **6. The "Stickiness" Factor:** Once a substitution occurs, do prescribers switch back when the original drug returns, or is market share permanently lost?
* **7. Adoption Lag:** When a new Fixed-Dose Combination (FDC) enters the market, what is the cannibalization rate of older single-agent drugs?
* **8. The "Hoarding" Hypothesis:** Detecting anomalies where supply exists (Import > 0) but downstream sales drop, indicating speculative hoarding.

### 🛡️ Pillar 3: Strategic Stockpiling (Prediction & Prevention)
*Focus: Building a data-driven safety net.*

* **9. The "High-Risk" Watchlist:** Developing a Risk Score for every Generic Code based on shortage frequency and duration. *Output: A definitive list of drugs requiring a strategic national stockpile.*
* **10. Pattern Recognition:** Seasonality decomposition to check if shortages correlate with fiscal cycles (e.g., Nowrouz, End of Budget Year/Esfand).
* **11. Predictive Modeling:** Can we use sales velocity + current inventory levels to predict a stockout 3 months in advance?

---

## 🧪 Completed Case Studies

### 1. The Warfarin Crisis (1403-1404)
* **Focus:** Supply Chain Collapse & Treatment Gaps
* **Status:** Complete ✅
* **Key Insight:** Quantified a **45% supply drop** and a resulting **~50,000 patient treatment gap**, proving that the substitution to alternative drugs was insufficient to protect public health.


### 2. The Insulin Market Paradox (1403-1404)
* **Focus:** Brand Loyalty, Market Rejection & The "Trust Gap"
* **Status:** Complete ✅
* **Key Insight:** Identified a **"Production-Sales Gap"** in the insulin market (Glargine/Aspart). Despite a significant increase in domestic production, sales did not proportionally rise. Statistical analysis (Structural Break Test, p < 0.05) confirmed **Market Rejection**, where patients preferred scarcity of imported brands over abundance of domestic generic substitutes.

---

## 📬 Contact & Contribution
This is an open research initiative. I am looking to answer these questions using Python, Time-Series Analysis, and Econometrics.
* **Author:** Yasaman Behzadipour, Pharm.D
* **Data Source:** IFDA Public Dashboard/Pharmaceutical Statistics 
