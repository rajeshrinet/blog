---
toc: true
layout: post
description: Statistical field theory without time-reversal symmetry
categories: [markdown]
title: Splitting and self-propelling active droplets
sticky_rank: 2
---

### Splitting active droplets
<img src="https://raw.githubusercontent.com/rajeshrinet/pystokes-misc/master/gallery/droplets/active_stress.jpg" alt="drawing" width="400"/>

Microphase separation is often observed in suspensions of spherical active particles. In such suspensions, the scalar concentration is the only order parameter, when there is no orientational order in the bulk. At a continuum level, coupling the scalar density to fluid flow, there are two distinct explanations. Each involves an effective interfacial tension: the first mechanical (causing flow) and the second diffusive (causing Ostwald ripening). Here we show how the negative mechanical tension of contractile swimmers creates, via a self-shearing instability, a steady-state life cycle of droplet growth interrupted by division whose scaling behavior we predict. When the diffusive tension is also negative, this is replaced by an arrested regime (mechanistically distinct, but with similar scaling) where division of small droplets is prevented by reverse Ostwald ripening.

![](https://raw.githubusercontent.com/rajeshrinet/pystokes-misc/master/gallery/droplets/ssi.gif)

Our starting point is a scalar field theory with mass and momentum conservation (model H). A self-shearing instability is obtained if active extensile stress, which does not respect time-reversal symmetry, is added to the momentum conservation equation in model H. This instability interrupts the growth of droplets by splitting them. The extensile active stress has the effect of reversing the sign of the effective tension which arrests the growth. This is balanced by Ostwald ripening: small droplets evaporate while large ones grow until they in turn become unstable. The result is a dynamical steady state maintained by the self-shearing instability. 


Reference: [Rajesh Singh and Michael E. Cates. Phys. Rev. Lett. 123, 148005 (2019)](https://doi.org/10.1103/PhysRevLett.123.148005)



<br/><br/>

## Self-propelling active droplets

![](https://raw.githubusercontent.com/rajeshrinet/pystokes-misc/master/gallery/droplets/ssb.jpg) 

In this work, we present a model of self-propulsion in active droplets, such as cells, by extending the above theory to two scalar fields. The two scalar fields, in the case of a cell, represent the cytoplasm and a contractile cortex. An active stress couples the two scalar fields. The self-propulsion results from the activity when rotational symmetry is spontaneously broken. We find, both analytically and numerically, that the swimming speed does not depend on the radius of the droplet, while it varies linearly with the activity parameter and with the droplet area fraction.

I have also developed, [PyGL](https://github.com/rajeshrinet/pygl), a numerical library for statistical field theory in Python. The library has been specifically designed to study field theories without time-reversal symmetry. The library constructs differentiation matrices using finite-difference and spectral methods. To study the role of momentum conservation, the library also allows computing fluid flow from the solution of the Stokes equation.

Reference: [Rajesh Singh, Elsen Tjhung, and Michael E. Cates. Phys. Rev. Research 2, 032024(R) (2020)](https://journals.aps.org/prresearch/abstract/10.1103/PhysRevResearch.2.032024)