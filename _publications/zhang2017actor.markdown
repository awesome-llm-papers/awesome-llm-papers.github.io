---
layout: publication
title: Actor-critic Sequence Training For Image Captioning
authors: Li Zhang, Flood Sung, Feng Liu, Tao Xiang, Shaogang Gong, Yongxin Yang, Timothy
  M. Hospedales
conference: Arxiv
year: 2017
bibkey: zhang2017actor
citations: 110
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1706.09601'}]
tags: ["Reinforcement Learning", "Training Techniques"]
short_authors: Zhang et al.
---
Generating natural language descriptions of images is an important capability
for a robot or other visual-intelligence driven AI agent that may need to
communicate with human users about what it is seeing. Such image captioning
methods are typically trained by maximising the likelihood of ground-truth
annotated caption given the image. While simple and easy to implement, this
approach does not directly maximise the language quality metrics we care about
such as CIDEr. In this paper we investigate training image captioning methods
based on actor-critic reinforcement learning in order to directly optimise
non-differentiable quality metrics of interest. By formulating a per-token
advantage and value computation strategy in this novel reinforcement learning
based captioning model, we show that it is possible to achieve the state of the
art performance on the widely used MSCOCO benchmark.