# CardForge
Modern digital business card generator with live preview and standalone HTML export. 
# CardForge ✦

**A minimal, self-contained digital business card generator.**  
Fill in your info, pick a palette, export a single HTML file — no backend, no account, no install.

> Made by [Gasp-arnd](https://haunt.gg/gasp)

---

## Features

### 🪪 Identity
- First name, last name, job title, and short bio
- **Profile picture** — upload any image, displayed as a circular avatar on the card; embedded as base64 in the export so it works offline

### 🔗 Social & Contact links
Dedicated fields with **auto-detected branded icons** (SVG, inline):
- Email
- Website
- GitHub
- LinkedIn
- Twitter / X
- Instagram

### ➕ Unlimited extra links
Add as many custom links as you want (YouTube, TikTok, Dribbble, Twitch, portfolio…). The icon is automatically detected from the URL ; unknown domains get a neutral link icon.

### 🎨 30 curated color palettes
Organized in four families:
- **Dark vivid** — Midnight Lime, Blush Noir, Ocean Depth, Golden Ember, Violet Dusk, Neon Moss, Rose Carbon, Arctic Night, Copper Wire, Electric Plum
- **Dark muted** — Ash & Rust, Storm Petrel, Parchment Night, Fog Machine, Absinthe, Crimson Ink
- **Basic / neutral** — Pure Black, Pure White, Warm Gray, Cool Gray, Sepia, Chalk
- **Light** — Sage Concrete, Glacier, Cream & Ink, Blush Paper, Mint Notepad, Sunbleached, Lavender Field, Seafoam Press

Each palette defines a background, text color, and accent. Palette names appear on hover.

### ⚡ Live preview
The card updates in real time as you type — no need to click a generate button.

### 📦 Export
Two export options:
- **↓ Download Card** — saves a `.html` file to your computer
- **⌥ Copy HTML** — copies the full HTML to your clipboard

The exported file is 100% self-contained: all styles are inline, icons are embedded SVGs, and the profile picture is base64-encoded. Share it as a file, drop it on any static host, or open it directly in a browser.

### ✅ Input validation
- Email format is validated on the fly
- Website URLs are normalized (adds `https://` if missing) and validated
- Social handle inputs are smart: paste a full URL or just a username/handle — CardForge normalizes it either way for GitHub, LinkedIn, Twitter/X, and Instagram

---

## Usage

No install ndedee. Just open the file in a browser:

```bash
git clone https://github.com/gasp-arnd/cardforge.git
open cardforge.html
```

Or [download the latest release](https://github.com/gasp-arnd/cardforge/releases) and open `cardforge.html`.

---

## Stack

Pure HTML, CSS, and vanilla JavaScript. Zero build step, zero dependencies, zero frameworks.

```
cardforge.html   ← the entire app
```

---

## License

MIT, do whatever you want with it, [credit](https://haunt.gg/gasp) are appreciated.
