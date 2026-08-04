<div align="center">

# The Sparks Foundation Tasks

### Data Science and Business Analytics Projects

A collection of machine-learning and data-analysis tasks completed as part of **The Sparks Foundation** programme.

![R](https://img.shields.io/badge/R-Data%20Analysis-276DC3?logo=r)
![Python](https://img.shields.io/badge/Python-Data%20Science-3776AB?logo=python&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-F37626?logo=jupyter&logoColor=white)
![Machine Learning](https://img.shields.io/badge/Machine%20Learning-Projects-green)

</div>

---

## Table of Contents

- [About the Repository](#about-the-repository)
- [Project Overview](#project-overview)
- [Task 1: Student Score Prediction](#task-1-student-score-prediction)
- [Task 2: Iris Clustering](#task-2-iris-clustering)
- [Task 3: Retail Data Analysis](#task-3-retail-data-analysis)
- [Technologies](#technologies)
- [Repository Structure](#repository-structure)
- [Getting Started](#getting-started)
- [Skills Demonstrated](#skills-demonstrated)
- [Author](#author)
- [Acknowledgements](#acknowledgements)

---

## About the Repository

This repository contains practical data-science projects covering:

- Exploratory data analysis
- Statistical analysis
- Data visualisation
- Supervised machine learning
- Unsupervised machine learning
- Business-focused data analysis

The projects use **R, Python, R Markdown and Jupyter Notebook**.

---

## Project Overview

| Task | Project | Method | Technology | Status |
|:---:|---|---|---|:---:|
| 1 | Student Score Prediction | Simple linear regression | R, R Markdown | ✅ Completed |
| 2 | Iris Clustering | K-means clustering | R, factoextra | ✅ Completed |
| 3 | Retail Data Analysis | Exploratory data analysis | Python, Jupyter | 🚧 In progress |

---

## Task 1: Student Score Prediction

### Objective

Build a supervised machine-learning model that predicts a student’s examination score based on the number of hours studied.

### Dataset

The dataset contains two variables:

| Variable | Description |
|---|---|
| `Hours` | Number of hours studied |
| `Scores` | Examination score achieved |

### Analysis Steps

1. Import and inspect the dataset.
2. Calculate descriptive statistics.
3. Visualise the relationship between hours and scores.
4. Examine the correlation between the variables.
5. Split the observations into training and testing sets.
6. Train a simple linear regression model.
7. Examine the model residuals.
8. Compare predicted and actual scores.
9. Generate a prediction for a selected number of study hours.

### Methods and Tools

- Simple linear regression
- Train-test split
- Correlation analysis
- Residual analysis
- R
- `readr`
- `ggplot2`
- `caTools`

### Project Files

- [Task 1 R Markdown file](./Task_1/task1.Rmd)
- [Student scores dataset](./Task_1/student_scores%20-%20student_scores.csv)

---

## Task 2: Iris Clustering

### Objective

Use unsupervised machine learning to determine the optimum number of clusters in the Iris dataset and visualise the resulting groups.

### Dataset

The analysis uses four numerical flower measurements:

| Variable | Description |
|---|---|
| `Sepal.Length` | Sepal length |
| `Sepal.Width` | Sepal width |
| `Petal.Length` | Petal length |
| `Petal.Width` | Petal width |

### Analysis Steps

1. Load and inspect the Iris dataset.
2. Check for missing observations.
3. Standardise the numerical variables.
4. use the within-cluster sum of squares method.
5. Select the optimum number of clusters.
6. Apply K-means clustering.
7. Visualise the final clusters.

### Methods and Tools

- Data standardisation
- Elbow method
- K-means clustering
- Cluster visualisation
- R
- `factoextra`
- `cluster`

### Project Files

- [Task 2 R Markdown file](./Task_2/Task_2.Rmd)
- [Iris dataset](./Task_2/Iris.csv)

---

## Task 3: Retail Data Analysis

### Objective

Perform exploratory data analysis on the Sample Superstore dataset to identify business problems, performance patterns and potential improvement opportunities.

### Planned Analysis

1. Clean and validate the dataset.
2. Examine overall sales and profitability.
3. Compare product categories and subcategories.
4. Analyse regional performance.
5. Investigate customer segments.
6. Identify loss-making products and markets.
7. Create business-focused visualisations.
8. Present actionable recommendations.

### Planned Tools

- Python
- pandas
- Matplotlib
- Seaborn
- Jupyter Notebook

### Project Files

- [Task 3 notebook](./Task_3/Untitled.ipynb)
- [Sample Superstore dataset](./Task_3/SampleSuperstore.csv)

> **Project status:** The dataset and starter notebook are available. The complete analysis is still in development.

---

## Technologies

| Category | Technologies |
|---|---|
| Programming | R, Python |
| Development | RStudio, Jupyter Notebook |
| Data manipulation | `readr`, pandas |
| Visualisation | `ggplot2`, Matplotlib, Seaborn |
| Machine learning | Linear regression, K-means clustering |
| Reporting | R Markdown |

---

## Repository Structure

```text
The_Sparks_Foundation_Tasks/
│
├── Task_1/
│   ├── task1.Rmd
│   └── student_scores - student_scores.csv
│
├── Task_2/
│   ├── Task_2.Rmd
│   └── Iris.csv
│
├── Task_3/
│   ├── Untitled.ipynb
│   └── SampleSuperstore.csv
│
├── internR.Rproj
├── renv.lock
└── README.md
```

---

## Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/AzmirAlam/The_Sparks_Foundation_Tasks.git
cd The_Sparks_Foundation_Tasks
```

### 2. Install the R Packages

Open R or RStudio and run:

```r
install.packages(c(
  "readr",
  "ggplot2",
  "caTools",
  "factoextra",
  "cluster"
))
```

### 3. Run the Projects

- Open `internR.Rproj` in RStudio.
- Select the required task folder.
- Open the corresponding `.Rmd` file.
- Run the code sections or knit the document to HTML.

For Task 3, open the notebook using Jupyter Notebook or JupyterLab.

---

## Skills Demonstrated

- Data importing and validation
- Data cleaning and preparation
- Exploratory data analysis
- Statistical summaries
- Data visualisation
- Linear regression
- Model evaluation
- K-means clustering
- Business insight generation
- Reproducible analytical reporting

---

## Author

### Md. Azmir Alam

[![GitHub](https://img.shields.io/badge/GitHub-AzmirAlam-181717?logo=github)](https://github.com/AzmirAlam)

---

## Acknowledgements

Thank you to [The Sparks Foundation](https://www.thesparksfoundationsingapore.org/) for providing the project tasks and learning opportunity.

---

<div align="center">

If you found this repository useful, consider giving it a ⭐.

</div>
