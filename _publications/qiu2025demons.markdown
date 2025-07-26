---
layout: publication
title: 'Demons In The Detail: On Implementing Load Balancing Loss For Training Specialized
  Mixture-of-expert Models'
authors: Zihan Qiu, Zeyu Huang, Bo Zheng, Kaiyue Wen, Zekun Wang, Rui Men, Ivan Titov,
  Dayiheng Liu, Jingren Zhou, Junyang Lin
conference: No Venue
year: 2025
bibkey: qiu2025demons
additional_links: [{name: Code, url: 'https://huggingface.co/discussions/paper/679071db11a3f67d8f498680'},
  {name: Paper, url: 'https://arxiv.org/abs/hf2501.11873'}]
tags: ["Training Techniques"]
short_authors: Qiu et al.
---
This paper revisits the implementation of Load-balancing Loss (LBL) when training Mixture-of-Experts (MoEs) models. Specifically, LBL for MoEs is defined as N_E sum_\{i=1\}^\{N_E\} f_i p_i, where N_E is the total number of experts, f_i represents the frequency of expert i being selected, and p_i denotes the average gating score of the expert i. Existing MoE training frameworks usually employ the parallel training strategy so that f_i and the LBL are calculated within a micro-batch and then averaged across parallel groups. In essence, a micro-batch for training billion-scale LLMs normally contains very few sequences. So, the micro-batch LBL is almost at the sequence level, and the router is pushed to distribute the token evenly within each sequence. Under this strict constraint, even tokens from a domain-specific sequence (e.g., code) are uniformly routed to all experts, thereby inhibiting expert specialization. In this work, we propose calculating LBL using a global-batch to loose this constraint. Because a global-batch contains much more diverse sequences than a micro-batch, which will encourage load balance at the corpus level. Specifically, we introduce an extra communication step to synchronize f_i across micro-batches and then use it to calculate the LBL. Through experiments on training MoEs-based LLMs (up to 42.8B total parameters and 400B tokens), we surprisingly find that the global-batch LBL strategy yields excellent performance gains in both pre-training perplexity and downstream tasks. Our analysis reveals that the global-batch LBL also greatly improves the domain specialization of MoE experts.

https://huggingface.co/discussions/paper/679071db11a3f67d8f498680