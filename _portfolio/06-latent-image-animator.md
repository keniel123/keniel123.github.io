---
title: "Latent Image Animator — Reimplementation"
excerpt: "A faithful reimplementation of a self-supervised motion-transfer method that animates still images from driving video, reproducing the full training and benchmark evaluation pipeline."
collection: portfolio
permalink: /portfolio/latent-image-animator/
---

Reproducibility work on a self-supervised motion-transfer method: animating a still image by applying **latent-space linear transformations** learned from a driving video, with no paired supervision.

The project reimplemented the method from the paper, reproduced the full training pipeline, and evaluated transfer fidelity and temporal coherence on standard video benchmarks — a useful exercise in how much of a published result survives independent reimplementation.

**Stack:** PyTorch, OpenCV, NumPy, self-supervised learning

**Code:** [github.com/keniel123/latent-image-animator](https://github.com/keniel123/latent-image-animator)
