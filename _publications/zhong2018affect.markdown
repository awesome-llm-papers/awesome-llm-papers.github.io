---
layout: publication
title: An Affect-rich Neural Conversational Model With Biased Attention And Weighted
  Cross-entropy Loss
authors: Peixiang Zhong, di Wang, Chunyan Miao
conference: Proceedings of the AAAI Conference on Artificial Intelligence
year: 2019
bibkey: zhong2018affect
citations: 85
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1811.07078'}]
tags: ["AAAI", "Model Architecture"]
short_authors: Peixiang Zhong, di Wang, Chunyan Miao
---
Affect conveys important implicit information in human communication. Having
the capability to correctly express affect during human-machine conversations
is one of the major milestones in artificial intelligence. In recent years,
extensive research on open-domain neural conversational models has been
conducted. However, embedding affect into such models is still under explored.
In this paper, we propose an end-to-end affect-rich open-domain neural
conversational model that produces responses not only appropriate in syntax and
semantics, but also with rich affect. Our model extends the Seq2Seq model and
adopts VAD (Valence, Arousal and Dominance) affective notations to embed each
word with affects. In addition, our model considers the effect of negators and
intensifiers via a novel affective attention mechanism, which biases attention
towards affect-rich words in input sentences. Lastly, we train our model with
an affect-incorporated objective function to encourage the generation of
affect-rich words in the output responses. Evaluations based on both perplexity
and human evaluations show that our model outperforms the state-of-the-art
baseline model of comparable size in producing natural and affect-rich
responses.