# Alzheimer's Disease and Healthy Aging Data Analysis

This project analyzes data from the Behavioral Risk Factor Surveillance System (BRFSS) to explore the relationship between Alzheimer's disease, healthy aging, and various lifestyle factors. The goal of the analysis is to uncover key insights into how health behaviors, demographics, and medical conditions contribute to healthy aging and Alzheimer's disease risk.

## Overview

The dataset used for this project is sourced from the BRFSS, a comprehensive health survey system that collects data on various health behaviors, chronic conditions, and health-related risk factors across the U.S. The analysis focuses on identifying patterns and trends related to Alzheimer's disease and factors that contribute to healthy aging. The insights gained from this analysis could be valuable for public health initiatives and interventions targeting healthy aging and Alzheimer's prevention.

## Dataset

The BRFSS dataset contains various health metrics, including:

- **Demographics** (age, gender, education level, etc.)
- **Lifestyle Factors** (physical activity, smoking, alcohol use, etc.)
- **Chronic Conditions** (diabetes, hypertension, etc.)
- **Cognitive Health** (self-reported Alzheimer's diagnosis, memory issues, etc.)

### Key Columns in the Dataset

- `Age`: Age of the participant
- `Gender`: Gender of the participant
- `Education`: Highest level of education attained
- `PhysicalActivity`: Whether the participant engages in regular physical activity
- `Smoking`: Smoking status (e.g., smoker, non-smoker)
- `AlcoholUse`: Alcohol consumption habits
- `ChronicConditions`: Presence of chronic conditions like diabetes, hypertension
- `AlzheimerDiagnosis`: Self-reported diagnosis of Alzheimer's disease or dementia
- `MemoryIssues`: Self-reported memory problems or cognitive decline

## Objectives

1. **Data Cleaning and Preprocessing:**
   - Handle missing data, outliers, and incorrect entries.
   - Convert categorical variables into a usable format for analysis.

2. **Exploratory Data Analysis (EDA):**
   - Visualize the distribution of key variables such as age, gender, and health behaviors.
   - Investigate the relationship between Alzheimer's diagnosis and other health factors.

3. **Correlation Analysis:**
   - Identify correlations between Alzheimer's diagnosis and lifestyle factors, medical conditions, and demographics.
  
4. **Predictive Modeling:**
   - Build machine learning models to predict the likelihood of Alzheimer's diagnosis based on demographic and health-related factors.
  
5. **Statistical Analysis:**
   - Conduct hypothesis testing to understand significant factors contributing to healthy aging and Alzheimer's risk.

## Technologies Used

- Python
  - Pandas (for data manipulation)
  - NumPy (for numerical computations)
  - Matplotlib, Seaborn (for data visualization)
  - Scikit-learn (for machine learning)
  - Statsmodels (for statistical analysis)

- Jupyter Notebook (for interactive data exploration)

