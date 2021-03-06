# A Hitchhiker’s Guide to Mesh Generation from Medical Images

#### by Alexandra K. Diem [@akdiem](https://github.com/akdiem)

![Segmented and post-processes heart geometry from CT images](figures/heart_segmented.png "Segmented and post-processes heart geometry from CT images")

The scope of this tutorial is to serve as a visual guide for anyone getting into medical image segmentation for the purpose of creating a finite element mesh. It has been developed in the hope to streamline the workflow used to handle medical image data at Simula. It covers image segmentation and mesh optimisation using only software that is freely available and works on any operating system. The software packages used in this tutorial are:

* [ITK-SNAP](http://www.itksnap.org/) for segmentation of medical images
* [Autodesk Meshmixer](http://www.meshmixer.com/) for optimisation of surface meshes
* [FreeCAD](https://www.freecadweb.org/) for generating solid parts from surface meshes and boolean operations on solid parts
* [Gmsh](http://gmsh.info/) for creating finite element volume meshes suitable for FEniCS


### Contents

1. [Semi-automatic image segmentation](itksnap_guide.md)
2. [Clean-up of surface meshes and optimisation](meshmixer_guide.md)
3. [Conversion of surface meshes to solid parts](freecad_guide.md)
4. Generation of finite element volume meshes