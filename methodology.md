# Methodology

## 1. Objective

Exposure BTC is built to improve exposure decisions in Bitcoin by evaluating whether current conditions are **structurally favorable** or **increasingly fragile**.

The objective is not to call exact tops or bottoms.

The objective is to reduce time spent in poor exposure conditions, especially when:
- price still looks strong
- sentiment is optimistic
- underlying risk is already rising

## 2. Conceptual framework

The model treats market conditions as a **regime problem**, not just a direction problem.

A rising market can still become lower quality if:
- volatility starts expanding
- trend strength weakens
- drawdown pressure rises
- price becomes increasingly disconnected from healthy structure

That distinction matters because many bad entries happen after price has already advanced.

## 3. Core components

### A. Trend structure

Trend is assessed through structural variables rather than headlines.

Examples of the type of information considered:
- short-term and long-term moving-average relationship
- slope persistence
- price location relative to long-term structure
- spread behavior between trend measures

The point is not "price is up" but whether the uptrend remains orderly and supported.

### B. Volatility regime

Volatility is treated as a major truth signal.

Broad interpretation:
- **Compression** can indicate orderly structure
- **Expansion** can indicate instability, transition, or elevated downside risk

This matters because a market can continue rising while volatility behavior becomes less healthy underneath.

### C. Risk / drawdown pressure

The framework attempts to identify when upside becomes lower quality.

Examples of the type of risk evidence considered:
- drawdown behavior under comparable conditions
- structural deterioration before full trend failure
- mismatch between visible price strength and hidden fragility

This is one of the central ideas behind Exposure BTC:
a market can appear strong to the eye while becoming weaker in exposure quality.

## 4. Regime classification

Publicly, the methodology can be summarized into three broad states:

### Favorable
Conditions are aligned enough that exposure quality is relatively strong.

Typical traits:
- supportive trend structure
- controlled volatility
- limited visible structural stress

### Neutral
Signals are mixed.

Typical traits:
- trend not fully broken, but no longer clean
- volatility not catastrophic, but not confirming either
- risk begins to rise without a complete breakdown

### High risk
Conditions suggest poor exposure quality.

Typical traits:
- volatility expansion
- weakening structure
- greater risk that recent price action is misleading rather than supportive

## 5. What the model is not

Exposure BTC is not:
- a hype-driven price prediction engine
- a promise of perfect top/bottom timing
- a system that claims certainty

It is a discipline framework for **exposure management under uncertainty**.

## 6. Practical philosophy

The methodology is built around a simple belief:

> Avoiding bad exposure periods can matter as much as capturing good ones.

That is why drawdown control, regime detection, and structural caution are central to the product.

## 7. Public vs private layer

This repository intentionally describes the conceptual layer only.

The full internal system includes proprietary implementation details, thresholds, weighting, and decision logic that are not public.
