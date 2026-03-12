# Field Solvers & Diagnostics

Numerical solvers for field equations and diagnostic tools for testing and validation.

## Simulators

### [TRR-G Radial Solver — Coherence-Modified Gravitational Potential](trrg_radial_solver.html)
Solves radial field equations with coherence modifications to gravitational potential.

**Features:**
- ∇²κ = 4πGρ/c² with exponential envelope
- δC ∝ 1/r exterior profile validation
- M_eff/M_GR table computation
- Solver-corrected values (supersede estimates by ~3×)

**Best for:** Computing effective mass and validating gravitational field modifications.

---

### [TRR-G κ Isolation Test — Mismatch Diagnostics](trrg_kappa_isolation_test.html)
Diagnostic tool for testing and validating field solver outputs.

**Features:**
- Mismatch detection
- Solver validation
- Error diagnostics
- Coherence field isolation analysis

**Best for:** Debugging and validating field computation accuracy.

---

### [TRR-G 3D κ Field Simulator](trrg_3d_sim_v2.html)
3D spatial solution of Poisson's equation for coherence fields.

**Features:**
- 128³ grid capability
- SOR Gauss-Seidel solver
- Web Worker backend
- Optimized for Paper II parameter regime (ξ/r_s = 0.15)

**Best for:** Verifying 2D results in full 3D space and confirming radial profiles.

---

### [TRR-G Substrate Evaluator v2 — Dynamic Field Evolution](TRRG_Substrate_Evaluator_v2.html)
Dynamic evaluation of field evolution on computational substrates.

**Features:**
- Substrate performance analysis
- Field evolution tracking
- Time-domain dynamics
- Parameter sensitivity analysis

**Best for:** Understanding how fields evolve and interact with computational environments.

---

### [TRR-G Klein-Gordon 1D (flipped)](TRRG_KleinGordon_1D_flipped.html)
1‑D Klein–Gordon solver with flipped boundary conditions.

**Features:**
- Demonstrates kink dynamics under inverted boundary setup
- Useful for validating analytic solutions with nonstandard edges

**Best for:** Experimenting with one-dimensional field behaviour under flipped conditions.

---

## Technical Notes

- Solvers validate each other's results
- Cross-referenced across different implementations
- Suitable for Paper II and Paper III parameter regimes
- Precision validation and error analysis support
