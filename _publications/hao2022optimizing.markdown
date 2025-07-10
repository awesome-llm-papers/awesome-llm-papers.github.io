---
layout: publication
title: Optimizing Prompts For Text-to-image Generation
authors: Yaru Hao, Zewen Chi, Li Dong, Furu Wei
conference: Arxiv
year: 2022
citations: 32
bibkey: hao2022optimizing
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2212.09611'}]
tags: [Fine-Tuning, RAG, Reinforcement Learning, Tools, Prompting, Agentic, Training
    Techniques, Evaluation, Merging]
---
Well-designed prompts can guide text-to-image models to generate amazing
images. However, the performant prompts are often model-specific and misaligned
with user input. Instead of laborious human engineering, we propose prompt
adaptation, a general framework that automatically adapts original user input
to model-preferred prompts. Specifically, we first perform supervised
fine-tuning with a pretrained language model on a small collection of manually
engineered prompts. Then we use reinforcement learning to explore better
prompts. We define a reward function that encourages the policy to generate
more aesthetically pleasing images while preserving the original user
intentions. Experimental results on Stable Diffusion show that our method
outperforms manual prompt engineering in terms of both automatic metrics and
human preference ratings. Moreover, reinforcement learning further boosts
performance, especially on out-of-domain prompts. The pretrained checkpoints
are available at https://aka.ms/promptist. The demo can be found at
https://aka.ms/promptist-demo.