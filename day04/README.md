# Task 01:
## 📈 Polynomial Function & Its Derivative – Subplot Visualization

This notebook uses Python with **NumPy** and **Matplotlib** to:

- Define a cubic polynomial:  
  \[
  f(x) = 3x^3 + 2x^2 − 5x + 7
  \]
- Apply the **power rule** to calculate its derivative:  
  \[
  f'(x) = 9x^2 + 4x − 5
  \]
- Visualize both the original function and its derivative side-by-side using **subplots**.

#### 🔍 Output Graph

The plot below shows:
- **Left subplot**: The original function `f(x)`
- **Right subplot**: Its derivative `f′(x)`

### 📸 Screenshot  
<img width="877" height="476" alt="download" src="https://github.com/user-attachments/assets/3db41e1e-bae8-4dc0-9951-ab1517bf409b" />

### 🛠 Requirements

To run this notebook, you’ll need:

- Python 3.x
- NumPy
- Matplotlib

Install packages using pip:

```bash
pip install numpy matplotlib
```
-----------------------------------------------------------------------------------------------------------------------------------------------

# Task 2 
## ✏️LaTeX Markdown & NumPy Stats

This task includes:

- A **Markdown cell** using LaTeX to explain the power rule:
  
$\frac{d}{dx}(x^n) = nx^{n-1}$
- A **NumPy script** to:
  - Generate 100 random numbers from a **normal distribution**
  - Compute their **mean** and **standard deviation**
  - ### 📸 Screenshot
  - <img width="401" height="54" alt="image" src="https://github.com/user-attachments/assets/17f36769-6438-4f27-9f51-0b50d45e751e" />


📎 *Basic stats practice using Python & math formula formatting with LaTeX.*
---

#  Task 3:
## 📉 Introduction to Cost Functions (MSE)

This task covers:

- A simple implementation of the **Mean Squared Error (MSE)** cost function
- Used two arrays: predictions and actual target values

🧮 MSE Formula:
\[
\text{MSE} = \frac{1}{n} \sum_{i=1}^{n} (y_{\text{pred}} - y_{\text{true}})^2
\]

Example:
- Predictions = [2.5, 0.0, 2.1, 7.8]  
- Targets = [3.0, -0.5, 2.0, 7.5]
### 📸 Screenshot
<img width="394" height="44" alt="image" src="https://github.com/user-attachments/assets/d0b40a3a-4968-40dc-9fe1-dca298d5600d" />

---
# Task 4:
## 🔁 Linear Regression with Gradient Descent

This task implements **gradient descent** to learn the parameters of a simple linear model:

> y = 2x + 1

---

## 📌 What It Does

- Generates synthetic data using `y = 2x + 1`
- Initializes weights (`w`) and bias (`b`) to zero
- Uses **gradient descent** to iteratively minimize the Mean Squared Error (MSE)
- Plots the learned regression line over the original data

---

## 📉 Output Visualization

- 🔵 Blue Dots: Original data points  
- 🔴 Red Line: Best fit line learned by gradient descent

### 📸 Screenshot  
<img width="790" height="490" alt="download" src="https://github.com/user-attachments/assets/f82a7186-c9dd-47dd-aed6-10cfa363063d" />


---
# Task 5:
# 🧠 Gradient Descent: Learning Rate Experiment

This notebook explores how different learning rates affect the performance of the gradient descent algorithm on a simple quadratic cost function.

---

## 📌 Function Definition

- Function:         `f(x) = x² + 1`  
- Derivative:        `f′(x) = 2x`  

---

## 🎯 Objective

Implement gradient descent for three different learning rates:

- `0.01` → slow convergence  
- `0.1` → optimal speed  
- `0.5` → unstable or diverging  

---

## 📊 Output Visualization

The plot compares how `x` changes over iterations under different learning rates:

- 🟦 Blue: Learning rate = 0.01  
- 🟧 Orange: Learning rate = 0.1  
- 🟥 Red: Learning rate = 0.5  

### 📸 Screenshot  
<img width="838" height="554" alt="download" src="https://github.com/user-attachments/assets/1d15e514-12d7-4040-bf28-410a2dcc8037" />



---


# Task 6
# 🧪 Tuple-based Hyperparameter Optimization in Linear Regression

This project demonstrates how to use Python tuples to pass multiple hyperparameters (learning rate, epochs) into a simple linear regression model, and determine which combination gives the best result using gradient descent.

---

## 🧠 What This Code Does

- Implements gradient descent for a line-fitting task (`y = 2x + 1`)
- Accepts different `(learning_rate, epochs)` combinations via tuples
- Tracks the cost (Mean Squared Error) for each combination
- Identifies the best performing tuple with the lowest cost
- Prints the best hyperparameters and final model weights

---

## 🔧 Example Hyperparameter Tuples

```python
hyperparams = [
    (0.001, 500),
    (0.01, 300),
    (0.1, 100),
    (0.05, 200),
    (0.2, 80)
]
```

---
# 🏠 Mini Project: House Price Prediction using Linear Regression

This mini-project combines multiple core concepts of optimization and machine learning using **NumPy** and **Matplotlib** — all implemented **from scratch**, without ML libraries.



---
# MINI PROJECT

## 🚀 What This Project Does

It simulates a **house price prediction** model using **linear regression**. The model learns the relationship between a house's **size** and its **price** through gradient descent.

---

## ✅ Concepts Applied

| Feature | Applied |
|--------|---------|
| 🔢 Data Generation (NumPy) | ✅ |
| 📊 Visualization (Subplots) | ✅ |
| 🧮 Cost Function (MSE) | ✅ |
| 🔁 Gradient Descent | ✅ |
| ⚙️ Learning Rate Tuning | ✅ |

---

## 🛠 How It Works

1. **Synthetic Data Generation**  
   `x = house sizes`, `y = prices` generated using NumPy with some random noise.

2. **Model Hypothesis**  
   We predict price using:  
   `ŷ = w * x + b`

3. **Cost Function (MSE)**  
   Measures average squared difference between predicted and actual prices.

4. **Gradient Descent**  
   We iteratively update weights to minimize the MSE.

5. **Learning Rate Experimentation**  
   Try values like `0.001`, `0.01`, `0.1`, and visualize convergence.

---

## 🖼 Output Graphs

Using subplots to visualize:
- Original Data vs Predictions  
- Cost vs Epochs

### 📸 Screenshot 
<img width="1390" height="490" alt="download" src="https://github.com/user-attachments/assets/742481d1-c1be-4bc0-9324-7baaea5dd507" />

