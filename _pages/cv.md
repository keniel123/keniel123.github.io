---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

<a href="{{ base_path }}/files/Keniel_Peart_CV.pdf" class="btn btn--primary"><i class="fas fa-download" aria-hidden="true"></i> Download CV (PDF)</a>

Machine learning researcher working across computer vision, 3D human modelling, differentiable radar simulation, foundation-model transfer, and sensor-based perception. I build end-to-end AI systems — from dataset collection and model design through rigorous evaluation to deployment on real sensing hardware — with prior industry experience leading production software teams.

Education
======

* **PhD in Artificial Intelligence**, University of Southampton, 2022–present
  * UKRI MINDS CDT Studentship (supervisor: Dr Shelly Vishwakarma)
* **MSc in Artificial Intelligence (Distinction)**, University of Southampton, 2021–2022
  * Thesis: *Universal Gene Transformer: Cancer Subtype Classification using RNA-Seq Data* (supervisor: Dr Jo Grundy)
* **BSc in Computer Science (Distinction)**, University of the West Indies, Mona, Jamaica, 2014–2017
  * Thesis: *An Evolutionary Approach to Training Intelligent Agents using NEAT* (supervisor: Dr Gunjan Mansingh)

Professional experience
======

**PhD Researcher — Radar-based AI, Human Motion Modelling & Sensor Simulation**
*University of Southampton · 2022–present*

* Developed a temporally coherent whole-body 3D human mesh recovery framework for reconstructing motion from monocular video, using PyTorch, LoRA/PEFT fine-tuning, mixed-precision training, and model distillation; evaluated across 12 datasets (~12M samples) with state-of-the-art whole-body accuracy *(manuscript under review)*
* Built a differentiable sensor-simulation pipeline that generates synthetic radar micro-Doppler data directly from 3D human motion, enabling scalable training-data augmentation for activity and gesture recognition without new radar captures *(manuscript under review)*
* Adapted vision foundation models (DINOv2, CLIP, MAE) for radar and WiFi spectrogram recognition, studying cross-modal transfer under sensor shift *(manuscript under review)*
* Designed multimodal data collection and evaluation pipelines integrating TI mmWave radar, Azure Kinect, OpenCV, MATLAB, and signal-processing workflows — including radar-based neuroimaging work published at **IEEE EMBC 2024** (oral presentation; NextGen Scholar Award)
* Optimised ML workflows for efficient training and deployment using CUDA, TensorRT, NVIDIA DALI, mixed precision, and model compression
* Developed robotics and edge-AI prototypes with ROS, NVIDIA Jetson, Arduino, and MQTT for heterogeneous swarm robotics and disaster-response applications

**Masters Researcher**
*University of Southampton · 2021–2022*

* Built an end-to-end deep learning model combining 1D convolutions and multi-head self-attention for cancer subtype classification from high-dimensional gene expression data, achieving 92–94% accuracy across 33 subtypes and outperforming deep learning and classical baselines
* Designed an explainability pipeline using saliency maps and gene-effect scores to identify candidate biomarkers, validated against established cancer databases
* Reimplemented a self-supervised motion-transfer method for animating still images via latent-space transformations from driving video

**Technical Lead / Scrum Master / Lead Software Developer**
*NCB Financial Group, Kingston, Jamaica · 2018–2021*

* Led delivery of Jamaica's first online mortgage portal and centralised lending platform, reducing application time from weeks to 3 days and digitising 80% of the lending process
* Architected microservices, testing, and analytics infrastructure; contributed to **$200M+ annual cost reduction** and drove Kubernetes enablement across engineering teams
* Presented architecture proposals and delivery updates to C-suite stakeholders

Technical skills
======

* **AI & deep learning:** PyTorch, TensorFlow, Hugging Face Transformers, DINOv2, CLIP, MAE, DeepSpeed, RAPIDS cuML, TensorRT
* **Training & optimisation:** LoRA, mixed precision, model distillation, multi-GPU / multi-node training, HPC, DALI
* **Architectures:** Transformers, 1D CNNs, Mamba, Mixture of Experts, Diffusion, Flow Matching
* **LLM & retrieval:** RAG pipelines, embedding models, reranking, vector search, agentic workflows
* **Evaluation:** benchmark design, ablation studies, cross-domain evaluation, macro-F1, MCC, cross-validation, retrieval metrics
* **Programming:** Python, C++, Java, JavaScript, TypeScript, MATLAB
* **3D & simulation:** SMPL-X, differentiable simulation / rendering, Ansys HFSS, Blender, Open3D, Trimesh, PyVista, OpenCV
* **Hardware & sensors:** FMCW radar, micro-Doppler, TI 77 GHz radar, Infineon radar, Azure Kinect / RGB-D, Jetson, Raspberry Pi, ROS
* **Infrastructure:** Docker, Kubernetes, CI/CD, Git

Publications
======

<ul>{% for post in site.publications reversed %}
  {% include archive-single-cv.html %}
{% endfor %}</ul>

*Three further first-author manuscripts are currently under review at international machine learning and computer vision venues.*

Talks & demonstrations
======

<ul>{% for post in site.talks reversed %}
  {% include archive-single-talk-cv.html %}
{% endfor %}</ul>

Teaching
======

<ul>{% for post in site.teaching reversed %}
  {% include archive-single-cv.html %}
{% endfor %}</ul>

Awards & scholarships
======

* **IEEE EMBC NextGen Scholar Award** (2024)
* **Best Demonstration Award**, ECS Student Showcase (2026)
* **Chevening Scholarship** (2021)
* **UKRI MINDS CDT Studentship** (2022)
* Dean's List (2016–2017), Letters of Commendation (2014–2016), UWIDEF and Flow Foundation Jamaica Merit-Based Scholarships — University of the West Indies

Certifications
======

* Neural Networks and Deep Learning — DeepLearning.AI
* AI For Everyone — DeepLearning.AI
* Advanced Certified Scrum Developer (A-CSD) — Scrum Alliance
* Certified ScrumMaster (CSM) — Scrum Alliance
* Agile Project Management (ICP-ACM) — ICAgile / Cprime
* Enterprise Design Thinking Practitioner & Team Essentials for AI — IBM
