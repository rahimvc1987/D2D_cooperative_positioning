# Joint Tensor Completion, Anchor Selection, and Coordinate Transformation (JTCASCT) for Cooperative Positioning in D2D Systems

## Overview
This repository provides the implementation and supporting materials for our research on **high-precision cooperative positioning in Device-to-Device (D2D) communication systems**, as published in our journal article:

**[Joint Tensor Completion, Anchor Selection, and Coordinate Transformation for Cooperative Positioning in D2D Systems](https://www.sciencedirect.com/science/article/pii/S1874490723002410)**

The **JTCASCT** framework addresses the challenge of recovering missing values in distance measurements between nodes and accurately estimating the global positions of unknown stationary nodes within ultra-dense 5G networks.

---

## Abstract
The synergistic amalgamation of device-to-device (D2D) communication between mobile terminals (MT) and ultra-dense networks in 5G systems enables cooperative positioning. In this work, we propose a **JTCASCT** framework for high precision cooperative positioning in D2D systems. 

The positioning is achieved by mitigating the challenging issue of recovering missing values from the corrupted distances between nodes and determining the global positions of unknown stationary nodes. 

Key steps include:
1. **Euclidean Distance Tensor (EDT):** Constructing a hankelized distance tensor from incomplete EDM.
2. **Tensor Completion:** Recovery of missing values via **SiLRTC** and **HaLRTC**.
3. **Multidimensional Scaling (MDS):** Determining relative node positions.
4. **Anchor Selection via Kruskal-Wallis (KW) Test:** Low-complexity anchor node selection.
5. **Helmert Transformation (HT):** Global position computation of unknown nodes.

**Numerical evaluations** show that JTCASCT significantly improves cooperative positioning accuracy compared to state-of-the-art techniques.

---

## Key Features
- Tensor completion with **SiLRTC** and **HaLRTC**.
- Anchor selection using the **Kruskal-Wallis test**.
- **Helmert Transformation** for global position recovery.
- MATLAB/Python implementations with performance comparison.

---

## Repository Structure

---

## Dependencies
- MATLAB (preferred) or Python (`NumPy`, `SciPy`, `TensorLy`)
- Dependencies listed in `requirements.txt`

---

## Usage
1. Clone the repository:
   ```bash
   git clone https://github.com/<your-username>/<repo-name>.git
   cd <repo-name>
@article{Rahim2023JTCASCT,
  title   = {Joint Tensor Completion, Anchor Selection, and Coordinate Transformation for Cooperative Positioning in D2D Systems},
  author  = {Abdul Rahim V.C. and Chris Prema S.},
  journal = {Physical Communication},
  volume  = {XX},
  pages   = {XX--XX},
  year    = {2023},
  doi     = {10.1016/j.phycom.2023.102079}
}
