---
layout: publication
title: Adapting Large Language Models By Integrating Collaborative Semantics For Recommendation
authors: Bowen Zheng et al.
conference: Arxiv
year: 2023
citations: 18
bibkey: zheng2023adapting
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2311.09049'}, {name: Code,
    url: 'https://github.com/RUCAIBox/LC-Rec/'}]
tags: [Training Techniques, RAG, Fine-Tuning, RecSys, Efficiency and Optimization,
  Has Code, Quantization]
---
Recently, large language models (LLMs) have shown great potential in
recommender systems, either improving existing recommendation models or serving
as the backbone. However, there exists a large semantic gap between LLMs and
recommender systems, since items to be recommended are often indexed by
discrete identifiers (item ID) out of the LLM's vocabulary. In essence, LLMs
capture language semantics while recommender systems imply collaborative
semantics, making it difficult to sufficiently leverage the model capacity of
LLMs for recommendation. To address this challenge, in this paper, we propose a
new LLM-based recommendation model called LC-Rec, which can better integrate
language and collaborative semantics for recommender systems. Our approach can
directly generate items from the entire item set for recommendation, without
relying on candidate items. Specifically, we make two major contributions in
our approach. For item indexing, we design a learning-based vector quantization
method with uniform semantic mapping, which can assign meaningful and
non-conflicting IDs (called item indices) for items. For alignment tuning, we
propose a series of specially designed tuning tasks to enhance the integration
of collaborative semantics in LLMs. Our fine-tuning tasks enforce LLMs to
deeply integrate language and collaborative semantics (characterized by the
learned item indices), so as to achieve an effective adaptation to recommender
systems. Extensive experiments demonstrate the effectiveness of our method,
showing that our approach can outperform a number of competitive baselines
including traditional recommenders and existing LLM-based recommenders. Our
code is available at https://github.com/RUCAIBox/LC-Rec/.