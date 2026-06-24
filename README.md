# Heart Disease Data Analysis

**End-to-end data analytics project** exploring factors associated with heart disease using Python, pandas, and data visualization.

## Project Overview

Heart disease remains one of the leading causes of death worldwide. This project analyzes a heart disease dataset to identify key risk factors and patient characteristics associated with the presence of heart disease. The goal is to uncover actionable insights that could support early detection and prevention strategies.

**Main Business / Analytical Question:**
What factors are most strongly associated with heart disease, and can we identify high-risk patient profiles through exploratory data analysis?

## Dataset

- **Source**: Kaggle – [Heart Failure Prediction Dataset](https://www.kaggle.com/datasets/fedesoriano/heart-failure-prediction)
- **Records**: 918 patients
- **Features**: 11 clinical and demographic variables + 1 target variable (`HeartDisease`)
- **Key Variables**:
  - Demographics: Age, Sex
  - Clinical: ChestPainType, RestingBP, Cholesterol, FastingBS, RestingECG, MaxHR, ExerciseAngina, Oldpeak, ST_Slope
  - Target: HeartDisease (1 = heart disease present, 0 = no heart disease)

## Project Goals

- Load and thoroughly explore the dataset
- Clean and prepare the data for analysis (handle missing values, data types, outliers)
- Perform exploratory data analysis using summary statistics and visualizations
- Identify relationships between clinical/demographic factors and heart disease
- Communicate key findings clearly through visualizations and narrative

## Methodology

1. **Data Loading & Inspection** — Understand structure, data types, and initial quality issues.
2. **Data Cleaning & Wrangling** — Handle missing values, fix data types, rename columns for consistency, and address outliers where appropriate.
3. **Exploratory Data Analysis (EDA)**:
   - Univariate analysis (distributions of key variables)
   - Bivariate analysis (relationships with `HeartDisease`)
   - Multivariate exploration and correlations
4. **Visualization** — Use matplotlib and seaborn to create clear, insightful charts.
5. **Insight Generation** — Summarize findings and discuss potential implications.

## Key Skills Demonstrated

This project showcases core data analyst competencies:

- **Python for Data Analysis** — pandas for data loading, cleaning, transformation, and aggregation
- **Data Wrangling & Tidying** — Handling missing data, data type conversion, and feature engineering
- **Exploratory Data Analysis** — Summary statistics, distributions, and pattern identification
- **Data Visualization** — Creating clear univariate and bivariate visualizations using matplotlib and seaborn
- **Statistical Thinking** — Identifying correlations and relationships between variables
- **Communication of Findings** — Documenting the analysis process and insights in a reproducible Jupyter Notebook

## How to Run This Project

1. Clone the repository:
   ```bash
   git clone https://github.com/senseirandystl/Data-Analyst-Final-Project.git
   cd Data-Analyst-Final-Project