# Excel Project Portfolio for Data Analysis and Mathematical Model Implementation

Welcome to this portfolio dedicated to advanced Excel usage for data analysis, mathematical model implementation, and statistical testing. Excel is a preferred tool for data exploration and model development due to its user-friendly interface, flexibility, and power. It provides an intuitive visual approach to understanding and interpreting complex data.

In this directory, you will find a selection of Excel files I have used to explore various topics. Each file represents a distinct project and includes a range of data analysis techniques, model implementations, and statistical tests.

These files showcase my ability to use Excel to analyze data, derive insights, and test hypotheses. They also demonstrate my understanding of complex mathematical and statistical concepts and how I apply these concepts to extract knowledge from real-world data.

Each Excel file is carefully organized and annotated to facilitate understanding. However, the true treasure lies in Excel's ability to offer intuitive and interactive visualization, enabling a better understanding of the relationships between different variables and the underlying logic of the models.

These projects will show you how Excel can be used to solve data analysis problems in various contexts. They also illustrate how Excel skills can be applied to understand, explain, and solve complex real-world problems.

Feel free to explore these files, use them as inspiration for your own projects, or even modify them to meet your specific needs. Happy exploration!


## Breusch-Godfrey Autocorrelation Test - Excel File

The first file in this portfolio is an Excel tool for conducting the Breusch-Godfrey autocorrelation test. This test is used in econometrics to detect the presence of autocorrelation (or serial correlation) in the residuals of a regression model.

Autocorrelation is a characteristic of data in which the errors or residuals of a regression model are correlated with each other. If the residuals are autocorrelated, it means that the error for a given observation depends on the errors of previous observations. This can be problematic as it violates the classical assumption that regression errors are independent of each other.

The Breusch-Godfrey test is particularly useful as it can be applied in the context of regression models where errors are assumed to be autocorrelated up to a certain order. This Excel file allows you to input your own data and run the test to determine whether your residuals are autocorrelated or not.

This tool is an excellent example of how Excel can be used to conduct advanced statistical tests and provide important insights into the quality of your regression model. It provides a clear demonstration of Excel's ability to handle complex statistical issues while offering a user-friendly and intuitive interface.


## Durbin-Watson Autocorrelation Test - Excel File

The second file in this portfolio implements the Durbin-Watson autocorrelation test using Excel. Similar to the Breusch-Godfrey test, the Durbin-Watson test is also used to detect the presence of autocorrelation in the residuals of a regression model.

The Durbin-Watson test is specifically used to identify the presence of first-order autocorrelation, which means that the residuals from one period to another are correlated. The value of the Durbin-Watson test typically ranges from 0 to 4, where a value of 2 indicates no autocorrelation, a value below 2 indicates positive autocorrelation, and a value above 2 indicates negative autocorrelation.

In this Excel file, you can enter your own data and run the Durbin-Watson test. The results provide a quick and intuitive way to check for autocorrelation in your regression models, which can help improve the accuracy and reliability of your forecasts.

Once again, this file showcases the power of Excel in performing sophisticated statistical analyses while providing a user-friendly and visually intuitive interface.



## Engle-Granger Cointegration in the Context of Algorithmic Trading - Excel File

The third file in this portfolio is an implementation of Engle-Granger cointegration in the context of algorithmic trading, using Excel. Cointegration is a powerful statistical technique used in pairs trading to determine the degree of statistical relationship between two or more time series.

Pairs trading strategy is a popular algorithmic trading strategy that involves trading two highly correlated securities. When the correlation between the two securities breaks down, meaning one goes up while the other goes down, a trade is placed in the hope that the correlation will be reestablished in the future.

The Engle-Granger cointegration test is used to determine if two time series are cointegrated, meaning they share a long-term equilibrium relationship even if they may deviate from each other in the short term. If two series are cointegrated, it means there is a certain linear combination of these series that is stationary.

In this Excel file, you can enter your own data on the time series and run the Engle-Granger cointegration test. While this file is not designed to build a complete trading algorithm, it helps you understand how these strategies work in practice and how cointegration can be used to develop pairs trading strategies.


## ARCH Heteroscedasticity Test - Excel File

The fourth file in this portfolio contains an implementation of the ARCH (Autoregressive Conditional Heteroskedasticity) heteroscedasticity test using Excel. This test is commonly used in quantitative finance to identify whether a time series has a variance that changes over time, a phenomenon known as conditional heteroscedasticity.

Heteroscedasticity refers to a situation where the variance of the errors or residuals in a statistical or regression model is not constant. It is a violation of the classical assumption of homoscedasticity, which states that the variance of the errors is constant over time. Heteroscedasticity can lead to inefficient estimates of regression coefficients and biased standard errors, resulting in incorrect inferences.

The ARCH test is particularly useful for modeling financial time series, where conditional heteroscedasticity is often present. This is due to the frequent changes in volatility observed in financial markets.

In this Excel file, you can enter your own time series data and run the ARCH test to determine whether your series has a variance that changes over time.


## Estimating the Hurst Exponent through R/S Analysis - Excel File

The fifth file in this portfolio is dedicated to estimating the Hurst exponent using R/S analysis, implemented using Excel. The Hurst exponent, named after British hydrologist Harold Edwin Hurst, is a statistical indicator used to characterize the long-term persistence or memory of a time series.

R/S analysis, or "Range over Standard Deviation," is a method for estimating the Hurst exponent. It is based on calculating the ratio between the cumulative fluctuation range of a time series and its standard deviation.

The Hurst exponent helps determine whether a time series is anti-persistent, random (or white noise), or persistent. This information is crucial in many fields, including finance for modeling the stock market, hydrology for estimating river flows, or telecommunications for analyzing internet traffic.

In this Excel file, you can input your own time series data and apply R/S analysis to estimate the Hurst exponent. This implementation provides a concrete opportunity to understand and apply this important statistical technique in a user-friendly interface. It once again demonstrates the flexibility and power of Excel for performing complex data analyses.


## Jarque-Bera Test - Excel File

The sixth file in this portfolio is an implementation of the Jarque-Bera test using Excel. The Jarque-Bera test is a statistical test that assesses whether a data series follows a normal distribution. It is based on the measures of skewness and kurtosis of a distribution, also known as the third and fourth moments.

The Jarque-Bera test is widely used in finance, economics, and other fields where the normal distribution is often assumed. It is useful for evaluating whether data follows a normal distribution or if it exhibits significant skewness and non-negligible kurtosis.

In this Excel file, you can input your own data and run the Jarque-Bera test to assess whether your data follows a normal distribution. The test results will indicate whether you can assume that your data is normally distributed or if it deviates significantly from this assumption.


## Using the Omega Ratio to Optimize Portfolio Performance - Excel File

The seventh file in this portfolio is dedicated to using the Omega ratio to optimize portfolio performance, using Excel's Solver. The Omega ratio is a widely used performance measure in finance to assess the risk-adjusted return of a portfolio.

The goal of portfolio optimization is to find the optimal combination of assets that maximizes returns while minimizing risk. The Omega ratio is a metric that takes into account both the expected return and the risk, focusing on the distribution of returns below a certain minimum acceptable return threshold.

In this Excel file, you can enter the historical returns of available assets and specify a minimum acceptable return threshold. Excel's Solver is then used to find the optimal allocation of assets in the portfolio that maximizes the Omega ratio.

Using Solver in Excel automates the optimization process and quickly finds the asset allocation that offers the best trade-off between return and risk.

This Excel file is an excellent demonstration of using advanced Excel features, including Solver, to solve portfolio optimization problems. It allows you to explore different asset allocations and gain a clear perspective on how the Omega ratio can be used to make informed investment decisions.


## Using Sortino, Calmar, and Sterling Ratios to Optimize Portfolio Performance - Excel File

The eighth file in this portfolio focuses on using Sortino, Calmar, and Sterling ratios to optimize portfolio performance, still using Excel Solver. These ratios are commonly used measures in finance to evaluate the risk-adjusted performance of a portfolio.

1. The Sortino ratio is a performance measure that focuses on returns below the average portfolio return. It measures the risk-adjusted excess return by considering only the volatility of negative returns.

2. The Calmar ratio is used to assess the risk-adjusted return of a portfolio, emphasizing the ratio between the total return and the maximum drawdown (the maximum decline of the portfolio from its peak level).

3. The Sterling ratio is a performance measure that takes into account the risk-adjusted return of a portfolio, focusing on the ratio between the total return and the return volatility adjusted by drawdown.

In this Excel file, you can enter the historical returns of the portfolio assets and specify a minimum target return or a maximum acceptable drawdown level. Excel Solver is then used to find the optimal asset allocation that maximizes the Sortino, Calmar, or Sterling ratio, based on your specific goals.

The use of Excel Solver automates the portfolio optimization process based on these different performance ratios.

This Excel file is an additional example of the advanced use of Excel features, particularly Solver, to solve portfolio optimization problems. It allows you to explore different asset allocations and gain a deep understanding of how specific performance ratios can be used to make informed investment decisions.

## Using the Starr Ratio to Optimize Portfolio Performance - Excel File

The ninth file in this portfolio focuses on using the Starr ratio to optimize portfolio performance using Excel's Solver. The Starr ratio is a performance measure developed by Kenneth Starr that seeks to evaluate risk-adjusted performance by considering both the returns and maximum drawdowns of a portfolio.

The Starr ratio is similar to the Sharpe ratio, but it distinguishes itself by using a maximum acceptable loss threshold instead of the traditionally used risk-free rate in the Sharpe ratio. It places more emphasis on capital protection by considering the maximum losses incurred by the portfolio.

In this Excel file, you can enter the historical returns of the portfolio assets and specify a maximum acceptable loss threshold. Excel's Solver is then used to find the optimal allocation of assets in the portfolio that maximizes the Starr ratio while respecting the specified maximum loss threshold.

Using Excel's Solver facilitates portfolio optimization based on the Starr ratio and helps determine the asset combination that offers the best trade-off between return and capital protection.


## Implementation of the TGARCH Model with Different Residual Distribution Assumptions - Excel File

The latest file in this portfolio is dedicated to the implementation of a TGARCH (Threshold Generalized Autoregressive Conditional Heteroscedasticity) model with different assumptions about the distribution of residuals, using Excel. The TGARCH model is used in financial econometrics to model the conditional volatility of financial returns.

The TGARCH model is an extension of the GARCH model that takes into account asymmetric effects in volatility. It allows for modeling different volatility regimes based on past returns levels. The TGARCH model is often used to capture volatility clustering phenomena and market shocks.

In this Excel file, you can enter your own financial return data and specify different assumptions about the distribution of residuals, such as the normal distribution, Laplace distribution, or generalized normal distribution. The TGARCH model is then fitted using the maximum likelihood method to estimate the optimal coefficients of the model.

The use of Excel for implementing the TGARCH model allows for visualizing the results and understanding the different assumptions about the distribution of residuals. You can compare the model's performance with different distributions and evaluate the relevance of each assumption.

This Excel file is an advanced demonstration of using Excel for estimating complex financial models and optimizing coefficients through maximum likelihood. It enables you to explore different assumptions about the distribution of residuals and enhance your understanding of modeling conditional volatility in financial returns.
