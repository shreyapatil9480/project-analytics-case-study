## Data Generation

The underlying dataset is **synthetic** and was generated programmatically. Random start and end dates between 2022 and 2024 were sampled along with budgets, spend amounts, team sizes and risk scores.

To simulate realistic behaviour:

- **Spending** was computed as a random multiplier (0.5 – 1.5 × budget) to allow for underspend and overspend.
- **Project duration** is the number of days between the start and end dates.
- **Client satisfaction ratings** were derived from the overspend ratio and risk score, with added noise to mimic real-world variability.

A binary indicator, `high_satisfaction`, flags projects with satisfaction ratings of 7 or above. You can regenerate a similar dataset by modifying the data generation script or creating your own synthetic parameters.
