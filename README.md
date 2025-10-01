# Olympic Medal Prediction 

This project uses Linear Regression to predict the number of medals won by countries in the Olympic Games based on historical performance and team characteristics.

 ***Project Overview***

Accurately predicting Olympic medal counts helps analyze performance trends across nations. This project applies machine learning to historical Olympic datasets, focusing on team-level attributes such as athlete count, average age, and prior medal history.

 ***Dataset***

The dataset includes:

* Team / Country

* Year

* Number of Athletes

* Average Age

* Previous Medals

* Actual Medals

 ***Tech Stack***

 * Python

* Pandas, NumPy (data processing)

* Seaborn (visualization)

* Scikit-learn (machine learning)

 ***Workflow***

* Data Preprocessing

* Cleaning and formatting Olympic dataset.

* Exploratory Data Analysis (EDA)

* Trends across teams, athletes, and medals.

 ***Model Building***

* Applied Linear Regression for prediction.

* Evaluation

* Mean Absolute Error (MAE).

* Error analysis by country.

 ***Sample Results***
 
| Country | Year | Athletes | Previous Medals | Actual Medals | Predicted Medals |
|---------|------|----------|-----------------|---------------|------------------|
| USA     | 2012 | 530      | 103             | 248           | 285              |
| USA     | 2016 | 554      | 104             | 264           | 236              |
| IND     | 2012 | 83       | 3               | 6             | 7                |
| IND     | 2016 | 117      | 2               | 2             | 12               |


* High medal-winning countries (USA, Russia, China) → Model performs well with low percentage error.

* Low medal-winning countries (India, Nigeria, etc.) → Model error is higher due to limited data.

 ***Key Insights***

* Predictions are more reliable for countries with a strong Olympic history.

* Relative error is smaller for teams with high medal counts.

* Improvements possible with feature engineering and advanced models.
