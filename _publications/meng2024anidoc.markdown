---
layout: publication
title: 'Anidoc: Animation Creation Made Easier'
authors: Yihao Meng, Hao Ouyang, Hanlin Wang, Qiuyu Wang, Wen Wang, Ka Leong Cheng,
  Zhiheng Liu, Yujun Shen, Huamin Qu
conference: No Venue
year: 2024
bibkey: meng2024anidoc
additional_links: [{name: Code, url: 'https://yihao-meng.github.io/AniDoc_demo'},
  {name: Code, url: 'https://huggingface.co/discussions/paper/67639f330e317931ea62652d'},
  {name: Paper, url: 'https://arxiv.org/abs/hf2412.14173'}]
tags: ["Has Code"]
short_authors: Meng et al.
---
The production of 2D animation follows an industry-standard workflow, encompassing four essential stages: character design, keyframe animation, in-betweening, and coloring. Our research focuses on reducing the labor costs in the above process by harnessing the potential of increasingly powerful generative AI. Using video diffusion models as the foundation, AniDoc emerges as a video line art colorization tool, which automatically converts sketch sequences into colored animations following the reference character specification. Our model exploits correspondence matching as an explicit guidance, yielding strong robustness to the variations (e.g., posture) between the reference character and each line art frame. In addition, our model could even automate the in-betweening process, such that users can easily create a temporally consistent animation by simply providing a character image as well as the start and end sketches. Our code is available at: https://yihao-meng.github.io/AniDoc_demo.

https://huggingface.co/discussions/paper/67639f330e317931ea62652d