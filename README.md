# NODEO: A Neural Ordinary Differential Equation Based Optimization Framework for Deformable Image Registration

This reproducibility project was conducted by students from TU Delft as part of the course CS4240 Deep Learning (Q3 2023).

Victoria Leskoschek | 5701627 | v.leskoschek@student.tudelft.nl

Ariel Ebersberger   | 4874951 | a.ebersberger@student.tudelft.nl

The aim of the project was to reproduce the results of the paper *NODEO: A Neural Ordinary Differential Equation Based Optimization Framework for Deformable Image Registration* by Wu et al., based on the source code provided by the authors.

Links to the original NODEO paper:
- [Paper](https://arxiv.org/pdf/2108.03443.pdf)
- [Source Code](https://github.com/yifannnwu/NODEO-DIR)
- [Project Website](https://yifannnwu.com/NODEO-DIR/)

## Reproducibility Project
For our project, we focused on the following categories:

**1. Reproduction**

We reproduced the code provided on GitHub for 3D deformable image registration on the OASIS dataset.

**2. New Algorithm Variant**

Since the existing code only functions for 3D images, we modified the code for compatibility with 2D brain images. Additionally, we implemented a variant that supports PNG images, enabling us to assess the model with a self-created toy dataset based on the one provided in the paper.

**3. New Code Variant**

We refactored certain hard-coded snippets to make the code more generalisable and implemented a loop structure allowing to iterate over multiple image pairs and compute the average dice scores. We further tried to add more comments to the code, explaining its functionality better.