# SVM & SVR — From Scratch to Practical Implementation

Hands-on implementation of Support Vector Machines, built while learning the algorithm from the ground up — from basic classification to kernel intuition to regression on a real dataset.

## 📒 Notebooks

| Notebook | What it covers |
|---|---|
| [`Basic_SVC_Implementation.ipynb`](./Basic_SVC_Implementation.ipynb) | Support Vector Classifier on synthetic data — comparing linear, RBF, polynomial, and sigmoid kernels, plus hyperparameter tuning with `GridSearchCV` |
| [`SVM_Kernels_Implementation.ipynb`](./SVM_Kernels_Implementation.ipynb) | In-depth intuition for the kernel trick — visualizing how non-linearly separable data (e.g. concentric circles) becomes separable in higher dimensions |
| [`Support_Vector_Regression_Implementation.ipynb`](./Support_Vector_Regression_Implementation.ipynb) | SVR applied to the Tips dataset — feature encoding (label + one-hot), model training, and hyperparameter tuning |

## 🧠 Key concepts practiced

- Support Vector Classification with multiple kernels (linear, RBF, poly, sigmoid)
- The kernel trick — mapping non-linear data into higher-dimensional space
- Support Vector Regression on real-world tabular data
- Feature encoding pipelines (LabelEncoder, OneHotEncoder, ColumnTransformer)
- Hyperparameter tuning via GridSearchCV
- Model evaluation (classification report, confusion matrix, R², MAE)

## 🛠️ Tools

Python · scikit-learn · pandas · NumPy · seaborn · matplotlib · plotly

## 📌 Why this repo

Built as part of my daily machine learning practice — documenting concepts as I learn them, with a focus on intuition first, code second.

---
⭐ Feel free to explore, fork, or reach out if you spot something worth discussing!
