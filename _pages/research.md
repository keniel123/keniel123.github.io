---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---

{% include base_path %}

My research asks a simple question: **how can machines understand human motion when cameras alone aren't enough?** Answering it has taken me across computer vision, 3D human modelling, differentiable simulation, and radar signal processing — usually all at once.

> **A note on what's listed here.** Several first-author manuscripts from this work are currently under double-blind review, so the descriptions below stay deliberately high-level. The published work is linked in full.

Temporally coherent 3D humans from video
======

Most human mesh recovery models treat video as a stack of independent frames, producing jittery, implausible motion. I designed a structured transformer decoder that recovers the **full expressive body — body, hands, and face — from monocular video**, with temporal coherence built in as a first-class objective rather than a post-processing step.

The system fine-tunes a ViT-Huge-scale vision foundation backbone parameter-efficiently (LoRA) with mixed-precision training and model distillation, and is evaluated across **12 datasets totalling ~12 million samples**, achieving state-of-the-art whole-body accuracy on standard benchmarks. *First-author manuscript under review.*

Differentiable radar simulation for human sensing
======

Radar is a compelling sensor for human activity understanding — it works in darkness, through occlusion, and without capturing identifiable images. But labelled radar data is scarce and expensive to collect. I build **differentiable, mesh-faithful simulators that render radar micro-Doppler directly from animated 3D human body meshes**, distilled from expensive physical-optics renders across seven motion datasets and 60/77 GHz radar platforms.

Synthetic data from these simulators improves real-world zero-shot recognition by **+7.4 pp overall and +8.0 pp in an unseen room** — without a single new radar capture. *First-author manuscript under review.*

Do vision foundation models transfer beyond vision?
======

Spectrograms aren't natural images, yet the question of whether frozen vision foundation models can read them was surprisingly open. I benchmarked **frozen DINOv2, CLIP, and MAE features on radar and WiFi micro-Doppler recognition under cross-sensor shift**, against CNN, JEPA, and generative adaptation baselines.

The headline: a frozen DINOv2 probe **more than doubles cross-sensor recognition** over the strongest matched CNN, while extra synthetic augmentation doesn't move frozen-feature performance — evidence that cross-sensor recognition is first and foremost a *representation transfer* problem. *First-author manuscript under review.*

Radar-based neuroimaging <span style="font-size:.65em; vertical-align:middle;">(published)</span>
======

Can radar see inside the head? With colleagues at Southampton I studied the **feasibility of radar for non-invasive brain imaging and tumour detection**, simulating electromagnetic interactions in anatomical brain-tissue models (Ansys HFSS) and evaluating signal penetration, fidelity, and safety across Patch and Vivaldi antenna configurations.

The work was published at **IEEE EMBC 2024** ([paper](/publication/2024-embc-radar-neuroimaging)), presented as an **oral talk** in Orlando, and received the **IEEE EMBC NextGen Scholar Award**.

Earlier research
======

* **Universal Gene Transformer** (MSc thesis, Distinction) — a 1D-CNN + self-attention classifier over 60,660-gene TCGA RNA-seq profiles spanning 33 cancer subtypes, reaching 92–94% accuracy and matching or beating published baselines without manual feature selection; an explainability pipeline converted saliency maps into gene-effect scores that recovered known biomarkers via TCGA cross-reference and MSigDB enrichment.
* **Cooperative swarm robotics for disaster response** — a heterogeneous swarm of Thymio ground robots and Tello drones with a virtual mesh network, delivered as a [physical demonstrator](/portfolio/swarm-robotics-disaster-response/) with DSTL as industry sponsor.
* **Self-supervised motion transfer** — a faithful [reimplementation](/portfolio/latent-image-animator/) of a latent image animator that animates still images from driving video, reproducing the full training and evaluation pipeline.
