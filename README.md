# time-series-portfolio

3. Consider three stocks (Google, AAL, and Tesla) with prices from 2018/1/1 to 2021/10/1. Let $S_t$ denote the stock price at day $t$. The log-return at day $t$ is 
$$r_t = \log\frac{S_t}{S_{t-1}}.$$
    1. Show the time series plots historical prices of these three stocks. 
    2. Show the time series plots of log-returns of these three stocks. 
    3. Use the whole periods to summarize their expected returns and risk. Draw these three points on the 2D-plane. 
    4. Report the portfolio weight of the global-minimum portfolio. 
4. Assume we have 100,000 USD. Follow 3 and perform a backtest: 
    1. Start with the first 60 days of return and calculate the portfolio weight of the global minimum portfolio. Report the portfolio weight and the number of shares to buy for each stock. 
    2. *A rolling-window backtest procedure* 
   [(Details)](https://docs.google.com/spreadsheets/d/1SEGhzMLycKQh425jmCKHCsiHKKfdKHXXMDCK0kjWinY/edit#gid=0): Hold a portfolio for the next 5 days. Roll the window to use the latest 60 dys of return and hold a portfolio for 5 days. Continue these steps till the end of the study period. Show the accumalative return of the global minium variance portfolio and compare it with the 1/3 portfolio. Hint: let $P_t$ denote the market value of the portfolio. The acccumulative return is calcuated as 
    $$accR_t = (\frac{P_t-P_0}{P_0})\times 100\%$$
   