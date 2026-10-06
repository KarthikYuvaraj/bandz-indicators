# Bandz Sessions

Bandz Session Ranges + ORG is an intraday market-context tool that combines configurable session liquidity ranges, an independent opening-range bracket, and an Opening RTH Gap (ORG) map.

HOW IT WORKS

Session Ranges
The indicator tracks the high and low formed inside enabled time windows such as Asia, London, pre-market, the New York opening range, lunch, and optional custom sessions. After a session ends, its high, low, midpoint, labels, and box can remain visible. Pivot extensions can stop when price mitigates the level or remain visible beyond mitigation, depending on the settings.

Opening Range
A separate bracket records the high and low formed during a selected minute-based window, which defaults to 9:30–10:00 New York time. Optional edge projections connect the completed range back to price. This module is intended for 1–5 minute charts.

Opening RTH Gap
ORG compares the current 9:30 New York open with the selected prior RTH close. Futures users can select the CME 16:14 close, while US-equity users can select the 15:59 close. The script obtains this information from exact one-minute data, displays the gap boundaries and internal levels, and distinguishes small and large gaps.

ORG extension levels use complete ORG-range increments projected above and below the gap. They are progressively revealed as price reaches the currently visible extension. “STDV” in this module means a measured ORG-range extension; it is not a statistical standard-deviation calculation.

HOW TO USE IT

First select the correct time zone and prior-close source for the instrument. Use session highs, lows, and midpoints to identify where liquidity formed. Use the opening-range and ORG modules to evaluate how New York price action relates to the prior close and the initial cash-session range.

DESIGN VALUE

Sessions, opening ranges, gaps, and measured extensions are established concepts. This implementation’s value is the integration of exact one-minute ORG normalization, configurable session-pivot lifecycles, an independent opening-range bracket, progressive gap extensions, and drawing-retention controls in one intraday workflow. The components share time-zone and lifecycle controls so session liquidity, the cash opening range, and the prior-close gap can be reviewed together.

LIMITATIONS

ORG appears only on 1–3 minute charts, and the opening-range bracket appears on 1–5 minute charts. Results depend on the selected time zone, data feed, exchange session, and close source. Developing session levels can change until their window closes. The indicator provides reference levels, not trade entries, forecasts, or guaranteed objectives.
