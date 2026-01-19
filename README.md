# TradingView Indicators Portfolio

A collection of TradingView Pine Script indicators focused on
market breadth, macro risk regimes, and systematic signal generation.

---

## 🌐 Macro Risk Regime Map

![Macro Regime](assets/SPX_regime_map_example.png)

**Purpose**
Classifies the market into Risk-On, Slowdown, and Risk-Off regimes
based on normalized growth impulses.

**Features**
- Background regime coloring
- Trend reset logic
- Regime-aware signal filtering

**Code**
👉 [View Pine Script](pine/macro_risk_regime_map.pine)

---
## 🌐 SKFI Buy Signal + Macro Risk Regime

![Macro Regime](assets/SPX_SKFI_buy_example.png)

**Purpose**
Generates regime-aware SKFI buy signals by adapting oversold thresholds
based on the current macro risk environment.

**Features**
-SKFI-based mean-reversion buy signals
-Macro Risk Regime classification (Risk-On / Slowdown / Risk-Off)
-Regime-dependent entry thresholds
-Background regime coloring
-On-chart buy signals (green up triangles)

**Code**
[View Pine Script](pine/SKFI_buy_signal_with_risk_regime.pine)

## 🧠 Design Philosophy

These indicators emphasize:
- Signal clarity over noise
- Regime-aware risk management
- Visual simplicity (shapes, not labels)

