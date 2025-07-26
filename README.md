# bayesian-dl
Bayesian Deep Learning: Bayesian reasoning, Uncertainty quantification, Variational Autoencoders

# Bayesian Deep Learning (UCL MSc Coursework)

This repository contains a collection of Jupyter notebooks developed for the Bayesian Deep Learning module at UCL. Each notebook demonstrates a core concept in probabilistic machine learning, including uncertainty quantification, Bayesian inference, and generative modeling.

## 📚 Notebooks Overview

All notebooks are fully self-contained with inline documentation and visual outputs.

### Uncertainty Quantification in Regression
- Implements Bayesian linear regression using conjugate priors.
- Decomposes predictive uncertainty into epistemic and aleatoric components.
- Visualizes confidence intervals and compares with frequentist predictions.

### Bayesian Classifiers
- Builds Gaussian-distributed logistic regression and Naive Bayes classifiers.
- Visualizes decision boundaries and predictive uncertainty.
- Evaluates performance on both linearly and non-linearly separable datasets.

### Variational Autoencoder (VAE)
- Implements a VAE in PyTorch using the reparameterization trick.
- Optimizes the ELBO to learn structured latent representations.
- Generates novel samples and visualizes latent space dynamics.

### The Seven Scientists Problem
- Simulates Bayesian belief updates in a multi-agent setting.
- Models how agents with noisy observations and different priors reach (or fail to reach) consensus.
- Explores effects of observation noise and prior bias on belief convergence.

## 🧠 Core Concepts Covered
- Bayesian linear and logistic regression
- Predictive posterior distributions
- Uncertainty decomposition
- Variational inference and ELBO optimization
- Generative modeling with VAEs
- Belief updating and probabilistic reasoning

## 🛠️ Requirements

Install dependencies using pip:
numpy, scipy, matplotlib, seaborn, torch, torchvision

