# Electrogravitic Constraint Theory (ECH)

[![License: MIT](https://img.shields.io/badge/Code%20License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![License: CC BY-SA 4.0](https://img.shields.io/badge/Text%20License-CC--BY--SA%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by-sa/4.0/)
[![Preprint (Coming Soon)](https://img.shields.io/badge/Preprint-Zenodo%20%7C%20arXiv-blue.svg)](https://)
[![ORCID](https://img.shields.io/badge/Author-0000--0002--1041--814X-blue?style=flat&logo=orcid)](https://orcid.org/0000-0002-1041-814X)

**Author:** [Daniel Sandner](https://orcid.org/0000-0002-1041-814X)

## Project Overview: Gravito-Magnetic Flux Pinning

This repository contains the source code, numerical notes, and papers for the **Electrogravitic Constraint Theory (ECH)**.

The ECH is a unified field framework that proposes a fundamental coupling between gravity and electromagnetism, driven by a new field in the vacuum. This mechanism, coined **Gravito-Magnetic Flux Pinning (GMFP)**, converts the gravitational constant $G$ from a fixed value into a dynamic, local field.

### The Core Hypothesis: Spacetime with a Quantum Memory

The theory is born from the question: *What if the extreme stability of quantum levitation (flux pinning in superconductors) is an analogy for the geometry of the universe?*

1.  **The Cosmic Condensate ($\Phi$):** The vacuum is filled with an invisible, energy-minimizing quantum field, the **Cosmic Condensate ($\Phi$)**, analogous to the coherent electron-pair fluid in a superconductor.
2.  **The Constraint:** The local **electromagnetic field (magnetism)** acts on this Condensate, which in turn dictates the geometry of spacetime.
3.  **The Result:** The fundamental strength of gravity is not constant, but is locally and dynamically constrained by the topology of the electromagnetic field:

$$G_{\text{eff}} \propto \frac{1}{\text{Local Vacuum Coherence}} \propto \text{Local Field Geometry} \times \text{Electromagnetic Field Strength}$$

---

## Key Predictions & Testable Consequences

The ECH generates specific, falsifiable predictions that deviate from General Relativity (GR):

| Prediction | Physical Manifestation | Test Regime |
| :--- | :--- | :--- |
| **Gravitational Hysteresis** | The gravitational field possesses "memory." Its current state depends on its past magnetic field history. | **Magnetar Observations:** Look for damped oscillations in a binary star's orbit following a massive magnetic flare. |
| **Dynamic Anisotropy of G** | The strength of gravity varies with direction, aligning with the local magnetic field (e.g., the Galactic B-field). | **Precision Metrology:** Re-analyze GPS/LLR satellite data to detect a $\delta G/G \sim 10^{-14}$ signal correlated with celestial coordinates. |
| **Topological Dark Matter** | Dark Matter is composed of stable, massive **topological defects** (monopoles, cosmic strings) that formed as the Condensate crystallized in the early universe. | **Cosmology & Pulsar Timing:** Search for gravitational lensing signatures and the unique spectral glitches predicted by these structures. |
| **Baryogenesis & $\Lambda$ Screening** | The Condensate's structure solves the origin of matter-antimatter asymmetry and provides a **dynamical screening mechanism** for the cosmological constant. | **CMB Analysis:** Search for subtle parity-violating signatures in the CMB power spectrum. |

---

## 📂 Repository Structure

| Folder | Content | Description |
| :--- | :--- | :--- |
| `papers/` | P1\_Formalism, P2\_Phenomenology, P3\_Cosmology | Drafts, preprints, and published versions of the core research papers. |
| `code/` | C1\_GR\_Sim, C2\_Condensate\_Solver, C3\_Orbital\_Corrections | Numerical code (Python/C++/Julia) used for simulations, field equation solutions, and calculating observable corrections. **(Each code directory includes a specific `README.md`)** |
| `docs/` | Public articles, guides, tutorials | User-friendly explanations of the ECH, technical simulation guides, and visualization assets for public outreach. |
| `papers/PX/drafts/research/notes/` | Derivations, calculations | Detailed handwritten and LaTeX notes for complex derivations in the Lagrangian, field equations, and perturbation analysis. |

---

## Research & Collaboration

This is a living research program. We actively seek collaboration and funding in the following areas:

*   **Theoretical Physics:** Expertise in Quantum Field Theory in Curved Spacetime, numerical GR, and alternative gravity models.
*   **Astrophysics/Observational:** Access to and expertise in analyzing archival data (GPS, LLR, Pulsar Timing Arrays) and planning future magnetar observation campaigns.
*   **Experimental Physics:** Expertise in designing high-precision, low-noise experiments (torsion balances, atom interferometry) for testing fundamental physics.

---

## License

This repository uses a dual-license model to adhere to open science principles:

*   All source code is licensed under the **[MIT License](LICENSE)**.
*   All scientific texts, papers, notes, and this README are licensed under the **[Creative Commons Attribution-ShareAlike 4.0 International License](LICENSE_TEXT.md)** (CC-BY-SA 4.0).

**Please cite the relevant papers when using this work.**
