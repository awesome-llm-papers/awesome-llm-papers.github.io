---
layout: publication
title: Simple And Effective Noisy Channel Modeling For Neural Machine Translation
authors: Yee et al.
conference: Proceedings of the 2019 Conference on Empirical Methods in Natural Language
  Processing and the 9th International Joint Conference on Natural Language Processing
  (EMNLP-IJCNLP)
year: 2019
bibkey: yee2019simple
citations: 54
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1908.05731'}]
tags: [Alt, EMNLP, Merging]
---
Previous work on neural noisy channel modeling relied on latent variable
models that incrementally process the source and target sentence. This makes
decoding decisions based on partial source prefixes even though the full source
is available. We pursue an alternative approach based on standard sequence to
sequence models which utilize the entire source. These models perform
remarkably well as channel models, even though they have neither been trained
on, nor designed to factor over incomplete target sentences. Experiments with
neural language models trained on billions of words show that noisy channel
models can outperform a direct model by up to 3.2 BLEU on WMT'17 German-English
translation. We evaluate on four language-pairs and our channel models
consistently outperform strong alternatives such right-to-left reranking models
and ensembles of direct models.