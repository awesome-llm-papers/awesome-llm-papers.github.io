---
layout: publication
title: Learn Your Reference Model For Real Good Alignment
authors: Alexey Gorbatovski, Boris Shaposhnikov, Alexey Malakhov, Nikita Surnachev,
  Yaroslav Aksenov, Ian Maksimov, Nikita Balagansky, Daniil Gavrilov
conference: No Venue
year: 2024
bibkey: gorbatovski2024learn
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/hf2404.09656'}]
tags: ["Datasets", "Efficiency", "Evaluation", "Fine-Tuning", "Model Architecture", "Reinforcement Learning", "Training Techniques"]
short_authors: Gorbatovski et al.
---
The complexity of the alignment problem stems from the fact that existing methods are unstable. Researchers continuously invent various tricks to address this shortcoming. For instance, in the fundamental Reinforcement Learning From Human Feedback (RLHF) technique of Language Model alignment, in addition to reward maximization, the Kullback-Leibler divergence between the trainable policy and the SFT policy is minimized. This addition prevents the model from being overfitted to the Reward Model (RM) and generating texts that are out-of-domain for the RM. The Direct Preference Optimization (DPO) method reformulates the optimization task of RLHF and eliminates the Reward Model while tacitly maintaining the requirement for the policy to be close to the SFT policy. In our paper, we argue that this implicit limitation in the DPO method leads to sub-optimal results. We propose a new method called Trust Region DPO (TR-DPO), which updates the reference policy during training. With such a straightforward update, we demonstrate the effectiveness of TR-DPO against DPO on the Anthropic HH and TLDR datasets. We show that TR-DPO outperforms DPO by up to 19%, measured by automatic evaluation with GPT-4. The new alignment approach that we propose allows us to improve the quality of models across several parameters at once, such as coherence, correctness, level of detail, helpfulness, and harmlessness.

https://huggingface.co/discussions/paper/661de9b936eb62686fcce16d