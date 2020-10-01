---
toc: true
layout: post
description: Field theories without time-reversal symmetry in Python
categories: [markdown]
title: PyGL
sticky_rank: 2
---

## About 
![Imagel](https://raw.githubusercontent.com/rajeshrinet/pygl/master/examples/banner.jpeg)


[PyGL](https://github.com/rajeshrinet/pygl) is a numerical library to simulate field theories without time-reversal symmetry in Python. The name GL corresponds to the [Ginzburg–Landau](https://en.wikipedia.org/wiki/Ginzburg%E2%80%93Landau_theory) theory. The library constructs differentiation matrices using finite-difference and spectral methods. The library also allows to compute fluid flow on a 2D or 3D grid from the solution of the Stokes equation using a spectral solver.

<br/><br/>

## Research applications of PyStokes

In what follows, we present we present a selected list of research applications of PyStokes. 

## Self-shearing instability in active matter

Reference: [Rajesh Singh and Michael E. Cates. Phys. Rev. Lett. 123, 148005 (2019)](https://doi.org/10.1103/PhysRevLett.123.148005)

![](https://raw.githubusercontent.com/rajeshrinet/pygl/master/examples/ssi.gif)

Suspensions of spherical active particles often show microphase separation. At a continuum level, coupling their scalar density to fluid flow, there are two distinct explanations. Each involves an effective interfacial tension: the first mechanical (causing flow) and the second diffusive (causing Ostwald ripening). Here we show how the negative mechanical tension of contractile swimmers creates, via a self-shearing instability, a steady-state life cycle of droplet growth interrupted by division whose scaling behavior we predict. When the diffusive tension is also negative, this is replaced by an arrested regime (mechanistically distinct, but with similar scaling) where division of small droplets is prevented by reverse Ostwald ripening.

<br/><br/>

## Self-propulsion of active droplets without liquid-crystalline order
![](https://raw.githubusercontent.com/rajeshrinet/pystokes-misc/master/gallery/active_droplets.JPG) 
Reference: [Rajesh Singh, Elsen Tjhung, and Michael E. Cates. Phys. Rev. Research 2, 032024(R) (2020)](https://journals.aps.org/prresearch/abstract/10.1103/PhysRevResearch.2.032024)

This work presents a two dimensional model of self-propulsion in active droplets, such as cells, involving two scalar fields, representing the cytoplasm and a contractile cortex. An active stress couples the two scalar fields. The self-propulsion results from the activity when rotational symmetry is spontaneously broken.