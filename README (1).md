# 💳 Creditworthiness Prediction using Random Forest

This project predicts whether a customer is creditworthy using a Random Forest Classifier on the Statlog (German Credit Data) dataset.

---

## 📚 Dataset Source

- **UCI Machine Learning Repository**  
- [Statlog (German Credit Data)](https://archive.ics.uci.edu/dataset/144/statlog+german+credit+data)

---

## 📁 Project Files

- `final_creditworthiness_random_forest.ipynb`: Main notebook
- `credit_predictions.csv`: Exported predictions
- `credit_rf_model.joblib`: Trained model
- `encoded_german_credit_data.csv`: Preprocessed dataset
- `images/`: Visual outputs (confusion matrix, feature importance, ROC)

---

## 🔍 Problem Statement

Classify customers as **Good (1)** or **Bad (0)** credit risk based on financial and demographic information.

---

## 🧠 Model: Random Forest Classifier

- Feature Encoding using LabelEncoder
- 80/20 Train-Test Split
- 100 Trees
- Evaluated with Accuracy, Precision, Recall, ROC AUC

---

## 📊 Results and Visualizations

### 📌 Confusion Matrix

Illustrates the model's prediction performance.

![Confusion Matrix](images/confusion_matrix.png)

---

### 🔥 Top 10 Feature Importances

The most influential features in predicting creditworthiness.

![Feature Importance](images/feature_importance.png)

---

### 📈 ROC Curve

Shows true vs false positive rates across thresholds.

![ROC Curve](images/roc_curve.png)

---

## ✅ Evaluation Metrics (Example)

| Metric       | Value  |
|--------------|--------|
| Accuracy     | 0.78   |
| Precision    | 0.75   |
| Recall       | 0.80   |
| F1 Score     | 0.77   |
| ROC AUC      | 0.84   |

> 📌 Replace these with actual values from your output.

---

## 🚀 How to Run This Project

1. Clone the repo or open in Google Colab
2. Run `final_creditworthiness_random_forest.ipynb`
3. Outputs will be generated and saved in local directory

---

## 🧑‍💻 Author

**Tanushree Rathod**

---

## 📜 License

This project is open-source under the [MIT License](LICENSE).
