---
layout: publication
title: Cf-vlm:counterfactual Vision-language Fine-tuning
authors: Zhang et al.
conference: 2020 IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR)
year: 2025
bibkey: zhang2025cf
citations: 85
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2506.17267'}]
tags: [Interpretability And Explainability, Training Techniques, Tools, CVPR, Evaluation,
  Reinforcement Learning, Fine Tuning, Multimodal Models, Datasets]
---
Recent advances in vision-language models (VLMs) have greatly improved cross-modal semantic understanding, yet significant limitations remain in fine-grained discrimination and deep causal reasoning tasks. Existing VLMs often rely on superficial statistical correlations, lacking the ability to capture the underlying causal logic between visual and textual content. To address this, we propose CounterFactual Vision-Language Fine-tuning (CF-VLM), a novel framework that enhances the causal reasoning capabilities of VLMs through the targeted use of counterfactual samples. CF-VLM introduces three complementary training objectives: maintaining foundational cross-modal alignment, reinforcing the uniqueness and stability of factual scene representations against coherent counterfactuals, and sharpening the model's sensitivity to minimal but critical causal edits. Extensive experiments demonstrate that CF-VLM consistently outperforms strong baselines and state-of-the-art methods on compositional reasoning and generalization benchmarks. Furthermore, it shows promise in mitigating visual hallucinations, indicating improved factual consistency. Our CF-VLM provides a robust foundation for deploying VLMs in high-stakes, real-world scenarios requiring reliable reasoning and interpretability.