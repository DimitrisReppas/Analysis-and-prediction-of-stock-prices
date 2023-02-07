
# Analysis and prediction of stock prices
This project was developed in cooperation with Katsogiannis Giorgos for the purposes of the Deep Neural Networks course in my postgraduate studies (MSc) in Data Science and Information Technologies (NKUA). 

The topic of this research project is centered around the domain of stock prices. In general, our
main focus relies on understanding the data and then making predictions. With this in mind, the first
part of the project contains the **analysis of the time series data**. In descriptive modelling or time
series analysis, a time series is modelled to determine its components in terms of seasonal patterns,
trends, relation to external factors, the correlation between features and other key characteristics of
each series. Having obtained an understanding of the data, the second part of this research is
dedicated to **stock prices predictions**. Specifically, we begin by tackling a **one-step price forecast**
problem, by applying classic machine learning methods as well as deep neural architectures . During
this regression problem, many experiments were conducted to find which set of features, that
represent the data, is the most suitable and of course, which model manages to better fit the series
after the fine tuning process. By finding which models generalize better to our data, we proceed to a
**60-day price forecast** as well. Moving on, we continue with the slightly different problem of the
**prediction of stock price movements**. In this case, the regression problem is converted into a
classification problem with two classes and the goal is to predict whether the price of a certain stock
will rise or fall. During this set of experiments, many different architectures were applied to find which
method generalizes better on this problem. 



## Dataset 

The dataset that was used to achieve the goals of this project was the [CAC40 Stocks Dataset](https://www.kaggle.com/datasets/bryanb/cac40-stocks-dataset).
CAC40 is a benchmark of the French stock market index.

## Models

We experiment using both neural models and classic machine learning algorithms as a baseline.
Namely, we use Linear Regression, XGBoost and Support Vector Machines (SVM) as our baselines
for the regression problem and Logistic Regression, Random Forests and SVM as our baselines for
the classification problem. We also use 5 different deep neural networks:
LSTM, GRU, Bidirectional LSTM (BiLSTM), Bidirectional GRU (BiGRU) and Linear

## Reproducibility of the project

The code of the project is distributed to three different Jupyter Notebooks. For ease of use, we have also provided Google Colab links for all Notebooks which automatically load the dataset. In order to run these files locally, the user must also download the [CAC40 Stocks Dataset](https://www.kaggle.com/datasets/bryanb/cac40-stocks-dataset) separately. 

## Analysis of the time series data

We provide a Jupyter Notebook containing all the code used
for data exploration and time series analysis:
 [Deep_Learning_Project_Data_Analysis.ipynb](https://colab.research.google.com/github/DimitrisReppas/Analysis-and-prediction-of-stock-prices/blob/main/Deep_Learning_Project_Data_Analysis.ipynb)


## Predictions on Stock Price Time Series

Having completed the time series analysis process, the next step of our project is to make
predictions on our data. As we’ve already mentioned, this section contains two major experiments: the
stock price forecast and the prediction of stock price movements.
The Jupyter Notebook containing the code used for
the regression and classification experiments is the following: [Deep_Learning_Project_Predictions.ipynb](https://colab.research.google.com/github/DimitrisReppas/Analysis-and-prediction-of-stock-prices/blob/main/Deep_Learning_Project_Predictions.ipynb)

## Long-term price forecast

[Deep_Learning_Project_Long_term_Predictions.ipynb](https://colab.research.google.com/github/DimitrisReppas/Analysis-and-prediction-of-stock-prices/blob/main/Deep_Learning_Project_Long_term_Predictions.ipynb) is a Jupyter Notebook containing the code for the multiple day prediction experiment.

## Results

A short presentation with the results of this project can be found [here](https://docs.google.com/presentation/d/1SbOTc_H7ndlsw38mbj5BmuISYe9ccTp0IRh96cSQm6Q/edit#slide=id.gf4f9ddc3bf_0_142)
