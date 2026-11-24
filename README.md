# Gengxuan Zhu · 朱耕玄

**PhD student in solid mechanics · School of Aeronautics and Astronautics, Zhejiang University**

I develop inverse methods that turn measured displacements into spatial maps of material stiffness. My main research is full-field modulus reconstruction for functionally graded materials. I use finite-element-guided neural networks and adjoint-state methods, with applications in high-throughput mechanical characterization and collaborative work on contact and indentation.

### Academic background

- **PhD in Solid Mechanics, Zhejiang University** · 2023–present. Advisor: Weiqiu Chen. Co-advisor: Ronghao Bao.
- **Undergraduate studies** · Engineering Mechanics at Zhejiang University, with a final year in Propulsion Engineering at Moscow Aviation Institute through the 3+1 joint undergraduate program.

[ORCID](https://orcid.org/0009-0000-3445-9109) · [Flagship project](#flagship-project-fe-gin) · [Research code projects](#research-code-projects) · [Selected papers](#selected-papers)

---

## Flagship project: FE-GIN

**Recovering the full-field Young’s modulus of graded materials from displacement measurements**

FE-GIN combines finite element equilibrium constraints with a U-Net for field reconstruction. The repository brings together MATLAB data generation, PyTorch training, and a comparison with an iterative adjoint-state solver.

In the benchmark, FE-GIN achieved lower reconstruction errors for the tested bilinear and exponential modulus fields and comparable accuracy for the random-field case, using a single forward pass after training.

[Explore the code](https://github.com/zhugx-zju/FE-GIN) · [Read the paper](https://doi.org/10.1016/j.ijmecsci.2026.112126)

## Research code projects

| Research task | Repository |
| --- | --- |
| Continuous high-throughput characterization | [CHTC](https://github.com/zhugx-zju/CHTC) — deep learning workflow for continuous mechanical-property characterization |
| Adjoint-state inversion | [ASM-Python](https://github.com/zhugx-zju/ASM-Python) — 2D finite element solver with gradient checks and regularization-parameter selection |
| Comparing inversion methods | [fgm-inverse-fenics](https://github.com/zhugx-zju/fgm-inverse-fenics) — manual FEM, FEniCSx, and physics-informed neural networks on a shared inverse problem |

### Experimental displacement data

[fgm_dic](https://github.com/zhugx-zju/fgm_dic) reconstructs two-dimensional modulus fields from experimental digital image correlation (DIC) displacement measurements.

<details>
<summary>Earlier implementations</summary>

- [Direct-FEM](https://github.com/zhugx-zju/Direct-FEM) — direct finite element methods for plane inverse problems.
- [adjoint-method-Matlab](https://github.com/zhugx-zju/adjoint-method-Matlab) — MATLAB implementation of adjoint-based modulus identification.

</details>

## Selected papers

- **Zhu, G.**, et al. [Finite-element-guided inversion network for full-field reconstruction of graded modulus distributions](https://doi.org/10.1016/j.ijmecsci.2026.112126). *International Journal of Mechanical Sciences*, 2026.
- **Zhu, G.**, et al. [Continuous high-throughput characterization of mechanical properties via deep learning](https://doi.org/10.1016/j.ijmecsci.2025.110137). *International Journal of Mechanical Sciences*, 2025.
