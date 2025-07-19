---
layout: publication
title: 'Pairwise Proximal Policy Optimization: Harnessing Relative Feedback For LLM
  Alignment'
authors: Wu et al.
conference: 'IEEE Transactions on Systems, Man, and Cybernetics: Systems'
year: 2023
bibkey: wu2023pairwise
citations: 90
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2310.00212'}]
tags: [Training Techniques, Agentic, Tools, Evaluation, Efficiency And Optimization,
  Reinforcement Learning]
---
Large Language Models (LLMs) can acquire extensive world knowledge through
pre-training on large corpora. However, due to exposure to low-quality data,
LLMs may exhibit harmful behavior without aligning with human values. The
dominant approach for steering LLMs towards beneficial behavior involves
Reinforcement Learning with Human Feedback (RLHF), with Proximal Policy
Optimization (PPO) serving as the default RL optimizer. Despite its
effectiveness, PPO has limitations when optimizing rewards trained from
comparison-based loss. Primarily, PPO is not invariant to equivalent reward
functions containing identical preference information due to the need to
calibrate the reward scale. Additionally, PPO's necessity for token-wise
updates introduces complexity in both function approximation and algorithm
design compared to trajectory-wise optimization. This paper proposes a new
framework, reinforcement learning with relative feedback, and a novel
trajectory-wise policy gradient algorithm, Pairwise Proximal Policy
Optimization (P3O) that operates directly on comparative rewards. We show
theoretically that P3O is invariant to equivalent rewards and avoids the
complexity of PPO. Empirical evaluations demonstrate that P3O outperforms PPO
in the KL-Reward trade-off and can align with human preferences as well as or
better than prior methods. In summary, this work introduces a simpler yet
effective approach for aligning LLMs to human preferences through relative
feedback.