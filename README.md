# The Celestial Compact ✦

A premium, interactive single-page landing website and manifesto for a Discord astrology server. Powered by **Three.js** for immersive 3D celestial animations, including a drifting starfield, interlocking wireframe spheres, orbiting zodiac glyphs, and a responsive floating 3D solar system orrery.

## 🌌 Features

- **Drifting 3D Starfield**: 2,000 drifting point-particles rotating through 3D space.
- **Interlocking Wireframe Spheres**: Concentric celestial grids rotating in opposite directions.
- **Orbiting Zodiac Sprites**: 12 custom-textured zodiac symbols orbiting the hero section with bobbing animations.
- **Projected Click Tooltips**: Select any orbiting zodiac sprite to trigger a 2D projected CSS tooltip listing its keywords. The tooltip follows the symbol's orbit in real-time.
- **Floating 3D Orrery**: A mini-solar system with three planets orbiting concentric paths. Hovering over the Orrery speeds up the orbits with smooth acceleration and deceleration curves.
- **Elegant Typography**: Utilizing Google Fonts `Cinzel` for celestial displays and `Inter` for modern body copies.
- **Intersection Observer Animations**: Manifesto sections fade and slide up smoothly as they enter the viewport.
- **Celestial Aesthetics**: Styled with a deep navy background (`#0a0914`), gold accents (`#c9a84c`), and soft purples (`#9b8ec4`), including a custom star-dot Radial Gradient background for the server Oath.

## 🛠️ Tech Stack

- **Three.js (r128)** — 3D rendering.
- **HTML5 & CSS3** — Fully vanilla, zero CSS frameworks or build steps.
- **Google Fonts** — `Cinzel` + `Inter`.

## 🚀 Getting Started

Since this is a client-side purely static application, there is no installation or build step required.

### Run Locally
1. Clone the repository:
   ```bash
   git clone https://github.com/Poleter69/astroparty.git
   ```
2. Open `index.html` directly in your browser or run a simple local server:
   ```bash
   # Using Python
   python -m http.server 8000
   
   # Using Node.js
   npx serve .
   ```
3. Open `http://localhost:8000` (or the corresponding port) in your web browser.

## 📜 Server Oath

> "I look up, not down on others.  
> I read charts, not people's worth.  
> I hold space as wide as the sky.  
> As above — so, beloved, below. ✦"

## 📄 License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
