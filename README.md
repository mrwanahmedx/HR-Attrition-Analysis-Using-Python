# HR Attrition Analysis in Python

Exploratory analysis of employee attrition using the IBM HR Analytics dataset, focused on workforce segmentation, overtime, income, role, experience, and other variables associated with employee turnover.

> This is an exploratory analytics project. The analysis identifies associations in the dataset; it does **not** establish causal drivers of attrition.

## Business question

Which workforce characteristics are associated with higher or lower attrition rates, and how does the story change when the same employee population is segmented in different ways?

## Analysis workflow

```mermaid
flowchart LR
    A[IBM HR dataset] --> B[Data inspection and cleaning]
    B --> C[Univariate exploration]
    C --> D[Segment comparisons]
    D --> E[Attrition-rate analysis]
    E --> F[Visualization]
    F --> G[Business interpretation]
```

## Areas explored

- overtime versus attrition,
- monthly income and compensation patterns,
- job-role differences,
- experience and tenure variables,
- department / workforce segmentation,
- correlation and distribution analysis.

## Key observations

The notebook highlights patterns such as:

- employees working overtime showing a higher attrition rate in this dataset,
- lower-income groups displaying different turnover patterns,
- some job roles showing visibly different attrition rates,
- experience and tenure variables varying between employees who stayed and left.

These are **descriptive findings** from one dataset. They should not be converted directly into HR policy without further validation, confounder analysis, and appropriate causal or experimental evidence.

## Notebook

- **Repository notebook:** [hr_attrition_analysis.ipynb](./hr_attrition_analysis.ipynb)
- **Kaggle version:** [View the notebook on Kaggle](https://www.kaggle.com/code/jinxraven/jinx-s-ibm-hr-worksheet)

## Run locally

1. Install dependencies with `pip install -r requirements.txt`.
2. Place the public IBM HR CSV at `data/WA_Fn-UseC_-HR-Employee-Attrition.csv`.
3. Open `hr_attrition_analysis.ipynb`.

The notebook also detects the original Kaggle input path automatically.

## Tech stack

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

## What this project demonstrates

- reproducible data loading and inspection,
- data inspection and preprocessing,
- exploratory data analysis,
- group-level rate calculation,
- distribution and correlation analysis,
- translating statistical patterns into business-readable findings,
- separating descriptive evidence from causal claims.

## Limitations

- cross-sectional exploratory analysis,
- associations do not establish causality,
- no production attrition model or intervention strategy is claimed,
- results depend on the IBM HR dataset and may not generalize to other organizations,
- demographic / fairness implications require separate analysis before operational use.

## Related browser case study

A companion interactive workforce view is included in **Data Observatory**, where the same population can be explored under different groupings.

**[Open the browser case study](https://mrwanahmedx.github.io/data-observatory/people.html)**  
**[View Data Observatory source](https://github.com/mrwanahmedx/data-observatory)**

## Author

**Marwan Ahmed**  
[LinkedIn](https://www.linkedin.com/in/mrwan-ahmed/) · [GitHub](https://github.com/mrwanahmedx)
