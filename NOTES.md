# Notes on this fork

- Upstream: https://github.com/TauricResearch/TradingAgents
- Fork: https://github.com/bisource05/TradingAgents
- Source that led me here: https://x.com/carm1nee/article/2113257064352915664 ("The 10 Most Dangerous GitHub Repos in Trading", Carm1ne, Oct 22, 2026)
- Role in that stack: Investment committee

## What it is

A multi-agent framework that organises LLM agents the way a trading firm is organised: separate analysts for fundamentals, sentiment, news and technicals, a bull-versus-bear debate, a trader, a risk team and a portfolio manager who can approve or reject the idea.

## Caution

Grade it on a backtest grid over past dates before trusting any single call. The same ticker and date can give different answers on different runs, because the underlying models are not deterministic.

## Status

Forked Oct 27, 2026. Nothing here has been run, configured, or connected to any account, API key, or real money. Paper / dry-run first, and only after a walk-forward backtest with fees, a look-ahead check, and 30 days on paper.
