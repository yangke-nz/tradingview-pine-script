# TradingView Pine Script Indicators

This repository contains custom Pine Script™ indicators for use on TradingView. Each script is designed to enhance chart analysis for day trading and higher time frame strategies.

## Included Indicators

### 1. Day Trade — Bar Counter & EMAs
**File:** `indicatorDayTradeBarCountingAndEMAs.pine`

Displays a bar counter for each trading day and overlays multiple EMAs:
- Counts and labels bars for each new trading day.
- Shows every Nth bar (configurable).
- Plots:
	- EMA 20 (current timeframe)
	- EMA 20 (1H)
	- EMA 20 (Daily, with smooth intraday interpolation)

**Usage:**
1. Open the script in TradingView Pine Script editor.
2. Add to chart.
3. Adjust the `Display every N bars` input as needed.

### 2. High Time Frame EMAs
**File:** `IndicatorHighTimeFrameEMAs.pine`

Plots the 20-period EMA from multiple higher timeframes on your current chart:
- EMA 20 (current timeframe)
- EMA 20 (1H)
- EMA 20 (Daily)
- EMA 20 (Weekly)

**Usage:**
1. Open the script in TradingView Pine Script editor.
2. Add to chart.

---
All scripts are licensed under the Mozilla Public License 2.0.