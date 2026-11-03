# Energy Desk Challenge

A browser trading game built for FMKT 256. You start with $100,000, are assigned one of nine S&P 500 energy stocks at random (XOM, CVX, COP, EOG, DVN, SLB, HAL, VLO, PSX), and trade the stock and its options one month at a time over five years of real prices. You are scored on Sharpe ratio, maximum drawdown and IRR against buy-and-hold.

**Play:** open the GitHub Pages link for this repository. No login or install needed.

- Prices: month-end closes adjusted for dividends and splits, January 2021 onward, stored in the `prices` JSON block in `index.html` and refreshed monthly.
- Options: priced with Black-Scholes on trailing 12-month realized volatility, with a bid/ask spread and commission.
- Import: players can add or extend any ticker by pasting a CSV of prices.

Everything runs in the browser in a single file, `index.html`.
