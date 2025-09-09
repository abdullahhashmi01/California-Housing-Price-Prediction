### Project Description: California Housing Price Prediction

This project is a detailed analysis of the **California Housing dataset** to predict median house values using a **Linear Regression** model. The entire workflow, from data fetching to model evaluation, is contained within a single Jupyter Notebook. This project is a practical example of how to apply a fundamental machine learning algorithm to a real-world, multivariate dataset. It is ideal for those who want to understand the end-to-end process of building a predictive model.

The notebook showcases key stages of a data science project:

  * **Data Acquisition and Preparation:** It demonstrates how to load a dataset, explore its features and target variable, and prepare it for a machine learning algorithm.
  * **Model Training:** The project trains a Linear Regression model on the prepared data.
  * **Performance Evaluation:** It uses multiple metrics—Mean Absolute Error, Mean Squared Error, and R-squared—to provide a robust assessment of the model's accuracy.
  * **Visualization:** It includes a scatter plot to visually compare the model's predictions against the actual values, which is crucial for interpreting the model's performance.

-----

### GitHub README.md

#### **California Housing Price Prediction**

This repository contains a comprehensive machine learning project for predicting median house values in California. The project uses the **scikit-learn** library's built-in **California Housing dataset** and employs a **Linear Regression** model to perform the prediction.

The entire project is self-contained within the `California Model.ipynb` Jupyter Notebook, making it an excellent resource for learning and replicating a complete data science workflow.

### **Detailed Breakdown of the Project**

The notebook follows a standard machine learning pipeline:

1.  **Data Loading and Initial Exploration:**

      * The project begins by fetching the dataset directly from scikit-learn.
      * It loads the data into a **pandas DataFrame** and performs initial checks to understand the dataset's structure, features, and target variable.

2.  **Data Splitting:**

      * The data is split into a **training set** (for teaching the model) and a **testing set** (for evaluating its performance on unseen data). This ensures an unbiased assessment of the model's predictive capability.

3.  **Model Training:**

      * A **Linear Regression** model is initialized and trained on the training data. The model learns the linear relationship between the input features (e.g., median income, population) and the target variable (median house value).

4.  **Prediction and Evaluation:**

      * Once trained, the model is used to make predictions on the testing data.
      * Its performance is evaluated using three key regression metrics:
          * **Mean Absolute Error (MAE):** This metric measures the average absolute difference between the predicted and actual values. It's easy to interpret as it is in the same units as the target variable.
          * **Mean Squared Error (MSE):** This metric calculates the average of the squared differences. It heavily penalizes large errors, giving you a sense of the model's largest mistakes.
          * **R-squared ($R^2$) Score:** This score indicates the proportion of the variance in the target variable that is predictable from the independent variables. A value close to 1.0 means the model is a strong predictor.

5.  **Data Visualization:**

      * A final scatter plot is generated to provide a visual representation of the model's performance. The plot compares the model's predictions against the actual house prices, allowing you to see how closely the predictions align with reality.

### **How to Run the Code**

To get started with this project, you'll need a Python environment with the following libraries:

1.  **Install Dependencies:**
    You can install all the necessary libraries using `pip`:
    ```bash
    pip install pandas numpy scikit-learn matplotlib
    ```
2.  **Open and Run the Notebook:**
    Simply open the `California Model.ipynb` file in a Jupyter environment (such as Jupyter Notebook, JupyterLab, or VS Code with the Python extension) and run all the cells. The notebook will execute each step and display all the results and plots automatically.
