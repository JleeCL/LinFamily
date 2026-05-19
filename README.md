# LinFamily

A lightweight mobile-first family meal tracker.

## Run

Open `index.html` in a browser.

## Features

- Dynamic family member list (add/remove)
- Optional avatar URL per member
- Daily lunch/dinner status tracking with one-tap toggles
- Default state is coming (`✅`) for both meals
- Automatic weekday/weekend label
- Instant local auto-save in `localStorage`
- WhatsApp trigger when a meal is set to not coming (`❌`)

- To override the default WhatsApp recipient, set `localStorage.linfamily_whatsapp_number` to digits-only international number.
  - Example: `localStorage.setItem('linfamily_whatsapp_number', '6597299918')`
