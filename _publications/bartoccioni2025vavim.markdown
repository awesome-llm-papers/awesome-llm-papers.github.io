---
layout: publication
title: 'Vavim And Vavam: Autonomous Driving Through Video Generative Modeling'
authors: Bartoccioni et al.
conference: IEEE Transactions on Intelligent Transportation Systems
year: 2025
bibkey: bartoccioni2025vavim
citations: 75
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2502.15672'}]
tags: [RAG, Training Techniques, Evaluation, Reinforcement Learning, Responsible AI]
---
We explore the potential of large-scale generative video models for
autonomous driving, introducing an open-source auto-regressive video model
(VaViM) and its companion video-action model (VaVAM) to investigate how video
pre-training transfers to real-world driving. VaViM is a simple auto-regressive
video model that predicts frames using spatio-temporal token sequences. We show
that it captures the semantics and dynamics of driving scenes. VaVAM, the
video-action model, leverages the learned representations of VaViM to generate
driving trajectories through imitation learning. Together, the models form a
complete perception-to-action pipeline. We evaluate our models in open- and
closed-loop driving scenarios, revealing that video-based pre-training holds
promise for autonomous driving. Key insights include the semantic richness of
the learned representations, the benefits of scaling for video synthesis, and
the complex relationship between model size, data, and safety metrics in
closed-loop evaluations. We release code and model weights at
https://github.com/valeoai/VideoActionModel