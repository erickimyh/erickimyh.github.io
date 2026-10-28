---
title: "Anisotropic Area-preserving Mean Curvature Flow"
excerpt: "Long-term dynamics of gradient flows for interfacial surface energies"
# order: 2
---

My [PhD thesis](https://escholarship.org/uc/item/6b0538wt) was devoted to studying the dynamics of an evolution called **anisotropic area-preserving mean curvature flow**. Roughly speaking, the evolution models the interfacial behavior of liquids and crystals as their surface tension tends towards an equilibrium state. My work brought together tools and perspectives from **optimization**, **dynamical systems**, **partial differential equations**, and **geometric measure theory**.

Mathematically, the flow can be thought of as a gradient flow of surface tension, within the space of sets of constrained volume. For most liquids, the surface tension is well-modeled by surface area. However, in certain cases, such as with crystals, the surface tension favors certain directions over others, so is modeled by a *weighted* surface area

$$ 
P_\phi(E) = \int_{\partial E} \phi(\nu_E) d\cal H^{n-1}.
$$

My work focused on the dynamics of this evolution for special types of anisotropies in dimension $$n=2$$ (see also [my publications](/_pages/publications.md)). It aimed to answer questions such as:
1. Does the evolution always converge to an equilibrium state, even if it starts from a "rough" initial set far from equilibrium?
2. Can we quantify how quickly the set converges to the limiting set?