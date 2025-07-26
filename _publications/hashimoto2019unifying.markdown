---
layout: publication
title: Unifying Human And Statistical Evaluation For Natural Language Generation
authors: Tatsunori B. Hashimoto, Hugh Zhang, Percy Liang
conference: Proceedings of the 2019 Conference of the North
year: 2019
bibkey: hashimoto2019unifying
citations: 180
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1904.02792'}]
tags: ["Evaluation"]
short_authors: Tatsunori B. Hashimoto, Hugh Zhang, Percy Liang
---
How can we measure whether a natural language generation system produces both
high quality and diverse outputs? Human evaluation captures quality but not
diversity, as it does not catch models that simply plagiarize from the training
set. On the other hand, statistical evaluation (i.e., perplexity) captures
diversity but not quality, as models that occasionally emit low quality samples
would be insufficiently penalized. In this paper, we propose a unified
framework which evaluates both diversity and quality, based on the optimal
error rate of predicting whether a sentence is human- or machine-generated. We
demonstrate that this error rate can be efficiently estimated by combining
human and statistical evaluation, using an evaluation metric which we call
HUSE. On summarization and chit-chat dialogue, we show that (i) HUSE detects
diversity defects which fool pure human evaluation and that (ii) techniques
such as annealing for improving quality actually decrease HUSE due to decreased
diversity.