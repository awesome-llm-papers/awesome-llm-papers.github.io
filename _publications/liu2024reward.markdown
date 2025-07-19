---
layout: publication
title: Reward Learning From Preference With Ties
authors: Liu Jinsong, Ge Dongdong, Zhu Ruihao
conference: 'Robotics: Science and Systems XIII'
year: 2024
bibkey: liu2024reward
citations: 139
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2410.05328'}]
tags: [RAG, Training Techniques, Prompting, Agentic, RSS, Ethics And Bias, Evaluation,
  Reinforcement Learning, Fine Tuning, Datasets]
---
Reward learning plays a pivotal role in Reinforcement Learning from Human
Feedback (RLHF), ensuring the alignment of language models. The Bradley-Terry
(BT) model stands as the prevalent choice for capturing human preferences from
datasets containing pairs of chosen and rejected responses. In preference
modeling, the focus is not on absolute values but rather on the reward
difference between chosen and rejected responses, referred to as preference
strength. Thus, precise evaluation of preference strength holds paramount
importance in preference modeling. However, an easily overlooked factor
significantly affecting preference strength measurement is that human attitudes
towards two responses may not solely indicate a preference for one over the
other and ties are also a common occurrence. To address this, we propose the
adoption of the generalized Bradley-Terry model -- the Bradley-Terry model with
ties (BTT) -- to accommodate tied preferences, thus leveraging additional
information. We prove that even with the access to the true distributions of
prompt and response, disregarding ties can lead to a notable bias in preference
strength measurement. Comprehensive experiments further validate the advantages
of incorporating ties in preference modeling. Notably, fine-tuning with BTT
significantly outperforms fine-tuning with BT on synthetic preference datasets
with ties, labeled by state-of-the-art open-source LLMs.