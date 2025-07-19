---
layout: publication
title: Object-driven One-shot Fine-tuning Of Text-to-image Diffusion With Prototypical
  Embedding
authors: Lu Jianxiang, Xie Cong, Guo Hui
conference: 2023 IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR)
year: 2024
bibkey: lu2024object
citations: 1132
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2401.15708'}]
tags: [Fine Tuning, CVPR, Training Techniques, Merging]
---
As large-scale text-to-image generation models have made remarkable progress
in the field of text-to-image generation, many fine-tuning methods have been
proposed. However, these models often struggle with novel objects, especially
with one-shot scenarios. Our proposed method aims to address the challenges of
generalizability and fidelity in an object-driven way, using only a single
input image and the object-specific regions of interest. To improve
generalizability and mitigate overfitting, in our paradigm, a prototypical
embedding is initialized based on the object's appearance and its class, before
fine-tuning the diffusion model. And during fine-tuning, we propose a
class-characterizing regularization to preserve prior knowledge of object
classes. To further improve fidelity, we introduce object-specific loss, which
can also use to implant multiple objects. Overall, our proposed object-driven
method for implanting new objects can integrate seamlessly with existing
concepts as well as with high fidelity and generalization. Our method
outperforms several existing works. The code will be released.