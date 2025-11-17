🚀 3D Solar System Explorer

<img width="826" height="731" alt="image" src="https://github.com/user-attachments/assets/318324f5-9607-4c43-a103-1fb4b1cbe116" />


This is a real-time, interactive 3D simulation of our solar system built using the Three.js library, enabling users to explore celestial mechanics, view orbits, and check planetary data in a dynamic environment.

✨ Key Features

Interactive 3D Visualization: Renders a scaled model of the Sun and the eight major planets, complete with a star field background and appropriate lighting.

Physics Simulation: Implements orbital movement and axial rotation for all celestial bodies.

Dynamic Camera Controls: Provides smooth, intuitive control over the camera:

Mouse Drag / Touch Swipe: Orbit the entire system.

Mouse Wheel / Pinch: Zoom in and out.

Click-to-Inspect: Click on any planet or the Sun to reveal a dedicated information panel showing its scaled size, orbital distance, and speed.

Planetary Trails: Visualizes the path of each planet with a dynamic trail line, distinct from the static orbit path.

Time Warp Control: Use the slider in the top right to adjust the simulation speed from 0.1x (slow motion) up to 5.0x (fast forward).

Saturn Rings: Includes a visually represented ring system for Saturn, tilted to mimic its natural axial tilt.

▶️ How to Use

The application is self-contained in a single HTML file and runs directly in the browser, leveraging your computer's GPU via WebGL.

Feature

Control

Action

Orbit Camera

Mouse Left-Click and Drag / Touch Swipe

Rotate the view around the Sun (center).

Zoom View

Mouse Wheel Scroll

Move the camera closer to or farther from the center.

Inspect Planet

Single Click on a Planet

Displays the detailed information panel at the bottom.

Toggle Orbits

Pause Orbits / Start Orbits button

Stops/resumes the orbital motion animation.

Adjust Speed

Time Warp Speed Slider

Changes the rate of all orbital and rotational animations.

⚙️ Technology Stack

Core Library: Three.js (r128 via CDN) for all 3D scene rendering, geometries, lighting, and camera management using WebGL.

Rendering: WebGL (via Three.js)

Structure: HTML5 and Vanilla JavaScript (ES6+).

Styling & UI: Tailwind CSS (via CDN) for the responsive overlay, control panel, and planet information display.
