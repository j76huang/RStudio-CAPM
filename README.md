# RStudio-CAPM
Exploring R with Capital Asset Pricing Model (CAPM)

The dataset that is used contains stock prices for Bloomberg's SPTX60 constituents from Jan 1, 1983 to May 30, 2014. 
The dataframe has 2 columns: Yt and Xt
where Yt is the return rate of stock i less risk free rate and Xt is the market return rate less risk free rate

File #1
- finds OLS using time series regression using 2 methods: matrices and lm() 
- finds ESS, TSS, RSS
- var-covar matrix (variance of B hat)
- tests for heteroskedasticity with White's test
- tests for validity of CAPM model with Jensen's alpha with t-test

File #2
- finds OLS using cross section regression 
- tests for heteroskedasticity using White's test
- tests for autocorrelation using Durbin-Watson's test
