# Telco-Customer-Churn-Prediction-Scriptguru
This project focuses on predicting **customer churn** — that is, identifying whether a customer is likely to continue this service or not. The model uses customer data, account information, and service usage patterns to churn behavior.  
## Project Objective
The main goal of this project is to build and evaluate two machine learning models (logistic regression and random forest) that can accurately predict customer churn and help businesses make data-driven decisions to improve customer retention.
## Data Set Overveiw
This data set is extracted from Kaggle named "Telco-Customer-Churn-Prediction".
The dataset contains detailed information about telecom customers such as:
- **Customer Basic details** (gender, senior citizen, dependents, etc.)
- **Account information** (contract type, payment method, tenure, monthly charges)
- **Service details** (internet service, online security, tech support, etc.)
- **Target variable:** `Churn` — indicates whether the customer has left the service.
## Models Implemented
Two Models are implemented **Logistic Regression and Random Forest**.
1. **Logistic Regression** – baseline model for linear relationships.  
2. **Random Forest Classifier** – captures complex, non-linear patterns.
Each model was evaluated based on accuracy, precision, recall, and F1-score to ensure balanced performance.
## Tools and Technologies Used
- **Python**
- **Jupyter Notebook**
- **Pandas** and **NumPy** for data manipulation.
- **StandardScaler** for sacling X and Y.
- **Matplotlib** and **Seaborn** for visualization.
- **LabelEncoder** for coverting strings into numeric.
## Results and Comparison
The models were evaluated using key performance metrics — **Accuracy**, **Precision**, **Recall**, and **F1-Score** — to understand how well they predict customer churn.
### Model Performance Comparison
| Model | Accuracy | Precision | Recall | F1-Score | Key Notes |
|:------|:----------:|:-----------:|:---------:|:-----------:|:------------|
| **Logistic Regression** | **0.815** | 0.677 | 0.579 | 0.624 | Achieved the best balance between precision and recall. The model effectively differentiates between customers likely to churn and those who will stay. |
| **Random Forest** | **0.796** | 0.662 | 0.472 | 0.551 | Showed strong precision but lower recall, meaning it missed more actual churn cases. However, it captured complex relationships between input features well. |
## Project Wrokflow
1. **Data Cleaning:** Handled missing and categorical values.  
2. **Exploratory Data Analysis:** Identified trends and correlations.  
3. **Feature Engineering:** Converted categorical features and scaled numerical ones.  
4. **Model Training:** Tested two ML algorithms.  
5. **Evaluation:** Compared models using standard performance metrics. 
## Visualisation
The project includes several insightful visualizations such as:
- Churn rate by contract type.
- Bar Graph for distribution of tenure by churn.  
- Correlation heatmap of key features. 
- Actual Vs Predicted bar graph to see model performance of both the models.
## Future Improvement
- Implement XGBoost or LightGBM for higher accuracy  
- Deploy the best model using Flask or Streamlit for live predictions  
## Conclusion
This project demonstrates how machine learning can help telecom companies reduce customer churn by identifying at-risk customers early. With further optimization, the system can be a valuable tool for customer retention strategies.
