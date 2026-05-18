# DogStudio Clone 🐕

A high-performance, immersive 3D web experience inspired by the award-winning Dogstudio website. Built to demonstrate advanced scroll-based 3D animations and modern frontend techniques.

**🌟 Live Demo: [https://dog-studio-clone-six.vercel.app/](https://dog-studio-clone-six.vercel.app/)**

## 🚀 Technologies Used

- **React.js**: Core UI framework
- **Three.js & React Three Fiber (@react-three/fiber)**: For rendering and managing the 3D canvas
- **Drei (@react-three/drei)**: Utility ecosystem for React Three Fiber, used for loading compressed `.glb` models efficiently.
- **GSAP (GreenSock) & ScrollTrigger**: For complex, buttery-smooth scroll-based animations linking the DOM to 3D object properties.
- **Vite**: Ultra-fast frontend build tool.

## ✨ Features

- **Interactive 3D Dog Model**: A fully rendered 3D model that reacts to the user's scroll position.
- **Dynamic Lighting & Textures**: Utilizes normal maps and ambient lighting to create a dramatic, studio-quality look.
- **Scroll-Triggered Rotations**: As the user scrolls down the page, the 3D model dynamically scales, rotates, and translates in the background while HTML content overlays in the foreground.
- **Responsive Overlay**: A sleek, minimal UI overlay synchronized with the 3D scene.

## 🛠️ Setup & Installation

To run this project locally, make sure you have Node.js installed.

1. **Clone the repository:**
   ```bash
   git clone https://github.com/Tiku57/DogStudio-Clone.git
   cd DogStudio-Clone
   ```

2. **Install dependencies:**
   ```bash
   npm install
   ```

3. **Start the development server:**
   ```bash
   npm run dev
   ```

4. **Build for production:**
   ```bash
   npm run build
   ```

## 📸 Assets

- The 3D model (`dog.drc.glb`) and corresponding textures are located in the `/public` directory.
- The model uses Draco compression to keep the bundle size small while maintaining high fidelity.

---
👨‍💻 Author
Aaditya Sattawan
---
GitHub: https://github.com/Tiku57
