# Diabetes Prediction using Decision Tree Classifier

## 📌 Project Overview

This project uses the **Decision Tree Classification** algorithm to predict whether a patient is diabetic based on various medical diagnostic measurements.

The model is trained on the **Pima Indians Diabetes Dataset**, a widely used dataset for binary classification problems in machine learning.

---

## 🎯 Objective

The primary objective of this project is to:

- Predict whether a patient has diabetes.
- Train a Decision Tree Classification model.
- Evaluate the model's performance using classification metrics.
- Visualize the decision tree for better interpretability.

---

## 📂 Dataset

**Dataset:** Pima Indians Diabetes Dataset

### Features

| Feature | Description |
|---------|-------------|
| Pregnancies | Number of pregnancies |
| Glucose | Plasma glucose concentration |
| BloodPressure | Diastolic blood pressure (mm Hg) |
| SkinThickness | Triceps skin fold thickness (mm) |
| Insulin | 2-Hour serum insulin (mu U/ml) |
| BMI | Body Mass Index |
| DiabetesPedigreeFunction | Diabetes pedigree function |
| Age | Age of the patient |
| Outcome | Target variable (0 = Non-Diabetic, 1 = Diabetic) |

---

## 🛠 Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- Jupyter Notebook

---

## 🤖 Machine Learning Algorithm

**Algorithm:** Decision Tree Classifier

Decision Trees are supervised machine learning algorithms used for both classification and regression tasks. They classify data by learning simple decision rules inferred from the training data.

### Example Model Parameters

```python
DecisionTreeClassifier(
    criterion='entropy',
    random_state=42
)
```

---

## 📈 Project Workflow

1. Load the dataset.
2. Perform exploratory data analysis (EDA).
3. Handle missing or invalid values (if required).
4. Split the dataset into training and testing sets.
5. Train the Decision Tree model.
6. Make predictions on the test dataset.
7. Evaluate model performance.
8. Visualize the Decision Tree.

---

## 📊 Model Evaluation

The model can be evaluated using:

- Accuracy Score
- Confusion Matrix
- Precision
- Recall
- F1-Score
- Classification Report

Example:

```python
from sklearn.metrics import accuracy_score

accuracy = accuracy_score(y_test, y_pred)
print("Accuracy:", accuracy)
```

---

## 🌳 Decision Tree Visualization

The trained Decision Tree can be visualized using:

```python
from sklearn.tree import plot_tree

plot_tree(model)
```

This helps understand how the classifier makes predictions based on feature values.

---

## 🚀 Installation

Clone this repository:

```bash
git clone https://github.com/your-username/diabetes-prediction-decision-tree.git
```

Navigate into the project directory:

```bash
cd diabetes-prediction-decision-tree
```

Install the required dependencies:

```bash
pip install -r requirements.txt
```

---

## ▶️ Running the Project

Launch Jupyter Notebook:

```bash
jupyter notebook
```

Open the notebook and run all cells.

---

## 📁 Project Structure

```
Diabetes-Prediction-DecisionTree/
│
├── diabetes.csv
├── Decision_Tree_Diabetes.ipynb
├── README.md
├── requirements.txt
└── images/
    ├── decision_tree.png
    ├── confusion_matrix.png
    └── feature_importance.png
```

---

## 📊 Results

The Decision Tree model learns patterns from patient health data and predicts whether a patient is diabetic.

The trained model can assist in:

- Early diabetes prediction
- Medical decision support
- Risk assessment
- Healthcare data analysis

---

## 📈 Future Improvements

- Perform hyperparameter tuning using GridSearchCV.
- Compare Decision Tree with:
  - Random Forest
  - Logistic Regression
  - Support Vector Machine (SVM)
  - K-Nearest Neighbors (KNN)
- Improve model accuracy through feature engineering.
- Deploy the model using Flask or Streamlit.

---

## 📚 Required Libraries

- pandas
- numpy
- matplotlib
- scikit-learn
- jupyter

Install all dependencies using:

```bash
pip install pandas numpy matplotlib scikit-learn jupyter
```

or

```bash
pip install -r requirements.txt
```

---

## 📷 Sample Output

You can include screenshots such as:

- Dataset Preview
- Decision Tree Visualization
- Confusion Matrix
- Feature Importance Plot
- Accuracy Score Output

Example:

```markdown
## Decision Tree

![Decision Tree](images/decision_tree.png)

## Confusion Matrix

![Confusion Matrix](images/confusion_matrix.png)

## Feature Importance

![Feature Importance](images/feature_importance.png)
```

---

## 📖 Learning Outcomes

Through this project, you will learn:

- Data preprocessing
- Train-test splitting
- Decision Tree Classification
- Model evaluation
- Tree visualization
- Binary classification using Scikit-learn

---

## 👨‍💻 Author

**Adil Mushtaq**

GitHub: https://adilmushtaq67/Decision_Treee

LinkedIn: https://www.linkedin.com/in/adilmushtaqai

---

## 📜 License

This project is open-source and available under the **MIT License**.

---

## ⭐ Support

If you found this project helpful, please consider giving it a **⭐ Star** on GitHub. Your support is appreciated!
