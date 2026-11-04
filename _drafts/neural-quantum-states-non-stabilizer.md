---
title: "How 'magical' is a Neural Quantum State?"
date: 2026-08-19
permalink: /posts/2026-08-19/neural-quantum-states-non-stabilizer/
header:
  overlay_image: /images/nqs-non-stabilizer/fig2-infidelity-vs-m2.png
  overlay_filter: 0.65
  teaser: /images/nqs-non-stabilizer/fig2-infidelity-vs-m2.png
  title: 'Neural quantum states in non-stabilizer regimes'
tags:
  - neural-quantum-states
  - nuclear-structure
  - quantum-complexity
  - machine-learning
excerpt: "What quantum complexity can tell us about neural quantum states"
---

The use of Neural Quantum States (NQS) --- using neural networks to represent quantum many-body wavefunctions --- have become the gold standard of classical techniques over the past few years. However, the performance of NQS models in representing quantum many-body wavefunctions remains an open question.

In recent research with Alessandro Lovato (IFIC, University of Valencia) and Caroline Robin (Microsoft Quantum, Seattle), we demonstrate how the performance of an Restricted Boltzmann Machine (RBM) directly correlates with its non-stabilizerness and not the number of configurations, which directly highlights the role of quantum information science in analysing NQS.



























# Why are some nuclear wavefunctions harder for neural networks to learn?

*[One-line subtitle: the plain-English version of your thesis. e.g. "Quantum 'magic' — not entanglement — turns out to be the bottleneck for neural quantum states."]*
 
**By [Author names] · [Date] · [Read time estimate]**
 
---
 
## TL;DR
 
*[2–4 sentences a busy reader can stop at. State the question, the method in one clause, and the headline finding. No jargon yet.]*
 
> We built neural-network representations of atomic nuclei and asked: what makes some nuclei easier to learn than others? The answer isn't how entangled they are — it's how much "quantum magic" (non-stabilizerness) they contain.
 
---
 
## Why This Question Matters
 
*[1–2 short paragraphs. Motivate the problem for a reader who isn't a specialist. Answer: what's a neural quantum state, why do people care, what's been unclear.]*
 
- What are neural quantum states (NQS) used for?
- What's the open question your field has been circling (entanglement vs. something else)?
- Why atomic nuclei specifically make a good testbed (rapid Hilbert-space growth, two fermion species, known high-complexity ground states)?
---
 
## Background, Briefly
 
*[Keep this section short — link out to a primer or footnote definitions rather than re-deriving everything. One paragraph per concept, max.]*
 
**Neural quantum states.** *[1–2 sentences — RBM as a compact way to represent many-body wavefunctions.]*
 
**Non-stabilizerness ("magic").** *[1–2 sentences — why entanglement alone isn't a sufficient measure of quantum complexity; magic as the missing ingredient.]*
 
**The interacting shell model (ISM).** *[1–2 sentences — your "ground truth" benchmark from exact diagonalization.]*
 
---
 
## What We Did
 
*[Describe your method conversationally — a reader should come away understanding the pipeline without needing the equations.]*
 
1. Map nuclear orbitals onto visible nodes of a restricted Boltzmann machine (RBM).
2. Optimize network parameters two ways: (a) maximize fidelity against the exact ISM ground state, (b) minimize energy via variational Monte Carlo.
3. Compare accuracy against a measure of non-stabilizerness (stabilizer Rényi entropy) for each nucleus.
![Method overview — nuclear orbitals mapped onto RBM visible/hidden nodes](template.png)
*Figure 1. [Caption: describe what the reader is looking at and the one thing they should notice.]*
 
---
 
## The Key Result
 
*[This is the heart of the post — one clear finding, explained twice: once in plain language, once with the supporting numbers/figure.]*
 
*[Plain-language version, 2–3 sentences.]*
 
![Accuracy vs. non-stabilizerness across nuclei](template.png)
*Figure 2. [Caption: what's on each axis, what the color/size encodes, what trend to look for.]*
 
### Results at a glance
 
| Nucleus | # Configurations | Non-stabilizerness (𝓜₂) | Fidelity (α = 1) | Fidelity (α = 8) |
|---|---|---|---|---|
| [e.g. ²⁶O] | [14] | [0.31] | [1.000] | [1.000] |
| [e.g. ²⁴Mg] | [28,503] | [10.60] | [0.522] | [0.792] |
| [e.g. ²⁸Si] | [93,710] | [8.11] | [0.640] | [0.872] |
| *[…add rows as needed]* | | | | |
 
*Table 1. [One-line note on what this table demonstrates — e.g. "nuclei with higher magic content need more network parameters to reach comparable fidelity."]*
 
---
 
## Why It Happens (Interpretation)
 
*[1–2 paragraphs of intuition-building. What's the mechanism? Why would magic — rather than entanglement — limit an RBM's expressivity? Feel free to use an analogy here.]*
 
---
 
## Caveats & What's Next
 
*[Be upfront: what this study doesn't show, where it might not generalize, what a skeptical reader would ask.]*
 
- *[Limitation 1 — e.g. scope limited to sd-shell nuclei]*
- *[Limitation 2 — e.g. RBM is the simplest NQS architecture; more expressive networks untested]*
- *[Open question / future work — e.g. testing Transformer-based NQS, basis-optimization to reduce complexity]*
---
 
## Takeaways
 
*[3 bullets max — what should stick with the reader.]*
 
- 
- 
- 
---
 
## Read the Paper
 
**[Full paper title]** — [Author list]
📄 [arXiv link] · [Journal link if published]
 
*[Optional: BibTeX block for citation]*
 
```bibtex
  @article{Keeble_2026,
    author = {Keeble, James W. T. and Lovato, Alessandro and Robin, Caroline E. P.},
    title = {Neural Quantum States in Non-Stabilizer Regimes: Benchmarks with Atomic Nuclei},
    eprint = {2603.28646},
    archivePrefix = {arXiv},
    primaryClass = {nucl-th},
    year = {2026},
    url = {https://arxiv.org/abs/2603.28646}
  }
```
 