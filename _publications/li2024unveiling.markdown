---
layout: publication
title: Unveiling The Backbone-optimizer Coupling Bias In Visual Representation Learning
authors: Siyuan Li, Juanxi Tian, Zedong Wang, Luyuan Zhang, Zicheng Liu, Weiyang Jin,
  Yang Liu, Baigui Sun, Stan Z. Li
conference: No Venue
year: 2024
bibkey: li2024unveiling
additional_links: [{name: Code, url: 'https://bocb-ai.github.io/'}, {name: Code, url: 'https://huggingface.co/discussions/paper/67073a7b95f90bdb8e86a176'},
  {name: Paper, url: 'https://arxiv.org/abs/hf2410.06373'}]
tags: ["Fine-Tuning", "Training Techniques"]
short_authors: Li et al.
---
This paper delves into the interplay between vision backbones and optimizers, unvealing an inter-dependent phenomenon termed \textbf\{backbone-optimizer coupling bias\} (BOCB). We observe that canonical CNNs, such as VGG and ResNet, exhibit a marked co-dependency with SGD families, while recent architectures like ViTs and ConvNeXt share a tight coupling with the adaptive learning rate ones. We further show that BOCB can be introduced by both optimizers and certain backbone designs and may significantly impact the pre-training and downstream fine-tuning of vision models. Through in-depth empirical analysis, we summarize takeaways on recommended optimizers and insights into robust vision backbone architectures. We hope this work can inspire the community to question long-held assumptions on backbones and optimizers, stimulate further explorations, and thereby contribute to more robust vision systems. The source code and models are publicly available at https://bocb-ai.github.io/.

https://huggingface.co/discussions/paper/67073a7b95f90bdb8e86a176