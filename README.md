# Simple-Linear-Regression-Height-Prediction-from-Weight
Simple Linear Regression using Python to predict height from weight, including data standardization, model training, test-set prediction, and evaluation using MAE, MSE, and R² score.
📌 Project Overview

This project demonstrates the implementation of Simple Linear Regression using a small dataset containing weight and height values.

The objective is to build a machine learning model that learns the relationship between weight and height and uses weight to predict height for unseen test data.

The project covers the basic machine learning workflow:

Loading the dataset
Exploring the data
Standardizing the features
Splitting the data into training and testing sets
Training a Simple Linear Regression model
Making predictions on test data
Evaluating model performance using MAE, MSE, and R² score
🎯 Objective

The main objective of this project is to understand how Simple Linear Regression can be used to model the relationship between two numerical variables.

In this project:

Independent variable (X): Weight
Dependent variable (y): Height

The model learns a linear relationship between weight and height and predicts height based on a given weight.

📊 Dataset

The dataset is a small dataset containing two numerical variables:

Feature	Description
Weight	Weight of the individual
Height	Height of the individual

The dataset is used to demonstrate the complete workflow of a basic regression problem.

🔄 Project Workflow
Dataset
   ↓
Data Exploration
   ↓
Data Preprocessing
   ↓
Feature Standardization
   ↓
Train-Test Split
   ↓
Simple Linear Regression
   ↓
Prediction on Test Data
   ↓
Model Evaluation
   ↓
MAE | MSE | R² Score
🛠️ Technologies Used
Python
NumPy
Pandas
Matplotlib
Scikit-learn
Jupyter Notebook
⚙️ Methodology
1. Data Loading

The dataset is loaded using Pandas and inspected to understand its structure, features, and values.

2. Data Preprocessing

The weight and height data are checked and prepared for machine learning.

3. Feature Standardization

The input feature is standardized using StandardScaler.

Standardization transforms the feature so that it has approximately:

Mean = 0
Standard deviation = 1

This can be represented as:

z = (x - μ) / σ

where:

x = original value
μ = mean
σ = standard deviation
4. Train-Test Split

The dataset is divided into training and testing sets.

The training data is used to learn the relationship between weight and height, while the test data is used to evaluate how well the model performs on unseen observations.

5. Simple Linear Regression

A Simple Linear Regression model is trained using Scikit-learn.

The model represents the relationship between the input and output using a linear equation:

y = b₀ + b₁x

where:

y = predicted height
x = weight
b₀ = intercept
b₁ = regression coefficient
6. Prediction

After training, the model is used to predict height values for the test dataset.

7. Model Evaluation

The model is evaluated using three regression metrics.

Mean Absolute Error (MAE)

MAE measures the average absolute difference between actual and predicted values.

MAE = average(|actual - predicted|)

A lower MAE indicates smaller prediction errors.

Mean Squared Error (MSE)

MSE calculates the average squared difference between actual and predicted values.

MSE = average((actual - predicted)²)

A lower MSE indicates better predictive performance.

R² Score

R² measures how well the model explains the variation in the target variable.

An R² value closer to 1 indicates that the model explains a larger proportion of the variation in the target data.

📈 Results

The trained model was evaluated on the test dataset using:

Metric	Purpose
MAE	Measures average absolute prediction error
MSE	Measures squared prediction error
R² Score	Measures the proportion of variance explained by the model

The actual metric values obtained from the notebook can be added here:

MAE = [your value]
MSE = [your value]
R² Score = [your value]
📁 Project Structure
Simple-Linear-Regression/
│
├── dataset/
│   └── height_weight.csv
│
├── Simple_Linear_Regression.ipynb
│
├── README.md
│
└── requirements.txt
🚀 How to Run the Project
1. Clone the repository
git clone <your-github-repository-url>
2. Navigate to the project directory
cd Simple-Linear-Regression
3. Install the required libraries
pip install numpy pandas matplotlib scikit-learn jupyter
4. Open the Jupyter Notebook
jupyter notebook

Open:

Simple_Linear_Regression.ipynb

and run the cells sequentially.

💡 Key Learnings

Through this project, I gained practical understanding of:

Data preprocessing
Feature standardization
Train-test splitting
Simple Linear Regression
Model training and prediction
Regression evaluation metrics
MAE, MSE, and R² score
Basic machine learning workflow using Scikit-learn
🔮 Future Improvements

Some possible improvements to this project include:

Using a larger dataset
Visualizing the regression line
Comparing Linear Regression with other regression algorithms
Performing cross-validation
Adding residual analysis
Deploying the model using Streamlit or Flask
👩‍💻 Author
Adwaitha

Adwaitha T

This project was created as part of my learning journey in Machine Learning and Data Science.
