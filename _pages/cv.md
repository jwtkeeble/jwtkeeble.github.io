---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---
 
{% include base_path %}
 
Education
======
* Ph.D. in Theoretical Physics, University of Surrey, UK, 2022
* MPhys in Physics, First Class Honours, University of Surrey, UK, 2018

Awards
======
* PyTorch Pace-Setter Award [(First recipient)](https://pytorch.org/ecosystem/contributor-awards-2023/#:~:text=PYTORCH%20PACE%2DSETTER,James%20Keeble), PyTorch Foundation, CA, USA, 2023

Work experience
======
<div style="display:flex; justify-content:space-between; flex-wrap:wrap; margin-top:1em;">
<span>April 2024 – May 2026 &middot; <strong>Researcher & Software Engineer</strong></span>
<span>Bielefeld, Germany</span>
</div>

  * Developed a GPU-accelerated Julia/CUDA package to analyse wavefunctions, scaling computation to billions of configurations — 10,000× larger than previous methods — reduced runtime from months to hours.
  * Built Variational Monte Carlo (VMC) codes to simulate atomic nuclei with neural networks in JAX — demonstrated that model performance correlated with complexity measures rather than configuration size.
  * Implemented reproducible software infrastructure using Apptainer and CI/CD pipelines for automated testing across HPC environments.

<div style="display:flex; justify-content:space-between; flex-wrap:wrap; margin-top:1em;">
<span>Oct. 2018 – Oct. 2022 &middot; <strong>Doctoral Researcher</strong></span>
<span>Surrey, UK</span>
</div>

  * Designed a novel game-theoretic optimization algorithm to accelerate neural-network convergence — achieved 10× speed-up in convergence over first-order methods.
  * Published peer-reviewed research and mentored Masters students on neural-network techniques and Monte Carlo methods for Scientific Machine Learning (SciML).

<div style="display:flex; justify-content:space-between; flex-wrap:wrap; margin-top:1em;">
<span>Feb. 2017 – Dec. 2017 &middot; <strong>Research Internship</strong></span>
<span>Texas, USA</span>
</div>

  * Developed Exploratory Data Analysis (EDA) tools in C++ ROOT to analyse multi-variable experimental data in inverse kinematics reactions.
  * Assembled a bench-top vacuum system to validate a position-sensitive detector and improve the experimental beamline.

Skills
======
* Programming
  * Python, Julia, Bash, CUDA.jl, FORTRAN, LaTeX
* Machine Learning
  * PyTorch, JAX, Equinox, Optax, Orbax, Monte Carlo methods
* System & Dev
  * HPC (SLURM, Apptainer), Linux, Git, CI/CD, Globus
* Languages
  * Native English, Conversational German (B1)

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
