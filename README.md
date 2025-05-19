# Groundwater Quality Analysis of Maharashtra

## Project Overview
This project analyzes the groundwater quality across various districts in Maharashtra (a State in India) using data from the Central Ground Water Board (CGWB) 2023. The analysis helps identify contamination hotspots and informs decision-making for sustainable water management.

## Tools & Technologies
- **Data Collection**: Central Ground Water Board (CGWB), Maharashtra Groundwater Reports
 2023 (Official Government Website )
- **Data Scarping**: Python (Camelot library for PDF scraping)
- **Data Cleaning & Analysis**: Power BI
- **Visualization**: Power BI, custom KPIs, heatmaps, scatter plots, treemaps

## Dataset
- Parameters: NO3, Fluoride (F), Uranium (U), SAR, RSC, TDS, pH
- 1300+ village wells across Maharashtra
- Classified by Aquifer Types: Confined (137 samples) & Unconfined (1346 samples)

## Key Visual Insights
- **Aquifer Distribution**: Most wells are in unconfined aquifers, making them vulnerable to pollution
- **NO3 Hotspot Map**: High nitrate levels in Nashik, Jalgaon, Ratnagiri
- **NO3 vs TDS Scatter Plot**: High NO3 often correlates with high TDS
- **District Risk Distribution (Donut Chart)**:
  - 12% High-risk districts
  - 44% Moderate risk
  - 43% Safe

## KPIs Identified
- **NO3**: 36% samples exceeded BIS limits (>45 mg/L)
- **Fluoride**: 12% exceeded safe limit (>1.0 mg/L)
- **TDS**: 15% above 1000 mg/L, affecting taste and safety
- **RSC**: 10% above critical level (>1.25), risking soil and crop health
- **Risk Score (BIS-based)**: Used to categorize contamination severity by district

## Notable Findings
- **Chandrapur and Nashik**: High overall contaminant exceedance
- **Ratnagiri, Nashik, Wardha**: High number of wells unsuitable for drinking

## Conclusion
The analysis highlights urgent need for intervention in high-risk regions and the value of continuous monitoring and better aquifer protection practices.
