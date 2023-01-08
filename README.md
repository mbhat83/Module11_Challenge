## Module 11 Challenge: Forecasting Net Prophet

### Background

As a growth analyst at [MercadoLibre](http://investor.mercadolibre.com/investor-relations). With over 200 million users, MercadoLibre is the most popular e-commerce site in Latin America. Analyst has  been tasked with analyzing the company's financial and user data in clever ways to make the company grow. So, you want to find out if the ability to predict search traffic can translate into the ability to successfully trade the stock.
 
### Instructions & Technology used

First, configure a Google Colab workspace as follows:

* Open [Google Colab](https://colab.research.google.com/) and upload your starter notebook.

* Run the provided code in the _Install and import the required libraries and dependencies_ section.
    * The first cell will install the necessary libraries into the Google Colab runtime.
    * The second cell will import the dependencies for use in the notebook.
- !pip install prophet
- !pip install hvplot
- !pip install holoviews
  
* Import libraries
- import pandas as pd
- import holoviews as hv
- from prophet import Prophet
- import hvplot.pandas
- import numpy as np
- import datetime as dt
- %matplotlib inline

### Usage

Use the Resources folder files to upload the data complete the tasks outlined in the Instructions
  
    The instructions are divided into five steps, as follows:

* Step 1: Find unusual patterns in hourly Google search traffic

* Step 2: Mine the search traffic data for seasonality

* Step 3: Relate the search traffic to stock price patterns

* Step 4: Create a time series model with Prophet

* Step 5 (optional): Forecast revenue by using time series models


### Contributor 
Madhuri