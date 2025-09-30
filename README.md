🪐 Interactive 3D Solar System Explorer
A Real-time WebGL Simulation built with Three.js
This project is a single-page web application that renders an interactive, navigable model of our solar system using Three.js. It showcases mastery of 3D graphics programming, precise mathematical modeling of orbits, and high-performance front-end optimization.

✨ Key Features & Technical Highlights
This explorer demonstrates expertise in complex 3D rendering and interaction:

Real-time Orbital Mechanics: Implemented physics modeling to calculate planetary orbits and axial rotation using the requestAnimationFrame loop.

Planetary Trails: Continuous manipulation of Line Geometry (BufferGeometry) to dynamically render faint, persistent trails behind each planet, showcasing performance optimization by managing vertex data.

Advanced Raycasting & Interactivity: Uses Three.js Raycasting for sophisticated interactions:

Hover Glow: Identifies planets on mouse hover and applies a subtle glow using material.emissive.

Click Panel: On click, displays the Information Panel with scaled metrics.

Complex Geometry: Custom rendering of Saturn's Rings using RingGeometry with proper tilt (rotation.x = Math.PI / 2), enhancing visual fidelity.

Custom Camera Control: Implemented custom mousedown, mousemove, and wheel handlers for smooth, non-linear camera rotation and zoom control.

Performance Rendering: Utilized optimization techniques for running a smooth, CPU-efficient simulation with multiple dynamic objects.

🛠️ Technology Stack
3D Library: Three.js (WebGL)

Frontend: HTML5, Vanilla JavaScript

Styling: Tailwind CSS (for modern UI overlays and controls)

🚀 How to Run the Explorer
This project is designed to run instantly in any modern web browser as a single file.

Open the file: Load solar_system_explorer/index.html in your browser.

Navigate:

Click & Drag/Touch: Rotate the camera's view angle around the Sun.

Scroll Wheel: Zoom in and out of the scene.

Interact: Click on any planet or the Sun to reveal the Information Panel with its scaled metrics.

Control Time: Adjust the Time Warp Speed slider to slow down or accelerate the orbital simulation.
