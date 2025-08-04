#  Titanic EDA – Coding Samurai Internship Project

This project is an in-depth Exploratory Data Analysis (EDA) on the Titanic dataset using Python, done as part of my Data Science internship at Coding Samurai.

## Objectives
- Clean and preprocess raw data
- Visualize relationships between variables and survival
- Perform feature engineering
- Draw insights using graphs and summary statistics

## Tools Used
- Python (pandas, numpy)
- seaborn, matplotlib
- Jupyter Notebook

## Key Insights
- Females and 1st class passengers were more likely to survive
- Children had higher survival rates
- Passengers with family had better odds than those alone
- Cherbourg (C) boarders survived more often than Southampton (S)

## Feature Engineering
- `FamilySize` = SibSp + Parch + 1
- `IsAlone` = 1 if FamilySize == 1
- `Title` = extracted from Name (Mr, Miss, etc.)

## Visualizations
- Survival counts by gender, class, age
- Violin plots, histograms, countplots
- Correlation heatmap

## Author
- Utsav Thapaliya
- Data Science Intern at Coding Samurai
