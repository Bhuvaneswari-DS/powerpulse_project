# powerpulse_project
📌 Project Overview This dashboard allows users to explore about power supply of one organisation as the name of power pulse project.

✅ Here the data includes of date and time wise data for the power consumption as reactive power and active power. Units calculated on the basis of sub metering 1,2 and 3.
Initialised as 9 columns only in raw data, but we have to analysis through this we get moere column for our prediction of results we got 23 columns. As per the seperation
of parse date and time, weekday also.

For our machine learning, we have install scikit-learn, check the columns not having null or Nan values, whether load the data for test and train the appropriate percentage,
then let it give for training the models and predict the value.
Choose the correct model for machine learning as per the dataset range, and lets give in the code as the name of the model, then back of it runs the algorithms and formulas 
for the given model.  We train it by 2 or 3 models, then also predict the best model as well.
Here did this methods to analyse the power consumption of daily, weekly and monthly basis.
Some graphs also used as correlation matrix heatmap, kde plot, barplot and so on.

i have used Machine Learning algorithms are Linear Regression, Randam Forest Regressor, Decision Tree, Gradient boost regressor for train and test.
After that i have found that best model to perform good for this huge dataset is Random Forest Regressor.

