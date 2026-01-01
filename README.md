# Titanic-Data-Analysis-with-Predictions

## Summary 
A full data science workflow on the Titanic dataset. We cleaned data, built plots for complex analysis, and engineered features to train a machine learning model that predicts passenger survival with high accuracy.

## 📊 Dashboard

![Titanic Dashboard](outputs/dashboard.png)

## 📊 Dashboard features:

- KPI overview (survival rate, death rate, average age, fare analysis)
- Survival breakdown by class, gender, age group, fare bin, family group, and embarkation port
- Deep-dive comparison tables for detailed pattern analysis
- Fully interactive filters to support exploratory analysis


## 📁 Dataset Columns

- `PassengerId:` Unique identifier for each passenger
- `Survived:` Survival status (0 = Died, 1 = Survived)
- `Name:` Passenger name
- `Sex:` Gender of the passenger
- `Pclass:` Passenger class (1st, 2nd, 3rd)
- `Fare:` Ticket fare
- `Embarked:` Port of embarkation (C, Q, S)
- `Ticket:` Ticket number
- `SibSp:` Number of siblings/spouses aboard
- `Parch:` Number of parents/children aboard

## 🛠️ Feature Engineering

The following new features were created to enhance the analysis:

- `AgeGroup:` Categorized age ranges (Child, Adult, Senior, etc.)
- `FareGroup:` Fare categories (Low, Medium, High)
- `FamilySize:` Total family members aboard (SibSp + Parch + 1)
- `FamilyGroup:` Family size classification (Alone, Small, Large)
- `Status:` status based on survival outcome

## 🔍 Key insights from the analysis:

- Gender and passenger class were the strongest predictors of survival
- Female passengers especially those in 1st and 2nd class—had survival rates exceeding 90%.
- 3rd class males experienced the lowest survival rates by 9.53%.
- Fare level showed a strong correlation with survival.
- Passengers who paid higher fares generally had significantly better outcomes.
- Passengers traveling in small to medium-sized families had higher survival rates by 53.4% compared to those traveling alone or in large families.


## 🛠 Tools & Skills Applied:


- Data cleaning and transformation
- Exploratory Data Analysis (EDA)
- Data storytelling and dashboard design
- Translating historical data into business-focused insights
