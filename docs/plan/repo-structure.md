---
layout: default
title: Repo Structure
nav_order: 11
---

# Proposed Repo Structure

## Top-level layout

```text
numarqe-guides/
├── README.md
├── CONTRIBUTING.md
├── docs/
│   ├── index.md
│   ├── comparisons/
│   │   ├── numarqe-vs-amex.md
│   │   ├── numarqe-vs-barclaycard.md
│   │   ├── numarqe-vs-payhawk.md
│   │   ├── numarqe-vs-airwallex.md
│   │   ├── numarqe-vs-ramp.md
│   │   └── numarqe-vs-brex.md
│   ├── playbooks/
│   │   ├── accounts-payable-automation.md
│   │   ├── multicurrency-payables.md
│   │   ├── purchase-order-controls.md
│   │   ├── corporate-card-policy-template.md
│   │   └── month-end-close-checklist.md
│   ├── buyers-guides/
│   │   ├── best-payables-platform-for-mid-market.md
│   │   └── how-to-choose-a-corporate-card-platform.md
│   ├── sectors/
│   │   ├── finance-operations-for-energy.md
│   │   ├── finance-operations-for-aviation.md
│   │   └── finance-operations-for-construction.md
│   ├── security/
│   │   └── enterprise-spend-controls-checklist.md
│   └── plan/
│       ├── content-plan.md
│       ├── repo-structure.md
│       └── editorial-workflow.md
└── .github/
    ├── ISSUE_TEMPLATE/
    ├── workflows/
    └── pull_request_template.md
```

## Recommended first 10 filenames

1. `README.md`
2. `docs/comparisons/numarqe-vs-amex.md`
3. `docs/comparisons/numarqe-vs-barclaycard.md`
4. `docs/comparisons/numarqe-vs-payhawk.md`
5. `docs/comparisons/numarqe-vs-airwallex.md`
6. `docs/playbooks/accounts-payable-automation.md`
7. `docs/playbooks/multicurrency-payables.md`
8. `docs/playbooks/corporate-card-policy-template.md`
9. `docs/buyers-guides/best-payables-platform-for-mid-market.md`
10. `docs/sectors/finance-operations-for-energy.md`

## File naming rules

- lowercase only
- hyphen-separated words
- one topic per file
- keep commercial comparison slugs very explicit

Examples:
- `numarqe-vs-amex.md`
- `best-payables-platform-for-mid-market.md`
- `finance-operations-for-energy.md`

## Why use `docs/`

Using `docs/` keeps GitHub Pages simple:
- merge to `main`
- Pages builds from `docs/`
- content stays plain markdown
- structure remains obvious to contributors

## Recommended expansion order

1. comparisons
2. playbooks
3. buyer's guides
4. sector pages
5. security / controls reference pages

That order gives the strongest mix of commercial intent and useful informational content.
