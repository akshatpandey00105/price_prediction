# 🚗 Car Price Prediction using Machine Learning

This project uses machine learning techniques to predict the resale price of used cars based on key features like brand, fuel type, transmission, ownership, kilometers driven, and more.

## 📌 Problem Statement

Used car dealerships and customers often struggle with inconsistent or unfair pricing. This system aims to provide data-driven, accurate resale price predictions using regression models trained on historical car data.

## 💡 Proposed Solution

A machine learning pipeline was built to:
- Preprocess and clean the dataset
- Encode categorical variables
- Train and compare multiple regression models
- Evaluate performance using standard metrics
- Select the best model for predicting car prices

## 🧰 Tech Stack

- Python 3.x  
- Jupyter Notebook  
- scikit-learn  
- pandas, numpy  
- matplotlib, seaborn  

## 🗃️ Dataset Features

| Feature         | Description                        |
|----------------|------------------------------------|
| Car_Name        | Name of the car                    |
| Year            | Year of manufacturing              |
| Selling_Price   | Price of the car (target variable) |
| Present_Price   | Original price when bought         |
| Kms_Driven      | Kilometers driven                  |
| Fuel_Type       | Petrol / Diesel / CNG              |
| Transmission    | Manual / Automatic                 |
| Owner           | Number of previous owners          |

## ⚙️ Machine Learning Models Used

- Linear Regression  
- Lasso Regression  
- Random Forest Regressor  


## 📊 Evaluation Metrics
- R² Score

## 📈 Result Highlights

- Random Forest gave predictions close to actual prices  
- Proper preprocessing significantly improved model accuracy  
- Visual comparisons between predicted and actual prices were plotted

## 🚀 Future Scope

- Deploy as a web app using Streamlit or Flask  
- Integrate real-time market data or API sources  
- Add explainability using SHAP or LIME  
- Expand dataset with location, accident history, etc.



 License
This project is licensed under the MIT License.
