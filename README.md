# HR Employee Analysis

A Python data analysis project exploring workforce composition and attrition patterns using IBM HR employee data.

## Objective

Identify the main factors behind employee turnover and understand how income, age, and department relate to attrition.

## Technologies Used

- Python 3.12
- Pandas — data manipulation and cleaning
- NumPy — numerical operations
- Matplotlib — custom visualizations
- Seaborn — statistical charts
- Jupyter Notebook

## Dataset

| Field | Details |
|---|---|
| Source | IBM HR Employee dataset |
| Records | 1,470 employees |
| Columns | Age, Department, Job Role, Monthly Income, Attrition, Satisfaction Scores |

## Questions Answered

1. What is the overall attrition rate?
2. Which departments have the highest turnover?
3. How does income vary across job roles?
4. Are younger or lower-paid employees more likely to leave?
5. What factors correlate most with income and tenure?

## Key Insights

- **16.1% attrition rate** — approximately 1 in 6 employees left the company
- **Sales** has the highest number of departures in absolute terms
- Most employees earn between **$2,000 and $6,000/month**
- **Younger, lower-paid employees** show a higher concentration of attrition
- **Income, working years, and age** are strongly correlated — experience drives pay
- **Satisfaction scores have a weak correlation with income**, suggesting pay alone is not the only driver

## Visualizations

| Chart | Description |
|---|---|
| Bar chart | Overall attrition rate (Yes vs No) |
| Count plot | Attrition breakdown by department |
| Histogram + KDE | Monthly income distribution |
| Box plot | Income range by job role |
| Scatter plot | Age vs income, colored by attrition |
| Heatmap | Correlation between key HR variables |

## Project Structure

```
hr-employee-analysis/
├── data/
│   └── ibm_hr_data.csv
├── notebooks/
│   └── hr_analysis.ipynb
├── images/
├── README.md
└── requirements.txt
```

## How to Run

```bash
pip install -r requirements.txt
jupyter notebook notebooks/hr_analysis.ipynb
```

## Conclusion

Attrition is concentrated among younger, lower-paid employees — especially in Sales. Retention strategies focused on competitive entry-level pay and career development are likely to have the highest impact.
