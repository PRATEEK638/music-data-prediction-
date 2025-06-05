This GitHub project uses machine learning regression models to predict song popularity based on Spotify-style audio features.

**What I have used:**

* **Python**: The core programming language.
* **Pandas, NumPy**: For data manipulation and numerical operations.
* **Scikit-learn**: For implementing various machine learning regression models (Linear Regression, Random Forest Regressor, Gradient Boosting Regressor).
* **Matplotlib, Seaborn**: For data visualization.
* **Jupyter Notebook**: For interactive coding, analysis, and model development.
* **`train.csv`**: Training data with audio features and song popularity.
* **`test.csv`**: Real-world test set for model evaluation without popularity scores.

**What I have done:**

* **Data Preprocessing**: Loaded and cleaned a dataset of over 21,000 songs, handled missing values, and selected key audio features (e.g., `release_year`, `loudness`, `speechiness`, `instrumentalness`, `acousticness`).
* **Model Training**: Implemented and compared multiple regression models to estimate track popularity.
* **Model Evaluation**: Used `test.csv` to evaluate models, comparing actual vs. predicted popularity scores using Root Mean Squared Error (RMSE) and visualizations.
* **Key Findings**: Discovered that Random Forest and Gradient Boosting models generally outperformed Linear Regression, showing higher accuracy in predicting song popularity.
