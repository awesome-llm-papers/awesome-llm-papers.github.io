---
layout: publication
title: 'Learn To Code-switch: Data Augmentation Using Copy Mechanism On Language Modeling'
authors: Genta Indra Winata, Andrea Madotto, Chien-sheng Wu, Pascale Fung
conference: Arxiv
year: 2018
citations: 22
bibkey: winata2018learn
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1810.10254'}]
tags: [Language Modeling, Training Techniques, Model Architecture]
---
Building large-scale datasets for training code-switching language models is
challenging and very expensive. To alleviate this problem using parallel corpus
has been a major workaround. However, existing solutions use linguistic
constraints which may not capture the real data distribution. In this work, we
propose a novel method for learning how to generate code-switching sentences
from parallel corpora. Our model uses a Seq2Seq model in combination with
pointer networks to align and choose words from the monolingual sentences and
form a grammatical code-switching sentence. In our experiment, we show that by
training a language model using the augmented sentences we improve the
perplexity score by 10% compared to the LSTM baseline.