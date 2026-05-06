# Sumble Strategic Outreach (Outbound) — Research Briefs

This directory holds **Outbound Strategic Research Briefs** — both the reusable template and completed instances. Briefs are produced via the Outbound Strategic Sales Motion documented in the main [Sumble Sales Brain](../Sumble%20Sales%20Brain.md) (see `## Workflows` → `Outbound Sales Brain — target deep-research methodology`).

## How to start a new brief

**Trigger phrase:** *"Create use case for [target]"* (single account) or *"Create use cases for [cluster name]"* (cluster — produces one brief per member).

1. Copy [`TEMPLATE.md`](TEMPLATE.md) to `{target-company}-{anchor-prospect}-{YYYY-MM-DD}.md` in this directory.
2. Run the 10-phase Outbound Sales Brain methodology (Sumble MCP + WebFetch + WebSearch).
3. Fill every bracketed placeholder. No sections are optional.
4. Commit. The brief is now a permanent reference + reusable proof point.

## Single account vs. cluster runs

- **Single account:** one brief file. Sumble pitches one target (e.g., Gong) with one anchor prospect (e.g., LastPass).
- **Cluster:** N brief files in this directory, one per cluster member. Same methodology, different *intricacies* per company. The cluster's intricacy table lives in the methodology doc; each individual brief has its own complete file. Example cluster: Zendesk → Intercom → Freshworks → Salesforce Service Cloud → ServiceNow CSM → Forethought → Ada → HubSpot Service Hub → Genesys / NICE / Five9.

## What lives here

Each brief is a self-contained 9-section deliverable for a single outbound target company (the company Sumble is pitching). Every brief documents:

1. **TL;DR** — 2-line summary (problem + anchor + magnitude)
2. **Business Problem Sumble Solves For [Target]** — anchored to a public sales goal when one exists
3. **Anchor prospect** — `[NEW LOGO]` or `[WIN-BACK + EXPANSION]` tagged
4. **Why the anchor fits the trophy pattern**
5. **Financial frame** — segment-by-segment math
6. **Strategic frame** — trigger events, why now, why the window will close
7. **Buyer at the prospect** (per *target's* ICP)
8. **What Sumble surfaced** (that ZoomInfo / Apollo / 6sense / Clay / Demandbase cannot)
9. **The pitch the target should run**

Plus a **Methodology** block at the bottom documenting how the MCP query path produced the brief (essential for showing *how Sumble surfaced this*, which is part of the proof).

## Filename convention

`{Prospect}-{AnchorCompany}-{SumblePlay}.md`

- **Prospect** — the target company Sumble is pitching, brand-cased (e.g., `Gong`, `SolarWinds`, `Five9`).
- **AnchorCompany** — the anchor prospect named in the brief, brand-cased (e.g., `LastPass`, `YETI`, `Mastercard`). For engaged accounts with no anchor company, use the named individual (e.g., `ColetteBishogo`).
- **SumblePlay** — the dominant Sumble play this brief executes, PascalCase (e.g., `MQLEnrichment`, `TriggerEvent`, `ABMListBuild`, `ExpansionDefense`, `EngagedAccount`, `TechDisplacement`, `CRMEnrichment`).

Example: `Gong-LastPass-TriggerEvent.md` — Sumble pitching Gong, with LastPass as the anchor prospect, executing the new-CRO trigger-event play.

The date sits inside the brief's frontmatter (`**Date:** YYYY-MM-DD`), not the filename — keeps filenames stable across re-runs and clean in URL paths.

## How briefs get made

Per the methodology:
1. Eric names the target company (or asks for a recommendation).
2. ~3 minutes of Sumble MCP research (~150–350 credits typical):
   - `GetMyCompanyProfile` (free) to refresh Sumble's persona/play context
   - WebFetch the target's homepage + customer-stories page
   - `EnrichOrganization` on the target — map their GTM data stack
   - `FindJobs` on the target — surface initiatives + spear-tip product
   - `FindPeople` on the target — build the persona shortlist
3. Phase 6.5 anchor query pre-validation — confirm ICP filter set + competitor set with Eric before spending search credits.
4. Anchor identified → verified via `EnrichOrganization` + `FindPeople` on the anchor → segment-by-segment pipeline math.
5. Brief drafted in this folder, then a persona-specific cold email drafted to Gmail with SFDC BCC.

## Index

| Date | Target | Anchor | Sumble Play | Magnitude |
|---|---|---|---|---|
| 2026-05-06 | [Genesys](Genesys-Mastercard-ABMListBuild.md) | Mastercard | ABM List-Build | $3M–$7M anchor ACV; ~$160M qualifying pipeline/yr (~18% of $910M net-new Cloud ARR target) |
| 2026-05-06 | [Five9](Five9-SoFi-MQLEnrichment.md) | SoFi | MQL Enrichment | $750K–$1.5M anchor; ~$45M qualifying pipeline/qtr (~90% of >40% AI growth target) |
| 2026-05-06 | [Gladly](Gladly-YETI-MQLEnrichment.md) | YETI | MQL Enrichment | $200K–$400K anchor; ~$8M annualized new-logo ARR from a single play |
| 2026-05-06 | [SolarWinds](SolarWinds-Leidos-ExpansionDefense.md) | Leidos | Expansion-Defense | $500K–$2M anchor; ~$7M–$14M defendable ARR/qtr (10–18% of net-new sub ARR) |
| 2026-05-06 | [Sana](Sana-ColetteBishogo-EngagedAccount.md) | (engaged-account, no anchor) | Engaged Account | Live thread + multi-thread to NYC May 21 Summit |
| 2026-05-06 | [Gong](Gong-LastPass-TriggerEvent.md) | LastPass | Trigger Event (new CRO) | $500K–$800K anchor; ~$25M new ARR/yr lookalike play |
| 2026-05-06 | [Xero](Xero-OrionHealth-TechDisplacement.md) | Orion Health (NZ) | Tech-Stack Displacement | $200K–$500K anchor; ~$2M–$4M annualized NZ mid-market TAM |
