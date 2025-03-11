# 🏥 Diabetes Prediction using Logistic Regression & KNN Imputation

🚀 This project focuses on predicting diabetes using a dataset with missing values, which are handled using K-Nearest Neighbors (KNN) imputation. The processed data is then used to train a **Logistic Regression** model, with performance evaluation using accuracy, precision, recall, and ROC curve.

## 📂 Project Structure
- **Data Preprocessing**: Handling missing values using KNN imputation
- **Feature Standardization**: Scaling input features for better model performance
- **Model Training**: Logistic Regression for classification
- **Performance Evaluation**: Accuracy, Confusion Matrix, Precision, Recall, and ROC Curve

## 📥 Installation & Setup
1️⃣ Clone this repository:
```bash
git clone https://github.com/your-username/diabetes-prediction.git
```
2️⃣ Navigate to the project folder:
```bash
cd diabetes-prediction
```
3️⃣ Install dependencies:
```bash
pip install -r requirements.txt
```

## 🛠 Usage
Run the main script to preprocess data and train the model:
```bash
python diabetes_prediction.py
```

## 📊 Results
- **Accuracy:** 76.19%
- **Confusion Matrix:**
  ```
  [[140  17]
   [ 38  36]]
  ```
- **Precision:** 0.68
- **Recall:** 0.49
- **ROC AUC:** 0.83

## 📌 Key Insights
✅ KNN imputation improves missing data handling compared to simple mean imputation.
✅ Logistic Regression provides interpretable coefficients, helping understand feature impact.
✅ Precision and Recall indicate a balanced performance but can be improved with feature engineering.

## 📜 License
This project is licensed under the MIT License.

---
🌟 **Contributions are welcome!** Feel free to fork, modify, and submit a pull request.

