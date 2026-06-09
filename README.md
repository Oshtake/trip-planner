# Trip Planner — מתכנן נסיעות

A fully offline, single-file trip planning application for managing business and personal travel.  
Built with vanilla HTML/CSS/JavaScript — no server, no install, no dependencies to manage.

## Features

- **Multi-trip management** — create, clone, and switch between trips
- **Daily schedule** — drag-and-drop timeline with activity categories
- **Logistics** — flights, transfers, and hotel tracking with auto-sync from the schedule
- **Gantt chart** — visual overview of logistics and day types across the trip
- **Calendar view** — monthly calendar with day-level drill-down
- **Checklist** — pre-flight checklist with progress tracking
- **Budget tracker** — set a budget limit, track expenses, pull costs from transfers automatically
- **Readiness dashboard** — trip validation score with missing items highlighted
- **Export** — Excel (XLSX) and PDF export
- **Backup / Restore** — JSON backup and restore
- **Dark / Light theme** — toggle with one click
- **Hebrew / English** — full bilingual support (RTL/LTR)

## Usage

1. Open `מתכנן_נסיעות.html` in any modern browser (Chrome, Firefox, Edge, Safari).
2. All data is saved automatically to `localStorage` — no account or server needed.
3. Use **Backup** to export a JSON snapshot; **Restore** to reload it on another device.

## No Installation Required

This is a zero-dependency, single-file app.  
The only network requests are two CDN loads on first open:
- Google Fonts (Figtree, IBM Plex Mono)
- [SheetJS / xlsx.js](https://github.com/SheetJS/sheetjs) — for Excel export

Everything else runs fully offline after those assets are cached.

## File Structure

```
מתכנן נסיעות/
├── מתכנן_נסיעות.html   # The entire application
├── .gitignore
└── README.md
```

## Browser Support

Chrome 90+, Firefox 88+, Edge 90+, Safari 14+.

## License

MIT
