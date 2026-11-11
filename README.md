# [ad] Naked POC D/W/M

Pine Script v6 indicator for TradingView. Draws untouched ("naked") Point of Control levels from completed daily, weekly and monthly volume profiles and fades them out after price touches them.

## Install

1. Open the Pine Editor in TradingView.
2. Paste `naked-poc-dwm.pine`, click **Save**, then **Add to chart**.

Or add it from TradingView: [Naked Point of Control (Daily, Weekly, Monthly)](https://www.tradingview.com/script/h6cMBSds-Naked-Point-of-Control-Daily-Weekly-Monthly/).

## Notes

- Profiles are built from 1H OHLCV samples (changeable in the settings), so POC prices can differ slightly from TradingView's built-in volume profile.
- Each level starts on the last candle of its day, week or month that touched the level, on every chart timeframe.
- Use standard candles.
- Optional alerts: enable the alert router in the settings, then create one alert with **Any alert() function call**.

Not financial advice.

## License

Mozilla Public License 2.0. See `LICENSE`.
