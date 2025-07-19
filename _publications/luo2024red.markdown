---
layout: publication
title: Red-teaming For Inducing Societal Bias In Large Language Models
authors: Luo et al.
conference: Proceedings of the 2022 Conference on Empirical Methods in Natural Language
  Processing
year: 2024
bibkey: luo2024red
citations: 98
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2405.04756'}]
tags: [EMNLP, Evaluation, Ethics And Bias, Reinforcement Learning, Applications, Security,
  Responsible AI]
---
Ensuring the safe deployment of AI systems is critical in industry settings where biased outputs can lead to significant operational, reputational, and regulatory risks. Thorough evaluation before deployment is essential to prevent these hazards. Red-teaming addresses this need by employing adversarial attacks to develop guardrails that detect and reject biased or harmful queries, enabling models to be retrained or steered away from harmful outputs. However, most red-teaming efforts focus on harmful or unethical instructions rather than addressing social bias, leaving this critical area under-explored despite its significant real-world impact, especially in customer-facing systems. We propose two bias-specific red-teaming methods, Emotional Bias Probe (EBP) and BiasKG, to evaluate how standard safety measures for harmful content affect bias. For BiasKG, we refactor natural language stereotypes into a knowledge graph. We use these attacking strategies to induce biased responses from several open- and closed-source language models. Unlike prior work, these methods specifically target social bias. We find our method increases bias in all models, even those trained with safety guardrails. Our work emphasizes uncovering societal bias in LLMs through rigorous evaluation, and recommends measures ensure AI safety in high-stakes industry deployments.