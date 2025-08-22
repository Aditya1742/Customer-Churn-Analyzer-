# Customer Churn Analysis Using Machine Learning

## Project Overview
This project analyzes customer churn in the telecom industry using machine learning models. Customer churn refers to customers leaving or discontinuing service, which significantly impacts business revenue. The goal is to predict churn using telecom customer data, enabling companies to take proactive retention measures.

## Dataset
- **Source:** Telco Customer Churn Dataset (CSV format)
- **Records:** 7,043 customers
- **Features:** 21 including demographic information, subscription details, account info, and service usage
- **Target Variable:** `Churn` (Yes/No)

## Project Workflow
1. **Data Loading and Exploration:**  
   Loaded and examined the dataset to understand feature characteristics and target distribution.

2. **Data Preprocessing:**  
   - Cleaned and handled missing data.  
   - Encoded categorical variables using Label Encoding.  
   - Addressed class imbalance via SMOTE (Synthetic Minority Over-sampling Technique).

3. **Exploratory Data Analysis (EDA):**  
   Visualized key feature relationships, churn distributions, and important customer segments.

4. **Model Building:**  
   Developed and compared multiple classification models:  
   - Logistic Regression  
   - Decision Tree  
   - Random Forest  
   - XGBoost (XGBRFClassifier)

5. **Model Evaluation:**  
   Evaluated models on accuracy, confusion matrix, and classification metrics. The Random Forest model performed best.

## Technologies and Libraries
- Python 3  
- Pandas, NumPy (data handling and manipulation)  
- Matplotlib, Seaborn (visualization)  
- scikit-learn (machine learning models and metrics)  
- imbalanced-learn (SMOTE for handling class imbalance)  
- XGBoost (advanced boosting classifier)  

## How to Run
1. Clone the repository:  
2. Install required packages:  
3. Run the Jupyter Notebook (`Customer_Churn_Analyzer.ipynb`) to execute the analysis and modeling steps.

## Results
- Random Forest classifier achieved the highest accuracy (replace with actual score).  
- Key insights on drivers of churn were obtained to help business decision-making.

## Future Work
- Tune hyperparameters for better performance.  
- Include additional feature engineering.  
- Experiment with other advanced models like neural networks.

## Author
Aditya Kumar 
aditya_2312res878@iitp.ac.in
