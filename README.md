# Bandz Indicators

The seven Bandz indicators are free and open source. This repository preserves their complete Pine Script v6 source independently of TradingView.

## Indicators

| Indicator | Source |
| --- | --- |
| HTF | [Bandz-HTF.pine](indicators/htf/Bandz-HTF.pine) |
| All-in-One | [Bandz-All-in-One.pine](indicators/all-in-one/Bandz-All-in-One.pine) |
| STDV Flow | [Bandz-STDV-Flow.pine](indicators/stdv-flow/Bandz-STDV-Flow.pine) |
| Reference Levels + Gaps + ADR | [Bandz-Levels.pine](indicators/levels/Bandz-Levels.pine) |
| Session Ranges + ORG | [Bandz-Sessions.pine](indicators/sessions/Bandz-Sessions.pine) |
| Multi-Timeframe SMT + Timecycle Scanner | [Bandz-SMT.pine](indicators/smt/Bandz-SMT.pine) |
| Intraday Timing + FVG | [Bandz-Intraday.pine](indicators/intraday/Bandz-Intraday.pine) |

## Individual public repositories

Each indicator also has its own public repository with complete Pine source, a license, and installation instructions:

- [HTF](https://github.com/samuelharting/bandz-htf)
- [All-in-One](https://github.com/samuelharting/bandz-all-in-one)
- [STDV Flow](https://github.com/samuelharting/bandz-stdv-flow)
- [Levels](https://github.com/samuelharting/bandz-levels)
- [Sessions](https://github.com/samuelharting/bandz-sessions)
- [SMT](https://github.com/samuelharting/bandz-smt)
- [Intraday](https://github.com/samuelharting/bandz-intraday)

[Discord-ready link list](DISCORD-LINKS.txt)

## Use in TradingView

1. Open a source file above, select **Raw**, and copy the complete code.
2. Open TradingView's Pine Editor and create a new indicator.
3. Replace the starter code, save, and select **Add to chart**.
4. Configure the indicator inputs for your symbol and timeframe.

No Whop subscription or invite-only approval is required when you use this source. Downloading or cloning this repository gives you a local backup. Pine Script requires TradingView to execute; a GitHub backup preserves the code but does not bypass TradingView platform rules or limits.

## Source and releases

Initial source snapshot: October 6, 2026, taken from the latest seven current Bandz publications. Trading logic was preserved; non-breaking whitespace introduced by TradingView's source display was normalized to ordinary spaces. See each indicator folder for its description and `catalog.json` for publication links. Legacy invite-only links remain in the catalog for provenance and require their existing permissions; open-source publication links are added as they are released.

## License

Mozilla Public License 2.0, matching TradingView's default license for open-source scripts. See [LICENSE](LICENSE). Existing author notices are preserved.

## Limitations

These are discretionary chart tools, not automated trading systems. Developing candles and multi-timeframe inputs can change before closing; comparison markets can have different sessions. Signals and projected levels do not guarantee outcomes. There is no promise of future maintenance or compatibility. Trading involves risk.
