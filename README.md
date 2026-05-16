-- 32146983_Batch2 --

# NorthStar Urban Mobility – Databases and Analytics Coursework

## Overview
This repository contains the analytical work supporting the coursework report:
*"Improving Operational Performance at NorthStar Urban Mobility: An Integrated NoSQL Analytics Approach"*

## Notebooks
|       Notebook              |             Description                 |
|-----------------------------|-----------------------------------------|
| 01_SQL_R_Analysis           | SQL queries in R                        |
| 02_R_Statistics.ipynb       | Statistical Analysis                    |
| 02_Python_Analytics         | Data cleaning and visualisation         |
| 03_MongoDB_Implementation   | NoSQL design and CRUD                   |
| 04_Query_Optimisation       | Index strategy and explain plans        |

## Dataset
All data files are in the `/data` directory and are loaded directly into the notebooks.

## Dependencies
- R: `sqldf`, `dplyr`, `ggplot2`, `readr`, `lubridate`
- Python: `pandas`, `numpy`, `matplotlib`, `seaborn`, `scipy`, `pymongo`

## Directory Structure
```
northstar-data_analysis/
│
├── README.md
├── case-study/
├── coursework-report/
|   └── DBACoursework_32146983_Batch2.pdf
|
├── data/
│   ├── raw/
|   └── cleaned/
│
├── notebooks/
│   ├── 01_SQL_R_Analysis.ipynb            # R  – SQL queries + CRUD Operations
|   ├── 02_R_Statistics.ipynb              # R  – Statistical analysis
│   ├── 03_Python_Analytics.ipynb          # Python – Pandas, cleaning, charts
│   ├── 04_MongoDB_Implementation.ipynb    # Python – PyMongo CRUD and aggregation
│   └── 05_Query_Optimisation.ipynb        # Python – Index creation, explain plans
│
└── outputs/
    ├── figures/                           # All exported charts (PNG)
    |   ├── notebook1/                     # Figures generated in: 01_SQL_R_Analysis.ipynb
    │   ├── notebook2/                     #                   in: 02_R_Statistics.ipynb
    │   ├── notebook3/                     #                   in: 03_Python_Analytics.ipynb
    │   └── notebook4/                     #                   in: 04_MongoDB_Implementation.ipynb
    └── tables/
```
---

*The true measure of success isn't a perfect grade, but the commitment to learn continously for a slong as you live and the willingness to oversome challenges that matter.
Every line of code is a step forward. Keep learning.* 📊
