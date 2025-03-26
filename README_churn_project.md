
# Customer Churn Prediction App

This is a Streamlit web application designed to predict customer churn using a pre-trained deep learning model. The app allows users to input customer details and receive a real-time prediction of churn probability.

## 🔍 Project Summary

This app loads a Keras model (`model.h5`) and utilizes pre-trained encoders and scalers to process user inputs in real-time. The front end is powered by Streamlit, allowing interactive selection of inputs such as geography, gender, age, balance, credit score, and more.

## 📂 Files Included

- `app.py`: Main Streamlit application script
- `model.h5`: Trained neural network model for churn prediction
- `label_encoder_gender.pkl`: LabelEncoder for encoding gender
- `ohe_geography.pkl`: OneHotEncoder for geography feature
- `scaler.pkl`: StandardScaler to scale numerical inputs
- `Churn_Modelling.csv`: Dataset used for training and testing
- `requirements.txt`: Python dependencies for the project

## ⚙️ Technologies Used

- **Streamlit**: Web application interface
- **TensorFlow/Keras**: Model training and loading
- **Scikit-learn**: Preprocessing (encoding, scaling)
- **Pandas & NumPy**: Data manipulation
- **Pickle**: Model and encoder serialization

## 🛠️ How to Run

1. Install dependencies:
    ```bash
    pip install -r requirements.txt
    ```

2. Launch the app:
    ```bash
    streamlit run app.py
    ```

3. Enter the customer details via the Streamlit UI and view the churn probability output.

## 📌 Features

- Real-time churn prediction based on customer input
- Uses a trained neural network model for prediction
- Preprocessing pipeline includes:
  - Gender label encoding
  - Geography one-hot encoding
  - Feature scaling

## ✅ Output

- Displays the **churn probability**.
- Provides a prediction on whether the customer is likely to churn or not.

---

Built by Nithyasree Kusakula
