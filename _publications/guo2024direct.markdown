---
layout: publication
title: Direct Language Model Alignment From Online AI Feedback
authors: Shangmin Guo, Biao Zhang, Tianlin Liu, Tianqi Liu, Misha Khalman, Felipe
  Llinares, Alexandre Rame, Thomas Mesnard, Yao Zhao, Bilal Piot, Johan Ferret, Mathieu
  Blondel
conference: No Venue
year: 2024
bibkey: guo2024direct
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/hf2402.04792'}]
tags: ["Datasets", "Evaluation", "Prompting", "Reinforcement Learning", "Training Techniques"]
short_authors: Guo et al.
---
Direct alignment from preferences (DAP) methods, such as DPO, have recently emerged as efficient alternatives to reinforcement learning from human feedback (RLHF), that do not require a separate reward model. However, the preference datasets used in DAP methods are usually collected ahead of training and never updated, thus the feedback is purely offline. Moreover, responses in these datasets are often sampled from a language model distinct from the one being aligned, and since the model evolves over training, the alignment phase is inevitably off-policy. In this study, we posit that online feedback is key and improves DAP methods. Our method, online AI feedback (OAIF), uses an LLM as annotator: on each training iteration, we sample two responses from the current model and prompt the LLM annotator to choose which one is preferred, thus providing online feedback. Despite its simplicity, we demonstrate via human evaluation in several tasks that OAIF outperforms both offline DAP and RLHF methods. We further show that the feedback leveraged in OAIF is easily controllable, via instruction prompts to the LLM annotator.

https://huggingface.co/discussions/paper/65c43fcb7273e436da4ace7f