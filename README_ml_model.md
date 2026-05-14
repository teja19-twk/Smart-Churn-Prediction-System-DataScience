# Machine Learning Model – Customer Churn Prediction

This phase focuses on building and training a Machine Learning model to predict customer churn using telecom customer data. The objective of the model is to identify customers who are likely to discontinue telecom services, enabling businesses to improve customer retention strategies and reduce revenue loss.

## Machine Learning Algorithm

A Random Forest Classifier was used for churn prediction due to its strong performance, robustness, and ability to handle both numerical and categorical data effectively. The algorithm analyzes customer behavior patterns and predicts whether a customer is likely to churn or remain retained.

## Data Preprocessing and Encoding

Before model training, the dataset was preprocessed and transformed into a machine-learning-ready format. Categorical columns such as gender, contract type, payment method, and internet services were encoded into numerical values using Label Encoding techniques. Unnecessary columns and irrelevant features were removed to improve model performance and reduce complexity.

## Train-Test Split

The cleaned dataset was divided into:

* 80% Training Data
* 20% Testing Data

The training dataset was used to train the machine learning model, while the testing dataset was used to evaluate prediction performance and accuracy.

## Model Training

The Random Forest model was trained using Scikit-learn libraries in Python. The model learned patterns from customer demographics, service usage, contract information, monthly charges, tenure, and churn-related behavior.

## Accuracy and Evaluation

The model performance was evaluated using:

* Accuracy Score
* Classification Report
* Confusion Matrix

The trained model achieved strong prediction performance in identifying churn-prone customers and retention patterns.

## Model Saving

After successful training and evaluation, the machine learning model was saved using the Pickle/Joblib format as:

text
churn_model.pkl

The saved model can later be reused for:

* Real-time churn prediction
* Deployment in web applications
* Dashboard integration
* Future predictive analytics

## Technologies Used

* Python
* Pandas
* NumPy
* Scikit-learn
* Random Forest Classifier
* Google Colab
* Joblib / Pickle

This machine learning phase transformed customer data into predictive business intelligence, enabling data-driven customer retention strategies and advanced analytics.
