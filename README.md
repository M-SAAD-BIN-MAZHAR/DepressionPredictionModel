# 🧠 Depression Prediction Model

Welcome to the **Depression Prediction Model**, a web-based application designed to predict depression risk based on user inputs. This repository implements an interactive Streamlit app and a machine learning pipeline for inference.

## 🚀 Features
- **Interactive Web Form:** Inputs about age, gender, profession, lifestyle, and psychological factors.
- **ML-Powered Prediction:** Uses a trained logistic regression model to estimate depression risk.
- **Configurable Threshold:** Users can adjust the sensitivity for positive (depressed) predictions.
- **Confidence Visualization:** Displays model confidence with progress bar and statistical output.
- **Debug Output:** Optionally displays raw model outputs for transparency.

## 🗂 Repository Structure

- App.py — Streamlit web app, handles user input and runs predictions.
- DepressionDetectionModel.ipynb — Jupyter notebook containing training and evaluation code for the machine learning model.
- pipe.pkl, Logistic_Model.pkl — Serialized pipeline/model files for prediction logic.
- requirements.txt — Dependencies needed to run the app.
- .idea/ — IDE configuration (can be ignored).

## 🛠️ Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/M-SAAD-BIN-MAZHAR/DepressionPredictionModel.git
   cd DepressionPredictionModel
   ```

2. **Install dependencies**
   ```bash
   pip install -r requirements.txt
   ```

3. **Run the app**
   ```bash
   streamlit run App.py
   ```

   Make sure pipe.pkl is in the same directory as App.py.

## 📋 Usage

- Fill in details about yourself in the web form.
- Adjust the threshold slider to modify sensitivity.
- Click "Predict" to see if you are at risk for depression according to the model.
- Optional: check "Show raw model output" for debug info.

## 🤖 Model Details

- Trained using logistic regression and feature pipeline.
- Inputs include: Gender, Age, Profession, Sleep Duration, Dietary Habits, Suicidal Thoughts, Work/Study Hours, Financial Stress, Family History, Pressure, Satisfaction.

## ⚠️ Disclaimer

This tool provides a prediction based on self-reported data and should **not** be used as a clinical diagnosis. If you have concerns about depression, consult a healthcare professional.

## 👤 Author

**M.Saad Bin Mazhar**  
_Focused on creating efficient and innovative solutions._

## 📄 License

This project is for educational and research purposes.

---

For suggestions, bug reports, or contributions, feel free to open an issue or pull request.