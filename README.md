# 🏥 Libby's Habbadabba Dashboard

**Activity Attendance Tracker** — a single-page web app for tracking patient activity attendance across multiple units.

## Features

- **Multi-unit support** — Switch between Unit 1 (North), Unit 2 (South), and Unit 3 (East)
- **Per-patient attendance** — Set daily attendance in minutes for each patient
- **Weekday/Weekend options** — Weekdays: 0, 45, 90 mins. Weekends: 0, 45, 90, 120, 240, 330 mins
- **Automatic weekly totals** — See each patient's total at a glance
- **CSV export** — Download attendance data as a CSV report
- **State persistence** — Data stays intact when switching between units
- **Inline patient editor** — Add, remove, or rename patients per unit. Existing attendance data is preserved for patients whose names stay the same

## Usage

1. Select a unit from the dropdown
2. Set attendance minutes for each patient per day using the dropdowns
3. Weekly totals auto-calculate
4. Click **Export to CSV** to download the report

## Tech Stack

- Pure HTML / CSS / JavaScript — no dependencies
- GitHub Pages hosted

## License

All Rights Reserved. See [LICENSE](LICENSE) for full terms.
