# 📊 Task 2: Exploratory Data Analysis (EDA) – Titanic Dataset

This project performs Exploratory Data Analysis (EDA) on the Titanic dataset. The goal is to understand the structure and patterns in the data using statistics and visualizations.

---

## 📁 Dataset

- **File Used**: `Titanic-Dataset.csv`
- **Source**: [Kaggle - Titanic Dataset](https://www.kaggle.com/datasets/yasserh/titanic-dataset)

---

## 🛠 Tools & Libraries

- Python
- Pandas
- Matplotlib
- Seaborn

---

## 🔍 Objectives

- Generate summary statistics
- Visualize data distribution and outliers
- Explore feature relationships and correlations
- Identify meaningful patterns and trends
- Make basic feature-level inferences

---

## 📌 Steps Performed

### 1. 📊 Summary Statistics
- Used `df.describe(include='all')` to display:
  - Count, Mean, Median, Std Dev, Min, Max
  - Frequency for categorical columns

### 2. 📈 Histograms and Boxplots
- Created histograms to visualize data distributions
- Created boxplots to detect **outliers**
- Features analyzed: `Age`, `Fare`, `SibSp`, `Parch`

### 3. 🔗 Correlation Matrix & Heatmap
- Calculated correlations between numeric features
- Visualized using a **Seaborn heatmap**

### 4. 🧩 Pairplot
- Used Seaborn’s `pairplot()` to:
  - Show pairwise relationships between `Survived` and numerical columns
  - Identify separability and trends

### 5. 💡 Feature-level Inferences
- Survival Rate by:
  - `Sex`: Females had higher survival rate
  - `Pclass`: First class passengers more likely to survive
  - `Embarked`: Port of embarkation had impact on survival

---

## 🧠 Sample Insights

- **Sex**: Females had a higher chance of survival.
- **Pclass**: Higher-class passengers had better survival rates.
- **Fare & Age**: Showed skewness and required outlier analysis.
- **Embarked**: Passengers from 'C' (Cherbourg) showed better survival.# task-2
