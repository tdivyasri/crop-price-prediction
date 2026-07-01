# Crop Price Prediction using Machine Learning

## Overview

Agricultural markets are influenced by several factors, making it difficult for farmers and businesses to estimate the selling price of crops accurately. This project explores how machine learning can be used to predict crop prices by analyzing historical agricultural and environmental data.

The notebook covers the complete machine learning workflow—from cleaning raw data and exploring patterns to building predictive models and evaluating their performance. The goal was not only to build an accurate model but also to understand how different preprocessing techniques and algorithms affect prediction quality.

---

## Problem Statement

Crop prices fluctuate due to variations in production, cultivation costs, yield, weather conditions, and regional factors. Predicting these prices can support better decision-making for farmers, traders, and agricultural organizations.

This project aims to develop a regression model capable of estimating crop prices using these influencing factors.

---

## Project Workflow

The notebook follows a structured data science pipeline:

- Data loading and inspection
- Data cleaning and preprocessing
- Exploratory Data Analysis (EDA)
- Feature engineering
- Handling categorical variables
- Model training
- Performance evaluation
- Prediction and comparison of results

---

## Dataset

The dataset contains agricultural information including:

- Crop Name
- State
- Cost of Cultivation
- Production
- Yield
- Annual Rainfall
- Temperature
- Crop Price (Target Variable)

---

## Models Implemented

The following regression algorithms were used and compared:

- Linear Regression
- Decision Tree Regressor
- Support Vector Regressor (SVR)

Each model was evaluated using standard regression metrics to understand its predictive performance.

---

## Data Preprocessing

Before training the models, several preprocessing techniques were applied:

- Missing value handling
- Feature engineering
- Log transformation of skewed features
- One-Hot Encoding for categorical variables
- Feature scaling where required
- Train-test split

---

## Evaluation Metrics

Model performance was measured using:

- R² Score
- Mean Squared Error (MSE)

These metrics were used to compare the effectiveness of each regression algorithm.

---

## Technologies Used

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---

## Repository Structure

```
Crop-Price-Prediction/
│
├── crop_price_prediction.ipynb
├── crop_price.csv
├── README.md
```

---

## Running the Project

Clone the repository:

```bash
git clone https://github.com/your-username/Crop-Price-Prediction.git
```

Install the required libraries:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn notebook
```

Launch Jupyter Notebook:

```bash
jupyter notebook
```

Open `crop_price_prediction.ipynb` and execute the notebook cells in order.

---

## Key Learnings

Working on this project provided practical experience in:

- Building an end-to-end machine learning pipeline
- Performing exploratory data analysis
- Feature engineering and data preprocessing
- Comparing multiple regression models
- Evaluating model performance using regression metrics

---

## Future Improvements

Some possible enhancements include:

- Hyperparameter tuning
- Ensemble learning methods such as Random Forest and XGBoost
- Model deployment using Streamlit or Flask
- Integration with real-time agricultural datasets
- Building an interactive dashboard for predictions

---

## Contributing

Suggestions and improvements are always welcome. Feel free to fork the repository, open an issue, or submit a pull request.

---

## License

This project is intended for educational and learning purposes.
