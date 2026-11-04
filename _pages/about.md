---
permalink: /
title: "James W. T. Keeble"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I'm a computational physicist and research software engineer with a Ph.D. in theoretical physics from the University of Surrey. I build machine-learning models and high-performance scientific software: most recently neural-network simulations of atomic nuclei in JAX and GPU-accelerated analysis code in Julia/CUDA at Universität Bielefeld.

I'm currently open to new roles in machine learning and scientific computing. See my [CV](/cv/) and [software](/software/), or get in touch on [LinkedIn](https://www.linkedin.com/in/james-wt-keeble).

## Highlights

- **Scaling scientific code on GPUs.** Developed a GPU-accelerated Julia/CUDA package that analyses wavefunctions with billions of configurations, 10,000× larger than previous methods, cutting runtime from months to hours.
- **Faster neural-network training.** Designed a game-theoretic second-order optimizer that converges 10× faster than first-order methods ([paper](/publication/2024-01-31-second-order-optimisation), [code](https://github.com/jwtkeeble/second-order-optimization-NQS)).
- **PyTorch Pace-Setter Award, 2023.** [First recipient](https://pytorch.org/ecosystem/contributor-awards-2023/#:~:text=PYTORCH%20PACE%2DSETTER,James%20Keeble) of the PyTorch Foundation's contributor award.
- **Reproducible HPC workflows.** Built containerised (Apptainer) environments and CI/CD pipelines for automated testing across HPC clusters.
- **Published and presented.** Five papers and five invited talks, including Los Alamos National Laboratory, ECT* and CECAM.

## Skills

**Programming:** Python · Julia · CUDA.jl · Bash · Fortran · LaTeX

**Machine learning:** PyTorch · JAX (Equinox, Optax, Orbax) · neural-network quantum states · second-order optimization (KFAC) · Monte Carlo methods

**Systems & development:** HPC (SLURM, Apptainer) · Linux · Git · CI/CD · Globus

**Languages:** English (native) · German (B1)

## Research interests

**Neural quantum states for nuclear structure.** Using neural networks as compact representations of many-body wavefunctions, from the deuteron to medium-mass nuclei.

**Quantum complexity of nuclear wave functions.** Measuring entanglement and non-stabilizerness ("magic") in nuclei, and what they imply for classical and quantum simulation.

**Optimization for variational quantum methods.** Second-order optimizers that make variational Monte Carlo training faster and more stable.

## Recent work

- **Neural Quantum States in Non-Stabilizer Regimes: Benchmarks with Atomic Nuclei** (2026, with A. Lovato & C. E. P. Robin) — showing that larger non-stabilizerness makes nuclear states systematically harder for RBMs to learn. *arXiv preprint.* [arXiv:2603.28646](https://arxiv.org/abs/2603.28646)
- **Quantum magic and multipartite entanglement in the structure of nuclei** (2025, with F. Brökemeier, S. M. Hengstenberg, C. E. P. Robin, F. Rocco & M. J. Savage) — characterizing quantum magic and multipartite entanglement in nuclear wave functions. *Phys. Rev. C* **111**, 034317. [DOI](https://journals.aps.org/prc/abstract/10.1103/PhysRevC.111.034317)
- **Second-order optimisation strategies for neural network quantum states** (2024, with M. Drissi, J. Rozalén Sarmiento & A. Rios) — applying second-order methods to stabilize and accelerate NQS training. *Phil. Trans. R. Soc. A* **382**, 20240057. [DOI](https://doi.org/10.1098/rsta.2024.0057)
- **Machine learning one-dimensional spinless trapped fermionic systems with neural-network quantum states** (2023, with M. Drissi, A. Rojo-Francàs, B. Juliá-Díaz & A. Rios) — learning trapped-fermion ground states with NQS. *Phys. Rev. A* **108**, 063320. [DOI](https://journals.aps.org/pra/abstract/10.1103/PhysRevA.108.063320)

See the [Publications](/publications/) page for the full list, and the [Talks](/talks/) page for recent and upcoming presentations.
