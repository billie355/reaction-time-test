# Reaction Time Test

Minimalist, animated **Reaction Time Test** in white/grey themes. Mobile-friendly, with stats and history bars. Includes **unit toggle** (milliseconds ↔ seconds).

![Banner](assets/banner.png)

## ✨ Features
- White/Grey theme toggle (animated)
- Large tappable pad with states: *Idle → Waiting → Tap Now*
- False start detection
- Stats: Last, Best, Average, Tries
- History bars with labels
- **Unit toggle**: `ms` or `s`
- Keyboard: Space / Enter

## 🚀 Demo
Open the single-file HTML locally:

```bash
# save the file
reaction-time.html
# then double-click to open in your browser
```

Or deploy via GitHub Pages.

## 📁 Project Structure
```
.
├── assets/
│   └── banner.png
└── reaction-time.html
```

## 🧩 Usage
1. Copy the HTML from your app (see `reaction-time.html`).
2. Open in Chrome/Edge/Safari.
3. Click **Start**, hintayin ang **NOW**, tap agad.
4. Use the **Theme** and **Unit** toggles.

## 🌐 Deploy to GitHub Pages
1. Create a new repo (e.g., `reaction-time-test` or `reactime`).
2. Add your `reaction-time.html` and this `README.md`.
3. Commit & push.
4. In **Settings → Pages**, set Source to `main` and folder to `/root`.
5. Visit `https://<username>.github.io/<repo>/reaction-time.html`.

## 🛠 Customization
- Change default unit: set `state.unit = 's'` on init.
- Adjust random delay: tweak `randomDelay()`.
- Increase history size: change `maxShown` in `updateStats()`.

## 📄 License
MIT

---
Built for Billy Joe Sablayan • White/Grey minimalist UI
