---
layout: publication
title: 'Refined Policy Distillation: From VLA Generalists To RL Experts'
authors: "J\xFClg Tobias, Burgard Wolfram, Walter Florian"
conference: Proceedings of the 32nd international ACM SIGIR conference on Research
  and development in information retrieval
year: 2025
bibkey: "j\xFClg2025refined"
citations: 76
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2503.05833'}]
tags: [Distillation, Agentic, Efficiency And Optimization, Reinforcement Learning,
  SIGIR, Fine Tuning, Multimodal Models]
---
Recent generalist Vision-Language-Action Models (VLAs) can perform a variety
of tasks on real robots with remarkable generalization capabilities. However,
reported success rates are often not on par with those of expert policies.
Moreover, VLAs usually do not work out of the box and often must be fine-tuned
as they are sensitive to setup changes. In this work, we present Refined Policy
Distillation (RPD), an RL-based policy refinement method that enables the
distillation of large generalist models into small, high-performing expert
policies. The student policy is guided during the RL exploration by actions of
a teacher VLA for increased sample efficiency and faster convergence. Different
from previous work that focuses on applying VLAs to real-world experiments, we
create fine-tuned versions of Octo and OpenVLA for ManiSkill2 to evaluate RPD
in simulation. As our results for different manipulation tasks demonstrate, RPD
enables the RL agent to learn expert policies that surpass the teacher's
performance in both dense and sparse reward settings. Our approach is even
robust to changes in the camera perspective and can generalize to task
variations that the underlying VLA cannot solve.