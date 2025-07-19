---
layout: publication
title: 'DCIS: Efficient Length Extrapolation Of Llms Via Divide-and-conquer Scaling
  Factor Search'
authors: Yang Lei, Xu Shaoyang, Xiong Deyi
conference: Lecture Notes in Computer Science
year: 2024
bibkey: yang2024dcis
citations: 90
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2412.18811'}]
tags: [Training Techniques, Tools, Transformer, Model Architecture, Efficiency And
    Optimization, Fine Tuning]
---
Large language models (LLMs) based on the Transformer architecture usually
have their context length limited due to the high training cost. Recent
advancements extend the context window by adjusting the scaling factors of RoPE
and fine-tuning. However, suboptimal initialization of these factors results in
increased fine-tuning costs and reduced performance at target length. To
address these challenges, we propose an innovative RoPE-based fine-tuning
framework that diverges from conventional scaling factors search. Specifically,
we present a Divide-and-Conquer Incremental Search (DCIS) algorithm that
strategically determines the better scaling factors. Further fine-tuning with
the identified scaling factors effectively extends the context window of LLMs.
Empirical results demonstrate that our methodology not only mitigates
performance decay at extended target lengths but also allows the model to
fine-tune on short contexts and generalize to long contexts, thereby reducing
the cost of fine-tuning. The scaling factors obtained through DCIS can even
perform effectively without fine-tuning. Further analysis of the search space
reveals that DCIS achieves twice the search efficiency compared to other
methods. We also examine the impact of the non-strictly increasing scaling
factors utilized in DCIS and evaluate the general capabilities of LLMs across
various context lengths.