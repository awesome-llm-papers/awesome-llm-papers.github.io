---
layout: publication
title: 'Zclip: Adaptive Spike Mitigation For LLM Pre-training'
authors: "Abhay Kumar, Louis Owen, Nilabhra Roy Chowdhury, Fabian G\xFCra"
conference: No Venue
year: 2025
bibkey: kumar2025zclip
additional_links: [{name: Code, url: 'https://github.com/bluorion-com/ZClip'}, {name: Code,
    url: 'https://huggingface.co/discussions/paper/67ef5a3e4417508df8d99dfc'}, {name: Paper,
    url: 'https://arxiv.org/abs/hf2504.02507'}]
tags: ["Has Code", "Training Techniques"]
short_authors: Kumar et al.
---
Training large language models (LLMs) presents numerous challenges, including gradient instability and loss spikes. These phenomena can lead to catastrophic divergence, requiring costly checkpoint restoration and data batch skipping. Traditional gradient clipping techniques, such as constant or norm-based methods, fail to address these issues effectively due to their reliance on fixed thresholds or heuristics, leading to inefficient learning and requiring frequent manual intervention. In this work, we propose ZClip, an adaptive gradient clipping algorithm that dynamically adjusts the clipping threshold based on statistical properties of gradient norms over time. Unlike prior reactive strategies, ZClip proactively adapts to training dynamics without making any prior assumptions on the scale and the temporal evolution of gradient norms. At its core, it leverages z-score-based anomaly detection to identify and mitigate large gradient spikes, preventing malignant loss spikes while not interfering with convergence otherwise. Our code is available at: https://github.com/bluorion-com/ZClip.

https://huggingface.co/discussions/paper/67ef5a3e4417508df8d99dfc