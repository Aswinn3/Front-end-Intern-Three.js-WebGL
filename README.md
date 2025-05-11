# Three.js Raycasting Drag-and-Drop

This project is a 3D drag-and-drop scene built using [Three.js](https://threejs.org/). It allows interactive manipulation of 3D objects like a box, sphere, cylinder, and a custom-loaded castle model via raycasting.

## 🌟 Features

- Perspective camera with OrbitControls for easy navigation
- Interactive dragging of 3D objects on a ground plane using raycasting
- Support for custom `.obj` model loading (castle)
- Real-time rendering with lighting and shadows
- Responsive window resize handling

## 🛠️ Tech Stack

- [Three.js](https://threejs.org/)
- TypeScript
- Webpack
- Live Server


## 🚀 Setup and Run

1. **Clone the repository**
   ```bash
   git clone https://github.com/Aswinn3/Front-end-Intern-Three.js-WebGL.git
   cd Front-end-Intern-Three.js-WebGL


2. **Install dependencies**

   npm install
   
3. **Start development server**

   npm start


4. **Open your browser and navigate to http://127.0.0.1:8080**


## 📦 Build

To bundle the project using Webpack:

npm run bundle


## 🧪 Interactions

Click on any object to select it.

Move your mouse to drag the object along the ground.

Click again to release the object.

## 🧰 Scripts


json

"scripts": {
  "start": "npm run bundle && npm-run-all --parallel webpack serve",
  "serve": "cd src && live-server",
  "bundle": "webpack --config webpack.config.js",
  "webpack": "webpack --config webpack.config.js --watch"
}
