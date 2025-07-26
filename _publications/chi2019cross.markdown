---
layout: publication
title: Cross-lingual Natural Language Generation Via Pre-training
authors: Zewen Chi, Li Dong, Furu Wei, Wenhui Wang, Xian-ling Mao, Heyan Huang
conference: Proceedings of the AAAI Conference on Artificial Intelligence
year: 2020
bibkey: chi2019cross
citations: 142
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1909.10481'}]
tags: ["AAAI", "Training Techniques"]
short_authors: Chi et al.
---
In this work we focus on transferring supervision signals of natural language
generation (NLG) tasks between multiple languages. We propose to pretrain the
encoder and the decoder of a sequence-to-sequence model under both monolingual
and cross-lingual settings. The pre-training objective encourages the model to
represent different languages in the shared space, so that we can conduct
zero-shot cross-lingual transfer. After the pre-training procedure, we use
monolingual data to fine-tune the pre-trained model on downstream NLG tasks.
Then the sequence-to-sequence model trained in a single language can be
directly evaluated beyond that language (i.e., accepting multi-lingual input
and producing multi-lingual output). Experimental results on question
generation and abstractive summarization show that our model outperforms the
machine-translation-based pipeline methods for zero-shot cross-lingual
generation. Moreover, cross-lingual transfer improves NLG performance of
low-resource languages by leveraging rich-resource language data. Our
implementation and data are available at https://github.com/CZWin32768/xnlg.