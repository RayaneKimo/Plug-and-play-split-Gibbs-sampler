# Plug-and-Play Split Gibbs Sampler with Inpainting Problems

This repository provides a Python implementation of the **Plug-and-Play Split Gibbs Sampler (PnP-SGS)** algorithm for imaging inverse problems, integrating deep generative priors into Bayesian inference. The original paper is [here](https://arxiv.org/pdf/2304.11134).

## Overview

PnP-SGS combines variable splitting, Gibbs Sampling, and Denoising Diffusion Probabilistic Models (DDPM) for efficient posterior distribution sampling. Unlike traditional methods that offer point estimates, PnP-SGS provides comprehensive insights into the posterior distribution, which can enhance applications in image reconstruction, inpainting and super-resolution.
In this case, we

### Key Features
- **Variable Splitting**: Separates fidelity and regularization terms to allow flexibility in solving complex imaging problems.
- **Stochastic Denoising with DDPM**: Uses pre-trained DDPMs within the Gibbs Sampling framework, allowing for adaptive regularization.
- **Comparative Approach**: Benchmarks the PnP-SGS method against Diffusion Posterior Sampling (DPS) to evaluate performance in tasks like image inpainting.


