# Uber Trip Analysis & Weekly Trip Prediction

A Python-based data analysis and machine learning project that analyzes Uber pickup patterns and predicts weekly trip demand using real-world Uber pickup data.

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Joblib
* Jupyter Notebook

## Project Highlights

* Analyzed Uber pickup data from April to September 2014
* Performed exploratory data analysis on hourly, daily, weekday and weekly trip patterns
* Identified peak trip hours and busiest days
* Built a Linear Regression model for weekly trip prediction
* Evaluated the model using MAE, RMSE and R² Score
* Saved the trained model using Joblib
* Generated a weekly demand prediction for the next week in the project dataset

## Machine Learning

A Linear Regression model was trained using chronological weekly trip data.

**Evaluation Metrics:**

* MAE: 25,544.26
* RMSE: 27,032.59
* R² Score: 0.1383

The model predicted approximately **222,841 trips** for the next week in the project dataset.

## Project Structure

```text
Uber-Trip-Analysis/
├── data/
├── models/
│   └── uber_weekly_prediction_model.pkl
├── notebooks/
│   └── uber_trip_analysis.ipynb
├── .gitignore
├── requirements.txt
└── README.md
```

## Dataset

The project uses the FiveThirtyEight Uber TLC FOIL Response dataset containing Uber pickup records from April–September 2014.

The raw CSV files are kept locally and excluded from this repository using `.gitignore`.

 ## Future Improvements :

* Add more time-based features
* Compare additional machine learning models
* Improve prediction accuracy
* Add interactive visualizations
* Build a simple web interface for prediction
