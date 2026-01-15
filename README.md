# Burnout-Meter
Mobile-first burnout tracker exploring how balance, stress, and recovery interact over time using simple interactions and visual feedback.
This project uses simple taps and press-and-hold interactions to log stressors and balancers, then visualizes how those patterns affect burnout. The goal isn’t productivity tracking — it’s awareness.

---

## Why this exists

Burnout usually isn’t caused by one big thing.  
It’s caused by small pressures stacking up while recovery gets ignored.

This experiment treats burnout like a signal:
- Stress and recovery are always happening
- Short imbalance is okay
- Long imbalance is what causes problems

By interacting with the app throughout the day, you can start to see which inputs dominate and which behaviors actually help restore balance.

---

## How it works

### Interactions
- **Tap** a category to log a quick moment of stress or recovery
- **Press & hold** to represent prolonged pressure or intentional recovery
- **Idle time** allows the system to naturally rebalance

Each interaction records:
- Tap count per category
- Total hold time per category (seconds)

---

## Results (V2)

The Results view summarizes your session with:
- Total stress vs recovery interactions
- Bar charts for:
  - Tap counts
  - Hold duration
- Simple insights like your most frequent stressor or balancer

Data is stored locally in the browser using `localStorage`, so patterns persist across sessions.

---

## Design goals

- Mobile-first and touch-friendly
- No external assets or build tools
- Single HTML file
- Calm, minimal visuals
- Clear metaphors over complex UI

This is intentionally lightweight and approachable.

---

## Tech stack

- **p5.js** (creative coding + rendering)
- Vanilla HTML / CSS / JavaScript
- No frameworks
- No backend
- No dependencies beyond p5

---

## Live demo

👉 https://burnout-meter.netlify.app/

---

## What’s next (ideas)

- Multi-day summaries
- Exporting data (JSON / CSV)
- Gentle insights or nudges
- Custom categories
- Accessibility improvements

---

## Notes

This project is an experiment — not a medical tool or productivity tracker.

If it sparks reflection or awareness, it’s doing its job.
