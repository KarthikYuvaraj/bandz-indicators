# Bandz STDV-Flow

Bandz STDV Flow is a multi-timeframe liquidity and market-structure tool that requires a complete sequence before drawing a projection: an external liquidity sweep, CISD confirmation, and a break of the opposing swing.

HOW IT WORKS

The engine begins with completed higher-timeframe highs and lows. When price sweeps an unresolved reference using the selected wick or body-close rule, the script records the manipulation extreme without repeatedly restarting the setup timer if that extreme deepens.

It then evaluates completed confirmation-timeframe candles for a contiguous opposing delivery leg. That leg defines the CISD threshold. A setup advances only after price closes through the threshold in the expected direction and subsequently closes through the relevant opposing swing. This staged process separates the liquidity event, delivery shift, and structural confirmation.

After confirmation, the opposing swing and manipulation extreme become the two measured-range anchors. The indicator displays selected multiples of that anchored range, together with the confirmed CISD. “STDV” is the name used for this measured-range ladder; it is not statistical standard deviation, variance, volatility, or a probability calculation.

Fixed timeframe routing is used:

• 1–5 minute charts: 1H liquidity, 5m confirmation, 4H context
• Below 1H after the 5m group: 4H liquidity, 15m confirmation, Daily context
• 1H–3H charts: 4H liquidity, 1H confirmation, Daily context
• 4H–23H charts: Daily liquidity, 4H confirmation, Weekly context
• Daily and higher: Daily liquidity, Daily confirmation, Monthly context

Within each active context window, the script protects the lowest valid bullish CISD and highest valid bearish CISD. Additional structures are selected from bounded event data using recency and structural-strength criteria, which limits overlapping projection clutter.

Users can adjust setup sensitivity, visible range levels, CISD extension, forming-CISD visibility, colors, and line styles. Lifecycle controls determine whether an anchor breach or the final -4 objective is evaluated by wick or close. By default, the entire CISD, anchor, and projection structure is removed when its manipulation anchor is breached or the -4 objective is completed.

HOW TO USE IT

Allow the fixed preset to match the chart timeframe. Wait for confirmed CISD and opposing-swing structure before treating a projection set as active. Use the levels to organize scenarios and risk discussions; do not interpret them as statistical probabilities or guaranteed price targets.

DESIGN VALUE

Liquidity sweeps, CISD, swing breaks, and measured-range projections are established concepts. This implementation’s intended value is its ordered state machine, fixed multi-timeframe routing, frozen setup identity, competition-window selection, anchor lifecycle, and bounded relevance filtering. The components are sequenced so projections appear only after all structural stages are satisfied.

LIMITATIONS

Confirmation deliberately introduces delay. Forming CISD displays are provisional and can disappear. Historical and real-time multi-timeframe compression can differ around incomplete candles. Projection levels do not estimate probability, expected return, or statistical volatility, and no objective is guaranteed to be reached.
