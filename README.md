# Solar System Simulation

A 3D interactive simulation of our solar system built with Three.js

## Features
- Real-scale planetary orbits
- Adjustable simulation speed
- Celestial body information panels
- Pause/Resume functionality
- Camera controls for exploration

## Requirements
- Modern web browser
- WebGL support

## Installation & Usage
```bash
# Clone repository
git clone https://github.com/yourusername/solar-system-simulation.git

# Launch local server (from project root):
py -m http.server 8000
```

Open `http://localhost:8000/Solar%20System%20Simulation.html` in your browser

## Deployment
### Vercel
This project is configured for easy deployment to Vercel:

1. Connect your GitHub repository to Vercel
2. Vercel will automatically detect and deploy the project
3. The deployment uses `index.html` as the entry point
4. Configuration is managed by `vercel.json`

You can also deploy directly from the command line:
```bash
# Install Vercel CLI (if not already installed)
npm install -g vercel

# Deploy to Vercel
vercel
```

## Technologies
- Three.js
- HTML5 Canvas
- CSS3
- JavaScript ES6

## License
MIT License
