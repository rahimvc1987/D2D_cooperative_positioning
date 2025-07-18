# Joint Tensor Completion, Anchor Selection, and Coordinate Transformation (JTCASCT) for Cooperative Positioning in D2D Systems

## Overview
This repository contains the implementation and supplementary materials for our research on **high-precision cooperative positioning in Device-to-Device (D2D) communication systems**, as presented in our journal paper.

The proposed approach, **Joint Tensor Completion, Anchor Selection, and Coordinate Transformation (JTCASCT)**, addresses the challenge of recovering missing values in distance measurements between nodes and determining the global positions of unknown stationary nodes within ultra-dense 5G networks.

---

## Abstract
The synergistic amalgamation of device-to-device (D2D) communication between mobile terminals (MT) and ultra-dense networks in 5G systems enables cooperative positioning. In this work, we propose a **JTCASCT** framework for high precision cooperative positioning in D2D systems. 

The positioning is achieved by mitigating the challenging issue of recovering missing values from the corrupted distances between nodes and determining the global positions of unknown stationary nodes. 

Key steps in the framework include:
1. **Euclidean Distance Tensor (EDT):** Construction of a hankelized distance tensor from incomplete EDM (Euclidean Distance Matrix).
2. **Tensor Completion:** Recovery of missing values by exploiting the latent low-rank structure using **Simple Low-Rank Tensor Completion (SiLRTC)** and **High Accuracy Low-Rank Tensor Completion (HaLRTC)** algorithms.
3. **Multidimensional Scaling (MDS):** Determination of relative node positions.
4. **Anchor Selection via Kruskal-Wallis (KW) Test:** A low-complexity statistical method for optimal anchor node selection and dimension reduction.
5. **Helmert Transformation (HT):** Computation of global positions of unknown nodes.

**Numerical evaluations** demonstrate that the proposed JTCASCT approach significantly outperforms state-of-the-art techniques in terms of cooperative positioning accuracy.

---

## Key Features
- Implementation of **SiLRTC** and **HaLRTC** for tensor completion.
- Anchor selection via **Kruskal-Wallis test** for improved accuracy and reduced complexity.
- **Helmert Transformation** for global position recovery.
- Simulation scripts for **error evaluation and performance comparison** with benchmark methods.

---

## Repository Structure
