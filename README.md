# Catch the Valorous Rabbit 🐇

A minimalist 3D endless-runner game built with Three.js and GSAP. Guide the rabbit to collect carrots, dodge hedgehogs, and outrun a hungry monster in a low-poly world.

🎮 **Play it live:** [Click Me!](https://the-rabbit.vercel.app/)

## 🎯 Features

- Smooth 3D animations powered by Three.js and GSAP
- Intuitive one-tap or one-click jump controls
- Progressive difficulty with distance-based scoring and increasing speed
- Collectible carrots for bonus points and hedgehog obstacles
- Game-over screen with instant replay functionality
- Responsive design for desktop and mobile (touch support)

## 🚀 Getting Started

### Prerequisites
- A modern browser with WebGL support (Chrome, Firefox, Safari)
- Optional: Node.js and a local server package for development

### Option 1: Open Directly
1. Clone or download this repository
2. Open `index.html` in a WebGL-compatible browser

### Option 2: Serve Locally (Recommended)
1. Clone or download this repository
2. Install a local server package:
3. npm install -g http-server
4. Start the server
5. live-server

4. Open the provided URL (e.g., `http://localhost:8080`) in your browser

## 🎮 Controls

- **Jump:** Click or tap the screen
- **Replay:** Click or tap after game over to restart

## 🛠️ Tech Stack

- [Three.js (r80)](https://threejs.org/) - 3D rendering
- [GSAP (TweenMax 1.19.0)](https://greensock.com/gsap/) - Animation
- HTML/CSS - User interface and overlay styling
- OrbitControls - Optional debugging (disabled by default)

> **Note:** This project uses an older Three.js version (r80) to match the original demo. Upgrading to a newer version requires refactoring geometry constructors and materials.

## 📁 File Structure
 -  index.html # Main HTML with canvas and script includes
 -   style.css # UI and overlay styling
 -  ript.js # Game logic, 3D models, and animation loop


## ⚙️ How It Works

- **Scene Setup:** 3D environment with camera, lights, fog, and a spherical "floor"
- **Characters:** Rabbit (player) and monster (pursuer) built from Three.js primitive geometries
- **Gameplay:** Collect carrots for points, avoid hedgehogs, and stay ahead of the monster
- **Objects:** Carrots (bonuses), hedgehogs (obstacles), and decorative trees
- **Game Loop:** Updates floor rotation, object positions, collision detection, score, and renders each frame
- **States:** `play`, `gameOver`, and `readyToReplay`

## 🚀 Deployment

- **Vercel:** Upload `index.html`, `style.css`, and `script.js` to a Vercel project and deploy (no build step needed)
- **Other Static Hosts:** Deploy to GitHub Pages, Netlify, or any static hosting service

## 🔧 Troubleshooting

- **Black Screen / Nothing Renders:** Ensure your browser supports WebGL and hardware acceleration is enabled
- **Audio Issues:** Browsers may block autoplay audio; click or tap to enable sound
- **Performance Issues:** Close resource-heavy tabs or reduce animation speed in `script.js`

## 🙏 Credits

- **Inspiration:** Low-poly endless-runner concept from CodePen
- **Music:** Vivaldi – Summer (First Movement) (public domain)
- **Models:** All 3D models are programmatically created using Three.js primitives

## 📄 License

[MIT License](LICENSE) — free to use, modify, and distribute.

## 🤝 Contributing

Feel free to fork, tweak, or build upon this project! If you create something awesome, share a link—I'd love to see it.

---

**Happy hopping! 🐇**

