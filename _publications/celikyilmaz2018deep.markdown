---
layout: publication
title: Deep Communicating Agents For Abstractive Summarization
authors: Asli Celikyilmaz, Antoine Bosselut, Xiaodong He, Yejin Choi
conference: 'Proceedings of the 2018 Conference of the North American Chapter of the
  Association for Computational Linguistics: Human Language Technologies, Volume 1
  (Long Papers)'
year: 2018
bibkey: celikyilmaz2018deep
citations: 337
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1803.10357'}]
tags: ["Model Architecture", "NAACL"]
short_authors: Celikyilmaz et al.
---
We present deep communicating agents in an encoder-decoder architecture to
address the challenges of representing a long document for abstractive
summarization. With deep communicating agents, the task of encoding a long text
is divided across multiple collaborating agents, each in charge of a subsection
of the input text. These encoders are connected to a single decoder, trained
end-to-end using reinforcement learning to generate a focused and coherent
summary. Empirical results demonstrate that multiple communicating encoders
lead to a higher quality summary compared to several strong baselines,
including those based on a single encoder or multiple non-communicating
encoders.