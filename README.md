# Real_Estate_Price_Prediction_Project
## Introduction

Designing an advanced Machine Learning system for forecasting residential property prices in Bangalore, India is our primary objective. Leveraging the dataset accessible on Kaggle.com, we aim to harness the power of data-driven insights to enhance the accuracy of our predictions.

Below data science concepts are used in this project
* Data loading and cleaning
* Feature engineering
* Outlier detection and removal
* Dimensionality reduction
* K fold cross validation
* Gridsearchcv for hyperparameter tunning


Technology and tools used in this project
* Python
* Numpy and Pandas for data cleaning
* Google Colaboratory Notebook
* Matplotlib for data visualization
* Python flask for http server
* Sklearn for model building
* HTML/CSS/Javascript for UI

## Steps
1. we'll construct a predictive model utilizing the Scikit-Learn library, employing Linear Regression techniques. This model will be trained on the extensive Bangalore home prices dataset obtained from Kaggle.com.
2. Second step would be developing a Python Flask server that will leverage the trained model to respond to incoming HTTP requests.
3. Third component is the website built in html, css and javascript that allows user to enter home square ft area, bedrooms etc and it will call python flask server to retrieve the predicted price. 

  ```
  Step#1: Import the required libraries
  Step#2: Load the data
  Step#3: Understand the data
          -drop unnecessary columns
  Step#4: Data Cleaning
          - Check for na values
          - Verify unique values of each column
          - Make sure values are correct (eg. 23 BHK home with 2000 Sqrft size is worng)
          - Feature Engineering
          - Dimesionality Reduction
          - Outlier removal using domain knowledge (2bhk price < 3bhk price, size per bhk >= 300 sqft)
          - Outlier removal using standard eviation and mean
          - One Hot encoding
  Step#5: Build Machine Learning Model
  Step#6: Testing The model
  Step#7: Export the model
  Step#8: Export any other important info
  ```

## Dataset Reference
* [Bengaluru House price data](https://www.kaggle.com/amitabhajoy/bengaluru-house-price-data)
* I have also uploaed the csv file in this repository [Bengaluru_House_Data.csv](Bengaluru_House_Data.csv)

Reference
[codebasics](https://youtu.be/rdfbcdP75KI)
