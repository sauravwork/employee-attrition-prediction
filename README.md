# Employee Attrition Prediction

This project predicts whether an employee will leave the company using machine learning models.  
The dataset used is **IBM HR Analytics Employee Attrition**.

---

## 📖 Description
Employee attrition is a major challenge for organizations. Using employee data such as job role, salary, years at company, and work-life balance, this project applies **machine learning** to predict the likelihood of attrition.

---

## 🚀 Project Workflow
1. **Data Preprocessing**  
   - Encoded categorical features  
   - Handled class imbalance  
   - Scaled numerical features  

2. **EDA (Exploratory Data Analysis)**  
   - Visualized attrition trends  
   - Plotted correlations  
   - Checked feature importance  

3. **Modeling**  
   - Logistic Regression  
   - Random Forest  
   - XGBoost  

4. **Evaluation**  
   - Accuracy, Precision, Recall, F1-score  
   - ROC-AUC Curve  

---

## 📊 Dataset
- File: `WA_Fn-UseC_-HR-Employee-Attrition.csv`  
- Source: [IBM HR Analytics Dataset on Kaggle](https://www.kaggle.com/pavansubhasht/ibm-hr-analytics-attrition-dataset)

---

## 🛠️ Tech Stack
- Python (pandas, numpy, matplotlib, seaborn)  
- scikit-learn (ML models, evaluation)  
- XGBoost  
- Jupyter Notebook  

---

## 📌 How to Run
```bash
# Clone the repo
git clone https://github.com/sauravwork/employee-attrition-prediction.git

# Go into the project folder
cd employee-attrition-prediction

# Install dependencies
pip install -r requirements.txt

# Run Jupyter Notebook
jupyter notebook notebooks/EDA_and_Modeling.ipynb
