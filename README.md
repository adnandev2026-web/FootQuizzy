# FootQuizzy
A neon-styled open-world mini-game inspired by the thrill of GTA-style city action, built for both mobile and desktop play.

## Overview
FootQuizzy is a lightweight browser game experience designed to feel fast, fun, and playable on almost any device. You can cruise through a city, complete missions, collect cash, avoid police, and survive the chaos.

This project is designed to be:
- Playable on desktop laptops
- Playable on mobile phones
- Easy to run locally in a browser
- Lightweight and beginner-friendly

## Features
- Open-city driving gameplay
- Police chase system
- Collectible cash pickups
- Mission-based progression
- Mobile touch controls
- Keyboard controls for laptop/desktop
- Responsive layout for different screen sizes

## Gameplay
- Move your car through a city map
- Pick up money and power-ups
- Avoid police patrols
- Complete missions to increase score
- Survive as long as possible in the chaos

## How to Run
1. Download or clone the project.
2. Open the project folder.
3. Start a local web server:
   - With Python:
     ```bash
     python -m http.server 8000
     ```
   - Or use any local static server tool.
4. Open this in your browser:
   - Desktop: http://localhost:8000
   - Mobile: http://YOUR-PC-IP:8000

## Mobile Play
To play on a phone:
1. Connect your phone to the same Wi-Fi network as your computer.
2. Start the local server.
3. Open the browser on your phone and visit:
   ```bash
   http://YOUR-COMPUTER-IP:8000
