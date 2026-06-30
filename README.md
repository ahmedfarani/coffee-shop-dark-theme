<div align="center">

# ☕ Cold Brew - Coffee Shop Landing Page

**A responsive, animated dark-themed hero page for a coffee brand, built with Vanilla JS and AOS scroll animations.**

![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black)
![AOS](https://img.shields.io/badge/AOS-Animate%20On%20Scroll-orange)

</div>

---

## 📖 Overview

A single-page, fully responsive **landing page hero section** for a fictional Cold Brew coffee brand. The page combines a dark theme, custom typography, scroll-triggered entrance animations, and a working mobile navigation toggle — all without any front-end framework.

## ✨ Features

- **Scroll-triggered animations** | every hero element (title, paragraph, CTA, image, social icons) animates in using the [AOS](https://michalsnik.github.io/aos/) library with staggered delays
- **Responsive navigation bar** | logo, nav links, "Sign In" button, and a hamburger icon that toggles an open/close state in JavaScript
- **Functional mobile menu** | `script.js` toggles the `.open` class on the nav list and switches the menu icon to a close (✕) icon via Boxicons
- **8-tier responsive design** | fine-grained `@media` breakpoints from `1770px` down to `440px` for smooth scaling across all screen sizes
- **Social + scroll-down indicators** | animated icon row (Facebook, YouTube, Twitter) and an animated "Scroll Down" prompt

## 🛠️ Tech Stack

- **HTML5 / CSS3** | semantic layout with custom responsive breakpoints
- **JavaScript (Vanilla)** | mobile menu toggle logic
- **[AOS (Animate On Scroll)](https://michalsnik.github.io/aos/)** | scroll-reveal animation library (via CDN)
- **[Boxicons](https://boxicons.com/)** | menu and UI icons
- **[Remix Icon](https://remixicon.com/)** | social and scroll-indicator icons
- **Google Fonts (Roboto)** | primary typeface

## 🚀 Getting Started

```bash
git clone https://github.com/ahmedfarani/coffee-shop-dark-theme.git
cd coffee-shop-dark-theme
```

Open `index.html` directly in a browser. All dependencies (AOS, Boxicons, Remix Icon, Google Fonts) load from public CDNs, so an internet connection is required for full styling and animation.

## 📁 Project Structure

```
coffee-shop-dark-theme/
├── index.html       # Header, hero section, social icons, scroll indicator
├── style.css         # Theme, layout, and 8-breakpoint responsive design
├── script.js          # Mobile menu open/close toggle
└── img/
    ├── logo.png
    ├── hero.png
    └── bg.png
```

## 📜 License

This project is open source and available for personal or educational use.

---

<div align="center">

Built by **Ahmed Farani**

</div>
