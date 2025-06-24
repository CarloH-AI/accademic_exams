## Overview

This repository contains **three university projects completed during the Data & Coding degree programme**: two first-year exam projects (“Coding and Data Management 1” and “Coding and Data Management 2”) and one second-year exam project (“Lab of Information Systems and Analytics”). Each folder includes Jupyter notebooks, supporting datasets, and—when required—a final PDF report.

## Repository Structure

```text
accademic_exams/
├── Coding and Data Management 1/
│   ├── Datasets/
│   │   ├── GDP_dataset.csv
│   │   ├── tourism_arrivals.csv
│   │   └── tourism_departures.csv
│   └── Coding Project.ipynb
└── Lab of Information Systems and Analytics/
    ├── Dataset/
    │   └── SeoulBikeData.csv
    ├── Project Notebook.ipynb
    └── Project_Report.pdf
```

## Projects

| Folder                                       | Year | Main topic & goals                                                                                                                                                                                           |
| -------------------------------------------- | ---- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| **Coding and Data Management 2**             | 1st  | • Exploratory analysis of macro-economic indicators (GDP) and tourist flows.<br>• Data cleaning, interactive visualisations, K-Means clustering.                                                             |
| **Lab of Information Systems and Analytics** | 2nd  | • Analysis of bike-sharing demand in Seoul (*SeoulBikeData*).<br>• Modelling (Linear Regression, SVR, XGBoost) and performance evaluation.<br>• PDF report with analyses, charts, and discussion of results. |

## Quick Requirements

```bash
python >= 3.10
pip install pandas numpy scikit-learn matplotlib seaborn plotly jupyter
```

> Tip: create a virtual environment first (`python -m venv .venv && source .venv/bin/activate`) before installing dependencies.

## Quick Start

1. Clone the repo

   ```bash
   git clone https://github.com/CarloH-AI/accademic_exams.git
   cd accademic_exams
   ```
2. Launch Jupyter Lab/Notebook and open the desired project:

   ```bash
   jupyter lab
   ```
