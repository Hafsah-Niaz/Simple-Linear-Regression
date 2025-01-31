# Simple-Linear-Regression
📌 Simple Linear Regression on Admission Prediction Data
📝 Overview
This project demonstrates Simple Linear Regression using Python and Scikit-Learn. It involves data preprocessing, visualization, model training, and prediction on an admission prediction dataset.

🚀 Steps Performed

1️⃣ Importing Required Libraries
NumPy, Pandas for data handling
Matplotlib for visualization
Scikit-Learn for machine learning

2️⃣ Loading and Exploring the Dataset
Reading the dataset using pandas.read_csv()
Checking shape and first few rows using .shape and .head()

3️⃣ Data Preprocessing
Dropping irrelevant columns
Extracting GRE Score as X and Chance of Admit as Y
Reshaping data for model training

4️⃣ Data Visualization
Scatter plot to visualize the relationship between GRE Score and Chance of Admit

5️⃣ Splitting the Dataset
Using train_test_split() to create training (80%) and testing (20%) sets

6️⃣ Building and Training the Model
Using LinearRegression() from Scikit-Learn
Training the model with lm.fit(x_train, y_train)

7️⃣ Making Predictions
Predicting values for x_test using lm.predict(x_test)

📊 Results
The trained model predicts Chance of Admission based on GRE Score. The results can be visualized using scatter plots.
