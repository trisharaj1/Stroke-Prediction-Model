# Stroke-Prediction-Model
This project explores how machine learning can help predict the risk of stroke based on patient health information. I cleaned and prepared the data, balanced it so the models could learn from both classes fairly, and then tested a few different algorithms to see which performed best. In the end Linear Discriminant Analysis worked the best (83.7% ROC-AUC Score)

**What I Did**

Preprocessing – Filled in missing values, normalized numeric features, and one-hot encoded categories.

Balancing the data – Used SMOTE to handle the big class imbalance.

Tried different models – Logistic Regression, Linear Discriminant Analysis, and Random Forest.

Evaluation – Compared models using ROC-AUC with repeated cross-validation to get reliable results.

**Why This Matters**

Strokes can be life-threatening, and early prediction helps doctors make better decisions. While this model isn’t a replacement for medical advice, it’s a step toward using data science in healthcare.

**How to Use**

Clone the repo.

Install the requirements.

Run the notebook to see the data processing, model training, and evaluation steps.
