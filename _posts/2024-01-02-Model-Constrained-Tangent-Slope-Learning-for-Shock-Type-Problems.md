---
layout: post
mathjax: true
title: "mcTangent Learning Slope Approach for Shock Type Problems"
# permalink: /research/mctangent_extension
---

# Methodology 
This work aims to solve shock-type problems with machine learning.

<p align="center">
<img src="/assets/figures/hainguyen/mctangent_0.png">
<figcaption align="center"><b>Figure 0:</b> The schematic of mcTangent network architecture for S = 1.</figcaption>
</p>

# Numerical results

## Problem 1. Euler equation configurations 6, 12

- Training data is generated from Euler configuration 6 with time interval [0,0.16]s
- Test data is generated from Euler configuration 6 for time interval [0, 0.8]s and Euler configuration 12 for time interval [0, 0.25]s

<p align="center">
  <img src="/assets/figures/hainguyen/Euler_config_6_12.png" width="80%" alt="Euler configurations">
  <br>
  <em>Figure 1: (Euler configurations) Information.</em>
</p>

<p align="center">
  <img src="/assets/figures/hainguyen/3D_Euler_config6.gif" width="80%" alt="DGNet predictions for configuration 6">
  <br>
  <em>Figure 2: (Euler configurations) predictions by DGNet for configuration 6.</em>
</p>

<p align="center">
  <img src="/assets/figures/hainguyen/3D_Euler_config12.gif" width="80%" alt="DGNet predictions for configuration 12">
  <br>
  <em>Figure 3: (Euler configurations) predictions by DGNet for configuration 12</em>
</p>

## Problem 2: Double Mach Reflection

- Training data is generated with time interval [0,0.02]s
- Test data is generated with time interval [0, 0.25]s

<p align="center">
  <img src="/assets/figures/hainguyen/2D_Double_Mach_model.png" width="80%" alt="Double Mach Reflection model">
  <br>
  <em>Figure 4: (Double Mach Reflection) model</em>
</p>

<p align="center">
  <img src="/assets/figures/hainguyen/2D_Double_Mach.gif" width="80%" alt="Double Mach Reflection predictions">
  <br>
  <em>Figure 5: (Double Mach Reflection) predictions by DGNet</em>
</p>

## Problem 3. Forward facing corner 

- Training data is generated from Model 1 with time interval [0,1]s
- Test data is generated from Model 1 and Model 2 for time interval [0,4]s

<p align="center">
  <img src="/assets/figures/hainguyen/2D_Euler_forth_models.png" width="80%" alt="Forward-facing corner models">
  <br>
  <em>Figure 6: (Forward-facing corner) Model 1 and Model 2.</em>
</p>

<p align="center">
  <img src="/assets/figures/hainguyen/2D_Euler_forth_same_mesh.gif" width="80%" alt="DGNet predictions for Model 1">
  <br>
  <em>Figure 7: (Forward-facing corner) predictions by DGNet for Model 1.</em>
</p>

<p align="center">
  <img src="/assets/figures/hainguyen/2D_Euler_forth_different_mesh.gif" width="80%" alt="DGNet predictions for Model 2">
  <br>
  <em>Figure 8: (Forward-facing corner) predictions by DGNet for Model 2.</em>
</p>

## Problem 4. ScramJet

- Training data is generated from Model 1 with time interval [0,1.6]s
- Test data is generated from Model 1 and Model 2 for time interval [0, 6]s

<p align="center">
  <img src="/assets/figures/hainguyen/2D_Euler_scram_jet_models.png" width="80%" alt="ScramJet models">
  <br>
  <em>Figure 9: (ScramJet) Model 1 and Model 2.</em>
</p>

<p align="center">
  <img src="/assets/figures/hainguyen/2D_Euler_scram_jet_same_mesh_Mach3.gif" width="80%" alt="DGNet predictions for ScramJet Model 1">
  <br>
  <em>Figure 10: (ScramJet) predictions by DGNet for Model 1.</em>
</p>

<p align="center">
  <img src="/assets/figures/hainguyen/2D_Euler_scram_jet_different_mesh_Mach3.gif" width="80%" alt="DGNet predictions for ScramJet Model 2">
  <br>
  <em>Figure 11: (ScramJet) predictions by DGNet for Model 2</em>
</p>

## Problem 5. Airfoil

- Training data is generated from Airfoil AoA = 3 and Mach = 0.8, in time interval [0,1.2]s
- Test data is generated from Airfoil AoA = 3 and Mach = 0.8 and Airfoil AoA = 5 and Mach = 1.2 for time interval [0, 7.5]s

<p align="center">
  <img src="/assets/figures/hainguyen/2D_Euler_Airfoil_model.png" width="60%" alt="Airfoil configuration">
  <br>
  <em>Figure 12: (Airfoil) Airfoil configuration AoA-3.</em>
</p>

<p align="center">
  <img src="/assets/figures/hainguyen/2D_Euler_Airfoil_Mach08_AoA3.gif" width="80%" alt="DGNet predictions for Airfoil M = 0.8, AoA = 3">
  <br>
  <em>Figure 13: (Airfoil) predictions by DGNet for Airfoil M = 0.8, AoA = 3</em>
</p>

<p align="center">
  <img src="/assets/figures/hainguyen/2D_Euler_Airfoil_Mach1p2_AoA5.gif" width="80%" alt="DGNet predictions for Airfoil M = 1.2, AoA = 5">
  <br>
  <em>Figure 14: (Airfoil) predictions by DGNet for Airfoil M = 1.2, AoA = 5</em>
</p>