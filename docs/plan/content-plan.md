---
layout: default
title: Content Plan
nav_order: 10
---

# Numarqe GitHub Content Plan

## Goal

Build a public, markdown-first GitHub repository that ranks for buyer-intent and finance-operations search queries while sending strong, relevant backlinks to [numarqe.com](https://numarqe.com/).

## Positioning

This repository should not read like a spare copy of the marketing site.

It should position itself as:
- finance operations guidance
- AP and spend control playbooks
- vendor comparison content
- buyer's guides for mid-market finance teams
- sector-specific operating content

Primary framing:
“Open finance operations guides, AP playbooks and vendor comparisons by Numarqe.”

## Why this format works

A pure brochure repository is weak for both ranking and credibility.

A practical guide repository is better because it:
- targets long-tail search intent
- gives every page a clear purpose
- supports natural backlinks to product and conversion pages
- makes future content batching easy
- can publish directly via GitHub Pages with very little overhead

## Site pillars from the current Numarqe site

The current site suggests these content clusters:

### Product clusters
- corporate cards
- supplier payments
- procurement
- accounting integrations
- insights and analytics
- governance and controls

### Sector clusters
- energy
- travel and aviation
- yachting and marine
- international NGOs
- mining and resources
- construction
- professional services
- logistics and freight

### Comparison clusters
- Numarqe vs American Express
- Numarqe vs Barclaycard
- expansion comparisons: Payhawk, Airwallex, Ramp, Brex, Pleo, Spendesk

### Trust and buyer enablement clusters
- security requirements
- finance controls checklists
- case-study summaries
- implementation and buying guides

## Target content types

### 1. Comparison pages
Best for commercial intent.

Template:
- who each vendor fits
- where competitor is strong
- where card-only or point-solution tools stop
- where Numarqe extends into a wider payables and controls platform
- decision table
- buyer summary
- links to Numarqe product and comparison pages

### 2. Playbooks and checklists
Best for operational intent.

Template:
- problem definition
- checklist or framework
- common failure modes
- recommended operating model
- where platform support matters
- light Numarqe CTA

### 3. Buyer's guides
Best for higher-volume search and category positioning.

Template:
- what the category is
- evaluation criteria
- procurement checklist
- team questions to ask
- comparison categories
- why unified platforms outperform tool sprawl

### 4. Sector guides
Best for niche relevance and sector language.

Template:
- sector-specific spend patterns
- approval and control issues
- FX and supplier complexity
- project or field operations realities
- what finance teams need from tooling

## Publishing strategy

### Repository role
- canonical public markdown library
- linked from company site and profiles
- GitHub Pages deploy target

### Website role
- primary brand and conversion destination
- product depth
- demo / meeting CTA
- richer design and case-study presentation

### Linking strategy
Every page in this repo should link back to:
- https://numarqe.com/
- one or more product pages
- the comparison hub or sector page
- https://numarqe.com/book-a-meeting/

## First 10 priority pages

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

## Drafting standards

Each page should include:
- one clear search-intent title
- a short intro with the target phrase naturally included
- a useful body with original framing
- at least one table, checklist or decision structure where relevant
- a “Why Numarqe” section
- 2 to 4 backlinks to [numarqe.com](https://numarqe.com/)
- one soft CTA and one direct CTA

## Tone rules

Use:
- practical
- CFO / Finance Director / AP lead language
- credible, comparison-led framing
- straightforward trade-off language

Avoid:
- overclaiming
- generic startup hype
- thin SEO filler
- direct copy-paste from the marketing site

## Recommended workflow

Do planning, drafting and review through GitHub issues and pull requests:
- issue = brief / task / review record
- branch = one page or one batch
- PR = draft and review checkpoint
- merge to `main` = publish to GitHub Pages

## Where the full plan should live

Put the canonical plan in the repository, not the wiki.

Recommended location:
- `docs/plan/content-plan.md`

Why not the wiki:
- easier to version with content changes
- visible in PRs
- easier to keep close to templates and drafts
- avoids plan drift from the actual repo state

Use the wiki only if you later want a more free-form internal notebook. For now the repo itself should stay the source of truth.
