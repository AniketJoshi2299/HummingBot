# Advanced Market Making Strategy

This strategy enhances traditional market making by dynamically adjusting buy and sell quotes based on market volatility, price trends, and portfolio inventory levels. It widens spreads during high volatility, skews prices against market trends for mean reversion, and manages inventory to maintain balanced exposure. Designed for crypto markets, it combines liquidity provision with risk management and automated profit-taking.

## Detailed Description

This is an advanced Pure Market Making (PMM) strategy tailored for crypto markets. It continuously places buy and sell limit orders while adapting to changing market conditions through three key mechanisms:

### 1. Volatility Awareness
The strategy measures market volatility using technical indicators and adjusts spreads accordingly. High volatility leads to wider spreads to minimize risk, while low volatility results in tighter spreads for higher fill rates.

### 2. Trend Biasing
Momentum and moving average signals are used to detect trends. When the market shows strong upward or downward momentum, the bot skews quotes slightly against the trend to capture potential mean-reversion opportunities.

### 3. Inventory Management
To maintain portfolio balance, the bot monitors holdings and adjusts pricing to favor rebalancing. Overexposure to the base asset results in more aggressive sell pricing, while underexposure favors buys.

## Features

- Dynamic spread adjustment based on market volatility
- Trend-aware quoting for mean-reversion opportunities
- Inventory-based price skewing for balanced exposure
- Frequent order refresh for real-time market alignment
- Auto profit realization to lock in gains
- Tracks both realized and unrealized PnL

## Why Use This Strategy

This approach delivers adaptive quoting, automated rebalancing, and disciplined risk management, making it effective in volatile trading environments where traditional market making may fall short.
