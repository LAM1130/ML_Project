# Rental Price Prediction in Kuala Lumpur & Selangor

## Project Overview
This project aims to develop a predictive model for estimating rental prices in Kuala Lumpur and Selangor. The rental market in these regions is highly dynamic, with prices influenced by factors such as location, property size, number of bedrooms, and available amenities. By leveraging machine learning techniques, this project provides insights into rental pricing trends and helps tenants and landlords make informed decisions.

## Key Objectives
- **Analyze Factors Affecting Rent:** Identify the primary features influencing rental prices.
- **Develop a Predictive Model:** Use machine learning to estimate rental prices based on property attributes.
- **Provide Market Insights:** Offer insights into rental trends across different regions.
- **Enhance Decision-Making:** Assist landlords and tenants in making data-driven pricing decisions.

## Dataset
- **File:** `mudah-apartment-kl-selangor.csv`
- **Description:** The dataset consists of rental listings from Kuala Lumpur and Selangor, including attributes such as location, price, size, number of bedrooms, and amenities.

## Technologies Used
- **Programming Language:** Python
- **Libraries:**
  - Pandas
  - NumPy
  - Matplotlib
  - Seaborn
  - Scikit-learn

## Installation & Setup
1. Clone the repository or download the project files.
2. Install the required dependencies:
   ```bash
   pip install pandas numpy matplotlib seaborn scikit-learn
   ```
3. Run the Jupyter Notebook in Google Colab or locally:
   ```python
   from google.colab import drive
   drive.mount('/content/drive')
   ```
4. Load the dataset:
   ```python
   import pandas as pd
   data = pd.read_csv('mudah-apartment-kl-selangor.csv')
   data.info()
   ```

## Usage
- The notebook includes data preprocessing, exploratory data analysis (EDA), feature engineering, and model training.
- The predictive model uses Linear Regression to estimate rental prices.
- Performance metrics such as Mean Squared Error (MSE) and R-squared are used to evaluate the model.

## Contributors
- **Lam Zi Foong** (ID: 1221303175)
- **Chai Di Sheng** (ID: 1211101961)
- **Teoh Kai Loon** (ID: 1211101582)
- **Wong Kah Chun** (ID: 1221304973)

## License
This project is for educational purposes and is open-source.