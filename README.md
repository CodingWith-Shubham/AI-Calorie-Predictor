# AI Calorie Predictor 

This project is a machine learning-based Calorie Predictor that uses a Random Forest Regression model to estimate calories burned during physical activity. Built to assist in fitness tracking and health analytics.

##  Features

- Predicts calories burned using user-specific data
- Trained on real-world dataset
- Uses Random Forest Regressor for accurate predictions
- Simple and easy to use

##  Tech Stack

- Python
- Pandas
- Scikit-learn
- Matplotlib / Seaborn (for visualization, optional)

##  Dataset

Used a dataset containing features such as:
- Age
- Gender
- Height
- Weight
- Duration
- Heart Rate
- Body Temperature

(Target: Calories burned)

##  Model

- Random Forest Regressor
- Train-test split (e.g., 80/20)
- Evaluation metrics: R² Score, MAE, MSE

##  How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/calorie-predictor.git
   cd calorie-predictor
2.Install dependencies:

 ```bash
pip install -r requirements.txt
Run the notebook or script:
python calorie_predictor.py

📈 Results
The model achieved a high R² score, indicating reliable predictions for most user inputs.
