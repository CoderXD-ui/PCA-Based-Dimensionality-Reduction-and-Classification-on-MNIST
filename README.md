# PCA-Based Dimensionality Reduction and Classification on MNIST

This project investigates Principal Component Analysis (PCA) on the
MNIST dataset to study:

-   📈 Variance distribution in high-dimensional image space
-   🎯 Effect of dimensionality reduction on classification accuracy
-   🖼️ Reconstruction quality after compression
-   🔎 Residual structure using secondary (Residual) PCA

Full mathematical derivations and detailed explanations are provided in
the documentation PDF.

------------------------------------------------------------------------

## 📂 Dataset

-   MNIST handwritten digits
-   70,000 images (28×28 grayscale)
-   784 features per sample
-   10 digit classes (0--9)

------------------------------------------------------------------------

## 🚀 Pipeline Overview

1.  Data loading (OpenML MNIST)
2.  Standardization
3.  PCA decomposition
4.  Variance & scree analysis
5.  Logistic Regression on reduced space
6.  Reconstruction analysis
7.  Residual computation
8.  Residual PCA

------------------------------------------------------------------------

## 🛠 Tech Stack

-   Python
-   NumPy
-   Pandas
-   Matplotlib
-   Scikit-learn

------------------------------------------------------------------------

## 📁 Repository Structure

│── full_pipeline.ipynb\
│── Documentation.pdf\
│── README.md

------------------------------------------------------------------------

## 📌 Key Results

-   PC1 explains **5.64%** variance
-   149 components retain **80%** variance
-   330 components retain **95%** variance
-   Classification accuracy stabilizes near **K ≈ 250**
