# Multiple Disease Prediction System

A machine learning-based system that predicts the likelihood of **Diabetes**, **Heart Disease**, and **Parkinson's Disease** using patient health data. Built to assist in early detection and risk assessment through predictive analytics.

## 🩺 Overview

This project uses supervised machine learning models trained on publicly available medical datasets to predict whether a person is likely to have:

- **Diabetes**
- **Heart Disease**
- **Parkinson's Disease**

Each disease has its own trained model, allowing users to input relevant health parameters and receive an instant prediction.

## ✨ Features

- Three independent ML models for disease prediction
- Simple and clean interface for user input
- Fast and accurate predictions based on trained models
- Easily extendable to add more disease prediction models

## 🧠 Tech Stack

- **Language:** Python
- **Libraries:** NumPy, Pandas, Scikit-learn, Pickle
- **Interface:** Streamlit *(update if you used Flask/Django/other)*
- **IDE:** Jupyter Notebook / VS Code

> Update the tech stack above to match what you actually used.

## 📊 Datasets

| Disease | Dataset Source |
|----------|----------------|
| Diabetes | [PIMA Indians Diabetes Dataset](https://www.kaggle.com/datasets/uciml/pima-indians-diabetes-database) |
| Heart Disease | [UCI Heart Disease Dataset](https://archive.ics.uci.edu/dataset/45/heart+disease) |
| Parkinson's Disease | [UCI Parkinson's Dataset](https://archive.ics.uci.edu/dataset/174/parkinsons) |

## ⚙️ Installation

1. Clone the repository
   ```bash
   git clone https://github.com/your-username/multiple-disease-prediction.git
   cd multiple-disease-prediction
   ```

2. Create a virtual environment (optional but recommended)
   ```bash
   python -m venv venv
   source venv/bin/activate   # On Windows: venv\Scripts\activate
   ```

3. Install the required dependencies
   ```bash
   pip install -r requirements.txt
   ```

4. Run the application
   ```bash
   streamlit run app.py
   ```

## 🚀 Usage

1. Launch the app using the command above.
2. Select the disease you want to check predictions for (Diabetes / Heart Disease / Parkinson's).
3. Enter the required medical parameters (e.g., glucose level, blood pressure, age, etc.).
4. Click **Predict** to get the result instantly.

## 🏗️ Project Structure

```
multiple-disease-prediction/
│
├── models/
│   ├── diabetes_model.sav
│   ├── heart_disease_model.sav
│   └── parkinsons_model.sav
│
├── dataset/
│   ├── diabetes.csv
│   ├── heart.csv
│   └── parkinsons.csv
│
├── app.py
├── requirements.txt
└── README.md
```

> Update this structure to match your actual repo layout.

## 📈 Model Performance

| Model | Algorithm Used | Accuracy |
|--------|----------------|----------|
| Diabetes Prediction | Support Vector Machine (SVM) | XX% |
| Heart Disease Prediction | Logistic Regression | XX% |
| Parkinson's Prediction | Support Vector Machine (SVM) | XX% |

> Replace the algorithm names and accuracy values with your actual results.

## 🔮 Future Improvements

- Add more diseases (e.g., liver disease, kidney disease)
- Improve model accuracy using hyperparameter tuning
- Deploy the app on cloud platforms (Heroku, AWS, Streamlit Cloud)
- Add a user authentication system for saving prediction history

## 🤝 Contributing

Contributions are welcome! Feel free to fork this repository, raise issues, or submit pull requests.

## 📜 License

This project is licensed under the [MIT License](LICENSE).

## 👤 Author

HARSH SINHA

---

⭐ If you found this project useful, consider giving it a star on GitHub!