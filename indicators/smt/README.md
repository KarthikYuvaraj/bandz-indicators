# Bandz SMT

Bandz Multi-Timeframe SMT + Timecycle Scanner scans several timeframes for non-confirmation between the chart instrument and up to two related comparison instruments. Its purpose is to show where correlated markets disagree around prior highs or lows while controlling duplicate lower-timeframe drawings.

HOW IT WORKS

The scanner can process weekly, daily, four-hour, one-hour, 30-minute, 15-minute, five-minute, and one-minute structures. A slot is evaluated only when its timeframe is equal to or higher than the chart timeframe.

For bearish SMT, the engine evaluates a valid prior high and checks whether the chart market and enabled comparison markets disagree about taking that high. Bullish SMT applies the inverse test to a prior low. Users can trigger on either enabled comparison or require all enabled comparisons to diverge. An optional rule requires price to close back inside the reference.

Each timeframe has its own lookback and retention controls. Developing SMTs are updated or removed when they stop qualifying. Closed events may persist, and broken events can be removed automatically.

The engine processes higher timeframes before lower ones. “Highest TF Wins” mode suppresses weak or duplicate lower-timeframe events while retaining a lower-timeframe child only when it satisfies the selected recency and extremity rules. Additional caps limit fast-timeframe clutter and stored drawings.

For continuous futures comparisons, selectable back-adjustment handling helps keep the chart and comparison data aligned. Labels identify the timeframe and the comparison market responsible for the divergence.

HOW TO USE IT

Choose markets with a defensible relationship and keep their sessions and contract settings consistent. Begin with “Highest TF Wins” and the default clutter controls. Treat a developing higher-timeframe SMT as provisional until its candle closes; use optional close-back confirmation if a stricter display is preferred.

DESIGN VALUE

SMT divergence is an established concept. This implementation’s value is its high-to-low multi-timeframe processing, two-comparison trigger modes, futures-data normalization, live invalidation, hierarchical duplicate suppression, fractal child filtering, and per-timeframe retention controls. The components work together to prioritize the strongest higher-timeframe disagreement and reduce redundant lower-timeframe drawings.

LIMITATIONS

Correlation can change, and divergence does not guarantee reversal or continuation. Live events can appear, move, or disappear before their timeframe closes. Different sessions, symbols, contract rolls, or back-adjustment modes can materially change comparisons. Invalid comparison data prevents reliable evaluation. This is a contextual reference tool, not a signal or guarantee.
