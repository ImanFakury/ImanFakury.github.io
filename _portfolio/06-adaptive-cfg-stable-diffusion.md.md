---
title: "Norm-Regulated Adaptive Classifier-Free Guidance for Stable Diffusion"
excerpt: "Training-free adaptive CFG mechanism using conditional–unconditional conflict scaling and EMA smoothing, evaluated with CLIP and LPIPS."
collection: portfolio
---

*Jan. 2026* · [GitHub Repository](https://github.com/ImanFakury/GITHUB_REPO_URL)

* Proposed an adaptive Classifier-Free Guidance (CFG) mechanism for diffusion models that dynamically adjusts guidance strength based on conditional–unconditional prediction conflict.
* Introduced exponential scaling and EMA smoothing to stabilize guidance without retraining or extra UNet forward passes.
* Built an evaluation framework for Stable Diffusion comparing fixed, scheduled, and adaptive guidance via CLIP score, LPIPS diversity, and image quality metrics.