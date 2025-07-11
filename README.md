# 🔢 Digit Classification with Naïve Bayes (MNIST Subset)

This project focuses on binary classification of handwritten digits (0 vs 1) from the MNIST dataset using a **custom Naïve Bayes classifier** — no libraries like `scikit-learn` were used for modeling.

---

## 🎯 Goal

To implement Gaussian Naïve Bayes from scratch and classify images of digits "0" and "1" using two simple features:
- **Average brightness**
- **Standard deviation of brightness**

---

## 📌 Key Steps

### 🧩 Feature Engineering
- Each image (28×28) is converted to 2D data:
  - Feature 1: Average pixel intensity
  - Feature 2: Standard deviation of pixel intensity

### 📐 Parameter Estimation
- Estimated class-wise means and variances for each feature (digit 0 and digit 1)
- Assumed independent Gaussian distributions

### 🧠 Classification
- Implemented likelihood-based prediction using Gaussian PDF
- Used maximum likelihood for class decision

### 📊 Accuracy
- **Digit 0 Test Set Accuracy**: ~94.7%  
- **Digit 1 Test Set Accuracy**: ~95.8%

🧠 Learning Outcomes
 - Hands-on understanding of Naïve Bayes and probability theory
 - Feature design and statistical thinking
 - Modeling without ML libraries — pure NumPy & math!
  

