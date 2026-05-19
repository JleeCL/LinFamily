# LinFamily

A lightweight mobile-first family meal tracker.

## Run

Open `index.html` in a browser.

## GitHub Pages (public link)

After this repository enables GitHub Pages with **Build and deployment source = GitHub Actions**, pushes to `main` will deploy this static app.

Typical hosted URL format:

`https://<owner>.github.io/<repository>/`

For this repository, that is typically:

`https://jleecl.github.io/LinFamily/`

## Features

- Dynamic family member list (add/remove)
- Optional avatar URL per member
- Daily lunch/dinner status tracking with one-tap toggles
- Default state is coming (`✅`) for both meals
- Automatic weekday/weekend label
- Instant local auto-save in `localStorage`
- WhatsApp trigger when a meal is set to not coming (`❌`)

- To override the default WhatsApp recipient, set `localStorage.linfamily_whatsapp_number` to a digits-only international number.
  - Example: `localStorage.setItem('linfamily_whatsapp_number', '6597299918')`
