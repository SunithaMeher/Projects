# Introduction
• Economic growth signifies a rise in the production of goods and services when compared between different periods of time.<br/>

• Without a defined economic framework, accountability and responsibility in production become unclear, leading to uncalculated   allocation of resources.<br/>
 
• This project primarily focuses on predicting a country’s economic condition by considering factors such as investments and capital stocks deployed by both governmental and private entities.

# Dataset
• This Project's dataset is acquired from IMF(international Monetary Fund<br/>

• Furthermore, this dataset comprises of 14 features intended for predicting a country's classification into a low, emerging, or advanced economy category based on various statistical indicators.<br/>

• Project evaluates classifier models for accurate economic predictions, aiming to identify the model with the highest accuracy and integrate into the final prediction system.

• Includes data on public/private investments, GDP, and capital stock, highlighting Quality Infrastructure across countries in the Fund's membership.

# Project Process
EDA:Exploratory Data Analysis (EDA) is an approach to analyse the data using visual techniques
Data Collection
Data Cleaning
Data Preparation 
One-hot-encoding: One Hot Encoding is used to convert numerical categorical variables into binary vectors.
Build Predictive Model
# Selection of algorithms
Validating the algorithm
# Deployment
After validating model with the best accuracy score amongst the ML models, we deploy the model using a python library called pickle.
The pickle module is something which  transforms a complex object into a byte stream and it can transform the byte stream into an object with the same internal structure.
The loaded model from pickle is then integrated with the front-end of the website to turn it into a working model
For the front-end , another useful module of python called streamlit  was utilised-which helps us create web apps for data science and machine learning in a short time and compatible with other modules too.




