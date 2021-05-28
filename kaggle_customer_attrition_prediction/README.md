# Customer Attrition Prediction

[Competition Link](https://www.kaggle.com/c/customerattritionprediction)

## Problem Overview

The training dataset contains 6338 samples and the testset contains 705 samples. Each sample contains 15 features and 1 prediction variable **CustomerAttrition** which indicates the class of the sample. There are 15 input features and 1 prediction variable

## Features

**ID**, string, the Customer ID allocated to each customer,<br>
**sex**, string, the gender of the person,<br>
**Aged**, Boolean, the gender of the person,<br>
**Married**, Boolean, The marrital status of the person<br>
**TotalDependents**, Boolean, Tells whether the person is dependent or independent.<br>
**ServiceSpan**, numerical, gives the timespan of the service taken by the person.<br>
**4GService**,string, the intenet service taken by the person,<br>
**CyberProtection**, Boolean, tells if cyber protection plan of company is taken by the person or not<br>
**HardwareSupport**, Boolean, tells if hardware support plan of company is taken by the person or not,<br>
**TechnicalAssistance**, Boolean, tells if technical assistance of company is taken by the person or not,<br>
**FilmSubscription**, Boolean, tells whether the person has subscribed for films,<br>
**SettlementProcess**, string, The payment process chosen by the person,<br>
**QuarterlyPayment**, numerical, The quaterly payment made by the person,<br>
**GrandPayment**, numerical, The cummalative payment made by the person,<br>
**CustomerAttrition**, Boolean, The choice of continuation of services taken by the customer,<br>

## Objective

Your task is to predict the customer Attrition for each customer in the given dataset using data science models.