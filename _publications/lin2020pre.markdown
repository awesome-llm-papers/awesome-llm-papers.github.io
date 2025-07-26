---
layout: publication
title: Pre-training Multilingual Neural Machine Translation By Leveraging Alignment
  Information
authors: Zehui Lin, Xiao Pan, Mingxuan Wang, Xipeng Qiu, Jiangtao Feng, Hao Zhou,
  Lei Li
conference: Proceedings of the 2020 Conference on Empirical Methods in Natural Language
  Processing (EMNLP)
year: 2020
bibkey: lin2020pre
citations: 81
additional_links: [{name: Code, url: 'https://github.com/linzehui/mRASP'}, {name: Paper,
    url: 'https://arxiv.org/abs/2010.03142'}]
tags: ["EMNLP", "Training Techniques"]
short_authors: Lin et al.
---
We investigate the following question for machine translation (MT): can we
develop a single universal MT model to serve as the common seed and obtain
derivative and improved models on arbitrary language pairs? We propose mRASP,
an approach to pre-train a universal multilingual neural machine translation
model. Our key idea in mRASP is its novel technique of random aligned
substitution, which brings words and phrases with similar meanings across
multiple languages closer in the representation space. We pre-train a mRASP
model on 32 language pairs jointly with only public datasets. The model is then
fine-tuned on downstream language pairs to obtain specialized MT models. We
carry out extensive experiments on 42 translation directions across a diverse
settings, including low, medium, rich resource, and as well as transferring to
exotic language pairs. Experimental results demonstrate that mRASP achieves
significant performance improvement compared to directly training on those
target pairs. It is the first time to verify that multiple low-resource
language pairs can be utilized to improve rich resource MT. Surprisingly, mRASP
is even able to improve the translation quality on exotic languages that never
occur in the pre-training corpus. Code, data, and pre-trained models are
available at https://github.com/linzehui/mRASP.