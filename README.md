# Titanic-Python-
This project involved building a predictive model to determine the survival probability of passengers on the Titanic. By analyzing historical passenger data, I implemented a machine learning workflow—from data cleaning and exploratory analysis to model deployment via an interactive function.

Key Responsibilities & Highlights:

Exploratory Data Analysis (EDA): Utilized Seaborn and Matplotlib to identify key survival drivers. Visualized the correlation between survival rates and variables such as Gender and Socio-economic Class (Pclass), revealing significant survival disparities.

Data Preprocessing & Cleaning: Addressed missing values by imputing the mean for the Age column and dropping features with excessive missing data (e.g., Cabin).

Performed feature selection by removing non-predictive attributes like PassengerId, Ticket, and Name.

Feature Engineering: Created a consolidated Family feature by combining SibSp (siblings/spouses) and Parch (parents/children) to better represent the impact of traveling with family on survival outcomes.

Machine Learning Modeling: Applied Label Encoding to convert categorical variables into numerical format for model compatibility.

Trained and optimized a Logistic Regression model using a standard 80/20 train-test split.

Performance Evaluation: Assessed model reliability using multiple metrics, including Accuracy Score, Confusion Matrix, and Classification Report (Precision, Recall, F1-Score). Compared training and testing scores to ensure the model was well-generalized and not overfitted.

Deployment Logic: Developed a custom Python interface (survival_predictor) that allows users to input passenger details and receive an immediate survival prediction based on the trained model.
