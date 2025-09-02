# 🍷 Wine Quality Prediction Using Random Forest

A machine learning project to classify red wine quality (good vs. not good) using the Red Wine Quality dataset.
The pipeline covers data exploration, preprocessing, visualization, model training with Random Forest, and thorough evaluation (accuracy, F1, confusion matrix, ROC–AUC).

---

## 🚀 Features

📊 **Exploratory Data Analysis (EDA):** Summary stats, missing values, class balance, feature distributions, correlation heatmap

🧮 **Preprocessing:** Binary encoding of target (quality ≥ 7 → Good), optional scaling (MinMaxScaler)

🌲 **Model Training:** RandomForestClassifier with reproducible settings

📈 **Evaluation Metrics:** Train & test accuracy, precision/recall/F1, confusion matrix, ROC curve & AUC

🧪 **Prediction on New Samples:** Reshaping custom inputs and predicting wine quality in real time

🔎 **Visualization:** Count plot of quality, barplots vs. quality, correlation heatmap, confusion matrix, ROC curve

---

## 🧠 Machine Learning Workflow

- Import libraries (Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn)

- Load Red Wine dataset (CSV file)

- Explore dataset (shape, info, describe, value counts)

- Encode target to binary label (≥ 7 = 1 “Good”, else 0 “Bad”)

- Split into train & test sets (80% / 20%, stratified)

- (Optional) Scale features with MinMaxScaler

- Train RandomForestClassifier (fixed random_state)

- Evaluate performance (accuracy, classification report, F1)

- Visualize confusion matrix and ROC curve (AUC)

- Test model on sample inputs

---

## 🛠️ Tech Stack

| Layer       | Technology       |
|-------------|------------------|
| Language    | Python 3.12      |
| Framework   | Scikit-learn     |
| Dataset     | Red Wine Quality (CSV)|
| Tools       | NumPy, Pandas, Matplotlib, Seaborn|

---

## 📁 Project Structure

```text
├── Data/
│   └── winequality-red.csv                ← Main dataset
├── Wine_Quality_Prediction.ipynb          ← Jupyter Notebook (main workflow)
├── outputs/                               ← Saved plots (optional)
├── models/                                ← Saved model/scaler (optional)
└── README.md                              ← Project documentation
