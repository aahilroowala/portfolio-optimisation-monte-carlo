# portfolio-optimisation-monte-carlo
Monte-Carlo  portfolio simulation
Objective
I wanted to experience what real quantitative finance work feels like — analysing historical data, building risk-return models, 
running large-scale simulations, and interpreting the output the way analysts and portfolio managers do every day. This project was not part of any school assignment; 
I built it independently to bridge the gap between theory and actual desk-level thinking.
Approach
• Selected six liquid, diverse stocks/ETFs: Cisco Systems, NVIDIA, Rolls-Royce, Lloyds Banking Group, BP, Procter & Gamble.
• Pulled adjusted close prices using Excel’s built-in Stocks data type.
• Calculated daily returns → annualised mean returns and the 6×6 covariance matrix.
• Wrote a Google Apps Script (with AI assistance for structure and debugging) that generates 10,000 random valid portfolios (weights ≥ 0, sum = 1).
• For each portfolio computed expected return, annualised volatility, and Sharpe ratio (rf = 4%).
• Stored every weight set so the allocation behind each point is traceable.
Results
The 10,000 points form the classic “cloud” shape. The upper-left boundary (highlighted in red) approximates the Efficient Frontier — portfolios that no other combination beats in both return and risk.
The single highest-Sharpe portfolio from the run delivered:
• Expected annual return: 42.52 %
• Annual volatility: 1.67%
• Sharpe ratio: 23.04
Typical top portfolios overweighted high-conviction growth names (e.g. NVIDIA) while keeping meaningful exposure to defensive names (P&G, Lloyds) to dampen volatility.
Takeaways
• Even simple random sampling quickly reveals the power of diversification — the best outcomes almost never come from 100% in one name.
• Storing and inspecting weights makes the exercise far more insightful than just looking at a scatter plot.
• The workflow (data → covariance → simulation → visualisation → interpretation) mirrors steps used in real asset management and risk teams.
• Using AI to accelerate coding let me focus on the finance problem rather than syntax — a pattern I expect to see a lot in future quant / data roles.
This small project gave me a tangible sense of the analytical rhythm, data intensity, and decision-making.

