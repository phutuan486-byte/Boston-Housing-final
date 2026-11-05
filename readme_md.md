# Boston Housing Data Analysis & Hypothesis Testing

This project performs an exploratory data analysis (EDA) and statistical hypothesis testing on the **Boston Housing Dataset** as part of the IBM Data Science / Statistics course requirements.

---

## 📌 Project Overview

The objective of this project is to analyze various factors influencing median home values in the Boston area during the 1970s. The analysis includes:

1. **Exploratory Data Analysis (EDA):** Visualizing distributions, relationships, and categorical groupings using `seaborn` and `matplotlib`.
2. **Hypothesis Testing:**
   - **T-test:** Evaluating differences in median home values (`MEDV`) based on proximity to the Charles River (`CHAS`).
   - **ANOVA:** Assessing variance in home values (`MEDV`) across discretized age groups (`AGE`).
   - **Pearson Correlation:** Testing the relationship between Nitric Oxide concentrations (`NOX`) and weighted distances to employment centers (`DIS`).

---

## 📊 Dataset Information

The dataset is loaded directly from IBM's public storage link:
- **Source:** Boston Housing Dataset (`boston_housing.csv`)
- **Key Variables:**
  - `MEDV`: Median value of owner-occupied homes in $1000's
  - `CHAS`: Charles River dummy variable (1 if tract bounds river; 0 otherwise)
  - `AGE`: Proportion of owner-occupied units built prior to 1940
  - `INDUS`: Proportion of non-retail business acres per town
  - `NOX`: Nitric oxides concentration (parts per 10 million)
  - `PTRATIO`: Pupil-teacher ratio by town
  - `DIS`: Weighted distances to five Boston employment centers

---

## 📁 Repository Contents

| File | Description |
| :--- | :--- |
| `Boston_Housing_Final_Project.ipynb` | Complete Jupyter Notebook containing all Python code, visualizations, and statistical tests. |
| `README.md` | Overview and documentation for the repository. |

---

## 🚀 How to Run

### Requirements
Ensure you have Python installed along with the following libraries:
```bash
pip install pandas seaborn matplotlib scipy statsmodels
```

### Execution
1. Clone this repository:
   ```bash
   git clone https://github.com/YOUR-USERNAME/boston-housing-final-project.git
   cd boston-housing-final-project
   ```
2. Open Jupyter Notebook or JupyterLab:
   ```bash
   jupyter notebook Boston_Housing_Final_Project.ipynb
   ```
3. Run all cells to execute data loading, visualizations, and statistical testing.

---

## 📈 Key Visualizations & Tests Included

1. **Boxplot of MEDV:** Outlier detection and distribution of median home values.
2. **Count Plot of CHAS:** Proportion of homes bounded by the Charles River.
3. **Discretized AGE vs MEDV:** Boxplots categorizing units into three age groups (≤35, 35–70, ≥70 years).
4. **Scatter Plot of INDUS vs NOX:** Correlation between industrial land use and air pollution.
5. **Histogram of PTRATIO:** Frequency distribution of pupil-teacher ratios.