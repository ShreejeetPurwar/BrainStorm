# Healthcare Stroke Prediction Project

## Overview

This project aims to analyze and predict stroke occurrence based on various health and lifestyle factors using the Healthcare Stroke Dataset. The dataset includes information about individuals' gender, age, hypertension, heart disease, marital status, work type, residence type, average glucose level, BMI, smoking status, and stroke status.

## Dataset

The dataset used for this project is available in the file `healthcare-dataset-stroke-data.csv`. It contains 5110 rows and 12 columns, capturing details about different individuals.

### Data Cleaning

- The initial exploration revealed missing values in the 'bmi' column, which were handled by dropping the corresponding rows.
- The 'id' column was dropped as it did not contribute to the analysis.

### Exploratory Data Analysis

1. **Categorical Feature Analysis:**
   - Visualized various categorical features using donut charts.
   - Explored the distribution of gender, hypertension, heart disease, marital status, work type, residence type, smoking status, and stroke.

2. **Feature Distribution Analysis:**
   - Created histograms for age and average glucose level to understand their distribution in the dataset.

3. **Box Plots:**
   - Analyzed the distribution of age and average glucose level for stroke and non-stroke cases using box plots.

4. **Correlation Matrix:**
   - Visualized the correlation between numerical features using a heatmap.

### Stroke Prediction Insights

- Explored key insights related to stroke prediction based on gender, hypertension, marital status, work type, residence type, and smoking status.
- Provided observations and statistics related to stroke occurrence in different subgroups.

### Sunburst Charts

- Utilized sunburst charts to visualize relationships between gender, hypertension, marital status, work type, residence type, smoking status, and stroke.

## Requirements

- Python 3.x
- Libraries: pandas, numpy, matplotlib, seaborn, plotly, scikit-learn

## Usage

1. Install the required libraries using the following command:
   ```bash
   pip install pandas numpy matplotlib seaborn plotly scikit-learn
2. Run the script using the command:
   ```bash
   python healthcare_stroke_prediction.py
