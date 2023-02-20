<img src="https://camscanada.com/img/CarGurus.png" width=600>

# **Driving the Future of Vehicle Pricing: A Machine Learning Approach**

### **Introduction**

Welcome to my Vehicle Price Prediction Project! In this project, our goal is to build a model that can accurately predict the price of a vehicle based on various factors such as make, model, year, mileage, and condition. The automobile industry is one of the largest and most competitive industries in the world, with millions of vehicles being sold each year. The price of a vehicle can have a significant impact on a consumer's purchasing decision and it is important for both buyers and sellers to have an understanding of the market value of a vehicle. By using machine learning algorithms and data analysis, we aim to provide a reliable and robust model that can assist in determining the fair market value of a vehicle. Join us on this exciting journey as we delve into the world of vehicle price prediction.

### **Buisness Problem Statement**

The vehicle price prediction project aims to address a crucial business problem in the automotive industry: accurately determining the fair market value of a vehicle. The automobile market is highly competitive and the price of a vehicle is a key factor in a consumer's purchasing decision. For both buyers and sellers, having an accurate understanding of a vehicle's market value is essential in making informed decisions. However, determining the fair market value of a vehicle can be a complex and challenging task, as it depends on a variety of factors such as make, model, year, mileage, condition, and location. As a result, there is a growing need for a reliable and objective tool that can assist in determining the market value of a vehicle. The vehicle price prediction project aims to provide such a tool by utilizing advanced machine learning algorithms and data analysis techniques to accurately predict the price of a vehicle based on relevant factors. This will not only help consumers make more informed purchasing decisions but also provide valuable insights for dealers, manufacturers, and other stakeholders in the automotive industry.

## **The Data**
This data was obtained using web scraping techniques on [cargurus.com](https://www.cargurus.com/). This data is for academic, research and individual experimentation only and is not intended for commercial purposes. This dataset contains 3 million new and used vehicle listings in the United States. The data set can be downloaded on [Kaggle.com](https://www.kaggle.com/datasets/ananaymital/us-used-cars-dataset?select=used_cars_data.csv). The data dictionary can be downloaded/reviewed [here](https://drive.google.com/file/d/177p54r5GarfVBSzNn3jFTkHS1N-yXNwx/view?usp=share_link)

<img width="418" alt="image" src="https://user-images.githubusercontent.com/100140174/220082585-70a88e6a-b8c2-42f8-b618-a48222c01bcb.png">

## **Data Cleaning**
Data cleaning is an essential step in the vehicle price prediction project as it helps to prepare the data for analysis and modeling. What we have seen so far is how to handle missing values, duplicate values, outliers, categorical variables, feature scaling, and feature engineering. In the next notebook, we will be using the cleaned dataset to explore the data and pre-process the data for modeling. 

## **Exploratory Data Analysis**
The goal of EDA is to gain a deeper understanding of the data, identify any trends, patterns, outliers, and anomalies that may impact the accuracy of the predictions, and help to formulate hypotheses about the relationships between the variables. This information can then be used to refine the data cleaning steps and feature engineering, and to select the appropriate modeling techniques.

![image](https://user-images.githubusercontent.com/100140174/220082762-0c897806-e885-4b7b-a536-4708ddd97cb8.png)

## **Model Selection**
Modeling is the process of creating a mathematical representation of a system or phenomenon. In this project, we aim to build a predictive model for our target variable, based on the features we have collected in our dataset. The goal of the modeling process is to find the best fitting mathematical function that describes the relationship between the features and the target variable.

![image](https://user-images.githubusercontent.com/100140174/220081797-ad037e8f-c428-4f21-88ee-e43adead8c79.png)

## **Conclusion**
In conclusion, the goal of the vehicle price prediction project was to build a model that could accurately predict the price of a vehicle based on its attributes. Through the process of exploratory data analysis and feature engineering, we gained a deeper understanding of the relationships between various attributes and the target variable. The modeling process involved training and evaluating several machine learning algorithms, including linear regression, decision tree, and random forest.

After careful evaluation, the random forest model was selected as the best model for this project, with an R-squared value of 0.96 and a mean absolute error of 0.67. This model demonstrated a high level of accuracy and was able to capture complex relationships between the attributes and the target variable.

This project serves as a demonstration of the power of machine learning in predicting real-world problems, and the results can be used by car dealerships or consumers to make informed decisions about vehicle prices. However, it is important to keep in mind that the model is only as good as the data it was trained on and limitations may arise when applied to new, unseen data. Further work could be done to gather additional data and improve the model's robustness.

Overall, this project highlights the importance of data exploration, feature engineering, and model selection in building a successful machine learning model.
