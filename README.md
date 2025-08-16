# 🧳 Holiday Package Prediction  

This project predicts whether a customer will purchase a holiday package based on their demographic and behavioral data. It uses **machine learning techniques** to analyze patterns in customer features and classify their likelihood of purchasing.   

---

## 📊 Dataset
The dataset contains customer-related features such as:  
- **Age**  
- **Gender**  
- **Occupation**  
- **Monthly Income**  
- **Number of Trips Taken**  
- **Preferred Destinations**  
- **Past Package Purchase**  

The target variable is whether the customer will purchase a **Holiday Package**.  

---

## ⚙️ Steps in the Notebook
1. **Data Loading & Cleaning**  
   - Imported dataset and handled missing values.  
   - Encoded categorical features.  

2. **Exploratory Data Analysis (EDA)**  
   - Visualized customer distribution (age, income, gender, etc.).  
   - Found correlations between features and target variable.  

3. **Feature Engineering**  
   - Normalization and scaling of numerical features.  
   - Label encoding for categorical variables.  

4. **Model Training**  
   Implemented and compared multiple machine learning models:  
   - Logistic Regression  
   - Decision Tree  
   - Random Forest  
   - Gradient Boosting / XGBoost  

5. **Model Evaluation**  
   - Accuracy, Precision, Recall, F1-score  
   - Confusion Matrix  
   - ROC Curve & AUC  

---

## 🚀 Results
- The best performing model was **XGBoost**.  
- Achieved an accuracy of **95%** on test data.  
- Model can be used to identify customers most likely to buy holiday packages.  

---

## 🛠️ Technologies Used
- Python  
- Pandas, NumPy  
- Matplotlib, Seaborn  
- Scikit-learn / XGBoost 
- Jupyter Notebook  

---

  
