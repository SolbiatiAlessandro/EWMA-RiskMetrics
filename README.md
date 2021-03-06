# EWMA_RiskMetrics()

An implementation on R of the EWMA filter for volatility by RiskMetrics™ (JPMorgan &amp; Reuters 1996)
This software use RiskMetrics™ volatility model to compute the risk associated with and asset's return.

Website of the project https://solbiatialessandro.github.io

***

## Current State of the Project:


### Implemented in 'R-code' folder the core functions for the EWMA filter:

- calculate the EWMA volatility with RiskMetrics formulas
- compute the Value at Risk with three diffrent methods: non parametric, returns distributed as a normal, returns distributed as a student's t
- binomial backtest of the Value at Risk correctness

### Implemented in 'Utility' folder the functions to use the filter and evaluate risk

- getPrice() to get an asset's price from yahoo.finance
- study() to compute the Value at Risk, Expected Shortfall and associated p-value of the time series
- display_study() to study different assets at the same time




***



##Reference for the project

The project has been developed based on the Techincal Document by JPMorgan and Reuters (specifically on chapter 5 https://www.msci.com/documents/10199/5915b101-4206-4ba0-aee2-3449d5c7e95a)

***

##Case studies

##Italian bank associated risk

The software has analysed the major banks in the FTSE.MIB and these are the Value at Risk obtained

![alt tag](https://cloud.githubusercontent.com/assets/20618047/17279595/5733f586-5778-11e6-9712-03b5f50d60b0.jpeg)









