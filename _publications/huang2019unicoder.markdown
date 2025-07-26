---
layout: publication
title: 'Unicoder: A Universal Language Encoder By Pre-training With Multiple Cross-lingual
  Tasks'
authors: Haoyang Huang, Yaobo Liang, Nan Duan, Ming Gong, Linjun Shou, Daxin Jiang,
  Ming Zhou
conference: Proceedings of the 2019 Conference on Empirical Methods in Natural Language
  Processing and the 9th International Joint Conference on Natural Language Processing
  (EMNLP-IJCNLP)
year: 2019
bibkey: huang2019unicoder
citations: 166
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1909.00964'}]
tags: ["Datasets", "EMNLP", "Fine-Tuning", "Model Architecture", "Training Techniques"]
short_authors: Huang et al.
---
We present Unicoder, a universal language encoder that is insensitive to
different languages. Given an arbitrary NLP task, a model can be trained with
Unicoder using training data in one language and directly applied to inputs of
the same task in other languages. Comparing to similar efforts such as
Multilingual BERT and XLM, three new cross-lingual pre-training tasks are
proposed, including cross-lingual word recovery, cross-lingual paraphrase
classification and cross-lingual masked language model. These tasks help
Unicoder learn the mappings among different languages from more perspectives.
We also find that doing fine-tuning on multiple languages together can bring
further improvement. Experiments are performed on two tasks: cross-lingual
natural language inference (XNLI) and cross-lingual question answering (XQA),
where XLM is our baseline. On XNLI, 1.8% averaged accuracy improvement (on 15
languages) is obtained. On XQA, which is a new cross-lingual dataset built by
us, 5.5% averaged accuracy improvement (on French and German) is obtained.