# K-Nearest Neighbors (KNN) Classifier - Machine Learning Project

This project implements a **K-Nearest Neighbors (KNN)** classification pipeline on a random dataset. It demonstrates data pre-processing, hyperparameter optimization, and detailed model evaluation techniques.

## 🚀 Key Features & Workflow
- **Libraries Used:** Pandas, NumPy, Scikit-Learn, Matplotlib, and Seaborn.
- **Hyperparameter Tuning:** Conducted an exhaustive search via `GridSearchCV` to find the optimal combination of `n_neighbors` (range 1-50) and `weights` ('uniform' vs 'distance').
- **Model Evaluation:** Utilized robust evaluation metrics, including:
  - Confusion Matrix (`ConfusionMatrixDisplay` with 'magma' colormap)
  - Full `classification_report` (Precision, Recall, F1-Score per class).

## 📊 Key Results
- **Optimized Framework:** The Grid Search evaluated the best standard model setup through cross-validation.
- **High Performance:** The tuned model achieved a high test accuracy of **96%**, demonstrating balanced precision and recall across all target classes.

## 🛠️ How to Run
1. Clone the repository:
   ```bash
   git clone [https://github.com/YOUR_USERNAME/YOUR_REPOSITORY_NAME.git](https://github.com/YOUR_USERNAME/YOUR_REPOSITORY_NAME.git)
