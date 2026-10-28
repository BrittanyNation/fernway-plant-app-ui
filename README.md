# Fernway — Plant Care App UI Concept

An original mobile app UI concept for a fictional plant care companion: an overview page with CSS phone mockups of the today, plant list, and detail screens, a screens page that maps each core screen to the one question it answers (including empty, all-done, and kindly-overdue states), and a design system page with palette, type, and components.

**Live demo:** https://brittanynation.github.io/fernway-plant-app-ui/
- Overview: https://brittanynation.github.io/fernway-plant-app-ui/
- Screens: https://brittanynation.github.io/fernway-plant-app-ui/screens.html
- Design System: https://brittanynation.github.io/fernway-plant-app-ui/system.html

## Roles this supports

Built to support applications for **UI Designer**, **Front-End Designer**, **Web Designer**, and **Junior UI/UX Designer** roles — mobile app UI and front-end design work that sits between visual design and implementation.

## What it demonstrates

- **Mobile information architecture** — one question per screen: Today ("what now?"), My Plants ("how is everyone?"), Detail ("what does this one plant need?")
- **Designed states, not just screens** — empty, all-done, and overdue states written kindly, with a fact and a fix instead of a warning
- **Honest, concrete care info** — amounts in plain units ("about 2 cups"), next and last watered dates, and sample data labeled as sample data
- **Accessibility-minded choices** — health and progress always paired with words or counts, never color alone, skip link, `aria-current` navigation, a real `<table>` for the screen map, and labelled progress bars
- **A disciplined highlight color** — lemon is reserved for due-today items only, so its meaning never drifts across screens
- **Responsive layout** — phone mockups and grids step down cleanly on small screens, and the screen-map table scrolls horizontally while remaining readable
- **Semantic, framework-free build** — hand-written HTML/CSS, one stylesheet, no JavaScript required, no external images; all visuals are CSS-only

## Palette

| Token | Hex | Use |
| --- | --- | --- |
| Aubergine | `#342447` | Header, headings, phone frames, footer |
| Iris | `#7C5CBF` | Primary actions, progress, key values |
| Lilac | `#C4B5FD` | Soft accents, badges, secondary surfaces |
| Lemon | `#FDE68A` | Due-today highlights only |
| Paper | `#FAF9FF` | Page background |
| Ink | `#221C2E` | Body text |

## Contents

| Page | What it covers |
| --- | --- |
| `index.html` | Overview — hero, at-a-glance band, three CSS phone mockups (Today / My Plants / Plant Detail), design notes and palette |
| `screens.html` | Screens — screen-to-question map table, empty / all-done / overdue states, add-a-plant flow in three steps |
| `system.html` | Design System — palette table, buttons / task row / progress / type components, accessibility notes |

## Workflow note

My design workflow runs in **Sketch and Webflow**, where I design interfaces and systems visually. This demo is hand-built in HTML/CSS to show the same mobile UI thinking — one question per screen, words over alarms, and snooze without shame — expressed directly in code.

## Files

- `index.html` — overview for the concept
- `screens.html` — core screens view
- `system.html` — design system view
- `styles.css` — design tokens and all component styles
- `og-image.png` — 1200×627 social preview image in the project palette

## Note

This is an original portfolio concept created by Brittany Nation. Fernway is a fictional business; this project is not affiliated with any real plant care app. All names, prices, schedules, and figures shown are sample data, and the site is a design concept only — it does not diagnose plants or send reminders.
