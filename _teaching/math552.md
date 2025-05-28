---
title: "Applied Scientific Computing (MATH 552)"
collection: teaching
type: "Undergraduate course"
permalink: /teaching/math552
venue: "University of Massachusetts Amherst, Department of Mathematics and Statistics"
excerpt: 'Introduction to the application of computational methods to models arising in science and engineering, concentrating mainly on the solution of partial differential equations.'
date: 2023-01-01
course_numer: 'MATH 552'
semester: 'Spring 2023'
location: "Amherst, MA, USA"
---

The goals of MATH552 are to expand on the foundational numerical
techniques explored in MATH551. A core topic
is the discussion of spatially extended systems (e.g. partial differential
equations), and time dependent systems (e.g. ordinary differential equations),
which frequently arise in physics, finance and biology.
Climate models, fluid models, airplane models, biological models, or
computer game physics rely on the accurate and efficient solving of
differential equations.

Since it is impossible to represent continuous objects on a computer, we
must discretize these functions. Three main methods are frequently employed:

- In **finite differences** functions are discretized on grids
    or lattices. Approximations to derivatives and integrals are derived
    using Taylor's theorem. We will encounter these first. While the general
    theory is straight forward, it turns out that establishing
    convergence will prove difficult in more advanced applications.

- **Finite elements** are a collection of methods in which the domain
    is divided into small pieces (i.e. finite elements). Triangulation algorithms
    are commonly used to generate these finite elements. On the finite elements
    the partial differential equations reduce to simple algebraic equations, which
    are assembled into large (non)linear systems and solved.

    An advantage of this method is that the method easily extends to irregularly
    shaped domains, and in addition to being a computational technique, it extends
    the analytical tools from functional analysis to the numerical discrete
    setting. Hence allowing the establishment of convergence results more
    easily than in the finite difference setting.

    Due to their theoretical complexity we will not consider finite element
    methods in this course.

- **Spectral methods** approximate functions using special functions
    such as the complex exponential (Fourier), Chebyshev polynomials, or many
    others depending on the domain and functions of interest.

In addition to our discussion of methods to discretize functions, we will
encounter a few more numerical linear algebra topics: (1)
Iterative linear system solvers such as the preconditioned conjugate
gradient and/or multigrid methods; and (2) eigenvalue problems and
the QR/QZ methods to approximate these eigenvalues using
Householder reflections. Beyond the techniques involving differential
equations (and time and interest permitting) we will discuss:

- Introduction to numerical methods for stochastic processes e.g.
Brownian motion, stochastic integration, stochastic differential equations. Stochastic
simulations of particle systems of chemical reactions via **Gillespie methods**.

- A brief introduction to **Monte Carlo** methods, and possible Markov
Chain Monte Carlo (MCMC) methods and discussing the Metropolis-Hastings algorithm.

- **Mathematical optimization techniques**. These are the core methods for
modern machine learning approaches.

## Projects

In lieu of a final exam, this class will feature a term project. You will be expected to give a
short 5-minute project proposal presentation, create a final report, and give a final project
presentation.

## Lecture Notes

Detailed lecture notes will be available.
