# Cyber-Racer-2D-2D-Car-Game-

A fast-paced, 5-lane endless arcade racing game built from scratch using vanilla JavaScript and HTML5 Canvas. This project features universal device support, allowing seamless gameplay across both desktop computers and mobile touchscreen devices.

🚀 **[Click Here to Play the Game](https://git-hubratlee.github.io/Cyber-Racer-2D-2D-Car-Game-/)**


---

## Technical Features

* **Universal Device Input**: Fully playable on desktop using keyboard arrow keys, and on mobile/tablet via split-screen left and right touch interaction zones.
* **Deterministic Render Loop**: Utilizes a native `requestAnimationFrame` game loop to ensure smooth, frame-rate independent physics and rendering.
* **Procedural Obstacle Stream**: Spawns unpredictable oncoming traffic dynamically across 5 strict coordinates to guarantee highly replayable matches.
* **Linear Velocity Scaling**: Automatically accelerates game speed, background rendering cycles, and handling sensitivity every time you score 60 points.
* **Zero Dependencies**: Built entirely with raw HTML5 Canvas logic and vanilla ES6 programming without relying on any external gaming frameworks or wrappers.

---

## File Architecture

```text
├── index.html       # Unified core game loop, canvas logic, markup, and styling
├── .gitignore       # Operating system and workspace file exclusion list
└── README.md        # Technical project documentation
```

---

## Local Development

To test or modify this project locally, clone the repository and open the source file in your browser:

```bash
# Clone this repository
git clone https://github.com

# Navigate into the game directory
cd Cyber-Racer-2D-2D-Car-Game-

# Open the entry file
open index.html
```

---

## License

Distributed under the MIT Open Source License. See the repository documentation for terms.

