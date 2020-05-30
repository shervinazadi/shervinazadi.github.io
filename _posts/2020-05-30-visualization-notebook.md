---
layout: post
title: "Houdini Asset: Call Python"
description: "Running any python code with any environment from within Houdini"
thumb_image: "documentation/sample-image.jpg"
tags: [gss, python, houdini, computation, interface]
---

This houdini asset allows the user to choose a python file and choose a specific python environment and run the python script with the selected environment. This allows for separation of environments through a workflow and also solves the problem of importing libraries in houdini completely. This asset is compatible with conda environments as well.

This module uses the `sqlite3` standard library to replicate the Houdini's geo database and passes the address to the subprocess. The subprocess will read the database, execute the computational process and saves the data into the database. You can decide to keep or delete the database for trouble shooting purposes.

## GSS-Lab

This project is part of the setup for Generative Sciences & Systems Lab Setup. It is currently being developed by [Shervin Azadi](https://github.com/shervinazadi) and [Pirouz Nouria](https://github.com/Pirouz-Nourian) at GSS-Lab, Department of Architectural Engineering and Technology, at TU Delft.
