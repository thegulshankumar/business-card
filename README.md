# 🪪 Business Card

**A clean, responsive digital business card built with pure HTML & CSS**

🌐 **Live Demo:** [card.gulshankumar.com](https://card.gulshankumar.com)

[![W3C Validation](https://img.shields.io/badge/W3C-HTML5%20Valid-brightgreen?style=flat-square&logo=w3c&logoColor=white)](https://validator.w3.org/)
[![CSS Valid](https://img.shields.io/badge/W3C-CSS3%20Valid-blue?style=flat-square&logo=css3&logoColor=white)](https://jigsaw.w3.org/css-validator/)
[![License: GPL v3](https://img.shields.io/badge/License-GPLv3-blue?style=flat-square)](LICENSE)
[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/CSS)
[![No JavaScript](https://img.shields.io/badge/JavaScript-None%20Required-lightgrey?style=flat-square&logo=javascript)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)

---

## Overview

A minimal digital business card built with HTML5 and CSS3.

> 🎯 **Goal:** Showcase frontend fundamentals in one self-contained component.
> 🧱 CSS box model, responsive design, and visual polish.

---

## Preview

<img src="preview.png" alt="Business Card Preview" width="100%" style="border-radius: 12px;" />

---

## Features

- ⚡ No frameworks, build tools, or JavaScript
- ✅ Passes official W3C HTML5 & CSS3 validators
- 📱 Fully responsive across all screen sizes
- 🖼️ Gravatar integration for dynamic avatars
- 🎨 Smooth hover states on interactive elements

---

## Project Structure

```
business-card/
├── index.html        # HTML5 markup
├── styles.css        # Layout, colors, typography
├── preview.png       # Screenshot for README
└── README.md         # You're here!
```

---

## Getting Started

No installation or build step needed.

```bash
git clone https://github.com/your-username/business-card.git
cd business-card
open index.html
```

Or drag `index.html` directly into any browser tab.

---

## Customisation

All personal details live inside `index.html`:

| Field       | Location               | Example                      |
|-------------|------------------------|------------------------------|
| Name        | `.full-name` `<p>`     | `Gulshan Kumar`              |
| Designation | `.designation` `<p>`  | `WordPress Plugin Developer` |
| Company     | `.company` `<p>`       | `Forget Spam Comment`        |
| Email       | `<p>` in card body     | `admin@example.com`          |
| Phone       | `<p>` in card body     | `(+91) 8XYZ-XY-8XYZ`        |
| Portfolio   | `.portfolio-link` `<a>`| `http://example.com`         |
| Avatar      | `<img src="">`         | Gravatar URL or local path   |
| Social links| `.social-media` `<a>`  | Twitter, LinkedIn, GitHub    |

To change the accent colour, update `.business-card` in `styles.css`:

```css
.business-card {
    border: 4px solid #6366f1; /* ← change this */
}
```

---

## Validation

| Validator | Status |
|-----------|--------|
| [W3C HTML Validator](https://validator.w3.org/) | ✅ No errors |
| [W3C CSS Validator](https://jigsaw.w3.org/css-validator/) | ✅ No errors |

---

## License

Released under the GNU Public License. Fork, modify, and adapt freely.

---

Made with ❤️ and plain HTML & CSS · ⭐ Star if it helped!
