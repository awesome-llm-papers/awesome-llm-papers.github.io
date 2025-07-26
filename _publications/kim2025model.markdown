---
layout: publication
title: 'Model Already Knows The Best Noise: Bayesian Active Noise Selection Via Attention
  In Video Diffusion Model'
authors: Kwanyoung Kim, Sanghyun Kim
conference: No Venue
year: 2025
bibkey: kim2025model
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/hf2505.17561'}]
tags: ["Has Code", "Prompting", "Tools"]
short_authors: Kwanyoung Kim, Sanghyun Kim
---
The choice of initial noise significantly affects the quality and prompt alignment of video diffusion models, where different noise seeds for the same prompt can lead to drastically different generations. While recent methods rely on externally designed priors such as frequency filters or inter-frame smoothing, they often overlook internal model signals that indicate which noise seeds are inherently preferable. To address this, we propose ANSE (Active Noise Selection for Generation), a model-aware framework that selects high-quality noise seeds by quantifying attention-based uncertainty. At its core is BANSA (Bayesian Active Noise Selection via Attention), an acquisition function that measures entropy disagreement across multiple stochastic attention samples to estimate model confidence and consistency. For efficient inference-time deployment, we introduce a Bernoulli-masked approximation of BANSA that enables score estimation using a single diffusion step and a subset of attention layers. Experiments on CogVideoX-2B and 5B demonstrate that ANSE improves video quality and temporal coherence with only an 8% and 13% increase in inference time, respectively, providing a principled and generalizable approach to noise selection in video diffusion. See our project page: https://anse-project.github.io/anse-project/

https://huggingface.co/discussions/paper/6833cb9430cd9df52a11765d