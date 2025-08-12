# ElevateLabs_Internship_Task-5
Extract insights using visual and statistical exploration.
# Titanic EDA (Task 5 - Data Analyst Internship)

## Description
Exploratory data analysis of the Titanic dataset. Notebook explores distributions, missingness, relationships, and produces insights.

## Files
- Elevate Labs_Task 5.ipynb : Jupyter notebook with code and plots
- README.md

## 📂 Dataset Information
- **Training Data (`train.csv`)**  
  Contains 891 passenger records with the following columns:  
  `PassengerId`, `Survived`, `Pclass`, `Name`, `Sex`, `Age`, `SibSp`, `Parch`, `Ticket`, `Fare`, `Cabin`, `Embarked`.
  
- **Target Variable:** `Survived` (1 = survived, 0 = did not survive)

- **Test Data (`test.csv`)**  
  Contains 418 passenger records without the `Survived` column (used for predictions).

- **Gender Submission (`gender_submission.csv`)**  
  Sample submission format with `PassengerId` and `Survived`.

  ---

## 🛠️ Steps Performed
1. **Data Loading**  
   Imported the datasets (`train.csv`, `test.csv`, and `gender_submission.csv`) using Pandas.

2. **Initial Exploration**  
   - Viewed the first few rows of each dataset.  
   - Checked dataset structure (`info()`) and statistical summary (`describe()`).

3. **Data Cleaning**  
   - Detected and handled missing values in `Age`, `Cabin`, and `Embarked`.  
   - Converted categorical variables (`Sex`, `Embarked`) to numeric codes.  
   - Created new features for analysis.

4. **Exploratory Data Analysis (EDA)**  
   - Visualized survival rate by **Sex**, **Pclass**, and **Embarked**.  
   - Analyzed the impact of **Age**, **Fare**, **Family Size** on survival.  
   - Generated correlation heatmaps to understand relationships between numerical variables.

5. **Feature Engineering**  
   - Derived new variables like `FamilySize` and `IsAlone`.  
   - Grouped passenger titles from the `Name` column to capture social status.

---

## 📊 Key Insights
- **Gender:** Females had a significantly higher survival rate than males.
- **Class:** First-class passengers were more likely to survive compared to lower classes.
- **Age:** Children had a higher survival rate than adults.
- **Fare:** Higher fares correlated with higher survival probability.
- **Embarked:** Passengers embarking from certain ports had higher survival rates.

---

## 🖥️ Technologies Used
- **Python**  
- **Pandas** – Data manipulation  
- **NumPy** – Numerical operations  
- **Matplotlib & Seaborn** – Data visualization

---

