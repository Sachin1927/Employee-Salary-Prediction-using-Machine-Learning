# Employee-Salary-Prediction-using-Machine-Learning

Predicting Employee Salaries with Data-Driven Accuracy


📘 Overview

This project implements a machine learning–based salary prediction system that estimates employee salaries using features such as experience, education, skill, department, and location.
It provides data-backed insights for HR teams, business analysts, and data scientists to evaluate compensation fairness and predict market-aligned pay.

The system leverages multiple regression models, hyperparameter tuning, and Gradio-based UI deployment for interactive predictions.

🎯 Key Objectives

Predict employee salary with high accuracy using regression models.

Identify key features influencing compensation patterns.

Build a scalable ML pipeline with feature encoding, scaling, and model validation.

Enable real-time salary predictions through an interactive web interface.

📂 Dataset

Dataset Attributes:

Feature	Description
department	Department or role category
education	Education level (Bachelor, Master, PhD, etc.)
experience	Total years of experience
skill	Skill level (Beginner, Intermediate, Advanced)
location	City or region of employment
salary	Annual salary (target variable)

⚙️ Project Workflow

Data Preprocessing

Handled missing values using SimpleImputer

Applied OneHotEncoder for categorical features

Scaled numerical data using StandardScaler

Exploratory Data Analysis (EDA)

Visualized feature distributions and salary trends

Explored correlations among education, experience, and salary

Used seaborn, matplotlib, and plotly for interactive visual insights

Model Development

Trained and compared several models:

Linear Regression

Ridge & Lasso Regression

Random Forest Regressor

Gradient Boosting Regressor

XGBoost (final model)

Evaluated using K-Fold cross-validation

Optimized hyperparameters for best performance

Model Evaluation

Compared models using R², RMSE, and MAE

Selected the XGBoost model as the final solution for its stability and generalization

Deployment

Integrated with Gradio UI for real-time, user-friendly predictions

Users can input their details and instantly get a salary prediction

🧩 Tools & Technologies
Category	Libraries / Tools
Language	Python
Data Analysis	Pandas, NumPy
Visualization	Matplotlib, Seaborn, Plotly
Machine Learning	Scikit-learn, XGBoost
UI / Deployment	Gradio
Development	Jupyter Notebook / Google Colab
📊 Model Comparison
Model	R² Score	RMSE	Remarks
Linear Regression	0.84	Moderate	Baseline model
Random Forest	0.91	Low	Strong generalization
Gradient Boosting	0.92	Lower	Stable learning
XGBoost	0.94	Lowest	✅ Best performer


📈 Results Visualization

🔹 Salary Distribution by Experience


<img width="851" height="501" alt="Screenshot 2025-11-06 000733" src="https://github.com/user-attachments/assets/b988b5b6-5bcc-4403-806d-fa6d5e8ab8a9" />


🔹 Education Level Impact on Salary

<img width="936" height="645" alt="image" src="https://github.com/user-attachments/assets/c3f64b2a-5ad5-49cb-9925-d40c5d1dc8ba" />



🔹 Skill vs Salary Correlation

<img width="746" height="549" alt="Screenshot 2025-11-06 001736" src="https://github.com/user-attachments/assets/6a5d8a25-48ec-46f8-a927-ccb328a2c220" />



🔹 Feature Importance (XGBoost)

<img width="992" height="629" alt="Screenshot 2025-11-06 001304" src="https://github.com/user-attachments/assets/41064f5f-e771-4bf2-91e6-b1c755188768" />



🔹 Model Performance Comparison

<img width="737" height="620" alt="Screenshot 2025-11-06 001521" src="https://github.com/user-attachments/assets/20368136-8f55-46fd-8484-61d4b6ba21ae" />
<img width="749" height="439" alt="Screenshot 2025-11-06 001534" src="https://github.com/user-attachments/assets/882c1b93-0aa9-48e4-8a33-dd23c094e853" />



🔮 Insights

Salary correlates strongly with experience, education, and location.

Technical skill proficiency has a higher predictive weight than department.

XGBoost outperformed all other algorithms in both accuracy and generalization.

The pipeline is ready for deployment as an API or Flask/Dash web app.
