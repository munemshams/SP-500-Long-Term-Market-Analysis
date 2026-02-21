# S&P 500 Long-Term Market Analysis (1927–2020)

This project analyzes nearly a century of S&P 500 index data (23,323 daily observations) from the years 1927 to 2020 using R Studio to evaluate long-term growth, return behavior, volatility patterns, seasonality effects, and major market shocks.

The analysis combines financial time-series techniques with statistical inference to understand how the U.S. market behaves over time.

The raw dataset has been hosted in Kaggle and the link is provided below:

https://www.kaggle.com/datasets/henryhan117/sp-500-historical-data


# Project Overview

Dataset Coverage: 1927 – 2020
Observations: 23,323 daily records
Variables: Open, High, Low, Close, Adjusted Close, Volume

# Key Analysis Components

- Data cleaning and time transformation

- Daily return calculation

- Volatility measurement

- Bootstrap confidence intervals (95%)

- Hypothesis testing (post-2008 crash returns)

- Decade-wise return & volatility comparison

- Weekday and monthly seasonality analysis

- Market crash visualization (1987 & 2008)

- Linear regression modeling of price trends

# Major Insights

- Mean daily return: ~0.03%

- Daily volatility (SD): ~1.2%

- Extreme returns: −20.5% to +16.6%

- 95% bootstrap CI confirms consistent long-term positive drift

- Mild Monday effect and September weakness observed

- Strong upward linear trend over nearly 100 years

- Bootstrapped hypothesis testing suggests post-2008 returns were slightly positive but not statistically different from zero at the 5% significance level.

# Libraries Used

-tidyverse

-readr

-infer

-broom
