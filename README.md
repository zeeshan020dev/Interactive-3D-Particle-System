# 🌌 AI Hand-Controlled Particle System

![Gemini 3.0](https://img.shields.io/badge/Generated%20with-Gemini%203.0-4285F4?style=for-the-badge&logo=google)
![Three.js](https://img.shields.io/badge/Three.js-Black?style=for-the-badge&logo=three.js)
![MediaPipe](https://img.shields.io/badge/MediaPipe-Computer%20Vision-009973?style=for-the-badge)

> **"From blank canvas to a physics-based, hand-tracking engine in exactly 59.3 seconds."**

## 🚀 Overview
This project is a real-time, interactive 3D particle system controlled entirely by hand gestures. It was architected and coded using **Google's Gemini 3.0** inside AI Studio via advanced prompt engineering. 

The application utilizes **MediaPipe** for skeletal hand tracking and **Three.js** for high-performance WebGL rendering, mapping 2D hand coordinates to a 3D volumetric space.

### 🔴 [Live Demo](https://zeeshan020dev.github.io/Interactive-3D-Particle-System/) 
*(See "Deployment" below to enable this link)*

---

## 🎮 How to Interact
Ensure your webcam is enabled. The system detects your hand landmarks to drive the physics engine.

| Gesture | Action | Visual Effect |
| :--- | :--- | :--- |
| **🖐 Open Hand** | **Navigation** | Rotate the particle universe and position the center. |
| **👌 Pinch (Thumb + Index)** | **Morph Shape** | Transforms particles into complex geometries (Sphere → Heart → Saturn → Flower → Torus). |
| **✊ Closed Fist** | **Implode** | Triggers a physics collapse (implosion), shrinking the universe. |

---

## 🛠️ Technical Stack
* **AI Architect:** Google Gemini 3.0 (via Google AI Studio)
* **Rendering Engine:** Three.js (WebGL)
* **Computer Vision:** MediaPipe Hands (Client-side ML)
* **Language:** JavaScript (ES6+), HTML5

## 🧠 The "Gemini 3.0" Workflow
This code was not manually written line-by-line. It was generated using a single, comprehensive prompt structure that defined:
1.  **Context:** "Expert Creative Technologist"
2.  **Constraints:** Single file, CDN links only, no build steps.
3.  **Logic:** Mapping specific MediaPipe landmarks (Tips 4 & 8) to Three.js vector attributes.
4.  **Math:** Parametric equations for the "Heart" and "Rose Curve" shapes.

**Generation Time:** 59.3 Seconds.

---

## 📦 Installation & Usage
No installation required! This is a vanilla JS project.

1.  Clone the repo:
    ```bash
    git clone [https://github.com/YOUR_USERNAME/gemini-particle-system.git](https://github.com/YOUR_USERNAME/gemini-particle-system.git)
    ```
2.  Open `index.html` in your browser.
    * *Note: For MediaPipe to work correctly locally, it is recommended to use a local server (like Live Server in VS Code) due to browser security policies regarding webcams.*

## 📄 License
MIT License. Feel free to use this as a base for your own AI experiments!

---
*Created by Muhammad Zeeshan Islam - Co-Founder of Unicodrex & Technical Associate of Skill Sprint, Powered by Prompt Engineering.*
