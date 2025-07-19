---
layout: publication
title: 'Drivemind: A Dual-vlm Based Reinforcement Learning Framework For Autonomous
  Driving'
authors: Wasif et al.
conference: Electronic Imaging
year: 2025
bibkey: wasif2025drivemind
citations: 742
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2506.00819'}]
tags: [Interpretability And Explainability, RAG, Distillation, Prompting, Agentic,
  Tools, Efficiency And Optimization, Reinforcement Learning, Multimodal Models, Responsible
    AI]
---
End-to-end autonomous driving systems map sensor data directly to control commands, but remain opaque, lack interpretability, and offer no formal safety guarantees. While recent vision-language-guided reinforcement learning (RL) methods introduce semantic feedback, they often rely on static prompts and fixed objectives, limiting adaptability to dynamic driving scenes. We present DriveMind, a unified semantic reward framework that integrates: (i) a contrastive Vision-Language Model (VLM) encoder for stepwise semantic anchoring; (ii) a novelty-triggered VLM encoder-decoder, fine-tuned via chain-of-thought (CoT) distillation, for dynamic prompt generation upon semantic drift; (iii) a hierarchical safety module enforcing kinematic constraints (e.g., speed, lane centering, stability); and (iv) a compact predictive world model to reward alignment with anticipated ideal states. DriveMind achieves 19.4 +/- 2.3 km/h average speed, 0.98 +/- 0.03 route completion, and near-zero collisions in CARLA Town 2, outperforming baselines by over 4% in success rate. Its semantic reward generalizes zero-shot to real dash-cam data with minimal distributional shift, demonstrating robust cross-domain alignment and potential for real-world deployment.