# Saswat Ranjan Nayak — 3D Interactive Portfolio

![Portfolio Preview](images/pic.png)

A modern, highly interactive, and immersive 3D personal portfolio website built for **Saswat Ranjan Nayak**, a Data Analyst and Full-Stack Web Developer. 

The site abandons traditional flat web design in favor of a dynamic, physics-based 3D environment featuring interactive elements, glassmorphism UI, a custom-built Light/Dark theme system, and scroll-triggered animations.

## 🚀 Live Demo
**[saswatnayak.com](https://saswatnayak.com)**

---

## ✨ Key Features

- **Immersive 3D Background**: A fully interactive, rotating 3D galaxy of stars and geometric meshes built with Three.js that responds to mouse parallax.
- **Dynamic Light/Dark Mode**: A custom, cache-busting theme toggle system that transitions the entire site (including 3D canvas rendering and CSS variables) smoothly between dark neon and premium light modes. Persistent via `localStorage`.
- **Advanced Scroll Animations**: Sections and elements gracefully reveal themselves as you scroll, powered by `IntersectionObserver`.
- **3D Card Interactivity**: Project cards feature a pure CSS 3D-flip effect, while the About Me section utilizes `vanilla-tilt.js` for physics-based 3D tilting and glare.
- **Custom Cursor & Trail**: A completely custom, glowing cursor system that leaves a trailing dot mapped to mouse movements.
- **SEO Optimized**: Fully equipped with descriptive metadata, keyword targeting, `robots.txt`, Open Graph (`og:`), and Twitter Card integrations for rich social sharing previews.
- **Responsive & Performant**: Mobile-first grid layouts combined with hardware-accelerated CSS and optimized 3D rendering.

---

## 🛠️ Technology Stack

This project is built using powerful, modern web technologies without reliances on heavy overarching frameworks:

* **Core Structure**: HTML5
* **Styling**: Pure CSS3 (CSS Variables, Flexbox, CSS Grid, Glassmorphism, CSS 3D Transforms)
* **Logic**: Vanilla JavaScript (ES6+)
* **3D Rendering**: [Three.js](https://threejs.org/) (WebGL)
* **Text Animation**: [Typed.js](https://github.com/mattboldt/typed.js/)
* **Physics/Tilt Animation**: [Vanilla-tilt.js](https://micku7zu.github.io/vanilla-tilt.js/)
* **Icons**: [Font Awesome 6.5](https://fontawesome.com/)

---

## 📂 Project Structure

```text
├── css/
│   ├── 3d-theme.css      # Core styles, variables, light/dark themes, and animations
│   └── style.css         # Legacy styles (deprecated)
├── images/               # Project thumbnails and profile pictures
├── js/
│   ├── main.js           # Core interactions
│   └── Typed.js          # Legacy scripts
├── index.html            # Main portfolio layout and 3D logic
└── robots.txt            # Search Engine crawler rules
```

---

## 💻 Local Setup & Development

Because this project uses Three.js (which requires fetching textures via WebGL), it cannot simply be opened via the `file://` protocol. You must run it through a local web server.

### Prerequisites
- [Node.js](https://nodejs.org/) OR [Python](https://www.python.org/) installed on your machine.

### Running with Python
```bash
# Navigate to the project directory
cd saswatnayak.com

# Start a local HTTP server
python -m http.server 8000
```
Then open your browser and navigate to `http://localhost:8000`

### Running with Node.js / npx
```bash
# Navigate to the project directory
cd saswatnayak.com

# Start a local server
npx serve .
```
Then open your browser and navigate to the localhost port provided in the terminal.

---

## 👨‍💻 Author

**Saswat Ranjan Nayak**
- Role: Data Analyst & Full-Stack Web Developer
- GitHub: [@Saswat132002](https://github.com/Saswat132002)
- Website: [saswatnayak.com](https://saswatnayak.com)
