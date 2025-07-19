---
layout: publication
title: Task Reconstruction And Extrapolation For \(\pi_0\) Using Text Latent
authors: Li Quanyi
conference: Journal of Mathematical Analysis and Applications
year: 2025
bibkey: li2025task
citations: 125
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2505.03500'}]
tags: [RAG, Prompting, Evaluation, Security, Applications, Multimodal Models, Datasets]
---
Vision-language-action models (VLAs) often achieve high performance on demonstrated tasks but struggle significantly when required to extrapolate, combining skills learned from different tasks in novel ways. For instance, VLAs might successfully put the cream cheese in the bowl and put the bowl on top of the cabinet, yet still fail to put the cream cheese on top of the cabinet. In this work, we demonstrate that behaviors from distinct tasks can be effectively recombined by manipulating the VLA's internal representations at inference time. Concretely, we identify the text latent by averaging the text tokens' hidden states across all demonstrated trajectories for a specific base task. For executing an extrapolated task, we can temporally interpolate the text latent of the two base tasks and add it back to the text hidden states, so sub-behaviors from the two tasks will be activated sequentially. We evaluate this approach using the newly created libero-ood benchmark, featuring 20 tasks extrapolated from standard LIBERO suites. The results on libero-ood show that all SOTA VLAs achieve < 15% success rate, while \\(\pi0\\) with text latent interpolation reaches an 83% success rate. Further qualitative analysis reveals a tendency for VLAs to exhibit spatial overfitting, mapping object names to demonstrated locations rather than achieving genuine object and goal understanding. Additionally, we find that decoding the text latent yields human-unreadable prompts that can nevertheless instruct the VLA to achieve a 70% success rate on standard LIBERO suites, enabling private instruction or backdoor attacks.