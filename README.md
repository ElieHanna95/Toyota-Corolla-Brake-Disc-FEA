# Toyota Corolla Brake Disc Design Optimization & FEA

Academic engineering project | July 2026

## Overview
A comparative design and finite element analysis (FEA) study of three brake disc configurations for a 2025 Toyota Corolla. The study evaluates structural, thermal, and modal performance to assess the effect of ventilation-hole geometry.

## Designs
1. **Disc 1 — Original reference design:** unmodified baseline.
2. **Disc 2 — Increased ventilation:** greater number of ventilation holes, reduced mass.
3. **Disc 3 — Optimized ventilation:** fewer, strategically arranged ventilation holes than Disc 2 to balance heat dissipation with structural stiffness.

See [`images/`](images/) for extracted design images and screenshots. The final PDF and original PowerPoint are in [`presentation/`](presentation/). The uploaded Autodesk Inventor assemblies and component part files are in [`cad/Autodesk-Inventor/`](cad/Autodesk-Inventor/).

## Methods
- CAD modelling: Autodesk Inventor Professional 2027
- Simulation: ANSYS Mechanical 2026 R1 Student
- Material: Grey cast iron
- Structural pressure cases: 1.5, 3, and 6 MPa
- Thermal cases: 100°C, 200°C, 350°C, and 500°C
- Modal analysis: natural frequencies and vibration modes
- Consistent finite-element mesh (reported global element size: 12 mm)

## Findings
The comparative simulation results favor **Disc 3** for overall balance of structural, thermal, and modal performance. **Disc 2** had the lowest mass and highest factor of safety in the reported comparisons. **Disc 1** served as the reference baseline. See the full presentation for underlying calculations and results.

## Limitations
Numerical simulations only; no manufactured prototype or experimental validation. Wear, braking airflow, and repeated loading were simplified.

## Repository contents
- `presentation/` — Original PowerPoint and final project PDF
- `cad/Autodesk-Inventor/` — Native `.iam` assemblies and `.ipt` component parts (provided source files)
- `images/disc_*.png` — Selected disc design graphics extracted from the presentation
- `images/source-images/` — All embedded images from the presentation (original file names preserved)

> **Note:** These are project presentation assets, not independently validated product designs. Some images may be simulation screenshots or other illustrations. The selected filenames provide a navigation guide based on the presentation's labels; consult the original slides for context.

## Opening the CAD assemblies
Use Autodesk Inventor to open `disc 1.iam`, `disc 2.iam` and `disc 3.iam`. Keep all `.iam` and `.ipt` files together in their current folder to preserve file references. Some assembly links may require manual resolution if components not included in the uploaded set were used.

## Contributors
Elie Sami Hanna, Karim Ahmed, Karim Mohamed Abdeldayem, Youssef Elghareeb Mahmoud, El Azaby Ahmed, and Ahmed Aly (as credited in the final report).
