---
layout: publication
title: Can A Suit Of Armor Conduct Electricity? A New Dataset For Open Book Question
  Answering
authors: Todor Mihaylov, Peter Clark, Tushar Khot, Ashish Sabharwal
conference: Proceedings of the 2018 Conference on Empirical Methods in Natural Language
  Processing
year: 2018
bibkey: mihaylov2018can
citations: 503
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1809.02789'}]
tags: ["Datasets", "EMNLP"]
short_authors: Mihaylov et al.
---
We present a new kind of question answering dataset, OpenBookQA, modeled
after open book exams for assessing human understanding of a subject. The open
book that comes with our questions is a set of 1329 elementary level science
facts. Roughly 6000 questions probe an understanding of these facts and their
application to novel situations. This requires combining an open book fact
(e.g., metals conduct electricity) with broad common knowledge (e.g., a suit of
armor is made of metal) obtained from other sources. While existing QA datasets
over documents or knowledge bases, being generally self-contained, focus on
linguistic understanding, OpenBookQA probes a deeper understanding of both the
topic---in the context of common knowledge---and the language it is expressed
in. Human performance on OpenBookQA is close to 92%, but many state-of-the-art
pre-trained QA methods perform surprisingly poorly, worse than several simple
neural baselines we develop. Our oracle experiments designed to circumvent the
knowledge retrieval bottleneck demonstrate the value of both the open book and
additional facts. We leave it as a challenge to solve the retrieval problem in
this multi-hop setting and to close the large gap to human performance.