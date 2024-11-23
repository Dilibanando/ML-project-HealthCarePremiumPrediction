# ML-project-HealthCarePremiumPrediction
## Healthcare Premium Prediction
This project aims to predict the healthcare premium amount based on various features such as age, income, medical history, and more. Using machine learning, the model takes in user-specific information and provides an estimated premium.

## Use Case
### By inputting the following features:

Age
Number of Dependants
Income in Lakhs
Genetic Risk
Insurance Plan
Employment Status
Gender
Marital Status
BMI Category
Smoking Status
Region
Medical History
The model predicts the healthcare premium amount, which can be used to understand expected healthcare costs.

## Steps Involved
### 1. Exploratory Data Analysis (EDA)
Understanding the data through statistical summaries and visualizations.
Identifying trends, correlations, and outliers in the dataset.
### 2. Feature Engineering
Handling missing values, encoding categorical variables, and scaling numerical features.
Creating new features from the existing ones to improve model performance.
### 3. Model Training and Fine-Tuning
Tested Linear Regression and XGBoost models for regression.
Fine-tuned hyperparameters using RandomizedSearchCV to find the best-performing model.
### 4. Error Analysis
Evaluating the model performance using appropriate metrics (e.g., RMSE, R^2).
Identifying underperforming areas and improving the model.
### 5. Model Segmentation
Dividing the dataset into training and testing sets.
Using cross-validation to ensure the model generalizes well.
### 6. Model Deployment
The trained model is deployed using Streamlit, enabling users to input their data and predict the healthcare premium amount via a simple web interface.

## Technologies Used
Python: Main programming language.
Pandas: For data manipulation and cleaning.
Scikit-learn: For machine learning models and evaluation.
XGBoost: For advanced gradient boosting model.
Streamlit: For deploying the model as a web application.
Matplotlib / Seaborn: For data visualization.
Joblib: For saving and loading the trained model.

## How to Use
### Clone the Repository:

bash
git clone <repository_url>
Install Required Libraries: Navigate to the project directory and install the dependencies:

bash
pip install -r requirements.txt
Run the Streamlit App: To start the web application locally:

bash
streamlit run app.py
Input Your Data: Enter the required information in the web interface and click the Predict button to see the healthcare premium estimate.

## Results
The model predicts the healthcare premium amount based on user-provided features, providing valuable insights for individuals seeking insurance coverage or understanding healthcare costs.

## Future Improvements
Enhance the model using more advanced algorithms like Gradient Boosting or Neural Networks.
Integrate more external data sources for more accurate predictions.
Improve user interface for a better user experience.
