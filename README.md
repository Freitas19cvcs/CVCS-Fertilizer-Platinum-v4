# CVCS Turf + Irrigation Platinum v4.1

Live iPad-first landscape maintenance application for CVCS Landscaping.

## v4.1 easy-mode command system

- Six large iPad navigation buttons, larger account cards, plain-language status colors, and large touch targets.
- Correct Gold, Silver, and Bronze assignments imported from the CVCS Tier Master workbook.
- Connected care tiers: Gold (6 treatment windows), Silver (4), and Bronze (2).
- Separate property plans for standard sites, McDonald's, apartments, shrub-heavy properties, and recovery sites.
- Step-by-step workflows for fertilizer, fungus, weeds, irrigation, aeration, and seed work.
- Jalin Weststeyn's 13-step September-December 2026 recovery calendar is preloaded.
- Multi-controller irrigation profiles with timer location, brand/model, programs, and station-by-station mapping.
- Jalin's Programs A/B/C, Stations 1-20, seasonal settings, and seed-watering override are preloaded.
- Walk-through findings can automatically start weed, fungus, or irrigation workflows.
- Work Week view plus monthly, active-cycle, annual forecast, and individual-property PDF reports.
- Exact generated v4.1 PDFs are kept in on-device report history for reprinting.
- Existing v3.2 scheduler, products, diagnosis library, compliance reports, bids, history, and account data remain available under More.

## Data safety

This release is intentionally on-device: operational data uses browser storage, generated PDF files use IndexedDB, and JSON backup/restore includes the structured program and irrigation data. Use the app and backups on the same iPad until a later controlled phase adds authentication, cloud sync, permissions, and multi-device conflict handling.

## Deployment

GitHub Pages serves the root `index.html` from the `main` branch.
