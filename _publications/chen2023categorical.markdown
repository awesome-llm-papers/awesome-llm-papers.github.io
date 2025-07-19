---
layout: publication
title: 'Categorical Traffic Transformer: Interpretable And Diverse Behavior Prediction
  With Tokenized Latent'
authors: Chen Yuxiao, Tonkens Sander, Pavone Marco
conference: Advanced Engineering Informatics
year: 2023
bibkey: chen2023categorical
citations: 52
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2311.18307'}]
tags: [Interpretability And Explainability, Training Techniques, Transformer, Model
    Architecture, Multimodal Models]
---
Adept traffic models are critical to both planning and closed-loop simulation
for autonomous vehicles (AV), and key design objectives include accuracy,
diverse multimodal behaviors, interpretability, and downstream compatibility.
Recently, with the advent of large language models (LLMs), an additional
desirable feature for traffic models is LLM compatibility. We present
Categorical Traffic Transformer (CTT), a traffic model that outputs both
continuous trajectory predictions and tokenized categorical predictions (lane
modes, homotopies, etc.). The most outstanding feature of CTT is its fully
interpretable latent space, which enables direct supervision of the latent
variable from the ground truth during training and avoids mode collapse
completely. As a result, CTT can generate diverse behaviors conditioned on
different latent modes with semantic meanings while beating SOTA on prediction
accuracy. In addition, CTT's ability to input and output tokens enables
integration with LLMs for common-sense reasoning and zero-shot generalization.