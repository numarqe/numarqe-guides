---
layout: default
title: Editorial Workflow
nav_order: 12
---

# Editorial Workflow

## Short answer

On GitHub, use pull requests, not merge requests.

Flow:
- issue documents the brief, target keyword, backlinks and acceptance criteria
- branch carries the draft work
- pull request is the review gate
- merge to `main` publishes to GitHub Pages

## Workflow stages

### 1. Open an issue

Use issues for:
- strategy decisions
- page briefs
- draft tracking
- editorial review
- SEO QA
- publish follow-ups

Each content issue should include:
- page title
- target URL slug
- content type
- target keyword / query intent
- related Numarqe product page links
- required backlinks
- acceptance criteria

### 2. Create a branch

Suggested branch naming:
- `docs/compare-amex`
- `docs/playbook-ap-automation`
- `docs/sector-energy`
- `ops/pages-workflow`

### 3. Draft in markdown

Each draft should:
- follow the page template in the issue
- include backlinks to [numarqe.com](https://numarqe.com/)
- include internal links to related docs in this repo
- avoid direct duplication of live site copy

### 4. Open a PR

PR should include:
- linked issue
- summary of what was added
- page URLs affected
- backlink targets used
- checklist for review

### 5. Review

Review should check:
- factual accuracy
- commercial positioning
- readability
- duplicate-content risk
- backlink coverage
- title and headings
- markdown rendering

### 6. Merge to `main`

Once merged:
- GitHub Pages rebuilds the site
- content goes live from the repository markdown

## Labels to use

### Type labels
- `type:comparison`
- `type:playbook`
- `type:buyers-guide`
- `type:sector`
- `type:ops`

### Stage labels
- `stage:brief`
- `stage:draft`
- `stage:review`
- `stage:ready`
- `stage:published`

### Supporting labels
- `seo`
- `backlinks`
- `high-intent`

## Recommended issue flow for each page

1. create issue with brief
2. apply `stage:brief`
3. start draft branch
4. move to `stage:draft`
5. open PR
6. move to `stage:review`
7. merge PR
8. move issue to `stage:published`
9. add live Pages URL and backlinks used in a final comment

## Where planning lives

The canonical plan lives in-repo:
- `docs/plan/content-plan.md`
- `docs/plan/repo-structure.md`
- `docs/plan/editorial-workflow.md`

Do not make the wiki the source of truth.

## Why not use the wiki for the main plan

- no tight PR review loop
- easier for docs to drift away from implementation
- less visible in repo history
- harder to tie to issues and branches

The repo itself should be the operational system. The wiki can stay optional.
