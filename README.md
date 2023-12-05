# Week 2: Resampling Methods

## Objective
This assignment reviews the basic concepts of **resampling methods** for model selection and regularization. It includes both conceptual questions and applied exercises in Python.

Topics covered:
- Bootstrap sampling and probabilities
- k-Fold Cross-Validation (implementation, bias-variance tradeoff, comparison to validation set and LOOCV)
- Polynomial regression with cross-validation
- Bootstrap confidence intervals for parameter estimates
- Ridge and Lasso regression with cross-validation

---

## Repository Structure
```

resampling-methods-assignment/
│── README.md
│── requirements.txt
│── .gitignore
│── Week2_Resampling_Methods.ipynb
└── Dataset/
└── data.csv

```

---

## Dataset
The assignment uses a **public dataset of U.S. colleges**, saved here as `Dataset/data.csv`.  
A sample of the columns is shown below:

| private | apps | accept | enroll | top10perc | top25perc | f_undergrad | p_undergrad | outstate | room_board | books | personal | phd | terminal | s_f_ratio | perc_alumni | expend | grad_rate |
|---------|------|--------|--------|-----------|-----------|-------------|-------------|----------|------------|-------|----------|-----|----------|-----------|-------------|--------|-----------|
| Yes     | 1660 | 1232   | 721    | 23        | 52        | 2885        | 537         | 7440     | 3300       | 450   | 2200     | 70  | 78       | 18.1      | 12          | 7041   | 60        |
| Yes     | 2186 | 1924   | 512    | 16        | 29        | 2683        | 1227        | 12280    | 6450       | 750   | 1500     | 29  | 30       | 12.2      | 16          | 10527  | 56        |
| Yes     | 1428 | 1097   | 336    | 22        | 50        | 1036        | 99          | 11250    | 3750       | 400   | 1165     | 53  | 66       | 12.9      | 30          | 8735   | 54        |

---

## Setup Instructions
Use the shared virtual environment `~/venvs/ml-env` across assignments.

```bash
# Navigate to repo
cd ~/projects/resampling-methods-assignment

# Activate shared environment
source ~/venvs/ml-env/bin/activate

# Install dependencies
pip install -r requirements.txt
```

---

## References

* James, Witten, Hastie, Tibshirani (2021). *An Introduction to Statistical Learning with Applications in Python*.
* Scikit-learn documentation: [https://scikit-learn.org/](https://scikit-learn.org/)
* Statsmodels documentation: [https://www.statsmodels.org/](https://www.statsmodels.org/)


---

