---
layout: publication
title: Improving Abstraction In Text Summarization
authors: "Wojciech Kry\u015Bci\u0144ski, Romain Paulus, Caiming Xiong, Richard Socher"
conference: Proceedings of the 2018 Conference on Empirical Methods in Natural Language
  Processing
year: 2018
bibkey: "kry\u015Bci\u0144ski2018improving"
citations: 151
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1808.07913'}]
tags: ["EMNLP"]
short_authors: "Kry\u015Bci\u0144ski et al."
---
Abstractive text summarization aims to shorten long text documents into a
human readable form that contains the most important facts from the original
document. However, the level of actual abstraction as measured by novel phrases
that do not appear in the source document remains low in existing approaches.
We propose two techniques to improve the level of abstraction of generated
summaries. First, we decompose the decoder into a contextual network that
retrieves relevant parts of the source document, and a pretrained language
model that incorporates prior knowledge about language generation. Second, we
propose a novelty metric that is optimized directly through policy learning to
encourage the generation of novel phrases. Our model achieves results
comparable to state-of-the-art models, as determined by ROUGE scores and human
evaluations, while achieving a significantly higher level of abstraction as
measured by n-gram overlap with the source document.