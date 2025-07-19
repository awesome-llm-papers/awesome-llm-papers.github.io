---
layout: publication
title: Natural Language Fine-tuning
authors: Liu et al.
conference: Proceedings of the 58th Annual Meeting of the Association for Computational
  Linguistics
year: 2024
bibkey: liu2024natural
citations: 319
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2412.20382'}]
tags: [Training Techniques, Efficiency And Optimization, Fine Tuning, ACL, Applications,
  RAG, Datasets, Reinforcement Learning]
---
Large language model fine-tuning techniques typically depend on extensive
labeled data, external guidance, and feedback, such as human alignment, scalar
rewards, and demonstration. However, in practical application, the scarcity of
specific knowledge poses unprecedented challenges to existing fine-tuning
techniques. In this paper, focusing on fine-tuning tasks in specific domains
with limited data, we introduce Natural Language Fine-Tuning (NLFT), which
utilizes natural language for fine-tuning for the first time. By leveraging the
strong language comprehension capability of the target LM, NLFT attaches the
guidance of natural language to the token-level outputs. Then, saliency tokens
are identified with calculated probabilities. Since linguistic information is
effectively utilized in NLFT, our proposed method significantly reduces
training costs. It markedly enhances training efficiency, comprehensively
outperforming reinforcement fine-tuning algorithms in accuracy, time-saving,
and resource conservation. Additionally, on the macro level, NLFT can be viewed
as a token-level fine-grained optimization of SFT, thereby efficiently
replacing the SFT process without the need for warm-up (as opposed to ReFT
requiring multiple rounds of warm-up with SFT). Compared to SFT, NLFT does not
increase the algorithmic complexity, maintaining O(n). Extensive experiments on
the GSM8K dataset demonstrate that NLFT, with only 50 data instances, achieves
an accuracy increase that exceeds SFT by 219%. Compared to ReFT, the time
complexity and space complexity of NLFT are reduced by 78.27% and 92.24%,
respectively. The superior technique of NLFT is paving the way for the
deployment of various innovative LLM fine-tuning applications when resources
are limited at network edges.
  Our code has been released at https://github.com/Julia-LiuJ/NLFT.