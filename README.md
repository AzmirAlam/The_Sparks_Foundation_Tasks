<div align="center">

# The Sparks Foundation Tasks

### Data Science and Business Analytics Projects

A structured collection of machine-learning and data-analysis tasks completed as part of **The Sparks Foundation** programme.

![R](https://img.shields.io/badge/R-Data%20Analysis-276DC3?logo=r)
![Python](https://img.shields.io/badge/Python-Data%20Science-3776AB?logo=python&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-F37626?logo=jupyter&logoColor=white)

</div>

## Project overview

| Task | Project | Method | Technology | Status |
|:---:|---|---|---|:---:|
| 1 | [Student Score Prediction](./task-01-supervised-learning/) | Simple linear regression | R, R Markdown | Completed |
| 2 | [Iris Clustering](./task-02-unsupervised-learning/) | K-means clustering | R, factoextra | Completed |
| 3 | [Retail Data Analysis](./task-03-retail-eda/) | Exploratory data analysis | Python, Jupyter | Completed |

## Repository structure

```text
The_Sparks_Foundation_Tasks/
├── README.md
├── .gitignore
├── sparks-foundation-tasks.Rproj
├── task-01-supervised-learning/
│   ├── README.md
│   ├── student-score-prediction.Rmd
│   └── data/
│       └── student_scores.csv
├── task-02-unsupervised-learning/
│   ├── README.md
│   ├── iris-clustering.Rmd
│   └── data/
│       └── iris.csv
└── task-03-retail-eda/
    ├── README.md
    ├── retail-eda.ipynb
    └── data/
        └── sample_superstore.csv
```

Each task keeps its analysis, data and documentation together. Generated editor files, session history and notebook checkpoints are excluded from version control.

## Getting started

### Clone the repository

```bash
git clone https://github.com/AzmirAlam/The_Sparks_Foundation_Tasks.git
cd The_Sparks_Foundation_Tasks
```

### Install the R packages

```r
install.packages(c("readr", "ggplot2", "caTools", "factoextra", "cluster"))
```

Open `sparks-foundation-tasks.Rproj` in RStudio, then open the relevant task file. The data paths are relative to each task directory.

Task 3 can be opened with Jupyter Notebook or JupyterLab.

## Skills demonstrated

- Data importing, cleaning and validation
- Exploratory and statistical analysis
- Data visualisation
- Linear regression and model evaluation
- K-means clustering
- Reproducible analytical reporting

## Author

**Md. Azmir Alam** — [GitHub profile](https://github.com/AzmirAlam)

## Acknowledgements

Thank you to [The Sparks Foundation](https://www.thesparksfoundationsingapore.org/) for providing the project tasks and learning opportunity.
