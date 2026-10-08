# Movie Rating Prediction with Python

Predicts IMDb ratings of Indian movies using regression.

## Dataset
IMDb Movies India (15,509 movies; 7,919 with ratings used for training).

## Steps
1. Data cleaning (Year, Duration, Votes parsing, missing values)
2. EDA (rating distribution, genres, correlations)
3. Feature engineering (smoothed out-of-fold target encoding, log votes)
4. Models: Linear Regression, Random Forest, Gradient Boosting
5. Evaluation: MAE, RMSE, R²

## Results
Random Forest: MAE 0.80, RMSE 1.05, R² 0.41

## Tech
Python, pandas, NumPy, scikit-learn, matplotlib, seaborn

## Run
pip install pandas numpy scikit-learn matplotlib seaborn
jupyter notebook Movie_rating_system.ipynb