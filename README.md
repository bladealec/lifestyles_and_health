# Lifestyle Analysis

This repository contains a Jupyter Notebook (`lifestyle_analysis.ipynb`) that analyzes a dataset on sleep health and lifestyle factors. The dataset is sourced from Kaggle.

## Dataset

The dataset used in this analysis is `Sleep_health_and_lifestyle_dataset.csv`. It contains the following columns:

1. **Person ID**: Unique identifier for each person.
2. **Gender**: Gender of the person.
3. **Age**: Age of the person.
4. **Occupation**: Occupation of the person.
5. **Sleep Duration**: Average sleep duration in hours.
6. **Quality of Sleep**: Quality of sleep on a scale of 1 to 10.
7. **Physical Activity Level**: Physical activity level in minutes per day.
8. **Stress Level**: Stress level on a scale of 1 to 10.
9. **BMI Category**: Body Mass Index category.
10. **Blood Pressure**: Blood pressure measurement.
11. **Heart Rate**: Heart rate in beats per minute.
12. **Daily Steps**: Number of daily steps.
13. **Sleep Disorder**: Type of sleep disorder if any.

## Analysis Overview

The analysis in `lifestyle_analysis.ipynb` includes the following sections:

1. **Dataset Information and Descriptive Statistics**: Initial exploration of the dataset including data types, non-null counts, and summary statistics.
2. **Visualization**:
    - **Sleep Duration by Occupation**: Boxplot of sleep duration across different occupations.
    - **Quality of Sleep by Occupation**: Boxplot of sleep quality across different occupations.
    - **Correlation Matrix**: Heatmap showing correlations between numerical variables.
    - **Distribution of Sleep Disorders**: Count plot showing the distribution of different sleep disorders.
    - **Sleep Duration by BMI Category**: Boxplot of sleep duration across different BMI categories.
    - **Physical Activity Level by Sleep Disorder**: Bar plot of average physical activity level across different sleep disorders.
    - **Heart Rate by Sleep Disorder**: Boxplot of heart rate across different sleep disorders.
3. **Insights**:
    - **Average Sleep Duration by Occupation**: Analysis of average sleep duration by occupation.
    - **Average Quality of Sleep by Occupation**: Analysis of average sleep quality by occupation.
    - **Average Blood Pressure by Occupation**: Analysis of average systolic and diastolic blood pressure by occupation.
    - **Mean Arterial Pressure (MAP) and Pulse Pressure**: Calculation and analysis of MAP and pulse pressure by occupation.
    - **Average Stress Level by Occupation**: Analysis of average stress levels by occupation.
    - **Best and Worst Occupations**: Identification of the best and worst occupations in terms of sleep duration, sleep quality, blood pressure, MAP, pulse pressure, and stress level.
  
## Results

Some key insights from the analysis include:

- **Engineers** have the best sleep duration and quality.
- **Sales Representatives** have the worst sleep duration and quality.
- **Accountants** have the best blood pressure readings and MAP.
- **Nurses** have the worst blood pressure readings and MAP.
- **Engineers** have the lowest stress levels, while **Sales Representatives** have the highest stress levels.

For detailed analysis and visualizations, refer to the `lifestyle_analysis.ipynb` notebook.

