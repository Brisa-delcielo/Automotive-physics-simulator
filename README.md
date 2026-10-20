# Automotive Physics Simulator

An interactive, web-based automotive physics simulator built with HTML5, CSS3, and JavaScript. It calculates and visualizes real-time vehicle dynamics, engine metrics, and performance forces based on user-defined inputs.

## Features

- **Real-time Calculations:** Instantly computes power-to-weight ratio, braking distance, aerodynamic drag, and traction force.
- **Dynamic Animation:** Visualizes engine components (crankshaft, piston, and connecting rod) moving in sync with vehicle speed and RPM.
- **Interactive Controls:** Adjust power, mass, speed, and friction coefficient on the fly.
- **Responsive UI:** Clean, modern, monospace terminal-style interface.

## Physics Formulas Used

- **Power-to-Weight Ratio:** $R = \frac{m}{P}$
- **Braking Distance:** $d = \frac{v^2}{2 \cdot \mu \cdot g}$
- **Aerodynamic Drag:** $F_d = 0.5 \cdot \rho \cdot C_x \cdot A \cdot v^2$
- **Traction Force:** $F_t = \frac{P_{watts}}{v_{ms}}$ (adhesion-limited)

## How to Run

1. Clone or download this repository.
2. Open the `index.html` file in any modern web browser.

## Technologies Used

- HTML5
- CSS3 (Grid, Flexbox)
- JavaScript (HTML5 Canvas & Math operations)
