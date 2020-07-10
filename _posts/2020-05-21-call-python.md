---
layout: post
title: "Houdini Asset: Call Python"
description: "Running any python code with any environment from within Houdini"
thumb_image: "documentation/sample-image.png"
tags: [gss, python, houdini, interface, development]
---

Houdini is a great software not only for VFX artists but anyone who's work is intertwined with computational geometry. Houdini supports python out of the box, however there are restirictions in terms of the environment that your python code is being executed in. These restrictions become problematic when your development environment needs specific python version, certain libraries or even installation of in-development libraries. To overcome these restrictions and also benefit from the underlying geometrical database of Houdini, we have developed the [Call Python houdini asset](https://github.com/shervinazadi/GSS_Call_Python), at GSS-Lab.

[This houdini asset](https://github.com/shervinazadi/GSS_Call_Python) allows the user to choose a python file and choose a specific python environment and execute the python script within the selected environment. This allows for separation of environments through a workflow and also solves the problem of importing libraries in houdini completely. This module utilises the `sqlite3` standard library to replicate the Houdini's geo-database and passes the address to the subprocess. The subprocess will read the database, execute the computational process and saves the data into the database. You can decide to keep or delete the database for trouble shooting purposes.

[GSS_Call_Python GitHub](https://github.com/shervinazadi/GSS_Call_Python)
[Download Latest Version](https://github.com/shervinazadi/GSS_Call_Python)

## GSS-Lab

This project is part of the [Generative Sciences & Systems Lab Setup](https://github.com/shervinazadi/GSS_PyHou_Setup). It is currently being developed by [Shervin Azadi](https://github.com/shervinazadi) and [Pirouz Nouria](https://github.com/Pirouz-Nourian) at GSS-Lab, Department of Architectural Engineering and Technology, at TU Delft.
