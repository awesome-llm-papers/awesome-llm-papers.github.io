---
layout: publication
title: 'Add-it: Training-free Object Insertion In Images With Pretrained Diffusion
  Models'
authors: Yoad Tewel, Rinon Gal, Dvir Samuel Yuval Atzmon, Lior Wolf, Gal Chechik
conference: No Venue
year: 2024
bibkey: tewel2024add
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/hf2411.07232'}]
tags: ["Model Architecture"]
short_authors: Tewel et al.
---
Adding Object into images based on text instructions is a challenging task in semantic image editing, requiring a balance between preserving the original scene and seamlessly integrating the new object in a fitting location. Despite extensive efforts, existing models often struggle with this balance, particularly with finding a natural location for adding an object in complex scenes. We introduce Add-it, a training-free approach that extends diffusion models' attention mechanisms to incorporate information from three key sources: the scene image, the text prompt, and the generated image itself. Our weighted extended-attention mechanism maintains structural consistency and fine details while ensuring natural object placement. Without task-specific fine-tuning, Add-it achieves state-of-the-art results on both real and generated image insertion benchmarks, including our newly constructed "Additing Affordance Benchmark" for evaluating object placement plausibility, outperforming supervised methods. Human evaluations show that Add-it is preferred in over 80% of cases, and it also demonstrates improvements in various automated metrics.

https://huggingface.co/discussions/paper/6732f726e6a45b6a0b314551