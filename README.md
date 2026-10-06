# Bandz Indicators

The seven Bandz indicators are free and open source. This repository preserves their complete Pine Script v6 source independently of TradingView.

## Indicators

| Indicator | Complete source | Public repository |
| --- | --- | --- |
| Bandz HTF Candles &#124; PSP & SMT | [Bandz-HTF.pine](indicators/htf/Bandz-HTF.pine) | [GitHub](https://github.com/samuelharting/bandz-htf-candles-psp-smt) |
| Bandz All-in-One &#124; ICT Trading Toolkit | [Bandz-All-in-One.pine](indicators/all-in-one/Bandz-All-in-One.pine) | [GitHub](https://github.com/samuelharting/bandz-ict-all-in-one) |
| Bandz PO3 &#124; STDV Projections & CISD | [Bandz-STDV-Flow.pine](indicators/stdv-flow/Bandz-STDV-Flow.pine) | [GitHub](https://github.com/samuelharting/bandz-po3-stdv-cisd) |
| Bandz Key Levels &#124; NWOG, NDOG & ADR | [Bandz-Levels.pine](indicators/levels/Bandz-Levels.pine) | [GitHub](https://github.com/samuelharting/bandz-key-levels-nwog-ndog-adr) |
| Bandz Sessions &#124; Killzones, Opening Range & ORG | [Bandz-Sessions.pine](indicators/sessions/Bandz-Sessions.pine) | [GitHub](https://github.com/samuelharting/bandz-sessions-killzones-org) |
| Bandz SMT / SSMT &#124; Multi-Timeframe Divergence | [Bandz-SMT.pine](indicators/smt/Bandz-SMT.pine) | [GitHub](https://github.com/samuelharting/bandz-smt-ssmt-divergence) |
| Bandz Intraday &#124; Macros, FVGs & Time Cycles | [Bandz-Intraday.pine](indicators/intraday/Bandz-Intraday.pine) | [GitHub](https://github.com/samuelharting/bandz-intraday-macros-fvg) |

## Individual public repositories

Each repository includes the complete Pine source, license, and installation instructions.

- [Bandz HTF Candles | PSP & SMT](https://github.com/samuelharting/bandz-htf-candles-psp-smt)
- [Bandz All-in-One | ICT Trading Toolkit](https://github.com/samuelharting/bandz-ict-all-in-one)
- [Bandz PO3 | STDV Projections & CISD](https://github.com/samuelharting/bandz-po3-stdv-cisd)
- [Bandz Key Levels | NWOG, NDOG & ADR](https://github.com/samuelharting/bandz-key-levels-nwog-ndog-adr)
- [Bandz Sessions | Killzones, Opening Range & ORG](https://github.com/samuelharting/bandz-sessions-killzones-org)
- [Bandz SMT / SSMT | Multi-Timeframe Divergence](https://github.com/samuelharting/bandz-smt-ssmt-divergence)
- [Bandz Intraday | Macros, FVGs & Time Cycles](https://github.com/samuelharting/bandz-intraday-macros-fvg)

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

