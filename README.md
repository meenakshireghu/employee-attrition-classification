# Employee Attrition Classification
This project uses machine learning techniques to predict employee attrition based on a Kaggle dataset. By applying various models such as Logistic Regression, Random Forest, SVM, and AdaBoost, the goal is to accurately classify employees at risk of leaving based on key attributes.
## Project Overview
The project utilizes Kaggle’s Employee Attrition dataset and applies various machine learning algorithms to predict whether an employee will leave the company. The main techniques used in this project include:

- **Predictive Modeling:** Logistic Regression, Random Forest, Support Vector Machine (SVM), and AdaBoost Classifier.
- **Hyperparameter Tuning:** GridSearchCV was applied to tune the Random Forest and SVM models for optimal performance.
- **Dimensionality Reduction:** Principal Component Analysis (PCA) was used to reduce the feature space and improve the performance of the models.
- **Model Comparison:** Multiple models were compared to evaluate their accuracy.

## Model Performance

The following models were trained and evaluated:

| Model                  | Accuracy Score  | Methodology               |
|------------------------|-----------------|---------------------------|
| Logistic Regression     | 0.903790        | Base Model                |
| Random Forest Classifier| 0.982507        | GridSearchCV & PCA        |
| Support Vector Machine  | 0.862974        | GridSearchCV              |
| AdaBoost Classifier     | 0.906706        | Base Model                |


## Key Techniques and Tools

- **Machine Learning Algorithms:** Logistic Regression, Random Forest, Support Vector Machine (SVM), AdaBoost Classifier.
- **Dimensionality Reduction:** PCA (Principal Component Analysis) to enhance model performance.
- **Hyperparameter Tuning:** GridSearchCV to optimize Random Forest and SVM.
- **Data Analysis Libraries:** Pandas, NumPy for data manipulation and preprocessing.
- **Visualization Libraries:** Matplotlib, Seaborn for visualizing results and model performance.
