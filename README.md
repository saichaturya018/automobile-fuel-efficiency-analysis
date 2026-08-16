# 🚗 Vehicle Fuel Efficiency (MPG) Prediction & Diagnostics
An end-to-end Data Science and Machine Learning project for analyzing and predicting vehicle fuel efficiency using Ordinary Least Squares (OLS) Linear Regression and Random Forest Regressor models.

---
## 📌 About the Project
Predicting vehicle fuel efficiency (Miles Per Gallon – MPG) accurately is important for automotive engineering, performance benchmarking, and environmental impact assessment.

This project focuses on:

- 📊 Exploratory Data Analysis (EDA)
- 🧹 Data preprocessing and feature engineering
- 📈 Statistical modeling using OLS Linear Regression
- 🌲 Machine Learning using Random Forest Regressor
- 🔍 Model diagnostic analysis
- 📉 Residual and prediction error analysis
- ⚖️ Comparison between statistical inference and predictive accuracy

«🎓 Developed as part of the IBM Applied Skills & Training Program.»

---


## ✨ Key Features

### 📊 Exploratory Data Analysis (EDA)
- Feature correlation analysis
- Distribution analysis
- Outlier detection
- Target variable analysis
- Visualization of relationships between vehicle characteristics and MPG

### ⚙️ Data Preprocessing & Feature Engineering
- Automated missing-value handling
- Data cleaning
- Feature transformation
- Feature scaling
- Preparation of data for machine learning models

### 🤖 Comparative Machine Learning
Two models are evaluated:

1. OLS Linear Regression – provides statistical inference and interpretable coefficients.
2. Random Forest Regressor – captures complex non-linear relationships and feature interactions.

### 📈 Residual Diagnostics
Model performance is evaluated using:

- RMSE (Root Mean Squared Error)
- R² (Coefficient of Determination)
- Actual vs. Predicted MPG analysis
- Residual error distribution
- Prediction performance across different MPG ranges

### 🚀 Modular ML Pipeline
The project follows a clean and modular structure for:

- Data preprocessing
- Model training
- Model evaluation
- Diagnostics
- Future inference and deployment

---


## 🛠️ Tech Stack
Category| Technologies
🐍 Programming Language| Python 3.x
📊 Data Processing| Pandas, NumPy
🤖 Machine Learning| Scikit-Learn
📈 Statistical Modeling| OLS / Linear Regression
🌲 Ensemble Learning| Random Forest Regressor
📉 Visualization| Matplotlib, Seaborn
💻 Development Environment| Jupyter Notebook
🔧 Version Control| Git, GitHub

---


## 📊 Key Results & Model Comparison
Evaluation Dimension| OLS Linear Regression| Random Forest Regressor
Model Architecture| Parametric / Linear| Non-Parametric / Ensemble
Out-of-Sample RMSE| Higher Error Spread| Lower Error
Variance Explained (R²)| Moderate Fit| Higher R²
Non-Linear Dynamics| Limited| Captures complex interactions
Tail-End Performance| Higher error at extreme MPG values| More consistent accuracy
Interpretability| ⭐⭐⭐⭐⭐ High| ⭐⭐⭐ Moderate
Prediction Accuracy| ⭐⭐⭐ Moderate| ⭐⭐⭐⭐⭐ High
Primary Advantage| Statistical inference & coefficient interpretation| Production-grade prediction accuracy


### 🏆 Overall Finding
Random Forest Regressor provides superior predictive performance by capturing non-linear relationships and complex feature interactions, while OLS Linear Regression remains valuable for statistical interpretation and understanding the influence of individual features.

---


## 📁 Repository Structure
Automobile-Fuel-Efficiency-Analysis/
│
├── 📂 data/
│   └── vehicle_dataset.csv
│
├── 📂 notebooks/
│   └── mpg_model_evaluation.ipynb
│
├── 📂 src/
│   ├── preprocess.py
│   ├── train_ols.py
│   └── train_rf.py
│
├── 📄 app.py
├── 📄 requirements.txt
└── 📄 README.md

### 📂 Directory Description
File / Folder| Purpose
"data/"| Contains the vehicle dataset
"notebooks/"| EDA, model development and diagnostic analysis
"src/preprocess.py"| Data cleaning and feature transformation
"src/train_ols.py"| OLS / Linear Regression training pipeline
"src/train_rf.py"| Random Forest training and evaluation
"app.py"| Main project execution entry point
"requirements.txt"| Required Python dependencies
"README.md"| Project documentation

---

## ⚙️ Installation & Setup

### 1️⃣ Prerequisites
Make sure the following are installed:

- Python 3.9 or higher
- Git
- Jupyter Notebook (optional)

---

### 2️⃣ Clone the Repository
git clone https://github.com/saichaturya018/automobile-fuel-efficiency-analysis.git
cd automobile-fuel-efficiency-analysis

---

### 3️⃣ Create a Virtual Environment
Windows

python -m venv venv
venv\Scripts\activate

macOS / Linux

python3 -m venv venv
source venv/bin/activate

---


### 4️⃣ Install Dependencies
pip install -r requirements.txt

---

### 5️⃣ Run Model Training & Diagnostics

🌲 Random Forest Model

python src/train_rf.py

📈 OLS / Linear Regression Model

python src/train_ols.py

📓 Run the Jupyter Notebook

jupyter notebook

Then open:

notebooks/mpg_model_evaluation.ipynb

---

## 🔮 Future Enhancements
The project can be further extended with:

- 🌐 REST API integration for real-time MPG prediction
- 🧠 Deep Learning baseline using Multi-Layer Perceptron (MLP)
- ☁️ Automated model deployment on IBM Cloud
- 📊 Interactive feature importance dashboard
- 🔍 SHAP-based model interpretability
- 🚀 Real-time prediction interface
- 📦 Model serialization and production deployment

## 🎓 Academic & Team Information
Details| Information
Project Title| Vehicle Fuel Efficiency (MPG) Prediction & Diagnostics
Domain| Data Science | Machine Learning | Predictive Analytics
Institution| Anil Neerukonda Institute of Technology and Sciences (ANITS)
Department| Computer Science and Engineering (Data Science)
Program| IBM Applied Skills & Training Program

---


## 👤 Author
Amjuri Sai Chaturya

🎓 B.Tech – Computer Science and Engineering (Data Science)
🏫 Anil Neerukonda Institute of Technology and Sciences (ANITS)

---

## 📜 License & Acknowledgements
### 📄 License

This project is developed for educational and academic purposes under the MIT License.

### 🙏 Acknowledgements
Special thanks to:

- IBM – Applied Skills & Training Program
- Anil Neerukonda Institute of Technology and Sciences (ANITS)
- Python Open Source Community
- Scikit-Learn Open Source Community
- Pandas & NumPy
- Matplotlib & Seaborn

---


## ⭐ Project Highlights
🌲 Random Forest → Superior predictive performance
📈 OLS Regression → Strong statistical interpretability
📊 EDA → Comprehensive understanding of vehicle data
⚙️ Modular Pipeline → Clean and reusable ML workflow
🚀 Future Ready → API, cloud deployment & SHAP integration


