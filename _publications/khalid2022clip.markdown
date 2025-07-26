---
layout: publication
title: 'Clip-mesh: Generating Textured Meshes From Text Using Pretrained Image-text
  Models'
authors: Nasir Mohammad Khalid, Tianhao Xie, Eugene Belilovsky, Tiberiu Popa
conference: SIGGRAPH Asia 2022 Conference Papers
year: 2022
bibkey: khalid2022clip
citations: 127
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2203.13333'}]
tags: ["Applications"]
short_authors: Khalid et al.
---
We present a technique for zero-shot generation of a 3D model using only a
target text prompt. Without any 3D supervision our method deforms the control
shape of a limit subdivided surface along with its texture map and normal map
to obtain a 3D asset that corresponds to the input text prompt and can be
easily deployed into games or modeling applications. We rely only on a
pre-trained CLIP model that compares the input text prompt with differentiably
rendered images of our 3D model. While previous works have focused on
stylization or required training of generative models we perform optimization
on mesh parameters directly to generate shape, texture or both. To constrain
the optimization to produce plausible meshes and textures we introduce a number
of techniques using image augmentations and the use of a pretrained prior that
generates CLIP image embeddings given a text embedding.