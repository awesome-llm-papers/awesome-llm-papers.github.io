---
layout: publication
title: 'SNOOPI: Supercharged One-step Diffusion Distillation With Proper Guidance'
authors: Viet Nguyen, Anh Aengus Nguyen, Trung Dao, Khoi Nguyen, Cuong Pham, Toan
  Tran, Anh Tran
conference: No Venue
year: 2024
bibkey: nguyen2024snoopi
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/hf2412.02687'}]
tags: ["Efficiency", "Evaluation", "Prompting", "Tools", "Training Techniques"]
short_authors: Nguyen et al.
---
Recent approaches have yielded promising results in distilling multi-step text-to-image diffusion models into one-step ones. The state-of-the-art efficient distillation technique, i.e., SwiftBrushv2 (SBv2), even surpasses the teacher model's performance with limited resources. However, our study reveals its instability when handling different diffusion model backbones due to using a fixed guidance scale within the Variational Score Distillation (VSD) loss. Another weakness of the existing one-step diffusion models is the missing support for negative prompt guidance, which is crucial in practical image generation. This paper presents SNOOPI, a novel framework designed to address these limitations by enhancing the guidance in one-step diffusion models during both training and inference. First, we effectively enhance training stability through Proper Guidance-SwiftBrush (PG-SB), which employs a random-scale classifier-free guidance approach. By varying the guidance scale of both teacher models, we broaden their output distributions, resulting in a more robust VSD loss that enables SB to perform effectively across diverse backbones while maintaining competitive performance. Second, we propose a training-free method called Negative-Away Steer Attention (NASA), which integrates negative prompts into one-step diffusion models via cross-attention to suppress undesired elements in generated images. Our experimental results show that our proposed methods significantly improve baseline models across various metrics. Remarkably, we achieve an HPSv2 score of 31.08, setting a new state-of-the-art benchmark for one-step diffusion models.

https://huggingface.co/discussions/paper/674fd501696ab96e570221b8