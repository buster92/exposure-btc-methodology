# FAQ

## What is Exposure BTC?

Exposure BTC is a quantitative Bitcoin exposure framework focused on regime detection, drawdown control, and risk-aware market participation.

It evaluates whether Bitcoin market conditions are structurally favorable or increasingly fragile — and adjusts exposure accordingly.

It is not a price prediction system. It is not a trading bot.

---

## Is this a price prediction model?

No. The framework does not predict where price is going.

It evaluates whether the current environment supports disciplined participation. Those are different problems.

---

## How does it outperform buy-and-hold in absolute return if it reduces exposure during downturns?

This is the right question to ask.

The answer is mechanical: Bitcoin buy-and-hold suffered a −76.6% drawdown in 2022. Recovering from that trough required the entire subsequent bull market — and passive holders still finished at only 1.30x their starting value by April 2026.

Exposure BTC avoided most of that drawdown. That preserved compounding capital at a significantly higher base. When favorable conditions returned, it was participating from a level that buy-and-hold hadn't recovered to yet.

That compounding gap is the structural advantage of drawdown control. It does not require being right about every move.

---

## Why does the backtest start in March 2021?

The backtest period — March 2021 through April 2026 — was not selected to flatter the framework. It was selected because it includes both extended favorable conditions and one of the most severe Bitcoin drawdowns on record (the 2022 bear market, −76.6% peak to trough).

Any exposure management framework that looks good through a period containing that drawdown is passing a genuine stress test, not a convenient one.

---

## Why not just use a simple moving average crossover or similar rule?

Single indicators often fail to capture the full context of market behavior. A moving average crossover can signal an exit after most of the damage is already done, and can generate excessive false positives during choppy but ultimately healthy markets.

Exposure BTC evaluates multiple dimensions of market behavior simultaneously. The regime classification is built on whether conditions are consistent and stable across several observed factors — not whether a single line has crossed another.

---

## What is a regime, and why does it matter?

A regime is a characterization of the underlying market environment — not just the price direction, but the quality and consistency of behavior behind the price.

Markets can move upward while becoming structurally less stable. Most investors only observe the price and remain fully exposed. The regime framework tries to assess whether that price movement is occurring in a healthy, supportive environment or a fragile one.

---

## Does this repository contain the full model?

No. The public repository explains the conceptual framework, validation philosophy, and public performance framing.

The internal implementation — including signal construction, weighting, thresholds, and decision logic — remains private.

---

## Is this financial advice?

No. Exposure BTC is a quantitative decision-support framework. Nothing in this repository or the associated product constitutes financial advice. Always do your own research and consult a qualified professional before making investment decisions.

---

## How is the performance measured?

Performance is measured as cumulative return normalized to 1.0 at the start of the period, compared against a passive Bitcoin buy-and-hold baseline with identical starting capital.

Maximum drawdown is measured as the largest peak-to-trough decline during the full backtest period.

See [`metrics.md`](metrics.md) for full framing.

---

## Where can I access the active framework?

Active signals and full framework access: **[exposurebtc.com](https://exposurebtc.com)**
