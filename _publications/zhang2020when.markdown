---
layout: publication
title: When Do You Need Billions Of Words Of Pretraining Data?
authors: Yian Zhang, Alex Warstadt, Haau-sing Li, Samuel R. Bowman
conference: 'Proceedings of the 59th Annual Meeting of the Association for Computational
  Linguistics and the 11th International Joint Conference on Natural Language Processing
  (Volume 1: Long Papers)'
year: 2021
bibkey: zhang2020when
citations: 83
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2011.04946'}]
tags: ["Fine-Tuning", "Training Techniques"]
short_authors: Zhang et al.
---
NLP is currently dominated by general-purpose pretrained language models like
RoBERTa, which achieve strong performance on NLU tasks through pretraining on
billions of words. But what exact knowledge or skills do Transformer LMs learn
from large-scale pretraining that they cannot learn from less data? We adopt
four probing methods---classifier probing, information-theoretic probing,
unsupervised relative acceptability judgment, and fine-tuning on NLU
tasks---and draw learning curves that track the growth of these different
measures of linguistic ability with respect to pretraining data volume using
the MiniBERTas, a group of RoBERTa models pretrained on 1M, 10M, 100M and 1B
words. We find that LMs require only about 10M or 100M words to learn
representations that reliably encode most syntactic and semantic features we
test. A much larger quantity of data is needed in order to acquire enough
commonsense knowledge and other skills required to master typical downstream
NLU tasks. The results suggest that, while the ability to encode linguistic
features is almost certainly necessary for language understanding, it is likely
that other forms of knowledge are the major drivers of recent improvements in
language understanding among large pretrained models.