# 🛳️ Titanic Dataset - Exploratory Data Analysis (EDA)

This project explores the famous Titanic dataset using **Python**, **Pandas**, **Seaborn**, and **Matplotlib** to extract insights, visualize patterns, and understand the relationships between different features.

---

## 📁 Dataset Files Used

- `train.csv` – Main dataset containing passenger information and survival status.
- `test.csv` – Passenger data without survival labels (used for model testing, not EDA).
- `gender_submission.csv` – Sample submission file for reference.

---

## 🎯 Objective

The goal of this task is to perform **Exploratory Data Analysis (EDA)** on the Titanic dataset to:

- Understand the structure and summary statistics of the data
- Visualize relationships and trends using plots
- Identify patterns and anomalies
- Generate actionable insights

---

## 🛠️ Tools & Libraries

- Python 3.x
- Pandas
- Seaborn
- Matplotlib

---

## 📊 Steps Followed in EDA

1. **Data Loading & Initial Inspection**
   - Used `.info()`, `.describe()`, `.head()` to understand the dataset structure
   - Checked for missing values and unique value counts

2. **Univariate Analysis**
   - Plotted histograms and countplots for features like `Age`, `Sex`, `Pclass`, `Fare`, `Survived`

3. **Bivariate Analysis**
   - Analyzed survival trends across gender, passenger class, age, and fare
   - Used boxplots and countplots to compare distributions

4. **Correlation Analysis**
   - Generated a heatmap of numeric features
   - Interpreted feature relationships with `Survived`

5. **Observations**
   - Added markdown cells after each visualization to explain key insights

6. **Summary of Findings**
   - Concluded with 6–8 bullet points summarizing the patterns and trends

---

## 📌 Key Insights

- Females had a significantly higher survival rate than males
- 1st class passengers were more likely to survive
- Younger passengers (especially children) had better survival odds
- `Fare` and `Pclass` showed correlation with `Survived`
- Missing values present in `Age`, `Cabin`, and `Embarked` columns

---



