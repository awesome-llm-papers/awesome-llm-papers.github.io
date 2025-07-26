---
layout: publication
title: 'Scenescript: Reconstructing Scenes With An Autoregressive Structured Language
  Model'
authors: Armen Avetisyan, Christopher Xie, Henry Howard-jenkins, Tsun-yi Yang, Samir
  Aroudj, Suvam Patra, Fuyang Zhang, Duncan Frost, Luke Holland, Campbell Orme, Jakob
  Engel, Edward Miller, Richard Newcombe, Vasileios Balntas
conference: No Venue
year: 2024
bibkey: avetisyan2024scenescript
additional_links: [{name: Code, url: 'https://huggingface.co/discussions/paper/65fb9f7b769c433dc27c4064'},
  {name: Paper, url: 'https://arxiv.org/abs/hf2403.13064'}]
tags: ["Model Architecture"]
short_authors: Avetisyan et al.
---
We introduce SceneScript, a method that directly produces full scene models as a sequence of structured language commands using an autoregressive, token-based approach. Our proposed scene representation is inspired by recent successes in transformers & LLMs, and departs from more traditional methods which commonly describe scenes as meshes, voxel grids, point clouds or radiance fields. Our method infers the set of structured language commands directly from encoded visual data using a scene language encoder-decoder architecture. To train SceneScript, we generate and release a large-scale synthetic dataset called Aria Synthetic Environments consisting of 100k high-quality in-door scenes, with photorealistic and ground-truth annotated renders of egocentric scene walkthroughs. Our method gives state-of-the art results in architectural layout estimation, and competitive results in 3D object detection. Lastly, we explore an advantage for SceneScript, which is the ability to readily adapt to new commands via simple additions to the structured language, which we illustrate for tasks such as coarse 3D object part reconstruction.

https://huggingface.co/discussions/paper/65fb9f7b769c433dc27c4064