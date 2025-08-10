#  Employee Attrition Analysis

This project analyzes HR data from Salifort Motors to uncover key drivers of employee attrition and predict the likelihood of turnover. Using data-driven techniques, it provides actionable insights to support strategic HR decisions aimed at improving employee satisfaction and retention.

---

## 📌 Key Objectives
- Identify key factors contributing to employee resignation  
- Build a predictive model to forecast attrition  
- Generate interpretable insights to guide HR policy decisions  

---

## 🛠️ Tools & Techniques
- **Languages/Libraries**: Python, Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn  
- **Methods**: Exploratory Data Analysis (EDA), Correlation Analysis, Feature Engineering  
- **Models**: Logistic Regression, Decision Tree, Random Forest  
- **Evaluation**: Accuracy, Confusion Matrix, ROC-AUC Score  

---

## 👥 Stakeholders
- HR Department  
- Department Heads  
- Executive Management  

---

## 📁 Dataset Overview
- ~15,000 employee records  
- Features include satisfaction level, performance evaluation, number of projects, average monthly hours, time at company, promotions, department, salary level  

---

## ⚖️ Ethical Considerations
- Developed with transparency and fairness in mind  
- Aimed to support retention strategies—not individual targeting  
- Ensured interpretability and stakeholder awareness  

---

## ✅ Results & Conclusions
- **Key attrition indicators**:
  - Low satisfaction level
  - High workload (avg. monthly hours)
  - Lack of recent promotion
  - Lower salary level

- **Best Model**: Random Forest Classifier  
  - **Precision**: ~99%  
  - **ROC-AUC Score**: 0.9785 

- **Recommendations**:
  - Enhance employee satisfaction initiatives  
  - Monitor and balance workloads  
  - Improve promotion and compensation structures  
  
  
  **Major Issue** 
  - Since the recall and accuracy is much higher than industry standards the model is prone to overfit and cannot generalise well for the data it hasn't seen 
---


