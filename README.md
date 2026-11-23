# 🌊 THE OCEAN — A Realtime Exploration

An immersive real-time 3D ocean simulation shaped by wind, water, and light. Built with Three.js, WebGL, and custom GLSL water shaders.

![The Ocean Preview](https://coding-assets.oss-ap-southeast-1.aliyuncs.com/og-image.jpg)

## 🎮 Live Demo
- **GitHub Pages:** [https://mdhasibul35.github.io/the-ocean/](https://mdhasibul35.github.io/the-ocean/)
- **Netlify:** [https://hasib-the-ocean.netlify.app](https://hasib-the-ocean.netlify.app)

---

## ✨ Features
- 🌊 **Procedural Ocean Waves**: Gerstner wave simulation and Fourier spectrum wave displacements responding to dynamic wind forces.
- 🌅 **Dynamic Atmosphere & Lighting**: Smooth transitions between Golden Hour, Noon Sun, Twilight, and Violent Storm conditions.
- 🚣 **3D Boatman & Vessel Physics**: Realistic buoyancy simulation with vessel pitching, rolling, and heaving on wave crests.
- 🔊 **Synthesized Ambient Audio**: Dynamic ocean waves and wind audio generated procedurally using the Web Audio API.
- 🎥 **Cinematic Camera Modes**: Free orbit camera, drone view, and cinematic chase cameras.
- 📱 **Mobile & Desktop Responsive**: Full touch and mouse support with adaptive resolution scaling.

---

## 🛠️ Local Development & Running

Because this project uses ES modules and loads 3D models (`.glb`), run it via any local web server:

```bash
# Using Node.js npx serve
npx serve .

# Or using Python 3
python -m http.server 8080
```

Then open [http://localhost:3000](http://localhost:3000) or [http://localhost:8080](http://localhost:8080) in your browser.

---

## 🚀 Deployment

### GitHub Pages
1. Push this repository to GitHub under your account.
2. Go to **Settings** > **Pages**.
3. Under **Build and deployment** > **Branch**, select `main` and `/ (root)`.
4. Click **Save**. The `.nojekyll` file included in the repository ensures all assets load properly without Jekyll processing.

### Netlify
1. Go to [Netlify Drop](https://app.netlify.com/drop).
2. Drag and drop this folder or the `the-ocean.zip` file.
3. Instant live link in seconds!

---

## 👨‍💻 Author
**Hasibul Hasan**
- GitHub: [@mdhasibul35](https://github.com/mdhasibul35)
- X (Twitter): [@hasibdreamer35](https://x.com/hasibdreamer35)
