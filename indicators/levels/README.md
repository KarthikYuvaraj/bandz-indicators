# Bandz Levels

Bandz Reference Levels + Gaps + ADR organizes recurring price references into one configurable chart map. It combines new-week and new-day opening gaps, confirmed higher-timeframe levels, scheduled opening prices, period quadrants, and Average Daily Range markers.

HOW IT WORKS

NWOG and NDOG
At confirmed weekly and daily transitions, the indicator records the opening-gap boundaries and can display the 25%, 50%, and 75% positions inside qualifying gaps. Users can control how many gaps remain, which gaps extend, their labels, backgrounds, and line styles.

Higher-Timeframe References
The script displays selected daily, weekly, monthly, and yearly opens and confirmed prior-period highs and lows. Optional automatic levels mark the 25%, 50%, and 75% positions of completed weekly and monthly ranges, with an optional prior-day equilibrium level. Confirmed prior-period data is used so these references remain stable when changing chart timeframes.

Scheduled Opens
User-configurable prices can be captured at times such as midnight, 6:00, 8:30, 9:30, 10:00, 13:30, and 14:00 New York time. Each opening line has its own visibility range and lock time, allowing it to stop independently after the relevant session.

ADR
The indicator averages completed daily ranges over the selected lookback. From the current daily open, it marks one-third and full-range extensions above and below price. These are range-context markers, not probability bands.

Close labels can be combined when multiple references occupy nearly the same price area, reducing repeated text while preserving the underlying levels.

HOW TO USE IT

Select only the reference families relevant to the market and chart timeframe. Confirm the time zone and scheduled-open times. Use gap boundaries, prior-period extremes, range quadrants, timed opens, and ADR markers to judge price location and confluence rather than as automatic entries.

DESIGN VALUE

The underlying reference concepts are established. This implementation’s value is their consolidation into a stable multi-period map with independent timeframe gates, scheduled-line locks, selective gap extension, confirmed-period calculations, ADR context, and automatic label clustering. The components share consistent visibility and label controls so several recurring references remain readable in one workflow.

LIMITATIONS

Period boundaries and scheduled opens depend on the exchange feed, instrument session, and selected time zone. Continuous futures settings may change historical prices. ADR describes past average range and does not predict the current day’s final range. The script does not provide trading advice or guaranteed support, resistance, or targets.
