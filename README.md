# Scorpio Cursor Game

Hey everyone! This is my **Scorpio Cursor Game** project. I built a cool mechanical scorpion that lives on your screen and follows your mouse around.

It's mostly an experiment in **Procedural Animation**—which means I didn't use any pre-made videos or GIFs. All the leg movements and body bending are calculated in real-time using math (JavaScript) while you play with it!

## YouTube Demo

Watch the complete demonstration and explanation: [**Scorpio Cursor Game - YouTube**](https://youtu.be/bH68xT8f1nk)

## Features

* **Real-time Following:** The scorpion chases your cursor naturally.
* **Walking Logic:** The legs don't just slide; they actually step and plant on the ground.
* **Custom Graphics:** I drew the body parts using code (Canvas API) to make them look like shiny metal armor.
* **Lighting:** It has glowing eyes and a glowing red stinger!

## Project Architecture

The project consists of 3-4 main components:

1. **Input Handler** - Captures mouse movements and tracks cursor position in real-time
2. **Physics Engine** - Implements inverse kinematics for realistic limb movement and body physics
3. **Rendering System** - Uses HTML5 Canvas to draw the scorpion with metallic textures and glow effects
4. **Animation Controller** - Orchestrates all components and manages the game loop at 60 FPS

## Tech Stack

### Frontend Technologies
- **HTML5** - Semantic structure and viewport configuration
- **CSS3** - Styling with custom fonts and positioning
- **JavaScript (ES6+)** - Core logic and physics calculations

### Graphics & Animation
- **HTML5 Canvas API** - 2D rendering context for custom graphics
- **Procedural Animation** - Real-time movement calculations
- **Inverse Kinematics (IK)** - Mathematical system for realistic joint movement
- **Custom Shaders** - Gradient fills and glow effects using Canvas 2D

### Development Tools
- **Git** - Version control and project management
- **Live Server** - Local development environment
- **Browser DevTools** - Debugging and performance optimization

## How to Run It

### Method 1: Simple File Opening
1. Download this folder
2. Make sure you have the background image `scorpion_bg.png` in the same folder as `index.html`
3. Double-click `index.html` to open it in Chrome, Edge, or Firefox
4. Move your mouse and watch it go!

### Method 2: Local Server (Recommended)
```bash
# Start a local HTTP server
python -m http.server 8000

# Or use Node.js live server
npx live-server

# Open http://localhost:8000 in your browser
```

## Git Commands

If you want to update the code and push it to GitHub, here are the commands I use:

```bash
# Add all new changes
git add .

# Save the changes with a message
git commit -m "Updated README with YouTube link and project details"

# Push to GitHub
git push origin main
```

## Live Demo

Try the live version: [**Scorpio Cursor Game on GitHub Pages**](https://sankalpvasekar.github.io/Scorpio-Cursor-Game/)
