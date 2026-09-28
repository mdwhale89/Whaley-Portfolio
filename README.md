# TookStarz Designs — Personal Portfolio & Creative Archive

[![Live Demo](https://img.shields.io/badge/Live-Demo-00F0FF?style=for-the-badge&logo=githubpages&logoColor=black)](https://mdwhale89.github.io/Whaley-Portfolio/)
[![Built With](https://img.shields.io/badge/Stack-HTML5%20%7C%20CSS3-7B5CFA?style=for-the-badge)](https://developer.mozilla.org/en-US/docs/Web/CSS)
[![Author](https://img.shields.io/badge/Creator-Mel%20Whaley-F6D365?style=for-the-badge)](https://www.linkedin.com/in/mel-whaley-31b588372/)

Welcome to the official repository for **TookStarz Designs**, a space-themed, multi-disciplinary portfolio website showcasing fine arts foundations, technical animation, commercial direct-to-film (DTF) fabrication, and high-contrast photography.

---

## ✦ Core Design & Architecture

The site is built with pure, semantic **HTML5** and **vanilla CSS3**, intentionally omitting heavy JavaScript frameworks to maximize load speeds, SEO performance, and responsive reliability.

### Key Technical Features:
* **Persistent Obsidian Nebula:** Viewport-pinned rotating radial color mesh (`rotateNebula`) and two-tier twinkling CSS starfields that persist seamlessly across page scrolling.
* **Zero-JS CSS Slide Galleries:** Horizontal carousel navigation built with CSS Scroll Snap (`scroll-snap-type: x mandatory`), utilizing anchor targets and celestial star buttons (`✦`) with smooth transitions.
* **Fluid Media & Video Support:** Mobile-first responsive video embeds (`56.25%` aspect ratio) and URL-encoded asset paths for consistent cross-browser and GitHub Pages asset resolution.
* **Accessibility & Performance:** Native support for `prefers-reduced-motion: reduce`, custom browser scrollbars, and tactile touch targets for mobile devices.

---

## ✦ Site Map & Disciplines

| Page | Filename | Key Highlights & Studies |
| :--- | :--- | :--- |
| **Home** | `index.html` | Mission control, competency badges, and 2x2 interactive discipline portals. |
| **About** | `about.html` | Multidisciplinary pipeline statement, brand logo, identity tags, and social/professional portals. |
| **Animation** | `animation.html` | ASL rotoscoping kinematic study & 5-slide modular video gallery for *"Mother Doesn't Want a Dog"*. |
| **Digital to Film** | `digital-to-film.html` | Industrial RIP software calibration, white underbase density, rasterization, and heat press fabrication. |
| **Fine Arts** | `fine-art.html` | 24"×36" Chernobog / *View of Toledo* graphite chiaroscuro study & cool/warm pointillist optical color mixing. |
| **Photography** | `photography.html` | Environmental self-portraiture (tenebrism), candid street documentary (B&W), and arboreal psychology. |
| **Contact** | `contact.html` | Client commission transmission terminal and direct contact channels. |

---

## ✦ Color System

```css
:root {
  --primary-color:      #7B5CFA; /* Deep Nebula Violet - buttons, active borders */
  --secondary-color:    #12183A; /* Midnight Surface - cards, navigation panels */
  --secondary-border:   #2E3875; /* Container borders */
  --text-color:         #F6D365; /* Warm Celestial Gold - body text */
  --text-heading:       #FFE8A3; /* Bright Starlight Gold - headings */
  --text-muted:         #B3B9D6; /* Stardust Silver - captions, metadata */
  --link-color:         #00F0FF; /* Pulsar Cyan - interactive links */
  --link-hover-color:   #FF5E8E; /* Supernova Pink - hover states */
  --nebula-void:        #010208; /* Deep Space Void - background base */
}