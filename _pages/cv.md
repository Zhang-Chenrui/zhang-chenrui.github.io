---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

[Download PDF CV]({{ base_path }}/files/Chenrui_s_final_Resume_for_research.pdf)

## Education

* **Ph.D. Computer Science** — University of California, Santa Barbara (Sep 2025 – present)

* **B.S. Computer Science**, minor Data Science — California State Polytechnic University, Pomona (Aug 2021 – Dec 2025)  
  GPA 3.9/4.0. Cal-Bridge Scholar; President’s Honor List 2021–2023.  
  Relevant coursework: computer vision, CUDA programming, machine learning.

## Research interests

Machine learning on graphs; LLMs with graphs; representation learning.

## Experience

* **Visiting Student** — Wang Lab, UC San Diego (Mar 2025 – Aug 2025)  
  *Advisor: Prof. Yusu Wang*  
  - AGOP interpretability for graph neural networks: extended AGOP from MLPs to GNNs; feature- and edge-level analysis benchmarked against GNNExplainer and ground truth; adjacency-power metrics for explanation alignment; experiments across linear/ReLU and non-ReLU GCN variants.  
  - Structure-aware modeling / Set2Graph: synthetic detector-style data with Gaussian mixture models; graph- and geometry-based architectures (3D Graph U-Net, Set2Graph, geometric transformers); dynamic-k regularization and multi-loss training for center prediction and activity classification.

* **NSF-Sponsored Research Assistant** — Mobility Scooter Lab, Cal Poly Pomona (May 2023 – Jan 2025)  
  *Advisor: Prof. Tingting Chen*  
  - Multimodal pipeline aligning pose keypoints with motion sensors; transformer encoder replacing LSTM with self-attention over nodes and time; ablations and hyperparameter studies; kinematic evaluation metrics from keypoints.

* **Machine Learning Engineer Intern** — Character Face Generation (CFG) (May 2024 – Sep 2024)  
  *Supervisor: Amrish Baskaran*  
  - Mesh semantic segmentation with Mesh Transformer (MeT); triangle-, vertex–edge-, and Laplacian-graph representations; edge attention and pooling for high-curvature regions; regional vertex offsets; geodesic and curvature evaluation.

* **Teaching Assistant** — Computer Science Department, Cal Poly Pomona (Aug 2024 – present)  
  *Supervisor: Prof. Hao Ji*  
  - Grading and support for CUDA, parallel algorithms, and GPU optimization; lectures on self-attention and applications in NLP and ViT.

## Skills

* **Languages:** Python, C/C++, Kotlin, Java, Bash  
* **Frameworks:** PyTorch, PyTorch Geometric, OpenCV, NumPy, CUDA, Pandas  
* **Tools:** Git, Linux, Docker, REST APIs, MySQL

## Publications

  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

## Service and honors

* Cal-Bridge Fellowship (doctoral support)
