# Awesome-Foreign-Exchange-Risk-Management

# Top Foreign Exchange (FX) Risk Management Platforms

A curated list of leading platforms for FX risk management, currency hedging automation, exposure management, multi-currency payments, treasury FX modules, and related cross-border solutions for corporates and financial institutions.  
**Primary focus: open-source software.**

Commercial / hosted platforms are listed separately for completeness. Open-source alternatives and community tools are emphasized throughout.

---

## SaaS / Hosted Platforms

| Platform | Description | Key Focus |
|----------|-------------|-----------|
| **[Kantox](https://www.kantox.com/)** | Leading FX risk management and currency management automation platform. End-to-end workflow covering exposure collection, automated hedging (including layered and micro-hedging), pricing, execution, reporting, and hedge accounting. | Automated FX risk reduction & hedging workflows |
| **[MillTech FX](https://www.milltechfx.com/)** | FX and payments technology focused on transparent pricing, multi-currency accounts, and risk management tools for corporates and institutions. | Transparent FX & multi-currency solutions |
| **[Corpay Cross-Border](https://www.corpay.com/)** | Cross-border payments and FX solutions including multi-currency accounts, local payment rails, currency management, and risk tools for global businesses. | Cross-border payments + FX risk |
| **[GTreasury FX](https://www.gtreasury.com/)** | Treasury management system (TMS) with strong FX modules for exposure management, hedging strategy, risk assessment, and integrated treasury operations. | TMS + FX risk & hedging |
| **[Kyriba FX](https://www.kyriba.com/)** | Cloud treasury and finance platform with advanced FX capabilities, analytics, risk management, and cash/FX visibility for global organizations. | Cloud TMS & FX analytics |
| **[360T](https://www.360t.com/)** | Multi-bank, multi-asset FX execution management system (EMS) tailored for corporates. Supports spot, forwards, swaps, NDFs, automated rule-based execution, and connectivity to TMS/ERP. | Corporate FX execution & EMS |
| **[Integral](https://www.integral.com/)** | Institutional FX technology for liquidity aggregation, pricing, execution, and workflow automation across FX, CFDs, and related asset classes. | Liquidity aggregation & FX trading tech |
| **[FX HedgePool](https://www.fxhedgepool.com/)** | Specialized FX hedging and risk management solutions focused on efficient hedge execution and portfolio-level currency risk control. | Dedicated FX hedging |
| **[StoneX Treasury](https://www.stonex.com/)** | Treasury and FX services from StoneX, providing execution, risk management, and liquidity access for corporate and institutional clients. | Institutional FX & treasury services |
| **[Convera](https://www.convera.com/)** (formerly Western Union Business Solutions) | Cross-border payments, multi-currency accounts, and FX risk management tools for businesses managing international cash flows. | Cross-border payments & FX |

---

## Open-Source Softwares

Fully featured, production-grade open-source FX risk management platforms (with automated hedging workflows, multi-bank connectivity, hedge accounting, and corporate-grade exposure management) are very limited. Useful open-source building blocks exist for pricing, risk analytics, hedging simulations, reconciliation, and capital-markets foundations.

### Core Frameworks & FX / Treasury Platforms

| Project | Description | License | Notes |
|---------|-------------|---------|-------|
| **[Eclipse Tradista](https://www.tradista.finance/)** | Open-source capital markets and treasury platform covering trade capture, market data, position & P&L, risk reporting, and operations. Modular design suitable for banks and treasuries; supports FX among other asset classes. | Apache 2.0 | Most complete open capital-markets / treasury foundation |
| **[rateslib](https://github.com/attack68/rateslib)** | Advanced Python fixed-income and derivatives library for pricing bonds, IRS, cross-currency swaps (XCS), FX swaps, curve construction, and risk sensitivities (delta, cross-gamma). | Source-available (non-commercial / commercial) | Strong quantitative FX & rates toolkit |
| **Dynamic FX Risk Management projects** | Community repositories demonstrating Bollinger Band volatility regimes, dynamic hedging simulations (forwards/options), and Sharpe-ratio comparisons of hedged vs unhedged portfolios. | Various (often MIT/Apache) | Educational / research hedging frameworks |
| **FX Exposure Reconciliation tools** | Python applications for multi-source trade reconciliation, break detection, mark-to-market exposure, margin alerts, and dashboard reporting. | Open source | Operations & risk-control focused |
| **SFRM (Spot and Futures Risk Management)** | Lightweight system for managing spot-futures hedging/arbitrage projects, P&L, hedge ratios, and risk exposure (primarily commodities but conceptually transferable). | Open source | Hedge project management example |
| **Risk toolkits for FX** | Interactive quant toolkits implementing delta/gamma exposure, VaR/CVaR, optimal hedge ratios, toxicity scoring, and related risk metrics in FX contexts. | Open source | Quantitative risk analytics |

### Specialized Libraries & Related Tools

| Project | Description | Focus Area |
|---------|-------------|---------|
| **QuantLib** | Comprehensive open-source quantitative finance library with FX, options, swaps, and risk engines. Widely used as a foundation for pricing and risk systems. | Pricing & risk engines |
| **FX rate & data libraries** | Open tools and APIs for historical/live FX rates (e.g., via public endpoints or self-hosted collectors) used in exposure calculations. | Market data |
| **Curve & swap pricing** | Libraries supporting multi-currency curve construction, cross-currency basis, and FX forward/swap valuation. | Valuation & curves |
| **Optimization & hedging solvers** | SciPy, CVXPY, or custom optimizers for minimum-variance hedge ratios and portfolio hedging strategies. | Hedge optimization |
| **Reconciliation & ops tools** | Open frameworks for trade matching, break management, and audit trails adaptable to FX operations. | Post-trade & ops |
| **Dashboarding** | Streamlit, Dash, or Grafana + time-series DBs for building internal FX exposure and P&L monitors. | Visualization & monitoring |

### Additional Notable Open-Source Tools

- **Market data pipelines** — Collectors and normalizers for FX spots, forwards, and volatility surfaces that feed risk engines.
- **Hedge accounting prototypes** — Research or simple implementations of cash-flow and fair-value hedge accounting logic (often incomplete relative to IFRS 9 / ASC 815 requirements).
- **Multi-currency cash management scripts** — Custom tools for netting, sweeping, and basic exposure aggregation.
- **Academic & research code** — University and quant-blog repositories exploring dynamic hedging, carry optimization, and regime-based FX risk models.
- **Integration layers** — Open API gateways and workflow tools to connect internal ERP/TMS data with pricing and execution services.

**Note:** Commercial FX risk platforms provide critical advantages in live multi-bank connectivity, automated rule-based hedging, regulatory-grade hedge accounting, real-time exposure aggregation across systems, and seamless payment/FX execution. Open-source solutions are strongest as quantitative libraries, reconciliation tools, and foundational capital-markets platforms (especially Eclipse Tradista) that organizations can extend. Building a full corporate FX risk system typically requires combining open components with commercial execution and data services.

---

## Quick Start Recommendations

| Goal | Recommended Starting Point |
|------|---------------------------|
| Open-source capital markets / treasury foundation | **Eclipse Tradista** |
| Quantitative FX & rates pricing / risk | **rateslib** or **QuantLib** |
| Hedging simulation & analytics | Community dynamic FX risk projects + optimization libraries |
| Trade reconciliation & exposure monitoring | FX exposure reconciliation tools |
| Fully automated corporate FX risk & hedging | **Kantox** |
| Cloud TMS with strong FX module | **Kyriba** or **GTreasury** |
| Corporate multi-bank FX execution | **360T** |
| Liquidity aggregation & institutional FX tech | **Integral** |
| Cross-border payments + FX | **Corpay Cross-Border** or **Convera** |
| Transparent FX & multi-currency accounts | **MillTech FX** |

---

## Contributing

Contributions, corrections, and new open-source projects are welcome.  
Please open an issue or pull request.

---

**Last updated:** August 2026  
Emphasizing open-source tools while documenting the major commercial platforms for context. Fully featured open-source FX risk management platforms with automated hedging and multi-bank connectivity remain scarce; the strongest options are capital-markets foundations (Eclipse Tradista), quantitative libraries (rateslib, QuantLib), and specialized risk/reconciliation tools that can form the core of a custom solution.
