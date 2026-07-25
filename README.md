# CarInsurance-DecisionTree
🚗 Car Insurance Purchase Prediction using Random Forest

📌 Project Overview

Insurance companies spend significant resources on marketing campaigns to acquire new customers. Predicting which customers are more likely to purchase car insurance helps businesses focus their efforts on high-potential leads, reduce marketing costs, and improve campaign effectiveness.

In this project, a Random Forest Classifier was developed to predict whether a customer would purchase car insurance based on demographic, financial, and vehicle-related attributes.

---

🎯 Business Problem

Instead of contacting every customer, insurance companies can use machine learning to identify customers with a higher probability of purchasing insurance, allowing sales teams to prioritize outreach and improve conversion rates.

---

📂 Dataset

The dataset contains customer information such as:

- Age
- Gender
- Region
- Vehicle Age
- Vehicle Damage History
- Annual Premium
- Policy Sales Channel
- Vintage
- Driving License Status
- Previously Insured Status

Target Variable

- CarInsurance
  - 1 = Customer purchases insurance
  - 0 = Customer does not purchase insurance

---

🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Random Forest Classifier
- Matplotlib
- Seaborn

---

⚙️ Model Development

The workflow included:

- Data preprocessing
- Feature preparation
- Train-Test Split
- Random Forest model training
- Model evaluation using Classification Report
- Performance comparison on training and testing datasets

Random Forest Parameters

- Estimator: 25 Trees
- Criterion: Gini
- Max Depth: 4
- Minimum Samples Split: 100
- Random State: 20

---

📊 Model Performance

Training Performance

- Accuracy: 70%
- Class 0 Precision: 0.96
- Class 0 Recall: 0.67
- Class 1 Precision: 0.31
- Class 1 Recall: 0.83

Testing Performance

- Accuracy: 69%
- Class 0 Precision: 0.95
- Class 0 Recall: 0.67
- Class 1 Precision: 0.28
- Class 1 Recall: 0.79

The model produced similar performance on both training and testing datasets, indicating stable generalization with limited overfitting.

---

✅ Outcome

The Random Forest model achieved approximately 69% testing accuracy while maintaining consistent performance across train and test datasets. It successfully identified a large proportion of customers likely to purchase insurance (high recall for the positive class), making it useful for customer targeting where minimizing missed opportunities is more important than maximizing overall accuracy.

---

💼 Business Impact

- Prioritize high-potential customers for marketing campaigns.
- Improve insurance conversion rates.
- Reduce customer acquisition costs.
- Support data-driven sales and marketing decisions.
- Enable more efficient allocation of marketing resources.

---

🚀 Future Improvements

- Hyperparameter tuning using GridSearchCV or RandomizedSearchCV.
- Address class imbalance using SMOTE or class weighting.
- Compare with XGBoost, LightGBM, and Gradient Boosting.
- Perform feature importance analysis for better business insights.
- Deploy the model as a web application for real-time predictions.
