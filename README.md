# IFFCO Supply Chain Management Internship

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)

**Author:** Anish Das  
**Organization:** IFFCO BAZAR Ltd.  
**Internship Period:** May 15, 2024 – July 15, 2024  

---

## 📋 Table of Contents

1. [Problem Statement](#problem-statement)  
2. [Objectives](#objectives)  
3. [Project Overview](#project-overview)  
4. [Scope](#scope)  
5. [Methodology](#methodology)  
6. [Key Findings & Results](#key-findings--results)  
7. [Conclusion](#conclusion)  
8. [Future Work](#future-work)  
---

## 1. Problem Statement

IFFCO BAZAR Ltd. manages procurement, storage, and distribution of agro‑produce across a network of warehouses and retailer outlets.  
- **Issue:** Frequent stock‑outs at high‑demand locations and delays in last‑mile delivery lead to customer dissatisfaction and higher costs.  
- **Challenge:** Identify data‑driven ways to optimize inventory levels and delivery routes without high‑tech solutions.

---

## 2. Objectives

- **Analyze** historical inventory and delivery data to spot bottlenecks.  
- **Optimize** reorder points and safety stock to reduce stock‑outs.  
- **Improve** delivery lead times by proposing efficient routing.  
- **Streamline** vendor communication for timely dispatches.  
- **Recommend** process changes based on customer feedback to lower delivery failures.

---

## 3. Project Overview

During my two‑month internship, I collected and analyzed data from IFFCO’s ERP system, interviewed logistics managers, and ran simple forecasting models to propose actionable improvements in supply chain operations.

---

## 4. Scope

- **Geography:** Tier 3 and Tier 4 cities served by IFFCO BAZAR.  
- **Products:** High‑volume staples (rice, wheat, pulses).  
- **Data Range:** January 2023 – April 2024.  
- **Exclusions:** Cold‑chain, perishables, and international logistics.

---

## 5. Methodology

1. **Data Collection**  
   - Exported CSVs: stock levels, purchase orders, delivery logs.  
2. **Data Cleaning & Preparation**  
   - Standardized date formats, merged tables, handled missing values.  
3. **Exploratory Data Analysis (EDA)**  
   - Plotted inventory trends, calculated average lead times, identified outliers.  
4. **Forecasting Model**  
   - Built a moving‑average demand forecast to set reorder points.  
5. **Route Optimization**  
   - Tested simple “nearest‑neighbor” heuristic to suggest shorter delivery loops.  
6. **Stakeholder Interviews**  
   - Gathered qualitative feedback from warehouse and field teams.  
7. **Recommendations**  
   - Compiled in final report and slide deck (see `docs/`).

---

## 6. Key Findings & Results

- **Inventory Trends:**  
  - Peak reorder points vary by location → safety stock adjusted accordingly.  
- **Lead‑Time Improvement:**  
  - Proposed route changes cut average delivery time from 48 hrs to 42 hrs (12% reduction).  
- **Forecast Accuracy:**  
  - Moving‑average model hit 85% accuracy in predicting weekly demand.  
- **Customer Feedback:**  
  - Top cause of failed deliveries: “no recipient at address.” Recommended SMS alerts.

---

## 7. Conclusion

Through low‑cost, data‑driven tactics, IFFCO can:
- Maintain optimal stock levels in all warehouses.
- Reduce delivery lead times and failed shipments.
- Improve customer satisfaction with timely notifications.
  
These improvements are implementable with existing systems and minimal additional tools.

---

## 8. Future Work

- **Advanced Forecasting:** Test ARIMA or ML models for better demand prediction.  
- **Dynamic Routing:** Integrate Google Maps API for real‑time traffic data.  
- **Dashboard:** Build a live Power BI or Tableau dashboard for ongoing monitoring.  
- **Scale Perishables:** Extend methodology to temperature‑sensitive goods.

---

