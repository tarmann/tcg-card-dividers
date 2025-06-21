# Card Divider Generator

A simple web-based tool to generate printable card dividers for organizing trading card game (TCG) collections.

## 🧩 Features

- Accepts a list of divider names (e.g., One Piece TCG set names)
- Automatically generates printable **A4 landscape pages**
- Each page includes **4 dividers laid out side by side**
- Each divider:
  - Measures **7cm width × 19.4cm height**
  - Includes a **fold line at 9.7cm**
  - Displays the name **below the fold**, centered
- Optimized for print: only the dividers are visible when printing
- Includes:
  - A `textarea` for name input (one per line)
  - A “Generate Dividers” button
  - A “Print” button

## 🛠️ Technologies

- **HTML** for structure
- **CSS** for layout, sizing, print rules, and fold line rendering
- **JavaScript** for rendering the dividers using template literals

## 🖨️ Print Layout

- Uses `@media print` to hide all UI except the dividers
- Uses Flexbox with wrapping to ensure dividers are laid out in horizontal rows
- Ensures each A4 page contains **exactly 4 dividers**

## 💡 Use Case

Designed for players and collectors of games like the One Piece TCG to neatly organize physical cards by set, type, or theme.

## 📎 Example Input

OP01 - Romance Dawn
OP02 - Paramount War
OP03 - Pillars of Strength
OP04 - Kingdoms of Intrigue
OP05 - Awakening of the New Era
OP06 - Wings of the Captain
OP07 - 500 Years in the Future
OP08 - Two Legends