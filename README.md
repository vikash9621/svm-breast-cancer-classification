# Support Vector Machines (SVM) - Breast Cancer Dataset

## 🎯 Objective
Train and evaluate Support Vector Machines using linear and RBF kernels on the Breast Cancer dataset. Tune hyperparameters and visualize decision boundaries.

## 📁 Dataset
- [Breast Cancer Dataset - Kaggle](https://www.kaggle.com/datasets/yasserh/breast-cancer-dataset)
- Target: Binary classification (malignant/benign)

## ⚙️ Tools Used
- Python, Scikit-learn, NumPy, Pandas, Matplotlib, Seaborn

## 🔧 Steps Performed
- Loaded dataset and normalized features
- Trained SVM with linear and RBF kernels
- Evaluated models with accuracy and confusion matrix
- Tuned C and gamma using GridSearchCV
- Visualized 2D decision boundary with PCA

## 📊 Results

| Model         | Accuracy |
|---------------|----------|
| Linear Kernel | 96.49%   |
| RBF Kernel    | 97.37%   |
| Best Tuned RBF | 98.24%  |
| Cross-Val Score | ~97.5% |

## 🧠 Interview Prep
- What is a support vector?
- Role of C and gamma
- Linear vs RBF kernel
- How SVM handles non-linearly separable data
- Kernel trick and margin maximization
