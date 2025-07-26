---
layout: publication
title: 'Controlnext: Powerful And Efficient Control For Image And Video Generation'
authors: Bohao Peng, Jian Wang, Yuechen Zhang, Wenbo Li, Ming-chang Yang, Jiaya Jia
conference: No Venue
year: 2024
bibkey: peng2024controlnext
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/hf2408.06070'}]
tags: ["Fine-Tuning", "Model Architecture", "Security", "Training Techniques"]
short_authors: Peng et al.
---
Diffusion models have demonstrated remarkable and robust abilities in both image and video generation. To achieve greater control over generated results, researchers introduce additional architectures, such as ControlNet, Adapters and ReferenceNet, to integrate conditioning controls. However, current controllable generation methods often require substantial additional computational resources, especially for video generation, and face challenges in training or exhibit weak control. In this paper, we propose ControlNeXt: a powerful and efficient method for controllable image and video generation. We first design a more straightforward and efficient architecture, replacing heavy additional branches with minimal additional cost compared to the base model. Such a concise structure also allows our method to seamlessly integrate with other LoRA weights, enabling style alteration without the need for additional training. As for training, we reduce up to 90% of learnable parameters compared to the alternatives. Furthermore, we propose another method called Cross Normalization (CN) as a replacement for Zero-Convolution' to achieve fast and stable training convergence. We have conducted various experiments with different base models across images and videos, demonstrating the robustness of our method.

https://huggingface.co/discussions/paper/66bac5924de574a3296832b8