---
layout: project
title: Mechanical Battery Pack Enclosure for Hyperloop
description: Design of a Wind Turbine Blade to Generate Maximum Power
technologies: [SolidWorks, ANSYS]
image: /assets/images/battery.pack.png
---


# Executive Summary

## 1. Desired Functions of the Design

The Battery Pack Mechanical Enclosure is designed to securely house, protect, and structurally support approximately 100 lithium-based battery cells used to power the Hyperloop pod. Its primary functions are to:

1. Mechanically restrain the battery modules under acceleration and vibration loads  
2. Provide a safe and electrically insulated environment for high-voltage components  
3. Maintain accessibility for inspection and maintenance  
4. Provide a mounting architecture for the Battery Management System (BMS), ensuring proper monitoring and health management of the cells during pod operation  

## 2. Design Constraints

The design must satisfy several mechanical, safety, and system-integration constraints:

- Withstand launch, braking, and vibration loads during pod operation  
- Prevent any movement of battery modules within the enclosure  
- Use non-conductive and thermally stable materials to reduce electrical hazards  
- Provide adequate ventilation while preventing foreign object intrusion  
- Fit within the designated volume of the pod chassis near the center of mass  
- Allow easy access to battery cells and BMS  
- Meet Hyperloop team safety protocols for high-voltage components  

## 3. Performance Objectives

Performance objectives focused on structural reliability, safety, and accessibility. Acrylic structural components were designed such that deflection under expected loading remained below 1-2 mm to prevent internal shifting. A strict mass target of 10 kg was imposed to minimize overall pod mass contribution.

Material integrity was required up to operating temperatures of 60 degrees Celsius. Maintenance accessibility was prioritized such that the BMS and module stack could be accessed in under 60 seconds using a hinged top panel and modular assembly layout.

## 4. Alternative Design Concepts

Several enclosure concepts were considered, including:

- A fully welded aluminum enclosure (high strength, poor modifiability)
- Sheet-metal bent enclosures (improved manufacturability, excessive mass)
- Polycarbonate snap-fit enclosure (impact resistance, manufacturing complexity)

A hybrid acrylic and aluminum extrusion solution was selected for its balance of structural strength, electrical insulation, manufacturability, and ease of iteration.

## 5. Design Selection Analysis

The final concept was selected using structural evaluations, material comparisons, manufacturability assessments, and integration checks. Acrylic provided sufficient stiffness while remaining electrically insulating. Aluminum extrusion enabled modular assembly and rapid iteration using in-house fabrication resources.

User-access simulations confirmed that the hinged top enclosure offered the fastest and safest maintenance access.

## 6. Industry and Safety Standards

The design was informed by principles from UL 2054 and UL 2580, guiding decisions on electrical isolation, mechanical robustness, and high-voltage handling. Best practices from EV and aerospace battery systems influenced module restraint, spacing, and enclosure transparency.

## 7. Coursework Applied

- **MAE 2250 - Mechanical Synthesis:** CAD modeling and modular enclosure architecture  
- **MAE 3270 - Mechanics of Materials:** Stress, strain, and deflection analysis  
- **MAE 3240 - Heat Transfer:** Battery heat generation and natural convection analysis  
- **MAE 3780 - Mechatronics:** BMS integration and wiring management  
- **ENGRD 2020 - Statics:** Reaction force and load path analysis  

## 8. Design Evaluation

The final design met all functional and performance objectives. Battery modules were precisely constrained, vertical motion was eliminated via a raised platform, and the hinged enclosure enabled safe and rapid access. Compared to commercial solutions, the design offered comparable mechanical performance while remaining significantly more customizable and manufacturable within a student engineering environment.

## 9. Societal and Environmental Impact

The enclosure improves safety and reliability in student-developed high-voltage systems by reducing electrical short and thermal runaway risks. Recyclable materials and modular reuse support sustainable engineering practices. The low-cost construction enables experimentation without excessive financial burden.

## 10. Final Design Format

Deliverables included a complete CAD assembly, detailed subassemblies, and a full physical prototype constructed from acrylic panels and aluminum extrusion.

## 11. Individual Contribution

This Independent Senior Design project was completed individually. As Structures Subteam Lead, I initiated the enclosure concept, coordinated subassembly development, completed the top-level assembly, and ensured compliance with structural, safety, and integration requirements.

---

# Final Design Report

## Overview

The Battery Pack Mechanical Enclosure supports and protects the Hyperloop pod's primary energy storage system. Approximately 100 lithium iron phosphate battery cells are housed near the system center of mass to minimize dynamic effects. The design prioritizes mechanical retention, electrical safety, passive thermal management, and maintenance accessibility.

## Battery Pack Design

Battery cells are grouped into modules of 10 and 12 cells and constrained using a laser-cut acrylic holder consisting of a top cutout plate and bottom support plate. The top plate prevents lateral translation while vertical spacing promotes airflow and prevents toppling under inertial loads.

![Battery Pack Holder CAD](images/battery pack holder.png)
*Figure 1: Battery Pack Holder*

## Battery Pack Enclosure and Structural Integration

An upper acrylic enclosure is supported by a 20x20 mm aluminum extrusion frame. Structural loads are transferred into the pod chassis while maintaining electrical isolation and modularity.

![Battery Pack Enclosure CAD](images/battery enclosure.png)
*Figure 2: Battery Pack Enclosure*

## Battery Management System Mounting

The BMS is mounted above the battery enclosure on a 0.25-inch acrylic plate supported by aluminum extrusion. Hinges allow the top enclosure to open for direct access.

## Thermal Analysis

Each battery cell has a mass of 75 g, yielding a total mass:

\[
m = 75 \times 100 = 7.5 \text{ kg}
\]

Total resistance:

\[
R_{total} = 100 \times 6 \times 10^{-3} = 0.6 \ \Omega
\]

Heat generation:

\[
P = I^2 R = (30)^2 \times 0.6 = 540 \text{ W}
\]

Temperature rise rate:

\[
\frac{dT}{dt} = \frac{540}{7.5 \times 825} \approx 0.087^\circ C/s
\]

Natural convection and auxiliary fans mitigate thermal accumulation.

![Thermal and Fan Placement CAD](images/battery.pack.png)
*Figure 3: Fan Locations in Enclosure*

## Material Analysis

Acrylic provides electrical insulation, low mass, and laser-cut compatibility. Aluminum extrusion offers high stiffness-to-weight ratio, modularity, and ease of assembly. Steel fasteners and spacers provide reliable structural connections.

## Manufacturability and Assembly

All components were designed for in-house fabrication using laser cutting and standard extrusion hardware. The modular assembly allows for rapid iteration and replacement.

## System Readiness and Validation

CAD fit checks and preliminary structural evaluations confirmed compatibility with the pod chassis. Future work includes electrical integration and operational testing.

---

# Appendix

![Side View CAD](images/battery pack side.png)
*Figure 4: Side View of Full Enclosure*

![Prototype Open](images/bp open.png)
*Figure 5: Prototype (Opened)*

![Prototype Closed](images/bp close.png)
*Figure 6: Prototype (Closed)*












## Figure 1: Final Blade Geometry (CAD)

![CAD rendering of the final wind turbine blade showing spanwise twist and chord variation]({{ site.baseurl }}/assets/images/blade_cad.png)

*Figure 1. CAD model of the optimized wind turbine blade designed using blade element theory and structural constraints.*

---

## Figure 2: Experimental Power Curves

![Power curves measured at multiple wind speeds]({{ site.baseurl }}/assets/images/power_curves.png)

*Figure 2. Mechanical power output as a function of rotational speed for multiple wind tunnel fan speeds near the design wind velocity.*

---

### Figure 3: Final Blade Design
![Wind turbine 3D printed pieces]({{ site.baseurl }}/assets/images/final_design.png)

*Figure 3. Final design of the 3d-printed wind turbine blade used for performance testing.*

