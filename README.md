# Drone Propeller Blade Design

Parametric propeller blade design project covering multiple diameter/pitch configurations for
multirotor UAV applications, built in SolidWorks from airfoil coordinate data (NACA/Eppler
profiles) with spanwise chord and pitch distribution tables.

## Contents
| File | Image | Description |
|---|---|---|
| `NACA2310` | ![2310](https://github.com/shansuberr-ux/NACA-Eppler-airfoil-drone-blades/blob/main/2310.PNG) | Propeller blade variant — [diameter/pitch spec] |
| `NACA2312` | ![2312]([./images/2312.png](https://github.com/shansuberr-ux/NACA-Eppler-airfoil-drone-blades/blob/main/2312.PNG)) | Propeller blade variant — [diameter/pitch spec] |
| `NACA2412` | ![2412]([./images/2412.png](https://github.com/shansuberr-ux/NACA-Eppler-airfoil-drone-blades/blob/main/2412%20PROPELLOR.PNG)) | Propeller blade variant — [diameter/pitch spec] |
| `NACA4412` | ![4412]([./images/4412.png](https://github.com/shansuberr-ux/NACA-Eppler-airfoil-drone-blades/blob/main/4412.PNG)) | Propeller blade variant — [diameter/pitch spec] |
| `E216` | ![e216]([./images/e216.png](https://github.com/shansuberr-ux/NACA-Eppler-airfoil-drone-blades/blob/main/e216.PNG)) | Propeller blade variant — Eppler E216 airfoil-based design |


## Design Approach
- Generated airfoil coordinate files (NACA/Eppler series) and lofted spanwise chord/pitch
  tables to build 3D blade geometry
- Iterated on multiple diameter/pitch combinations to compare thrust/efficiency tradeoffs for
  different multirotor payload and endurance targets
- Resolved geometry issues (self-intersection at blade root/tip) during CAD import and lofting
- [Optional: add CFD validation details if you ran Fluent analysis on these]

## Tools
SolidWorks, airfoil coordinate generation (NACA/Eppler profiles)
