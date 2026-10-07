# Machine Failure Prediction Using Machine Learning

## 📌 Project Overview

Machine Failure Prediction is a Machine Learning project that aims to predict whether a machine is likely to fail based on its operating and process data.

This project uses the AI4I 2020 Predictive Maintenance Dataset and applies classification algorithms to identify potential machine failures. Predicting failures can help reduce unexpected downtime and support better maintenance planning.

## 🎯 Objectives

- Analyze and understand the machine maintenance dataset.
- Perform data preprocessing and exploratory data analysis.
- Encode categorical features using One-Hot Encoding.
- Handle class imbalance using SMOTE.
- Detect and handle outliers.
- Perform feature selection and feature scaling.
- Train and compare multiple Machine Learning classification models.
- Evaluate model performance using different metrics.

## 📂 Dataset

**Dataset Name:** AI4I 2020 Predictive Maintenance Dataset

**Target Variable:** `Machine failure`

The target variable indicates whether a machine failure has occurred.

The dataset contains machine operating measurements and process-related features used to predict failures.

## 🛠️ Technologies Used

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Imbalanced-learn

## ⚙️ Project Workflow

1. Data Collection
2. Data Exploration and Analysis
3. Data Cleaning and Preprocessing
4. Categorical Feature Encoding
5. Class Balancing using SMOTE
6. Outlier Handling
7. Feature Selection using SelectKBest
8. Feature Scaling using StandardScaler
9. Model Training and Testing
10. Performance Evaluation

## 🤖 Machine Learning Algorithms

The following classification algorithms are implemented and compared:

- Logistic Regression
- Decision Tree Classifier
- Random Forest Classifier
- AdaBoost Classifier
- Gradient Boosting Classifier

## 📊 Evaluation Metrics

The models are evaluated using:

- Accuracy
- Precision
- Recall
- F1-Score
- Classification Report

These metrics help compare model performance and understand how effectively the models identify machine failures.

## 💻 Installation and Execution

### 1. Clone the Repository

```bash
git clone <your-github-repository-url>
```

### 2. Navigate to the Project Folder

```bash
cd <your-project-folder>
```

### 3. Install Required Libraries

```bash
pip install pandas numpy matplotlib seaborn scikit-learn imbalanced-learn jupyter
```

### 4. Add the Dataset

Place the `ai4i2020.csv` dataset in the project folder.

### 5. Run the Notebook

```bash
jupyter notebook
```

Open the project notebook and execute the cells in order.

## 📈 Results

The project compares five Machine Learning classification algorithms using accuracy, precision, recall, and F1-score.

The best-performing model should be identified based on the actual evaluation results obtained after running the notebook.

## 🚀 Future Enhancements

- Improve model performance through hyperparameter tuning.
- Validate the models on unseen data.
- Develop a simple web application for machine failure prediction.
- Integrate real-time machine sensor data for predictive maintenance.

## 👩‍💻 Project Type

Machine Learning | Classification | Predictive Maintenance

## 📄 License

This project is intended for educational and learning purposes.
