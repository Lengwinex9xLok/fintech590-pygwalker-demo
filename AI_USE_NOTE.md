# AI Use Note

For BTC/ETH section, I used Claude (Anthropic) as a supporting tool for debugging technical issues, understanding PyGWalker, and improving the structure of my analysis. It also helped identify a bias in my original fixed volatility threshold, which prompted me to adopt a relative threshold. I implemented and verified all analysis myself using pandas, checked reported values against the raw DataFrame, and independently confirmed flagged market events with contemporary news sources.
- Zhuoxi Li

For the NVDA section, I collected the NVDA quote snapshots and order-book updates through a data pipeline I maintain, using market data accessed via my broker. Chose the analysis and demo sequence. ChatGPT/Codex helped with Python troubleshooting, demo browsering and slide designing. I checked the quote counts, spread distribution, snapshot intervals, and order-book filtering with pandas.
- Ziye (Loki) Luo
