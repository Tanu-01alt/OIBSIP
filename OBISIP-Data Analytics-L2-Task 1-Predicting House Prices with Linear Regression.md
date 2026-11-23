# 🏠 House Price Prediction Using Linear Regression

## 📌 Project Overview

This project focuses on predicting house prices using Machine Learning techniques, specifically Linear Regression. The model analyzes different housing features such as overall quality, living area, garage capacity, basement area, number of bedrooms, bathrooms, and neighborhood to predict the sale price of a house.

The project involves data exploration, data preprocessing, categorical encoding, correlation analysis, model training, prediction, and performance evaluation.

This project is completed as part of the **Oasis Infobyte Internship (OIBSIP) – Data Analytics / Machine Learning Project**.

## 🎯 Project Objectives

- Understand and explore the house prices dataset.
- Perform data inspection and preprocessing.
- Handle missing values using appropriate imputation techniques.
- Convert categorical variables into numerical format.
- Identify important features affecting house prices.
- Analyze correlations between housing features and sale prices.
- Train a Linear Regression model.
- Predict house prices using test data.
- Evaluate model performance using regression metrics.

## 📂 Dataset Information

**Dataset Name:** `house_prices.csv`

The dataset contains 1,460 records and 14 columns related to house characteristics and selling prices.

### Dataset Features

| Column Name | Description |
|---|---|
| OverallQual | Overall quality of the house |
| GrLivArea | Above-ground living area |
| GarageCars | Garage capacity in number of cars |
| GarageArea | Garage area |
| TotalBsmtSF | Total basement area |
| 1stFlrSF | First-floor area |
| 2ndFlrSF | Second-floor area |
| YearBuilt | Year the house was constructed |
| Bedrooms | Number of bedrooms |
| Bathrooms | Number of bathrooms |
| HouseAge | Age of the house |
| YearsSinceRemodel | Years since the house was remodeled |
| Neighborhood | Location of the property |
| SalePrice | Target variable representing house selling price |

## 🛠️ Technologies & Tools Used

- **Python** – Programming language
- **VS Code** – Development environment
- **JupyterLab** – Interactive notebook environment
- **Pandas** – Data manipulation and analysis
- **NumPy** – Numerical operations
- **Matplotlib** – Data visualization
- **Seaborn** – Statistical data visualization
- **Scikit-learn** – Machine Learning and model evaluation

## ⚙️ Installation & Setup

### Step 1: Install Python

Download Python from:

https://www.python.org/downloads/

### Step 2: Install VS Code

Download Visual Studio Code:

https://code.visualstudio.com/

### Step 3: Install Required Libraries

Open Command Prompt or VS Code terminal and execute:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn jupyterlab
```

### Step 4: Launch JupyterLab

Run the following command:

```bash
python -m jupyterlab
```

Alternatively:

```bash
jupyter lab
```

### Step 5: Run the Project

1. Open your project folder in VS Code.
2. Launch JupyterLab.
3. Open `Predicting House Prices with Linear Regression.ipynb`.
4. Make sure `house_prices.csv` is available in the project directory.
5. Execute the notebook cells sequentially.

## 🔍 Project Workflow

### 1. Data Loading and Exploration
- Imported Pandas and NumPy.
- Loaded the house prices dataset.
- Checked dataset dimensions and column names.
- Examined data types and statistical information.

### 2. Data Preprocessing
- Identified missing values.
- Applied median imputation to numerical columns.
- Applied mode imputation to categorical columns.
- Verified that missing values were handled.

### 3. Categorical Encoding
- Identified categorical features.
- Applied One-Hot Encoding to the Neighborhood column.
- Converted categorical values into numerical features.
- Prepared the dataset for Machine Learning.

### 4. Correlation Analysis
- Calculated correlation between numerical features.
- Created a correlation heatmap.
- Identified features strongly associated with SalePrice.

### 5. Train-Test Split
- Separated input features (X) and target variable (y).
- Split the dataset into training and testing sets.
- Used 80% of the data for training and 20% for testing.
- Applied random_state=42.

### 6. Model Building
- Imported Linear Regression from Scikit-learn.
- Created a Linear Regression model.
- Trained the model using the training dataset.
- Generated predictions using test data.

### 7. Model Evaluation
Evaluated the model using:

- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)
- R² Score

### 8. Data Visualization
- Created a histogram to understand house price distribution.
- Created a correlation heatmap.
- Created an Actual vs Predicted House Prices scatter plot.

## 📊 Model Performance

The Linear Regression model achieved the following results:

| Evaluation Metric | Result |
|---|---:|
| MAE | 16,390.30 |
| MSE | 455,560,092.25 |
| RMSE | 21,343.85 |
| R² Score | 0.9356 |

**Model Accuracy:** The R² score indicates that the model explains approximately 93.56% of the variation in house prices on the test dataset. This is an R² score, not a classification accuracy percentage.

## 💡 Key Insights

- OverallQual has the strongest positive correlation with SalePrice (0.7468).
- GrLivArea has a positive correlation with SalePrice (0.4732).
- TotalBsmtSF also shows a positive relationship with house prices.
- YearBuilt is positively correlated with SalePrice.
- HouseAge has a negative correlation with SalePrice.
- The Linear Regression model successfully generated house price predictions.
- The Actual vs Predicted scatter plot helps visualize the model's prediction performance.

## 📁 Project Structure

```text
Task-3-House-Price-Prediction/
│
├── house_prices.csv
│
├── Predicting House Prices with Linear Regression.ipynb
│
└── README.md
```

## 🎓 Learning Outcomes

- Learned the fundamentals of Machine Learning.
- Understood Linear Regression.
- Gained experience in data preprocessing.
- Learned One-Hot Encoding for categorical variables.
- Understood feature correlation and selection.
- Practiced training and testing Machine Learning models.
- Learned regression evaluation metrics.
- Developed practical skills in Python and Scikit-learn.

## 👩‍💻 Author

**Tanushree Adsule**

Data Analytics / Machine Learning Intern

## 🏢 Internship Details

- **Organization:** Oasis Infobyte
- **Domain:** Data Analytics / Machine Learning
- **Project:** House Price Prediction Using Linear Regression


