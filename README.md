# UIDAI Data Hackathon 2026  
## Aadhaar Lifecycle Analytics Dashboard  
**Team InsightForge**

📌 This project presents a consolidated analytical study of Aadhaar Enrolments, Demographic Updates, and Biometric Updates using official UIDAI aggregated datasets (2025).

---

## 📖 Project Overview

Aadhaar is the world’s largest biometric identity system and a foundational digital public infrastructure of India.

While UIDAI provides enrolment and update datasets separately, this project integrates them into a unified analytical framework to understand:

- 📍 Regional Aadhaar activity
- 👶 Age-wise lifecycle patterns
- 📊 Update-to-enrolment intensity
- 🗺 State & district-level concentration
- 📈 Seasonal demand trends

This analysis transforms large-scale raw datasets into clear, actionable insights using dashboards and KPI-driven metrics.

---

## 📂 Datasets Used (Year 2025)

1️⃣ **Aadhaar Enrolment Dataset**
- age_0_5
- age_5_17
- age_18_greater
- State, District, Pincode

2️⃣ **Aadhaar Demographic Update Dataset**
- demo_age_5_17
- demo_age_17_plus
- State, District, Revised Districts

3️⃣ **Aadhaar Biometric Update Dataset**
- bio_age_5_17
- bio_age_17_plus
- State, District, Corrected Districts

⚠️ All datasets are aggregated and contain no personal data.

---

## 🛠 Methodology

### 1️⃣ Data Ingestion
- Imported all three UIDAI datasets
- Reviewed structure and segmentation

### 2️⃣ Data Cleaning & Standardization
- Standardized state & district names
- Handled missing values
- Unified date formats
- Removed irrelevant columns

### 3️⃣ Data Transformation
- State & district-level aggregation
- Age group alignment
- Combined update activity calculation
- Created derived KPIs

### 4️⃣ KPI Design
- Total Enrolments
- Total Demographic Updates
- Total Biometric Updates
- Combined Aadhaar Activity
- Update-to-Enrolment Ratios
- Adult-Dominant Update Index
- Update Density Metrics

### 5️⃣ Dashboard Development
- Interactive visualizations
- Maps, ranked charts, KPI cards
- Slicer-based filtering
- Clean and minimal layout

---

# 📊 Dashboards Created

## 1️⃣ Enrolment Dashboard

### 🔍 Key Insights
- **54.35 lakh total enrolments**
- 36 States & UTs covered
- 800+ districts covered
- 0–5 age group dominates (65%)
- Adult enrolment only 3%

📌 Enrolments are child-driven and geographically uneven.

---

## 2️⃣ Demographic Dashboard

### 🔍 Key Insights
- **4.93 crore demographic updates**
- Adults contribute 90% of updates
- Adult-Dominant Update Index = 9.14 : 1
- Avg 6,162 updates per PIN
- MoM Growth = 2%
- Urban Concentration Index = 0.36 (Rural-spread)

📌 Demographic activity is overwhelmingly adult-driven and operationally intensive.

---

## 3️⃣ Biometric Dashboard

### 🔍 Key Insights
- **6.98 crore biometric updates**
- Age split nearly equal (5–17 vs 17+)
- Adult-Dominant Index = 1.04 : 1
- MoM Growth = 9.5%
- Strong regional concentration in high-density districts

📌 Biometric updates are lifecycle-driven and age-neutral.

---

## 4️⃣ Summary Dashboard

### 🔍 Total Aadhaar Activity

| Metric | Value |
|--------|-------|
| Total Enrolments | 54.35 Lakh |
| Demographic Updates | 4.93 Crore |
| Biometric Updates | 6.98 Crore |
| Total Interactions | **12.45 Crore** |

### 🔥 Critical Insight

For every **1,000 enrolments**, there are:

- 9,071 demographic updates
- 12,837 biometric updates
- Over **21,000 update transactions**

👉 Aadhaar is a lifecycle-based, update-dominated system — not a one-time enrolment platform.

---

# 📈 Major Findings

✅ Updates far exceed new enrolments  
✅ Aadhaar operations are maintenance-heavy  
✅ Strong geographic concentration in select districts  
✅ Seasonal demand peaks (March, July, Nov-Dec)  
✅ Nationwide participation (36 States & UTs)  
✅ High update density requiring scalable infrastructure  

---

# 🧮 Analytical Components Used

- Pivot Tables
- Calculated Fields
- Dynamic Ranking (Top 10 Districts)
- State-wise Aggregations
- Age-based segmentation
- Indian number formatting logic (K/Lakh/Crore)
- Urban–Rural classification logic

---

# 🤖 Machine Learning Extension

A prediction model has been developed (linked in official submission) to forecast Aadhaar activity trends.

---

# 🎯 Key Outcomes

- Converted raw UIDAI datasets into actionable insights
- Designed lifecycle-driven KPIs
- Identified high-load regions
- Highlighted update intensity challenges
- Enabled policy-relevant decision metrics

---

# 👨‍💻 Team InsightForge

**Yug Trivedi**  
📧 ytrivedi561@gmail.com  

**Mantragna Shukla**  
📧 mantrashukla07@gmail.com  

---

# 🏁 Conclusion

This project demonstrates that Aadhaar is a high-frequency, lifecycle-driven digital public infrastructure requiring:

- Adaptive service delivery
- Capacity planning
- Region-specific operational strategy
- Continuous infrastructure scaling

---

**Created for UIDAI Data Hackathon 2026**
