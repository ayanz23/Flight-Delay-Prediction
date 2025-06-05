This project analyzes flight delay patterns and develops machine learning models to predict significant flight delays. Using the `delays.csv` dataset, it explores delay distribution, causes, and the impact of factors like carriers, airports, and time of year through comprehensive exploratory data analysis. The project then focuses on building and evaluating classification models (Random Forest, LightGBM, XGBoost, and MLP) to predict a high_delay event (delay rates exceeding 25%). Key features for prediction include various delay causes, encoded carrier and airport information, and time-based features. The models are evaluated using metrics such as ROC AUC, Average Precision, and Classification Reports, with Random Forest and LightGBM showing strong performance in predicting flight delays.

![output](https://github.com/user-attachments/assets/a34acd9b-28f5-4b3e-bf62-344b138c2449)
![output2](https://github.com/user-attachments/assets/25317f67-8013-4d29-8379-a36cfe153d78)
![output3](https://github.com/user-attachments/assets/5af10816-30f7-4514-a664-4683bb7d65ab)

How to run to see full insights/graphs:
1. Clone the git repository
2. Run `pip install pandas matplotlib seaborn numpy scikit-learn lightgbm xgboost`
3. Run the notebooks:
- new_analysis.ipynb: For data exploration and visualizations.
- new_modeling.ipynb: For data preprocessing, model training, and evaluation.
