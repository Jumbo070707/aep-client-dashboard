# AEP Client Dashboard

Internal account management dashboard for Adobe Experience Platform (AEP) implementation and optimization engagements.

## Features

- **Account Overview** — Health status, engagement type, current phase, scope summary
- **AEP Scope Tracking** — Components in scope (RT-CDP, AJO, CJA, Offer Decisioning, Web SDK, etc.)
- **Timeline Management** — Phase-based project timeline with visual progress bars
- **Resourcing** — Team structure with roles and allocation percentages
- **Solution Design** — XDM schemas, datasets, audiences, journeys, destinations, data sources
- **Risk Tracking** — Active risks, issues, and blockers per account

## Tech Stack

- React 18 (CDN)
- Single-file HTML application
- localStorage persistence
- BAiCi design system (Inter font, dark enterprise theme)

## Usage

Open `index.html` in a browser, or serve locally:

```bash
python3 -m http.server 8000
```

## Data

All data persists in browser localStorage under key `aep-dashboard-v1`. Seed data is loaded on first visit.
