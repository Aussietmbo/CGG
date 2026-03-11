# TRR-G Compact Object Simulators

Core simulators for studying compact object physics, vortex formation, and gravitational effects within the TRR-G framework.

## Simulators

### [TRR-G Paper III — Vortex Nucleation Simulator](trrg_vortex_nucleation.html)
Interactive 2D cross-section of compact object interior with vortex formation physics.

**Features:**
- Density profile computation from Gap3 equations
- Echo amplitude and timing calculations
- Mexican-hat potential profiles with vortex cores
- Presets for rotation and scalar field parameters
- Validated at ξ/r_s = 0.15, δ = 0.05

**Best for:** Understanding vortex nucleation conditions and compact object interior dynamics.

---

### [TRR-G / CGG — Light Propagation Simulator](trrg_light_propagation.html)
Fermat ray optics in effective refractive index backgrounds.

**Features:**
- Ray-optics approximation with n(r) ≈ 1 − 2δC(r)
- PPN framework integration (γ = 1)
- Analytical ray bending: δα = 4GM/c²b
- Interactive ray path visualization

**Best for:** Visualizing light deflection through scalar field backgrounds.

---

### [TRR-G — ψ Wavefront Propagation](trrg_wavefront2.html)
Ocean-crest visualization of Klein-Gordon phase propagation through coherence gradients.

**Features:**
- Dispersion relation: ω² = ω_c² + c²k²(1 − 2δC)
- Paraxial phase integral formulation
- Corrected wave vector scaling
- Visual phase front evolution
- Comparison with ray optics predictions

**Best for:** Observing WKB approximation and phase velocity effects in non-uniform fields.

---

### [TRR-G Vortex Field Explorer — WebGL](TRR_G_Vortex_WebGL.html)
Interactive WebGL visualization of vortex field topology.

**Features:**
- Real-time 3D rendering
- Vortex field topology visualization
- Interactive controls

**Best for:** Exploring vortex structure and field geometry in detail.

---

### [CGG Vortex-Core Black Hole](blackhole_cgg_vortex.html)
Compact object interior with emphasis on vortex core structure.

**Features:**
- Black hole vortex-core physics
- Interior field visualization
- Singularity dynamics

**Best for:** Understanding vortex dynamics near singular regions.

---

## Technical Notes

- All simulators interconnect within the TRR-G framework
- Parameter validation at ξ/r_s = 0.15 across simulators
- Results inform compact object observability (echoes, lensing, wave signatures)
- Incrementally developed alongside research papers
