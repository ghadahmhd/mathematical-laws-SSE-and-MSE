# Mathematical Laws: SSE & MSE

This repository focuses on the mathematical implementation and analysis of two important error laws used in Machine Learning:

1. Sum of Squared Errors (SSE)
2. Mean Squared Error (MSE)

The project demonstrates how these two formulas are derived, implemented, and applied in practical scenarios.

---

## 📐 The Two Laws Explained

### 1️⃣ Sum of Squared Errors (SSE)

SSE measures the total squared distance between data points and their assigned cluster centroids.

Formula:

SSE = Σ || xᵢ − c ||²

Where:
- xᵢ = data point
- c = centroid
- || · ||² = squared Euclidean distance

SSE is mainly used in clustering (e.g., K-Means) to evaluate how compact the clusters are.

---

### 2️⃣ Mean Squared Error (MSE)

MSE measures the average squared difference between predicted and actual values.

Formula:

MSE = (1/n) Σ (yᵢ − ŷᵢ)²

Where:
- yᵢ = actual value
- ŷᵢ = predicted value
- n = number of samples

MSE is widely used to evaluate regression models.

---

## 📂 Files in This Repository

- `ghada_SSE.ipynb`  
  → Implementation and calculation of SSE in clustering.

- `ghada_MSE.ipynb`  
  → Implementation and calculation of MSE for error analysis.

---

## 🧠 Key Concepts

- Squared error
- Euclidean distance
- Model evaluation
- Clustering quality
- Loss functions

---

## 🛠️ Tools Used

- Python
- NumPy
- scikit-learn
- Matplotlib

---

## 🚀 How to Run

1. Open the notebooks in Google Colab or Jupyter Notebook.
2. Install required libraries if needed:

   pip install numpy scikit-learn matplotlib

3. Run all cells step by step.

---

## 🎯 Purpose

This project was developed to understand the mathematical foundation of error measurement in Machine Learning and how these two laws affect model performance.
