# Stock-Recommendations
Machine Learning and Data Mining

# Stock Recommendation System through Financial Market Analysis

## Project Overview
This project aims to recommend stocks to investors by analyzing financial data of global companies. By evaluating key financial metrics and market trends, the system helps users make informed investment decisions based on their risk tolerance and preferences. This information assists millions of investors in
determining where to place their money. We take a look at stock market performance
for thousands of companies which provides directions on how to go about
investment strategies and helps know the market trends. 

---

## Dataset
- **Source**: Kaggle
- **Features**:
  - **Symbol**: Unique stock ticker
  - **Sector**: Industry sector (e.g., Technology, Healthcare)
  - **Country**: Company headquarters location
  - **Market Capitalization**: Total market value of shares
  - **Current Ratio**: Liquidity metric
  - **Beta**: Stock volatility relative to the market
  - **Dividend Rate**: Annual dividend as a percentage of share price
- **Size**: 1,775 companies with 8 attributes each.

---

## Tech Stack
- **Languages**: Python
- **Libraries**:
  - **Data Handling**: `pandas`, `numpy`
  - **Visualization**: `matplotlib`, `seaborn`
  - **Machine Learning**: `scikit-learn` (K-Means, Random Forest, Decision Trees), `XGBoost`
  - **Clustering**: K-Means, K-Medoids, Fuzzy C-Means
  - **Dimensionality Reduction**: PCA, t-SNE
- **Preprocessing**: Data cleaning, scaling (normalization), missing value imputation.

---

## Key Steps
1. **Data Cleaning**: Handled missing values, removed duplicates, and standardized formats.
2. **Exploratory Data Analysis (EDA)**:
   - Analyzed sector/country distributions.
   - Explored relationships between variables (e.g., Market Cap vs. Dividend Rate).
3. **Clustering**:
   - Grouped companies into 3 clusters using K-Means, K-Medoids, and Fuzzy C-Means.
   - Identified high-value, stable, and high-dividend companies.
4. **Dimensionality Reduction**:
   - Applied PCA and t-SNE to visualize high-dimensional data.
5. **Classification Models**:
   - Trained Random Forest, Decision Trees, and XGBoost to classify stocks as "Good" or "Bad."
   - Evaluated performance using MSE, confusion matrices, and AUROC curves.

---

## Results
- **Top Features**: Market Cap, Beta, and Current Ratio were most influential in predictions.
- **Best Model**: Random Forest achieved the lowest MSE (most accurate).
- **Recommendations**: Stocks with lower dividend rates and moderate market capitalization were often classified as "Good" investments.
- **Insights**: Financial Services, Energy, and Consumer Defensive sectors offered higher average dividend rates.

---

## How to Use
1. Clone the repository and install required libraries.
2. Run the Jupyter notebook to preprocess data, train models, and generate visualizations.
3. Adjust investment criteria (sector, risk tolerance) in the code for personalized recommendations.

---

**Note**: Full code and visualizations are available in the project files. Refer to the report for detailed analysis and methodology.

![image](https://github.com/user-attachments/assets/a3b7b585-1963-40a4-9734-5961d1f97641)

