# Interactive 3D Model Viewer

A web-based 3D model viewer built using [Three.js](https://threejs.org/) with support for VR (WebXR), mouse interaction, file uploads, and automatic annotations.

## Features

- Upload and view 3D models in `.gltf`, `.glb`, `.fbx`, `.obj`, `.stl`, and `.ply` formats
- Rotate, zoom, and pan with mouse controls (OrbitControls)
- View in Virtual Reality (VR) with WebXR-compatible devices
- VR interaction using controllers for grabbing and scaling models
- Automatic annotations for model orientation (Top, Bottom, Front, Back, etc.)
- Responsive and minimal UI

## Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/YOUR_USERNAME/interactive-3d-viewer.git
cd interactive-3d-viewer
````

### 2. Open the Viewer

Simply open `index.html` in a modern browser (e.g., Chrome or Edge). For VR support, use a compatible browser and headset.

>  Some loaders and features (like WebXR) may require a local server or HTTPS hosting. Use GitHub Pages or run a local server:

```bash
# Python 3
python -m http.server
```

Then visit `http://localhost:8000` in your browser.

## Supported Formats

* `.glb` / `.gltf` (GLTFLoader)
* `.obj` (OBJLoader)
* `.fbx` (FBXLoader)
* `.stl` (STLLoader)
* `.ply` (PLYLoader)

## Dependencies

This project uses the following libraries via CDN:

* [Three.js v0.134.0](https://threejs.org/)
* Loaders: GLTFLoader, OBJLoader, FBXLoader, STLLoader, PLYLoader
* OrbitControls for mouse interaction

## How It Works

* Users upload a 3D file via the file input
* File is parsed by the appropriate loader and added to the scene
* Model is centered, scaled to fit view, and annotated
* Mouse or VR controllers can be used to interact with the model

## Author

**Gift Ahanonu**
📧 [giftahanonu@outlook.com](mailto:giftahanonu@outlook.com)
🔗 [LinkedIn](https://www.linkedin.com/in/giftahanonu)

---

> © 2025 Gift Onyinyechi Ahanonu — Open-source for learning and experimentation.

