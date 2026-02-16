# Task-3-AI-ML
📂 Dataset

Dataset used: Housing.csv

Target Variable: price

Features: All remaining columns after preprocessing

Categorical variables were converted using one-hot encoding.

⚙️ Steps Performed
1️⃣ Data Preprocessing

Loaded dataset using pandas

Checked dataset structure

Converted categorical variables using pd.get_dummies()

Split data into training (70%) and testing (30%)

2️⃣ Model Training

Imported LinearRegression from sklearn.linear_model

Initialized the model

Fitted the model using:

model.fit(X_train, y_train)

3️⃣ Model Evaluation

The model was evaluated using:

MAE (Mean Absolute Error)

MSE (Mean Squared Error)

R² Score

These metrics help measure prediction accuracy and error.

4️⃣ Visualization

Plotted Actual vs Predicted values

Visualized regression performance

5️⃣ Coefficient Interpretation

Printed model intercept

Displayed feature coefficients

Interpreted impact of each feature on house price

📊 Evaluation Metrics Meaning

MAE → Average prediction error

MSE → Penalizes large errors more

R² Score → Indicates model accuracy (Closer to 1 = Better)

🛠️ Libraries Used

pandas

numpy

matplotlib

sklearn
