---
layout: publication
title: 'Americasnli: Evaluating Zero-shot Natural Language Understanding Of Pretrained
  Multilingual Models In Truly Low-resource Languages'
authors: "Abteen Ebrahimi, Manuel Mager, Arturo Oncevay, Vishrav Chaudhary, Luis Chiruzzo,\
  \ Angela Fan, John Ortega, Ricardo Ramos, Annette Rios, Ivan Meza-ruiz, Gustavo\
  \ A. Gim\xE9nez-lugo, Elisabeth Mager, Graham Neubig, Alexis Palmer, Rolando Coto-solano,\
  \ Ngoc Thang Vu, Katharina Kann"
conference: 'Proceedings of the 60th Annual Meeting of the Association for Computational
  Linguistics (Volume 1: Long Papers)'
year: 2022
bibkey: ebrahimi2021americasnli
citations: 62
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2104.08726'}]
tags: ["Datasets"]
short_authors: Ebrahimi et al.
---
Pretrained multilingual models are able to perform cross-lingual transfer in
a zero-shot setting, even for languages unseen during pretraining. However,
prior work evaluating performance on unseen languages has largely been limited
to low-level, syntactic tasks, and it remains unclear if zero-shot learning of
high-level, semantic tasks is possible for unseen languages. To explore this
question, we present AmericasNLI, an extension of XNLI (Conneau et al., 2018)
to 10 indigenous languages of the Americas. We conduct experiments with XLM-R,
testing multiple zero-shot and translation-based approaches. Additionally, we
explore model adaptation via continued pretraining and provide an analysis of
the dataset by considering hypothesis-only models. We find that XLM-R's
zero-shot performance is poor for all 10 languages, with an average performance
of 38.62%. Continued pretraining offers improvements, with an average accuracy
of 44.05%. Surprisingly, training on poorly translated data by far outperforms
all other methods with an accuracy of 48.72%.