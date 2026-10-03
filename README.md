# Developer & Designer Portfolio

> A responsive, single-page personal portfolio website built with semantic HTML5 and modern CSS3, designed to showcase web development and UI/UX design skills.

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)
[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/CSS)
[![Responsive Design](https://img.shields.io/badge/Design-Responsive-success)](https://web.dev/responsive-web-design-basics/)

---

## Table of Contents

- [Overview](#overview)
- [Key Features](#key-features)
- [HTML & CSS Skills Demonstrated](#html--css-skills-demonstrated)
- [Project Architecture](#project-architecture)
- [Responsive Breakpoints](#responsive-breakpoints)
- [Getting Started](#getting-started)
- [Live Demo / Preview](#live-demo--preview)
- [Author & License](#author--license)

---

## Overview

This project is a personal portfolio web page highlighting the creator's technical proficiency in front-end development and visual design. It provides a clean, engaging interface with high-contrast color palettes, smooth navigation, and a modern card-based layout.

---

## Key Features

- **Hero Header Section**: High-impact banner with slogan overlay and integrated social media links.
- **Sticky Top Navigation**: Smooth scrolling navigation anchored across all major page sections.
- **About Me Section**: Biography presentation with circular profile image and typography hierarchy.
- **Skills Grid**: Responsive grid displaying technical and design competencies with interactive hover effects.
- **Featured Projects**: Card-based project showcase with translucent glassmorphic backdrop styling.
- **Contact Info & Map**: Accessible contact details alongside an embedded studio location graphic.
- **Mobile-First Responsiveness**: Fluid layouts adapting seamlessly across mobile, tablet, and desktop screens.

---

## HTML & CSS Skills Demonstrated

### 1. Semantic HTML5 Markup
- Structured with `<header>`, `<nav>`, `<section>`, `<main>`, and `<footer>` elements for enhanced accessibility (a11y) and SEO.
- Explicit `aria-label` tags on icon-based social links.
- Responsive image tags with appropriate `alt` attributes.

### 2. Modern CSS3 Architecture
- **CSS Custom Properties (Variables)**: Centralized design tokens for colors, typography, shadows, and transitions (`:root`).
- **Flexbox Layout**: Dynamic alignment in the header, navigation, and contact sections.
- **CSS Grid**: Responsive multi-column grid layouts for Skills and Projects with `repeat(auto-fit, minmax(...))`.
- **Fluid Typography**: Responsive font sizing utilizing `clamp()`.
- **Glassmorphism & Gradients**: Subtle background blur (`backdrop-filter`) and multi-stop linear gradients.
- **Transitions & Transforms**: Interactive hover states with elevation changes (`translateY`) and smooth cubic-bezier easing.

---

## Project Architecture

```plaintext
html_assignment_1/
├── assets/
│   └── images/
│       ├── bioPic.png                 # Profile portrait
│       ├── dragonbit_social_icon.png  # Social platform icon
│       ├── headerBkg.png              # Hero header background image
│       ├── linkedin_social_icon.png   # LinkedIn profile icon
│       ├── logo.png                   # Brand mark / logo
│       ├── map.png                    # Location map graphic
│       ├── skillsBkg.png              # Background pattern for skills section
│       └── twitter_social_icon.png    # Twitter/X profile icon
├── css/
│   └── app.css                        # Modern responsive CSS stylesheet
├── .gitignore                         # Git exclusion rules
├── index.html                         # Single-page portfolio HTML document
├── LICENSE                            # MIT Open Source License
└── README.md                          # Project documentation
```

---

## Responsive Breakpoints

| Device Category | Viewport Range | Key Adjustments |
| :--- | :--- | :--- |
| **Desktop** | `> 900px` | Side-by-side flex layouts, multi-column grid (3-4 columns) |
| **Tablet** | `641px - 900px` | 2-column grids, stacked about & contact sections |
| **Mobile** | `<= 640px` | Single-column cards, fluid navigation wrap, compact padding |

---

## Getting Started

### Prerequisites
A modern web browser (Google Chrome, Mozilla Firefox, Safari, or Microsoft Edge).

### Installation & Local Setup
1. Clone or download the repository:
   ```bash
   git clone https://github.com/<username>/html_assignment_1.git
   cd html_assignment_1
   ```
2. Open `index.html` in your web browser:
   - On macOS: `open index.html`
   - On Windows: `start index.html`
   - On Linux: `xdg-open index.html`
   - Or use VS Code Live Server extension.

---

## Author & License

- **Author**: Sheikh Naim
- **License**: Released under the [MIT License](LICENSE).
