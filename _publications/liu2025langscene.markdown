---
layout: publication
title: 'Langscene-x: Reconstruct Generalizable 3D Language-embedded Scenes With Trimap
  Video Diffusion'
authors: Fangfu Liu, Hao Li, Jiawei Chi, Hanyang Wang, Minghui Yang, Fudong Wang,
  Yueqi Duan
conference: No Venue
year: 2025
bibkey: liu2025langscene
additional_links: [{name: Code, url: 'https://liuff19.github.io/LangScene-X'}, {name: Code,
    url: 'https://huggingface.co/discussions/paper/686735e69db35afc9c304ce8'}, {name: Paper,
    url: 'https://arxiv.org/abs/hf2507.02813'}]
tags: ["Datasets", "Efficiency", "Has Code", "Tools"]
short_authors: Liu et al.
---
Recovering 3D structures with open-vocabulary scene understanding from 2D images is a fundamental but daunting task. Recent developments have achieved this by performing per-scene optimization with embedded language information. However, they heavily rely on the calibrated dense-view reconstruction paradigm, thereby suffering from severe rendering artifacts and implausible semantic synthesis when limited views are available. In this paper, we introduce a novel generative framework, coined LangScene-X, to unify and generate 3D consistent multi-modality information for reconstruction and understanding. Powered by the generative capability of creating more consistent novel observations, we can build generalizable 3D language-embedded scenes from only sparse views. Specifically, we first train a TriMap video diffusion model that can generate appearance (RGBs), geometry (normals), and semantics (segmentation maps) from sparse inputs through progressive knowledge integration. Furthermore, we propose a Language Quantized Compressor (LQC), trained on large-scale image datasets, to efficiently encode language embeddings, enabling cross-scene generalization without per-scene retraining. Finally, we reconstruct the language surface fields by aligning language information onto the surface of 3D scenes, enabling open-ended language queries. Extensive experiments on real-world data demonstrate the superiority of our LangScene-X over state-of-the-art methods in terms of quality and generalizability. Project Page: https://liuff19.github.io/LangScene-X.

https://huggingface.co/discussions/paper/686735e69db35afc9c304ce8