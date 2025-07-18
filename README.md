# 🚢 Titanic Survival Prediction - ML Project

Predicting survival outcomes on the Titanic using supervised machine learning techniques. This classic binary classification problem leverages passenger data to train and evaluate multiple models, exploring both model performance and feature impact.

---

## 📁 Dataset

The dataset used is the **Kaggle Titanic dataset**, which contains details about passengers such as:
- **Pclass**: Ticket class (1st, 2nd, 3rd)
- **Sex**
- **Age**
- **Fare**
- **Embarked**: Port of Embarkation
- **SibSp**: Number of siblings/spouses aboard
- **Parch**: Number of parents/children aboard

> 📌 Missing values in `Age`, `Embarked`, and `Fare` were handled appropriately through imputation and preprocessing.

---

## 🎯 Goal

Predict whether a passenger survived the Titanic disaster using supervised machine learning algorithms.

---

## 🧼 Preprocessing & Feature Engineering

- Handled missing values (mean/mode imputation)
- Converted categorical variables using `LabelEncoder`
- Dropped irrelevant features like `PassengerId`, `Name`, `Cabin`, and `Ticket`
- Normalized the dataset for models that benefit from scaling

---

## 📊 Visualizations

To better understand feature distributions and relationships:

- 📈 Age distribution histogram
- 🧍 Gender-based survival rates
- 🌡 Correlation heatmap
- 🌳 Decision tree visualization (with feature names)

---

## 🧪 Models & Evaluation

Three models were trained and evaluated:

### ✅ Logistic Regression
- Used as a baseline linear classifier
- Evaluated with:
  - Accuracy
  - Confusion Matrix
  - Classification Report (Precision, Recall, F1-score)

### 🌲 Decision Tree Classifier
- Simple and interpretable model
- Visualized using `sklearn.tree.plot_tree`
- Evaluated using:
  - Accuracy Score
  - Confusion Matrix
  - Feature Importance

### 🌳 Random Forest Classifier
- Ensemble method using multiple trees for better performance
- Evaluated using:
  - Accuracy Score
  - Confusion Matrix
  - Feature Importance

---

## 📌 Key Insights

- **Sex** and **Pclass** are strong indicators of survival.
- **Fare** shows a moderate positive correlation with survival.
- **Decision Trees** offer explainability, while **Random Forests** often yield better accuracy.
- Logistic Regression provides a good baseline but lacks the non-linear flexibility of tree-based models.

---

## 💻 Installation & Usage

### 🔧 Requirements

- Python 3.7+
- scikit-learn
- pandas
- matplotlib
- seaborn
- numpy

### 🚀 Run the notebook

You can run the notebook using [Google Colab](https://colab.research.google.com/) or locally:

```bash
git clone https://github.com/your-username/titanic-survival-prediction.git
cd titanic-survival-prediction
pip install -r requirements.txt
jupyter notebook Titanic_Survival_Prediction.ipynb
```
📂 Project Structure

<img width="293" height="130" alt="image" src="https://github.com/user-attachments/assets/ed42fdf4-e8db-4d4c-b3d0-571e0c4627b6" />

🧠 Skills Demonstrated
- Data Cleaning & Preprocessing
Exploratory Data Analysis (EDA)
Supervised Learning (Logistic Regression, Decision Tree, Random Forest)
Model Evaluation & Interpretation
Feature Importance Visualization
Clean, modular notebook structure

📌 Ideal for
- This project is an excellent demonstration of your knowledge in:
  - Applied ML
  - EDA & visualization
  - Model selection
  - Python coding best practices

📌 Requirements
See [requirements.txt]().

If you're running this in Google Colab or locally via virtualenv, this file helps others easily recreate your environment by running:

```
pip install -r requirements.txt
```

👤 Author
Ganguli Silva
[LinkedIn](https://www.linkedin.com/in/ganguli-silva-a0773b199/) | [GitHub](https://github.com/ganguliSilva)


