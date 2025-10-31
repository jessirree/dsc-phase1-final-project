# Aviation Risk Analysis Project

## Overview

This project analyzes civil aviation accident data to help a company make informed decisions about purchasing and operating aircraft for commercial and private enterprises. Using data cleaning, analysis, and visualization techniques, we identify low-risk aircraft models and generate actionable business recommendations.

The dataset includes aviation accidents and selected incidents in the United States and international waters from 1962 to 2023, sourced from the National Transportation Safety Board (NTSB).

---

## Business Understanding

The company is expanding into the aviation industry but lacks knowledge about aircraft risk levels. The primary objective of this project is to:

- Identify aircraft models with the lowest accident and fatality rates.
- Highlight trends in aviation accidents over time.
- Provide data-driven recommendations for purchasing decisions.

Key Business Questions:

1. Which aircraft models are the safest for investment?
2. How do accident and fatality rates vary by aircraft type?
3. Are there trends in accident frequency or severity over time that the company should consider?

---

## Data Understanding

**Source:** National Transportation Safety Board (NTSB) aviation accident dataset.

**Relevant Columns:**

- `Event.Date` – Date of the accident
- `Location` / `Country` – Geographic location of the incident
- `Make` / `Model` – Aircraft manufacturer and model
- `Injury.Severity` – Severity of injuries
- `Aircraft.damage` – Extent of aircraft damage

**Data Challenges:**

- Missing values in certain fields (handled via imputation or removal)
- Standardizing categorical values (e.g., "Fatal" vs. "fatal")
- Aggregating accident data by aircraft model

---

## Data Analysis & Visualizations

The analysis focused on identifying aircraft risk by combining accident frequency and fatality data.

**Key Visualizations:**

1. **Top 20 Aircraft by Accident Count** – Highlights models with the highest number of incidents.
2. **Fatal Accident Rate by Model** – Shows the proportion of fatal accidents per aircraft model.
3. **Accident Trends Over Time** – Displays how the number of aviation accidents has changed from 1962 to 2023.

These visualizations are included in the notebook and the interactive dashboard, allowing stakeholders to filter by aircraft make, model, or country.

[Here is thelink to Tableau dashboard:](https://public.tableau.com/app/profile/faith.koech/viz/AviationData_17619372859230/Dashboard1)

---

## Recommendations

Based on the analysis:

1. **Purchase Low-Risk Aircraft Models**  
   Focus on aircraft with the lowest fatal accident rates to minimize potential financial and operational risks.

2. **Prioritize Modern Aircraft**  
   Older models tend to have higher accident rates. Investment in newer models can improve safety and reduce maintenance costs.

3. **Consider Regional Risk Factors**  
   Certain regions show higher accident frequencies. Incorporate geographic risk assessment in operational planning and insurance considerations.

---

## Next Steps

- Explore maintenance and operational factors contributing to accidents.
- Incorporate additional datasets (e.g., flight hours, airline usage) to refine risk assessment.
- Continuously update the dashboard with new data to maintain up-to-date insights for business decisions.
