# Employee Turnover Prediction
This project predicts which employees are most likely to leave and identifies the key drivers of turnover, helping companies take proactive retention measures.

## Introduction
Using HR data from Portobello Tech, the notebook explores employee characteristics, uncovers factors influencing retention, and applies machine learning models to predict turnover risk. It combines **exploratory data analysis (EDA), clustering, class imbalance handling, and model evaluation** to generate actionable insights for HR decision-making.

## Project Structure

#### `Employee_Turnover_Prediction.ipynb`  
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/<INSERT_NOTEBOOK_ID_HERE>)

[View on GitHub](https://github.com/angelatyk/<REPO_NAME>/blob/main/notebooks/Employee_Turnover_Prediction.ipynb)

Key highlights:  

- Explored and visualized HR dataset to identify turnover patterns.
- Clustered employees who left using **K-Means** to detect distinct risk groups.  
- Balanced classes with **SMOTE** to strengthen model performance.  
- Built and compared **Logistic Regression, Random Forest, and Gradient Boosting** models with 5-fold cross-validation. 
- Predicted employee turnover probabilities and categorized employees into **risk zones** (Safe, Low, Medium, High) for actionable retention strategies.

**Tech:** Python, Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn, imbalanced-learn

## Dataset
- **HR Dataset** – Includes features such as satisfaction level, last evaluation, number of projects, monthly hours, years at company, promotion history, salary, department, and turnover label.
    - Source: [Link to dataset](https://github.com/angelatyk/bikeease-analytics-series/blob/main/data/04_nlp_sentiment_analysis/bike_rental_reviews.csv)  

## Author
[@angelatyk](https://www.github.com/angelatyk)