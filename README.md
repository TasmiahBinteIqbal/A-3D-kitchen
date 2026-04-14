# A-3D-kitchen
Interactive 3D Kitchen Scene

This project is an interactive 3D kitchen simulation built using Three.js and WebGL with custom GLSL shaders. It demonstrates real-time rendering, lighting, animation, and user interaction directly in the browser without external 3D models.

Features:
Graphics & Rendering
Fully procedural 3D kitchen scene
5 custom GLSL ShaderMaterial implementations:
Wood Floor (grain + plank effect)
Steam Particle System
Wall Tiles (grout + checker effect)
Metal Shader (realistic reflections & scratches)
Stove Surface (procedural burner rings)
No external textures — all generated using HTML5 Canvas

Lighting System
Ambient Light (global illumination)
Directional Light (sunlight effect)
Point Lights: warm fill light, ceiling light (flicker), window light (dynamic effect)

User Interaction
Keyboard Controls
W / S → Move forward / backward
A / D → Move left / right
Q / E → Move up / down
Arrow Keys → Rotate camera
Mouse Interaction
Click refrigerator door to open/close (smooth animation)
Raycasting used for object detection

Animations
Refrigerator door (smooth pivot rotation)
Steam particle system (180 particles)
Stove animation
Ceiling light flicker
Real-time wall clock

Scene Objects
Refrigerator (procedural texture)
Stove (burners + control panel)
Floor, walls, ceiling (custom shaders)
Lighting setup & decorative elements

Technologies Used
HTML5 / CSS3
JavaScript (ES6)
Three.js (r128)
WebGL
GLSL (Vertex + Fragment Shaders)
Canvas API
