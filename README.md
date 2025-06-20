# Heart-Disease-Cleveland-UCI
Machine Learning project for heart disease prediction using SVM, Random Forest, and Gradient Boosting. Includes model comparison, evaluation metrics, and healthcare insights using the Cleveland Heart Disease dataset.
# Heart Disease Prediction using Machine Learning

This project uses supervised machine learning models to predict the presence of heart disease based on patient health data. It is built using the Cleveland Heart Disease dataset and focuses on comparing the performance of three models: **Support Vector Machine (SVM)**, **Random Forest Classifier**, and **Gradient Boosting Classifier**.

## Project Overview

Heart disease remains a leading cause of death globally. Early prediction using machine learning can assist in timely diagnosis and preventive care. This notebook demonstrates how data-driven approaches can be used to classify patients as high or low risk for heart disease.

## Files

- `Heart_Disease_Prediction.ipynb`: Jupyter Notebook with complete implementation, from data loading to model evaluation.

## Models Used

- **Support Vector Machine (SVM)**
- **Random Forest Classifier**
- **Gradient Boosting Classifier**

Each model was evaluated based on:
- Accuracy
- Precision
- Recall (Sensitivity)
- F1 Score
- ROC-AUC Score

## Summary of Findings

- **Gradient Boosting** outperformed other models with the highest ROC-AUC (~0.94) and Recall, making it suitable for medical diagnostics where minimizing false negatives is critical.
- **Random Forest** also performed strongly due to its ensemble nature and robustness to overfitting.
- **SVM** worked well but had slightly lower recall, which is a drawback in healthcare prediction contexts.

## Technologies Used

- Python
- scikit-learn
- pandas, NumPy
- seaborn, matplotlib

## Dataset

- Cleveland Heart Disease dataset (UCI Repository)
- https://archive.ics.uci.edu/ml/datasets/heart+disease

## How to Use

1. Clone this repository:
   git clone https://github.com/yourusername/heart-disease-prediction.git
   cd heart-disease-prediction

2. Open the notebook:
   jupyter notebook Heart_Disease_Prediction.ipynb

3. Run the cells to explore the data, train the models, and evaluate performance.

## References

- Breiman, L. (2001). Random forests. Machine Learning, 45(1), 5–32. https://doi.org/10.1023/A:1010933404324  
- Cortes, C., & Vapnik, V. (1995). Support-vector networks. Machine Learning, 20(3), 273–297. https://doi.org/10.1007/BF00994018  
- Natekin, A., & Knoll, A. (2013). Gradient boosting machines, a tutorial. Frontiers in Neurorobotics, 7, 21. https://doi.org/10.3389/fnbot.2013.00021  
- Detrano, R., et al. (1989). International application of a new probability algorithm for the diagnosis of coronary artery disease. The American Journal of Cardiology, 64(5), 304-310. https://doi.org/10.1016/0002-9149(89)90524-9  

