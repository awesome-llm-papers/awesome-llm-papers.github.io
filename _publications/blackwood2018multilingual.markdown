---
layout: publication
title: Multilingual Neural Machine Translation With Task-specific Attention
authors: Blackwood Graeme, Ballesteros Miguel, Ward Todd
conference: Arxiv
year: 2018
bibkey: blackwood2018multilingual
citations: 51
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1806.03280'}]
tags: [Model Architecture, Reinforcement Learning, Datasets, Attention Mechanism]
---
Multilingual machine translation addresses the task of translating between
multiple source and target languages. We propose task-specific attention
models, a simple but effective technique for improving the quality of
sequence-to-sequence neural multilingual translation. Our approach seeks to
retain as much of the parameter sharing generalization of NMT models as
possible, while still allowing for language-specific specialization of the
attention model to a particular language-pair or task. Our experiments on four
languages of the Europarl corpus show that using a target-specific model of
attention provides consistent gains in translation quality for all possible
translation directions, compared to a model in which all parameters are shared.
We observe improved translation quality even in the (extreme) low-resource
zero-shot translation directions for which the model never saw explicitly
paired parallel data.