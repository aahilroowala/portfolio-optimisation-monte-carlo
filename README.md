 Portfolio Optimisation – Monte-Carlo Simulation

10,000 random portfolios simulated across 6 assets (Cisco, NVIDIA, Rolls-Royce, Lloyds Banking Group, BP, Procter & Gamble) to visualise the approximate Efficient Frontier.

## Files
- **Portfolio-Optimizer-2026.xlsx** – full spreadsheet with historical prices, returns, covariance matrix and simulation output
- **Code.gs** – Google Apps Script that generates random weights, calculates risk/return/Sharpe, and stores everything

## How to use
1. Open the spreadsheet
2. Go to Extensions → Apps Script
3. Paste the content of Code.gs into the editor
4. Save & run `generateRandomPortfolios()`
5. Results appear in columns Q–Z (sorted by Sharpe)

Built as a self-learning project to understand real quant workflows.


