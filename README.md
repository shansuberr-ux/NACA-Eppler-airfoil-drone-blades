# Drone Propeller Blade Design

Parametric propeller blade design project covering multiple diameter/pitch configurations for
multirotor UAV applications, built in SolidWorks from airfoil coordinate data (NACA/Eppler
profiles) with spanwise chord and pitch distribution tables.

## Contents
| File | Description |
|---|---|
| `NACA 2310` | Propeller blade variant — [diameter/pitch spec] |
| `NACA 2312` | Propeller blade variant — [diameter/pitch spec] |
| `NACA 2412` | Propeller blade variant — [diameter/pitch spec] |
| `NACA 4412` | Propeller blade variant — [diameter/pitch spec] |
| `E216` | Propeller blade variant — Eppler E216 airfoil-based design |

## Design Approach
- Generated airfoil coordinate files (NACA/Eppler series) and lofted spanwise chord/pitch
  tables to build 3D blade geometry
- Iterated on multiple diameter/pitch combinations to compare thrust/efficiency tradeoffs for
  different multirotor payload and endurance targets
- Resolved geometry issues (self-intersection at blade root/tip) during CAD import and lofting
- [Optional: add CFD validation details if you ran Fluent analysis on these]

## Tools
SolidWorks, airfoil coordinate generation (NACA/Eppler profiles)
