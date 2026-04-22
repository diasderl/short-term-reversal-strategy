# Short-Term Reversal Strategy

## Overview
This project implements a short-term reversal trading strategy designed to exploit temporary mispricing in equity markets.

## Strategy
- Long-short portfolio
- Long past losers, short past winners
- Monthly rebalancing
- Equal-weighted positions

## Enhancements
- Volatility scaling to improve risk-adjusted returns
- Regime filter to reduce exposure during unfavorable market conditions

## Results
- Volatility scaling provided the best performance
- Regime filtering reduced risk but lowered returns
- Combined strategy improved stability but did not outperform volatility scaling

## Files
- notebooks/: Python implementation
- slides/: Presentation slides
- results/: Graphs and outputs

## Conclusion
The strategy shows strong performance, but real-world implementation would require careful consideration of transaction costs and market impact.
