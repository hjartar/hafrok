# Hafrok — European Offshore Wind Forward View

An independently compiled database and interactive dashboard tracking the full visible development pipeline of European offshore wind — 144 projects across 13 countries, totalling 165 GW of capacity.

**[View the dashboard](https://hjort.github.io/ofw-projects/)**

## What this covers

Every non-operational European offshore wind project above 100 MW:
- Under construction (COD 2025–2028)
- FID reached but not yet in construction
- Pre-FID (approved/permitted, awaiting financial close)
- Pipeline (in planning, consented, or in auction/tender process)

## Confidence scoring

Each project receives a 0–100 confidence score based on seven development parameters: FID status, offtake, consents, grid connection, time to COD, project complexity, and information recency. The confidence-weighted pipeline multiplies each project's capacity by its normalised score, converting a gross pipeline into a risk-adjusted demand signal.

| Segment | Score range | Projects | Capacity |
|---|---|---|---|
| Committed | 80–100 | 22 | 21.9 GW |
| Expected | 45–79 | 38 | 33.2 GW |
| Speculative | 0–44 | 84 | 110.0 GW |

## Data sourcing

Compiled through systematic web research across government registries, developer announcements, regulatory filings, and industry press. Every project cross-validated against at least two independent sources. Scoring engine is fully deterministic — no manual adjustments.

Primary sources include national energy agency databases (DESNZ, BSH, RVO, Energistyrelsen, CRE), Crown Estate / Crown Estate Scotland leasing portals, developer corporate disclosures, and specialised offshore wind media.

## Built with

- Data compilation and cross-validation: [Claude Code](https://claude.ai/code) (Claude Opus 4.6)
- Map: [Leaflet](https://leafletjs.com/) with [CartoDB](https://carto.com/) tiles
- Lease area polygons: [EMODnet Human Activities](https://emodnet.ec.europa.eu/en/human-activities) WFS + Crown Estate ArcGIS
- EEZ borders: [Marine Regions](https://marineregions.org/) (VLIZ)

---

Data as of February 2026.
