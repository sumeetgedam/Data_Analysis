# Data_Analysis

Data Analysis on some famous datasets available online.

## Content :clipboard:

1. [Kaggle](#kaggle)
    - [Time Series Basics](#time-series-basics)
    - [Diamond Prices Data Analysis](#diamond-prices-data-anaysis)
    - [Premier League Data Analysis](#premier-league-data-analysis)
    - [Titanic Survival Data Analysis](#titanic-data-anaysis)
    

## Kaggle

### Time Series Basics

- Dataset
   - [Air Passengers](https://www.kaggle.com/datasets/rakannimer/air-passengers/data)
   - [Shampoo Sales Dataset](https://www.kaggle.com/datasets/redwankarimsony/shampoo-saled-dataset)
   - [Time Series Data](https://www.kaggle.com/datasets/saurav9786/time-series-data)

- Notebook
   - [Time Series Basics](https://www.kaggle.com/code/sumeetgedam/time-series-basics)

- Implementation Points
    - Explored Univariate and multivariate timeSeries
    - Visualized datasets to understand the Components of TimeSeries
      - Trend
        - Deterministic Trends
        - Stochastic Trends
      - Seasonality
      - Cyclic Patterns
      - Noise
    - Models for Decomposition of TimeSeries
      - Additive Model
        - Additive Decomposition
      - Multiplicative Model
        - Multiplicative Decomposition
    - Visualized the Seasonality in datasets
    - TimeSeries Forecasting Techniques
      - Moving Average
        - Centred Moving Average
        - Trailing Moving Average
    - Handling Missing Values
    - Forcasting Requirements
      - Outliers
      - Resampling
      - Up-sampling
      - Down-sampling
    - Measuring Accuracy
      - Mean Absolute Error
      - Mean Absolute Percentage Error
      - Mean Squared Error
      - Root Mean Square Error
    - ETS ( Error , Trend, Seasonality ) Models
      - SES
        - Simple smoothing with additive errors
      - Holt
        - Holt's linear method with additive errors
          - Double Exponential Smoothing
      - Holt-Winters
        - Holt Winter's linear method with additive errors
          - Multi-step forecast
    - Auto Regressive Models
      - Auto-Correlation function ( ACF ), Partial Auto-Correlation function ( PACF )
      - Stationarity check using Dickey Fuller Test
      - ARIMA Model ( AutoRegressive Integrated Moving Average )
      - Auto ARIMA
        - using AIC ( Akaike Information Criterion ) and BIC (Bayesian Information Criterion ) for model selection

      




###  Premier League Data Analysis

- Dataset
   - [Premier League Player Statistics](https://www.kaggle.com/datasets/rishikeshkanabar/premier-league-player-statistics-updated-daily/data)

- Notebook
   - [Premier League Data Analysis](https://www.kaggle.com/code/sumeetgedam/premier-league-player-s-analysis)

- Implementation Points
    - Explored the dataset and visualized missing values
    - Used plotly.express to visualize : 
      - Countried most represented
      - Players appearance
      - Player's age
    - Used ***plotly.subplots*** to visualize Players Stats by playing position
    - Used ***plotly.graph_objects*** to plot graphs for the way goal was made and the mistakes by players

### Diamond Prices Data Anaysis

- Dataset
   - [Diamonds](https://www.kaggle.com/datasets/shivam2503/diamonds)

- Notebook
   - [Diamond Prices Data Anaysis](https://www.kaggle.com/code/sumeetgedam/data-analysis-on-daimond-prices)

- Implementation Points
   - We started with exploring the dataset which gave us an idea about the attributes present in it.
   - We later made some changes and visualized the following:
     - Carat
     - Cut
     - Color
     - Clarity
     - Depth
     - Dimensions 
     - along with their comparision with Price.
   - Introduced a new feature Volume to see the relationship between volume of diamond and price.
   - Divided the dataset into test and train to use them for evaluating with different Algorithms including :
     - Linear Regression
     - Lasso Regression
     - AdaBoost Regression
     - Ridge Regression
     - GradientBoosting Regression
     - RandomForest Regerssion
     - KNeighours Regression
   - which gave us the ***r2 values*** ( Co-efficient of determination ) and visualized the same which showed us RandomForest Regressor giving the highest r2 value.


### Titanic Data Anaysis

- Dataset
   - [Titanic](https://www.kaggle.com/competitions/titanic)

- Notebook
   - [Titanic Data Anaysis](https://www.kaggle.com/code/sumeetgedam/smg-titanic)

- Implementation Points
   - Reviwed the train and test data provided
   - Calculated the survival rate of men and women
   - Predicted suvival rate using ***RandomForestClassifier***