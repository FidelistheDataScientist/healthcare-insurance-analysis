# Healthcare Insurance Analysis

A two-page Power BI dashboard analysing medical insurance charges by age, BMI, smoking status, region, sex and number of children.

## Dashboard Preview

### Page 1: Overview
![Overview](Images/dashboard-overview.png)

### Page 2: Risk & Cost Drivers
![Risk and Cost Drivers](Images/dashboard-risk-cost-drivers.png)

## Dataset

Medical insurance dataset with 1.34K policyholders and these fields: age, sex, BMI, children, smoker, region, charges.

Source: [Medical Cost Personal Datasets (Kaggle)](https://www.kaggle.com/code/mragpavank/medical-cost-personal-datasets)

## Key Metrics

| Metric | Value |
|---|---|
| Total policyholders | 1.34K |
| Total charges | $17.8M |
| Average charge | $13.3K |
| Smokers | 20.48% |
| Average BMI | 30.66 |
| Smoker cost multiple | 3.80x |
| Average charge, smokers | $32.1K |
| Average charge, non-smokers | $8.4K |
| Smokers' share of total charges | 49.46% |
| High-cost claims (> $30K) share | 37.19% |

## Key Findings

- **Smoking is the biggest cost driver.** Smokers are about 20% of policyholders but account for nearly half (49.46%) of total charges. Their average charge is 3.8x that of non-smokers.
- **Smoker costs are high for both sexes.** Average charges are about $33.0K for male smokers and $30.7K for female smokers, versus $8.1K and $8.8K for non-smokers.
- **Charges rise with age.** The average charge climbs from $9K (18-29) to $21K (60+).
- **Charges rise with BMI.** The average is $15K for the obese category, against $9K for underweight.
- **Region:** the Southeast has the highest total charges ($5.36M).

## Tools Used

- **Power Query:** data cleaning and preparation
- **Power BI:** data modelling and visualisation
- **DAX:** measures such as smoker cost multiple, smoker share of charges and high-cost share

## Repository Structure

```
├── README.md
├── data/        # source CSV
├── dashboard/   # .pbix file
├── images/      # dashboard screenshots
└── docs/        # DAX measures
```

## Author

**Fidelis Emechete**
[LinkedIn](https://www.linkedin.com/in/fidelis-emechete)
