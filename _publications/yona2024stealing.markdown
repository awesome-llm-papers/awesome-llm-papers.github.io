---
layout: publication
title: Stealing User Prompts From Mixture Of Experts
authors: Yona et al.
conference: Proceedings of the 26th ACM SIGKDD International Conference on Knowledge
  Discovery &amp; Data Mining
year: 2024
bibkey: yona2024stealing
citations: 57
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2410.22884'}]
tags: [RAG, Prompting, Efficiency And Optimization, Security, KDD]
---
Mixture-of-Experts (MoE) models improve the efficiency and scalability of
dense language models by routing each token to a small number of experts in
each layer. In this paper, we show how an adversary that can arrange for their
queries to appear in the same batch of examples as a victim's queries can
exploit Expert-Choice-Routing to fully disclose a victim's prompt. We
successfully demonstrate the effectiveness of this attack on a two-layer
Mixtral model, exploiting the tie-handling behavior of the torch.topk CUDA
implementation. Our results show that we can extract the entire prompt using
\\(O(\{VM\}^2)\\) queries (with vocabulary size \\(V\\) and prompt length \\(M\\)) or 100
queries on average per token in the setting we consider. This is the first
attack to exploit architectural flaws for the purpose of extracting user
prompts, introducing a new class of LLM vulnerabilities.