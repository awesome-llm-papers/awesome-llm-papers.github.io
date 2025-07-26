---
layout: publication
title: 'Gsum: A General Framework For Guided Neural Abstractive Summarization'
authors: Zi-yi Dou, Pengfei Liu, Hiroaki Hayashi, Zhengbao Jiang, Graham Neubig
conference: 'Proceedings of the 2021 Conference of the North American Chapter of the
  Association for Computational Linguistics: Human Language Technologies'
year: 2021
bibkey: dou2020gsum
citations: 186
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2010.08014'}]
tags: ["NAACL", "Tools"]
short_authors: Dou et al.
---
Neural abstractive summarization models are flexible and can produce coherent
summaries, but they are sometimes unfaithful and can be difficult to control.
While previous studies attempt to provide different types of guidance to
control the output and increase faithfulness, it is not clear how these
strategies compare and contrast to each other. In this paper, we propose a
general and extensible guided summarization framework (GSum) that can
effectively take different kinds of external guidance as input, and we perform
experiments across several different varieties. Experiments demonstrate that
this model is effective, achieving state-of-the-art performance according to
ROUGE on 4 popular summarization datasets when using highlighted sentences as
guidance. In addition, we show that our guided model can generate more faithful
summaries and demonstrate how different types of guidance generate
qualitatively different summaries, lending a degree of controllability to the
learned models.