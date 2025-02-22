# Sales Analysis Using Linear Regression 1

# Introduction
Technological advancements have significantly impacted sales by enabling real-time data access, business process automation, and in-depth analytics. Companies utilize big data to understand consumer behavior, optimize marketing strategies, and improve operational efficiency.

Linear Regression is a powerful method for analyzing relationships between sales-related factors such as seasonal trends, pricing, and marketing campaigns. By leveraging big data analytics, businesses can make more accurate sales predictions and optimize strategies proactively.

# Features
1. Data Preprocessing: Cleaning and preparing dataset.
2. Exploratory Data Analysis (EDA): Understanding sales trends through visualizations.
3. Linear Regression Model: Predicting sales trends using historical data.
4. Correlation Analysis: Identifying relationships between variables.
5. Performance Metrics: Evaluating model accuracy using RMSE, R², and MSE.

# Technologies Used
1. Programming Language: Python
2. Libraries: pandas, numpy, matplotlib, seaborn, scikit-learn

Dataset
The dataset, sourced from Kaggle, contains online retail transaction data. It includes attributes such as:

1. Invoice Number
- Stock Code & Product Description.
- Quantity & Unit Price.
- Transaction Date & Time.
- Customer Country.
- Data preprocessing involves handling missing values, outliers, and transforming categorical variables into numerical formats.

# Installation & Usage
1. **Clone this repository:**
   ```bash
   git clone https://github.com/azkalltlhn/Sales-Analysis-Using-Linear-Regression.git

2. **Install the required dependencies::**
   ```bash
   pip install numpy pandas scikit-learn matplotlib seaborn

3. Run the Notebook
- Open Jupyter Notebook or Google Colab.
- Load BIGDATA.ipynb.
- Execute all cells to see data analysis and model predictions.

# Results & Evaluation
The Linear Regression model is evaluated using various metrics:
1. Mean Squared Error (MSE): Measures the average squared difference between actual and predicted sales values.
2. Root Mean Squared Error (RMSE): The square root of MSE, making the error measure interpretable.
3. R² Score (Coefficient of Determination): Indicates how well independent variables explain the variance in sales.

# Key Insights:
1. The model successfully identified correlations between sales volume and influencing factors.
2. Seasonal trends, product pricing, and marketing activities were found to significantly impact sales.
3. Predictive analysis helped optimize inventory management and marketing strategies.
