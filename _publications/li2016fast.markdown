---
layout: publication
title: A Simple, Fast Diverse Decoding Algorithm For Neural Generation
authors: Jiwei Li, Will Monroe, Dan Jurafsky
conference: Arxiv
year: 2016
citations: 239
bibkey: li2016fast
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1611.08562'}]
tags: [Reinforcement Learning, Agentic]
---
In this paper, we propose a simple, fast decoding algorithm that fosters
diversity in neural generation. The algorithm modifies the standard beam search
algorithm by adding an inter-sibling ranking penalty, favoring choosing
hypotheses from diverse parents. We evaluate the proposed model on the tasks of
dialogue response generation, abstractive summarization and machine
translation. We find that diverse decoding helps across all tasks, especially
those for which reranking is needed.
  We further propose a variation that is capable of automatically adjusting its
diversity decoding rates for different inputs using reinforcement learning
(RL). We observe a further performance boost from this RL technique. This paper
includes material from the unpublished script "Mutual Information and Diverse
Decoding Improve Neural Machine Translation" (Li and Jurafsky, 2016).