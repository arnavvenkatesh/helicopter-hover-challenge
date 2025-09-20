# Helicopter Hover Challenge — Earth vs. Mars

## Overview
This project explores the physics of helicopter hovering on Earth and Mars. It computes the minimum rotor speeds required for helicopters and small drones to hover, and compares the results with NASA’s Ingenuity drone on Mars. The project was completed as a **take-home assignment for the IIT Madras Online Aerospace Engineering Course – Fundamentals of Aerospace**, with additional analysis and reporting performed independently.

## Objectives
- Understand why hovering is more challenging on Mars despite weaker gravity.
- Compute rotor speeds (rad/s and rpm) for different masses on Earth and Mars.
- Compare theoretical results with NASA’s Ingenuity drone.
- Apply Newton’s laws to explain rotorcraft behavior (tail rotor, autorotation feasibility).

## Repository Structure
helicopter-hover-challenge/
├─ README.md # This file
├─ LICENSE # MIT License for code
├─ notebooks/
│ └─ hover_analysis.ipynb # Main Jupyter notebook with code
├─ report.pdf #  Report with results, analysis and discussion

## Instructions
1. Clone or download the repository.
2. Open `notebooks/hover_analysis.ipynb` in Jupyter Notebook or Jupyter Lab.
3. Run all cells to compute rotor speeds for different helicopter/drone masses.
4. Results include rotor angular velocity (rad/s), rpm, and tables for Earth, Mars, and a comparison with NASA’s Ingenuity.
   

## Notes
The calculations use a simplified thrust model with constant thrust coefficient (C_T = 0.008) and two rotors.
Real-world rotorcraft include aerodynamic effects, induced velocity, and safety/control margins, which can slightly increase practical rotor speeds.
Hovering is much harder on Mars due to its extremely thin atmosphere.

## License
Code (notebook) is released under the MIT License.

## Author
Arnav Venkatesh | Grade 11 | NHVPS Bangalore
Based on a take-home project for the IIT Madras Online Aerospace Engineering Course – Fundamentals of Aerospace.
