 ### Project Overview: California Housing Price Prediction

This project is a detailed case study in applying **supervised machine learning** to a real-world problem: predicting house prices. The entire process is contained within a single **Jupyter Notebook**, making it a self-contained and reproducible example. The project uses the well-known **California Housing dataset** and a **Linear Regression** model, a fundamental algorithm for understanding linear relationships in data.

#### **What is the Goal?**

The primary objective is to build a predictive model that can estimate the median house value in a given area of California based on several key features. This is a **regression** problem, which means the model's output is a continuous numerical value (the predicted price) rather than a category or class.

#### **How the Code Works (The Machine Learning Pipeline)**

The notebook follows a standard, step-by-step machine learning workflow:

1.  **Data Acquisition and Preparation:** The project begins by fetching the California Housing dataset directly from `scikit-learn`, which is a common practice for using built-in datasets for learning and experimentation. This step saves time and ensures the data is readily available.

2.  **Exploratory Data Analysis (EDA):** The code explores the dataset to understand its structure, including the features (e.g., median income, number of rooms, population) and the target variable (median house value). This phase is crucial for identifying data types, potential missing values, and the relationships between variables.

3.  **Data Splitting:** The dataset is divided into two parts: a **training set** and a **testing set**. The model is trained exclusively on the training data, while the testing data is held back. This separation ensures that the model's performance is evaluated on data it has never seen before, providing an unbiased assessment of its true predictive power.

4.  **Model Training:** The `LinearRegression` model is initialized and then "fitted" to the training data. During this process, the model learns the coefficients for each feature, which represent the weight or importance of that feature in predicting the house price.

5.  **Prediction and Evaluation:** After training, the model is used to make predictions on the testing data. The accuracy of these predictions is then measured using three key metrics:
    * **Mean Absolute Error (MAE):** 0.52
    * **Mean Squared Error (MSE):**  0.49
    * **R-squared ($R^2$) Score:**  0.52 
    * **Model Accuracy:** 62.01 %

6.  **Visualization:** Finally, the notebook uses a scatter plot to visually compare the predicted house prices against the actual prices. This plot is a powerful tool for seeing how well the model's predictions align with reality and for spotting any patterns or issues.

This project serves as a clear and practical template for anyone looking to get started with regression analysis in Python.
