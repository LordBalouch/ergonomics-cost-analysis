code README.md

# Ergonomics and Sick Leave Cost Analysis

## Overview

This project analyzes the financial impact of work-related musculoskeletal disorders (MSDs), focusing on sick leave caused by poor ergonomic conditions such as heavy lifting, poor posture, and repetitive movements.

Using real survey-based data and estimated country-level economic indicators, I evaluate how much MSD-related sick leave costs employers annually, and what potential savings could be achieved through ergonomic interventions like assistive equipment.

## Business Question

**How much could a company or industry save annually by reducing MSD-related sick leave through ergonomic interventions such as lifting aids?**

This project aims to answer that question using real data and cost modeling.

## Data Sources

- **EU-OSHA-Style Ergonomics Dataset**: Simulated sample based on the structure of the European Working Conditions Survey (EWCS). Includes physical strain exposure, assistive tool use, and reported back pain or MSD-related sick leave.
- **Country-Level Cost Data**: Estimated average daily salary and economic impact of sick leave across 10 European countries (based on OECD and Eurostat data).

## Key Steps in the Notebook

- Load and explore both datasets
- Clean and standardize country names
- Merge datasets to align ergonomics exposure with salary and sick leave costs
- Calculate estimated annual MSD-related cost per worker
- Save final dataset for visualization in Tableau

## Tools Used

- Python (pandas, matplotlib)
- Jupyter Notebook
- Tableau (for dashboard visuals)
- VS Code

## Output Files

- `ergonomics_cost_analysis.ipynb` – Main notebook
- `country_sick_leave_costs.csv` – Salary and sick leave cost data
- `eu_osha_ergonomics_dataset.csv` – Ergonomics survey data
- `final_ergonomics_cost_dataset.csv` – Merged and calculated dataset
- `README.md` – Project description

## Future Improvements

To expand this project further and enhance real-world value:

- Integrate official EWCS microdata (once access is granted via Eurofound)
- Incorporate real cost data for ergonomic assistive tools (e.g., RUBA, exosuits) to estimate ROI
- Develop a Tableau dashboard to visualize:
  - Country-level cost burdens
  - High-risk job roles
  - Projected savings from ergonomic interventions

These steps would enhance the project from analysis into a fully deployable business intelligence tool.

---

*This project was built as part of my data analytics portfolio to demonstrate real-world data cleaning, merging, cost modeling, and insight communication.*
