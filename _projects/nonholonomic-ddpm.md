---
title: "Nonholonomic DDPM"
excerpt: "A diffusion model that learns a nonholonomic control policy from the score function of a horizontal diffusion process."
# header:
#   teaser: /assets/images/nonholonomic-ddpm.png
---

This pipeline trains a DDPM (Denoising Diffusion Probabilistic Model) which learns a nonholonomic control policy by finding the score function of a corresponding horizontal diffusion process.

In control theory, one is often concerned with policies to transport one distribution to another. For example, given a swarm of robots, how can you give instructions to move the swarm to a desired target? For a high-dimensional
