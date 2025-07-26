---
layout: publication
title: Neurosymbolic Diffusion Models
authors: Emile van Krieken, Pasquale Minervini, Edoardo Ponti, Antonio Vergari
conference: No Venue
year: 2025
bibkey: krieken2025neurosymbolic
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/hf2505.13138'}]
tags: ["Model Architecture", "Nesy"]
short_authors: Krieken et al.
---
Neurosymbolic (NeSy) predictors combine neural perception with symbolic reasoning to solve tasks like visual reasoning. However, standard NeSy predictors assume conditional independence between the symbols they extract, thus limiting their ability to model interactions and uncertainty - often leading to overconfident predictions and poor out-of-distribution generalisation. To overcome the limitations of the independence assumption, we introduce neurosymbolic diffusion models (NeSyDMs), a new class of NeSy predictors that use discrete diffusion to model dependencies between symbols. Our approach reuses the independence assumption from NeSy predictors at each step of the diffusion process, enabling scalable learning while capturing symbol dependencies and uncertainty quantification. Across both synthetic and real-world benchmarks - including high-dimensional visual path planning and rule-based autonomous driving - NeSyDMs achieve state-of-the-art accuracy among NeSy predictors and demonstrate strong calibration.

https://huggingface.co/discussions/paper/682da62a975206d1caa8ca06