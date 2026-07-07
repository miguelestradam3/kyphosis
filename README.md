# 🦴 Kyphosis Prediction using Machine Learning

This project explores the **Kyphosis** dataset to predict whether a patient will develop kyphosis after corrective spinal surgery. It demonstrates a complete machine learning workflow, including data preprocessing, exploratory data analysis (EDA), handling class imbalance with **SMOTE**, and training multiple classification models.

The project compares the performance of several machine learning algorithms to identify the most effective approach for predicting postoperative kyphosis.

---

## 📌 Features

- Data exploration and visualization
- Dataset preprocessing
- Label encoding of categorical variables
- Correlation analysis
- Pairwise feature visualization
- Class imbalance handling using SMOTE
- Feature standardization
- Training multiple machine learning models
- Model evaluation using classification metrics
- Confusion matrix visualization

---

## 🛠 Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- imbalanced-learn (SMOTE)
- Jupyter Notebook

---

## 📚 Libraries

```python
pandas
numpy
matplotlib
seaborn
scikit-learn
imbalanced-learn
jupyterthemes
```

---

## 📂 Project Structure

```
kyphosis/
│
├── kyphosis.csv
├── main.ipynb
├── requirements.txt
└── README.md
```

---

## 📊 Dataset

The project uses the **Kyphosis** dataset, which contains medical information about children who underwent corrective spinal surgery.

### Features

| Feature | Description |
|----------|-------------|
| Age | Age of the patient (in months) |
| Number | Number of vertebrae involved |
| Start | Starting vertebra of the surgery |
| Kyphosis | Whether kyphosis was present after surgery (Target Variable) |

The target variable is converted into numerical values using **Label Encoding** before model training.

---

## 🔍 Exploratory Data Analysis (EDA)

The notebook performs several exploratory analyses, including:

- Dataset inspection
- Summary statistics
- Missing value inspection
- Maximum, minimum, and average patient age
- Correlation heatmap
- Pair plots
- Target class distribution
- Disease prevalence calculation

These visualizations help understand the relationships between the variables before model training.

---

## ⚖️ Handling Class Imbalance

Since the Kyphosis dataset is imbalanced, the project applies **SMOTE (Synthetic Minority Oversampling Technique)** to generate synthetic samples of the minority class.

This helps improve model performance by providing a more balanced training dataset.

---

## ⚙️ Data Preprocessing

The preprocessing pipeline includes:

- Label Encoding
- Train/Test Split
- SMOTE Oversampling
- Feature Standardization using `StandardScaler`

---

## 🤖 Machine Learning Models

The project trains and compares multiple supervised learning algorithms:

- Logistic Regression
- Decision Tree Classifier
- Random Forest Classifier

---

## 📈 Model Evaluation

Each model is evaluated using:

- Confusion Matrix
- Classification Report
- Precision
- Recall
- F1-Score

For Logistic Regression, additional regression-style metrics are also calculated:

- Mean Squared Error (MSE)
- Mean Absolute Error (MAE)
- R² Score

---

## 🚀 Getting Started

### Clone the repository

```bash
git clone https://github.com/miguelestradam3/kyphosis.git

cd kyphosis
```

---

### Install dependencies

```bash
pip install -r requirements.txt
```

Or install manually:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn imbalanced-learn jupyterthemes
```

---

## ▶️ Running the Project

Launch Jupyter Notebook:

```bash
jupyter notebook
```

Open:

```
main.ipynb
```

Run the notebook cells sequentially to reproduce the analysis and train the machine learning models.

---

## 🎯 Learning Objectives

This project demonstrates how to:

- Explore medical datasets
- Perform exploratory data analysis
- Handle imbalanced datasets using SMOTE
- Preprocess data for machine learning
- Train multiple classification algorithms
- Compare model performance
- Evaluate classifiers using standard metrics

---

## 🔮 Future Improvements

- Hyperparameter tuning with GridSearchCV
- Cross-validation
- ROC Curve and AUC analysis
- Feature importance visualization
- Model persistence using Joblib
- Pipeline implementation with Scikit-learn
- Additional ensemble learning methods (XGBoost, LightGBM)


---

⭐ If you found this project useful, consider giving it a star!
