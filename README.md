# **Vehicle Price Prediction Project**

## **Introduction**
One of the most important practices in the automotive industry is the ability to predict the price of a vehicle. This is especially important for the automotive industry as it is an extremely competitive market and the ability to predict the price of a vehicle is a key factor in the success of a dealership. The ability to predict the price of a vehicle is also important for the consumer as it allows them to make an informed decision on the purchase of a vehicle. This is a perfect area to apply data science techniques as the data is readily available and the problem is well defined.

## **Problem Statement**
The sale of vehicles is a complex process. There are many factors that influence the price which are not always obvious. This could mean that a vehicle is not sold at the price it is worth, or that a vehicle is sold at a price that is too high. This equates to a loss of revenue for the dealership and a loss of value for the customer. To maximize the revenue of a dealership, it is important to understand the factors that influence the sale of a vehicle.

## **Business Task**
The key task is to find out what features have a significant impact on the sale price of a vehicle and build a predictive model that can be used to predict the sale price based on its features. The insights gathered here can be used by the car dealers to price their vehicles competitively and by the customers to get a fair idea of the price of the vehicle they are interested in.

## **The Data**
This data was obtained using web scraping techniques on [cargurus.com](https://www.cargurus.com/). This data is for academic, research and individual experimentation only and is not intended for commercial purposes. This dataset contains 3 million new and used vehicle listings in the United States. The data set can be downloaded on [Kaggle.com](https://www.kaggle.com/datasets/ananaymital/us-used-cars-dataset?select=used_cars_data.csv). The data dictionary can be downloaded/reviewed [here](https://drive.google.com/file/d/177p54r5GarfVBSzNn3jFTkHS1N-yXNwx/view?usp=share_link)

## **Data Cleaning and Preprocessing**
In preparation for analysis and modeling, the data was cleaned and preprocessed using traditional data cleaning techniques. Standard data cleaning techniques such as removing duplicates, removing, or imputing missing values, removing outliers, and removing unnecessary columns were performed. Then the data was transformed using feature engineering techniques that were specific to the data. 


## **Exploratory Data Analysis**
Through the EDA, we have learned that the features of the vehicle are important to predicting the price of a vehicle. The features of the vehicle include the year, make, model, engine type, transmission type, mileage, speed, size, and if the vehicle has an incident. These features are important to predicting the price of a vehicle because they have a high correlation with the target variable. The higher the correlation, the more important the feature is to predict the price of a vehicle.

## **Model Selection**
Six different models were evaluated to determine which model would be the best fit for the data. The outcome resulted in XGBoost being the best model for predicting the price of a vehicle.

## **Conclusion**
In conclusion, we can see that:

* The XGBoost model was able to predict the price of a vehicle with an accuracy of 96%.
* Many features were found to be important in predicting the price of a vehicle.
* The model can be used by dealerships and consumers to help them understand the pricing of a vehicle.

The next steps for this project would be to deploy this model in a web application to be used by dealers or the buyers. To scale this project, I would need to collect more data and include outside factors such as the economy, the weather, and the time of year. This would help the model be more accurate in predicting the price of a vehicle. This was a fun project to work on and I learned a lot about the data science process. I hope you enjoyed this presentation and I look forward to hearing your feedback!




