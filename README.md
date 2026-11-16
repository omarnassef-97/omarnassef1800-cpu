# Hi, I'm Omar 👋

RF/Network Optimization Engineer (5 years across Huawei and Nokia, 2G/3G/LTE/5G) who builds Python tooling to automate the analysis work that used to eat my week — and closed-loop automation that acts on what it finds.

## What I build

- **Closed-loop network remediation** — designed and built KPI-triggered automated configuration-change and self-rollback logic for a commercial SON platform (detect a degraded condition → apply a targeted change → verify recovery → auto-revert). Measurably improved traffic performance by ~50% on affected cells, with gains across other key KPIs. Written up as a case study rather than published as code, since it integrates with vendor-licensed network management systems.
- **lte-overshoot-analyzer** — geometric neighbor-relation detection (haversine + azimuth alignment) fused with live KPI data to flag overshooting cells, with fuzzy column-name resolution for messy real-world exports. Iterated through 4 versions, the last consolidating four duplicated KPI-loading paths into one.
- **lte-cell-kpi-trend-engine** — statistical trend detection across 2G/3G/LTE KPIs using robust (median/MAD-based) week-over-week comparison, with daily incremental state for scheduled runs. Backs a Power BI dashboard that ranks degrading cells by severity and forecasts near-term KPI behavior.
- **lte-busy-hour-analyzer** — busy-hour and threshold-exceedance detection, rewritten from row-wise to fully vectorized for large daily exports.
- **lte-3g-kpi-degradation-gui** — a desktop tool colleagues without Python can run, comparing current KPIs against 14/30-day historical baselines.

## Dashboards

- **MOGA Network Performance Dashboard** (Power BI) — upgrade-impact tracking, traffic trends, and QoS KPIs across the MOGA region, with geographic drill-down and a "Top Runners" ranking of best-performing sites.
- **Cell KPI Trend Dashboard** (Power BI) — predictive, cell-level view of network performance combining current and forecasted KPIs, with severity-ranked degradation and ownership routing for faster resolution.

## Toolbox

Python (pandas, NumPy, openpyxl, pyodbc, tkinter) · SQL · Power BI · Tableau · AWS Cloud Practitioner

## Where I'm headed

Five years of turning inconsistent network data into decisions — and, more recently, into automated action — is good preparation for network automation and AI-assisted operations. That's where I'm building toward next.

## Connect

[LinkedIn](https://www.linkedin.com/in/omar-alaa-nassef)
