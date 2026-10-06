# 🏠 House Price Data Analysis

<img width="1024" height="100" alt="image" src="https://github.com/user-attachments/assets/9d8e78b0-1565-40c9-ad8c-b27c2ba4d73a" />


## 📊 House Prices Prediction & Exploratory Data Analysis

This project focuses on analyzing residential housing data and understanding the factors that influence **house sale prices**.

The dataset contains information about different aspects of residential properties, including house quality, living area, basement, garage, neighborhood, year built, and many other features. The main target variable is **`SalePrice`**, which represents the final sale price of each house.

---

## 🎯 Project Objective

The main objective of this project is to explore housing data and identify the important factors that affect house prices.

### Key objectives:

* 🔍 Explore the housing dataset
* 🧹 Clean and preprocess the data
* 📊 Perform Exploratory Data Analysis (EDA)
* 📈 Analyze relationships between features and house prices
* 🏠 Identify important factors affecting `SalePrice`
* 📉 Visualize housing price patterns
* 🤖 Prepare the dataset for machine learning
* 💰 Build a foundation for house price prediction

---

## 📁 Dataset

The dataset used in this project is:

```text
train.csv
```

The dataset contains **1,460 residential property records** with numerous features describing each house.

The target variable is:

```text
SalePrice
```

### Important Features

| Feature        | Description                         |
| -------------- | ----------------------------------- |
| `OverallQual`  | Overall material and finish quality |
| `OverallCond`  | Overall condition of the house      |
| `YearBuilt`    | Original construction year          |
| `YearRemodAdd` | Remodeling year                     |
| `GrLivArea`    | Above-ground living area            |
| `TotalBsmtSF`  | Total basement area                 |
| `1stFlrSF`     | First-floor area                    |
| `2ndFlrSF`     | Second-floor area                   |
| `FullBath`     | Number of full bathrooms            |
| `BedroomAbvGr` | Bedrooms above ground               |
| `GarageCars`   | Garage capacity in cars             |
| `GarageArea`   | Garage area                         |
| `Neighborhood` | Physical location of the property   |
| `LotArea`      | Lot size                            |
| `SalePrice`    | Final sale price — target variable  |

The actual dataset contains many additional categorical and numerical features.

---

## 🔎 Dataset Structure

The dataset contains information about:

### 🏡 Property Information

* Lot Area
* Lot Shape
* Neighborhood
* Building Type
* House Style
* Overall Quality
* Overall Condition

### 🧱 Construction Information

* Year Built
* Year Remodeled
* Exterior Materials
* Foundation
* Roof Style
* Heating System

### 🛋️ Interior Information

* Living Area
* Bedrooms
* Bathrooms
* Kitchens
* Total Rooms
* Basement Area
* First Floor Area
* Second Floor Area

### 🚗 Garage & Outdoor Features

* Garage Type
* Garage Area
* Garage Capacity
* Wood Deck
* Open Porch
* Enclosed Porch
* Pool Area

### 💰 Target Variable

```text
SalePrice
```

This is the variable that can be analyzed or predicted using the available house features.

---

## 🛠️ Technologies Used

* 🐍 Python
* 📓 Jupyter Notebook
* 🐼 Pandas
* 🔢 NumPy
* 📊 Matplotlib
* 📈 Seaborn
* 🤖 Scikit-learn
* 💻 Git & GitHub

---

## 🔄 Data Analysis Workflow

```text
Dataset
   ↓
Data Loading
   ↓
Data Exploration
   ↓
Data Cleaning
   ↓
Missing Value Analysis
   ↓
Exploratory Data Analysis
   ↓
Feature Analysis
   ↓
Data Visualization
   ↓
Feature Engineering
   ↓
Machine Learning Preparation
   ↓
House Price Prediction
```

---

## 📊 Exploratory Data Analysis

The project can analyze important relationships such as:

### 1. House Quality vs Sale Price

`OverallQual` can be compared with `SalePrice` to understand how house quality relates to the final selling price.

### 2. Living Area vs Sale Price

`GrLivArea` can be analyzed against `SalePrice` to understand the relationship between living space and property value.

### 3. Year Built vs Sale Price

The construction year can be studied to understand how newer or older properties differ in price.

### 4. Neighborhood vs Sale Price

Different neighborhoods can be compared based on their average or median house prices.

### 5. Garage Features vs Sale Price

Garage capacity and garage area can be analyzed to determine their relationship with property prices.

---

## 📈 Recommended Visualizations

The following visualizations can be created from the dataset:

* 📊 Sale Price Distribution
* 📈 GrLivArea vs SalePrice
* 🏠 OverallQual vs SalePrice
* 📅 YearBuilt vs SalePrice
* 📍 Neighborhood vs SalePrice
* 🚗 GarageCars vs SalePrice
* 🔥 Correlation Heatmap
* 📦 Boxplots for categorical features
* 📊 Top Features Affecting SalePrice

---

## 🖼️ Project Visualization

### House Price Analysis Dashboard

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/b0c74fae-2395-4dc5-90cb-4badb2a03085" />


> Add your own analysis chart/dashboard to this section after creating it from the dataset.

---

## 🧹 Data Preprocessing

The dataset contains both numerical and categorical variables.

Typical preprocessing steps include:

* Handling missing values
* Detecting duplicate records
* Converting categorical variables
* Encoding categorical features
* Scaling numerical variables when required
* Detecting outliers
* Selecting important features

---

## 🤖 Machine Learning

This dataset can also be used for a **regression problem**, where the objective is to predict:

```text
SalePrice
```

Possible machine learning models include:

* Linear Regression
* Ridge Regression
* Lasso Regression
* Decision Tree Regressor
* Random Forest Regressor
* Gradient Boosting
* XGBoost

Model performance can be evaluated using:

* MAE
* MSE
* RMSE
* R² Score

---

## 💡 Expected Insights

The analysis can help identify:

* Which house characteristics have the strongest relationship with price.
* How overall house quality affects selling price.
* Whether larger living areas are associated with higher prices.
* How neighborhood influences property value.
* How construction and remodeling years relate to prices.
* Which features are most useful for machine learning.

---

## 📂 Project Structure

```text
train-data/
│
├── 📊 train.csv
├── 📓 analysis.ipynb
├── 🖼️ house-price-analysis.png
└── 📄 README.md
```

---

## 🚀 How to Run the Project

### 1. Clone the repository

```bash
git clone https://github.com/khushiyadav222/train-data.git
```

### 2. Open the project

```bash
cd train-data
```

### 3. Install required libraries

```bash
pip install pandas numpy matplotlib seaborn scikit-learn jupyter
```

### 4. Start Jupyter Notebook

```bash
jupyter notebook
```

Then open the analysis notebook and run the cells.

---

## 📌 Future Improvements

* Build a complete house price prediction model
* Perform advanced feature engineering
* Compare multiple regression algorithms
* Tune machine learning hyperparameters
* Create an interactive dashboard
* Add model evaluation charts
* Deploy the prediction model as a web application


## ⭐ Conclusion

This project demonstrates how **Python, data analysis, visualization, and machine learning** can be used to understand residential housing data.

By analyzing property characteristics and their relationship with `SalePrice`, the project provides a strong foundation for **Exploratory Data Analysis and House Price Prediction**.

⭐ **If you find this project useful, consider giving the repository a star!**
