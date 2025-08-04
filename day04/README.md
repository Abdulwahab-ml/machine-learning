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
