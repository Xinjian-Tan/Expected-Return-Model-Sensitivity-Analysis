# Expected-Return-Model-Sensitivity-Analysis

## Research Question

How sensitive are portfolio allocation decisions
to the choice of expected return estimation method?

## Research Motivation

Expected returns are a fundamental input in portfolio optimization, but they are inherently difficult to estimate.
CAPM provides a theoretically grounded framework for estimating expected returns based on systematic risk and the market risk premium. However, its empirical implementation relies on parameters estimated from historical market data, while future asset returns may differ substantially from historical patterns.
This raises an important practical question: if expected returns are estimated using different methodologies, how sensitive are the resulting portfolio allocations to the choice of estimation method?
To investigate this question, this project compares three expected return estimation approaches — Historical Mean, CAPM, and a Shrinkage approach combining the two — and examines how they affect portfolio construction within a fixed universe of large-cap U.S. technology stocks.

## Methodology

### Expected Return Models
- Historical Mean
- CAPM
- Shrinkage

### Portfolio Optimization
- Equal Weight
- Minimum Variance
- Maximum Sharpe Ratio

## Result
The results of the study show that the portfolio allocation results are indeed significantly affected by the choice of expected return estimation method. We found that, within the given sample period, the expected return for NVIDIA obtained using the Historical Mean method is significantly higher than that obtained using CAPM. The difference for Google is also very large. The reason is actually quite obvious. The 2021–2025 sample period included a series of relatively unique developments in the technology industry, especially the rapid development of generative AI, which created a very special growth environment for companies such as NVIDIA. Therefore, under different historical environments, the choice of different return estimation methods may be important, and this may have a significant impact on our portfolio.


## Limitations

This study only examines a selected group of U.S. technology companies, and the findings may not be representative of stocks in other industries.
For industries with more mature and stable business models, the three expected return estimation methods may produce relatively similar estimates and therefore lead to less significant differences in portfolio allocation.

This study is intended for academic and research purposes only and does not constitute investment advice.
