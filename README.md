# ShopSmart-Ecommerce-Purchase-Prediction
A machine learning project that analyzes e-commerce browsing behavior and predicts whether an online shopping session will generate revenue using exploratory data analysis and a Decision Tree classifier.
# ShopSmart – E-commerce Purchase Prediction

## Overview
ShopSmart is a machine learning project that analyzes online shopping session data to understand customer browsing behavior and predict whether a session results in revenue.

The project uses exploratory data analysis, data visualization, feature correlation analysis, and a Decision Tree classifier to study purchase conversion patterns.

## Objectives
- Understand customer browsing and shopping-session behavior.
- Analyze the factors associated with revenue generation.
- Visualize visitor activity and product-related browsing duration.
- Explore correlations between numerical features and revenue.
- Build and evaluate a machine learning classification model.

## Dataset
- **Records:** 12,330
- **Features:** 17 input features and 1 target variable
- **Target variable:** `Revenue`
- **Target type:** Binary classification

The dataset includes administrative activity, informational pages, product-related browsing, bounce rates, exit rates, page values, visitor type, traffic type, month, weekend activity, and other session attributes.

## Technologies Used
- Python
- Pandas and NumPy
- Matplotlib and Seaborn
- Scikit-learn
- Jupyter Notebook

## Exploratory Data Analysis
The project explores:
- Revenue-generating versus non-revenue-generating sessions.
- Product-related browsing duration by revenue outcome.
- Visitor-type distribution.
- Visitor type in relation to revenue generation.
- Correlations between numerical features and revenue.

## Machine Learning Workflow
1. Load and inspect the dataset.
2. Explore customer behavior using visualizations.
3. Encode categorical and Boolean variables.
4. Analyze feature correlations.
5. Separate the input features and target variable.
6. Split the dataset into training and testing sets using an 80:20 ratio.
7. Apply StandardScaler to the training and testing features.
8. Train a Decision Tree classifier with `max_depth=8`.
9. Evaluate predictions using classification metrics.

## Model Evaluation
The notebook evaluates the classifier using:
- Confusion Matrix
- Accuracy
- Precision
- Recall
- F1-score

## Repository Structure
```text
ShopSmart-Ecommerce-Purchase-Prediction/
├── Shopsmart.ipynb
├── shop_smart_ecommerce.csv
└── README.md
```

## How to Run
1. Clone or download the repository.
2. Install the required libraries:
   ```bash
   pip install pandas numpy matplotlib seaborn scikit-learn jupyter
   ```
3. Open the notebook:
   ```bash
   jupyter notebook Shopsmart.ipynb
   ```
4. Ensure the CSV dataset is in the same directory.
5. Run the notebook cells in order.

## Disclaimer
This project is intended for educational purposes and exploratory analysis. Its predictions should not be treated as guaranteed indicators of actual customer purchases.
