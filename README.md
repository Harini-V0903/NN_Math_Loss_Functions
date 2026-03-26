# NN_Math_Loss_Functions(NN_Math)
# 📊 Neural Network Loss Functions (NN_Math)

---

##  Introduction

A **loss function** measures the difference between actual and predicted values, guiding the model to improve during training.

---

##  Objective

* Understand various loss functions
  
* Learn their purpose and usage

---

## 📚 Loss Functions

### 🔷 MSE (Mean Squared Error)

    * **What:** Measures error with higher penalty for large mistakes
    
    * **Why:** Encourages the model to minimize significant errors
    
    * **Use:** Regression

---

### 🔷 MAE (Mean Absolute Error)

    * **What:** Measures average error equally
    
    * **Why:** Provides stable results, less sensitive to outliers
    
    * **Use:** Regression

---

### 🔷 Binary Crossentropy
    
    * **What:** Evaluates error for two-class predictions
    
    * **Why:** Works effectively with probability outputs
    
    * **Use:** Binary classification

---

### 🔷 Categorical Crossentropy

* **What:** Used for multi-class problems with one-hot labels
* **Why:** Helps the model identify the correct class accurately
* **Use:** Multi-class classification

---

### 🔷 Sparse Categorical Crossentropy

    * **What:** Similar to categorical crossentropy using integer labels
    
    * **Why:** More efficient and simpler to implement
    
    * **Use:** Multi-class classification

---

## Key Insight

Selecting the appropriate loss function is essential for better model performance.

---


