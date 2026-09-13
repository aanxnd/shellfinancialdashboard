# Shell × Aerospace NBS — Carbon Compliance Financial Intelligence Platform

An interactive financial intelligence dashboard proposing a $600M/yr revenue strategy for Shell, repositioning its loss-making Nature-Based Solutions (NBS) portfolio as an embedded carbon compliance instrument for the aerospace manufacturing supply chain. Built for the Shell PIE Challenge 2026.

**[Live Demo](#)** · Built with vanilla HTML/CSS/JS — no dependencies, no build step

---

## The Core Thesis

Shell's NBS portfolio currently operates as a **$52M/yr cost centre**. This platform models a path to flip it into a **$22.5M–$281M/yr profit centre** by bundling forward carbon contracts, CBAM compliance documentation, and nature-backed credits into a single procurement line item — targeting SpaceX's 3,000+ supplier network ahead of its projected $1.5T IPO.

The dashboard exists to make that thesis interrogable: every number is a live variable, not a static claim.

## What It Does

### 📊 Overview
A data-dense landing page summarizing Shell's financial health, NCI/emissions pressure, existing NBS project portfolio, the target aerospace supply chain, CBAM's regulatory timeline, and community co-benefit structures — pulling from 20+ primary sources into one scannable view.

### 🎛️ Financial Scenario Modeler
The centerpiece: a live model where the user adjusts carbon price, supplier count, and coverage percentage via sliders (or three preset scenarios — Conservative, Base, Aggressive) and watches Shell's revenue, gross profit, NBS-investment coverage, and buyer liability recalculate in real time. Includes:
- A full formula breakdown panel showing exactly how each output is derived
- A CBAM-vs-margin comparison strip
- Contextual tooltips explaining every metric in plain language

### 🗂️ Research Intelligence Cards
12 filterable cards synthesizing financial pain points and market signals (Shell's earnings pressure, NBS credit quality crisis, CBAM cost exposure, SpaceX's IPO timeline, etc.), each with supporting data signals and proposed solution levers.

### 🔍 Searchable Statistics Browser
A searchable, filterable database of 90+ sourced data points spanning 20 categories — from Shell's quarterly earnings to aerospace material carbon intensity to mangrove flood-protection value — each tagged with its original source.

### 📈 Strategic Opportunity Matrix
Two impact-vs-feasibility matrices (one for Shell's strategic options, one for aerospace buyer adoption) plus a three-way value-creation breakdown showing how Shell, aerospace suppliers, and host communities all benefit financially.

### ⏳ Timeline & Competitive Window
A four-era timeline (2025–2040+) tracking regulatory triggers, carbon price escalation, and market expansion, alongside a flagged 12–18 month first-mover window before competitors lock in the aerospace segment.

## Tech Notes

- **Zero dependencies** — pure HTML/CSS/JS, no framework or build pipeline
- **Custom canvas animation** in the hero section (animated network-node visualization)
- **Fully responsive data structures** — all card/number/scenario data lives in JS objects (`CARDS_DATA`, `NUMBERS_DATA`, `SCENARIOS`), making content updates trivial without touching layout code
- **Live formula transparency** — every calculated metric has an accompanying breakdown showing its exact derivation, so the model is auditable rather than a black box

## Sources

Shell Annual Reports (2022–2024), Shell Q4 2025 Results, MSCI Carbon Markets Review 2025, BloombergNEF, South Pole Carbon Buyer Guide 2026, McKinsey Space Economy Report, FAA Environmental Impact Statements, NASA NTRS, Ecosystem Marketplace, and 15+ additional primary and industry sources (full citations in-app).

---

*Built as part of the Shell PIE Challenge 2026 submission.*
