# CO₂ Emission Prediction Web App 

This project predicts vehicle CO₂ emissions based on various input features such as engine size, fuel consumption, transmission type, and vehicle class.

##  Features
- Predicts CO₂ emissions in real-time
- User-friendly web interface
- Handles multiple input parameters
- Provides quick and accurate results

##  Machine Learning
- Regression-based model built using Scikit-learn
- Data preprocessing and feature engineering applied
- Model evaluation using metrics such as R² score and RMSE

##  Tech Stack
- Python
- Scikit-learn
- Pandas, NumPy
- Flask
- HTML, CSS, JavaScript

##  Input Parameters
- Engine Size (L)
- Cylinders
- Fuel Consumption (City, Highway, Combined)
- Transmission Type
- Fuel Type
- Vehicle Class

##  Live Demo
https://co2-emission-prediction-1-9ixn.onrender.com

##  Project Structure
- app.py → Flask application
- model.pkl → Trained ML model
- templates/ → HTML files
- static/ → CSS and JS files
- dataset → Training data

##  Output
- Predicts CO₂ emissions in g/km
- Displays results instantly based on user input

##  Dataset
Dataset used for training includes vehicle specifications and emission data.

##  Future Improvements
- Add emission category (Low/Medium/High)
- Improve UI/UX design
- Deploy using Docker
- Add model comparison (Random Forest, XGBoost)
