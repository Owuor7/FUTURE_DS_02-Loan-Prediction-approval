Loan Prediction Model
Overview
This project aims to predict the status of loan applications based on various applicant and loan-related features such as Applicant Income, Loan Amount, Credit History, and Education Level. The objective is to determine whether a loan will be approved (1) or denied (0) using machine learning models.

I implemented and compared three machine learning algorithms:

Decision Tree
Random Forest
Gaussian Naive Bayes (GNB)
The Gaussian Naive Bayes model emerged as the best performer in this case, offering an effective balance between simplicity and prediction accuracy.

Dataset
The dataset used contains features such as:

ApplicantIncome: Income of the loan applicant
LoanAmount: Amount of loan requested
CreditHistory: History of credit repayment (1 = good, 0 = poor)
Education: Education level of the applicant (Graduate/Not Graduate)
Project Highlights
Data Visualization: Conducted detailed Exploratory Data Analysis (EDA) using Matplotlib and Seaborn to visualize the distribution of key features like Applicant Income and the correlation between Credit History and loan approval.

Outlier Removal: Identified and removed outliers from the dataset to improve model performance.

Model Performance:

Gaussian Naive Bayes achieved the best results, demonstrating the strength of probabilistic approaches for this classification problem.
Random Forest and Decision Tree models were also evaluated for comparison.
Results
The Gaussian Naive Bayes model outperformed the other models, showing strong accuracy for predicting loan approval status. Further tuning and feature engineering could improve performance even more.

Tools and Libraries
Python
Pandas
Matplotlib & Seaborn (for data visualization)
Scikit-learn (for model building)
Future Improvements
Planned next steps include:

Feature Engineering: Further refinement of features to improve model performance.
Model Optimization: Explore additional machine learning models and apply hyperparameter tuning to enhance accuracy.
Collaboration
This project was completed in collaboration with FUTURE interns, where I gained valuable insights and experience in predictive modeling and data analysis.
