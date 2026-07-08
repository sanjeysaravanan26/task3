Titanic Exploratory Data Analysis (EDA)

A comprehensive Exploratory Data Analysis (EDA) project on the famous Titanic dataset using Python. This project demonstrates how data cleaning, feature engineering, and visualization techniques can be used to discover meaningful insights from real-world data.

---

 Project Overview

The objective of this project is to perform an in-depth analysis of the Titanic dataset by:

- Cleaning and preprocessing the data
- Handling missing values
- Creating new features
- Performing statistical analysis
- Building insightful visualizations
- Understanding factors affecting passenger survival

This project was completed as part of the **Data Science with Python Internship - Task 3**.

---

 Objectives

- Clean the dataset
- Handle missing values using imputation
- Remove unnecessary columns
- Analyze passenger survival patterns
- Visualize important relationships in the data
- Gain practical experience in Exploratory Data Analysis (EDA)

---

 Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

---

 Dataset

Dataset Used:
- Titanic Dataset

Dataset contains information such as:

- Passenger Age
- Gender
- Passenger Class
- Fare
- Embarked Port
- Family Members
- Survival Status

---

 Data Preprocessing

The dataset was cleaned by:

- Filling missing Age values using Mean Imputation
- Removing the Cabin column due to excessive missing values
- Creating Age Groups
- Creating a Family Size feature using:

```
FamilySize = SibSp + Parch
```

---

 Exploratory Data Analysis

The following analyses were performed:

Survival Rate by Age Group

Passengers were categorized into:

- Child
- Teen
- Young Adult
- Adult
- Senior

The survival rate for each age group was visualized using a bar chart.

---

Survival Rate by Embarkation Port

Analyzed passenger survival based on:

- Cherbourg (C)
- Queenstown (Q)
- Southampton (S)

---

 Survival Rate by Family Size

Created a new feature:

```
FamilySize = SibSp + Parch
```

Analyzed how family size influenced survival probability.

---

 Visualizations

The project includes:

-  Age Distribution Histogram
-  Correlation Heatmap
-  Survival by Age Group
-  Survival by Family Size
-  Survival by Embarkation Port

---

 Key Insights

- Missing values can significantly impact model performance if not handled properly.
- Passenger age has an influence on survival probability.
- Family size affects survival chances.
- Embarkation port shows varying survival rates.
- Data visualization helps uncover hidden trends effectively.

---

 Project Structure

```
Titanic-EDA/
│
├── Titanic_EDA.ipynb
├── titanic.csv
├── README.md
└── images/
```

---

 How to Run

1. Clone the repository

```bash
git clone https://github.com/yourusername/Titanic-EDA.git
```

2. Navigate to the project folder

```bash
cd Titanic-EDA
```

3. Install dependencies

```bash
pip install pandas numpy matplotlib seaborn
```

4. Launch Jupyter Notebook

```bash
jupyter notebook
```

5. Open

```
Titanic_EDA.ipynb
```

---

 Learning Outcomes

This project helped strengthen skills in:

- Data Cleaning
- Feature Engineering
- Data Visualization
- Exploratory Data Analysis (EDA)
- Python for Data Science
- Pandas Data Manipulation
- Statistical Analysis

---

 Future Improvements

- Build Machine Learning models for prediction
- Hyperparameter tuning
- Feature selection
- Interactive visualizations using Plotly
- Dashboard using Streamlit

---


 License

This project is intended for educational and learning purposes.
