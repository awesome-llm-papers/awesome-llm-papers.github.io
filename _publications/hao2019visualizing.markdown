---
layout: publication
title: Visualizing And Understanding The Effectiveness Of BERT
authors: Yaru Hao, Li Dong, Furu Wei, Ke Xu
conference: Proceedings of the 2019 Conference on Empirical Methods in Natural Language
  Processing and the 9th International Joint Conference on Natural Language Processing
  (EMNLP-IJCNLP)
year: 2019
bibkey: hao2019visualizing
citations: 168
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1908.05620'}]
tags: ["Datasets", "Efficiency", "Fine-Tuning", "Model Architecture", "Training Techniques"]
short_authors: Hao et al.
---
Language model pre-training, such as BERT, has achieved remarkable results in
many NLP tasks. However, it is unclear why the pre-training-then-fine-tuning
paradigm can improve performance and generalization capability across different
tasks. In this paper, we propose to visualize loss landscapes and optimization
trajectories of fine-tuning BERT on specific datasets. First, we find that
pre-training reaches a good initial point across downstream tasks, which leads
to wider optima and easier optimization compared with training from scratch. We
also demonstrate that the fine-tuning procedure is robust to overfitting, even
though BERT is highly over-parameterized for downstream tasks. Second, the
visualization results indicate that fine-tuning BERT tends to generalize better
because of the flat and wide optima, and the consistency between the training
loss surface and the generalization error surface. Third, the lower layers of
BERT are more invariant during fine-tuning, which suggests that the layers that
are close to input learn more transferable representations of language.