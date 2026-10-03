# 🚢 Titanic Dataset - Exploratory Data Analysis (EDA)

An end-to-end Exploratory Data Analysis (EDA) project on the famous Titanic dataset using Python, Pandas, Matplotlib, and Seaborn. This project explores key patterns, demographic factors, and socio-economic variables affecting passenger survival.

---

## 📌 Project Overview
The objective of this project is to clean, analyze, and visualize passenger data to uncover key insights, such as:
- Impact of passenger class (Pclass) and ticket fare on survival.
- Survival trends across genders and different age groups (Child, Adult, Old).
- Data distributions and relationships among key demographic attributes.

---

## 🛠️ Tech Stack & Libraries
- **Language:** Python
- **Data Manipulation:** `pandas`, `numpy`
- **Data Visualization:** `matplotlib.pyplot`, `seaborn`
- **Environment:** Jupyter Notebook

---

## 🔄 Workflow & Analysis Steps

### 1. Data Understanding & Inspection
- Inspected dataset shape (`891 rows, 12 columns`) and column data types.
- Checked statistical summaries (`df.describe()`) and overall structure (`df.info()`).

### 2. Data Cleaning & Preprocessing
- **Missing Values Handling:**
  - Dropped the `Cabin` column due to high missing values.
  - Imputed missing values in `Age` using the mean.
  - Imputed missing values in `Embarked` using the mode.
- Inspected numeric columns for outliers.

### 3. Feature Engineering & Binning
- Grouped passengers into custom age buckets using `pd.cut()`:
  - **Child:** 0–18 years
  - **Adult:** 18–40 years
  - **Old:** 40–70+ years

### 4. Dashboard & Visualizations
Created a multi-panel visualization dashboard covering:
1. **Survival Rate by Age Group:** Comparison of survival rates across age categories.
2. **Survival Rate by Gender:** Pie chart highlighting female vs. male survival distribution.
3. **Survival Rate by Pclass:** Horizontal bar chart showing survival probability across classes.
4. **Passenger Count by Pclass:** Line plot illustrating the volume of passengers in 1st, 2nd, and 3rd class.
5. **Age vs. Fare (Survival):** Scatter plot analyzing the combined impact of age, ticket fare, and survival status.
6. **Age Distribution:** Histogram with KDE showing passenger age spread.

---

## 💡 Key Insights
- **Gender Disparity:** Female passengers had a significantly higher survival rate (~79%) compared to male passengers (~20%).
- **Socio-Economic Class:** Passengers traveling in 1st class had a much higher likelihood of survival compared to those in 3rd class.
- **Age Factor:** Children showed higher survival rates compared to older age groups, aligning with the "women and children first" protocol.

---

## 🚀 How to Run the Project
:- Clone this repository:
   ```bash
   git clone [https://github.com/shivayadavsgcs-ship-it/PYTHON-REPORTS.git](https://github.com/shivayadavsgcs-ship-it/PYTHON-REPORTS.git)

   ---

2.# 📊 Job Market Dataset - Exploratory Data Analysis (EDA)

An end-to-end Exploratory Data Analysis project analyzing modern tech hiring trends, role distributions, and salary compensation benchmarks using Python.

## 🎯 Project Overview
The objective of this analysis is to evaluate tech hiring patterns and provide compensation insights:
- Benchmarking top paying roles based on maximum average salary.
- Evaluating active hiring volume and demand across tech categories.
- Proportional distribution of technical domains using distribution charts.
- Salary trends across leading tech firms.
- Highlighting peak in-demand job profiles.

## 🛠 Tech Stack & Libraries
- **Language:** Python
- **Data Manipulation:** `pandas`, `numpy`
- **Data Visualization:** `matplotlib.pyplot`, `seaborn`
- **Environment:** Jupyter Notebook

## 📊 Dashboard & Visualizations
Created a multi-panel visual dashboard covering:
1. Top Job Titles by Average Max Salary:** Bar plot highlighting highest paying roles.
2. Job Openings by Category:** Horizontal bar chart evaluating category-wise job counts.
3. Job Category Distribution:** Pie chart showcasing proportional domain distribution.
4. Top Companies by Average Max Salary:** Line plot tracking compensation benchmarks across companies.
5. Top Job Category by Avg Max Salary:** Seaborn bar plot showing domain-level salary trends.
6. Top 5 In-Demand Job Titles:** Horizontal bar plot of roles with peak hiring frequency.

## 💡 Key Insights
- High Compensation Profiles:** Machine Learning and Data Science roles command the highest salary tiers.
- Hiring Volume:** Data and Software domains represent the largest share of active job openings.
- Top Employers:** Leading multinational firms and tech giants offer premium compensation packages across technical positions.
