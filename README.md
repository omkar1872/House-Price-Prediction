# House Price Prediction (Regression Project)

This project builds a machine learning model to predict house prices based on various features such as area, bedrooms, bathrooms, parking, and furnishing status.

---

## Project Overview

The goal is to develop a regression model that can accurately estimate house prices using features related to the property and its amenities. The project includes data cleaning, preprocessing, exploratory data analysis, modeling, evaluation, and prediction steps.

---

## Dataset Features

| Feature             | Type        | Description                             |
|---------------------|-------------|---------------------------------------|
| Price               | Numerical   | Target variable (house price)         |
| Area                | Numerical   | Size of the house                      |
| Bedrooms            | Numerical   | Number of bedrooms                     |
| Bathrooms           | Numerical   | Number of bathrooms                    |
| Stories             | Numerical   | Number of floors                       |
| Main Road           | Binary      | Whether house is on main road (yes/no)|
| Guest Room          | Binary      | Guest room availability (yes/no)      |
| Basement            | Binary      | Basement availability (yes/no)        |
| Hot Water Heating   | Binary      | Hot water heating availability (yes/no)|
| Air Conditioning    | Binary      | Air conditioning availability (yes/no)|
| Parking             | Numerical   | Number of parking spaces               |
| Preferred Area      | Binary      | Preferred area (yes/no)                |
| Furnishing Status   | Categorical | Furnished, semi-furnished, unfurnished|

---

## Steps Followed

### 1. Load Data
- Read the CSV file into a pandas DataFrame.

### 2. Rename Columns
- Rename columns to readable and consistent names.

### 3. Handle Categorical Variables
- Map binary 'yes'/'no' to 1/0.
- One-hot encode the 'Furnishing Status' categorical column.

### 4. Remove Outliers
- Detect and remove outliers using the IQR method in numerical columns.

### 5. Feature Scaling
- Apply `StandardScaler` to scale numerical features.

### 6. Split Dataset
- Split the dataset into training and test sets (80%-20%).

### 7. Model Training
- Train a Linear Regression model on training data.

### 8. Model Evaluation
- Evaluate the model with RMSE and R² score on test data.

### 9. Make Predictions
- Use the trained model to predict house price for new inputs.

---
## Contact & Contributions

I welcome feedback and collaboration.  
Feel free to connect:

- GitHub: [https://github.com/omkar1872](https://github.com/omkar1872)  
- LinkedIn: [https://linkedin.com/in/omkar1872](https://www.linkedin.com/in/omkar1872/)  
- Email: chomkar1872@gmail.com


---
