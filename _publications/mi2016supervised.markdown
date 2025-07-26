---
layout: publication
title: Supervised Attentions For Neural Machine Translation
authors: Haitao Mi, Zhiguo Wang, Abe Ittycheriah
conference: Proceedings of the 2016 Conference on Empirical Methods in Natural Language
  Processing
year: 2016
bibkey: mi2016supervised
citations: 129
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1608.00112'}]
tags: ["EMNLP", "Training Techniques"]
short_authors: Haitao Mi, Zhiguo Wang, Abe Ittycheriah
---
In this paper, we improve the attention or alignment accuracy of neural
machine translation by utilizing the alignments of training sentence pairs. We
simply compute the distance between the machine attentions and the "true"
alignments, and minimize this cost in the training procedure. Our experiments
on large-scale Chinese-to-English task show that our model improves both
translation and alignment qualities significantly over the large-vocabulary
neural machine translation system, and even beats a state-of-the-art
traditional syntax-based system.