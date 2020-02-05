# A Hitchhiker’s Guide to Mesh Generation from Medical Images

#### by Alexandra K. Diem (@akdiem)

The scope of this tutorial is to serve as a visual guide for anyone getting into medical image segmentation for the purpose of creating a finite element mesh. It has been developed in the hope to streamline the workflow used to handle medical image data at Simula. It covers image segmentation and mesh optimisation using only software that is freely available and works on any operating system. The software packages used in this tutorial are:

* [ITK-SNAP](http://www.itksnap.org/) for segmentation of medical images
* [Autodesk Meshmixer](http://www.meshmixer.com/) for optimisation of surface meshes
* [FreeCAD](https://www.freecadweb.org/) for generating solid parts from surface meshes and boolean operations on solid parts
* [Gmsh](http://gmsh.info/) for creating finite element volume meshes suitable for FEniCS


### Contents

1. Semi-automatic image segmentation
2. Clean-up of surface meshes and optimisation
3. Conversion of surface meshes to solid parts
4. Generation of finite element volume meshes