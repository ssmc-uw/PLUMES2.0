# PLUMES2.0

## Introduction
PLUMES2.0 is a revived version of the Visual Plumes model that was developed by Dr. Walter Frick at USEPA. PLUMES2.0 and Visual Plumes are codes that compute initial and far-field dilution of buoyant discharges into receiving fresh or marine  environments. PLUMES2.0 is a Fortran-based implementation of the UM3 code. Visual Plumes was a Windows-based guided user interface for UM3 that superseded the DOS-based PLUMES (Baumgartner, Frick, and Roberts, 1994) mixing zone modeling system. However, following the retirement of Dr. Frick, the user community lost access to Visual Plumes, and the  model is considered a legacy tool and is no longer compatible with newer Windows versions. The PLUMES2.0 results from an initiative to re-develop the UM3 program with a GUI and added features for robust user interactions compatible with modern Windows operating systems. Plumes2.0 may be used by NPDES permit writers and wastewater engineers to simulate submerged water jets and plumes in support of mixing zone analyses, Total Maximum Daily Loads (TMDLs), and other water quality applications. The latest version of PLUMES2.0v1 can perform calculations for dissolved oxygen (DO) and carbonate chemistry conditions of the water column.
 
## Model Features
<img width="716" height="506" alt="plumes2 0_1" src="https://github.com/user-attachments/assets/ba86bf24-0676-4bde-aa5a-1a2247a5df20" />

The model uses Lagrangian Control Volume (LCV) to compute the near-field plume fate similar to UM3, and the fate of the plume far-field is evaluated using Brooks principles (Brooks, 1960). More specifically model features include:
- Near-field dilution and other plume parameters
- Far-field dilution and other plume parameters
- Integrated plume merging 
- Graphical model outputs
- Independent far-field calculation

Note: Please report the bugs and upgrades preferred by the user community for future releases to ssmc.uw@gmail.com
