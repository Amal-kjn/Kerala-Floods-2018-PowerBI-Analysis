# Kerala Floods 2018 Analysis Dashboard

## 📌 Project Overview

This Power BI dashboard analyzes the impact of the 2018 Kerala floods using district-wise disaster data. The project transforms raw data into interactive visualizations that highlight rainfall patterns, district-level damage, casualties, and key disaster metrics to support data-driven analysis.

---

## 📂 Dataset

- **Dataset:** district_wise_details.csv
- **Source:** Kerala State Disaster Management Authority (KSDMA)
- **Coverage:** District-wise flood statistics for all 14 districts of Kerala.

---

## 🎯 Objectives

- Compare actual rainfall with normal rainfall across districts.
- Identify the districts most severely affected by the floods.
- Analyze the relationship between rainfall and flood damage.
- Present disaster data through interactive Power BI visualizations.

---

## 🛠 Data Preparation

The following preprocessing steps were performed before visualization:

- Verified and corrected data types using Power Query.
- Created an **Excess Rainfall** calculated column.
- Created a **Percentage Deviation** calculated column using DAX.
- Cleaned and validated district-wise disaster data.

---

## 📊 Dashboard Visualizations

The dashboard consists of multiple interactive visualizations designed to provide a comprehensive overview of the impact of the 2018 Kerala floods.

| Visualization | Purpose |
|--------------|---------|
| 🗺️ Filled Map | Displays district-wise rainfall intensity across Kerala. |
| 📊 Clustered Column Chart | Compares actual rainfall with normal rainfall for each district. |
| 📈 Scatter Chart | Analyzes the relationship between rainfall and the number of fully damaged houses. |
| 📉 Bar Chart | Compares the number of landslides across districts to identify the most landslide-prone areas. |
| 📌 KPI Cards | Summarize key metrics such as total fatalities, relief camps, and fully damaged houses. |

---

## 📊 Dashboard Preview

![Kerala Floods Dashboard](screenshot.png)

---

## 📈 Key Insights

- **Idukki** received the highest rainfall during the 2018 floods, followed by **Wayanad**, while **Thiruvananthapuram** recorded the lowest rainfall among all districts.

- **Thrissur** reported the highest number of fatalities (**72 deaths**) despite ranking only **7th** in total rainfall received. The district also recorded approximately **3,000 fully damaged houses**, indicating that flood severity was influenced by factors beyond rainfall alone.

- **Kasaragod** experienced rainfall levels that were nearly identical to its normal rainfall, making it the least affected district in terms of rainfall deviation.

- **Idukki** recorded the highest number of landslides, followed by **Wayanad**, highlighting the increased landslide risk in Kerala's hilly districts during extreme rainfall events.

- A total of **339 fatalities** were reported across Kerala during the 2018 floods, demonstrating the significant human impact of the disaster.

---

## 💡 Recommendations

- Strengthen flood mitigation and landslide monitoring systems in high-risk districts such as Idukki and Wayanad.

- Enhance disaster preparedness and evacuation planning in districts with historically high casualty rates.

- Improve early warning systems by integrating rainfall forecasts with district-level vulnerability assessments.

- Prioritize resilient housing and infrastructure development in flood-prone regions to reduce future losses.

---

## 🧰 Tools Used

- Power BI Desktop
- Power Query
- DAX
- Data Cleaning
- Data Visualization

---

## 📥 Project Files

The complete Power BI project is available in this repository.

**Project File:** `Kerala_Floods_2018_Dashboard.pbip`

---

## 📚 Data Source

Kerala State Disaster Management Authority (KSDMA)

**Reference:** Additional Memorandum – Kerala Floods 2018
