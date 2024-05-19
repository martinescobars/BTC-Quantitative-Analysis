# BTC-Quantitative-Analysis

### Martin Escobar

<span style="font-size:0.25em;">*__The information presented reflects the views and assumptions of The Author(s) at the time of publication. Please note that this research may not be updated and The Author(s)' current views may materially differ from those presented without notice. The results will not be updated as The Author(s)' internal models change, or any information upon which the models relies upon changes.__*</span>

V1 published 5/19/2024.

This repository enables technical quantitative analysis and risk-return profiling for Bitcoin. Additionally, it helps identify the pros and cons of including Bitcoin in a total portfolio allocation strategy. For the dataset, we'll be using the end of day prices from Yahoo Finance through yfinance package.


## Project Description

The authors used quantitative analysis methods to examine the risk and return properties of Bitcoin.

Description of each section in the script:

- **Helping Functions**: Contains utility functions.
- **Project Functions**: Contains functions for quantitative analysis and plotting outputs.
- **Data Fetching**: Allows users to fetch closing prices for a given financial asset from Yahoo Finance using the yfinance package.
- **Quantitative Analysis**: Enables users to implement the project functions.
- **Asset Analysis Within a Total Portfolio**: Helps users identify the pros and cons of including Bitcoin in a total portfolio allocation strategy.
- **Key Findings**: Summarizes the major findings from the analysis observations. 


## Usage

```python
# what is the 3-year rolling sharpe ratio of Bitcoin?

asset = 'btc_usd'
df = data[['date', asset]]
rolling_period = 3
observed_periods = 6

plot_rolling_annualized_sharpe(df, rolling_period, observed_periods)

```


## The Author(s)
Martin Escobar

LinkedIn: [mescobars](https://www.linkedin.com/in/mescobars/)

Twitter: [@m_escobars](https://twitter.com/m_escobars)


## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss your proposed changes.


## Disclosure

You may not use the material for commercial purposes without first obtaining written permission.

2024, Martin Escobar. All content is original and has been researched and produced by The Author(s) unless otherwise stated herein. 

This material is for informational purposes only and does not constitute, either explicitly or implicitly, any provision of services or products by The Author(s). Nothing contained herein constitutes investment, legal, tax or other advice and is not to be relied on in making an investment or other decision. Investors should determine for themselves whether a particular service or product is suitable for their investment needs or should seek such professional advice for their particular situation.

This material is intended only to provide observations and views of The Author(s) at the time of writing, both of which are subject to change at any time without prior notice. Certain of the statements contained herein are statements of future expectations and other forward-looking statements that are based on The Author(s) current views and assumptions and involve known and unknown risks and uncertainties that could cause actual results, performance or events to differ materially from those expressed or implied in such statements. Past performance is no guarantee of future results. Financial Assets may decline in value due to both real and perceived general market, economic, and industry conditions. 

The Author(s) statements are not an endorsement of any company or a recommendation to buy,sell, or hold any security. Additionally, The Author(s) do not have investment banking, consulting, or any type of fee-paying relationship with the issuer's subject security.
