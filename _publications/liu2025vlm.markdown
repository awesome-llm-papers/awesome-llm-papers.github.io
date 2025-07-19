---
layout: publication
title: 'VLM-E2E: Enhancing End-to-end Autonomous Driving With Multimodal Driver Attention
  Fusion'
authors: Liu et al.
conference: IEEE Transactions on Intelligent Transportation Systems
year: 2025
bibkey: liu2025vlm
citations: 164
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2502.18042'}]
tags: [RAG, Training Techniques, Attention Mechanism, Tools, Model Architecture, Multimodal
    Models, Datasets, Merging]
---
Human drivers adeptly navigate complex scenarios by utilizing rich
attentional semantics, but the current autonomous systems struggle to replicate
this ability, as they often lose critical semantic information when converting
2D observations into 3D space. In this sense, it hinders their effective
deployment in dynamic and complex environments. Leveraging the superior scene
understanding and reasoning abilities of Vision-Language Models (VLMs), we
propose VLM-E2E, a novel framework that uses the VLMs to enhance training by
providing attentional cues. Our method integrates textual representations into
Bird's-Eye-View (BEV) features for semantic supervision, which enables the
model to learn richer feature representations that explicitly capture the
driver's attentional semantics. By focusing on attentional semantics, VLM-E2E
better aligns with human-like driving behavior, which is critical for
navigating dynamic and complex environments. Furthermore, we introduce a
BEV-Text learnable weighted fusion strategy to address the issue of modality
importance imbalance in fusing multimodal information. This approach
dynamically balances the contributions of BEV and text features, ensuring that
the complementary information from visual and textual modality is effectively
utilized. By explicitly addressing the imbalance in multimodal fusion, our
method facilitates a more holistic and robust representation of driving
environments. We evaluate VLM-E2E on the nuScenes dataset and demonstrate its
superiority over state-of-the-art approaches, showcasing significant
improvements in performance.