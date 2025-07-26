---
layout: publication
title: Jointly Learning To Align And Translate With Transformer Models
authors: Sarthak Garg, Stephan Peitz, Udhyakumar Nallasamy, Matthias Paulik
conference: Proceedings of the 2019 Conference on Empirical Methods in Natural Language
  Processing and the 9th International Joint Conference on Natural Language Processing
  (EMNLP-IJCNLP)
year: 2019
bibkey: garg2019jointly
citations: 132
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1909.02074'}]
tags: ["EMNLP", "Model Architecture", "Training Techniques"]
short_authors: Garg et al.
---
The state of the art in machine translation (MT) is governed by neural
approaches, which typically provide superior translation accuracy over
statistical approaches. However, on the closely related task of word alignment,
traditional statistical word alignment models often remain the go-to solution.
In this paper, we present an approach to train a Transformer model to produce
both accurate translations and alignments. We extract discrete alignments from
the attention probabilities learnt during regular neural machine translation
model training and leverage them in a multi-task framework to optimize towards
translation and alignment objectives. We demonstrate that our approach produces
competitive results compared to GIZA++ trained IBM alignment models without
sacrificing translation accuracy and outperforms previous attempts on
Transformer model based word alignment. Finally, by incorporating IBM model
alignments into our multi-task training, we report significantly better
alignment accuracies compared to GIZA++ on three publicly available data sets.