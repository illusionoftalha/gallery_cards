# Gallery Cards

> An interactive 3D card carousel showcasing Pakistani cities — draggable, scrollable, and touch-friendly, built with pure HTML, CSS, and vanilla JS.

---

## Overview

A visually striking gallery built as a single HTML file. Cards are arranged in a 3D perspective carousel that responds to mouse drag, scroll wheel, and touch swipe. Each card features a city name, number, and full-bleed photo. Showcases 10 cities across Pakistan.

---

## Features

- Smooth 3D card carousel with depth/z-index stacking
- Mouse drag to navigate
- Scroll wheel support
- Touch / swipe support for mobile
- Click any card to jump to it
- Custom animated dual cursor
- Zero dependencies — pure vanilla JS

---

## Cities Featured

| # | City |
|---|------|
| 01 | Karachi |
| 02 | Lahore |
| 03 | Islamabad |
| 04 | Faisalabad |
| 05 | Gilgit Baltistan |
| 06 | Kashmir |
| 07 | Peshawar |
| 08 | Quetta |
| 09 | Hyderabad |
| 10 | Multan |

---

## Tech Stack

- HTML5
- CSS3 (custom properties for 3D transforms)
- Vanilla JavaScript — no frameworks, no libraries

---

## Getting Started

No build step. Just open in a browser:

```bash
git clone https://github.com/illusionoftalha/gallery_cards.git
cd gallery_cards
# open gallery.html in your browser
```

---

## Project Structure

```
gallery_cards/
├── gallery.html   # Carousel markup + all JS logic
└── cards.css      # 3D card styles, cursor, layout
```

---

## Customization

To add or replace a card, copy an existing `.carousel-item` block in `gallery.html` and update the title, number, and `src`:

```html
<div class="carousel-item">
  <div class="carousel-box">
    <div class="title">Your City</div>
    <div class="num">11</div>
    <img src="your-image-url.jpg" />
  </div>
</div>
```

---

## License

© 2026 Sheikh Muhammad Talha Bin Khalid. All Rights Reserved.
