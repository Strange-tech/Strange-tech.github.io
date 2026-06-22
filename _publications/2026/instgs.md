---
title: >-
  InstGS: Shared-Template Gaussian Instancing for Object-Redundancy-Free Rendering
authors:
  - Ziang Lu
  - Kang Du
  - Xinyao Wei
  - ZhangQian
  - John Li
  - Dong Liang✉
  - Zeyu Wang✉
  - Jinyuan Jia✉
date: 2026-09-01
pub: ECCV 2026
cover: /assets/images/covers/cover_instgs.png
selected: true
abstract: >-
  3D Gaussian Splatting (3DGS) and Neural Radiance Fields (NeRF) have demonstrated remarkable capabilities in photo-realistic novel view synthesis. However, their practical adoption is often hindered by substantial storage requirements and limited rendering efficiency, particularly for scenes with repetitive structures. While existing acceleration methods primarily focus on optimizing individual Gaussian primitives or neural network architectures, they fail to address the fundamental redundancy inherent in repetitive content. To overcome this limitation, we introduce InstGS, the first Gaussian instancing-based accelerated rendering framework. To eliminate redundancy at the representation level, we perform gradient-driven cross-frame instance segmentation to group similar Gaussians into reusable components. A shared Gaussian template with instance-specific offsets is optimized to replace all similar instances, yielding substantial memory saving with negligible loss in visual fidelity. Extensive experiments demonstrate that InstGS achieves high-quality, high-frame-rate, and low-memory rendering performance.
links:
  - ["project page", "https://strange-tech.github.io/InstGS-homepage"]
  - ["pdf", ""]
  - ["code", "https://github.com/Strange-tech/InstGS"]
semantic_scholar_id: ""
---

<!-- 
  ABSTRACT: Replace "TODO: Write your abstract here." above with your actual abstract.
  Leave the rest of the frontmatter (between --- and ---) as is.

  Optional fields you can add:
    links:
      - ["pdf", "https://your-pdf-link"]
      - ["arXiv", "https://arxiv.org/abs/xxxx.xxxxx"]
      - ["code", "https://github.com/xxx/xxx"]
    semantic_scholar_id: "your-paper-id-here"
    pub_pre: "In "
    pub_post: ""
    pub_date: ""
-->
