# LANES — Patient Synopsis (UI prototype)

A static, self-contained HTML prototype of the LANES patient-synopsis page,
styled to the Falcon design system. Single file, no build step, no dependencies
(only Google Fonts loaded over the network; everything else is inline).

## Contents
- `index.html` — the full dashboard (demographics, coverage, encounters,
  readmissions, problems, allergies, medications, labs, vitals, social history,
  consent, ordered procedures) with two navigation modes (sidebar / tabs),
  collapsible filters, expanding search, and an Encounters-by-location chart.

## Running locally
Just open `index.html` in a browser, or serve the folder:

```bash
npx serve .
```

## Deployment
Deployed as a static site on Vercel (no framework; output is the repo root).
