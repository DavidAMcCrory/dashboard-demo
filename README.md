# Enterprise Technology Risk Dashboard — Demo

A single-page executive dashboard built from scratch in pure HTML and CSS, designed to replicate the kind of reporting artefact a Technology Risk or GRC function would present to senior leadership or a Board committee.

**Live demo:** [davidamccrory.github.io/dashboard-demo](https://davidamccrory.github.io/dashboard-demo/) &nbsp;|&nbsp; **Source:** [DavidAMcCrory/dashboard-demo](https://github.com/DavidAMcCrory/dashboard-demo)

---

## What it demonstrates

### Domain knowledge — Technology Risk & GRC
The content is drawn from real-world enterprise risk management practice:

- **Risk Appetite Alignment** — RAG-rated assessment of risk exposure against Board-approved appetite statements across six domains (Cybersecurity, Third-Party, Cloud, AI, Operational Resilience, Data Governance)
- **Key Risk Indicators (KRIs)** — metric-level thresholds with trend indicators and breach status, mirroring how a risk function tracks leading indicators
- **Control Effectiveness** — segmented bar visualisation of control testing results across IAM, Change Management, and Backup & Recovery domains
- **Issues & Audit Management** — open issue register with severity classification, ownership, and overdue tracking
- **Third-Party Risk** — vendor portfolio stats and highlighted exceptions requiring management attention
- **Emerging Risk (AI & Technology)** — AI use case governance metrics and a narrative risk assessment covering model risk, prompt injection, agent tool permissions, runtime monitoring, and AI incident readiness, referencing PIPEDA, OSFI Guideline E-23, NIST AI RMF, and ISO/IEC 42001

This reflects hands-on familiarity with how technology risk is communicated in regulated financial services environments (insurance, banking). Includes prioritization and time-bound management actions aligned to audit and remediation cycles.

### Front-end craft — no frameworks, no dependencies
The dashboard is intentionally built without any JavaScript libraries, CSS frameworks, or build tools — just a single `index.html` file. This demonstrates:

- **CSS custom properties** for a consistent, themeable design system (colour palette, typography, spacing)
- **CSS Grid** for the two-column responsive layout and full-width card spans
- **Semantic HTML** with appropriate use of `<table>`, `<header>`, `<footer>`, and sectioned card components
- **Visual hierarchy** — typography scale, colour-coded status badges (RAG), progress bar segments, and stat boxes communicate information density without clutter
- **Print stylesheet** — a dedicated `@media print` layer keeps cards intact across page breaks so the artifact exports cleanly to PDF as a board-pack-style report
- **Responsive layout** — a single mobile breakpoint collapses the grid to one column for phone viewing without altering the desktop board-pack presentation

---

## Who this is for

This project is a portfolio piece aimed at roles in:

- **Technology Risk Management** (1LOD / 2LOD)
- **GRC / IT Risk & Compliance**
- **Enterprise Risk Reporting**
- **Risk technology / risk tooling product roles**

It shows the ability to translate domain expertise into a polished, self-contained deliverable — without needing a developer to build it.

---

## Author

David McCrory — [github.com/DavidAMcCrory](https://github.com/DavidAMcCrory)

---

## Portfolio Demo Notice

This repository is a public portfolio demonstration. Dashboard data, incidents, vendors, metrics, and management actions are synthetic examples and are not connected to production systems or real employer/client environments.

No secrets or credentials are intended to be stored in this repository.

