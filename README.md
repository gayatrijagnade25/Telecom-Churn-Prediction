# 📊 Telecom Customer Churn Prediction

## 📌 Project Overview
Telecom Customer Churn Prediction is a Machine Learning project that predicts whether a customer is likely to leave a telecom service. The project analyzes customer information and uses a trained classification model to predict customer churn.

The application is built using Python and Streamlit to provide a simple, interactive user interface for making predictions.

## 🎯 Objectives
- Predict whether a customer is likely to leave a telecom service.
- Analyze customer information to understand churn behavior.
- Apply Machine Learning techniques to customer churn prediction.
- Build an interactive web application using Streamlit.
- Help telecom businesses identify customers who may need retention strategies.

## 🛠️ Technologies Used
- **Python** – Programming language
- **Pandas** – Data manipulation and analysis
- **NumPy** – Numerical operations
- **Scikit-learn** – Machine Learning and data preprocessing
- **Streamlit** – Interactive web application
- **Pickle** – Saving and loading the trained model
- **Git and GitHub** – Version control and project hosting

## 📂 Project Structure

```text
Telecom-churn/
│
├── app.py                 # Streamlit application
├── best_model.pkl         # Model training script
├── requirements.txt       # Required Python libraries
├── scaler.pkl              # Saved trained model (generated)
├── dataset.csv            # Customer dataset (use actual filename)
└── README.md              # Project documentation
```

*Note: Replace `dataset.csv` with your actual dataset filename. Include `train_model.py` if you create it, and generate `model.pkl` before running the app.*

## ⚙️ Installation and Setup

### 1. Clone the Repository

```bash
git clone https://github.com/YOUR-USERNAME/Telecom-churn.git
```

Replace `YOUR-USERNAME` with your GitHub username.

### 2. Navigate to the Project Folder

```bash
cd Telecom-churn
```

### 3. Install Dependencies

```bash
python -m pip install -r requirements.txt
```

### 4. Train the Machine Learning Model

If the model training script is included, run:

```bash
python train_model.py
```

This should generate the `model.pkl` file when training completes successfully.

### 5. Run the Streamlit Application

```bash
python -m streamlit run app.py
```

Open the local URL displayed in the terminal, usually `http://localhost:8501`.

## 🔍 How It Works
1. Load the telecom customer dataset.
2. Clean and preprocess the customer data.
3. Prepare the input features and target variable.
4. Train a Machine Learning classification model.
5. Save the trained model for future use.
6. Load the model in the Streamlit application.
7. Enter customer details and generate a churn prediction.

## 📈 Expected Outcome
The application predicts whether a customer is likely to churn based on the input features and the trained model.

- **Churn:** The customer is predicted to leave the service.
- **No Churn:** The customer is predicted to remain with the service.

Predictions depend on the dataset, preprocessing steps, and model performance.

## 🚀 Future Improvements
- Compare multiple classification algorithms.
- Display model evaluation metrics such as accuracy, precision, recall, F1-score, and ROC-AUC.
- Add interactive visualizations for customer churn analysis.
- Deploy the Streamlit application online.
- Develop strategies to help businesses reduce customer churn.

## 👩‍💻 Author
**Gayatri Jagnade**

Aspiring Data Analyst | Python | SQL | Excel | Power BI | Machine Learning

## 📄 License
This project is intended for educational and portfolio purposes. Add a suitable open-source license if you want others to reuse or modify the code.
