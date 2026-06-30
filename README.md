# Tringle Flight Simulator 🛸

A retro-inspired 3D flight game featuring a procedurally-generated park environment, intuitive mobile-friendly controls, and a minimalist aesthetic.

## Features

- **3D Flight Mechanics** - Pitch and yaw camera control with throttle acceleration
- **Tetrahedron Spaceship** - Pilot a rotating tetrahedron through endless procedural landscapes
- **Procedural Generation** - Randomly-placed trees and infinite grid-based terrain
- **Mobile-Friendly Controls** - Touch joystick and throttle slider for phones/tablets
- **Desktop Support** - Mouse/keyboard fallback for browser testing
- **Retro Aesthetic** - Pixelated 400x240 rendering with neon wireframe colors
- **Live Telemetry** - Real-time altitude and speed display

## Project Structure

```
Tringle-flight-sim/
├── index.html          # Landing page / home
├── pages/
│   └── game.html       # Flight simulator game
├── css/
│   └── style.css       # Shared styles
├── js/                 # (For future modularization)
└── README.md           # This file
```

## Getting Started

### Play Online
Open `index.html` in any modern web browser (Chrome, Firefox, Safari, Edge).

### Controls

**On Mobile:**
- **Left Joystick** - Steer (left/right) and pitch (up/down)
- **Right Throttle Slider** - Accelerate forward (top) or backward (bottom)

**On Desktop:**
- **Joystick** - Click and drag in the left circle to steer
- **Throttle** - Click and drag the throttle knob up/down

## Gameplay

1. Start at the landing page by opening `index.html`
2. Click **"LAUNCH SIMULATOR"** to enter the game
3. Use the joystick to navigate through the park
4. Watch the telemetry display for altitude and speed
5. Click the **"HOME"** button to return to the landing page

## Technical Details

### Technologies
- **Vanilla JavaScript** - No frameworks or libraries
- **HTML5 Canvas** - 3D rendering with perspective projection
- **Responsive CSS** - Mobile and desktop optimization

### 3D Engine
- **Custom 3D projection** - Perspective-corrected world-to-screen conversion
- **Camera system** - Pitch/yaw rotation with forward/backward movement
- **Object rotation** - Self-spinning tetrahedron wireframe

### Performance
- **Fixed 400x240 resolution** - Retro pixelated rendering
- **RequestAnimationFrame** - Smooth 60fps animations
- **Frustum culling** - Behind-camera objects not rendered

## Browser Compatibility

- Chrome/Chromium (Recommended)
- Firefox
- Safari 12+
- Edge

Requires HTML5 Canvas and ES6 JavaScript support.

## Future Enhancements

- [ ] Sound effects and music
- [ ] Different ship models
- [ ] Collectible objects
- [ ] Multiple flight modes
- [ ] Keyboard shortcuts (WASD, arrow keys)
- [ ] Difficulty levels
- [ ] Leaderboard/scoring system

## Development

To modify the game, edit the files directly:
- **Game logic** - See `/pages/game.html` (inline script)
- **Styles** - Edit `/css/style.css` for landing page, game styles inline in game.html
- **Landing page** - Edit `index.html` for home screen content

No build process required—just open in a browser!

## License

Free to use and modify.

---

**Created with vanilla JavaScript and Canvas API**
