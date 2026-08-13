# Sleep, Academic Pressure and Depression Among Students

## Authors

- Sapir Hai
- Lea Sayada

## Project Overview

This project investigates the relationship between sleep duration, academic pressure, and depression among university students using the Student Depression Dataset.

The main objective of the study was to determine whether sleep duration moderates the relationship between academic pressure and depression.

The project was completed as part of the **Statistical Theory** course at **Bar-Ilan University**.

---

## Dataset

Source:
https://www.kaggle.com/datasets/hopesb/student-depression-dataset

The original dataset contains information from more than **140,000 students**.

After data preprocessing and cleaning, the final analytical sample consisted of **27,901 students**.

The variables used in this project include:

- Sleep Duration
- Academic Pressure
- Depression Status

---

## Statistical Methods

The following statistical methods were used:

- Chi-Square Test of Independence
- Mann–Whitney U Test
- Logistic Regression
- Interaction Analysis
- Bootstrap Confidence Intervals

---

## Main Findings

The analysis showed that:

- Sleep duration is significantly associated with depression.
- Students with depression reported significantly higher academic pressure.
- Academic pressure is a strong predictor of depression.
- Sleeping more than eight hours was associated with lower odds of depression.
- No statistically significant interaction was found between sleep duration and academic pressure.

---

## Repository Contents

```
Student-Depression-Analysis/
│
├── Student_Depression_Analysis.ipynb
├── Statistic.pdf
├── student_depression.csv
├── figure1.png
├── figure2.png
├── figure4.png
├── requirements.txt
└── README.md
```

---

## Installation

Install the required Python packages:

```bash
pip install -r requirements.txt
```

---

## Running the Project

1. Download the repository.
2. Install the required packages.
3. Open the Jupyter Notebook:

```bash
jupyter notebook Student_Depression_Analysis.ipynb
```

4. Run all notebook cells to reproduce the complete statistical analysis and generate the figures.

---

## Libraries Used

- pandas
- numpy
- scipy
- statsmodels
- matplotlib
- jupyter

---

## Report

The final report is provided in:

```
Statistic.pdf
```

The report follows the IEEE conference paper format and summarizes the complete statistical analysis.
