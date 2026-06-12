# Store Layout Change Impact Analysis  
### Matched Control Store Evaluation of Retail Performance

---

## Overview

This project evaluates the impact of a new store layout introduced in selected retail locations using a matched control store approach.

The goal is to determine whether the intervention leads to measurable improvements in store performance compared to baseline operations.

Analysis focuses on three core retail KPIs:
- Sales revenue  
- Customer count  
- Transactions per customer  

The full interpretation of results is provided in the accompanying presentation.

---

## Business Context

A retail company tested a new store layout across selected stores in the chips category during the period Feb 2019 – Apr 2019.

The key question:

> Does the new layout improve performance relative to comparable stores operating under the existing layout?

---

## Analytical Approach

The evaluation is based on a matched control store framework designed to isolate the effect of the intervention.

Control stores were identified using a composite similarity measure combining:
- Correlation of pre-trial trends  
- Normalized RMSE for magnitude alignment  

Once matched, trial and control stores were compared across pre- and post-intervention periods to assess performance differences.

---

## Data Scope

This analysis uses a merged retail dataset derived from a previous customer segmentation project, combining transaction-level sales data with customer attributes.

---

## Key Insights (High-Level)

Store-level performance shows variation in response to the layout change, indicating that the effect is not uniform across locations.

Detailed results and interpretation are provided in the presentation and notebook.

---

## Tools Used

- Python (pandas, numpy)  
- Visualization (matplotlib, seaborn)  
- Statistical testing (SciPy: t-test, t-distribution)  
- Jupyter Notebook  
- PowerPoint (business communication)  

---

## Repository Contents

- [Analysis Notebook](sales-impact-analysis-using-matched-control-stores.ipynb) → Full analytical workflow  
- [Presentation](Store-Control-Analysis.pdf) → Business insights and conclusions  

---

## Workflow

1. Review the business context  
2. Explore the notebook for full analysis  
3. Review the presentation for interpretation and recommendations  
