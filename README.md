# Student Performance Prediction – Machine Learning Project

## 📝 Description  
A machine learning project predicting student performance using regression and classification models. Includes data preprocessing, feature engineering, model evaluation, and insights through visualization to identify key factors influencing academic outcomes.

---

## 📖 Overview  
This project analyzes student academic performance using both **regression** (score prediction) and **classification** (pass/fail prediction).  
It includes data preparation, model optimization, visualization, and performance comparison across multiple ML algorithms.

---

## 🎯 Objectives  
- Predict Math, Reading, and Writing scores  
- Classify students into Pass/Fail categories  
- Identify influential socio-economic and educational factors  
- Provide visual insights through Tableau and ML evaluation metrics  

---

## 📁 Dataset  
The dataset used in this project comes from Kaggle:  
🔗 **Students Performance in Exams Dataset**  
https://www.kaggle.com/datasets/spscientist/students-performance-in-exams

---

## 🔧 Methodology  

### **1. Data Preparation**
- Handling missing values  
- Outlier treatment  
- Feature engineering (verbal score, pass/fail label)  
- Encoding methods (Label, One-Hot, Ordinal)  
- Standardization (StandardScaler)  
- Train/Test split  

### **2. Regression Models**
- SVR  
- Random Forest Regressor  
- Gradient Boosting Regressor  
- XGBoost Regressor  
- KNN Regressor  
- Decision Tree Regressor  

### **3. Classification Models**
- KNN  
- SVC  
- Decision Tree  
- Logistic Regression  
- Random Forest  
- AdaBoost  
- Naive Bayes  
- XGBoost  
- MLP Classifier  

### **4. Advanced Techniques**
- PCA (Dimensionality Reduction)  
- Feature Selection (Random Forest importance)  
- Class Imbalance Handling (SMOTE, ADASYN, SMOTE-TOMEK)  
- Hyperparameter Tuning (GridSearchCV)  

---

## 📊 Results  

### **🔍 WandB Classification Report**  
Complete classification evaluation available on Weights & Biases:  
🔗 **https://wandb.ai/mohammedbardaoui88-ensaj/ML_Classification/reports/ML_classification_student_performance--VmlldzoxMzAzMTQzOA?accessToken=ql9nu9qo54ursgjql9avzd4u10umwzt9urnzlernowcp0dfahwkw8hfri64ylduj**


---

## 📈 Tableau Dashboard  
Interactive dashboard visualizing performance trends:  
🔗 **https://public.tableau.com/app/profile/ossama.ettaqafi/viz/VisutalisationProjectML2_v2024_3/Dashboard**

---

## 📁 Project Structure
Student_Performance_Project/
│
├── data_preparation/
│ ├── data/ # Raw dataset
│ └── data_preparation.ipynb
│
├── regression/
│ ├── data/ # Data prepared for regression
│ └── regression_models.ipynb
│
└── classification/
├── data/ # Data prepared for classification
└── classification_models.ipynb


---

## 🚀 Getting Started  
No installation required — the project runs entirely in Jupyter Notebook.

1. Open the **data_preparation** notebook  
2. Explore and clean the dataset  
3. Run the **regression** and **classification** notebooks  
4. Compare results and explore visual dashboards  

---

## 👥 Contributors  
- **BARDAOUI Mohammed** 
- **Ariri Abdelaziz**  
- **Ettaqafi Ossama**  
- **El Attar Fahd**  
