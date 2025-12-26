# Term-Deposit-Prediction-
## Task Objective
The objective of this task is to predict whether a bank customer will subscribe to a term deposit as a result of a marketing campaign. This helps banks understand customer behavior and improve the effectiveness of their marketing strategies.

## Dataset
- **Source:** Bank Marketing Dataset (UCI Machine Learning Repository)  
- Contains customer demographic, financial, and campaign-related features.  
- Target variable: `y` (subscription to term deposit: yes/no).
## Approach
1. **Data Loading & Exploration**
   - Imported dataset and performed exploratory data analysis (EDA).
   - Checked for missing values, feature distributions, and correlations.

2. **Feature Encoding**
   - Applied one-hot encoding to categorical variables (e.g., job, marital status, education).
   - Ensured proper handling of binary features.

3. **Model Training**
   - Implemented classification models:
     - Logistic Regression
     - Random Forest
   - Tuned hyperparameters for better performance.

4. **Model Evaluation**
   - Used **Confusion Matrix**, **F1-Score**, and **ROC Curve** to assess performance.
   - Compared results across models.

5. **Model Interpretability**
   - Applied **SHAP** and **LIME** to explain predictions.
   - Selected 5 customer cases to demonstrate feature contributions.

## Results and Findings
- Logistic Regression provided a good baseline performance for predicting term deposit subscriptions.
-Random Forest outperformed Logistic Regression with a higher F1-score and better overall prediction performance. The model effectively   identified customers more likely to subscribe to a term deposit. Key factors influencing customer decisions included contact duration and previous campaign outcomes.

- The confusion matrix showed that the Random Forest model reduced false negatives, making it more effective for identifying potential subscribers.
- Important factors influencing subscription included contact duration, previous campaign outcome, and customer balance.
- Overall, Random Forest was selected as the best-performing model for this task.
## Final Conclusion and Insights
The Random Forest model performed best for predicting term deposit subscriptions. The analysis showed that customer interaction duration and previous campaign success strongly influence subscription decisions. This model can help banks improve targeted marketing strategies.
