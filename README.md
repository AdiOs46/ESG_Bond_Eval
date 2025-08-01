Initial To DO:

Step 1: Get List of Top 100 ESG Bond Issuers
  ✅ Use the Climate Bonds Certified Database to identify companies that issued certified ESG bonds.
  ✅ Filter and rank based on issuance amount or frequency to get top 100.

Step 2: Get Financial Identifiers
  ✅ Map those companies to their public tickers (for Yahoo Finance lookup).
  → Use manual mapping or tools like OpenFIGI, ISIN match, or cross-reference via company name.

Step 3: Pull Financial Data (via yfinance API or equivalent)
  ✅ Key metrics for each company:
  • Stock price (pre and post bond issuance)
  • Revenue, Net income
  • Total debt / equity
  • Market cap

Step 4: ESG Score / Ratings
  ✅ Use S&P ESG Risk Ratings or similar dataset to get ESG scores for each company.
  ✅ Cross-match by company name/ticker.

Step 5: Analyze Performance
  ✅ Compare pre- vs post-issuance performance:
  • Financial: Growth in revenue/profit/stock price.
  • ESG: Did scores improve over time?

Step 6: Visualization + Storytelling
  ✅ Cluster companies by sector or ESG score bracket.
  ✅ Scatterplots (ESG score vs financial return), time series (pre/post performance), correlation heatmaps.

