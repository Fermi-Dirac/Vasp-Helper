#VASP Helper

Written by Christopher Buurma at the University of Illinois at Chicago

Code used for VASP calculations and related to publications by C. Buurma including thesis work. Some functions exist to integrate with Carbon. Feel free to use this code as needed, only cite the source as my thesis:

[*C. Buurma, “Application of ab-initio Methods to Grain Boundaries and Point Defects for Poly - CdTe Solar Cells,” University of Illinois at Chicago, 2015.*] (https://doi.org/10.13140/RG.2.1.2848.2724)

## Main functions in this project:
- Vasp Helper - Wrapper for VASPv4 and VASPv5 calculations with some functions written for Carbon
- Defect Buddy - Tool to compute defect formation energies, chemical potentials, and more from resulting VASP calculations.
- Grain Boundary Genie - Tool to create Grain Boundaries directly from the GB degrees of Freedom using the overlattice technique outlined in my thesis
- Structure Handler - Tool to manipulate atomic structures, add defects, plot and render in 3D and more.

Some code being ported to Python for use in ASE...
