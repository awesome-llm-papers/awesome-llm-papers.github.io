---
layout: publication
title: A Stack-propagation Framework With Token-level Intent Detection For Spoken
  Language Understanding
authors: Libo Qin, Wanxiang Che, Yangming Li, Haoyang Wen, Ting Liu
conference: Proceedings of the 2019 Conference on Empirical Methods in Natural Language
  Processing and the 9th International Joint Conference on Natural Language Processing
  (EMNLP-IJCNLP)
year: 2019
bibkey: qin2019stack
citations: 291
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1909.02188'}]
tags: ["EMNLP", "Model Architecture"]
short_authors: Qin et al.
---
Intent detection and slot filling are two main tasks for building a spoken
language understanding (SLU) system. The two tasks are closely tied and the
slots often highly depend on the intent. In this paper, we propose a novel
framework for SLU to better incorporate the intent information, which further
guides the slot filling. In our framework, we adopt a joint model with
Stack-Propagation which can directly use the intent information as input for
slot filling, thus to capture the intent semantic knowledge. In addition, to
further alleviate the error propagation, we perform the token-level intent
detection for the Stack-Propagation framework. Experiments on two publicly
datasets show that our model achieves the state-of-the-art performance and
outperforms other previous methods by a large margin. Finally, we use the
Bidirectional Encoder Representation from Transformer (BERT) model in our
framework, which further boost our performance in SLU task.