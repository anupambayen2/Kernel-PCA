Project Summary: Non-Linear Dimensionality Reduction Using Kernel PCA

This project applies Kernel Principal Component Analysis (Kernel PCA) to perform non-linear dimensionality reduction on the Wine dataset. It is part of my daily machine learning practice uploads on GitHub.

📌 Objective

To reduce high-dimensional data into a lower-dimensional space while capturing non-linear relationships that standard PCA cannot model.

📊 Dataset

Dataset used: Wine.csv

Contains multiple numerical chemical features of wine

Target variable represents different wine classes

Suitable for testing both linear and non-linear dimensionality reduction techniques

🛠️ Technique Used
Kernel PCA

Extension of PCA using kernel functions

Maps data into a higher-dimensional space before performing PCA

Common kernels used:

RBF (Gaussian)

Polynomial

Sigmoid

Kernel PCA is especially useful when data is not linearly separable.

🛠️ Steps Performed

Loaded and standardized the dataset

Applied Kernel PCA with a non-linear kernel

Reduced the dataset to two principal components

Trained a classification model on the transformed data

Visualized class separation in reduced dimensions

📈 Key Insight

Kernel PCA captures complex, curved data structures.

Provides better class separation than linear PCA when relationships are non-linear.

Improves visualization and classification performance in certain cases.

🧪 Outputs

Non-linearly transformed feature set

2D visualization of wine classes

Improved class separability

🚀 Conclusion

Kernel PCA is a powerful dimensionality reduction technique for non-linear datasets. This project demonstrates how kernel methods can uncover hidden patterns that linear PCA fails to capture, making it valuable for complex real-world data.
