# Machine-Learning-Model-Prediction-Of-Flight-Delay
This model predicts if there is any delay in flight time. 
To do this we first used XGBoost Classifier and found if there will be any delay in the flight or not.
If there is a delay in flight we predict by how much time it will get delayed using linear regression.

# System Requirements: 
Jupyter Notebook 
The IPython Notebook is now known as the Jupyter Notebook. It is an interactive computational environment, in which you can combine code execution, rich text, mathematics, plots and rich media. 
Python API‟s & Libraries requirements 
Matplotlib 
Matplotlib is a Python 2D plotting library which produces publication quality figures in a variety of hardcopy formats and interactive environments across platforms.Matplotlib tries to make easy things easy and hard things possible.
Sklearn 
Scikit-learn provides a range of supervised and unsupervised learning algorithms via a consistent interface in Python. 
NumPy 
NumPy is the fundamental package for scientific computing in Python. 
Pandas 
Pandas is a Python package providing fast, flexible, and expressive data structures designed to make working with “relational” or “labelled” data both easy and intuitive. 
Seaborn 
Seaborn is a Python data visualization library based on matplotlib. It provides a high-level interface for drawing attractive and informative statistical graphics.

# Dataset:
Flight Dataset: 
The US Bureau of Transport Statistics provides data on all domestic flights, including their scheduled and actual departure and takeoff times, date, origin, destination and carrier. 
Weather Dataset: 
The Local Climatological Data from NOAA includes the closest available weather data at the departure airport along with the standard flight data. The departure airport weather features include temperature, humidity, air pressure, and precipitation type and amount, if any. 
Final Dataset: 
Joining the flight and weather datasets to form final dataset: i. e., code used to join two datasets was: PLACE.YEAR.MONTH.DAY.HOUR

# TESTING AND RESULTS:
Result of Classification model: 
accuracy score: 94.1%
precision: 90.1%
recall: 71.0% f1 score: 79.4%
auc score: 84.7%
Result of Regression model: 
mean absolute error: 8.05 mins
root mean square error: 10.77 mins
r2-score: 0.93
Result of Overall model: 
mean absolute error: 9.12 mins
root mean square error: 12.70 mins
r2-score: 0.90
