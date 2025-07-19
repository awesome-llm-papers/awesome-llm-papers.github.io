---
layout: publication
title: Localizing Knowledge In Diffusion Transformers
authors: Zarei et al.
conference: 2021 IEEE/CVF International Conference on Computer Vision (ICCV)
year: 2025
bibkey: zarei2025localizing
citations: 57
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2505.18832'}]
tags: [Interpretability And Explainability, ICCV, Training Techniques, Tools, Transformer,
  Model Architecture, Applications, Fine Tuning, Merging]
---
Understanding how knowledge is distributed across the layers of generative models is crucial for improving interpretability, controllability, and adaptation. While prior work has explored knowledge localization in UNet-based architectures, Diffusion Transformer (DiT)-based models remain underexplored in this context. In this paper, we propose a model- and knowledge-agnostic method to localize where specific types of knowledge are encoded within the DiT blocks. We evaluate our method on state-of-the-art DiT-based models, including PixArt-alpha, FLUX, and SANA, across six diverse knowledge categories. We show that the identified blocks are both interpretable and causally linked to the expression of knowledge in generated outputs. Building on these insights, we apply our localization framework to two key applications: model personalization and knowledge unlearning. In both settings, our localized fine-tuning approach enables efficient and targeted updates, reducing computational cost, improving task-specific performance, and better preserving general model behavior with minimal interference to unrelated or surrounding content. Overall, our findings offer new insights into the internal structure of DiTs and introduce a practical pathway for more interpretable, efficient, and controllable model editing.