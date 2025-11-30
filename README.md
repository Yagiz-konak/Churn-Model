📉 Customer Churn Prediction Model
📌 Project Overview
Customer churn (attrition) is one of the biggest challenges for subscription-based businesses. This project aims to build a Machine Learning model to predict which customers are likely to leave the company. By identifying at-risk customers early, businesses can take proactive actions (such as targeted marketing or incentives) to retain them.

This repository contains the complete workflow from data exploration to model evaluation using Python and Scikit-Learn.

📂 Dataset
The dataset used in this project includes customer demographics, service usage details, and billing information.

Target Variable: Churn (Yes/No) - Whether the customer left the company.

Key Features: Tenure, Monthly Charges, Contract Type, Payment Method, etc.

⚙️ Methodology & Workflow
The project follows a structured data science pipeline:

Exploratory Data Analysis (EDA):

Analyzed the distribution of the target variable (Churn vs. Non-Churn).

Visualized correlations between features using Heatmaps.

Identified outliers and missing values.

Data Preprocessing:

Handling Missing Values: Imputed missing numerical and categorical values.

Encoding: Converted categorical variables into numerical format using One-Hot Encoding (or Label Encoding).

Scaling: Standardized numerical features to ensure model stability.

Model Selection & Training:

Tested various algorithms (e.g., Logistic Regression, Random Forest, Gradient Boosting).

The best performing model was selected for the final evaluation.

📊 Model Evaluation
Since customer churn datasets are often imbalanced (fewer people churn than stay), relying solely on accuracy can be misleading. Therefore, this project focuses on the Confusion Matrix to evaluate the model's real-world performance.

Performance Metrics

Best Model: LightGBM

Accuracy Score: 0.8696

🚀 Conclusion
The developed model provides a reliable tool for churn prediction. By integrating this model into the CRM system, the company can:

Automatically flag high-risk customers.

Reduce revenue loss by minimizing False Negatives.

Optimize marketing budget by targeting the right audience.

🛠️ Installation & Usage
To run this project locally, follow these steps:

Clone the repository:

Bash
git clone https://github.com/your-username/Customer-Churn-Model.git
Navigate to the project directory:

Bash
cd Customer-Churn-Model
Install the required dependencies:

Bash
pip install -r requirements.txt
Run the Jupyter Notebook:

Bash
jupyter notebook
📚 Libraries Used
Pandas & NumPy: Data manipulation and analysis.

Matplotlib & Seaborn: Data visualization.

Scikit-Learn: Machine learning modeling and evaluation.

Author: yağız konak - Statistics Student @ Hacettepe University
