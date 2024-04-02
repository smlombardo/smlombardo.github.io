---
title: "Biophysical Larval Dispersal Models"
excerpt: "The larval dispersal models that I programmed and visualized here are from my publication on [Bonefish larval dispersal](https://journals.plos.org/plosone/article?id=10.1371/journal.pone.0276528). Modeling and visualizing in Ichthyop, R, and ArcGIS allow for insights into population connectivity, larval development environments, and spatial management assessments. They also make for compelling visuals!<br/><img src='/images/FullDispersalSim.png'>"
collection: portfolio
---
<video controls="" width="800" height="500" muted="" loop="" autoplay="">
<source src='https://github.com/smlombardo/smlombardo.github.io/assets/163476157/cca0ca27-f951-4b6d-918a-60f0a4054de5'>
</video>
Dispersal is the wholistic measure of connectivity, bridging spawning and recruitment events through the inclusion of transport and settlement. I programmed dispersal simulations in the program Ichthyop using the Navy Coastal Ocean Model (NCOM AmSeas) as the hydrodynamic backbone, created the grid netcdf in MATLAB with ROMS, created and adjusted the larval settlement grid (nursery settlements) in ArcGIS, managed the model program files (xml) in R, and analyzed and produced visuals in R and Ichthyop itself.

<img src='/images/FullDispersalSim.png'>
Red and orange pixels depict the highest frequency and density of larval dispersal paths. Larval densities per pixel are shown for every timestep of all 100 simulation runs of the observed 2019 Bonefish spawning event in Abaco, The Bahamas.

<img src='/images/OceanConditions.jpg'>
Ocean conditions during the 2019 Bonefish spawn on Abaco, The Bahamas. Visualized using IDV.
