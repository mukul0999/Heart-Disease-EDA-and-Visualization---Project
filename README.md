# Heart Disease EDA and Visualization - Project

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.x-blue?logo=python" alt="Python">
  <img src="https://img.shields.io/badge/Pandas-Data%20Analysis-green" alt="Pandas">
  <img src="https://img.shields.io/badge/Matplotlib-Visualization-orange" alt="Matplotlib">
  <img src="https://img.shields.io/badge/Seaborn-EDA-red" alt="Seaborn">
  <img src="https://img.shields.io/badge/Status-Completed-success" alt="Status">
</p>

<p align="center">
  <b>Exploring Heart Disease Data Through Interactive Visualizations and Statistical Analysis</b>
</p>

---

## Project Overview

This project focuses on **Exploratory Data Analysis (EDA)** and **Data Visualization** of a Heart Disease dataset using Python.

The objective is to transform raw healthcare data into meaningful visual insights by exploring patient demographics, medical measurements, and disease-related factors through charts and statistical analysis.

Instead of building a machine learning model, this project emphasizes **understanding the data through visualization**, helping identify trends, relationships, and patterns associated with heart disease.

---

## Project Objectives

- Perform Exploratory Data Analysis (EDA)
- Clean and preprocess the dataset
- Analyze numerical and categorical variables
- Create informative visualizations
- Discover hidden trends and relationships
- Generate actionable insights using data storytelling

---

## Dataset Information

The dataset contains patient information related to heart disease.

| Feature | Description |
|----------|-------------|
| Age | Age of the patient |
| Sex | Gender |
| ChestPainType | Chest pain category |
| RestingBP | Resting Blood Pressure |
| Cholesterol | Serum Cholesterol |
| FastingBS | Fasting Blood Sugar |
| RestingECG | Resting ECG Result |
| MaxHR | Maximum Heart Rate |
| ExerciseAngina | Exercise-Induced Angina |
| Oldpeak | ST Depression |
| ST_Slope | ST Segment Slope |
| HeartDisease | Heart Disease Status |

---

## Technologies Used

- Python
- Google Colab
- Pandas
- NumPy
- Matplotlib
- Seaborn

---

## Exploratory Data Analysis Workflow

- Import Dataset
- Data Inspection
- Missing Value Analysis
- Duplicate Value Check
- Data Cleaning
- Statistical Summary
- Univariate Analysis
- Bivariate Analysis
- Correlation Analysis
- Data Visualization
- Insight Generation

---

## Visualizations Included

### Distribution Analysis

- Age Distribution
- Cholesterol Distribution
- Resting Blood Pressure Distribution
- Maximum Heart Rate Distribution

### Categorical Analysis

- Heart Disease Distribution
- Gender Distribution
- Chest Pain Type Distribution
- Exercise Angina Distribution
- ST Slope Distribution

### Comparative Analysis

- Age vs Heart Disease
- Cholesterol vs Heart Disease
- Maximum Heart Rate vs Heart Disease
- Oldpeak vs Heart Disease

### Outlier Detection

- Box Plots
- Violin Plots

### Relationship Analysis

- Scatter Plots
- Correlation Heatmap

---

## Correlation Analysis

Pearson Correlation was used to understand the relationship among numerical variables.

```python
correlation_matrix = df.corr()
```

### Correlation with Heart Disease

| Feature | Correlation |
|----------|------------:|
| Oldpeak | **0.404** |
| MaxHR | **-0.400** |
| Age | **0.282** |
| FastingBS | **0.267** |
| Cholesterol | **-0.233** |
| RestingBP | **0.108** |

---

## Key Insights

- Older patients have a higher likelihood of heart disease.
- Patients with higher **Oldpeak** values are more likely to have heart disease.
- Lower **Maximum Heart Rate (MaxHR)** is associated with heart disease.
- Exercise-induced angina is a strong indicator of heart disease.
- Cholesterol alone is not a strong predictor in this dataset.
- Visualizations help uncover hidden relationships between patient characteristics and heart disease.

---

## Visualization Gallery

> Save your charts inside a folder named **screenshots** and replace the image names below with your own.

### Correlation Heatmap

```markdown
![Correlation Heatmap](<img width="606" height="498" alt="correlation" src="https://github.com/user-attachments/assets/4b67c658-92f1-4b4c-bf25-8bee668fe3c7" />
)
```

### Age Distribution

```markdown
![Age Distribution](screenshots/age_distribution.png)
```

### Heart Disease Distribution


<img width="2000" height="2830" alt="image" src="https://github.com/user-attachments/assets/759999e2-b752-49b3-a925-a07bb40ad893" />


### Violin Plot

```markdown
![Violin Plot](screenshots/violin_plot.png)
```

---

## Project Structure

```text
Heart-Disease-EDA/
│
├── README.md
├── Heart_Disease_EDA.ipynb
├── heart.csv
├── requirements.txt
└── screenshots/
    ├── age_distribution.png
    ├── cholesterol_distribution.png
    ├── heart_disease_distribution.png
    ├── violin_plot.png
    └── correlation_heatmap.png
```

---

## Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/Heart-Disease-EDA.git
```

### 2. Navigate to the Project Directory

```bash
cd Heart-Disease-EDA
```

### 3. Install Dependencies

```bash
pip install pandas numpy matplotlib seaborn
```

### 4. Launch Jupyter Notebook

```bash
jupyter notebook
```

Open:

```text
Heart_Disease_EDA.ipynb
```

Run all cells to reproduce the complete analysis and visualizations.

---

## Python Libraries

```python
import pandas as pd
import numpy as np
import matplotlib.pyplot as plt
import seaborn as sns
```

---

## Skills Demonstrated

- Exploratory Data Analysis (EDA)
- Data Cleaning
- Statistical Analysis
- Data Visualization
- Correlation Analysis
- Healthcare Data Analytics
- Storytelling with Data

---

## Future Enhancements

- Interactive Power BI Dashboard
- Tableau Dashboard
- Streamlit Web Application
- Machine Learning Prediction Model
- Interactive Visual Analytics

---

## Author

**Mukul Sharma**

**Aspiring Data Analyst**

### Skills

- Python
- SQL
- Excel
- Power BI
- Pandas
- NumPy
- Matplotlib
- Seaborn

---

## Support

If you found this project useful, please consider giving it a **Star** on GitHub.

Your support motivates me to build and share more data analytics projects.
