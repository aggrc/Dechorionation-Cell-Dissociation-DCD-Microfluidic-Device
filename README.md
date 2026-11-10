# Dechorionation-Cell-Dissociation-DCD-Microfluidic-Device

## Publication
Publication reference:
Mohsen Norouzi, Seyedmajid Hosseini, Sydney Barker, Jose Cibelli, Jack Cushman Koch, William Todd Monroe, Terrence R. Tiersch, Jian Xu, Yue Liu. A 3-D Printed Microfluidic Platform for Flow-Induced Dechorionation, Chorion Filtration, and Cell Dissociation of Zebrafish Embryos. Lab Chip 2026; https://doi.org/10.1039/D6LC00569A

## Overview

This repository provides the design files for the **Dechorionation–Cell Dissociation (DCD) Microfluidic Device**, a high-resolution 3D-printed microfluidic platform developed for integrated zebrafish embryo processing. The device combines mechanical dechorionation, passive chorion filtration, and downstream dissociation of released embryonic contents within a single microfluidic architecture.

This project was developed as part of doctoral research at **Louisiana State University** and contributes to broader efforts in open-hardware development for standardized biological processing tools.

---

## Key Features

- High-resolution 3D-printed microfluidic platform
- Integrated upstream dechorionation zone
- Graded micropost chamber for chorion trapping
- Downstream dissociation and collection of embryo-derived fragments and cells
- Enzyme-free, geometry-driven processing
- Reusable device with post-run cleaning workflow
- Modular design compatible with future automated workflows
- Open-hardware format for sharing, adaptation, and refinement


---


## Device Design and Function

The DCD microfluidic device includes the following functional regions:

- **Inlet channel** for embryo transport
- **Dechorionation zone** with constricted corner subchannels surrounding a central obstruction
- **Downstream transition region**
- **Filtration chamber** with graded tear-drop–shaped micropost arrays
- **Outlet channel** for collection of released fragments and cells

The design separates two sequential processes:

1. **Chorion rupture** in the upstream dechorionation zone
2. **Progressive downstream dissociation** of the released embryo proper within the micropost chamber


---


## Intended Use

This device is intended for research workflows requiring:

- integrated embryo dechorionation and dissociation
- enzyme-free sample preparation
- collection of embryo-derived fragments and cells
- standardized microfluidic processing
- modular integration with downstream steps such as culture, sorting, cryopreservation, and nuclear transfer


---


## Printing and Fabrication Information

### Printer

- *Profluidics 285D resin 3D printer*  
&#x20; CADworks3D, Concord, ON, Canada


### Resin

- **Cyto-Clear™ photopolymer resin**  
&#x20; CADworks3D, Concord, ON, Canada


### Print Settings

- **Layer thickness:** 30 µm
- **Base exposure:** 15 s
- **Subsequent layer exposure:** 0.8 s


### Print Orientation

The device should be printed using the validated orientation that preserves internal channel geometry and micropost resolution while minimizing support-related damage to functional microfluidic features.


---


## Post-Processing and Post-Curing

After printing, the device was post-processed using the following workflow:

1. Flush channels with compressed air
2. Flush with deionized (DI) water
3. Flush with 100% isopropanol
4. Perform a final DI water rinse
5. Clean external surfaces
6. UV-cure for **5 min**
7. Keep the device submerged in DI water during final curing


### UV Curing Equipment

- **LED light cure box:** CureZone MKII  
- **Manufacturer:** Creative CADWorks, Toronto, ON, Canada  
- **Wavelength:** 390–410 nm


---


## Files Included

This repository includes or will include:

- `STL` file
- `3MF` file
- `SolidWorks (SLDPRT)` file
- device image
- `README.md`


---


## Open-Hardware Use

This repository is part of a broader effort to support development of standardized and reproducible open-hardware tools for biological processing and related applications. Users are encouraged to fabricate, evaluate, adapt, and improve the design with appropriate attribution.


---


## Citation

If you use this device or repository, please cite:

**Norouzi M., Hosseini S., Barker S., Cibelli J., Koch J.C., Monroe W.T., Tiersch T.R., Liu Y., Xu J.**  

*A 3-D Printed Microfluidic Platform for Flow-Induced Dechorionation, Chorion Filtration, and Cell Dissociation of Zebrafish Embryos.*  

**XXX**


---


## Acknowledgments

This device was developed at the **Aquatic Germplasm Center of Research Excellence (AGCoRE)** and **Aquatic Germplasm and Genetic Resources Center (AGGRC)** of the **Louisiana State University Agricultural Center**, in collaboration with the **Department of Electrical \& Computer Engineering at Louisiana State University**, the **Department of Biological \& Agricultural Engineering at LSU and LSU Agricultural Center**, and collaborators at **Michigan State University**.

The design was developed by **Mohsen Norouzi** as part of doctoral research at **Louisiana State University** and broader efforts to develop open-hardware tools for biological processing and genetic resource applications.

This study was funded in part by the National Institutes of Health Office of Research Infrastructure Programs (R24-OD028443, R24-OD034058, and R24-OD037797), the National Science Foundation (Award 2229680), and the LSU AgCenter Agriculture Collaborative Research Program. Further assistance was provided by the U.S. Department of Agriculture, National Institute of Food and Agriculture, through Hatch project LAB94420 and award 2024-70007-43549. 

---


