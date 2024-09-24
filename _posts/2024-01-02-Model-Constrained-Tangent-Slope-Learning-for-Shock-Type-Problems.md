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
### Problem 1. Euler equation configurations 6, 12

- Training data is generated from Euler configuration 6 with time interval $[0,0.16]$
- Test data is generated from Euler configuration 6 for time interval $[0, 0.8]$ and Euler configuration 12 for time interval $[0, 0.25]$

<p align="center">
<img src="/assets/figures/hainguyen/Euler_config_6_12.png">
<figcaption><b>Figure : (Euler configurations) </b> Information.</figcaption>
</p>

<p align="center">
<img src="/assets/figures/hainguyen/3D_Euler_config6.gif">
<figcaption><b>Figure 2: (Euler configurations)</b> predictions by DGNet for configuration 6.</figcaption>
</p>

<p align="center">
<img src="/assets/figures/hainguyen/3D_Euler_config12.gif">
<figcaption><b>Figure 3: (Euler configurations) </b> predictions by DGNet for configuration 12</figcaption>
</p>

### Problem 2: Double Mach Reflection

- Training data is generated with time interval $[0,0.02]$
- Test data is generated with time interval $[0, 0.25]$

<p align="center">
<img src="/assets/figures/hainguyen/2D_Double_Mach_model.png">
<figcaption><b>Figure 3: (Double Mach Reflection) </b> model</figcaption>
</p>

<p align="center">
<img src="/assets/figures/hainguyen/2D_Double_Mach.gif">
<figcaption><b>Figure 3: (Double Mach Reflection) </b> predictions by DGNet</figcaption>
</p>

### Problem 3. Forward facing corner 

- Training data is generated from Model 1 with time interval $[0,1]$
- Test data is generated from Model 1 and Model 2 for time interval $[0, 4]$


<p align="center">
<img src="/assets/figures/hainguyen/2D_Euler_forth_models.png">
<figcaption><b>Figure : (Forward-facing corner) </b> Model 1 and Model 2.</figcaption>
</p>

<p align="center">
<img src="/assets/figures/hainguyen/2D_Euler_forth_same_mesh.gif">
<figcaption><b>Figure 4: (Forward-facing corner)</b> predictions by DGNet for Model 1.</figcaption>
</p>

<p align="center">
<img src="/assets/figures/hainguyen/2D_Euler_forth_different_mesh.gif">
<figcaption><b>Figure 5: (Forward-facing corner)</b> predictions by DGNet for Model 2.</figcaption>
</p>


### 4. ScramJet

- Training data is generated from Model 1 with time interval $[0,1.6]s$
- Test data is generated from Model 1 and Model 2 for time interval $[0, 6]s$

<p align="center">
<img src="/assets/figures/hainguyen/2D_Euler_scram_jet_models.png">
<figcaption><b>Figure : (ScramJet) </b> Model 1 and Model 2.</figcaption>
</p>

<p align="center">
<img src="/assets/figures/hainguyen/2D_Euler_scram_jet_same_mesh_Mach3.gif">
<figcaption><b>Figure 6: (ScramJet) </b> predictions by DGNet for Model 1.</figcaption>
</p>

<p align="center">
<img src="/assets/figures/hainguyen/2D_Euler_scram_jet_different_mesh_Mach3.gif">
<figcaption><b>Figure 7: (ScramJet) </b> predictions by DGNet for Model 2 </figcaption>
</p>


### 5. Airfoil

- Training data is generated from Airfoil AoA $3^o$ and Mach = 0.8, in time interval $[0,1.2]s$
- Test data is generated from Airfoil AoA $3^o$ and Mach = 0.8 adn Airfoil AoA $5^o$ and Mach = 1.2 for time interval $[0, 7.5]s$

<p align="center">
<img src="/assets/figures/hainguyen/2D_Euler_Airfoil_model.png">
<figcaption><b>Figure 8: (Airfoil)</b> Airfoil configuration AoA-3.</figcaption>
</p>

<p align="center">
<img src="/assets/figures/hainguyen/2D_Euler_Airfoil_Mach08_AoA3.gif">
<figcaption><b>Figure 8: (Airfoil)</b> predictions by DGNet for Airfoil M = 0.8, AoA = $3^o$</figcaption>
</p>

<p align="center">
<img src="/assets/figures/hainguyen/2D_Euler_Airfoil_Mach1p2_AoA5.gif">
<figcaption><b>Figure 9: (Airfoil) </b> predictions by DGNet for for Airfoil M = 1.2, AoA = $5^o$</figcaption>
</p>

