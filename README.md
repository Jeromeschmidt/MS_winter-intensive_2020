# Basis Portfolio Selection and Analysis

## Introduction
### Inspiration
I was first inspired to begin this project when I first heard about the compant Titanvest(YC S18). The premise of their initial product was to analyze the 13F reports hedge funds managing over $100,000,000 in capital must report that contain their holdings. By doing this, they can in theory create a portfolio of high performing stocks with a minimal amount of research. Not needing to do as much research allows them to have less staff and therefore charge less overall. Typically hedge funds have charged a 2% management fee along with a 20% performance fee and Titanvest is able to charge only a 1% performance fee. Since first launching, they have consistantly out performed the S&P 500 by a significant amount. *separate paragraph*

Since Titanvest only chooses the top 20 stocks they believe to be high-performing so I planned to do the same. After selecting those, I would backtest that collection of stocks,equally weighting them just as Titanvest does, and compare that to the portfolio that they have constructed to see if they would achieve similar results. After that, I would try alternative methods of weighted different equities in the portfolio to see if better results could be easily achieved. Using strategies like 2-3 moving averages, I backtested these as well to see ifbetter results were reasonably more achievable


## Things to Know
* [Alpha](https://www.investopedia.com/terms/a/alpha.asp): Metric used to measure investing success. Typically uses S&P 500 to compare results.
* [Beta](https://www.investopedia.com/terms/b/beta.asp): Shows how a specific stock to portfolio of stock corrolates with market trends.
* [Sharpe Ratio](https://www.investopedia.com/terms/s/sharperatio.asp): Used to compare investments return to its risk. Higher that better.
  * greater than 1 is considered good
  * greater than 2 is considered great
  * greater than 3 is considered excellent
  * less than 1 is considered sub-optimal
* [Leverage](https://www.investopedia.com/terms/l/leverage.asp): Money borrowed on top of capital from bank or brokerage.
* [Turnover](https://www.investopedia.com/terms/t/turnoverratio.asp): Describes how long a firm has a particular investment before it is sold
* [S&P 500](https://www.investopedia.com/terms/s/sp500.asp): Market-capitalization-weighted index of the 500 largest U.S. publicly traded companies.
* [Volatility](https://www.investopedia.com/terms/v/volatility.asp): How much a stocks value changes in a short period of time. Higher volatility oftens means riskier investment
* [Stock Universe](https://www.investopedia.com/terms/u/universeofsecurities.asp): Collection of equities being traded

## Tools/Resources used
* 13F Reports from [WhaleWisdom](https://whalewisdom.com/)
* Developed backtesting strategy on [Quantopian](https://www.quantopian.com/home)
* Backtests written in python 3.5
* Zipline API used in Quantopian backtest

## Selecting Stock Universe

## Equally Weighted Portfolio

## Portfolio with changing weights

## Conclusion

## References
