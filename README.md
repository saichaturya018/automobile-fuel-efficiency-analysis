🚗 Vehicle Fuel Efficiency (MPG) Prediction & Diagnostics
An end-to-end Data Science and Machine Learning project analyzing vehicle fuel economy using Ordinary Least Squares (OLS) Linear Regression and Random Forest Regressor models.


📌 About the Project
Predicting vehicle fuel efficiency (MPG) accurately is vital for automotive engineering, performance benchmarking, and environmental impact assessment. This project evaluates model diagnostic metrics, non-linear interaction mapping, and the trade-off between statistical inference and predictive accuracy across different machine learning algorithms.
This project was developed as part of the IBM Applied Skills & Training Program.


✨ Key Features
📊 Exploratory Data Analysis (EDA): In-depth feature correlation, distribution analysis, and outlier detection.
⚙️ Data Preprocessing & Engineering: Automated missing value handling, feature scaling, and feature transformation.
🤖 Comparative ML Modeling: Baseline OLS Linear Regression vs. Non-Parametric Random Forest Regressor.
📈 Residual Diagnostics: Error distribution plotting (y_{\text{actual}} vs. y_{\text{predicted}}), RMSE, and R^2 evaluations.
🚀 Production-Ready Pipeline: Clean modular Python structure for model training, evaluation, and inference.


🛠️ Tech Stack
Programming Language: Python 3.x
Data Processing & Analytics: Pandas, NumPy
Machine Learning: Scikit-Learn (LinearRegression, RandomForestRegressor, metrics)
Data Visualization: Matplotlib, Seaborn
Environment & Tools: Jupyter Notebook, Git, GitHub


📊 Key Results & Model Comparison
Evaluation DimensionOLS Inference ModelRandom Forest Regressor
Model ArchitectureParametric (Linear)Non-Parametric (Ensemble Trees)
Out-of-Sample RMSEHigher Error SpreadLow Error (Tight Residual Clustering)
Variance Explained (R^2)Moderate FitHigh R^2 (Superior Fit)
Non-Linear DynamicsRestricted to linear combinationsCaptures complex feature interactions
Tail-End PerformanceHigher error at extremes (<15, >35 MPG)Consistent accuracy across all ranges
Primary AdvantageExplanatory Inference & Coefficient InterpretabilityProduction-Grade Prediction Accuracy.


Repository Structure
Automobile-Fuel-Efficiency-Analysis/
├── data/
│   └── vehicle_dataset.csv         # Vehicle specs & target MPG data
├── notebooks/
│   └── mpg_model_evaluation.ipynb  # EDA, training, & diagnostic plots
├── src/
│   ├── preprocess.py               # Data cleaning & feature transformation
│   ├── train_ols.py                # OLS implementation pipeline
│   └── train_rf.py                 # Random Forest training & evaluation
├── app.py                          # Main execution entry point
├── requirements.txt                # Python dependencies
└── README.md                       # Project documentation


Installation & Setup

1.Prerequisites
Python 3.9 or higher
Git

Setup Steps 

1. Clone the repository: git clone https://github.com/saichaturya018/automobile-fuel-efficiency-analysis.git
cd automobile-fuel-efficiency-analysis

2. Create and activate a virtual environment:  python -m venv venv
venv\Scripts\activate

3. Install dependencies: pip install -r requirements.txtFuture Enhancements
🌐 REST API integration for real-time MPG estimation
⚡ Deep Learning baseline evaluation (Multi-Layer Perceptron)
☁️ Automated model deployment pipeline on IBM Cloud
📊 Interactive feature importance and SHAP interpretability dashboard


🎓 Academic & Team Information
Project Title: Vehicle Fuel Efficiency (MPG) Prediction & Diagnostics
Domain: Data Science | Machine Learning | Predictive Analytics
Institution: Anil Neerukonda Institute of Technology and Sciences (ANITS)
Department: Computer Science and Engineering (Data Science)
👥 Author
Amjuri Sai Chaturya 


📜 License & Acknowledgements
License
This project is developed for educational and academic purposes under the MIT License.
Acknowledgements
We sincerely thank the following organizations and technologies for supporting this project:
IBM
Anil Neerukonda Institute of Technology and Sciences (ANITS)
Scikit-Learn & Python Open Source Community

5. Run Model Training & Diagnostics: python src/train_rf.py
