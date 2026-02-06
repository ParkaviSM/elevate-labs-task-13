# elevate-labs-task-13# Dimensionality Reduction using Principal Component Analysis (PCA)

---

### 📌 Project Overview
This project demonstrates the use of **Principal Component Analysis (PCA)** for
dimensionality reduction on a high-dimensional dataset. The objective of this
task is to reduce the number of features while preserving the maximum amount
of information (variance) and to analyze the impact of PCA on model performance.

PCA helps in simplifying datasets, improving computational efficiency, and
reducing noise without significant loss of information.

---


**Dataset Description:**
- Each row represents a handwritten digit image
- First column: digit label (0–9)
- Remaining 784 columns: pixel intensity values
- High dimensionality makes this dataset ideal for PCA

---

### 🛠 Tools & Libraries Used
- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- Jupyter Notebook / VS Code

---

### 🔄 Workflow
1. Loaded the MNIST dataset from CSV file
2. Separated features and target labels
3. Applied feature scaling using `StandardScaler`
4. Performed PCA with different numbers of components
5. Analyzed explained variance for dimensionality reduction
6. Plotted cumulative explained variance
7. Reduced the dataset using optimal PCA components
8. Compared model accuracy before and after PCA
9. Visualized the data in 2D using PCA
10. Interpreted results and impact of dimensionality reduction

---

### 📈 Analysis & Visualizations
The following analyses were performed:
- Explained variance for multiple PCA components
- Cumulative explained variance plot
- Comparison of classification accuracy with and without PCA
- 2D visualization of high-dimensional data after PCA

These visualizations help in understanding how PCA compresses data while
retaining important patterns.

---

### ✅ Results
- PCA significantly reduced the number of features (784 → fewer components)
- Most of the variance was retained using a smaller number of components
- Classification accuracy with PCA was comparable to the original dataset
- PCA successfully simplified the dataset without major performance loss

---

### 🎯 Conclusion
Principal Component Analysis is an effective dimensionality reduction technique
for high-dimensional datasets. By reducing the number of features, PCA improves
computational efficiency while maintaining similar model performance. This task
highlights the importance of feature scaling, variance analysis, and visualization
in dimensionality reduction.

---

### 📚 Learning Outcomes
- Understanding dimensionality reduction
- Importance of feature scaling for PCA
- Explained variance and cumulative variance concepts
- Performance comparison before and after PCA
- Practical application of PCA on real-world datasets

---

