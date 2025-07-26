---
layout: publication
title: Learning Paraphrastic Sentence Embeddings From Back-translated Bitext
authors: John Wieting, Jonathan Mallinson, Kevin Gimpel
conference: Proceedings of the 2017 Conference on Empirical Methods in Natural Language
  Processing
year: 2017
bibkey: wieting2017learning
citations: 93
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1706.01847'}]
tags: ["EMNLP", "Training Techniques"]
short_authors: John Wieting, Jonathan Mallinson, Kevin Gimpel
---
We consider the problem of learning general-purpose, paraphrastic sentence
embeddings in the setting of Wieting et al. (2016b). We use neural machine
translation to generate sentential paraphrases via back-translation of
bilingual sentence pairs. We evaluate the paraphrase pairs by their ability to
serve as training data for learning paraphrastic sentence embeddings. We find
that the data quality is stronger than prior work based on bitext and on par
with manually-written English paraphrase pairs, with the advantage that our
approach can scale up to generate large training sets for many languages and
domains. We experiment with several language pairs and data sources, and
develop a variety of data filtering techniques. In the process, we explore how
neural machine translation output differs from human-written sentences, finding
clear differences in length, the amount of repetition, and the use of rare
words.