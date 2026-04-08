# DIY Wind Tunnel: Aerofoil Performance Analysis
**Project Overview:** A custom-built wind tunnel designed to visualize airflow and analyze how different wing geometries (aerofoils) affect aerodynamic efficiency.

## 🛠️ The Build (Mechanical & Electrical)
This wasn't just a box with a fan. To get professional-grade results, I engineered a smoke-generation system:
* **Airflow Source:** Dual computer fan configuration for consistent velocity.
* **Visualization:** Built a thermal smoke generator using **Nichrome wire** and **Vegetable Glycerin**. 
* **Power:** Powered by a Lithium-ion battery system with an alligator-clip bridge for controlled heating of the wire.
* **Laminar Flow:** Used a straw-grid array to straighten air intake and reduce turbulence before it hit the testing chamber.

## 🧪 The Experiment
The goal was to test five different wing profiles to see how "blocky" vs. "smooth" geometries impacted lift and drag.

### Wing Profiles Tested:
1. **Teardrop (Control):** The classic aerodynamic shape.
2. **Triangular:** High-angle edges.
3. **Flat:** Low profile but sharp edges.
4. **Oval:** Rounded but thick.
5. **Rectangular:** Maximum surface area, high drag.

### Scoring Metrics (1-10 Scale):
* **Laminar Flow:** How smooth the smoke moved over the wing.
* **Vortex Formation:** Visualizing air "swirls" at the wingtips (drag).
* **Drag Resistance:** Stability of the wing under high wind speeds.

## 📊 Results Summary
| Shape | Drag Rating | Laminar Flow | Vortex Score | Total (Out of 30) |
| :--- | :--- | :--- | :--- | :--- |
| **Teardrop** | 8/10 | 10/10 | 8/10 | **26** |
| **Flat** | 8/10 | 10/10 | 7/10 | **25** |
| **Triangular** | 8/10 | 6/10 | 1/10 | **15** |
| **Circle** | 4/10 | 2/10 | 3/10 | **9** |
| **Rectangle** | 1/10 | 0/10 | 0/10 | **1** |

**Conclusion:** The data confirmed my hypothesis. Smoother, tapered shapes like the **Teardrop** allowed air to re-converge behind the wing without creating the massive vacuum (vortexes) seen in the rectangular and triangular models.

## 🔧 Engineering Refinement (Lessons Learned)
If I were to rebuild this for a professional lab:
1. **3D Printing:** I would 3D print the aerofoils to ensure perfect symmetry and surface finish, removing the "handmade" variability.
2. **Standardized Rating:** I used a "Mode" average from multiple human raters to reduce bias, but using a digital force sensor to measure actual Newtons of drag would be the next step.
