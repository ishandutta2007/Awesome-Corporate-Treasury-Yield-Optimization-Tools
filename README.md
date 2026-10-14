# Awesome-Corporate-Treasury-Yield-Optimization-Tools

## Top Corporate Treasury Yield Optimization Tools Ecosystem



**Curated List of SaaS Products & Open-Source GitHub Projects**  

*Focused on Cash Positioning, Idle Balance Sweeping & Yield Automation*  

**Last updated: March 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** for **Corporate Treasury Yield Optimization**. These tools enable treasury teams to automatically transfer idle capital into optimal yield products—sweeping excess cash into money market funds, T-bills, or term deposits while maintaining liquidity and policy compliance.



**Examples** include Kyriba, GTreasury, TIS (Treasury Intelligence Solutions), Modern Treasury, Atlar, Agicap, Coupa Treasury, ION Treasury, FIS Quantum, and Hazeltree (the category leaders).



**Open-source emphasis**: This section is heavily expanded with every major active project for self-hosting, deterministic policy engines, and open yield automation—ideal for treasury engineers, finance teams, and developers seeking transparent, vendor-independent cash optimization.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [SaaS/Hosted Platforms](#saas-hosted-platforms)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms



- **[Kyriba](https://www.kyriba.com/)**

  Enterprise treasury management platform with **liquidity planning as a core strength**, SWIFT connectivity, and payment fraud detection . Uses AI for payment fraud detection, working capital optimization, bank reconciliation, receivables management, and anomaly detection . Mid-market deployments (10-50 entities) run **$75,000-$200,000/year** in subscription plus $50,000-$150,000 implementation . Enterprise rollouts across 20+ entities take 6-12 months .



- **[GTreasury](https://www.gtreasury.com/)**

  Treasury and risk platform with **driver-based long-range forecasting**, treasury accounting and GL posting, and controls reporting as core strengths . Often **10-15% cheaper** than Kyriba for comparable scope and more flexible on professional services pricing . Best for organizations where forecasting sophistication and audit trails weigh heavily in selection .



- **[TIS (Treasury Intelligence Solutions)](https://www.tis.com/)**

  SaaS platform for corporate payments, bank connectivity, and treasury operations. Integrates with SAP and other ERPs to automate payment flows, offering **connectivity with 11,000+ banks**, cash flow visibility, process automation, and fraud control . Strong for payment factory automation and bank relationship management.



- **[Modern Treasury](https://www.moderntreasury.com/)**

  **Payment operations platform** built for engineering teams moving money on behalf of end users across ACH, wires, RTP, FedNow, push-to-card, checks, and stablecoins . Different from a TMS—not for managing company's own cash but for programmatic money movement. Deploys in **4-12 weeks** for a first rail live in production . Platform minimum plus usage-based per-transaction fees.



- **[Atlar](https://www.atlar.com/)**

  Modern treasury management platform for mid-market companies. Features cash visibility, payment automation, and bank connectivity.



- **[Agicap](https://agicap.com/)**

  Cash flow management platform for SMEs. Features cash forecasting, bank synchronization, and treasury dashboards.



- **[Coupa Treasury](https://www.coupa.com/)**

  Treasury module within Coupa's business spend management platform. Integrates treasury with procurement and expense workflows.



- **[ION Treasury](https://www.iongroup.com/)**

  Enterprise treasury and risk management solutions. Features cash management, payments, and risk analytics.



- **[FIS Quantum](https://www.fisglobal.com/)**

  Enterprise treasury management platform with cash positioning, forecasting, and risk management. FI-grade for large enterprises .



- **[Hazeltree](https://www.hazeltree.com/)**

  Treasury and portfolio management platform for hedge funds and asset managers. Features cash management, financing, and counterparty risk.



## Open-Source GitHub Projects



- **[Nexus Treasury](https://github.com/azaharizaman/nexus-treasury)**

  Atomic package for treasury management—liquidity pools, cash concentration, working capital optimization, and treasury analytics (PHP) . Features **treasury policy management** with configurable thresholds (minimum cash balance, maximum single transaction, approval threshold), **authorization limits** per user/role with currency support, **approval workflows** for transactions requiring authorization, **multi-currency support**, and comprehensive status tracking . The most directly applicable open-source treasury policy engine available.



- **[Vestiarion](https://github.com/duongnq2798/vestiarion)**

  Autonomous treasury agent for small business, settled in USDC on Arc (MIT) . **Screens counterparties, pays invoices under explicit guardrails, releases contractor milestones, and sweeps idle cash to yield**—every decision signed into a hash-chained audit ledger . **The most advanced open-source autonomous treasury agent available**, with 312 merged PRs in 18 days demonstrating active development.



- **[Vantage-Point](https://github.com/rasali535/vantage_point)**

  Agentic treasury engine with **mathematical anti-whipsaw filter layer** (Kaufman's Efficiency Ratio, ATR volatility scaling) executing prior to AI deliberation . **Agentic Boardroom Council** with four specialized agents: President/CEO (aggregates feedback, generates execution payload), General Counsel (compliance audit against enterprise risk rules), Risk Officer (volatility calculation, drawdown tolerance, trade size verification), Operations Officer (infrastructure health, execution node status) . **Zero-Trust Resilience** with 8-second route circuit-breaker and MongoDB isolation .



- **[Convex](https://github.com/sujitn/convex)**

  High-performance fixed income analytics library in Rust (published crates) . Features **yield curve bootstrapping, bond pricing (< 1 μs), YTM calculation (< 10 μs), Z-spread (< 50 μs), portfolio pricing (1000 bonds < 10 ms)** . Day count conventions (ACT/360, ACT/365, 30/360 US, 30E/360, ACT/ACT ICMA, ACT/ACT ISDA), holiday calendars with O(1) bitmap lookup, and **MCP server for agent integration** . **The fastest open-source fixed income pricing engine available.**



- **[IdleFinance](https://pypi.org/project/IdleFinance/)**

  Python library embedding portfolio theory, risk modeling, and asset pricing directly into pandas ecosystem (PyPI) . Features **Black-Litterman portfolio optimization** with flexible constraint handling, **shrinkage covariance estimators** (Ledoit-Wolf, OAS), **factor models** (Fama-French 3/5), **dynamic volatility models** (CCC, OGARCH), **risk decomposition** (MCTR, CVaR), and **fixed income analytics** (bond pricing, duration, convexity, YTM) . **The most comprehensive open-source quantitative finance toolkit for yield optimization.**



- **[BudgetBotics](https://codeberg.org/RoxanneA/BudgetBotics)**

  Open-source AI-powered platform for stock buyback planning and governance (Codeberg) . Features **buyback planning with budget computation based on cash, debt covenants, liquidity, and capital structure**, SEC Rule 10b-18 compliance, EPS accretion/dilution modeling, **AI-powered anomaly detection**, and immutable audit trail . Relevant for capital return optimization as alternative to yield products.



- **[Flowy](https://github.com/Xen0Xys/Flowy)**

  Self-hosted finance platform for shared money management (Docker Compose, PostgreSQL) . Features multi-account tracking (checking, savings, credit, cash, investment), shared account permissions, custom merchant/category catalog, and budget tracking . **Roadmap includes investment portfolio tracking and MCP server for LLM assistant** . Relevant for treasury teams managing multiple entity accounts.



- **[Puzzle](https://github.com/BaDaaS/puzzle)**

  Privacy-first asset management platform for businesses and sole traders (GPL-3.0) . **Take control back of your assets—crypto, stocks, real estates, T-bills, cash** . Self-hosted with complete control over financial data. Relevant for treasury teams holding mixed asset portfolios.



### Additional Strong Open-Source Options



- **[Picsou Finance](https://github.com/Cloeille/picsou-finance)** — Self-hosted personal finance dashboard tracking bank accounts, brokerage, crypto, and net worth . Relevant architecture for treasury dashboards.

- **[shared-finances](https://github.com/ynixt/shared-finances)** — Spring + Angular personal/group finance control . Reference for multi-entity permission models.

- Community **n8n** workflows for yield rate monitoring and sweep execution alerts.



**Frameworks for building custom systems**: Combine **Nexus Treasury** for policy management and approval workflows with **Convex** for fixed income pricing and yield curve bootstrapping, **IdleFinance** for portfolio optimization and risk decomposition, **Vestiarion** for autonomous sweep execution with audit trails, and **PostgreSQL** for persistence—creating a fully self-hosted, enterprise-grade treasury yield optimization platform.



## How to Contribute



1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer



- This is a **community-curated** list — not exhaustive and not an endorsement.

- Treasury yield optimization systems handling corporate cash must comply with internal treasury policies, investment guidelines, and applicable financial regulations.

- **Open-source treasury yield optimization is emerging but incomplete.** Nexus Treasury provides policy and approval workflows . Convex provides fixed income pricing . IdleFinance provides portfolio optimization . Vestiarion provides autonomous sweep execution . **No single open-source tool provides the end-to-end TMS of Kyriba or GTreasury.** Integration work is required.

- **"Yield optimization" requires policy guardrails.** Kyriba and GTreasury enforce investment policies, counterparty limits, and approval workflows . Vestiarion explicitly screens counterparties and pays under "explicit guardrails" . Never deploy autonomous yield sweeping without deterministic policy enforcement.

- **Treasury is not payment operations.** Modern Treasury is built for engineering teams moving money on behalf of end users—not for managing company's own cash . Choose the right tool for the job.

- **Enterprise TMS pricing is opaque.** Kyriba and GTreasury both quote-based; expect **$70,000-$1,500,000+/year** for enterprise suites plus **$50,000-$800,000+** implementation . Open-source alternatives require engineering investment instead of license fees.

- Self-hosted open-source solutions require proper security hardening, bank connectivity setup, and ongoing maintenance. Corporate cash is financially sensitive—access controls and audit trails are essential.



---



**Made for treasury teams, finance engineers, and developers building transparent yield optimization solutions.**  

Let's make Corporate Treasury Yield Optimization more open, data-driven, and policy-compliant.
