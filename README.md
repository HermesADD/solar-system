# 3D Solar System Simulation.

## Description
This project is an interactive 3D simulation of the Solar System, developed for the Computer Graphics course at the National Autonomous University of Mexico (UNAM). The simulation accurately demonstrates the rotation of the planets around the Sun, as well as the Moon's orbit around the Earth. The graphical rendering is built from scratch using WebGL2 and JavaScript, utilizing the Phong illumination model applied with high-resolution textures.

## Features
* **Phong Illumination Model:** Implements realistic lighting calculating ambient, diffuse, and specular light components.
* **Hierarchical Transformations:** Simulates complex orbital mechanics, calculating local and global matrices to correctly render sub-orbits (like the Earth-Moon system).
* **Custom Ring Geometry:** Features a custom-built `Anillo` (Ring) class to procedurally generate the vertices, faces, and UV coordinates required to render Saturn's rings.
* **Interactive Orbit Camera:** Includes a custom camera system based on spherical coordinates (radius, phi, and theta) to smoothly navigate the 3D space.

## Technologies Used
* JavaScript (ES6+)
* WebGL 2.0
* HTML5 Canvas

## Controls 
You can explore the Solar System using the following keyboard controls:

* **Vertical Rotation:** Use the `Up` and `Down` arrow keys to adjust the elevation angle (phi) and look up or down.The angle is restricted to prevent camera inversion.
* **Horizontal Rotation:** Use the `Left` and `Right` arrow keys to rotate around the vertical axis (theta).
* **Zoom:** Use the `+` key to zoom in (decrease radius) and the `-` key to zoom out (increase radius).

## Credits
* **Author:** Hermes Alberto Delgado Díaz.
* **Textures:** All planetary and universe textures were sourced from [Solar System Scope](https://www.solarsystemscope.com/textures/).
