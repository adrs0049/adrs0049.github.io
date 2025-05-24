---
layout: single
title: "Math-Bio Lab"
permalink: /lab/
author_profile: true
toc: true
toc_label: "Lab Info"
toc_icon: "flask"
---

Welcome to the Buttenschön Lab at the University of Massachusetts Amherst! We
use mathematical modeling and computational approaches to understand how cells
organize into functional tissues.

## Team

{% assign current_members = site.data.lab_members | where: "alumni", false %}
{% assign alumni_members = site.data.lab_members | where: "alumni", true %}

### Current Members
{% include member-grid.html members=current_members %}

### Alumni
{% include member-grid.html members=alumni_members %}

## Join Our Lab

### Graduate Students
I am actively recruiting PhD students interested in mathematical biology. Strong backgrounds in:
- Applied mathematics (PDEs, dynamical systems)
- Computational methods
- Biological sciences (complementary but not required)

are particularly welcome.

### Undergraduate Students
Motivated undergraduates can join through:
- Independent study projects
- Summer REU programs
- Honors thesis research

### Postdoctoral Fellows
Please contact me directly to discuss potential funding opportunities.

## Resources & Tools

### Software Developed
- **TDR** - Taxis-Diffusion-Reaction solver with non-local support.
- **FunPy** - [(i)PDE toolbox](https://github.com/adrs0049/funpy) for bifurcation analysis
- **AdhesionRandomWalk** - [Gillespie-SSA framework](https://github.com/adrs0049/AdhesionRandomWalk)

### Computational Resources
Our lab has access to high-performance computing resources for large-scale simulations.


## Lab Environment

We maintain a collaborative environment where ideas are shared openly and
everyone is welcome to contribute. Our weekly lab meetings provide a supportive
space for:

- Presenting research progress and getting feedback
- Discussing new papers and mathematical techniques
- Troubleshooting challenges together


