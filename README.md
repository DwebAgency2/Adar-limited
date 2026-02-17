# Adar Limited - Landing Page

Welcome to the official repository for the **Adar Limited** landing page. This project is a high-performance, responsive single-page website designed to capture leads for the Q2 Mastery Pod and promote Adar Limited's core services.

##  Overview

This website serves as the digital front door for Adar Limited, focusing on:
- **Brand Authority**: Establishing credibility in the AI literacy and career development space.
- **Lead Generation**: Capturing email sign-ups for the Mastery Pod waitlist.
- **Service Showcase**: Highlighting B2C programs, B2B partnerships, and corporate speaking engagements.

##  Tech Stack

- **Core**: Semantic HTML5
- **Styling**: Vanilla CSS3 (Custom Variables, Flexbox, CSS Grid)
- **Interactivity**: Vanilla JavaScript (ES6+)
- **Font**: Google Fonts (Barlow Condensed, Barlow, DM Mono)
- **Icons**: SVG Icons (Lucide / Feather style)

##  Project Structure

```
/
├── images/               # High-resolution assets
│   ├── photo-1.jpg       # Legacy Tour section image
│   ├── photo-2.jpg       # Why section image
│   └── ...
├── logo/                 # Brand assets
│   └── Adar_Logo_plain.png
├── index.html            # Main entry point
└── README.md             # Project documentation
```

##  Quick Start

1.  **Clone the repository** (if applicable) or download the source files.
2.  **Open `index.html`** in any modern web browser to view the site.
3.  No build step or package manager is required. This is a static site optimized for speed and simplicity.

##  Customization Guide

### Changing Images
Replace files in the `images/` directory. Ensure new images retain the same filenames (`photo-1.jpg`, `photo-2.jpg`, etc.) to avoid breaking links, or update the `src` attributes in `index.html`.

### Updating Content
All text content is directly editable within `index.html`. Look for the relevant section comments (e.g., `<!-- HERO SECTION -->`, `<!-- PROGRAMS SECTION -->`) to locate specific text blocks.

### modifying Colors
The color palette is defined in the `:root` block at the top of the `<style>` section in `index.html`:

```css
:root {
    --color-red: #D22B2B;        /* Primary Brand Color */
    --color-bg-black: #0E0E0E;   /* Background */
    /* ... */
}
```

##  License

© 2025 Adar Limited. All rights reserved.
Registered in Nigeria · RC 6896461
