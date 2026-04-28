# Hall-3 Energy Tracker

A zero-dependency, offline-capable HTML app for IIT Kanpur Hall-3 residents to track meals, prevent post-meal sleepiness, and find their personal energy patterns.

## What it does

- **📅 Today**: Auto-detects current day + meal slot. Shows what's being served with 🟢🟡🔴 energy risk ratings. Lets you pick dishes with portion sizes and predicts crash risk.
- **📊 This Week**: 7-day sleepiness score grid. Click any day to see its full menu. Green = low sleepiness, Red = crashed.
- **📝 Log Entry**: One-tap logging of what you ate, portion size, water intake, post-meal activity, and sleepiness score (1–10) 2–3 hours later.
- **📈 Charts**: Automatic scatter plots showing correlations between your sleepiness and (a) simple carbs, (b) protein, (c) activity done vs. not done.
- **🔥 Live Counter**: Always-available items (paneer bhurji, omelette, boiled eggs) that can rescue a carb-heavy meal.

## How to use

1. Open `hall3_energy_tracker.html` in any browser (Chrome/Firefox/Safari)
2. Data saves to `localStorage` — persists across sessions
3. Works offline once loaded
4. No server, no signup, no permissions needed

## Menu coverage

Includes full April 2026 Hall-3 menu:
- Daily base items (bread, sprouts, eggs, roti, rice, dal)
- All 7 days of rotating Breakfast / Lunch / Lunch Extras / Dinner / Dinner Extras
- Live counter always-available items (paneer bhurji, omelette, boiled eggs)

## Smart features

- **Energy Risk Prediction**: Real-time macro analysis. Warns if your plate is 🔴 high-carb/low-protein.
- **Smart Pick**: Suggests the best/worst dish for the current meal slot.
- **Activity Impact Chart**: Compares sleepiness on days you did post-meal activity vs. days you didn't.

## Nutrition estimates

All protein/fiber/simple carb values are approximate estimates based on standard Indian food nutrition data. They are directional, not exact.

## Built for

IIT Kanpur Hall-3 mess routine — April 2026.

## Live App

Open [`hall3_energy_tracker.html`](./hall3_energy_tracker.html) directly in your browser.
