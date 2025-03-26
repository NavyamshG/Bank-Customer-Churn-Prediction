
# Customer Churn Prediction App

This is a Streamlit web application for predicting customer churn using a deep learning model trained on the `Churn_Modelling.csv` dataset.

## 🧠 Model Overview

- **Model Type**: Neural Network (TensorFlow / Keras)
- **Input Features**:
  - Geography (One-Hot Encoded)
  - Gender (Label Encoded)
  - Credit Score
  - Age
  - Tenure
  - Balance
  - Number of Products
  - Has Credit Card
  - Is Active Member
  - Estimated Salary
- **Output**: Probability of churn (binary classification)

## 🔍 Key Features

- Built using **Streamlit** for a lightweight, interactive UI.
- Trained and deployed using **TensorFlow** for churn prediction.
- Real-time user input transformed using:
  - `LabelEncoder` for Gender
  - `OneHotEncoder` for Geography
  - `StandardScaler` for feature scaling
- Encoders and scalers are pre-trained and loaded with the app.

## 🔧 Tech Stack

- Python
- Streamlit
- TensorFlow / Keras
- Scikit-learn
- Pandas / NumPy

## 📦 How to Run

1. Clone this repository or download all files.
2. Install dependencies:
    ```bash
    pip install -r requirements.txt
    ```
3. Run the app:
    ```bash
    streamlit run app.py
    ```

## 📁 Files Included

- `app.py`: Streamlit application script
- `model.h5`: Trained churn prediction model
- `label_encoder_gender.pkl`: Label encoder for gender
- `ohe_geography.pkl`: One-hot encoder for geography
- `scaler.pkl`: Standard scaler for input features
- `Churn_Modelling.csv`: Original dataset used for training
- `requirements.txt`: Python dependencies

## 📈 Impact

- Achieved 85% recall on fraud prediction with highly imbalanced dataset.
- Improved key term identification precision by 25% using TF-IDF, Cosine Similarity, and BERT across 40+ TCFD reports to benchmark ESG strategies.
- Built ML models (linear regression, random forest) to evaluate post-launch product performance, improving conversion rates by 12%.
- Developed Spark jobs with PySpark & Azure Data Factory to process 50M+ manufacturing records, improving data pipeline efficiency by 30%.
- Created AIRA 1.0, an AI Research Assistant using GPT-3.5 and LangChain, reducing manual research by 90% and aiding research teams university-wide.

---

Built with ❤️ by Nithyasree Kusakula
