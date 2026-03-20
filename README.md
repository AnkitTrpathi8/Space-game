# Space-Plant-game

 Overview

Cosmic Creator is an interactive space-themed web application where users can design their own planet and then experience it through a dynamic astronaut training game.

This project combines science simulation + game development + modern UI design into one immersive experience.

 Features
 Planet Simulator

Adjust Gravity, Atmosphere, Distance from Star, Size, and Surface

Real-time calculation of:

 Temperature

 Life Possibility

 Weather Conditions

 Habitability Score

3D rotating planet visualization using Three.js

Dynamic textures and atmosphere effects

Astronaut Training Game

Play on the planet you created

Environment directly affects gameplay:

Low gravity → floaty movement

High gravity → heavy movement

No atmosphere → oxygen loss

Toxic atmosphere → health damage

Extreme temperature → survival difficulty

 Game Modes

 Movement Training

 Asteroid Avoidance

 Spacecraft Docking

Survival Mode

 UI & Experience

Futuristic neon + glassmorphism UI

Smooth animations and transitions

Interactive dashboard and HUD

Particle effects and combo system

Responsive design (works on different screen sizes)

Extra Features

Save planet configurations (LocalStorage)

Reset system

Score tracking system

Health & Oxygen mechanics

Dynamic difficulty scaling

Tech Stack

HTML5

CSS3 (Advanced animations + glassmorphism)

JavaScript (Vanilla)

Three.js (3D rendering)

Canvas API (game engine)

 Project Structure
Cosmic-Creator/
│── index.html
│── /assets
How to Run

Download or clone this repository

Open index.html in your browser

Start creating your planet 

Click "Explore Planet" to play the game 

No installation or backend required — fully browser-based

 How It Works
Simulation Logic

Temperature is calculated based on:

Distance from star

Atmosphere type

Surface type

Life detection:

Depends on temperature range + atmosphere + gravity

Game Logic

Physics adapts based on planet:

Gravity affects jump and movement

Environment affects survival:

Oxygen drains without atmosphere

Toxic planets damage health

Obstacles and power-ups dynamically spawn

Purpose of Project

This project was built to:

Combine creativity + real-world science concepts

Demonstrate interactive UI + game mechanics

Explore 3D rendering in browser

Build a portfolio-level modern project
