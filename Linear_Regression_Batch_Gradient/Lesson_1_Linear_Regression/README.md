# 📈 Linear Regression from Scratch

## 🎯 Overview
This project implements a **Linear Regression model entirely from scratch** using Python and NumPy. Instead of relying on high-level machine learning libraries like `scikit-learn`, I built the core mathematical optimization algorithm—**Gradient Descent**—to autonomously find the line of best fit. 

## 🧠 Core Implementations
* **Mathematical Optimization:** Implemented the Gradient Descent algorithm to iteratively minimize the Mean Squared Error (MSE) cost function.
* **Vectorized Operations:** Utilized NumPy for efficient matrix multiplication ($X^T X$, $X \cdot W$), avoiding inefficient `for` loops during data processing.
* **The Bias Trick:** Handled the y-intercept mathematically by dynamically appending a column of ones to the feature matrix.
* **Custom Evaluation Metrics:** Programmed $R^2$ (Coefficient of Determination) and RMSE (Root Mean Square Error) functions manually to evaluate model performance and test for overfitting.

## 📊 Results
The model was trained and evaluated on a Kaggle dataset, demonstrating excellent generalization capabilities on unseen test data:
* **Test RMSE:** ~3.00
* **Test $R^2$ Score:** 0.9893 (98.9%)

### Model Visualization
*(Note: Replace this text with the actual graph image you generated using Matplotlib. You can just drag and drop the image directly into GitHub's editor!)*

## 🛠️ Technologies Used
* **Python**
* **NumPy** (Linear Algebra)
* **Pandas** (Data loading & cleaning)
* **Matplotlib** (Data visualization)

## 💡 Why This Project?
While it's easy to import a model using `from sklearn.linear_model import LinearRegression`, building the algorithm from the ground up provides a much deeper understanding of the underlying calculus, linear algebra, and mechanics of machine learning models.
