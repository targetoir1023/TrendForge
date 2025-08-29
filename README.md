This project is an integrated trading framework built in Pine Script v5, designed to bring together three high-probability components into a single decision engine: EMA alignment, engulfing confirmations, and market structure (BOS/MSS).

The core idea is to filter trades using higher–lower timeframe EMA confluence, validate entries with engulfing candle patterns, and only allow signals that occur within a confirmed shift in market structure. By combining these, the system avoids noise and focuses on structured trend-based opportunities.

Key Highlights:

Multi-Timeframe EMA Alignment → Uses 1H vs 4H EMA200 (configurable), with the option to run real-time higher timeframe updates (fast but repainting) or confirmed closed-bar updates (safe, no repaint).

Market Structure Detection → Automatically tracks swing highs/lows and detects Break of Structure (BOS) and Market Structure Shift (MSS), providing context for continuation or reversal setups.

Engulfing Confirmation → Filters trades with bullish/bearish engulfing patterns, increasing probability of strong momentum follow-through.

Signal Limiting → Restricts to a maximum of three signals per EMA cross cycle, avoiding overtrading during consolidation.

Risk Management Integration → Auto-plots entry, stop loss, and take profit levels with either fixed percentage or reward:risk ratio.

Visual Clarity → Plots both EMAs, swing points, entry markers, TP/SL projection lines, and dynamically updates signals in real time.

In short, this project is not just another EMA crossover or candlestick pattern tool—it’s a structured market model that blends multi-timeframe trend bias, structural validation, and precise entry filters, making it suitable for swing trading and intraday strategies.
