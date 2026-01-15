<div align="center">

# Research Log: Dmytro S.

> *"Alpha is not found in the noise, but in the residuals."*

**Role:** Quantitative Strategist & ML Researcher
**Focus:** Stochastic Calculus, Market Microstructure, DeFi Liquidity
**Status:** Modeling Volatility Surface 📉

</div>

---

### 📐 Methodology & Stack

My research pipeline involves heavy statistical modeling and low-latency execution simulation.

| Domain | Toolchain |
| :--- | :--- |
| **Modeling** | $\int_{0}^{t} \sigma_s dW_s$ (Stochastic Volatility), Ornstein-Uhlenbeck |
| **ML / AI** | **PyTorch** (LSTM, Transformer), **JAX** (Auto-diff), Scikit-learn |
| **Data** | **Pandas** (Time-series), NumPy, KDB+/Q (Tick history) |
| **System** | **Rust** (Engine), **Python** (Research), LaTeX (Docs) |

---

### 🔬 Active Research (Open Source)

* **[`spreadlab-cointegration`]([https://github.com/Dmytrostrateg/spreadlab-cointegration](https://github.com/Dmytrostrateg/spreadlab-cointegration))**
    * *Cointegration pairs trading using Engle-Granger & Kalman Filters.*
* **[`avellaneda-stoikov-mm`]([https://github.com/Dmytrostrateg/avellaneda-stoikov-mm](https://github.com/Dmytrostrateg/avellaneda-stoikov-mm))**
    * *Inventory-based market making model simulation & calibration.*
* **[`noarb-vol-surface`]([https://github.com/Dmytrostrateg/noarb-vol-surface](https://github.com/Dmytrostrateg/noarb-vol-surface))**
    * *Implied volatility surface construction with no-arbitrage constraints.*
* **[`graph-arb-engine`]([https://github.com/Dmytrostrateg/graph-arb-engine](https://github.com/Dmytrostrateg/graph-arb-engine))**
    * *Bellman-Ford algorithm application for multi-hop FX arbitrage.*

---

### 📡 System Telemetry

```yaml
user@quant-lab:~$ ./show-stats.sh

[User]      Dmytrostrateg
[Rank]      Top 10% (Quant/HFT)
[Commits]   1,204 (Year to Date)
[Stack]     Rust (40%), Python (35%), C++ (25%)
[Uptime]    99.99%

> Running backtest simulation... [================>...] 85%
> Optimizing execution latency... DONE (42ns)
```

> *"In the short run, the market is a voting machine but in the long run, it is a weighing machine."*
