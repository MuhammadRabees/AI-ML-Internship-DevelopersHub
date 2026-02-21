# AI-ML-Internship-DevelopersHub

# 📊 Task 1 — Data Analysis / Preprocessing

**Objective**
The objective of this task is to learn how to load, inspect, and visualize a dataset to understand data trends and distributions. This serves as the foundational step for exploratory data analysis (EDA) before moving into machine learning.

**Dataset Used**
* Name: Iris Dataset

* Source: Loaded directly via the seaborn Python library.

**Description:**
A classic dataset containing 150 records of iris flowers, consisting of four features (sepal length, sepal width, petal length, petal width) categorized into three distinct species.

**Models Applied**
None (Exploratory Data Analysis): Because this specific task focuses entirely on data exploration and visualization, no machine learning models were trained. Tools used include pandas for descriptive statistics and matplotlib/seaborn for visualization.

**Key Results and Findings**
* Data Integrity: The .info() check confirmed the dataset contains no missing values, meaning no imputation was necessary.

* Feature Relationships: The scatter plots revealed a clear distinction between species based on their measurements. The Setosa species forms a very distinct, linearly separable cluster compared to the others.

Distributions & Outliers: The histograms visualized the frequency distribution of feature sizes. Additionally, the box plots successfully identified a few minor outliers in the sepal width feature.

# 📈 Task 2 — Stock Price Prediction (Short-Term)
**Objective:**
To predict the next day’s closing stock price using historical market data.

**Dataset Used:**
Historical stock data retrieved using the yfinance Python library.

**Features Used:**

* Open price

* High price

* Low price

* Volume

* Previous day close price

**Model Applied:**
Random Forest Regressor

**Methodology:**

* Loaded historical stock data

* Created target variable (next day closing price)

* Added lag feature (previous close)

* Split dataset into training and testing sets

* Trained model

* Evaluated predictions

* Visualized actual vs predicted prices

**Key Results:**

Model successfully learned price patterns from historical data

Generated realistic next-day price predictions

Visualization confirmed prediction trend alignment with actual values

**Conclusion:**
Random Forest performed well for short-term prediction because it can capture nonlinear relationships in financial data.
