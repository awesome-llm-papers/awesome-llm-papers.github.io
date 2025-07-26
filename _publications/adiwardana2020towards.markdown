---
layout: publication
title: Towards A Human-like Open-domain Chatbot
authors: Daniel Adiwardana, Minh-thang Luong, David R. So, Jamie Hall, Noah Fiedel,
  Romal Thoppilan, Zi Yang, Apoorv Kulshreshtha, Gaurav Nemade, Yifeng Lu, Quoc V.
  Le
conference: Arxiv
year: 2020
bibkey: adiwardana2020towards
citations: 444
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2001.09977'}]
tags: ["Evaluation"]
short_authors: Adiwardana et al.
---
We present Meena, a multi-turn open-domain chatbot trained end-to-end on data
mined and filtered from public domain social media conversations. This 2.6B
parameter neural network is simply trained to minimize perplexity of the next
token. We also propose a human evaluation metric called Sensibleness and
Specificity Average (SSA), which captures key elements of a human-like
multi-turn conversation. Our experiments show strong correlation between
perplexity and SSA. The fact that the best perplexity end-to-end trained Meena
scores high on SSA (72% on multi-turn evaluation) suggests that a human-level
SSA of 86% is potentially within reach if we can better optimize perplexity.
Additionally, the full version of Meena (with a filtering mechanism and tuned
decoding) scores 79% SSA, 23% higher in absolute SSA than the existing chatbots
we evaluated.