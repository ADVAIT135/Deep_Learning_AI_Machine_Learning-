# Machine Learning Fundamentals – Logistic & Linear Regression

This repository contains code implementations and visualizations related to **logistic regression**, **linear regression**, and **regularization**. It is designed as a learning resource to understand cost functions, gradient descent, overfitting, and classification boundaries.

---

## 📂 Contents

### 1. Python Implementations
- **sigmoid.py**  
  Implements the sigmoid function used in logistic regression.

- **compute_cost.py**  
  Calculates the logistic regression cost function.

- **compute_gradient.py**  
  Computes gradients for logistic regression.

- **predict.py**  
  Predicts binary outcomes (0 or 1) using logistic regression parameters.

- **compute_cost_reg.py**  
  Adds L2 regularization to the logistic regression cost function.

- **compute_gradient_reg.py**  
  Adds L2 regularization to the gradient computation.

---

### 2. Visualizations
The repository includes several plots and diagrams to illustrate key concepts:

- **Sigmoid Function**  
  S-shaped curve mapping input values to probabilities between 0 and 1.

- **Logistic Regression on Tumor Data**  
  Demonstrates classification of tumor sizes into benign vs malignant using a sigmoid boundary.

- **Cost Function Landscapes**  
  - 3D surface plots of cost functions \( J(w, b) \).  
  - Contour plots showing gradient descent paths.  
  - Squared error cost visualization for linear regression.

- **Overfitting Examples**  
  Polynomial decision boundaries on noisy categorical datasets, showing how high-degree polynomials can lead to overfitting.

- **Housing Prices Regression**  
  Linear regression example predicting housing prices based on size, with cost function visualizations.

---

## 🧮 Key Concepts Illustrated
- **Loss vs Cost**  
  - *Loss*: Error for a single training example.  
  - *Cost*: Average loss across all training examples.

- **Gradient Descent**  
  Iterative optimization to minimize cost functions.

- **Regularization (λ)**  
  Prevents overfitting by penalizing large weights.

- **Overfitting vs Generalization**  
  Visual examples of how polynomial features affect classification boundaries.

---

## 🚀 How to Use
1. Clone the repository:
   ```bash
   git clone https://github.com/ADVAIT135/ml-regression-examples.git
