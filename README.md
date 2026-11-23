# PATROL — Last Flight

**No destination. No backup. Just the last flight.**

PATROL — Last Flight is a free, browser-based 3D arcade air combat game where you take control of an F-22-inspired fighter jet and fight to survive endless waves of enemy aircraft.

Fly across a procedurally generated landscape of mountains, lakes, and forests. Engage hostile fighters, evade incoming missiles, deploy countermeasures, and push your aircraft to its limits.

No downloads. No installations. Just launch your browser and take flight.

## Features

- **3D Air Combat:** Fast-paced dogfights against AI-controlled enemy fighters.
- **Procedural World:** Explore a continuously repeating landscape featuring mountains, lakes, clouds, and changing terrain.
- **Three Camera Modes:** Switch between top-down, third-person chase, and cockpit views.
- **Missile Combat:** Acquire targets, lock on, and launch guided missiles.
- **Vulcan Cannon:** Engage enemies with a rapid-fire cannon featuring overheating and cooldown mechanics.
- **Countermeasures:** Deploy flares and perform evasive barrel rolls to avoid incoming missiles.
- **Aircraft Damage:** Survive enemy attacks while managing your aircraft's hull integrity.
- **Icing System:** Flying too high can freeze your aircraft's systems, causing temporary loss of control.
- **Power-Ups:** Collect hull repairs, missile reloads, and additional flares.
- **Endless Survival:** Face increasingly challenging waves of enemies and compete for higher scores.
- **Adaptive Rendering:** Dynamic internal resolution adjustment helps maintain performance.
- **Synthesized Audio:** Engine sounds, warnings, and combat effects generated through the Web Audio API.

## Controls

| Action | Control |
|---|---|
| Steer Aircraft | Mouse |
| Barrel Roll | Left Click |
| Boost | Hold Left Mouse Button |
| Fire Missile | F / Right Click |
| Vulcan Cannon | Hold G |
| Deploy Flares | C |
| Change Camera | Space |
| Toggle Sound | Sound Button |

Touchscreen controls are also available on supported devices.

## Technology

PATROL — Last Flight is built using web technologies:

- HTML5
- CSS3
- Vanilla JavaScript
- WebGL 2
- GLSL Shaders
- Canvas 2D
- Web Audio API
- Web Workers

The game uses a custom rendering and gameplay implementation without relying on external game engines such as Unity, Unreal Engine, or Three.js.

Terrain generation, flight simulation, enemy behavior, projectiles, and combat systems run directly in the browser.

## How to Play

1. Open the game in a WebGL 2-compatible browser.
2. Wait for the procedural world to finish generating.
3. Click **TAKE FLIGHT**.
4. Use your mouse to control your aircraft.
5. Lock onto enemy fighters and engage them using missiles or your Vulcan cannon.
6. Dodge incoming attacks using barrel rolls and flares.
7. Collect power-ups and survive as many waves as possible.

Watch your altitude. Flying too low can cause a collision, while flying too high can trigger severe icing.

## Run Locally

Clone the repository:

```bash
git clone https://github.com/YOUR-USERNAME/patrol-last-flight.git
```

Navigate to the project directory:

```bash
cd patrol-last-flight
```

Start a local web server:

```bash
python3 -m http.server 8000
```

Open your browser and visit:

`http://localhost:8000`

Make sure the main game file is named `index.html`.

## Browser Compatibility

PATROL requires a browser with WebGL 2 support.

Recommended browsers include:

- Google Chrome
- Microsoft Edge
- Mozilla Firefox
- Safari

Performance depends on the device, browser, and available GPU resources.

## Development Status

**Playable Prototype — Active Development**

PATROL is an experimental browser game focused on procedural environments, lightweight 3D rendering, and arcade-style aerial combat.

Future improvements may include additional aircraft, new weapons, expanded enemy behavior, visual enhancements, and more gameplay mechanics.

## Credits

Built with JavaScript, WebGL 2, and a passion for aviation and arcade combat.

---

**PATROL — Last Flight**

*The sky is yours. Until it isn't.*
