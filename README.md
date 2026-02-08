# .ac (anmolcreations)

> A space where my skills evolve into ideas and creations.

This repository serves as the central brand hub for **anmolcreations (.ac)**. It acts as a gateway to various digital services, design studios, and utility projects.

## 🚀 About

**Project AC** represents a digital identity focused on:

- **Online Digital Solutions:** Essential services for banking, government, and business needs.
- **Design Studio:** Branding, logo design, and creative visuals.
- **Innovation:** Experimental projects like PromtoEngine (AI) and UT.ac (Utilities).

The design philosophy emphasizes "depth" in the hero section and "surface-level" clarity for content cards, utilizing a "Dots & Motion" animation concept.

## ✨ Features

- **Interactive Hero Section:** A custom canvas-based "Dots & Motion" animation with a sequenced reveal.
- **Theme System:** Native Light/Dark mode toggle with persistent state.
- **Modular Architecture:** The Hero component is isolated (`/hero/`) for portability.
- **Responsive Design:** Optimized for all device sizes without framework dependencies.
- **No Dependencies:** Built entirely with **Vanilla HTML, CSS, and JavaScript**.

## 🛠️ Tech Stack

- **HTML5** - Semantic structure.
- **CSS3** - Custom properties (variables), Flexbox/Grid, and responsive media queries.
- **JavaScript (ES6+)** - DOM manipulation, Canvas API, and event handling.
- **Lucide Icons** - Lightweight, consistent iconography.

## 📂 Project Structure

```text
.
├── css/                # Global styles
│   ├── style.css       # Main stylesheet
│   └── solutions.css   # Styles for solutions page
├── hero/               # Isolated Hero Component
│   ├── hero.css        # Hero-specific styles
│   ├── hero.js         # Canvas animation logic
│   └── hero.html       # Component structure reference
├── js/                 # Global scripts
│   ├── main.js         # UI logic (theme, nav)
│   └── solutions.js    # Solutions page logic
├── index.html          # Main landing page
├── solutions.html      # Detailed solutions page
└── README.md           # Project documentation
```

## ⚡ Setup & Usage

Since this is a static site, no build process is required.

1.  **Clone the repository:**
    ```bash
    git clone https://github.com/anmol-creation/ac.git
    ```
2.  **Open in Browser:**
    Simply open `index.html` in your preferred web browser.

    *Or use a local server for a better experience:*
    ```bash
    # using python
    python3 -m http.server
    # using live-server extension
    live-server .
    ```

## 🎨 Design Guidelines

- **Colors:** Muted palette (Soft Blue, Pink/Purple, Cyan/Teal, Soft Green/Yellow) on a dark/light base.
- **Typography:** 'Inter' font family.
- **UI Elements:** Accordion-style layouts (no popups), glassy header effects, and outline-style icons.

## 📄 License

All rights reserved © 2024 anmolcreations.
