Supervised Machine Learning Model Comparison & Optimization

📖 Project Overview
This project focuses on building and comparing multiple supervised learning classification models to identify the most accurate model for the given dataset. The models are trained, evaluated, and optimized using hyperparameter tuning to achieve the best performance.

🧠 Models Implemented
The following machine learning algorithms were implemented and evaluated:
Logistic Regression
K-Nearest Neighbors (KNN)
Decision Tree
Random Forest
Support Vector Machine (SVM)
Each model was trained on the training dataset and evaluated using accuracy as the primary metric.

🔍 Model Evaluation & Comparison
After initial evaluation, Support Vector Machine (SVM) achieved the highest accuracy among the baseline models.
To further improve performance, hyperparameter optimization was applied, especially on ensemble models.

⚙️ Hyperparameter Optimization
GridSearchCV was used to tune the Random Forest model, resulting in the following optimal configuration:
Best Random Forest Parameters:
{
  'max_depth': 5,
  'min_samples_leaf': 2,
  'min_samples_split': 2,
  'n_estimators': 200
}
Best Accuracy Achieved:
📈 0.7957
After tuning, Random Forest outperformed all other models, including SVM.

🏆 Final Conclusion
SVM performed best among untuned models
After optimization, Random Forest achieved the highest accuracy overall
Hyperparameter tuning significantly improved model performance

🛠️ Tools & Technologies Used
Python
Scikit-learn
Pandas
NumPy
Jupyter Notebook

📂 Project Structure
Data preprocessing
Model training & evaluation
Hyperparameter tuning using GridSearchCV
Performance comparison and final model selection
