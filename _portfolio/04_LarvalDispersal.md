---
title: "Biophysical Larval Dispersal Models"
excerpt: "The larval dispersal models that I programmed and visualized here are from my publication on [Bonefish larval dispersal](https://journals.plos.org/plosone/article?id=10.1371/journal.pone.0276528). Modeling and visualizing in Ichthyop, R, and ArcGIS make for compelling visual assessments of dispersal patterns!<br/><img src='/images/FullDispersalSim.png'>"
collection: portfolio
---
Larval dispersal - the process inclusive of transport from spawn location by physical ocean processes (i.e., currents) and behavior (i.e., swimming, diel vertical migration, etc.) through the settlement phase at nursery habitats. I programmed dispersal simulations in the program Ichthyop using the Navy Coastal Ocean Model (NCOM AmSeas) as the hydrodynamic backbone, created the grid netcdf in MATLAB with ROMS, created and adjusted the larval settlement grid (nursery settlements) in ArcGIS, managed the model program files (xml) in R, and analyzed and produced visuals in R and Ichtyop itself.

<img src='/images/FullDispersalSim.png'>
Red and orange pixels depict the highest frequency and density of larval dispersal paths. Larval densities per pixel for every timestep of all 100 simulation runs of the observed 2019 Bonefish spawning event in Abaco, The Bahamas.

<img src='/images/OceanConditions.jpg'>
Ocean conditions during the 2019 Bonefish spawn on Abaco, The Bahamas. Visualized using IDV.
