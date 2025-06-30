# 🏦 German Credit Risk Prediction App

This Streamlit application predicts whether a person is a **good** or **bad credit risk** using an **XGBoost classification model** trained on the classic [German Credit Data](https://archive.ics.uci.edu/ml/datasets/statlog+(german+credit+data)) from the UCI Machine Learning Repository.

---

## 🚀 Features

- 📊 Interactive web interface using Streamlit
- 🧠 Trained XGBoost model on real-world credit risk data
- 📝 Real-time inference with categorical and numerical inputs
- 💾 Model saved and loaded via `joblib` for fast inference

---

## 📁 Project Structure

```
.
├── app.py                  # Streamlit inference app
├── train_model.py          # Model training and saving script
├── xgb_german_credit.pkl   # Saved trained XGBoost model
├── requirements.txt        # Python dependencies
└── README.md               # Project documentation
```

---

## 📦 Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/your-username/german-credit-risk-app.git
   cd german-credit-risk-app
   ```

2. **Install dependencies**
   ```bash
   pip install -r requirements.txt
   ```

3. **Train the model**
   ```bash
   python train_model.py
   ```

4. **Run the Streamlit app**
   ```bash
   streamlit run app.py
   ```

---

## 📊 Dataset Description

- **Records:** 1,000 customers
- **Features:** 20 attributes (categorical + numerical)
- **Target Variable:** 
  - `0` = Good Credit Risk  
  - `1` = Bad Credit Risk

---

## 🧪 Model Details

- **Model:** XGBoost Classifier
- **Evaluation:** Printed via confusion matrix and classification report
- **Feature Engineering:** One-hot encoding for categorical variables

---

## 🔮 Future Enhancements

- Add SHAP or LIME explainability
- Add model versioning and logging
- Deploy to Streamlit Cloud or Hugging Face Spaces

---

## 📜 License

This project is licensed under the MIT License. Feel free to use and modify with attribution.

---

## 🙋‍♂️ Author

**Debu Dey**  
Senior Data Scientist | AI/ML Specialist  
[LinkedIn](https://www.linkedin.com/in/debudey) • [GitHub](https://github.com/debudey)

---
