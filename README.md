# EQlib Examples

[![Download](https://img.shields.io/badge/Download-Examples-orange?style=for-the-badge)](https://github.com/oberbichler/EQlib-Examples/raw/main/examples.zip)

**EQlib** (like *equilib*rium) is a [Grasshopper plugin](https://www.rhino3d.com/features/#grasshopper) for interactive form finding. It supports **discrete geometries e.g., lines and meshes (classic FEM)** as well as **smooth freeforms e.g., NURBS and SubDs\* (IGA)**. Form finding can be done using **force-density method**, **updated reference strategy (URS)** or by using **elastic elements**. The general implementation allows the combination of different strategies within a single model. EQlib is implemented in pure C# which allows to interact with the simulation within Grasshopper.

The plugin is a side project of my research at the [Chair of Strucutral Analysis](https://www.cee.ed.tum.de/en/st/home/). It aims to demonstrate how finite element method can be interactively integrated into CAD programs for form finding. \*The project is work in progress.

## Installation

EQlib can be installed using the Rhino package manager.

1. Open Rhino
2. Open the package manager with the Rhino command `_PackageManager` and search for "EQlib"
3. Install "EQlib" **AND** "EQlib-MKL"
4. Restart Rhino

Now you can [download](https://github.com/oberbichler/EQlib-Examples/raw/main/examples.zip) and open the examples in Grasshopper.
