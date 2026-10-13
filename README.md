# Walmart Digital Transformation KPI Dashboard

> **Academic demonstration only — this is not an actual Walmart project.**
>
> This dashboard was created as a Week 7 Group 9 classroom demonstration for the **Value & KPIs** activity. It is not an official Walmart product, internal report, company-sponsored engagement, or representation of Walmart's own dashboards or systems. It is not affiliated with, endorsed by, or maintained by Walmart Inc. The Walmart name and referenced public disclosures are used only to frame the educational example.

## Overview

`walmart_kpi_dashboard.html` is a browser-based, executive-style KPI dashboard exploring a proposed digital-transformation thesis for Walmart Inc. across fiscal years 2023–2026. It demonstrates how a set of public-disclosure metrics can be brought together to discuss digital revenue mix, platform monetization, investment intensity, margins, productivity, and digital sales contribution.

The dashboard is a **static, illustrative analysis**. Its data and calculation assumptions are embedded in the HTML file; it does not connect to Walmart's internal systems, a live reporting service, or an external data API. Values, estimates, interpretations, and attribution of causes should be checked against original disclosures before they are used outside this classroom demo.

## Dashboard contents

The dashboard is organized into four sections:

1. **Dashboard** — executive readout, KPI summary cards, and eight charts.
2. **Data & notes** — period-by-period metric table, calculations, estimates, and comparability cautions.
3. **Thesis & rationale** — the transformation thesis, KPI selection rationale, and strategic interpretation included in the demo.
4. **Sources & team** — linked disclosure register and team roles.

### The eight KPIs

| # | KPI | Indicator type | Periods |
|---|---|---|---|
| 1 | eCommerce Sales as % of Total Revenue | Lagging | FY2023–FY2026 |
| 2 | Global eCommerce Growth, YoY | Leading | FY2023–FY2026 |
| 3 | Global Advertising Revenue Growth | Lagging | FY2023–FY2026 |
| 4 | Membership & Other Income | Lagging | FY2023–FY2026 |
| 5 | Capital Expenditures as % of Revenue | Leading | FY2023–FY2026 |
| 6 | Gross Profit Rate | Lagging | FY2023–FY2026 |
| 7 | Revenue per Employee | Lagging | FY2023–FY2026 |
| 8 | Walmart U.S. eCommerce Contribution to Comp Sales | Leading | Q4 FY2023–Q4 FY2026 |

The data window includes three annotated inflection points:

- **FY2024 — Global eCommerce Growth, YoY:** the value rises from approximately 12.2% to 21.9%; the dashboard notes reported store-fulfilled pickup and delivery adoption as context.
- **FY2026 — Global Advertising Revenue Growth:** the reported figure rises from 27% to 46%; the dashboard explicitly notes that FY2026 includes acquired VIZIO advertising revenue and should not be interpreted as wholly organic growth.
- **Q4 FY2026 — U.S. eCommerce Contribution to Comp Sales:** the reported contribution rises from approximately 290 to 520 basis points; the dashboard describes the context disclosed around expedited store-fulfilled delivery.

Each annotated event is an analytical explanation for discussion, not proof that a single event caused the measured change.

## Interactive features

Depending on browser and CDN availability, the dashboard supports:

- Navigation between the four dashboard sections.
- Light and dark themes.
- A **Show all sections** view for review and printing.
- Searching KPI cards and filtering by leading or lagging indicators.
- Focusing/expanding a chart for closer inspection.
- Exporting individual charts as PNG images.
- Exporting the KPI dataset to CSV.
- Printing or saving the dashboard as a PDF through the browser's print dialog.
- Responsive layouts for desktop, tablet, and mobile screen sizes.

## How to open it

1. Keep `walmart_kpi_dashboard.html` and `README.MD` together in the same folder.
2. Open `walmart_kpi_dashboard.html` directly in a current version of Chrome or Firefox. No local server or build step is required.
3. Keep an internet connection available so the browser can load Chart.js and its annotation plugin from the public CDNs used by the page.
4. Use the dashboard tabs to review the charts, source notes, rationale, and contributor section.

The file's dashboard data is hard-coded locally in JavaScript. Internet access is needed for the charting libraries, not for an API-based data feed. If the CDN libraries cannot load, the page displays a notice and interactive charts may not render.

## Data and methodology notes

- Values are based on the named SEC filings and Walmart investor-relations disclosures listed in the dashboard's source register (S1–S9).
- Some values are calculated from reported values; some are approximate because source figures or headcount are rounded. The dashboard labels these cases and includes notes on calculations and comparability.
- **Capital Expenditures as % of Revenue** is a broad investment-intensity proxy. It includes multiple kinds of capital spending and does not isolate digital-transformation investment.
- **Revenue per Employee** uses approximately 2.1 million reported associates and is therefore directional, not a precise full-time-equivalent productivity measure.
- The **Membership & Other Income** series is a consolidated line and includes non-membership items.
- Fiscal periods may not be perfectly comparable; the dashboard notes that FY2025 had 53 weeks compared with 52 weeks in FY2024.
- The digital-sales contribution to comparable sales is part of total comparable growth; the comparison shown does not independently establish causality or quantify physical-store demand in isolation.
- The FY2026 advertising growth figure includes VIZIO-related acquisition impact; it should not be read as a clean measure of organic ad-platform growth.
- The dashboard is not live and does not update automatically. The values and calculations are embedded in the file.

**Important:** Public-source links are supplied for traceability, but this README does not independently audit every figure or reproduce the full underlying filing methodology. Verify each figure, date, assumption, and interpretation against the original disclosure before using it for graded work, external presentation, investment decisions, or business decisions.

## Source register

The dashboard includes links to these nine public disclosures, with dates and metric coverage:

| ID | Source | Disclosure date |
|---|---|---|
| S1 | Walmart FY2023 Form 10-K | March 17, 2023 |
| S2 | Walmart FY2024 Form 10-K | March 15, 2024 |
| S3 | Walmart FY2025 Form 10-K | March 14, 2025 |
| S4 | Walmart FY2026 Form 10-K | March 13, 2026 |
| S5 | Walmart FY2023 Q4 Earnings Release | February 21, 2023 |
| S6 | Walmart FY2024 Q4 Earnings Release | February 20, 2024 |
| S7 | Walmart FY2025 Q4 Earnings Release | February 20, 2025 |
| S8 | Walmart FY2026 Q4 Earnings Release | February 19, 2026 |
| S9 | Walmart FY2026 Q4 Earnings Presentation | February 19, 2026 |

Use the links in the dashboard's **Sources & team** section to open each record.

## Team attribution

The dashboard credits the contributors for the classroom activity as follows:

- **Lira Sandoval Campos — Member A, Metric Selector:** transformation thesis, KPI selection, KPI rationale, and strategic interpretation.
- **Giang Khuu — Member B, Data Analyst:** public-disclosure data package, estimates and comparability notes, and inflection-point analysis.
- **Hudson Trussell — Member C, Dashboard Builder:** collaborated on parts of the shared HTML/Chart.js dashboard.
- **Azimjon Izzatillaev — Member C, Dashboard Builder:** collaborated with Hudson on parts of the shared HTML/Chart.js dashboard.

Hudson and Azimjon are shown as separate contributors but are credited with shared Member C responsibility; the dashboard does not assign exclusive ownership of individual components between them.

## Technology

- HTML5 and CSS for structure, styling, responsive layout, and printing.
- JavaScript for embedded data, interface controls, summary cards, source register, CSV export, and chart initialization.
- [Chart.js](https://www.chartjs.org/) for charts.
- [Chart.js annotation plugin](https://www.chartjs.org/chartjs-plugin-annotation/latest/) for inflection-point markers.
- Charting libraries are loaded from a CDN, so the HTML file is self-contained in its data and application code but **not fully offline/self-contained with respect to third-party libraries**.

## License and usage

No separate software license is specified for this classroom artifact. The dashboard is shared for educational demonstration and review. Do not represent it as an official Walmart deliverable, live company dashboard, or audited financial analysis. Respect the source terms for any third-party code or public documents referenced.
