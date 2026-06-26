# 💳 Fraud Detection Web App

A Machine Learning-powered web application for detecting potentially fraudulent transactions in real time.

The project uses data preprocessing, class imbalance handling, and ensemble learning techniques to analyze transaction information and estimate fraud risk through an interactive Streamlit interface.

---

##  Features

- Interactive Streamlit Web Application
- Real-Time Fraud Prediction
- Fraud Risk Probability Score
- Missing Value Handling using KNN Imputer
- Class Imbalance Handling using SMOTETomek
- Random Forest Classifier
- User-Friendly Interface
- Cloud Deployment Support
- Fraud Risk Visualization

---

## 🛠 Technologies Used

- Python
- Pandas
- NumPy
- Scikit-Learn
- Imbalanced-Learn
- Streamlit
- Joblib
- Matplotlib
- Seaborn

---

## 📊 Machine Learning Pipeline

### 1. Data Preprocessing

- Missing Value Detection
- KNN Imputation
- Data Cleaning

### 2. Handling Imbalanced Data

- SMOTETomek Resampling

### 3. Model Training

- Random Forest Classifier

### 4. Evaluation Metrics

- Accuracy
- Precision
- Recall
- F1 Score
- ROC-AUC

### 5. Deployment

- Streamlit Web Application
- Cloudflare Tunnel Deployment



---

## ⚙️ Installation

Clone the repository:

```bash
git clone https://github.com/your-username/Fraud-Detection-Web-App.git
```

Move to project directory:

```bash
cd Fraud-Detection-Web-App
```

Install dependencies:

```bash
pip install -r requirements.txt
```

Run Streamlit:

```bash
streamlit run app.py
```

---

## 🎯 Example Input

| Feature | Example |
|----------|----------|
| Transaction Amount | 100 |
| Hour Of Day | 12 |
| Is Weekend | 1 |
| Number Of Items | 3 |
| Customer Age | 31 |
| Previous Transactions | 6 |
| Distance From Home | 10 |
| Device Type | 2 |
| Network Quality | 70 |
| First Transaction | 1 |
| Store Type | 2 |
| Velocity Score | 5 |

---

## 📈 Example Output

```text
Legitimate Transaction

Fraud Probability: 13.12%
```

---

## 🔮 Future Improvements

- XGBoost Integration
- Hyperparameter Tuning
- Cross Validation
- Explainable AI (SHAP)
- Feature Importance Dashboard
- Multi-Model Comparison
- Online Deployment

---

## 👩‍💻 Author

Mai Nasr

Aspiring AI & Machine Learning Engineer passionate about building intelligent systems and solving real-world problems using Data Science and Machine Learning.

---

⭐ If you found this project useful, consider giving it a star.
