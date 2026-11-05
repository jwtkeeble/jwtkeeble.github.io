---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---
 
{% include base_path %}

<p><a href="/files/cv.pdf" class="btn btn--primary btn--large" download="CV_James_Keeble.pdf"><i class="fas fa-download"></i> Download CV (PDF)</a></p>

Experience
======
<div style="display:flex; justify-content:space-between; flex-wrap:wrap; margin-top:1em;">
<span><strong>Independent Researcher</strong>, in collaboration with Bielefeld University</span>
<span>June 2026 – Present</span>
</div>

  * Preparing an open-source release of the multi-GPU eigensolver, with tests, CI and reproducible benchmarks.
  * Developing new symmetry-aware neural-network wavefunctions for heavier nuclei on multi-GPU clusters.

<div style="display:flex; justify-content:space-between; flex-wrap:wrap; margin-top:1em;">
<span><strong>Postdoctoral Researcher</strong>, Bielefeld University, Germany</span>
<span>April 2024 – May 2026</span>
</div>

  * Built a multi-GPU neural-network variational Monte Carlo library in JAX, benchmarked against exact FCI where tractable and more accurate than coupled cluster (CCSD, CCSD(T)) on 40-qubit systems.
  * Identified quantum-state magic (non-stabilizerness) as a predictor of neural-network accuracy, showing where neural quantum states fail ([first-author preprint](https://arxiv.org/abs/2603.28646)).
  * Engineered an MPI-enabled, multi-GPU Lanczos eigensolver in Julia (CUDA.jl) for nuclear structure, 50× faster than the Fortran solver BIGSTICK, built with an agentic AI-assisted workflow.
  * Replaced computationally expensive CPU routines with custom CUDA.jl kernels, enabling the research group to scale calculations from 24-qubit to 44-qubit systems.
  * Maintained collaborative research software with CI/CD, automated testing and Apptainer containers.

<div style="display:flex; justify-content:space-between; flex-wrap:wrap; margin-top:1em;">
<span><strong>Doctoral Researcher</strong>, University of Surrey, UK</span>
<span>October 2018 – April 2023</span>
</div>

  * Developed an antisymmetric neural wavefunction in PyTorch for fermions in continuous space, outperforming Hartree–Fock and configuration interaction at fixed basis size across interaction strengths.
  * Created a neural-network wavefunction for the deuteron in continuous momentum space, among the first neural-network quantum states for an atomic nucleus.
  * Mentored PhD students in scientific ML software development, coding best practice and HPC workflows.

Open source & community
======
* Led the implementation of Decisional Gradient Descent, a game-theory extension of stochastic reconfiguration that outperformed it, published in [Phil. Trans. R. Soc. A](/publication/2024-01-31-second-order-optimisation).
* Evaluated functorch per-sample-gradient transforms, giving PyTorch developers validation results and usage examples ahead of their integration into `torch.func`.
* [PyTorch Foundation Pace-Setter Award (2023)](https://pytorch.org/ecosystem/contributor-awards-2023/#:~:text=PYTORCH%20PACE%2DSETTER,James%20Keeble) for nearly a hundred accepted forum solutions.

Education
======
* PhD, Theoretical Nuclear Physics, University of Surrey, UK, 2023
* MPhys, Physics (First-Class Honours), University of Surrey, UK, 2018

Skills
======
* **Scientific ML:** neural quantum states, symmetry-aware architectures (Pfaffians, Transformers), variational Monte Carlo, MCMC, natural-gradient optimisation, exact diagonalisation, numerical benchmarking
* **Programming:** Python, Julia, Fortran, Bash
* **GPU and distributed computing:** JAX, PyTorch, CUDA.jl, MPI, multi-GPU and multi-node, mixed precision
* **Software engineering:** Git, CI/CD, automated testing, Apptainer, SLURM, agentic AI development (Claude)
* **Languages:** English (native), German (B1)

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

Talks
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul>
