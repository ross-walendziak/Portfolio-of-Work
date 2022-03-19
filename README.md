# Portfolio-of-Work
Econometrics Portfolio

# [Project 1: Passenger Volume Forecast for Logan Airport:](https://github.com/ross-walendziak/Passenger-Forecast)
* Created a tool that scapes PDF documents from Massport for monthly passenger volumes at Boston Logan Airport using the pdftools package in r for the Jan 1999 to Oct 2021 period.
* Raw data is cleaned and assembed into a time series tsibble object using the various tidyverse packages.
* Exploratory data analysis is preformed to reveal insights on long term passenger terms, monthly seasonality patterns and the relationship between lags (autocorrelations) of successive passenger volume observations.
* Mean, naive, seasonal naive, linear trend, decomposition, harmonic, exponential smoothing, ARIMA, and a piecewise linear model with ARIMA errors are fit to the historial data.
* Best model selection is completed using a testing set and cross validation approach, as assessed by RMSE.
* A final 2-year passenger volume forecast is offered for the Nov 2021 through Oct 2023 period using all available data on the best model selection.

# [Project 2: Donation Estimator:](https://github.com/ross-walendziak/Clarity-in-Charity)
* Created various classification and regression models for a theoretical charity to optimize profits from a direct marketing campaign.
* Each individual mailing to a potential donor costs the charity $2.
* On average, without application of any predicitive models, the response rate for the mailing campaign is 10% and each mailing sent to a potential donor is expected       to cost the charity $0.55. Thus, sending mailings out to donors using a simple random sample approach is a negative net present value proposition for the charity.
* Our best classification model is the boost model and the best regression model is the random forest model.  
  * Expected profit outcomes change from -$0.55 per mailing without use of the models to +$0.09 per mailing with use of the models. The charity can become self-               sustaining.

# [Project 3: Liquor-Sales-Data-Visualization:](https://github.com/ross-walendziak/Liquor-Sales-Data-Visualization)
* Summarized a large liquor sales data from the state of Iowa to visually depict liquor sales from multiple angles.
* Specifically, GGPLOT2 was used to produce visualizations for:
    * A calander heatmap for sales data from the year 2015.
    * A box-and-whisker plot for the pricing of liquor categories.
    * Scatter plot of price vs volume across liquor categories.
    * Time series plot of monthly liquor sales by category.
    * Time series plot of weekly liquor sales by category.
    * Ranking of liquor categories by total sales dollars, total sales volume and number of by bottles sold
