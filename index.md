---
layout: default
title: "When to Update Your Model:Constrained Model-based Reinforcement Learning"
description: Tianying Ji <sup>1</sup>, Yu Luo <sup>1</sup>, Fuchun Sun <sup>1</sup>, Mingxuan Jing <sup>2</sup>, Fengxiang He <sup>3</sup>, Wenbing Huang <sup>4,5</sup> <br> NeurIPS 2022
---


### Abstract

Designing and analyzing model-based RL (MBRL) algorithms with guaranteed monotonic improvement has been challenging, mainly due to the interdependence between policy optimization and model learning. Existing discrepancy bounds generally ignore the impacts of model shifts, and their corresponding algorithms are prone to degrade performance by drastic model updating. In this work, we first propose a novel and general theoretical scheme for a non-decreasing performance guarantee of MBRL. Our follow-up derived bounds reveal the relationship between model shifts and performance improvement. These discoveries encourage us to formulate a constrained lower-bound optimization problem to permit the monotonicity of MBRL. A further example demonstrates that learning models from a dynamically-varying number of explorations benefit the eventual returns. Motivated by these analyses, we design a simple but effective algorithm CMLO (Constrained Model-shift Lower-bound Optimization), by introducing an event-triggered mechanism that flexibly determines when to update the model. Experiments show that CMLO surpasses other state-of-the-art methods and produces a boost when various policy optimization methods are employed.


### Proof Sketch

![proofsketch](assets/images/theoryrecipe.png)


### Experimental Results

![proofsketch](assets/images/main_res.png)



