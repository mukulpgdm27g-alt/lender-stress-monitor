# Lender Stress Monitor

FRA Group Project 2: credit-risk performance of **ICICI Bank** (large private bank) and **L&T Finance** (NBFC) against peer sets, FY16 to FY26, and how their share prices reacted to systematic and idiosyncratic risk.

**Live dashboard:** https://YOUR-USERNAME.github.io/YOUR-REPO/

## Files
- `index.html`: the whole dashboard (data, charts and code in one file; no server or build step; works offline).
- `data/credit_figures_with_sources.csv`: credit figures with basis and source. Rows marked "Author estimate" are assumptions, not company-reported figures, and appear in italics in the dashboard.
- `.nojekyll`: tells GitHub Pages to serve the files as they are.

## Dashboard flow
1. The question: Scope and method, Overview, Concepts and calculators
2. The credit story: Asset quality, Peer scorecard
3. The market's reaction: Stress periods, Share prices, Systematic risk, Idiosyncratic risk, Overall impact, Risk and correlation
4. The answer: Key takeaways
5. Reference: Data and sources

## Method in brief
- Peers: Axis, HDFC, Kotak, IndusInd for ICICI Bank; Bajaj Finance, Cholamandalam, M&M Financial, Shriram Finance for L&T Finance.
- Measures: gross NPA / Stage 3, net NPA, PCR, slippages, write-offs, credit cost, plus derived measures (implied coverage, net stress build-up, share of peak NPA cleared).
- Price split: market-driven part = beta x benchmark return (Nifty Bank or Nifty 50); lender-specific part = the remainder.
- Data breaks (HDFC merger, Kotak basis change, older GAAP to Ind AS, Shriram merger) are tagged, marked on charts, and change-based measures restart at each break.
