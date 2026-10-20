<div align="center">

# Microsoft AI Club — Website

### Innovate · Analyze · Connect

[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)](https://developer.mozilla.org/docs/Web/HTML)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white)](https://developer.mozilla.org/docs/Web/CSS)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)](https://developer.mozilla.org/docs/Web/JavaScript)
[![Vercel](https://img.shields.io/badge/Deployed-Vercel-000000?style=flat-square&logo=vercel&logoColor=white)](https://club-seven-sigma.vercel.app)
[![License](https://img.shields.io/badge/License-Open_to_use-green?style=flat-square)](#license)

**[🔗 Live Site](https://club-seven-sigma.vercel.app)**

</div>

---

## 📖 About

The official website of the **Microsoft AI Club** — a student-led community from the **Department of Artificial Intelligence & Data Science** exploring Artificial Intelligence, Data Science, and Microsoft technologies.

This is a **hand-crafted static site**: pure HTML5, CSS3, and vanilla JavaScript — no frameworks, no build step, no dependencies to install. Open it, and it runs.

## ✨ Features

**🧭 Sections**
Home · About · Vision · Objectives · Events · Gallery · Team · Contact

**🎬 Interactive polish**
- **Animated preloader** with live percentage counter
- **Dark / light theme toggle** with a view-transition ripple animation — no white flash on load (theme is applied before first paint via an inline script and persisted in `localStorage`)
- **Custom cursor** — smooth SVG pointer that follows the mouse
- **Neural-network canvas** background animation in the hero
- **Photo gallery with lightbox** — captions, category tags, and prev/next counter
- **Team roster modal** — 9 leadership members with an animated spark canvas
- **Announcement ribbon** for club-wide notices
- **Scroll-reveal animations** and hover effects on event cards
- **Responsive navigation** with an animated pill slider and mobile hamburger menu
- **Validated contact form**

**♿ Accessible & fast**
- `prefers-reduced-motion` respected throughout
- Semantic markup, keyboard-friendly navigation
- Static hosting — loads instantly on any CDN

## 📁 File Structure

```
Club-Site/
├── index.html          # Single-page site (all sections)
├── css/
│   └── styles.css      # Full styling, themes, animations
├── js/
│   └── script.js       # Theme, cursor, canvas, lightbox, nav logic
├── images/             # Club logo, event photos, leadership portraits
│   └── leadership/     # Team member photos
├── favicon.ico
└── README.md
```

## 🚀 Getting Started

No install, no build — it's static.

```bash
# 1. Clone the repo
git clone https://github.com/princekumar-dev/Club-Site.git
cd Club-Site

# 2. Open it
#    Either just double-click index.html,
#    or serve it locally (recommended, avoids file:// quirks):
npx serve .
```

Then visit `http://localhost:3000`.

## 🎨 Customization

| What | Where |
|------|-------|
| Club text, events, team members | `index.html` |
| Colors & theme variables | `css/styles.css` (search for the gradient hex values) |
| Animations & interactions | `js/script.js` |
| Images (logo, events, team) | `images/` |

- **Primary gradient:** `#6a11cb` → `#2575fc` (purple → blue)
- **Secondary gradient:** `#11998e` → `#38ef7d` (teal → green)
- **Theme tokens:** `data-theme="dark"` / `data-theme="light"` on `<html>`

## ▲ Deployment

Live at **[club-seven-sigma.vercel.app](https://club-seven-sigma.vercel.app)** via **Vercel**.

To deploy your own copy: push to GitHub → import the repo on [vercel.com](https://vercel.com) → done (framework auto-detected as *Other*, zero config). Netlify, GitHub Pages, or any static host works the same way.

## 🌍 Browser Support

Chrome · Firefox · Safari · Edge — desktop & mobile. Graceful degradation in older browsers.

## 📄 License

Free to use and modify for your club or personal projects.

## 🙏 Credits

- **Icons:** [Font Awesome 6](https://fontawesome.com)
- **Club identity:** Microsoft AI Club, Department of AI & Data Science

---

<div align="center">

Built with ❤️ by the **Microsoft AI Club** team

</div>
