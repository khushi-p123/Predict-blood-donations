# Predicting Blood Donation Behavior

This project builds a machine learning model to predict whether a donor is likely to give blood again. 
It's based on historical donation behavior and aims to support blood banks in identifying repeat donors.

*Features:
`Recency`: Months since last donation
`Frequency`: Total donations made
`Monetary`: Total blood donated (in cc)
`Time`: Months since first donation
`Target`: 1 if the donor gave blood recently, 0 otherwise

#Tools & Libraries

- Python  
- Pandas, NumPy  
- Matplotlib, Seaborn  
- Scikit-learn (Logistic Regression, Random Forest)  
- Jupyter Notebook

#Project Steps

1. Data Loading & Cleaning  
   - Checked for missing values  
   - Feature selection and formatting

2. Exploratory Data Analysis (EDA)  
   - Visualized relationships between donation frequency and recency  
   - Observed patterns in high-return donors

3. Model Training
   - Used Logistic Regression (baseline)  
   - Random Forest performed best (F1 Score ~0.80)  
   - Hyperparameter tuning with GridSearchCV

4. Evaluation  
   - Accuracy: 85%  
   - ROC AUC: 0.87  
   - Precision-Recall and ROC curve visualizations

#Results

- Best model: Random Forest Classifier  
- Accurately identifies potential repeat donors  
- Can be used to support marketing/awareness efforts by blood banks