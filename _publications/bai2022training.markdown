---
layout: publication
title: Training A Helpful And Harmless Assistant With Reinforcement Learning From
  Human Feedback
authors: Yuntao Bai, Andy Jones, Kamal Ndousse, Amanda Askell, Anna Chen, Nova Dassarma,
  Dawn Drain, Stanislav Fort, Deep Ganguli, Tom Henighan, Nicholas Joseph, Saurav
  Kadavath, Jackson Kernion, Tom Conerly, Sheer El-showk, Nelson Elhage, Zac Hatfield-dodds,
  Danny Hernandez, Tristan Hume, Scott Johnston, Shauna Kravec, Liane Lovitt, Neel
  Nanda, Catherine Olsson, Dario Amodei, Tom Brown, Jack Clark, Sam Mccandlish, Chris
  Olah, Ben Mann, Jared Kaplan
conference: Arxiv
year: 2022
bibkey: bai2022training
citations: 251
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2204.05862'}]
tags: ["Reinforcement Learning", "Training Techniques"]
short_authors: Bai et al.
---
We apply preference modeling and reinforcement learning from human feedback
(RLHF) to finetune language models to act as helpful and harmless assistants.
We find this alignment training improves performance on almost all NLP
evaluations, and is fully compatible with training for specialized skills such
as python coding and summarization. We explore an iterated online mode of
training, where preference models and RL policies are updated on a weekly
cadence with fresh human feedback data, efficiently improving our datasets and
models. Finally, we investigate the robustness of RLHF training, and identify a
roughly linear relation between the RL reward and the square root of the KL
divergence between the policy and its initialization. Alongside our main
results, we perform peripheral analyses on calibration, competing objectives,
and the use of OOD detection, compare our models with human writers, and
provide samples from our models using prompts appearing in recent related work.