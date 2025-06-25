# Cross Asset Quant-Dashboard

## Objective

![Dashboard](https://github.com/user-attachments/assets/d1dcfb61-dbbd-479f-b1b8-97cb3c867b2f)

This dashboard is a real-time, multi-factor monitoring system built to track sector momentum, volatility, and volume-adjusted flows across major U.S. equity sectors, bond proxies, and macro assets.

## Core Components & Features
🔹 Volume Analytics
- VWAP Z-Scores and Volume % Change track how current flows compare to historic activity.
- Volume spikes aligned with price weakness can indicate distribution, while volume surges on strength suggest accumulation.

🔹 Momentum Signal Cluster
- MACD, EMA, CMF (Chaikin Money Flow) used to measure trend strength and liquidity.
- CMF 7d and 30d breakdowns visually show  is favouring the average buyer  in or out over time.

🔹 Return & Return Z-Score Analysis
- Tracks absolute and standardized returns over multiple horizons: 1d, 7d, 14d, and 30d.
- Z-scores contextualize whether current returns are stretched or mean-reverting relative to recent history.

🔹 Realized Volatility Panel
- Tracks RVOL (1m/6m) and their ratios, highlighting volatility compression or expansion phases.
- The 1m/6m RVOL Z-score flags assets with abnormal realized volatility gaps — critical for vol targeting or mean-reversion setups.

## How It’s Used

🔹 Tactical Trade Scanning
- Identify oversold/overbought conditions using return and volume Z-scores.
- Confirm trend strength with momentum overlays.

🔹 Sector Rotation & Risk Flow
- Compare how sectors are performing on a normalized basis, not just raw returns.
- Quickly detect where money is flowing in/out via volume anomalies and CMF divergence.

🔹 Volatility Regime Awareness
- A sharp jump in short-term realized volatility vs. long-term is often a precursor to trend inflection.
- Helps calibrate position sizing, especially in mean-reversion vs breakout environments.


## Project Archive 

**<a href="https://github.com/PatrickRych/Portfolio-Manager">Project Archive </a>**
****
