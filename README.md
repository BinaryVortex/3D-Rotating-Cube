# 3D Rotating Cube

A lightweight 3D rotating cube built with plain HTML, CSS and JavaScript. This small project demonstrates CSS 3D transforms, perspective, and simple animation to create an interactive-looking rotating cube.

<p align="center">
  <img src="./Screenshot%202025-01-09%20003752.png" alt="3D Rotating Cube screenshot" width="600">
</p>

## Demo

Open `index.html` in your browser (double-click the file or serve the folder) to see the cube in action.

## Features

- Pure HTML/CSS/JS — no frameworks or build tools required
- Smooth 3D rotation using CSS transforms and keyframe animation
- Simple, easy-to-read code suitable for learning and customization

## How it works (short)

- The cube is constructed with HTML elements for each face.
- CSS provides a perspective on the parent container and positions each face in 3D space using `transform: rotateX()/rotateY() translateZ()`.
- A CSS animation rotates the cube continuously. JavaScript is minimal (if present) and used only to toggle classes or add interactivity.

## Run locally

1. Clone the repository:

   git clone https://github.com/BinaryVortex/3D-Rotating-Cube.git

2. Open `index.html` in your favorite browser:

   - Double-click `index.html`, or
   - Use a simple HTTP server (recommended for consistent behavior):

     python3 -m http.server 8000
     # then open http://localhost:8000 in your browser

## Customize

- Change rotation speed: edit the CSS keyframes or animation duration in `style.css`.
- Change cube size: adjust the face dimensions in `style.css`.
- Swap textures/colors: replace or edit images referenced in the HTML/CSS.

## File structure

- `index.html` — markup for the cube and container
- `style.css` — styles, 3D transforms and animation
- `image1.jpg`, `image2.jpg`, `image3.jpg`, `image4.jpg` — example images used for faces (if applicable)
- `Screenshot 2025-01-09 003752.png` — project screenshot

## Contribution

Contributions are welcome. Open an issue or submit a pull request with improvements, accessibility fixes, or new examples.

## License

This project is provided as-is. Add a license file if you want to specify terms.

---

Made with ❤️ by BinaryVortex
