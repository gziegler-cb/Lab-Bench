# Lab Bench

A prototype application for generating and reviewing innovative educational assessment items.

**Live demo:** https://gziegler-cb.github.io/Lab-Bench/

## What's here

The landing page offers two paths:

- **Invent** — _coming soon_ — generate new assessment item prototypes with AI assistance.
- **Review** — browse, sort, rename, and open existing item prototypes.

The Review screen currently contains three Phase 3 item examples:

| Item | Format |
| --- | --- |
| Public Comment Letter — Zoning Amendment | AI-mediated drafting task |
| Financial Literacy Graduation Requirement | Responsive revision (drafting → feedback → revising) |
| Explaining Reasoning | Multi-option analysis with free-text justification |

Each item opens its full interactive interface, including the "What this item assesses" panel intended for committee review.

## Running locally

This is a single static HTML file — no build step required. Either:

- Open `index.html` directly in any modern browser, or
- Serve the folder with any static server (e.g. `python -m http.server`) and visit `http://localhost:8000`.

React, ReactDOM, and Babel are loaded from `unpkg.com` at runtime, so an internet connection is required on first load.

## Stack

- React 18 (via CDN)
- Babel Standalone (in-browser JSX transpilation)
- Inline SVG icons (no icon library dependency)
