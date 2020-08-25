---
layout: post
title: "topoGenesis"
description: "Python Package of Computational Topology for Generative Systems and Sciences"
thumb_image: "documentation/sample-image.png"
tags: [research, spatial, math, generative, python, gss, development]
---

[topoGenesis](https://github.com/shervinazadi/topoGenesis) is an open-source python package that provides topological structures and functions for Generative Systems and Sciences.

## Vision

topoGenesis aims to utilize the vast functionalities of fields (mathematical objects) in generative systems and sciences. Therefore it seeks to:
1. offer basic mathematical functionalities on field data models
2. offer functionalities of computational topology on top of the field structures
3. facilitate the conversion between mesh-based data models and field data models. 
4. facilitate field simulations, whether governed by differential equations, spectral models or based on computational models (ABM)
5. construct a bridge between spatial data models and tensor data structures to facilitate the utilization of the latest artificial intelligence models

## Structure 

* Mesh to Field: Rasterization
    * Point Cloud Regularization
    * Line Network Voxelation
    * Mesh Surface Voxelation
    * Signed Distance Field
* Field to Mesh: Isosurface
    * Boolean Marching Cubes
    * Marching Cubes
    * Surface Nets
* Local Computation
    * Stencil / Kernels
        * von Neumann neighbourhood
        * Moore neighbourhood
        * Cube neighbourhood
        * Custom neighbourhoods
    * Universal Functions & Mathematical Operators (Numerical)
* Field Simulations (Vectorized)
    * Dynamic Systems (based on Differential Equations)
    * Agent-Based Modeling
    * Cellular Automata

## GSS-Lab

This project is currently being developed by [Shervin Azadi](https://github.com/shervinazadi) and [Pirouz Nouria](https://github.com/Pirouz-Nourian) at GSS-Lab, Department of Architectural Engineering and Technology, at TU Delft.

