# 🧠 SVM Binary Classification - Breast Cancer Dataset

This project uses Support Vector Machines (SVM) to perform binary classification on a breast cancer dataset. It compares linear and RBF kernels, visualizes decision boundaries, and tunes hyperparameters using GridSearchCV and cross-validation.

---

## 📊 Dataset

- **Name**: Breast Cancer Dataset  
- **Target Classes**: Benign (0) and Malignant (1)  
- **Source**: UCI Machine Learning Repository or similar CSV

---

## 🔧 Features & Workflow

- Data cleaning and preprocessing  
- Normalization using `StandardScaler`  
- Binary encoding of target labels (`LabelEncoder`)  
- SVM training with:  
  - Linear kernel  
  - RBF kernel  
- PCA for 2D visualization of decision boundaries  
- Evaluation metrics:  
  - Confusion Matrix  
  - Classification Report  
  - Accuracy Score  
- Hyperparameter tuning with `GridSearchCV`  
- Cross-validation for robustness  

---

## 🚀 How to Run

1. Clone this repo or download the files.  
2. Install the required Python packages:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn

