# 🩺 Breast Cancer Prediction using Logistic Regression

A Machine Learning classification project that predicts whether a tumor is **Benign** or **Malignant** using **Logistic Regression**.  
This project demonstrates a complete end-to-end supervised learning pipeline including preprocessing, model training, evaluation, and cross-validation.

---

## 📌 Project Overview

Breast cancer is one of the most common cancers worldwide. Early detection can significantly improve treatment outcomes.  
This project uses clinical tumor feature data to classify cancer diagnosis into:

- ✅ **Benign (0)** — Non-cancerous tumor  
- ❌ **Malignant (1)** — Cancerous tumor  

The model is trained using **Logistic Regression**, a widely used algorithm for binary classification problems.

---

## 🧠 Machine Learning Workflow

The project follows a structured ML pipeline:

1. **Load Dataset** (`breast_cancer.csv`)
2. **Data Cleaning**
   - Check for missing values
3. **Feature Selection**
   - Separate independent variables (features) and target label
4. **Train-Test Split**
   - 80% Training, 20% Testing
5. **Feature Scaling**
   - Standardization using `StandardScaler`
6. **Model Training**
   - Logistic Regression classifier
7. **Prediction**
   - Predict tumor class on test data
8. **Evaluation**
   - Confusion Matrix
   - Accuracy Score
   - Classification Report
9. **Cross Validation**
   - 10-Fold Cross Validation for stability

---

## 🚀 Key Features

- ✅ End-to-End Breast Cancer Classification Pipeline  
- ⚙️ Feature Scaling with StandardScaler  
- 📊 Model Evaluation using Confusion Matrix and Accuracy  
- 🔁 Cross Validation for reliable performance measurement  
- 🧾 Clean and beginner-friendly implementation  

---

## 📂 Dataset Information

The dataset contains tumor-related measurements and diagnosis labels.

- **File:** `breast_cancer.csv`
- **Target Column:** Diagnosis (0 or 1)
- **Features:** Multiple numerical clinical attributes

---

## 📊 Model Performance

The Logistic Regression classifier achieves strong performance:

- **Test Accuracy:** ~96%  
- **Cross Validation Accuracy:** ~95% – 97%  
- **Model Type:** Discriminative Linear Classifier  

This makes Logistic Regression an effective baseline model for breast cancer detection.

---

## 🛠️ Technologies Used

- **Python** — Core programming language  
- **Pandas & NumPy** — Data handling and preprocessing  
- **Scikit-learn** — Model building, scaling, evaluation  
- **Matplotlib (optional)** — Visualization support  

---

## ⚙️ Installation & Setup

### Clone the repository

```bash
git clone https://github.com/addsnag/Breast-Cancer-Prediction.git
cd Breast-Cancer-Prediction
```

### Install required dependencies

```bash
pip install -r requirements.txt
```

### Run the Notebook

```bash
jupyter notebook breast_cancer.ipynb
```

---

## 🔮 Future Enhancements

- [ ] Try advanced models like **SVM**, **Random Forest**, or **XGBoost**
- [ ] Add feature importance visualization
- [ ] Deploy the model using **Streamlit** or **Flask**
- [ ] Experiment with Deep Learning models for improved performance

---

## ⭐ Support

If you found this project useful, consider giving the repository a ⭐ on GitHub!
