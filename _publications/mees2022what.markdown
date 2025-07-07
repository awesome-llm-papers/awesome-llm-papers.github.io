---
layout: publication
title: What Matters In Language Conditioned Robotic Imitation Learning Over Unstructured
  Data
authors: Oier Mees, Lukas Hermann, Wolfram Burgard
conference: Arxiv
year: 2022
citations: 31
bibkey: mees2022what
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2204.06252'}, {name: Code,
    url: 'http://hulc.cs.uni-freiburg.de'}]
tags: [Training Techniques, Transformer, RAG, Reinforcement Learning, Has Code, Multimodal
    Models, Model Architecture]
---
A long-standing goal in robotics is to build robots that can perform a wide
range of daily tasks from perceptions obtained with their onboard sensors and
specified only via natural language. While recently substantial advances have
been achieved in language-driven robotics by leveraging end-to-end learning
from pixels, there is no clear and well-understood process for making various
design choices due to the underlying variation in setups. In this paper, we
conduct an extensive study of the most critical challenges in learning language
conditioned policies from offline free-form imitation datasets. We further
identify architectural and algorithmic techniques that improve performance,
such as a hierarchical decomposition of the robot control learning, a
multimodal transformer encoder, discrete latent plans and a self-supervised
contrastive loss that aligns video and language representations. By combining
the results of our investigation with our improved model components, we are
able to present a novel approach that significantly outperforms the state of
the art on the challenging language conditioned long-horizon robot manipulation
CALVIN benchmark. We have open-sourced our implementation to facilitate future
research in learning to perform many complex manipulation skills in a row
specified with natural language. Codebase and trained models available at
http://hulc.cs.uni-freiburg.de