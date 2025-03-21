# Movie-Rating-Prediction

## Overview
This project aims to predict movie ratings based on various factors such as genre, director, cast, and user reviews. The dataset contains movie-related features and user ratings, which will be used to train machine learning models for accurate predictions.

## Objectives
- Perform data preprocessing and exploratory data analysis (EDA)
- Apply feature engineering to enhance model performance
- Train machine learning models to predict movie ratings
- Evaluate model performance using suitable metrics

## Dataset
The dataset consists of:
1. `movies.csv` - Contains movie metadata such as title, genre, director, and release year.
2. `ratings.csv` - Contains user ratings for different movies.
3. `users.csv` - (Optional) Contains user demographic information.

## Requirements
Ensure you have the following installed:
- Python (>=3.8)
- Jupyter Notebook or any Python IDE
- Required libraries:
  ```bash
  pip install pandas numpy matplotlib seaborn scikit-learn
  ```

## Steps to Run the Project
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/movie-rating-prediction.git
   cd movie-rating-prediction
   ```
2. Download the dataset and place it in the project directory.
3. Open the Jupyter Notebook:
   ```bash
   jupyter notebook Movie_Rating_Prediction.ipynb
   ```
4. Run the notebook to preprocess the data, train models, and generate predictions.
5. Modify and test different models to improve accuracy.

```

## Machine Learning Models Used
- Linear Regression
- Random Forest Regressor
- Support Vector Regressor (SVR)
- Gradient Boosting Regressor

## Evaluation Metrics
- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- R-squared Score

## Contributing
Feel free to submit pull requests or report issues. Contributions are welcome!

## License
This project is licensed under the MIT License.

