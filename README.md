# 🚢 Titanic Data Analysis & Visualization

This project explores the famous Titanic dataset to analyze patterns in passenger survival using Python and visualization libraries like Matplotlib and Pandas.

## 📁 Dataset

The dataset used is `Titanic-Dataset.csv`, containing 891 passenger records with details such as:

- `Survived`: 0 = No, 1 = Yes
- `Pclass`: Passenger class (1st, 2nd, 3rd)
- `Sex`, `Age`, `Fare`, `Embarked` (Port of Embarkation), etc.

## 🧹 Data Cleaning

- Removed rows with missing values in the `Age` column.
- Dropped rows with any NaN values to prepare clean visuals.
  
## 📊 Visualizations

### 1. Survival Distribution (Pie Chart)
Shows percentage of passengers who survived vs. those who did not.

### 2. Passenger Class Distribution (Bar Chart)
Displays the number of passengers in each class (1st, 2nd, 3rd).

### 3. Embarkation Port (Column Chart)
Breakdown of passengers by their port of embarkation:
- **S**: Southampton
- **C**: Cherbourg
- **Q**: Queenstown

### 4. Age vs Fare (Scatter Plot)
Visualizes the relationship between passenger age and fare paid.

## 📎 Report

A full PDF report of the analysis and visualizations is available:

📄 [Titanic_Visual_Report.pdf](Titanic_Visual_Report.pdf)

## 🛠️ Tools Used

- Python 🐍
- Pandas
- Matplotlib
- Jupyter Notebook

## 📌 Insights

- Most passengers were in 3rd class.
- Women had a significantly higher survival rate.
- Younger passengers tended to survive more.
- Southampton was the most common embarkation point.

---

