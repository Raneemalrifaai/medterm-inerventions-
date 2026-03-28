# Kanaleneiland — WHO Healthy Cities Analysis

Interactive analysis of Kanaleneiland, Utrecht against WHO European Healthy Cities Phase VII 2019–2024 criteria.

**Live site:** `https://[your-username].github.io/kanaleneiland/`

---

## Pages

| File | # | Description |
|---|---|---|
| `index.html` | — | Homepage — overview, stats, location summaries, user manual |
| `bubble_map.html` | 01 | Interactive WHO 6P relationship bubble network |
| `6p_criteria.html` | 02 | WHO Phase VII benchmark vs CBS measured scores |
| `cascade_map.html` | 03 | Intervention → health outcome causal map |
| `intervention_sequence.html` | 04 | Six-step prioritised intervention guide |
| `full_intervention.html` | 05 | Full 20-slider simulator — 7 scenario presets |
| `location_simulator.html` | 06 | Real map + per-location problem/solution simulator |
| `sources.html` | 07 | Full evidence base, organised by WHO 6P pillar |

---

## Three priority locations (Location Simulator)

| # | Location | Coordinates | Key problem |
|---|---|---|---|
| 01 | Rooseveltlaan / 24 Oktoberplein | 52.07858, 5.08285 | Traffic junction, no green, no crossings |
| 02 | Winkelcentrum Nova | 52.07492, 5.09491 | Car-dominant, no public space, redevelopment 2024 |
| 03 | Beneluxlaan | 52.07244, 5.09900 | Highest noise, zero canopy, no cycle lane |

---

## Full Simulator — 7 scenario presets

1. **Current baseline** — all CBS measured values
2. **Greenery only** — green space, trees, parks raised
3. **+ Mobility** — adds cycle lanes and walking infrastructure
4. **Economic equity** — social and economic intervention
5. **Urban designers** — only spatially designable indicators shown
6. **Highest health impact** — only highest-coefficient indicators shown
7. **Full WHO HiAP** — all six pillars coordinated

---

## Deploy on GitHub Pages

1. Create a new repository (e.g. `kanaleneiland`)
2. Upload all `.html` files to the root
3. Go to **Settings → Pages → Source → main → / (root) → Save**
4. Live at `https://[username].github.io/kanaleneiland/`

No build step. No dependencies. Works offline in any modern browser.

---

## Data sources

- CBS OpenData Netherlands — Table 86270ENG
- CBS Gezondheidsmonitor Volwassenen en Ouderen 2020/2022
- WHO European Healthy Cities Network Phase VII 2019–2024
- Utrecht Monitor 2023
- Marmot Review 2010 · Holt-Lunstad 2015 · PMC 2021 · WHO GAPPA 2018 · WHO AQG 2021 · King's College Urban Mind 2021 · IPCC AR6 2021
