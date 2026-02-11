# Project Brief: HK POS Ads Planning

## What This Repo Is

This repo hosts a single-page HTML report for Hong Kong restaurant POS Meta ads planning.
Published via GitHub Pages from docs/.

## Audience

- Marketing: campaign setup and weekly optimization
- Sales: lead intake and follow-up SLA execution
- Ops: activation funnel and QA

## Current Scope (v1)

- Channel: Meta (Facebook/Instagram)
- Budget: HKD 6,000 for first 30 days
- Goal: lead acquisition + activation improvement
- Geo/language: Hong Kong, Traditional Chinese only

## Locked Inputs

- Lead intake SLA: first response within 5 minutes in business daytime
- Follow-up SLA: 3 follow-ups within 24 hours
- Temporary baseline: 7-day activation rate = 30% (denominator: successful login registrations)
- Effective activation definition:
  - completed registration/login
  - printer + payment terminal bound
  - menu input completed

## Repo Structure

- docs/index.html: live plan
- docs/versions/: historical snapshots
- scripts/publish.ps1: commit+push helper
- scripts/watch-publish.ps1: auto publish watcher

## Publishing

GitHub Pages:
- Branch: main
- Folder: /docs

## Iteration Rule

- Keep assumptions explicit
- Update stop/scale rules only with week-level data evidence
- If funnel definitions change, update docs/index.html and CHANGELOG.md in same commit
