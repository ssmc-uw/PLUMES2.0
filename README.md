# PLUMES2.0

## Introduction
PLUMES2.0 is a revived version of the Visual Plumes model that was developed by Dr. Walter Frick at USEPA. PLUMES2.0 and Visual Plumes are codes that compute initial and far-field dilution of buoyant discharges into receiving fresh or marine  environments. PLUMES2.0 is a Fortran-based implementation of the UM3 code. Visual Plumes was a Windows-based guided user interface for UM3 that superseded the DOS-based PLUMES (Baumgartner, Frick, and Roberts, 1994) mixing zone modeling system. However, following the retirement of Dr. Frick, the user community lost access to Visual Plumes, and the  model is considered a legacy tool and is no longer compatible with newer Windows versions. The PLUMES2.0 results from an initiative to re-develop the UM3 program with a GUI and added features for robust user interactions compatible with modern Windows operating systems. Plumes2.0 may be used by NPDES permit writers and wastewater engineers to simulate submerged water jets and plumes in support of mixing zone analyses, Total Maximum Daily Loads (TMDLs), and other water quality applications.
 
## Model Features
![Image](https://github.com/user-attachments/assets/68934e90-eccf-4ea7-a915-64f303633539)
The model uses Lagrangian Control Volume (LCV) to compute the near-field plume fate similar to UM3, and the fate of plume far-field is evaluated using Brooks principles (Brooks, 1960). More specifically model features includes:
- Near-field dilution and other plume parameters
- Far-field dilution and other plume parameters
- Integrated plume merging 
- Graphical model ouputs
- Independent far-field calculation

