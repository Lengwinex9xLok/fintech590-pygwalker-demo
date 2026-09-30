# AI Use Note

For BTC/ETH sectionI used Claude (Anthropic) to troubleshoot technical issues, understand PyGWalker, and improve the structure of my analysis. Claude also pointed out that my fixed volatility threshold favored ETH, which prompted me to use a relative threshold. I implemented and checked the BTC/ETH analysis with pandas, verified the reported values against the raw DataFrame, and checked flagged events against contemporary news sources.  
- Zhuoxi Li

For the NVDA section, I collected the NVDA quote snapshots and order-book updates through a data pipeline I maintain, using market data accessed via my broker. Chose the analysis and demo sequence. ChatGPT/Codex helped with Python troubleshooting, demo browsering and slide designing. I checked the quote counts, spread distribution, snapshot intervals, and order-book filtering with pandas.
- Ziye (Loki) Luo
