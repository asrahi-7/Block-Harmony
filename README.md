# Block Harmony 🧩

A sleek, dark-themed 10x10 block puzzle game built entirely with vanilla web technologies. Drop blocks, clear lines, and find your flow.

Whether you're playing on a desktop or swiping on your phone, Block Harmony offers a smooth, responsive puzzle experience with satisfying animations and combo multipliers.

 *(Note: Add a screenshot of your game here)*

## ✨ Features

* **Classic 10x10 Gameplay:** Strategically place randomly generated block shapes onto the grid.
* **Combo System:** Clear multiple rows or columns simultaneously to trigger combo multipliers and earn massive bonus points.
* **Smart Drag-and-Drop:** Features a dynamic "ghost" preview that shows exactly where your block will land—and turns red if the placement is invalid.
* **Satisfying Visuals:** Custom CSS animations for block placements and HTML5 Canvas-powered particle explosions when lines are cleared.
* **Persistent High Scores:** Your highest score is automatically saved locally in your browser.
* **Fully Responsive:** Touch-action optimized for flawless gameplay on mobile devices and tablets.
* **Zero Dependencies:** 100% pure HTML, CSS, and Vanilla JavaScript. No frameworks, no build tools, no bloated libraries.

## 🎮 How to Play

1. **Drag** a block from the bottom tray onto the 10x10 grid.
2. **Clear lines** by filling a complete row or column.
3. **Trigger Combos** by clearing multiple lines at once.
4. **Restock:** New blocks will appear only after you have placed all three blocks from the current tray.
5. **Survive:** The game ends when none of the remaining blocks can fit anywhere on the grid. Plan ahead!

## 🚀 How to Run Locally

Because this project uses vanilla web technologies, running it is as simple as opening a file.

1. Clone the repository:
```bash
git clone https://github.com/asrahi-7/Block-Harmony.git

```


2. Navigate to the project directory.
3. Double-click `index.html` to open it in your default web browser.

*(Alternatively, you can host it instantly using GitHub Pages!)*

## 🛠️ Technical Stack

* **HTML5:** Semantic structure and Canvas API for particle effects.
* **CSS3:** Flexbox/Grid layouts, CSS variables for theming, keyframe animations, and mobile-first media queries. The UI uses a modern, developer-friendly color palette inspired by GitHub's dark mode.
* **Vanilla JavaScript:** ES6+ syntax handling the game loop, drag-and-drop touch events, grid matrix logic, collision detection, and particle physics.

## 📁 Project Context

I developed **Block Harmony** as part of my broader portfolio to demonstrate proficiency in:

* **Algorithm Design:** Matrix manipulation for grid validation and line clearing.
* **Event Handling:** Seamlessly unifying mouse and touch events for cross-device compatibility.
* **Performance:** Keeping the DOM light and using the `<canvas>` element for performant particle animations.

---

### License

Distributed under the MIT License. See `LICENSE` for more information.
