Week 2 Mini Project – Simple scikit-learn Predictor
📌 Objective

The goal of this mini-project is to understand how theoretical ML concepts translate into actual code.
You will build a simple predictor model using scikit-learn, train it on the provided dataset, evaluate it, and observe real predictions.

📂 Project Structure
Week_2/
│── Week2_simple_predictor.ipynb
│── Housing.csv
│── README.md

📊 Dataset

We use the provided Housing.csv dataset.
The notebook loads it directly and performs:

Data cleaning

Feature selection

Train/Test split

Linear Regression model training

Prediction

Evaluation (MSE, MAE)

🤖 Model Used

LinearRegression (scikit-learn)
We predict house price using area as a single feature.

🧪 Evaluation Metrics

The notebook computes:

MSE — Mean Squared Error

MAE — Mean Absolute Error

These metrics show how close the model’s predictions are to actual prices.

🚀 How to Run
Option 1: Google Colab

Upload the .ipynb file

Upload Housing.csv

Run all cells (ensure outputs are visible)

Option 2: Jupyter Notebook locally
pip install pandas scikit-learn notebook
jupyter notebook

Open the notebook and run cells.

📤 Submission Requirements

To receive evaluation, ensure the following:

✔ Create a folder named Week_2 in your GitHub repo
✔ Upload:

Week2_simple_predictor.ipynb

Housing.csv (if allowed)

README.md
✔ All notebook cell outputs must be visible
✔ Ensure the notebook runs correctly without errors

💡 Learning Outcome

This project should help you understand how:

Real data flows into a model

A model learns relationships

Predictions differ from actual values

Performance is quantified

Do not rely only on AI—try to understand how each line works.
