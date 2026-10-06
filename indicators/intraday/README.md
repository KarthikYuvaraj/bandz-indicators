# Bandz Intraday

Bandz Intraday Timing + FVG combines recurring intraday macro windows with automatically routed first-presented Fair Value Gaps, special New York AM/PM FVGs, calendar separators, and custom timestamps.

HOW IT WORKS

Macro Windows
On a one-minute chart, the script identifies enabled windows around the change of each hour, together with optional New York afternoon windows. Users can display these as brackets with labels and projections or recolor the candles that occur inside each active window.

Automatic First-Presented FVG
The indicator searches for the first qualifying bullish or bearish three-candle imbalance inside each mapped structural period. It automatically changes the calculation and divider timeframes according to the chart:

• 1–3 minute charts: one-minute FVGs with hourly dividers
• 5–15 minute charts: five-minute FVGs with four-hour dividers
• 30 minute–2 hour charts: 30-minute FVGs with daily dividers
• Higher intraday charts: four-hour FVGs with weekly dividers
• Daily and higher charts: daily FVGs with monthly dividers

Where adjacent real bodies do not overlap, the script applies its volume-imbalance boundary rule to refine the visible FVG edge. If the bodies materially overlap, the normal wick boundary remains. Minimum-size filters are independently configurable by calculation timeframe.

Session FVGs
On 1–5 minute charts, the script separately identifies the first qualifying FVG during the 9:31–11:00 AM and 1:31–4:00 PM New York windows. These zones can remain extended through the same week.

Calendar Tools
Optional daily, weekly, monthly, and yearly separators, weekday labels, and custom timestamp lines provide additional time-cycle structure.

HOW TO USE IT

Use a one-minute chart for macro windows. On other supported timeframes, allow the automatic mapping to select the structural FVG timeframe. Set the New York time zone and minimum-tick filters for the instrument, then use the first-presented zones as areas for further price-action evaluation.

DESIGN VALUE

Macro timing and FVGs are established concepts. This implementation’s value is its first-presented selection, automatic timeframe routing, body-based imbalance refinement, separate AM/PM detection, same-week zone management, and unified calendar context. The components work together by pairing time windows with a single prioritized imbalance from each structural period, reducing repeated zones while retaining session and calendar context.

LIMITATIONS

Macro visuals are one-minute features, and special AM/PM FVGs require 1–5 minute charts. A displayed imbalance is not guaranteed to hold or produce a reaction. Results depend on market data, session timing, chart timeframe, and minimum-tick settings. This is a reference tool, not a trade signal, forecast, or guarantee.
