# Gengxuan Zhu · 朱耕玄

**PhD student in Solid Mechanics · School of Aeronautics and Astronautics, Zhejiang University**

> I use finite element models and neural networks to reconstruct spatially varying Young’s modulus from full-field displacement measurements.

I focus on functionally graded materials and high-throughput mechanical characterization. My collaborative research also covers contact and indentation inverse problems.

[ORCID](https://orcid.org/0009-0000-3445-9109) · [FE-GIN](#fe-gin) · [Research Code](#research-code-projects) · [Publications](#selected-publications) · [Education](#academic-background)

---

## FE-GIN

**Full-field modulus reconstruction for functionally graded materials**

FE-GIN incorporates weak-form equilibrium losses into U-Net training. The code covers MATLAB data generation, PyTorch training, and comparison with an iterative adjoint-state solver.

With the same forward model, FE-GIN recovered the tested bilinear and exponential modulus fields with lower error and achieved comparable accuracy on the random-field case. After training, it reconstructs a field in a single forward pass.

[Source Code](https://github.com/zhugx-zju/FE-GIN) · [Publication](https://doi.org/10.1016/j.ijmecsci.2026.112126)

## Research Code Projects

| Project | Research task |
| --- | --- |
| [CHTC](https://github.com/zhugx-zju/CHTC) | Continuous high-throughput characterization of mechanical properties with deep learning |
| [ASM-Python](https://github.com/zhugx-zju/ASM-Python) | 2D adjoint-state modulus inversion with gradient checks |
| [fgm-inverse-fenics](https://github.com/zhugx-zju/fgm-inverse-fenics) | Method comparison on a shared inverse problem using manual FEM, FEniCSx, and physics-informed neural networks |
| [fgm_dic](https://github.com/zhugx-zju/fgm_dic) | 2D modulus reconstruction from experimental digital image correlation (DIC) data |

<details>
<summary>Earlier implementations</summary>

- [Direct-FEM](https://github.com/zhugx-zju/Direct-FEM) — direct finite element methods for plane inverse problems.
- [adjoint-method-Matlab](https://github.com/zhugx-zju/adjoint-method-Matlab) — MATLAB implementation of adjoint-based modulus identification.

</details>

## Selected Publications

- **Zhu, G.**, et al. [Finite-element-guided inversion network for full-field reconstruction of graded modulus distributions](https://doi.org/10.1016/j.ijmecsci.2026.112126). *International Journal of Mechanical Sciences*, 2026.
- **Zhu, G.**, et al. [Continuous high-throughput characterization of mechanical properties via deep learning](https://doi.org/10.1016/j.ijmecsci.2025.110137). *International Journal of Mechanical Sciences*, 2025.

---

## Academic Background

- **PhD in Solid Mechanics, Zhejiang University** · 2023–present  
  Advisor: Weiqiu Chen · Co-advisor: Ronghao Bao
- **Undergraduate studies in Engineering Mechanics, Zhejiang University**
