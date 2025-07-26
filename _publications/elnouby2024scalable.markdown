---
layout: publication
title: Scalable Pre-training Of Large Autoregressive Image Models
authors: Alaaeldin El-nouby, Michal Klein, Shuangfei Zhai, Miguel Angel Bautista,
  Alexander Toshev, Vaishaal Shankar, Joshua M Susskind, Armand Joulin
conference: No Venue
year: 2024
bibkey: elnouby2024scalable
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/hf2401.08541'}]
tags: ["Training Techniques"]
short_authors: El-nouby et al.
---
This paper introduces AIM, a collection of vision models pre-trained with an autoregressive objective. These models are inspired by their textual counterparts, i.e., Large Language Models (LLMs), and exhibit similar scaling properties. Specifically, we highlight two key findings: (1) the performance of the visual features scale with both the model capacity and the quantity of data, (2) the value of the objective function correlates with the performance of the model on downstream tasks. We illustrate the practical implication of these findings by pre-training a 7 billion parameter AIM on 2 billion images, that achieves 84.0% on ImageNet-1k with a frozen trunk. Interestingly, even at this scale, we observe no sign of saturation in performance, suggesting that AIM potentially represents a new frontier for training large-scale vision models. The pre-training of AIM is similar to the pre-training of LLMs, and does not require any image-specific strategy to stabilize the training at scale.

https://huggingface.co/discussions/paper/65a7733dc26011a4a7ef8b59