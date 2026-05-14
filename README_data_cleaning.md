# Data Cleaning and Preprocessing

This phase focuses on preparing the raw telecom customer churn dataset for analysis, dashboard creation, and machine learning modeling. Real-world datasets often contain missing values, inconsistent formats, duplicate records, and incorrect data types, which can negatively affect analytical accuracy and model performance.

## Data Cleaning Process

### Handling Missing Values

Missing and null values were identified using Pandas functions such as `isnull()` and `sum()`. Numerical missing values were replaced with appropriate values such as `0`, while categorical missing values were handled carefully to maintain data consistency.

### Data Type Fixing

Several columns contained incorrect data types after importing the dataset. Numerical fields such as `Monthly Charges`, `Total Charges`, and `Tenure Months` were converted into appropriate numeric formats using Pandas preprocessing techniques to ensure accurate calculations and analysis.

### Duplicate Removal

Duplicate records were detected and removed using the `drop_duplicates()` function. This ensured that the dataset maintained unique customer records and prevented biased KPI calculations and machine learning predictions.

### Text Preprocessing

Categorical text columns were cleaned by removing extra spaces, standardizing text formatting, and correcting inconsistencies in categorical values. This improved data quality and ensured proper encoding for machine learning models.

### Column Optimization

Unnecessary columns such as geographical coordinates and less relevant identifiers were removed to improve processing efficiency and focus on important churn-related features.

## Tools and Technologies Used

* Python
* Pandas
* NumPy
* Google Colab

The cleaned dataset was saved as `cleaned_churn_data.csv` and used for Exploratory Data Analysis (EDA), KPI analysis, Power BI dashboard creation, and Machine Learning model training.
