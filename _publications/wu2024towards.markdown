---
layout: publication
title: Towards Better Text-to-image Generation Alignment Via Attention Modulation
authors: Wu et al.
conference: 2023 IEEE/CVF International Conference on Computer Vision (ICCV)
year: 2024
bibkey: wu2024towards
citations: 51
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2404.13899'}]
tags: [ICCV, Training Techniques, Attention Mechanism, Prompting, Transformer, Model
    Architecture, Reinforcement Learning, Merging]
---
In text-to-image generation tasks, the advancements of diffusion models have
facilitated the fidelity of generated results. However, these models encounter
challenges when processing text prompts containing multiple entities and
attributes. The uneven distribution of attention results in the issues of
entity leakage and attribute misalignment. Training from scratch to address
this issue requires numerous labeled data and is resource-consuming. Motivated
by this, we propose an attribution-focusing mechanism, a training-free
phase-wise mechanism by modulation of attention for diffusion model. One of our
core ideas is to guide the model to concentrate on the corresponding syntactic
components of the prompt at distinct timesteps. To achieve this, we incorporate
a temperature control mechanism within the early phases of the self-attention
modules to mitigate entity leakage issues. An object-focused masking scheme and
a phase-wise dynamic weight control mechanism are integrated into the
cross-attention modules, enabling the model to discern the affiliation of
semantic information between entities more effectively. The experimental
results in various alignment scenarios demonstrate that our model attain better
image-text alignment with minimal additional computational cost.