PREDICTING HOUSE PRICES WITH MACHINE LEARNING
This project was focused on looking at key parameters which may help with a focus on our local market (Charlotte City, NC).
To avoid bias on data, we started with Charlotte NC and proceeded to include nine other Cities in deferent States; Boston MA, Atlanta GA, Chicago IL, Portland OR, Williamsburg VA, Cookeville TN, Waterloo IA, St Augustine FL, and Santa Fe NM.
ETL: 
•	Utilized Quandl and Zillow historical data dating back 25years (1995-2020) for most cities.
•	Pulled Separate JSON files for each City and converted to CSV files.
•	Uploaded the CSV files into MongoDb as one database.
•	Utilized Tableau for Visualization and Prediction of home values for each City over the next 5 years (2020-2025). https://public.tableau.com/authoring/FinalProject3Updated2/Dashboard1#1
FINDINGS:
Analysis of nearly 25 years of data for 10 Cities shows:
●	Using multiple Cities (Nationwide statistics) as proxy for specific Cities NOT recommended
●	Using other similar size Cities as proxy may work in certain cases. 
●	Trends in individual smaller Cities are unique and warrant a focused approach.
●	Prices in certain Cities (big and small) show variability at ALL Price Points whereas some Cities (big or small) shows variability only at higher price points.  
MODEL ACCURACY AND VALIDITY:
●	We tested the Accuracy and validity of the trained model using the Deep Neural Network. The model was not overfitting and therefore concluded as Accurate and Valid.
●	Margin of Error of Average Projected (2025) Home values, is representative of the R2 Score.  
●	A majority of the studied cities are projected to have an increase in home values over the next 5 years.  
