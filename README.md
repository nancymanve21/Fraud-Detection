# 📊 Supervised Machine Learning Model Comparison & Optimization

## 📌 Project Description
This project focuses on building, evaluating, and comparing multiple **supervised machine learning classification models** to determine the most effective algorithm for the given dataset. The study also includes **hyperparameter tuning** to enhance model performance and select the optimal model.

---

## 🎯 Objectives
- Implement multiple supervised learning algorithms  
- Compare model performance using accuracy  
- Perform hyperparameter tuning to improve results  
- Identify the best-performing model  

---

## 🧠 Algorithms Implemented
The following machine learning models were trained and evaluated:

- Logistic Regression  
- K-Nearest Neighbors (KNN)  
- Decision Tree  
- Random Forest  
- Support Vector Machine (SVM)  

---

## 🔍 Model Evaluation
- All models were trained on the training dataset  
- Accuracy was used as the primary evaluation metric  
- Among baseline models, **Support Vector Machine (SVM)** achieved the highest accuracy  

---

## ⚙️ Hyperparameter Optimization
To further improve model performance, **GridSearchCV** was applied to tune the Random Forest classifier.

### Best Random Forest Parameters
{
  'max_depth': 5,
  'min_samples_leaf': 2,
  'min_samples_split': 2,
  'n_estimators': 200
}

## 📈 Best Accuracy Achieved
📊 **Accuracy:** **0.7957**

After hyperparameter optimization, the **Random Forest model outperformed all other models**, including Support Vector Machine (SVM).

---

## 🏆 Results & Conclusion
- SVM performed best among the untuned baseline models  
- Hyperparameter tuning significantly improved model performance  
- Optimized Random Forest achieved the highest overall accuracy  
- Random Forest was selected as the **final best-performing model**  

---

## 🛠️ Tools & Technologies
- Python  
- Scikit-learn  
- Pandas  
- NumPy  
- Jupyter Notebook  

---

## 📂 Project Workflow
- Data preprocessing  
- Model training and evaluation  
- Hyperparameter tuning using GridSearchCV  
- Model comparison and final model selection  

---

## 🎯 Final Outcome
The optimized **Random Forest classifier** achieved an accuracy of **79.57%**, making it the **best-performing model** in this project.

