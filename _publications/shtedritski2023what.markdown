---
layout: publication
title: What Does CLIP Know About A Red Circle? Visual Prompt Engineering For Vlms
authors: Aleksandar Shtedritski, Christian Rupprecht, Andrea Vedaldi
conference: 2023 IEEE/CVF International Conference on Computer Vision (ICCV)
year: 2023
citations: 52
bibkey: shtedritski2023what
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2304.06712'}]
tags: [Model Architecture, Attention Mechanism, Applications, Multimodal Models, Prompting,
  GPT]
---
Large-scale Vision-Language Models, such as CLIP, learn powerful image-text
representations that have found numerous applications, from zero-shot
classification to text-to-image generation. Despite that, their capabilities
for solving novel discriminative tasks via prompting fall behind those of large
language models, such as GPT-3. Here we explore the idea of visual prompt
engineering for solving computer vision tasks beyond classification by editing
in image space instead of text. In particular, we discover an emergent ability
of CLIP, where, by simply drawing a red circle around an object, we can direct
the model's attention to that region, while also maintaining global
information. We show the power of this simple approach by achieving
state-of-the-art in zero-shot referring expressions comprehension and strong
performance in keypoint localization tasks. Finally, we draw attention to some
potential ethical concerns of large language-vision models.