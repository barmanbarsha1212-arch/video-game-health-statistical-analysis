# Statistical Analysis of Video Game & Health Monitoring Data

## Project Overview

This project performs exploratory data analysis and statistical analysis on two datasets:

1. **Video Game Reviews Dataset** — analyzes player engagement and review scores.
2. **Health Monitoring Dataset** — analyzes blood pressure patterns across age groups and the relationship between smoking status and blood pressure.

The project focuses on data distributions, variability, outlier detection, correlation analysis, and statistical significance.

## Objectives

- Analyze descriptive statistics and data distributions
- Visualize distributions using box plots
- Identify statistical outliers using the IQR method
- Analyze blood pressure patterns across age groups
- Measure the relationship between hours played and review scores
- Measure the association between smoking status and blood pressure
- Select appropriate correlation methods based on variable types
- Interpret statistical significance and practical implications

## Datasets

### 1. Video Game Reviews

- Records: 60
- Variables:
  - Player ID
  - Hours Played
  - Review Score

### 2. Health Monitoring

- Records: 120
- Variables:
  - Participant ID
  - Age
  - Blood Pressure
  - Smoking Status

## Tools & Technologies

- Python
- Pandas
- NumPy
- SciPy
- Matplotlib
- Exploratory Data Analysis (EDA)
- Statistical Analysis
- Data Visualization

## Methodology

### Exploratory Data Analysis

Calculated:

- Mean
- Median
- Mode
- Minimum and Maximum
- Standard Deviation
- Quartiles
- Interquartile Range (IQR)
- Skewness

### Outlier Detection

The standard 1.5 × IQR rule was used to identify statistical outliers.

### Correlation Analysis

**Pearson Correlation**

Used for:

`Hours Played ↔ Review Score`

Both variables are continuous numerical variables.

**Point-Biserial Correlation**

Used for:

`Smoking Status ↔ Blood Pressure`

Smoking Status is binary while Blood Pressure is continuous.

## Key Findings

### Video Game Analysis

- Median Review Score: **80.50**
- Mean Review Score: **80.62**
- Review Score IQR: **17.25**
- No statistical outliers were identified in Review Score.
- Hours Played showed positive right-skewness.
- Pearson correlation between Hours Played and Review Score:

**r = 0.01, p = 0.96**

This indicates an extremely weak linear relationship that was not statistically significant in this dataset.

### Health Monitoring Analysis

- Highest median blood pressure was observed in the **40s group: 138.50 mmHg**.
- The **60+ group** had the largest IQR: **28.00 mmHg**.
- The **30s group** had the smallest IQR: **8.65 mmHg**, but contained four statistical outliers.
- Point-Biserial correlation between Smoking Status and Blood Pressure:

**r = -0.13, p = 0.15**

The observed association was weak and not statistically significant.

## Visualizations

The project includes:

- Review Score Box Plot
- Blood Pressure Box Plot by Age Group
- Distribution and outlier analysis
- Statistical summaries

## Statistical Interpretation

The analysis demonstrates that correlation does not imply causation.

The tested relationships were not statistically significant at the 5% significance level. The findings describe the analyzed samples and should not be generalized to broader populations without larger and more representative datasets.

## Limitations

- The datasets contain relatively small samples.
- The analysis is descriptive and correlational.
- Correlation does not establish causation.
- Additional variables and potential confounding factors were not available in the datasets.
- The findings should be interpreted within the scope of the provided samples.

## Project Files

## Project Files

## Project Files

- `Both updated dataset.csv` — Video Game Reviews dataset
- `Health_Monitoring_Dataset.csv` — Health Monitoring dataset
- `Barsha_Barman_Capstone_Project_Report.pdf` — Final capstone report
- `Barsha_Barman_Capstone_Project_Presentation.pptx` — Project presentation

## Author

**Barsha Barman**

Data Analytics | Python | Statistical Analysis | Data Visualization

## Academic Project

This project was completed as part of an academic capstone project.
