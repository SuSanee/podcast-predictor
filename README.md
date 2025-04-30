# 🎧 Predict Podcast Listening Time

## Description

This project aims to predict how long a user is likely to listen to a podcast episode based on metadata features like episode title, show information, and user behavior. Using machine learning regression models, the notebook explores various approaches to build a robust and accurate predictor. This is particularly useful for content recommendation engines and podcast platforms to understand engagement trends.

---

## Installation & Setup

1. Clone the repository:

  ```bash
  git clone https://github.com/SuSanee/podcast-predictor
  ```

2. Navigate to the project directory

  ```bash
  cd podcast-predictor
  ```

3. Install the required dependencies
```bash
pip install pandas numpy matplotlib seaborn scikit-learn xgboost
```

4. Run the notebook
```bash
jupyter notebook PredictPodcastListeningTime.ipynb 
```

## Usage

The dataset (train.csv) is already included in the repository.

Run the notebook PredictPodcastListeningTime.ipynb step-by-step to:

  Load and explore the dataset

  Preprocess the data (scaling, feature selection, PCA)

  Train various regression models (Lasso, Ridge, SVR, MLP, XGBoost, LightGBM, etc.)

  Ensemble models using VotingRegressor for better accuracy

  Evaluate results using RMSE and compare model performance


## Technologies Used

- Python
- NumPy
- Pandas
- Matplotlib
- Seaborn
- scikit-learn
  - StandardScaler, train_test_split
  - Lasso, MLPRegressor
  - VotingRegressor
  - cross_val_score, mean_squared_error
- XGBoost (XGBRegressor)

## References

Medium Blog: [Predicting Podcast Listening Time](https://medium.com/@23ucs604/633b620d6cb0)