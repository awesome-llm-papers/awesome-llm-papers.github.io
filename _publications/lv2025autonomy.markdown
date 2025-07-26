---
layout: publication
title: Autonomy-of-experts Models
authors: Ang Lv, Ruobing Xie, Yining Qian, Songhao Wu, Xingwu Sun, Zhanhui Kang, di
  Wang, Rui Yan
conference: No Venue
year: 2025
bibkey: lv2025autonomy
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/hf2501.13074'}]
tags: ["Efficiency"]
short_authors: Lv et al.
---
Mixture-of-Experts (MoE) models mostly use a router to assign tokens to specific expert modules, activating only partial parameters and often outperforming dense models. We argue that the separation between the router's decision-making and the experts' execution is a critical yet overlooked issue, leading to suboptimal expert selection and ineffective learning. To address this, we propose Autonomy-of-Experts (AoE), a novel MoE paradigm in which experts autonomously select themselves to process inputs. AoE is based on the insight that an expert is aware of its own capacity to effectively process a token, an awareness reflected in the scale of its internal activations. In AoE, routers are removed; instead, experts pre-compute internal activations for inputs and are ranked based on their activation norms. Only the top-ranking experts proceed with the forward pass, while the others abort. The overhead of pre-computing activations is reduced through a low-rank weight factorization. This self-evaluating-then-partner-comparing approach ensures improved expert selection and effective learning. We pre-train language models having 700M up to 4B parameters, demonstrating that AoE outperforms traditional MoE models with comparable efficiency.

https://huggingface.co/discussions/paper/6791baa79d6eba7f285d5f35