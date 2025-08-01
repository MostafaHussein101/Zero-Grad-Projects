
# 🧠 NumPy Assignments: Train-Test Split & Linear Regression from Scratch

This project includes two hands-on assignments using only **NumPy** — designed to reinforce core concepts in **Machine Learning** and **Linear Algebra** without relying on high-level libraries like `scikit-learn`.

---

## 📘 Contents

### 1️⃣ Assignment 1: Build Your Own `train_test_split_np()`

In real-world ML workflows, we split data into:
- **Training Set** — to train the model.
- **Test Set** — to evaluate generalization.

This notebook walks you through building a custom function:
```python
train_test_split_np(X, y, test_size=0.2, shuffle=True, seed=42)
```

#### ✅ Features
- Works just like `sklearn.model_selection.train_test_split`.
- Fully built using **NumPy**.
- Supports shuffling with optional seed for reproducibility.

---

### 2️⃣ Assignment 2: Linear Regression from Scratch

In this part, you'll implement a full **Linear Regression** model using:
- Normal Equation:  
  θ = (Xᵀ X)⁻¹ Xᵀ y
- Predictions made using:  
  y = θ₀ + θ₁ x

#### ✅ Features
- No use of `sklearn.linear_model.LinearRegression`.
- Uses the training/test split from Assignment 1.
- You build the pipeline manually: fitting, predicting, and evaluating.

---

## 🧪 Skills You’ll Practice

- NumPy slicing/indexing
- Data shuffling and reproducibility
- Matrix operations and algebra
- Linear regression theory and implementation
- Evaluating model performance

---

## 🚀 How to Use

1. Open the notebook: `Numpy_Assignments_R1024_286.ipynb`
2. Run the cells step-by-step in a Jupyter environment.
3. Modify parameters (like `test_size`, `shuffle`, `seed`) to experiment with different data splits and regression outputs.

---

## 📦 Dependencies

- Python 3.x
- NumPy

Install using:
```bash
pip install numpy
```

---

## 💡 Educational Value

These assignments are ideal for:
- Students learning ML from the ground up
- Developers transitioning from high-level libraries to understanding fundamentals
- Interview prep or bootcamp reinforcement

---
