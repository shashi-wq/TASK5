# Task 5 - Exploratory Data Analysis (Titanic Dataset)

## 🎯 Objective
The goal of this task is to perform **Exploratory Data Analysis (EDA)** on the Titanic dataset.  
EDA helps uncover data quality issues, distributions, correlations, and meaningful patterns that can guide machine learning modeling and business insights.

---

## 🛠️ Tools Used
- **Google Colab / Jupyter Notebook / VS Code** (Python environment)  
- **Python Libraries:**
  - `pandas` → Data loading & cleaning  
  - `matplotlib` → Basic plotting  
  - `seaborn` → Advanced visualization  

---

## 📂 Dataset
- **Name:** Titanic Dataset  
- **Source:** [Kaggle Titanic Challenge](https://www.kaggle.com/c/titanic/data) or public GitHub mirrors  
- **Size:** ~891 rows × 12 columns  
- **Key Columns:**
  - `PassengerId`, `Survived`, `Pclass`, `Name`, `Sex`, `Age`,  
  - `SibSp`, `Parch`, `Ticket`, `Fare`, `Cabin`, `Embarked`

---

## 📊 EDA Process

### 1. Data Understanding
- Loaded dataset and checked shape, column info, missing values.  
- Summary statistics using `.describe()`.  

### 2. Univariate Analysis
- **Categorical Variables** → Countplots for `Sex`, `Pclass`, `Embarked`.  
- **Numerical Variables** → Histograms and boxplots for `Age`, `Fare`.  

### 3. Bivariate Analysis
- Survival by Gender (`Sex` vs `Survived`).  
- Survival by Passenger Class (`Pclass` vs `Survived`).  
- Boxplots of `Age` vs `Survived`.  
- Correlation heatmap of numeric variables.  

### 4. Multivariate Analysis
- Pairplot for `Survived`, `Age`, `Fare`, and `Pclass`.  
- Survival breakdown by multiple factors (e.g., Gender + Class).  

### 5. Data Cleaning
- Filled missing `Age` with median values.  
- Dropped `Cabin` (too many missing).  
- Handled missing `Embarked` values.  

---

## 🔑 Key Insights
- **Gender:** Females had a higher survival rate compared to males.  
- **Passenger Class:** Survival was higher for 1st class passengers, lowest for 3rd class.  
- **Age:** Children and younger passengers had higher survival chances.  
- **Fare:** Higher fare passengers were more likely to survive.  
- **Family Size:** Having 1–2 relatives increased survival chances; too many decreased it.  

---

## 📂 Deliverables
- `task5_EDA.ipynb` → Jupyter/Colab notebook with full analysis.  
- `Titanic-Dataset.csv` → Dataset used.  
- `EDA_Report.pdf` → Exported PDF version of notebook with outputs.  
- `README.md` → Project documentation (this file).  

---

## 🚀 How to Run
1. Clone this repository.  
2. Open `task5_EDA.ipynb` in Google Colab / Jupyter Notebook.  
3. Run all cells to reproduce analysis and plots.  
4. Alternatively, view the exported `EDA_Report.pdf` directly.  

---

## 📌 Summary
This project demonstrates how to use **EDA techniques** to analyze the Titanic dataset.  
Through visualizations and statistical summaries, we gained insights into survival patterns and prepared the data for future machine learning models.
