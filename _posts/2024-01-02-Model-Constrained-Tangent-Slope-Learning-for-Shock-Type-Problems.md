---
layout: post
mathjax: true
title: "mcTangent Learning Slope Approach for Shock Type Problems"
# permalink: /research/mctangent_extension
---

## Major Activities 
This work aims to solve shock-type problems with machine learning.

<p align="center">
<img src="/assets/figures/hainguyen/mctangent_0.png">
<figcaption><b>Figure 1:</b> The schematic of mcTangent network architecture for S = 1.</figcaption>
</p>

## Significant Results
### 1. Euler equation configurations 6, 12

<p align="center">
<img src="/assets/figures/hainguyen/3D_Euler_configuration6.gif">
<figcaption><b>Figure 2: (Euler configuration 6)</b> predictions by mcTangent approach. The test data and training data are generated from the same configuration 6.</figcaption>
</p>

<p align="center">
<img src="/assets/figures/hainguyen/3D_Euler_configuration12.gif">
<figcaption><b>Figure 3: (Euler configuration 12) </b> predictions by mcTangent approach. The test data configuration 12 and training data are generated from the same configuration 6</figcaption>
</p>

### Problem 2: Double Mach Reflection


### Problem 2. Forward facing corner 

- Training data is generated from Model 1 with time interval $[0,1]$
- Test data is generated from Model 1 and Model 2 for time interval $[0, 4]$


<p align="center">
<img src="/assets/figures/hainguyen/2D_Euler_forth_models.png">
<figcaption><b>Figure : (Forward-facing corner) </b> Model 1 and Model 2.</figcaption>
</p>

<p align="center">
<img src="/assets/figures/hainguyen/2D_Euler_forth_same_mesh.gif">
<figcaption><b>Figure 4: (Forward-facing corner)</b> predictions by mcTangent approach. The test data and training data are generated from the same configuration.</figcaption>
</p>

<p align="center">
<img src="/assets/figures/hainguyen/2D_Euler_forth_different_mesh.gif">
<figcaption><b>Figure 5: (Forward-facing corner)</b> predictions by mcTangent approach. The test data and training data are generated from the different configurations.</figcaption>
</p>


### 3. ScramJet

- Training data is generated from Model 1 with time interval $[0,1.6]s$
- Test data is generated from Model 1 and Model 2 for time interval $[0, 6]s$

<p align="center">
<img src="/assets/figures/hainguyen/2D_Euler_scram_jet_models.png">
<figcaption><b>Figure : (ScramJet) </b> Model 1 and Model 2.</figcaption>
</p>

<p align="center">
<img src="/assets/figures/hainguyen/2D_Euler_scram_jet_same_mesh_Mach3.gif">
<figcaption><b>Figure 6: (ScramJet) </b> predictions by mcTangent approach. The test data and training data are generated from the same configuration.</figcaption>
</p>

<p align="center">
<img src="/assets/figures/hainguyen/2D_Euler_scram_jet_different_mesh_Mach3.gif">
<figcaption><b>Figure 7: (ScramJet) </b> predictions by mcTangent approach. The test data and training data are generated from the different configurations </figcaption>
</p>


### 4. Airfoil

- Training data is generated from Airfoil AoA $3^o$ and Mach = 0.8, in time interval $[0,1.2]s$
- Test data is generated from Airfoil AoA $3^o$ and Mach = 0.8 adn Airfoil AoA $5^o$ and Mach = 1.2 for time interval $[0, 7.5]s$

<p align="center">
<img src="/assets/figures/hainguyen/2D_Euler_Airfoil_model.png">
<figcaption><b>Figure 8: (Airfoil)</b> Airfoil configuration AoA-3.</figcaption>
</p>

<p align="center">
<img src="/assets/figures/hainguyen/2D_Euler_Airfoil_Mach08_AoA3.gif">
<figcaption><b>Figure 8: (Airfoil)</b> predictions by mcTangent approach. The test data and training data are generated from the same configuration, M = 0.8, AoA = 3.</figcaption>
</p>

<p align="center">
<img src="/assets/figures/hainguyen/2D_Euler_Airfoil_Mach1p2_AoA5.gif">
<figcaption><b>Figure 9: (Airfoil) </b> predictions by mcTangent approach. The test data (M=1.2, AoA = 5) and training data are generated from the different configuration</figcaption>
</p>

