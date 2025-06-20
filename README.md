AstroVista ->

AstroVista is a 3D solar system simulation built with Three.js, offering an immersive exploration of Mercury, Venus, Earth, Mars, Jupiter, Saturn, Uranus, Neptune, and an Asteroid Belt with over 200 uniquely shaped asteroids. It features high-quality 8K textures, a dynamic starfield background, enhanced deep space audio, and flexible speed controls for an engaging experience.

Features ->

3D Solar System Simulation: Models planetary orbits with dynamic minimum distances (surface + 5 units for planets, 20 units for deep space).
High-Quality Visuals: 8K textures for planets and the Sun, plus an Asteroid Belt with over 200 asteroids of varying shapes and sizes.
Immersive Audio: Enhanced deep space sound for a realistic cosmic feel.
Dynamic Starfield: A starry background to enhance the deep space experience.
Flexible Speed Controls: Universal speed controller for the solar system and planet-specific speed adjustments for customized exploration.
Interactive Interface: Built with Three.js, HTML, CSS, and JavaScript for seamless interaction.

Project Structure ->

solar-system/
├── index.html           # Main HTML file (single file with internal css and js)
├── Deep Space Sound     # Background audio file
├── images/              # Planet texture images
│   ├── mercury.jpg
│   ├── venus.jpg
│   ├── earth.jpg
│   ├── mars.jpg
│   ├── jupiter.jpg
│   ├── saturn.jpg
│   ├── uranus.jpg
│   └──  neptune.jpg
└── README.md            # This file

Getting Started ->
Prerequisites

A modern web browser with WebGL support (e.g., Chrome, Firefox, Edge).
A local development server to serve the project (required for texture loading due to CORS restrictions).

Running the Project
Important: Opening index.html directly via file:// will likely fail due to browser CORS restrictions. Use a local development server instead.
Option 1: VS Code with Live Server

Install the Live Server extension in VS Code.
Right-click index.html and select Open with Live Server.
Access the project at http://localhost:5500.

Option 2: Node.js http-server

Install http-server globally:npm install -g http-server


Navigate to the project directory:cd path/to/solar-system

Start the server:http-server

Access at http://localhost:8080.

Option 3: Python HTTP Server

Navigate to the project directory:cd path/to/solar-system

Start the server:python -m http.server 8000

Access at http://localhost:8000.

Troubleshooting

Textures not loading?
Verify texture files exist in the images/ folder and paths in main.js match (e.g., images/mercury.jpg).
Check browser console (F12 → Console) for errors.
Ensure file names are case-sensitive.

Simulation not rendering?
Confirm your browser supports WebGL (test at get.webgl.org).
Ensure Three.js is loaded correctly (check <script> tags in index.html).

Contributing
Contributions are welcome! To contribute:

Fork the repository.
Create a feature branch (git checkout -b feature-name).
Commit your changes (git commit -m "Add feature").
Push to the branch (git push origin feature-name).
Open a pull request.

Acknowledgments ->

Built with Three.js
8K Planet textures
Audio: Deep Space Sound

Crafted by Kapil Sandhu
