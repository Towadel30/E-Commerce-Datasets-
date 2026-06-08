# E-Commerce-Datasets-
This dataset contains online retail transactions including invoice numbers, Stock Code, Description, quantity, Invoice Date, unit price, customer id and country.
# E-commerce Dataset

## Dataset Understanding

## Data Cleaning

## Exploratory Data Analysis

## Visualizations

# ONE-PAGE SUMMARY REPORT: GLOBAL E-COMMERCE EXPLORATORY ANALYSIS
**Project Title:** End-to-End Data Engineering and Exploratory Data Analysis Pipeline (E-commerce)  
**Analyst:** Esther Ayodele  
**Date:** June 8, 2026  

---

### 1. Data Cleaning and Validation Challenges Encountered
* **Systemic Pricing Noise and Artifact Correction:** Advanced statistical distribution modeling via box plots exposed significant pricing anomalies from structural adjustments, debt charges, and administrative system noise. These errors manifested as extreme negative data points plunging below -$11,000. These elements were isolated and filtered to lock in pure retail financial variables.
* **Negative Transaction Volume Segmentation:** Flagged substantial tranches of negative vectors within the inventory quantity fields. These were algorithmically isolated as customer order cancellations and product returns (Invoice Series C), preventing the artificial deflation of gross customer product volume tracking.
* **Schema Normalization and Parsing:** Safely parsed highly erratic, mixed-format date-time stamps into a unified temporal system and synchronized all alphanumeric string structures to consistent casing criteria for seamless query aggregation.

---

### 2. Key EDA Findings and Top Portfolio Insights
* **Insight 1 (Explosive Q4 Holiday Sales Cycles):** Monthly financial gross margins reveal a highly predictable baseline hovering under $800,000 for the opening three quarters of the year. This baseline triggers into an explosive consumer buying curve starting in August, hitting a monumental all-time performance revenue ceiling of over $1,500,000 in November 2011, highlighting clear demand seasonality.
* **Insight 2 (Extreme Regional Revenue Concentration):** Macro geographic spend modeling shows absolute commercial centralization within the domestic market space. The United Kingdom represents the undisputed commercial driver, accounting for roughly $9,000,000 in transaction performance, entirely isolating secondary international markets like the Netherlands and Eire which sit beneath the $500,000 milestone.
* **Insight 3 (High-Velocity Operational Core Inventory):** Inventory transaction frequency is intensely anchored by accessible consumer home accent assets. The White Hanging Heart T-Light Holder commands the highest velocity index with over 2,300 independent orders, followed immediately by the Jumbo Bag Red Retrospot at over 2,000 orders, establishing these SKUs as high-priority operational targets for rapid fulfillment zoning.
* **Insight 4 (Strategic Cleaning Impact Justification):** Advanced retail distribution profiling proved that leaving raw systemic anomalies unchecked would directly risk incorporating massive multi-thousand-dollar system accounting noise into corporate reports. Programmatic filtering was verified as mandatory to ensure metrics remain accurate and unpolluted.
