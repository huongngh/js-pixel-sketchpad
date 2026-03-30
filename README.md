# Pixel sketchpad

A browser-based pixel drawing pad built with vanilla JavaScript, HTML, and CSS. Hover over the grid to paint cells — adjust grid size on the fly without refreshing the page.

## Live Demo

<img width="501" height="542" alt="Screenshot 2026-03-30 at 14 55 47" src="https://github.com/user-attachments/assets/035df973-a49d-4e22-8061-8b721429fcc4" />


## Features

- Dynamic grid generation — set any grid size (e.g. 16×16, 32×32, 64×64) via prompt
- Hover-to-draw interaction using `mouseover` events
- Grid resets cleanly when a new size is chosen
- Lightweight — no libraries or frameworks

## Tech Stack

| Layer | Technology |
|-------|-----------|
| Structure | HTML5 |
| Styling | CSS3 (Flexbox grid layout) |
| Logic | Vanilla JavaScript (ES6) |

## Getting Started

```bash
git clone https://github.com/huongngh/js-pixel-sketchpad.git
cd js-pixel-sketchpad
open index.html
```

No build step required — open `index.html` directly in any modern browser.

## Project Structure

```
js-pixel-sketchpad/
├── index.html   # Page layout and grid container
├── style.css    # Grid and cell styling
└── script.js    # Dynamic grid creation, hover events, reset logic
```

## What I Learned

- Dynamically creating and removing DOM elements with JavaScript
- Using CSS Flexbox to build a self-sizing pixel grid
- Handling mouse events (`mouseover`) to implement hover-based drawing
- Writing reusable functions to regenerate the grid on demand without a page reload
