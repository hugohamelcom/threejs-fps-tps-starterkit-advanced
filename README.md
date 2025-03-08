# 3D Collision World with Day/Night Cycle

A 3D interactive environment built with Three.js featuring:
- First-person and third-person camera modes
- Realistic player movement and collision detection
- Dynamic day/night cycle with smooth transitions
- Interactive physics-based spheres
- Player animations (walking, running, jumping)

## Features

### Player Controls
- **WASD**: Move forward/backward and strafe
- **Space**: Jump
- **Shift**: Sprint
- **Mouse**: Look around
- **C**: Toggle between first-person and third-person views

### Environment
- **Dynamic Lighting**: Sun and moon with realistic shadows
- **Day/Night Cycle**: Smooth transitions between day and night with:
  - Sunrise, midday, sunset
  - Moonrise, midnight, moonset
  - Starry night sky
- **Physics**: Realistic collision detection using octree spatial partitioning

### Technical Details
- Built with Three.js (v0.174.0)
- Uses GLTF models for environment and player character
- Implements octree-based collision detection
- Features additive animations for smooth transitions
- Includes performance stats display

## Setup

1. Clone the repository
2. Open `index.html` in your browser
3. Click to lock mouse pointer and start interacting

## Dependencies

- Three.js (loaded via CDN)
- GLTF models from Three.js examples

## Customization

The project includes a GUI for:
- Toggling debug visualization
- Adjusting day/night cycle duration
- Switching between first-person and third-person views

## License

This project is open-source and available under the MIT License.
