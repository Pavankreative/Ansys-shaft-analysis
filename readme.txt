# Shaft Torsion Structural Analysis (ANSYS)

This project analyzes torsional stress in a solid steel shaft using ANSYS Workbench Static Structural simulation.

## Objective
Validate analytical torsion stress equations using finite element analysis.

## Simulation Setup
Software: ANSYS Mechanical 2025 R2 Student

Material: Structural Steel  
Shaft diameter: 12 mm  
Torque applied: 3 N·m

Boundary Conditions:
- Fixed support on one end
- Moment applied on opposite end

## Results
Maximum von-Mises stress: ~16 MPa  
Analytical torsion stress: 15.3 MPa  
Error: ≈ 4.3 %

Safety Factor ≈ 15.6

## Figures
(Insert mesh and stress images)

## Conclusion
FEA results closely match analytical calculations, validating the simulation setup.