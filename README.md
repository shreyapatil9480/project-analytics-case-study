# Project Management Analytics: A Synthetic Case Study

This repository contains a self‑contained analytics project designed to showcase skills relevant for business analysts, program managers and data analysts. The project uses a **synthetic dataset** that simulates 500 projects with attributes such as budgets, spending, team sizes, risk scores and client satisfaction ratings. The goal is to perform exploratory analysis, visualize key relationships and build predictive models to anticipate project success.

## Repository structure

```
├── data/
│   └── synthetic_project_data.csv  # synthetic dataset of 500 projects
├── notebooks/
│   └── project_analysis.ipynb      # analysis notebook with EDA & models
├── requirements.txt                # Python dependencies for reproducibility
└── README.md                       # Project overview and instructions
```

### Dataset fields

| Column              | Description                                                      |
|---------------------|------------------------------------------------------------------|
| `project_id`        | Unique identifier for each project                               |
| `start_date`        | Project start date                                               |
| `end_date`          | Project completion date                                          |
| `duration_days`     | Number of days between start and end dates                       |
| `budget`            | Planned budget (in currency units)                               |
| `spend`             | Actual spend incurred                                            |
| `team_size`         | Number of people assigned to the project                         |
| `risk_score`        | Risk assessment on a scale from 1 (low) to 5 (high)              |
| `satisfaction_rating` | Client satisfaction score on a scale from 1 (worst) to 10 (best) |
| `high_satisfaction` | Binary indicator (1 if satisfaction_rating ≥ 7, else 0)          |

## Getting started

1. **Clone** or download this repository.
2. Create a Python environment and install dependencies:

   ```bash
   pip install -r requirements.txt
   ```
3. Launch Jupyter and open the analysis notebook:

   ```bash
   jupyter notebook notebooks/project_analysis.ipynb
   ```

4. Run the cells in order to reproduce the exploratory data analysis, visualizations and predictive models.

## Project tasks

This project is structured to progress from basic analysis to more advanced modeling:

1. **Exploratory Data Analysis (EDA)** – examine the distribution of project durations, budgets and satisfaction ratings; compute summary statistics.
2. **Visualization** – create histograms, scatter plots and correlation heatmaps to understand relationships among variables.
3. **Binary classification model** – use logistic regression to predict whether a project will yield **high client satisfaction** based on budget, spending, team size and risk score.
4. **Regression model** – use linear regression to predict the **continuous satisfaction rating** from the same set of predictors.
5. **Extensions** – suggestions are provided in the notebook for adding additional features, trying other algorithms and deploying the models.

Feel free to fork or clone this repository and build upon it. You can adjust the synthetic data generation process, experiment with alternative models or visualizations, and tailor the analysis to reflect the types of business problems you encounter.
