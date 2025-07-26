---
layout: publication
title: 'Bertscore: Evaluating Text Generation With BERT'
authors: Tianyi Zhang, Varsha Kishore, Felix Wu, Kilian Q. Weinberger, Yoav Artzi
conference: Arxiv
year: 2019
bibkey: zhang2019bertscore
citations: 1961
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1904.09675'}]
tags: ["Evaluation"]
short_authors: Zhang et al.
---
We propose BERTScore, an automatic evaluation metric for text generation.
Analogously to common metrics, BERTScore computes a similarity score for each
token in the candidate sentence with each token in the reference sentence.
However, instead of exact matches, we compute token similarity using contextual
embeddings. We evaluate using the outputs of 363 machine translation and image
captioning systems. BERTScore correlates better with human judgments and
provides stronger model selection performance than existing metrics. Finally,
we use an adversarial paraphrase detection task to show that BERTScore is more
robust to challenging examples when compared to existing metrics.