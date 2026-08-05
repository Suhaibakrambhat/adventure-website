<div align="center">

# 🏔️ ADVENTURE

### A cinematic, single-page landing site for travel & expedition experiences.

Built with plain HTML, CSS, and vanilla JavaScript — no frameworks, no build step. Parallax hero sections, a CSS-only image carousel, scroll-reveal animations, and a persistent dark/light theme toggle.

[Live Demo](#) · [Report a Bug](../../issues)

</div>

---

## About

**Adventure** is a single-page marketing site for a travel/expedition brand — built to show off motion-driven, editorial-style web design without relying on any frontend framework. Fixed parallax backgrounds, a shimmering gradient-text quote, glassmorphism cards, and a radio-input-powered carousel are all done in pure CSS, with a small vanilla JS layer handling theme persistence, scroll reveals, and navigation state.

---

## ✨ Features

- 🌗 **Dark / light mode** — toggled via a custom animated switch, persisted in `localStorage`
- 🎬 **Parallax hero & section backgrounds** — fixed-attachment images with gradient overlays
- ✨ **Animated gradient quote** — shimmering text effect on the hero subtitle
- 🖼️ **CSS-only image carousel** — radio-input driven "About" section slider, no JS required
- 📜 **Scroll-reveal animations** — sections fade/slide in via `IntersectionObserver`
- 🧭 **Active nav-link tracking** — highlights the current section while scrolling
- 📱 **Fully responsive** — collapsible mobile nav, stacked grids under 900px
- ⬆️ **Scroll-to-top button** — appears after scrolling past the hero
- 📬 **Contact section** — styled form (name, email, country, message) + direct contact info cards

---

## 🛠️ Tech Stack

| | |
|---|---|
| Markup | HTML5 |
| Styling | CSS3 — custom properties, `backdrop-filter`, CSS Grid/Flexbox, keyframe animations |
| Interactivity | Vanilla JavaScript (no framework, no dependencies) |
| Icons | [Font Awesome 4.7](https://fontawesome.com/) |
| Fonts | [Bebas Neue](https://fonts.google.com/specimen/Bebas+Neue), [Cormorant Garamond](https://fonts.google.com/specimen/Cormorant+Garamond), [DM Sans](https://fonts.google.com/specimen/DM+Sans), [Rubik Dirt](https://fonts.google.com/specimen/Rubik+Dirt) — loaded via Google Fonts |
| Images | [Unsplash](https://unsplash.com/) (hero, events, tours, about sections) |

No build tools, no package manager, no framework — it's a single static HTML file that runs anywhere.

---

## 📄 Sections

| Section | Description |
|---|---|
| **Home** | Full-screen parallax hero with animated quote and headline |
| **Events** | Card grid of upcoming expeditions (Everest Base Camp, Walking Holidays, Andaman Beaches) |
| **Explore** | Full-bleed parallax banner with a travel quote |
| **Tours** | Upcoming tour dates alongside an image gallery |
| **About** | Parallax section with a CSS-only rotating image carousel |
| **Contact** | Contact form + direct email/phone/location cards |

---

## 📸 Screenshot

<div align="center">
<img src="./assets/screenshot-home.png" alt="Adventure homepage" width="80%"/>
</div>

> Add a screenshot to an `/assets` folder and update the path above.

---

## 🚀 Getting Started

No installation required — it's a static HTML file.

1. **Clone the repository**
   ```bash
   git clone https://github.com/Suhaibakrambhat/adventure.git
   cd adventure
   ```

2. **Open it directly**
   ```bash
   open index.html      # macOS
   start index.html     # Windows
   ```

   Or serve it locally (recommended, avoids any `file://` restrictions):
   ```bash
   npx serve .
   # or
   python3 -m http.server 5500
   ```

3. Visit `http://localhost:5500` (or whichever port your server prints).

---

## 📁 Project Structure

```
adventure/
└── index.html      # Single-file site — HTML, CSS, and JS all inline
```

> If you split styles/scripts into separate files later, update this section (e.g. `/css/style.css`, `/js/main.js`).

---

## 🎨 Customization

Key design tokens live in `:root` at the top of the `<style>` block:

```css
--pink:     #fc036b;   /* primary accent */
--pink-dim: #a50046;
--white:    #f5f0eb;
--charcoal: #111111;   /* dark theme background */
```

Swap these to re-theme the entire site — every component references these variables rather than hardcoded colors.

---

## Roadmap

- [ ] Replace Unsplash placeholder images with licensed/owned photography
- [ ] Wire the contact form to a real backend or form service (e.g. Formspree)
- [ ] Split inline CSS/JS into separate files for maintainability
- [ ] Add real event/tour data instead of static placeholder content

---

## Author

**Mumin Bhat**
- GitHub: [@Suhaibakrambhat](https://github.com/Suhaibakrambhat)
- LinkedIn: [bhat-mumin](https://linkedin.com/in/bhat-mumin-796a39284)

---

## License

Distributed under the MIT License. See `LICENSE` for details.
